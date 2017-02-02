Nginx Django proxy
=========

Nginx uwsgi proxy for Django app combined with static files serving

Role Variables
--------------

- `domains` - list of domains
- `http_port` - default:80
- `ssl` - provide SSL connection channel (default: False)
- `http_redirect` - if both above variable and this is set - provide :80->https redirect
- `cert` - public SSL certificate path 
- `cert_key` - private SSL certificate path
- `static_root` - Django's `STATIC_ROOT` if unset dont serve static files
- `media_root` - Django's `MEDIA_ROOT`



Dependencies
------------

- `xkoralsky.nginx_base`

Example Playbook
----------------

License
-------

BSD
