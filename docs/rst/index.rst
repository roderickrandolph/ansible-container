Welcome to ansible-container!
=============================
Ansible Container is the ultimate workflow for container development, testing, and deployment.

Ansible Container enables you to build Docker images and orchestrate containers using only Ansible playbooks. Describe
your application in a Docker Compose-like format and, rather than using a Dockerfile, provide a playbook with tasks for
building images. Ansible Container will take it from there.

With Ansible Container, you are no longer limited by Dockerfile. You can now apply the power of Ansible to the image build
process. Use templates, copy files, drop in encrypted data, handle errors, add conditionals, and more. Everything
Ansible brings to orchestrating your infrastructure can now be applied to the image build process.

But Ansible Container does not stop there. Use Ansible Container to run the application, and push images to private and
public registries. When you are ready to deploy to the cloud, use it to generate an Ansible role that automates the
deployment.

Releases
````````

The current release available at `PyPi<http://pypi.org>`_ is `0.1.0<https://pypi.org/search/?q=ansible-container>`_. The 
next release is 0.2.0. Version 0.2.0 is in pre-release status and only available by `running from source</ansible-container/installation.html#running-from-source>`_ 
using the *develop* branch. 


.. toctree::
   :maxdepth: 2

   installation
   tour
   deploy_kubernetes
   example
   registry_auth
   reference/index
   community/index

