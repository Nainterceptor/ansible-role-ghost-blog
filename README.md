Nainterceptor.gogs
====================

Role used to install Ghost blog on CentOS with yum

Requirements
------------

CentOS Supported

Role Variables
--------------

Example Playbook
----------------

    - hosts: servers
      vars:
          mysql_database: ghost_blog
          mysql_username: root
          mysql_password: ""
          mysql_hostname: localhost
          ghost_disqus_shortname: shortname
          ghost_copyright_name: "My Copyright"
          ghost_url_github: "https://github.com/"
          ghost_url_linkedin: "https://www.linkedin.com/"
          ghost_url_twitter: "https://twitter.com/"
      roles:
         - { role: Nainterceptor.ghost-blog }

License
-------

CC-BY
