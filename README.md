Role Name
=========

Sets up Filebeat Collector (no config, useful for graylog sidecar)

Role Variables
--------------

Check defaults/main for variables that can be adjusted.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    ---
    
    - name: Setup Filebeat Collector
      hosts: all
      become: yes
      
      roles:
        - role: silviuvulcan.filebeat
    

License
-------

(BSD, MIT)


Author Information
------------------

https://github.com/silviuvulcan/ansible-role-filebeat/
