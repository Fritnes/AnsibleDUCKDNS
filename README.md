Role "Duckdns"
=========

https://www.duckdns.org/

Role Variables
--------------

duckdns_domains:
    - { domain: example, token: example-token}

Example Playbook
----------------

    - hosts: servers
      roles:
	- { role: AnsibleDUCKDNS, when: ansible_system == 'Linux' }

Author Information
------------------

fritnes
https://github.com/Fritnes/AnsiblePI-HOLE
