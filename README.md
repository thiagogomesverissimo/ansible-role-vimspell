vimspell
=========

Download languages (spell) for vim

Requirements
------------

vim installed

Role Variables
--------------

    vimspell_home: "/root"
    vimspell_user: root
    vimspell_languages:
      - pt
      - es
      - en

Example Playbook
----------------

    - hosts: servers
      roles:
         - uspdev.vimspell

License
-------

BSD

Author Information
------------------

@thiagogomesverissimo
