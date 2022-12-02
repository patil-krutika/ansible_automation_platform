---
- name: installing webserver
  hosts: localhost
  tasks:
    - name: Install latest version
      dnf:
        name: httpd
        state: latest
