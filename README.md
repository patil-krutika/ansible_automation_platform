---
- name: installing webserver
  hosts: localhost
  tasks:
    - nmae: Install latest version
      yum:
        name: httpd
        state: latest
