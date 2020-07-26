# Vagrant Orchestrated Containers

A script that will automate a Vagrant orchestrated five containers with ssh access from Controller container. The two containers out of five are frontend systems with Apache running on port 80 and remaining two are backend containers running Mariadb.

## Instructions

This script is written to run only in Debian environment. Running it in any other environment would result in error.

### Prerequisites

1.	Host running Debian 10 OS.
2.	Virtualization enabled in BIOS setting

### Note

1.	Download the script to automate the process of container creation.
2.	Script will automatically create a folder and run the required installation in necessary folders.
3.	5 Containers are created namely frontend-1, frontend-2, backend-1, backend-2 and controller which can be orchestrated through Vagrant.
4.	Frontend -1 and frontend -2 have http service running on port 80 and display “Hello World”
5.	Backend-1 and backend-2 are running MariaDb and root password is fred. There is one more user configured with username foo and password far

## Built With

* [Kali Linux]( https://www.kali.org/) - The Linux Operating System
* [Vagrant]( https://www.vagrantup.com/) – The tool for orchestration of Containers
* [Virtual Box]( https://www.virtualbox.org/) - Used to host the containers

## Authors

Pratik More

## Acknowledgments

1. Docker and Vagrant docs on container creation/ deployment materials were referenced.
2. You tube was of great help from beginner’s perspective.
