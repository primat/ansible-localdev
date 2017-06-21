# ansible-localdev
Set of Ansible roles and playbooks used to setup a development environment on Ubuntu

There's currently only a single playbook: setup.localdev.yml. This playbook contains all the roles to setup the development environment on Ubuntu 16.04 LTS.
Specifically, it has roles for installing and configuring:

  * common  : Installs git
  * docker_ubuntu : Docker
  * gogland : Installs the Gogland IDE
  * golang : Installs the Go language
  * intellij : Installs the Intellij IDE
  * mongodb : Installs ans secures mongo
  * nodejs : Installs node.js
  * pycharm : Installs the Pycharm IDE
  * vagrant : Installs Vagrant
  * virtualbox : Partially installs Virtualbox
  * webstorm : Installs the Webstorm IDE
  * vscode : Installs Visual Studio Code
