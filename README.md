<h1 align="center"> PlannedPay - Bank Application</h1>
<p align="center">
  <img src="https://img.shields.io/badge/build-passing-brightgreen">
  <img src="https://img.shields.io/badge/FrameWork-Django-informational">
  <img src="https://img.shields.io/badge/python-3.11-informational">
  <img href="https://img.shields.io/badge/Mainter-Deepak%20Sharma-brightgreen">
  <img src="https://img.shields.io/badge/maintainer-Deepak Sharma-information">
  <img src="https://img.shields.io/badge/os-linux-brightgreen">
  <img src="https://img.shields.io/badge/Database-MySQL-brightgreen">
  <img src="https://img.shields.io/badge/downloads-79-informational">
</p>


## Project Overview

https://user-images.githubusercontent.com/104820894/171664007-25b260a4-ed5a-40d5-a257-f3de722479dd.mp4

## ScreenShots
<p float="left">
<img src="https://user-images.githubusercontent.com/104820894/188601639-a658105e-f380-45cd-a5a9-e30ac240e893.jpg" width="250">
<img src="https://user-images.githubusercontent.com/104820894/188606683-3f2bd860-5f38-460b-ba94-bfb859bcc496.jpg" width="250">
<img src="https://user-images.githubusercontent.com/104820894/188604147-22a7ef42-069d-4a84-b1f8-812f4d0b63f2.jpg" width="250">
</p>


## Pre-requisite

- Python
- Django
- Mysql
- Git

## How to use

Clone the repo into your dir

- to clone open Terminal/Cmd and type 
```bash
git clone https://github.com/deepak-812/PlannedPay.git
```
- open mysql and type 
```bash 
create database dbbank;
```

- now go to settings in bank folder and set your mysql password section

- open bank folder(which you extracted now)

- type cmd in address bar (to open cmd/terminal in bank folder) and type 
```bash 
python manage.py makemigrations
python manage.py migrate
```

- open mysql and type in it 
```bash 
use dbbank;
insert into bankapp_cust values(101 , 'bnkadmin' , 'Deepak' , 10000 , '' , '2022-03-21' , 1)";
```
- Leave Empty email field for admin

- now open cmd in your extrated_location/bank

- (open bank folder(which you extracted now)

- type cmd in address bar (to open cmd in bak folder) and type)

- two dir with one file manage.py

- address bar type cmd on address bar to open cmd/terminal in present location(bank location)

- type in cmd/terminal 
```bash 
python manage.py runserver
```


- Admin login id is '101' and password is 'bnkadmin'

## Thanks for Visit !!
