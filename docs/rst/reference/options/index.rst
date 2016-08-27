
Optional Arguments
==================

:usage: ansible-container
    [-h] [--debug] [--engine ENGINE_NAME]
    [--project BASE_PATH] [--var-file VAR_FILE]
    {init,version,run,help,push,shipit,stop,restart,build}
                         ...

Build, orchestrate, run, and ship Docker containers with Ansible playbooks

.. option:: -h, --help

Show help message and exit.

.. option:: --debug

Enable debug output.

.. option:: --engine ENGINE_NAME

Select your container engine and orchestrator. Defaults to *docker*.

.. option:: --project BASE_PATH, -p BASE_PATH

Specify a path to your project. Defaults to curren working directory.

.. option:: --var-file

New in version 0.2.0.

Path to a YAML or JSON formatted file providing variables for Jinja2 template rendering in container.yml. Provide an absolute
file path, or a path relative to the *project BASE_PATH* or relative to *project BASE_PATH/ansible*. If the file
extension is one of 'yml' or 'yaml', the file will be parsed as Yaml. Otherwise, it is parsed as JSON.
