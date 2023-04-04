#

Use `git submodule update --init --recursive` to pull submodule repositories.

## Installation

### Docker Installation


### PHP Container
In this phase, we will install PHP itself.  
We will be using the FPM version which requires a reverse proxy setup.  

**Note:** This container (`8.1.17-fpm-alpine`) includes Apache configured.

It is important with the FPM version to not expose a port using the --publish (-p) flag.

1. Pull the image locally: `docker pull php:8.1.17-fpm-alpine`
2. 


