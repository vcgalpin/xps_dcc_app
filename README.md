There are two ways in which to run this software.

### Install it locally

To start the XPS DCC temporal DB application, type the following on the command line
```
linx --config=config.0.9.8 src/startXPS.links
```
To run `linx`, various packages such as opam and PostgreSQL must be installed, and for the web app to run, appropriate databases need to be available. More information about this will be provided in INSTALL.md

### Work with a Docker image

Two Docker images are available:

* Provides a demo version of the web application: https://github.com/vcgalpin/tempdb_simple_web_docker
* Provides the web app together with a bash shell: https://github.com/vcgalpin/tempdb_web_shell_docker

The Docker images include all required packages. When a container is run from an image, the relevant database tables are created.

