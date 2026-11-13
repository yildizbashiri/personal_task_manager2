# Personal Task Manager2
![Static Badge](https://img.shields.io/badge/python-blue?logo=python&logoColor=white)

A simple task manager built wit Python for learning git -github

## Features
- add multiple tasks
- save tasks 
- load saved tasks
- admin mode 
- set task priority
  

## Task Priority
each task can have one of these priority levels:
- low
- medium
- high

## Requirements
- Python 
- Python-dotenv

## Project strcture
```text
Personal Task Manager2/
│   .env.example
│   .gitignore
│   main.py
│   README.md
│   requirements.txt
│   tasks.py
│
├───images/
│       aaa.png
│       Animation.gif
│

```

## Installation
Install the required packages
```bash
python -m pip install -r requirements.txt
```
## Enviroment Setup
create a `.env` file in the project folder

Use `.env.example` as a templat

Add your admin password

```env
admin_pass=your_password_here
```
replace `your_password_here` with your own admin password


## Run the Program 
run the main file :
```bash
python main.py
```

## Screenshot
![Screenshot](images\Screenshot.png)

## Demo
![Animation.gif](images\Animation.gif)