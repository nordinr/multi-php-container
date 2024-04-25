# multi-php-container
Serve multiple php version in one deployment

                                   **# PHPVersDock 🐳 🐳**

PHPVersDock is a Docker-based solution designed to help you manage multiple PHP versions effortlessly within Docker containers. This repository simplifies the setup process for developers who need to work with different PHP versions across various projects.

Features
1- Multiple PHP Versions: Easily switch between different PHP versions for your projects.
2- Simple Configuration: Streamlined setup process using Docker for a hassle-free experience.
3- Virtual Host Configuration: Create and manage virtual hosts locally for your projects.

Getting Started
Prerequisites

Make sure you have Docker installed on your system.

Installation:
1- Clone this repository to your local machine:
git clone https://github.com/nordinr/multi-php-container

2-Customize PHP versions and configurations as needed in the docker-compose.yml file.
    Run the following command to start the Docker containers:
<!-- sudo for linux users -->
    sudo docker-compose up -d 
3-Setting Up Virtual Hosts
To create a virtual host for your project:
```
    Open the hosts file on your local machine:
    Windows: C:\Windows\System32\drivers\etc\hosts
    Mac/Linux: /etc/hosts
        Add an entry for your project:
        127.0.0.1   your-project.local
```
Configure the virtual host in the Docker containers
4-Restart the Docker containers:
    Now, you can access your project in the browser using http://your-project.local 😀😀

Contributing
Contributions are welcome! If you find any issues or want to improve the project, feel free to open a pull request or create an issue.

