<!-- 
! TEMPLATE|TEMPLATE|TEMPLATE|TEMPLATE|TEMPLATE|

## **TITLE**

### Added things:
    -

### Bug fixes:
    - 

<br><br> 

-->

# **MITTELBOT CHANGELOG**

## **BETA VERSION 0.41.0**

### Added things:
    - added slash commands
    - - ban, infractions, isbanned, kick, mute, purge, unban, unmute, warn
    - disabled normal moderation commands

### Bug fixes:
    - /

<br><br>

## **BETA VERSION 0.40.0**

### Added things:
    - added slash commands
    - - help, info, ping, rank

### Bug fixes:
    - fixed backup system

<br><br>

## **BETA VERSION 0.39.6**

### Added things:
    - added mention to infractions command response when no infractions was found
    - added abilitiy to ban member who isnt in the guild
    - worked on checkForScam

### Bug fixes:
    - fixed unban


## **BETA VERSION 0.39.5**

### Added things:
    - added database backup each day
    - new dep versions

### Bug fixes:
    - fixed auto role bug where bots got the user role

<br><br>

## **BETA VERSION 0.39.4**

### Added things:
    - whitelist link database for checkForScam

### Bug fixes:
    - fixed owner commands
    - fixed spawn bug on crash
    - fixed checkForScam bug (temporary solution)

<br><br>

## **BETA VERSION 0.39.3**

### Added things:
    - added new scam domain database

### Bug fixes:
    - /

<br><br>

## **BETA VERSION 0.39.2**

### Added things:
    - added restart after bot crash
    - changed lines of code (new module & new code)
    - added feature to delete every past message on ban (limit: 7 days)

### Bug fixes:
    - /

<br><br>

## **BETA VERSION 0.39.1**

### Added things:
    - /

### Bug fixes:
    - updated severity vulnerabilities

<br><br>

## **BETA VERSION 0.39.0**

### Added things:
    - added option to remove settings value from database

### Bug fixes:
    - fixed bug when user clicked on "x" on help command
    - upgraded version of dependecies

<br><br>

## **BETA VERSION 0.38.4**

### Added things:
    - added crash log to see if the bots crashed or not in logs

### Bug fixes:
    - /

<br><br>

## **BETA VERSION 0.38.3**

### Added things:
    - /

### Bug fixes:
    - lowered xp per message
    - fixed space bug in auditlog

<br><br>

## **BETA VERSION 0.38.2**

### Added things:
    - bot will update activity each 12h

### Bug fixes:
    - update scam manage to working one

<br><br>

## **BETA VERSION 0.38.1**

### Added things:
    - /

### Bug fixes:
    - fixed shard bug
    - new dependencies version

<br><br>

## **BETA VERSION 0.38.0**

### Added things:
    - added ability to disable commands global
    - added new insert data query on guildCreate

### Bug fixes:
    - fixed shard crash after 5 days

<br><br>

## **BETA VERSION 0.37.2**

### Added things:
    - /

### Bug fixes:
    - bug fixes on guildMemberRemove &  guildMemberAdd

<br><br>

## **BETA VERSION 0.37.1**

### Added things:
    - /

### Bug fixes:
    - Fatal bug fixed when member is muted but dont have any data in member info database

<br><br>

## **BETA VERSION 0.37.0**

### Added things:
    - added "isBanned" command to check if a user is banned or not
    - added npm script to install log folder

### Bug fixes:
    - /

<br><br>

## **BETA VERSION 0.36.6**

### Added things:
    - changed bot restart time to 5d

### Bug fixes:
    - /

<br><br>

## **BETA VERSION 0.36.5**

### Added things:
    - /

### Bug fixes:
    - fixed bug where roles didnt got given back after unmute 

<br><br>

## **BETA VERSION 0.36.4**

### Added things:
    - /

### Bug fixes:
    - fixed bug where roles didnt got given back after unmute 

<br><br>

## **BETA VERSION 0.36.3**

### Added things:
    - added timestamp to info command

### Bug fixes:
    - joined At bug fix

<br><br>

## **BETA VERSION 0.36.2**

### Added things:
    - /

### Bug fixes:
    - small bug fixes

<br><br>

## **BETA VERSION 0.36.1**

### Added things:
    - /

### Bug fixes:
    - fixed errorhandler in some files

<br><br>

