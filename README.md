<p align="center"><img width=100% height=15% src="https://i.ibb.co/H2sSf6T/JYTBOT02.png"></p>

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
![Java](https://img.shields.io/badge/JDK-11+-blue.svg)
[![GitHub Issues](https://img.shields.io/github/issues/triippz-tech/JYTB.svg)](https://github.com/triippz-tech/JYTB/issues)
![Contributions welcome](https://img.shields.io/badge/contributions-welcome-orange.svg)
[![License](https://img.shields.io/badge/license-GPL-blue.svg)](https://opensource.org/licenses/GPL-3.0)

# Basic Overview

**Note:** *This project was made for educational purposes. I am not liable for anything you decide to do with this bot*. 

JYTBOT02 is a multi-threaded Java application, which "views" a given YouTube video. The bot auto-rotates proxies if a proxy
has been determined to be dead, compromised, or the bot has finished watching the video. The goal is to provide unique 
views to a YouTube video.
<p align="center"><img width=100% height=35% src="https://i.ibb.co/mN1P6tx/example.jpg"></p>

<br>

# Important
- Released Version only Trial Version (Locked some Features). So Some ScriptKiddy cant just sell this bot.
- Join this Group Discord for Req full version : https://discord.gg/6Ax2Qbe

# Current State
- Only work with Firefox.
- Work for Linux and Windows (64-bit).


# Features 
- Paid Proxy using APIKEY from pubproxy.com.
- Free Proxy using lib from dev.
- Views using url.
- Views using yt search engine (Best).
- Views using link video from instagram profile.
- Headless or no headless options.
- Multi Thread (Multiple worker for the bot)

# How to run this app

## on LINUX

### Ubuntu :
- Download Firefox and Java
```console
sudo apt -y  install default-jdk firefox
```
- Download Gecko Driver 
```console 
sudo wget https://github.com/mozilla/geckodriver/releases/download/v0.26.0/geckodriver-v0.26.0-linux64.tar.gz
sudo tar -xvzf geckodriver*
sudo chmod +x geckodriver
sudo mv geckodriver /usr/local/bin/
```
- Download jar file from releases tab
- run the jar 
```console
java -jar JYTBtrial.jar
```
### Debian/Kali : 
- Download Firefox and Java
- Do instruction from this web
- Download java : 
  https://docs.datastax.com/en/jdk-install/doc/jdk-install/installOpenJdkDeb.html
- Download firefox
- https://miloserdov.org/?p=2848
- Download Gecko Driver 
```console 
sudo wget https://github.com/mozilla/geckodriver/releases/download/v0.26.0/geckodriver-v0.26.0-linux64.tar.gz
sudo tar -xvzf geckodriver*
sudo chmod +x geckodriver
sudo mv geckodriver /usr/local/bin/
```
- Download jar file from releases tab
- run the jar 
```console
java -jar JYTBtrial.jar
```

### on Windows
- Download Firefox (u can do it urself)
- Download Java 
  https://www.oracle.com/java/technologies/javase/jdk14-archive-downloads.html
- Download geckodriver
  https://github.com/mozilla/geckodriver/releases/download/v0.26.0/geckodriver-v0.26.0-win64.zip
- extract geckoDriver.exe to firefox directory
  here ->  C:\\Program Files\\Mozilla Firefox\\
- Download jar file from releases tab
- run the jar 
```console
java -jar JYTBtrial.jar
```



## Screenshot App Run on 6 vps linux  
<p align="left"><img width=50% src="https://i.ibb.co/b3vKp6k/SS0594.jpg"></p>

## Screenshot Traffic from yt video analystic
<p align="left"><img width=50% src="https://i.ibb.co/rfZFKfK/SS0595.jpg"></p>

# Change-Log:
## Version 2.0

###  Added 
- 3 Options for Viewing methods.
- Headless options.
- Latest user agents for Firefox.

###  Bug Fixed
- Proxy for Firefox Drivers.

###  Improved
- Complex handling for error.
- Bot Detect if proxy down.
- Bot Detect if proxy need user login.
- Bot Detect if Proxy Detected.
- Bot Detect if Bot Detected by Youtube.
