# Freeze

This app is for testing purpose and is still being worked on not advised for PRODUCTION use.

Freeze Web: Is the main app users will interact with videos.
FreezeDB: Is the backend piece where we store data and needs to be run on the same machine.
Freeze Census(https://github.com/HiGregory/FreezeCensus): Is a page where we compile data on police acitivies across 

## Contents

* [Background](#background)
* [Configuring](#Configuring)
* [Requirements](#Requirements)
* [Additional](#Additional)


# Background


Freeze is a winning ABA Justice Hack 2018 idea based on using technology and design to help people understand what public safety officers have to go through in their daily lives. This app has been rethought and designed to fit the purpose of being a Choose Your Adventure video based app using Public Safety data. 

The code here is from TNGARAUJO and is being repurposed to fit the needs of the Freeze App. The current app is a an interactive video manager which allows a user to create questions and answers to be displayed on top a of a Youtube video. Multiple videos can be added with their questions at specific required times within the video. 

# Configuring

This project requires it backend(https://github.com/HiGregory/FreezeDB) which should be running in the same machine. The technology used in this application are Angular2, ExpressJS, NodeJS, and SQLite3.

Install dependencies: `npm install`.
Run `ng serve` and navigate to `http://localhost:4200/`.
The back-end should be running in the same machine (please download at https://github.com/HiGregory/FreezeDB).

# Requirements

You can see full requirements (https://docs.google.com/document/d/1YqQyLOztCgizhvaufjct2E3WLf06bNtO-gagQ3ome5k/edit?usp=sharing) which will show you the specifications for this app.


# Additional

This app is a fork of Thinkific(https://github.com/tngaraujo/thinkific) and is an open source project.


Additional requirements from orginal app include:
1. Should work with videos that are hosted on a site like Wistia or Youtube

2. Should allow creators to prompt viewers with a question

3. Prompt should be possible at any video time specified by the creator (etc. 2min 30s of a

6 minute video)

4. Prompt should allow space for a question, and between 2 and 6 text responses

5. For each response, the behavior can be to resume playback, or link to another URL

6. Prompt and responses overlaid on video.

7. The interactive video link can be embedded into another page using HTML and a simple

![thinkific1](https://cloud.githubusercontent.com/assets/17129220/24840040/3c5b7664-1d3c-11e7-9023-3fb233c534db.jpg)
![thinkific2](https://cloud.githubusercontent.com/assets/17129220/24840041/3c623738-1d3c-11e7-9135-060e280496d0.jpg)


This app is a fork of Thinkific(https://github.com/tngaraujo/thinkific) and is an open source project.



