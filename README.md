RabbitMQ server
=========

Install RabbitMQ server with example exchange, queues and bindings.

Requirements
------------



Role Variables
--------------

See the vars/main.yml

Dependencies
------------

* geerlingguy.pip

Example Playbook
----------------

Include in playbook:

    - hosts: servers
      roles:
         - { role: jslmorrison.rabbitmq }

License
-------

BSD

Author Information
------------------

https://github.com/jslmorrison/
