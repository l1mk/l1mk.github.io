---
layout: post
title:      "Tips and Tricks I learned during my Sinatra Project"
date:       2019-10-21 03:52:10 +0000
permalink:  tips_and_tricks_i_learned_during_my_sinatra_project
---


Hey guys, a quick post here with some helpful tips I notice during the development of my Sinatra Project:

1. Create something you are excited for or can use: making something that you feel useable and usefull will help you be more passionate on finishing and even doing something extra! in my case, I spent more time on the front end trying to make the site look nice!, and you dont have to be an expert, CSS is pretty simple after you read about it a couple of time, dont me shy and try it out!
2.  Always be adding and commiting with an explanatory description in your repositery on Github, I had this issue since I was working on two different places all the time with two different computers. It helps when you know what changes and go back to older versions when you feel something is broken.
3.  In order to erase your db, you can simple erase the schema and the development.sqlite file, and migrate again using rake db:migrate. Really helpful when I realize all my data was pretty corrupted.
4.  Do not forget to use require 'pry' and binding.pry. This is your number one friend for troubleshooting.
5. When adding changes to stage before commiting make sure to go inside each folder file using #git add ./app/etc believe me, a lot of the times I found myself with some changes and some not, I want to kill myself lol.
6. If you using Learn IDE 3, save, SAVE a lot!, you can use the shortcut CTRL+S on windows, if necesary for you to pay attention to this, because a lot of the time I felt like nothing changed and it was because of this, (There is a light blue circle on the tab on top with the name of the file that indicates something changed but it hasnt been save yet)
7. Something simple as, after #git clone www.whateverpath.com make sure to go inside the folder you cloned using #cd.
8. Use the internet, google a lot and look back for older projects. Sometimes you feel stuck or without ideas and it is ok to find inspiration and answer in the internet, believe me, I can already see that our future depend on it!.
9. Do not forget there is a SLACK community out there for this bootcamp and people are willing to help you succeed!.

Well I think those are good tips, or some things to remember for any project, hopefully this will be helpfull, my best wishes guys...

Ill write you later 
