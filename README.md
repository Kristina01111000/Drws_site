# Drws_site
everything to do with dr w's wordpress site

 Hours worked 16 may to 16 june: 16 ->  recieved
 
 Hours worked  june 17 to july 16: 12 -> recieved
 
 Hours worked july 17 to august 16: 8 hours 30 min -> recieved
 
 Hours worked august 17 to spetember 16: 5 hour 30 min
 
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
- pages aloowed to nonmembers:
	- promo
	- login
	- registration
	- scorecard
	- patients
	- documentary page
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
- fix cellphone view of menu
- does he want articles in monthly course? or as articles? 
- emails every week? multiple times a week?
- excess pages deleted, check every month or so
- add cancel course early section to page and get prior month free
- fine tune new button description
- get rid of credit card link on payment (or see if it forces paypal)
	- check it, get paid for what i put in
	- set itto one dollar just for giggles
- check to see if 'one topic' word can be removed from the lesson content, or change it to lesson
- stop users from accessing wordpress login/logout page


Still Check:

-  peepso  for email issue

Next Call:

- different picture of him for front page? - torso or body shot
- ssl update
- does he have the front page video 

- write out directions for downloading googledoc

Next call:

- clean up scorecard paragraphs on page
- add pdf of scorecard directions
- add join here at bottom of front page menu


Next call:
- fixed the menus
- got widget context to work by downloading classic widgets plugin, will work until at least 2022
- pages to link to from copy of widgets on front page
	- documentary links to documentary?
	- scorecard links to scorecard?
	- monthly topic links to sale page?
- confirmation on extra widget copies: whole widget context thing adds several steps to making them and changing them,
	-  want confirmation before i do it
	- copy of weekly topic widget to sale page
	- copy of documentary widget to documentary and sale page
- see if nonmembers can be shuffled into a different page for sale

- documentary widget make text bigger, bold bottom text 
- make a second promo page menu widget separated between about the course and personal and professional growth
- septembers topic onleft for most of site, promo one on the right
- speed tests on the site
- leave a reply -> leave a comment, change words to comment section 
- see if we can take away website ask from from comment section, leave name and email


Next call:
to fix speed:
- redirect adds  a lot of time -> needed, looking at streamlining
- the activity stream is the slowest loading page on peepso -> pick different home page -> user page or promo page?
- change img file types for faster load -> researching a plugin for this
- peepso is a clunky theme -> new plugin for defering non critical css -> researching a plugin for this - autoptimize, lightspeed cache
- widgets slow it down a little -> holding off on adding more until the speed is better
- widget editor plugin slows it down a bit, will delete when confirmation on all widgets next week
- caching needed for faster load next time -> problem for later

to do:
- resize images manually, change img file types to avif, make less clunky
- redirect turned off, login not working right when it is on
- add pictures from google drive
- check promo page buttons, outline not meshing with button

next call:

- redirect really slowing it down, I think the promo page should be the main page
-  all w/o redirect
- added autoptimize, score: 19!!! bad
- added w3 total cache score: 70! good
- removed autooptimize: score: 57, reactivated it
- readded the redirect : score: 66 ok, but not good
- look for a redirect plugin? 

To do:
- manually size images, change img file types?
- research redirect plugin? peepso redirect might be the problem
