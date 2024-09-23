# Flask App Setup Guide

# Project Overview

A Flask app is a web application built using Flask, a lightweight web framework for Python. Flask is designed to be simple, flexible, and easy to scale, making it a popular choice for building web applications, APIs, and microservices.

# Prerequisites

Before you begin, ensure you have the following installed on your Linux system:


## How to Set Up and Run the Flask Application

* Clone the repository

```bash
git clone https://github.com/rsingh0706/Flask-Application.git
```

## Linux Essentials

Update your package list and install need Python and pip

1. install pythan 3.10 on your system, follow these steps depending on your operating system.

* Update the package list

```bash
sudo apt update
```

* Install required dependencies

```bash 
sudo apt install software-properties-common
```
* Add the deadsnakes PPA repository

```bash
sudo add-apt-repository ppa:deadsnakes/ppa
```
* Install Python 3.10

```bash
sudo apt install python3.10
```
* Verify the installation

```bash
python3.10 --version  (Python 3.10.15)
```
2. install pip (the package manager for Python) on Ubuntu, follow these steps

* Update the package list

```bash
sudo apt update
```
* Install pip for Python 3
```bash
sudo apt install python3-pip
```
* Verify the installation 

```bash
pip3 --version  (pip 20.0.2 from /usr/lib/python3/dist-packages/pip (python 3.8) )
```

3. To install Flask

* Update the System

```bash
sudo apt update
```
* Install Flask

```bash
pip install Flask
```

### Navigate into the project directory

```bash
cd Flask-Application 
```
* Start the application

```bash
flask run --host=0.0.0.0
```

By default, the app will be available at http://localhost:5000
















