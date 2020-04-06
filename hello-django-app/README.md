# Helloworld for Django Web Application

This repo stores a Django web sample

## Folder structure : 

Your project folder has the following within it:

- **manage.py**: The Django command-line administrative utility for the project. You run administrative commands for the project using python manage.py <command> [options].

A subfolder named web_project, which contains the following files:

- **__init__.py**: an empty file that tells Python that this folder is a Python package.
- **wsgi.py**: an entry point for WSGI-compatible web servers to serve your project. You typically leave this file as-is as it provides the hooks for production web servers.
- **settings.py**: contains settings for Django project, which you modify in the course of developing a web app.
- **urls.py**: contains a table of contents for the Django project, which you also modify in the course of development.


## Getting started

To start a new project : 

    django-admin startproject web_project .

## Up & Runining 

Use the following command when you're under the folder and has manage.py file :
    
     python3 manage.py runserver


## Ref : 

Here's a doc will help you get started : 

 https://docs.microsoft.com/en-us/windows/python/web-frameworks