---
title: Landmark Web App
date: 11-01-2022 08:22:49 +0100
category: [XAI Entity Matching Project]
subcategories: [frontend,backend]
tags: [landmark, explanation tool, entity matching, mit license]
---

# Landmark Web App

The repository is part of the _XAI Entity Matching Project_. This frontend and backend enables users to interact with the [Landmark](https://github.com/softlab-unimore/landmark), an explanation tool for Entity Matching.

More information about the [Landmark](https://github.com/softlab-unimore/landmark) can be found in the corresponding repository.

The Landmark frontend is supplied under MIT License. You can use and extend the frontend to interact with the Landmark platform.

## Prerequisites

### Install Node JS
Refer to https://nodejs.org/en/ to install nodejs
### Install Django

```bash
python -m pip install django django-cors-headers django-cleanup djangorestframework
```

## Cloning and Running the Application in local

Clone this project into local.


And clone [Landmark](https://github.com/softlab-unimore/landmark) 
repo in the backend folder. (LandmarkApp/backend/)

e.g.:
```bash
cd LandmarkApp/backend/
git clone https://github.com/softlab-unimore/landmark.git
cd ..
```

Intall the packages specified in the requirements.txt file.
```
pip install -r requirements.txt
```

#### Backend server
Go to the backend folder and initialize the django server database

```bash
cd backend
.\manage.py makemigrations
.\manage.py migrate
```

and launch the server

```bash
 .\manage.py runserver
```

django Runs on **localhost:8000**

#### Frontend server
Install all the npm packages.
In another terminal go into the frontend folder and type the following command to install all npm packages

```bash
cd frontend
npm install
```

In order to run the application type the following command

```bash
npm start
```

The Application Runs on **localhost:3000**




#### Use the app
open the browser at [http://localhost:3000/](http://localhost:3000/) 