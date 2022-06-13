# Pixel Bootstrap PRO Flask/Jinja

Seed project generated by AppSeed in **Flask/Jinja** Framework on top of **Pixel PRO** design. `Pixel` is a premium `Bootstrap 5` based UI Kit featuring over 200 fully coded UI elements and example pages that will help you prototype and build a website for your next project.

- 👉 [Flask Pixel PRO](https://appseed.us/product/pixel-bootstrap-pro/flask/) - product page
- 👉 [Flask Pixel PRO](https://flask-pixel-pro.appseed-srv1.com/) - LIVE Deployment
- 👉 [Complete documentation](https://docs.appseed.us/boilerplate-code/boilerplate-jinja) - `Learn how to use and update the product`
  - ✅ [Set up the environment](https://docs.appseed.us/boilerplate-code/boilerplate-jinja#environment)
  - ✅ [Start in Docker](https://docs.appseed.us/boilerplate-code/boilerplate-jinja#start-the-app-in-docker)
  - ✅ [Codebase structure](https://docs.appseed.us/boilerplate-code/boilerplate-jinja#codebase-structure)
  - ✅ [UI Assets and Templates](https://docs.appseed.us/boilerplate-code/boilerplate-jinja#ui-assets-and-templates)
  
<br />

> Built with [Pixel Pro Generator](https://appseed.us/generator/pixel-bootstrap-pro/)

- Timestamp: `2022-06-13 18:40`
- Build ID: `9a0c6b85-6b1c-4f1e-8eaa-030f12d0f549`
- **Free [Support](https://appseed.us/support/)** (registered users) via `Email` and `Discord`

<br />

> Features

- `Up-to-date dependencies`
- Render Engine: Flask / [Jinja2](https://jinja.palletsprojects.com/)

<br />

![Pixel Bootstrap PRO - Full-Stack Starter generated by AppSeed](https://user-images.githubusercontent.com/51070104/168760719-f0e45406-2b2a-43e0-badf-fa953edb62b8.png)

<br />

## ✨ Start the app in Docker

> **Step 1** - Download the [code](https://appseed.us/product/pixel-bootstrap-pro/flask/) and unzip the sources (requires a `purchase`). 

```bash
$ # Get the code
$ unzip flask-pixel-bootstrap-pro.zip
$ cd flask-pixel-bootstrap-pro
```

<br />

> **Step 2** - Edit `.env` and set `DEBUG=True`. This will activate the `SQLite` persistance. 

```txt
DEBUG=True
```

<br />

> **Step 3** - Start the APP in `Docker`

```bash
$ docker-compose up --build 
```

Visit `http://localhost:5085` in your browser. The app should be up & running.

<br />

## ✨ How to use it

> - Download the [code](https://appseed.us/product/pixel-bootstrap-pro/flask/) and unzip the sources (requires a `purchase`). 

```bash
$ # Get the code
$ unzip flask-pixel-bootstrap-pro.zip
$ cd flask-pixel-bootstrap-pro
```

<br />

### 👉 Set Up for `Unix`, `MacOS` 

> Install modules via `VENV`  

```bash
$ virtualenv env
$ source env/bin/activate
$ pip3 install -r requirements.txt
```

<br />

> Set Up Flask Environment

```bash
$ export FLASK_APP=run.py
$ export FLASK_ENV=development
```

<br />

> Start the app

```bash
$ flask run
```

At this point, the app runs at `http://127.0.0.1:5000/`. 

<br />

### 👉 Set Up for `Windows` 

> Install modules via `VENV` (windows) 

```
$ virtualenv env
$ .\env\Scripts\activate
$ pip3 install -r requirements.txt
```

<br />

> Set Up Flask Environment

```bash
$ # CMD 
$ set FLASK_APP=run.py
$ set FLASK_ENV=development
$
$ # Powershell
$ $env:FLASK_APP = ".\run.py"
$ $env:FLASK_ENV = "development"
```

<br />

> Start the app

```bash
$ flask run
```

At this point, the app runs at `http://127.0.0.1:5000/`. 

<br />

## ✨ Code-base structure

The project has a simple, intuitive structure presented bellow:

```bash
< PROJECT ROOT >
   |
   |-- apps/__init__.py
   |-- apps/
   |    |-- static/
   |    |    |-- <css, JS, images>         # CSS files, Javascripts files
   |    |
   |    |-- templates/
   |         |
   |         |-- includes/                 # Page chunks, components
   |         |    |
   |         |    |-- navigation.html      # Top bar
   |         |    |-- sidebar.html         # Left sidebar
   |         |    |-- scripts.html         # JS scripts common to all pages
   |         |    |-- footer.html          # The common footer
   |         |
   |         |-- layouts/                  # App Layouts (the master pages)
   |         |    |
   |         |    |-- base.html            # Used by common pages like index, UI
   |         |    |-- base-fullscreen.html # Used by auth pages (login, register)
   |         |
   |      index.html                       # The default page
   |      page-404.html                    # Error 404 page (page not found)
   |      page-500.html                    # Error 500 page (server error)
   |         *.html                        # All other pages provided by the UI Kit
   |
   |-- requirements.txt
   |
   |-- run.py
   |
   |-- ************************************************************************
```

<br />



---
Pixel Bootstrap PRO Flask/Jinja - Seed Project generated by **[AppSeed Generator](https://appseed.us/generator/)**.
