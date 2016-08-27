Roadmap for release 0.2.0
=========================

**Target delivery: early October 2016**

**Status: Open for comment**

- **Build Cache** (Jag @j00bar)
    One of the niceties of the Dockerfile is that the Docker engine re-uses cached layers to accelerate rebuilds. We can do something similar using a custom Ansible 
    execution strategy.
  - Build and test new execution strategy
  - Add CLI option to enable the new strategy in the build command

- Refactor the shipit command (House @chouseknecht)
  - Help the OpenShift team complete the new OpenShift/K8s modules for Ansible
  - Submit new modules to Ansible core
  - Refactor Shipit command to use the new modules  

- Help users navigate SELinux (Dusty @dustymabe)
  - Finish issue `#168 <https://github.com/ansible/ansible-container/issues/168>`_ 

- Naming and tagging images (?)
  - We need a mechanism that allows the user to set image names and tag images into repositories. Currently image names are set exclsuively
    by ansible-container.
  - Tracked on issue `#125 <https://github.com/ansible/ansible-container/issues/125`_.

- Support detached run, stop, and restart (Charlie @cdrage) 
  - Add --detached option to the *run* command.
  - Add *stop* and *restart* commands.

- Support template rendering in container.yml (House @chouseknecht)
  - Add jinja2 template rendering in the config object
  - Add CLI option for specifying a var file
  - Add examples and docs
  - Tracked on issue `#120 <https://github.com/ansible/ansible-container/issues/120>`_

- Create a reference guide for container.yml (House @chouseknecht)
  - Provide a reference guide for container.yml
  - Make it easy for users to know what compose directives are supported and how they are interpreted/handled by Ansible Container.
  - Provide a list of unsupported directives
  - Include examples

