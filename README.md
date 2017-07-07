Install from maven
==================

Installs files from maven on given directory and tests it's integrity with a md5sum.

Role Variables
--------------

* `file_url`: The url of the file to download.
* `deploy_dir`: Where to deploy the file.


Example Playbook
----------------

```yaml
    - hosts: servers
      roles:
         - { role: install-from-maven, file_url: https://repo1.maven.org/maven2/org/blablabla.war }
```
License
-------

GPL3
