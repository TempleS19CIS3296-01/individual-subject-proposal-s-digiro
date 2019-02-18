# Ncmpcpp Contributions

## Project Abstract
MPD is a popular music player for linux. It is a daemon that functions as a server which client programs must connect to. One such client is ncmpcpp, which functions mostly as a graphical front end for interfacing with mpd. Together, ncmpcpp and mpd work together to form a full flegged music player. Ncmpcpp uses a command line gui based on ncurses. Unfortunately, Ncmpcpp is missing a few importnat features. To start, ncmpcpp does not currently have any way of displaying the album art associated with an mp3 file. In addition, it also does not separate discs in an album in any way. Another problem, is that the system for tagging mp3 files does not allow the user to choose which id3 tag version the tagger will tag with. Implementing as many of these features as possible in ncmpcpp would improve the program greatly.

![Use Case Image](SeanDiGirolamo_NcmpcppContribution.png)

## Project Relevance
This project would be greatly relevant to software development for many reasons. First of all, ncpcpp is already an established piece of open source software that many developers have worked on. Therefore, contributing to this project would require the contributer to become familiar with other developer's code, some maybe even legacy. In addition, the experience of interfacing with mpd's API would be great because in the real world we will use many APIs we aren't familiar with.

## Conceptual Design
I propose we implement and add the following contributions. First of all, a way of viewing the album art embedded in the program. This can be done by maybe adding it to the corner in one of the program views, or maybe even adding a new tab to the program which could display song information and the album art. In addition to this, I propose adding lines between the individual discs in a music album to visually separate them. After this, I also propose adding an option in the mp3 tagger to choose between adding id3v1 tags or id3v2 tags, or both.

## Background
https://github.com/arybczak/ncmpcpp

## Required Resources
- Group members
- A linux operating system
