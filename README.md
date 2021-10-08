# Drws_site
everything to do with dr w's wordpress site

 HE CANNOT LOGIN, GETS ERROR 406, THERE IS AN ISSUE WITH SHORTCODES? OR SOMETHING ELSE?
 SERVER NOW RESPONDING TOO SLOW TO GO TO SITE --> got in turned off redirect, stopped plugins, still can't login
 got in, login works when w3 cache is disabled and you go to wp-admin to log in
 admins can login at /wp-admin/, only admins though

 Hours worked 16 may to 16 june: 16 ->  recieved
 
 Hours worked  june 17 to july 16: 12 -> recieved
 
 Hours worked july 17 to august 16: 8 hours 30 min -> recieved
 
 Hours worked august 17 to september 16: 7 hour 20 min
 
  Hours worked spetember 17 to  october 16: 3 hour 40 min
 
To Talk with peepso:
the redirect caused a huge slowdown in the site speed, how to fix this?
added autooptimization and w3 total cache to increase teh site speed, 
have had a login issue since then, sometimes can't login even if the password is changed, needed to wait a while and then it just works;
sometimes login attempt fails, it says to refresh the page, and the login attempt worked

Dr W's login news
- couldn't login, tried multiple times
- he pressed logout instead, took him to wordpress login instead of website login
- he could login from there, but it was weird

 
plugins im using on site:

- peepso
	- updated included installer, easy to add new plugins
	- autoupdates need to be enabled every time they are updated
	- auto updates only work for main peepso plugin, not the additional ones
- learndash 
- paid memberships pro
- real simple ssl 
- Forget About Shortcode button 
- aksimet
- total upkeep
- widget context 
- code snippets -> remove it if he wants the image there, remove it still?
- autoptimization (not css, messed it up really bad)
- w3 total cache

https://www.ssllabs.com/ssltest


speed test:
https://developers.google.com/speed/pagespeed/insights/

https://web.dev/measure/:
- resize images
- check image loading
- server response time

Notes:

- with gecko theme in editor main background photo is set in theme -> body settings
	- need to put separate background pictures into additional css
	- figure out how to make pictures scroll -> change to scroll
		- normal pictures can just be put in using image in page builder
- in peepso logo height has to be in px, not %
- non-members cannot get access to courses, can view the headings 
 	- fixed it in learndash settings, still can't figure out peepso setting
- pages allowed to nonmembers:
	- promo
	- login
	- registration
	- scorecard
	- patients
	- documentary page
	- second promo page
	- Need:
		- sale page for redirect from weekly topic


To Do:

- ssl not working in safari, silk browsers
	- certificate using old ip address, needs to be deleted from that server and it will use inmotion 
	- waiting on passwords/ usernames etc. 
	- he is taking the lead on this
	- work around? remove growing from syracuse, get new one
- change default user image
	-https://www.peepso.com/documentation/assets-overrides-customizing-peepso-images/ 
	- explains how to do it, need to figure out the default images we want
- test email plugin -> 
	- automatic login emails are working
- fix cellphone view of menus
- does he want articles in monthly course? or as articles? 
- emails every week? multiple times a week?
- excess pages deleted, check every month or so
- add cancel course early section to page and get prior month free
- stop users from accessing wordpress login/logout page
- Still Check peepso  for email issue - showing up in spam folder
- write out directions for downloading googledoc
- add pdf of scorecard directions




Next call:
to fix speed:
- redirect adds  a lot of time -> needed, looking at streamlining
- the activity stream is the slowest loading page on peepso -> pick different home page -> user page or promo page?
- change img file types for faster load -> researching a plugin for this
- peepso is a clunky theme -> new plugin for defering non critical css -> researching a plugin for this - autoptimize, lightspeed cache
- widgets slow it down a little -> holding off on adding more until the speed is better
- widget editor plugin slows it down a bit, will delete when confirmation on all widgets next week
- caching needed for faster load next time -> problem for later

next call:

- redirect really slowing it down, should seriously consider having the promo page the homepage, with a new text widget on the right that says login here, and have a redirect after they login
- can manually (in peepso) direct members to a page after login, would this be better combined with the different promo page?
-  all w/o redirect
- added autoptimize, score: 19!!! bad
- added w3 total cache score: 70! good
- removed autooptimize: score: 57, reactivated it
- readded the redirect : score: 66 ok, but not good
- look for a redirect plugin?  -> looks like peepso redirect is the best for a peepso site


To do:
- put quotes on site somewhere, change images, with new ones from big stock, 
	- one on promo page, one on documentary page
- he can't login, might be temporary server issue, could be real problem
- see if users who don't join in with email confirmation can automatically be deleted after a week

Next call:


TO do by thursday:
- switch picture file type -> maybe
- try to see what the redirect login issue is 
- add quotes to the images he says are good
- send invoice
- try to figure out redirect, frontpage issue
waiting on:  ssl, course material

this call:
- did he pick out the pictures he wants -> use purple plant picture for nature quote, look for different walking one in saved photos, crowd in the city is a good one


maybe to make a subdomain for people to be in? 
how do other people get around the login issue? talk to peepso

- make a break in the promo page left menu, between about the course and personal and professional growth
- score card below september's topics on left
- see if there are other smiley faces, less yellow, bigger for inside the buttons

 - sent support ticket into peepso - make sure that shortcodes are not being messed up by autooptimize

 for next call:
 - peepso has an upgrade sale where you can get 5 years for the price of 3, jsyk
 - redirect is reactivated, is site still slow?
 - check his login -> think it is fixed, check shortcodes if it isn't
 - site speed as fast as I think we can get it without upgrading the server
 - images for hippocrates quotes -> walking one good, others maybe good?
 - trying sending notes to him before call good? bad?


- make sure that short codes are all in autooptimize
- ask peepso about redirect, really slow in help 
- his login not working, must have missed a shortcode
- redirect not causing the login issue
- look for a different walking image, different quotes in big stock, look for them for pictures
- philosopher's corner thing
- redirect disabled, site randlmly cannot be reached by dr w
- not working in chrome,safari, working in firefox and silk, and mozilla on phone, all of mine work, none of his work 4 element lifestyle working for me, not him, maybe the server is not connecting to his computers, he was on it before, but it stopped working after 10 minutes
	- he is going to email me to see of all 3 of his sites work on his home computer

- server issue for him? firewall? every computer @ his office was not working
- email himm tomorrow to check the site @ his office again and at his house
	- he fot to the site, but could not login, got an error message
	- he got to the site at home, but still couldn't login

To Do:
- documentary widget make text bigger, bold bottom text 
- make a second promo page menu widget separated between about the course and personal and professional growth
- 
- see if we can take away website ask from from comment section, leave name and email

- crop pictures from google drive
- check promo page buttons, outline not meshing with button


- login issue still occuring,definitely caused by w3 cache
- server not responding, if it doesn't start working, manually deactivate plugin on inmotion

Next call:
- keep going back and forth with peepso


- see if inmotion can test what is wrong with the site, 
- check speed tests 
- make screen grab and send it to peepso 
- subdomain is an option for fixing it? redirect problem
- split up main menu on promo page
- make them use paypal when checking out, shows up as credit card possible
- at payment, say you will not be charged again after 4 months, "this learning program ends in four months, and your monthly payments will stop after your fourth month"
- put down included with membership under courses, monthly and 4 month 

updated peepso people, asked them about caause of login issue, stopped w3 cache and autoptimize
no response yet


clicking logout takes you to wordpress login page, fix it

administrators can login with wp-admin, others cannot
Next call:
- set up philosophy corner
