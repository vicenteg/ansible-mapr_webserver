mapr_webserver
=========

Install mapr-webserver

Requirements
------------

Role Variables
--------------

```
proxy_env:
  http_proxy: http://1.2.3.4:3128
  https_proxy: http://1.2.3.4:3128
```

Dependencies
------------


Example Playbook
----------------

```
- hosts: webserver
  roles:
    - webserver
```


License
-------

MIT

Author Information
------------------

vgonzalez@mapr.com