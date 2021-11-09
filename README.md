# **I.C.A.R.U.S.** v1.0  
![ICARUS Version](https://img.shields.io/badge/ICARUS-v1.0.4-49fcff)
![Python Version](https://img.shields.io/badge/python-v3.8.5-3571A3)
![Discord.py Version](https://img.shields.io/badge/discord.py-v1.7.3-94332c)
![Last Commit](https://img.shields.io/github/last-commit/tkomasa/ICARUS-documentation)
![IIF Logo](https://img.shields.io/badge/commissioned%20by-INVFED-0A2537)
![]()

### INVFED Computational Assistant and Recruitment Utility System
Created by **Turtle-12** for **Invictus Intergalactic Federation**  
<sub>_Special thanks to: **Terra**, **Majestic**, and **INVFED Command**._</sub>

## Table of Contents:  
[I. Ethos](#I-Ethos)  
[II. Use Cases](#II-Use-Cases)  
[III. Dependecies](#III-Dependencies)  
[IV. Events](#IV-Events)  
[V. Commands](#V-Commands)  
&emsp;&emsp; [V.a. Interview Commands](#Va-Interview-Commands)  
&emsp;&emsp; [V.b. Logging Commands](#Vb-Logging-Commands)  
[VI. Examples](#VI-Examples)  
[VII. Errors and Bugs](#VII-Errors-and-Bugs)  

## I. Ethos:
A. The purpose of this bot is _**to assist and augment the human**_ orientation group within the INVFED organization.  
B. It must be beneficial and practical, but _**must not act as a keystone for the system**_; i.e. the bot should be able to dissappear and the organization will still be able to function.  
C. The front-end _**must be understandable and useable by the layman**_, and have extensive documentation to aid in learning the systems and applications of the bot.  
D. The bot _**must not require administrative permissions**_ in order to function, for safety and security reasons.  

## II. Use Cases:
1. Pre-Interview: The primary use case, and original goal of the bot, was to have something to cover for the orientation members if no one is available. It will run through basic information with the user, collect data from the user, and have them think about and make preliminary choices about branch and enlistment. After these answers and data are logged into a specified channel, it is then up to a human to accept or deny the person, most likely by having a brief conversation with them when someone is finally available. This allows for the majority of the interview to be done with the bot when necessary, but still gives a human touch and the ability to ask any questions or make changes to choices before their choices become written in stone.
2. Post-Interview: After the user has made choices and they have been approved by a human, the bot allows for automation of nickname changes, text-channel announcements, and role assignment. *Please note, the bot currently only supports these operations for users who have done the pre-interview with the bot.*
3. Logging: The bot also makes use of JSON logs to create a long-term and interactable form of logging. This keeps track of mutable and immutable data on the user for historical, archival, and data-collection needs. For example, this keeps track of both the RSI username (mutable, changeable) and the Discord ID (immutable, permanent) of users in order to always have a way to access information on a user.

## III. Dependencies:
These are backend and frontend requirements that must be fulfilled in order for the bot to function. It is assumed that the raw Python code itself is all present and functional.

<!--List out all dependencies-->
<!--Also create then mention the requirements.txt file for PIP-->

## IV. Events:
These are automatic events that occur in the stream of data from Discord. When these events occur, an action is taken. This is a list of the events (including any specific rules such as channel or role required), along with their corresponding actions.

<!--List all @bot.events in the main bot.py file and their actions-->

## V. Commands:
These are commands that must be actively called by a user to take effect. Along with the command call itself (i.e. !command), they often require, or optionally allow, several other parameters to be given. Parameters are positional by Discord's restrictions, meaning the orders and amount will always matter.

#### Always remember...
1. Everything is cASe-SenSiTIve.
2. Position matters.
3. Channel matters.
4. Your roles matter.
5. _Good Practice_: Put all your parameters inside quotes like "this".
#### V.a. Interview Commands:
<!--List all interview commands, their parameters, their requirements(channel, roles, etc) and their functionality-->

#### V.b. Logging Commands:
<!--List all logging commands, their parameters, their requirements(channel, roles, etc) and their functionality-->

## VI. Examples:
Here we will show a few examples of the bot being used in order to help familiarize yourself with the practical usage of commands.
<!--Written and image-based examples of actually using commands in a Discord server-->
1. **Create** a JSON log for a user who did not interview with the bot.
2. **Decline** a user's bot submission log.
3. **Update** a user with a Red Flag.
4. **Update** a user's RSI username in their JSON log.
5. **Search** for a user's JSON log.
6. 

## VII. Errors and Bugs:
If you encounter an error or bug, here's what you should do:
#### 1. Verify the problem.
It's always a good idea at least to verify that you have used the command properly. Revisit the [Commands section](#V-Commands) and [Command reminders](#Always-remember) to verify that the command you are attempting meets all the requirements. Do you have permission to use that command? Are you in the right channel? Have you provided all the required parameters? Did you provide the parameters in the correct order? If you are sure that you have done everything properly, the next step is to...
#### 2. Contact INVFED Command.
If the bot is misbehaving, not working properly, or not working at all, please contact Command as soon as possible. Rampaging robots are no good at all, have you seen Terminator? Please provide as much information as possible to the officers, as the more information we have the better. What command did you call? When? Where? Why? What did you expect to happen? What actually happenned? All of these things are important and helpful to getting the bot back online and running as intended. We appreciate _all_ help in solving this issues and thank you in advance for you time and effort on getting this information to us.