## **BETA VERSION 0.36.0**

### Added things:
    - added errorhandling on missing permissions

### Bug fixes:
    - small bug fixes

<br><br>

## **BETA VERSION 0.35.4**
### Added things:
    - /

### Bug fixes:
    - removed old packages
    - fixed bug where banned people get unbanned on next check
    
<br><br>

## **BETA VERSION 0.35.3**
### Added things:
    - added new rank card

### Bug fixes:
    - /
    
<br><br>

## **BETA VERSION 0.35.2**
### Added things:
    - /

### Bug fixes:
    - hasPermission bug fix
    
<br><br>

## **BETA VERSION 0.35.1**
### Added things:
    - changed Audit-log format

### Bug fixes:
    - /
    
<br><br>

## **BETA VERSION 0.35.0**
### Added things:
    - added help command with every command in it
    - hasPermissions improvements


### Bug fixes:
    - /
    
<br><br>

## **BETA VERSION 0.34.4**
### Added things:
    - changed activity system


### Bug fixes:
    - /

<br><br>

## **BETA VERSION 0.34.3**
### Added things:
    - give user the value of xp each message in levelsettings


### Bug fixes:
    - /

## **BETA VERSION 0.34.2**
### Added things:
    - /


### Bug fixes:
    - bug fixes


<br><br>

## **BETA VERSION 0.34.1**
### Added things:
    - /


### Bug fixes:
    - bug fixes


<br><br>

## **BETA VERSION 0.34.0**
### Added things:
    - database connection will now be handled by a mysql connection pool


### Bug fixes:
    - !mods mr will now return a message when the value is empty


<br><br>

## **BETA VERSION 0.33.0**

### It's time to release a huge new feature: <b>Levelsystem</b> :yus:
<br>

### Added things:
    - Levelsystem (BETA)
    - - !rank (mention) [open to everyone]

    - - !levelsettings rank | r [open to server admins]
    - - - set level
    - - - set rankup role or "none"
    - - - set XP

    - - gain xp per message á 1 min


### Bug fixes:
    - removed whitelist (bot is now private)
    - "Lines of Code" bug is now fixed and the total lines of self-coded Code will be displayed
    - bot will now restart each 24h due JavaScript Heap out Memory bug & the bot didn't responsed after 24h+ uptime
    - disable owner only commands due unhandle bugs
    - my little bug hunters killed a few bugs too


<br><br>

## **BETA VERSION 0.32.0**

### Added things:
    - /

### Bug fixes:
    - checkDatabase is now working as it should

<br><br>

## **BETA VERSION 0.31.0**

### Added things:
    - /

### Bug fixes:
    - checkForScam function bug fixed

<br><br>

## **BETA VERSION 0.30.0**

### Added things:
    - /

### Bug fixes:
    - bug fixes




## **BETA VERSION 0.29.0**

### Added things:
    - automatically version control

### Bug fixes:
    - "database undefined" bug fixed in unban command


<br><br>

## **BETA VERSION 0.28.0**

### Added things:
    - /

### Bug fixes:
    - fixed bug where every infraction were shown


<br><br>

## **BETA VERSION 0.27.0**

### Added things:
    - roles will be saved on ban too

### Bug fixes:
    - huge bug fix
    - bot should work as usual now

<br><br>

## **BETA VERSION 0.26.0**

### Added things:
    - /

### Bug fixes:
    - bug fixes and bug fixes and bug fi...


<br><br>

## **BETA VERSION 0.25.0**

### Added things:
    - bot is running on shards now

### Bug fixes:
    - high memory storage fixed


<br><br>

## **BETA VERSION 0.24.0**

### Added things:
    - added better errorhandler
    - add advanced scamlist feature where every server admin can request to add an specified link
    - - commands: "add", "delete" and "view" added

### Bug fixes:
    - bug fixes
    - bot performance improved


<br><br>

## **BETA VERSION 0.23.0**

### Added things:
    - Settings to save, update or remove modroles is now with buttons (User friendly 100%)

### Bug fixes:
    - infractions command bug fixed


<br><br>

## **BETA VERSION 0.22.0**

### Added things:
    - /

### Bug fixes:
    - hot fix
    - improvements


<br><br>

## **BETA VERSION 0.21.0**

### Added things:
    - reactivate "checkScam" feature & improvements
    - add guild name to private Punishment response

