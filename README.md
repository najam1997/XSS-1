# Vulnerability: Reflected XSS

## Purpose
This is the beginning of a deliberately vulnerable application series by the name of NUSK Labs, to help the young and upcoming penetration testers to learn hacking.

## Pre-Requisites
1. Basic understanding of Web Apps and cross site scripting is a must.
2. Make sure you have python and flask installed.
3. For Windows, you'll have to download and install **python** as well as **pip** from browser. For Linux, following command would do:
```
sudo apt-get install python
```
Then download FLASK framework with the following command:
```
pip install flask
```

## Steps for setup

1. Open CMD/Terminal on your desktop.
2. Run the following command: 
```
git clone https://github.com/najam1997/XSS-1.git
```
3. This will clone the Repo.
4. Then we need to start our FLASK App, for that run:
```
cd XSS-1
python3 server.py
```
5. Then start the challenge, for which you'll have to go into the **templates** folder and open the **index.html** file on a browser.

## Vulnerability difficulty and Exploitation details
Difficulty: Very Easy
Exploitation: Just trigger an alert.
