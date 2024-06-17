Development Environment Setup on Ubuntu
Introduction
Setting up a development environment is crucial for effective software development. This report outlines the comprehensive steps taken to establish a robust development environment on Ubuntu, integrating tools such as Visual Studio Code (VS Code), Git, Python, and MySQL. Each step is detailed to ensure reproducibility and understanding of the configuration process.
Operating System Installation
Ubuntu is a preferred choice for developers due to its stability and extensive support for various development tools. For this setup, Ubuntu 20.04 LTS was used, which offers a reliable and up-to-date environment for development.
Visual Studio Code Installation
Visual Studio Code (VS Code) is a powerful and popular Integrated Development Environment (IDE) that supports a wide range of programming languages and extensions. The installation process for VS Code on Ubuntu involves several steps:
Update System Packages: First, ensure all system packages are up-to-date.
sudo apt update

Install VS Code: Finally, update your package lists and install VS Code.
sudo apt update
sudo apt install code

Git Installation and Configuration
Git is an essential version control system for managing source code. It was installed and configured as follows:
Install Git: Download and install Git using the package manager.
sudo apt install git

Configure Git: Set up your Git username and email, which will be used for your commits.
git config --global user.name Hussein Sadick
git config --global user.email "ahusesadick@gmail.com"

GitHub Account Setup: If not already done, a GitHub account was created at GitHub. This allows for hosting repositories and collaboration.
Initialize a Git Repository: A new project directory was created, and a Git repository was initialized within it.
mkdir my_project
cd my_project
git init

Python Installation
Python is a versatile programming language widely used in development. Here’s how Python was set up:
Install Python: Python and its package manager pip were installed.
sudo apt install python3 python3-pip
Verify Installation: To ensure Python and pip were installed correctly, their versions were checked.
python3 --version
pip3 –version
MySQL Installation and Configuration
MySQL is a powerful relational database management system (RDBMS). The setup process included:
Install MySQL Server: MySQL server was installed using the package manager.
sudo apt update
sudo apt install mysql-server
Installing Essential VS Code Extensions
VS Code’s functionality was extended with essential plugins for Python development, Git integration, and MySQL support:
Python Extension: This extension provides Python language support, including IntelliSense and debugging.
GitLens Extension: Enhances Git capabilities within VS Code, providing rich insights into the history and evolution of code.
MySQL Extension: Adds support for MySQL database management directly within VS Code.

Development Environment Setup 
Operating System - Ubuntu 20.04 LTS
Text Editor and IDE - Visual Studio Code
Version Control System - Git and GitHub
Programming Languages - Python 3.8 
Database - MySQL 8.0
VS Code Extensions - Python - GitLens - MySQL 
Setup Steps 1. Install the OS 
2. Install VS Code
3. Install and Configure Git
4. Install Python and pip
5. Install MySQL
6. Install VS Code Extensions
Challenges and Solutions :
Challenge MySQL did not start after installation.
Solution: Resolved by configuring the MySQL