### Bug fixes:
    - small bug fixes


<br><br>

## **BETA VERSION 0.20.0**

### Added things:
    - added feature to see the actual join time in info command
    - added scam detection feature with autoban

### Bug fixes:
    - improved and fixed some bugs in ban functions

<br><br>

## **BETA VERSION 0.19.0**

### Added things:
    - updated "config.example.json to lastest version

### Bug fixes:
    - fixed bug where the bot crashed on unban command when the user isnt banned
    - fixed rejoin bug where user got the muted role when they are muted on another guild

<br><br>

## **BETA VERSION 0.18.0**

### Added things:
    - added emotes to modlog embed
    - improved integration to add tables and columns automatically

### Bug fixes:
    - small bug fixes

<br><br>

## **BETA VERSION 0.17.0**

### Added things:
    - added integration to add tables and columns automatically
    - added image viewer on delete message event in auditlog
    - added checkScam integration
    - - member gets banned & message gets deleted
    - - its enabled on default

### Bug fixes:
    - small bug fixes

<br><br>

## **BETA VERSION 0.16.0**

### Added things:
    - /

### Bug fixes:
    - fixed "heap out of memory"

<br><br>

## **BETA VERSION 0.15.0**

### Added things:
    - added scripts to create template tables and columns

### Bug fixes:
    - /

<br><br>

## **BETA VERSION 0.14.0**

### Added things:
    - /

### Bug fixes:
    - bug fixes

<br><br>

## **BETA VERSION 0.13.0**

### Added things:
    - Complete rework of all moderation commands 
    - now more functions are more dynamically and can be used at every other command or interaction
    - tried to improve bots performance

### Bug fixes:
    - bug fixes

<br><br>

## **BETA VERSION 0.12.0**

### Added things:
    - improved auto unmute

### Bug fixes:
    - 

<br><br>

## **BETA VERSION 0.11.0**

### Added things:
    - added permanent feature to ban and mute command

### Bug fixes:
    - 

<br><br>

## **BETA VERSION 0.10.0**

### Added things:
    - the "till date" will now shown if it exits in infraction command

    - feature added to save roles when a user leaves and give them back when the same user joins back
    - - if the user is muted the bot gives only the muted role

### Bug fixes:
    - fixed error where tables didnt got added when one querie got an error - "npm run deployTables"

<br><br>

## **BETA VERSION 0.9.0**

### Added things:
    - /

### Bug fixes:
    - fixed bug where the infraction command didnt worked with only user id after last version

<br><br>

## **BETA VERSION 0.8.0**

### Added things:
    - added option to use infraction command with only user id

### Bug fixes:
    - removed useless fata error logging

<br><br> 

## **BETA VERSION 0.7.0**

### Added things:
    - [private]

### Bug fixes:
    - /

<br><br> 

## **BETA VERSION 0.6.0**

### Added things:
    - improved remove all roles function on mute command

### Bug fixes:
    - fixed bug where the bot gives a fatal error

<br><br> 

## **BETA VERSION 0.5.0**

### Added things:
    - Logging in file

### Bug fixes:
    - /

<br><br> 

## **BETA VERSION 0.4.0**

### Added things:
    - added server to whitelist

### Bug fixes:
    - /

<br><br> 

## **BETA VERSION 0.3.0**

### Added things:
    - added feature to remove and save all user roles on mute
    - added featute to add all saved roles to user on unmute

### Bug fixes:
    - /

<br><br> 

## **BETA VERSION 0.2.0**

### Added things:
    - /

### Bug fixes:
    - small bug fixes & improvements
    - infraction will now deleted from specified database and insert into another database


<br><br> 

## **BETA VERSION 0.1.0**

### Added things:
    - added color to specified auditlog events

### Bug fixes:
    - small bug fixes & improvements
    - infraction will now deleted from specified database and insert into another database


<br><br> 

## **BETA VERSION 0.0.2**

### Added things:
    - added error handler to ban command

### Bug fixes:
    - fixed bug where links triggered the updateMessage event
    - fixed bug where space were given as time


<br><br> 

## **BETA VERSION 0.0.1**

### Added things:
    - added error handler to ban command

### Bug fixes:
    - fixed permission bug where the mod role "helper" can't use all moderation commands
    - removed channelupdate log for now


<br><br> 

## ****