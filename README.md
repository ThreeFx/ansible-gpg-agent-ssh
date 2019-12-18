gpg-agent-ssh
=========

Configures gpg-agent to act as ssh agent.

Requirements
------------

None.

Role Variables
--------------

| Variable Name | Default Value | Description |
--------------- |---------------|--------------
`gpg_agent_ssh_keygrip` | "" | required, keygrip for the SSH key


Dependencies
------------

My [zsh role](https://github.com/ThreeFx/zsh) for drop-in zsh configuration.

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: gpg-agent-ssh, gpg_agent_ssh_keygrip: abcdef1234567890 }

License
-------

BSD

Author Information
------------------

Find me on [GitHub](https://github.com/ThreeFx).
