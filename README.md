# backend-task
## Project Goal
To make an API to fetch latest videos sorted in reverse chronological order of their publishing date-time from YouTube for a given tag/search query in a paginated response.

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

## ScreenShots
![Image of Dashboard](https://user-images.githubusercontent.com/52597536/112284534-5b11f100-8caf-11eb-8c2d-04ce168f0626.png)
