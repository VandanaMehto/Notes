# Notes

In this project I wrote Api's of keeps notes by using Express framework of NodeJS.


## project Introduction

* In this project to get tha data with help of GET method.
* By id also we can get tha data with help of GET method and we can get the data by id and by search also.
* We can post tha data with the help of Post method through postman.
* we can update the data by id, time and date also it will be update with the help of PUT method.
* we can delete tha data by id with tha help of  DELETE method.


## Router functionality

* I added get, Post, PUT and DELETE route.
* For set a date and reminder I used :- let startTime = new Date(Date.now());
let endTime = new Date(startTime.getTime());
* For router we will make one folder and we are following MVC pattern.


## Requirements

Installation process and execution first, if you are using linux-based-OS, open your terminal and install the latest version of
NodeJS and npm. after node Installation if you need to install dependencies which will you use in your project. you can use npm init 
with this code all dependencies install autometically. after that we need to install express.

```bash
 $ sudo apt install nodejs
 ```
 ```bash
 $ node --version
 ```
 ```bash
 $ v12.16.3
 ```
 ```bash
 $ npm --version
 ```
 ```bash
 $ npm install express --save
 ```
 ```bash
 $ npm install system-sleep --save
 ```

