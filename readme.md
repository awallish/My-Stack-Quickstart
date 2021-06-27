# Quickstart For My Stack
Consisting of:
- Outseta
- Flask
- Flask-Login
- Tailwind CSS
- 

## Outseta + Flask + Flask-Login Quickstart

This repo is for quickly getting started using [Outseta](https://outseta.com) with [Flask-Login](https://flask-login.readthedocs.io/en/latest/)

To use it, just paste your Outseta URL and keys into constants.py

### For authenticated pages
Include outseta_profile.html and pass the access_token stored in the Flask login user object to the template

See */hidden* for an example

### For unauthenticated pages
Include outseta_auth.html

## Shuffle.dev setup
- It's difficult to sync, so build out as much of the template as possible before exporting
- Export and download project in a different temporarily folder
- npm install
- NODE_ENV=production npm run build
- Copy files to templates and static in the project folder
- Update paths for loading static files
- Install shuffle vscode extension and use it to update files

## To do:
- Set up GitHub actions
- Setup logging
- Set up environment variables