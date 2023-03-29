# Grammar Error Correction using Transformer

## Table of Contents
   * [Project Overview](#project-overview)
   * [Getting Started](#getting-started)
   * [Installation](#installation)
   * [Run Server](#run-server)
   * [Features](#features)

## Project Overview

This project is built to correct grammatical errors

## Getting Started

In this project you need:
pip
pipenv
    
 * Install pip
   open the terminal and make sure you have python3 installed

   for Linux based
    
   ```
   sudo dnf install python-pip
   ```
   use apt for ubuntu-based distro, dnf for fedora based, pacman for arch-based and so on...
   
   or
   ```
   python3 get-pip.py
   ```
   verify the pip installation using:
   ```
   pip --version
   ```

* Install pipenv

   ```
   pip install pipenv
   ```

## Installation
   To install the required items for the project:

   For machine wide installation
   ```
   pip install -r requirements.txt
   ```
    
   Create a new virtual environment using 'pipenv':
   ```
   pipenv shell
   ```

   Install the required packages from 'requirements.txt'
   ```
   pipenv install -r requirements.txt
   ```

## Run server
   To run the django server:
   Make sure the virtual environment is active

   ```
   pipenv shell
   ```
   Then
   ```
   python manage.py runserver
   ```

   the default server is 127.0.0.1:8000
   you can change the port address by adding a 4 digit number at the end of runserver command, like
   ```
   python manage.py runserver 9000
   ```

   Now you can change the django file to your liking. Always make sure the virtual environment is activated using "pipenv shell"
## Features
    ok
    
Contact me at my socials if any problem aries.
