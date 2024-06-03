Template Role
=========

`pre_tasks` role for Ansible.

Requirements
------------

Generated initially via `galaxy init ./roles/pre-tasks` command.

Role Variables
--------------

There aren't any variables declared as they're all setup in the `tasks/main.yml` file.

Dependencies
------------

* `ansible`
* `ansible-lint`
* `ansible.cfg`
* `hosts` file

Example Playbook
----------------

* `playbook.yml`

    ```yaml
    ---
    - name: Call pre-tasks role
      hosts: all
      become: false
      roles:
        - pre-tasks
    ```

* Usage

    ```bash
    # all hosts
    ansible-playbook playbook.yml

    # only dev group
    ansible-playbook playbook.yml --limit dev
    ```

License
-------

Unlicense

<!-- Author Information
------------------ -->
