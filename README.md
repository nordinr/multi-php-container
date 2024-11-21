# Getting started
Serve multiple php version in a single docker stack.

This is a Docker-based solution designed to help you manage multiple PHP versions effortlessly within Docker containers. This repository simplifies the setup process for developers who need to work with different PHP versions across various projects.

Getting Started
Prerequisites

Make sure you have Docker installed on your system.

Installation:
1. Clone this repository to your local machine:
`git clone https://github.com/nordinr/multi-php-container.git`

2. Customize PHP versions and configurations as needed in the docker-compose.yml file.
    Run the following command to start the Docker containers:
<!-- sudo for linux users -->
    sudo docker-compose up -d 
3. Choose you primary php version and head your reverse proxy to the stack the add secondary php version by using custom locations.

Example:
```console
http://domain.com - primary php version
http://domain.com/app01 - secondary php version

```
You can add as many versions you like by adding the folders and deployment manifest in docker-compose file.

Thanks.


