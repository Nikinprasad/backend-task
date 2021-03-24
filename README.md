# backend-task
## Project Goal
To make an API to fetch latest videos sorted in reverse chronological order of their publishing date-time from YouTube for a given tag/search query in a paginated response.

### This project is fully based on Django Rest Framework and Youtube Data API v3. Crontab is used for await for a time of 10 sec.

## Create and start Virtural Environment 
`sudo apt-get install python3-venv`

`python3 -m venv env #env is the environment name (choose any of your own)`

`cd env`

`. bin/activate`

## Requirements
requirements.txt is added in the folder

`pip install -r requirements.txt`

Django and Django rest framework with all the necessary packages will be installed.

## Changing YouTube API link
Inside `settings.py`, YouTube Data API key is located at line 136

`GOOGLE_API_KEYS = ['Your_Key_1','Your_Key_2']`

## Start project
From the root folder where manage.py is located,

`python manage.py runserver`

#### Simply open `http://127.0.0.1:8000/` in your browser to view the page.
## ScreenShots
### Dashboard
![Image of Dashboard](https://user-images.githubusercontent.com/52597536/112284534-5b11f100-8caf-11eb-8c2d-04ce168f0626.png)

### Simple filter from Django Rest Framework
![Image of Filter](https://user-images.githubusercontent.com/52597536/112284773-990f1500-8caf-11eb-8125-fcd70f2b23eb.png)
 
