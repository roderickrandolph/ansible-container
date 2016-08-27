
Optional Arguments
==================

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

Path to a YAML or JSON formatted file providing variables for Jinja2 templating in container.yml. Provide an absolute
file path, or a path relative to the *project BASE_PATH* or relative to *project BASE_PATH/ansible*. If the file
extension is one of 'yml' or 'yaml', the file will be parsed as Yaml. Otherwise, it is parsed as JSON.
