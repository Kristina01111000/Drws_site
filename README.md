# Drws_site
everything to do with dr w's wordpress site


 Hours worked 16 may to 16 june: 16 ->  recieved
 
 Hours worked  june 17 to july 16: 12 -> recieved
 
 Hours worked july 17 to august 16: 8 hours 30 min -> recieved
 
 Hours worked august 17 to september 16: 7 hour 20 min -> recieved 
 
  Hours worked september 17 to  october 16: 5 hour 20 min -> recieved
  
  Hours worked october 17 to November 16:  3 hour 20 min

 
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
	- community activity
		- does peepso change the pages numbers when new updates are made?
	- Need:
		- sale page for redirect from weekly topic
- .customclass is the class name to add a border around a group

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
- see if users who don't join in with email confirmation can automatically be deleted after a week



To Do:


- see if there are other smiley faces, less yellow, bigger for inside the buttons
- documentary widget make text bigger, bold bottom text 
- see if we can take away website ask from from comment section, leave name and email
- crop pictures from google drive -> may have to redownload them
- check speed tests 
- make them use paypal when checking out, shows up as credit card possible
- at payment, say you will not be charged again after 4 months, "this learning program ends in four months, and your monthly payments will stop after your fourth month"
- put down included with membership under courses, monthly and 4 month 
- clicking logout takes you to wordpress login page, fix it
	- removed the logout button, put peepso logout somewhere visible

Next call:
- do you like the promo page  menu split?

3 things caused the problem:
wrong login link, pmp, not peepso
cache issue, needed to opt out of caching for peepso shortcodes
nonce check was also an issue with caching
-server speed made it worse b/c if it took too long it wouldnt go through instead of showing the crash



To Do:

- powerpoint course? -> in google drive, make a quiz, upload it to the site, break it up 

- add easier logout to page 

- check the new membership process - kinda screwy right now, he can login without paying, weird, make some new users, they can't join a membership level
	 - I found that it worked when I tried it with a different account (already made)
	 	- select the membership level
	 	- then press select
	 	- then click to add the discount code 
	 	- then click apply
	- for a new account: try with other email account
		- does it let you pick a membership level?

Next call:
- home/welcome page:
	- better description of what he wants, currently looks wierd, I think having an image with text on it for all sections then click on it to go to the article, or having a quote about the topic and then a link
	- /welcome what he described, /home close to what i think it should be
	- color scheme does not match the site, yellow good, brown ok, blue acceptable when really page, pink  not matching
	- archive system for the home page articles -> i think making them posts would be the best bet
		- have not linked the articles yet b/c waiting on archive system
	- different word than sturdying for here and now section -> steadying? strong?
- text on activity login pages, it it good?
- the powerpoint course is really long, how should i separate it?
	- do you have the rights to the photos in it?
	- intro slide 1 to 27 
	- why slide 28 - 35?
	- chakras 36 - 44
	- definitely needs a voice over or to be reorganized if we want it on the site

-using pixlr for basic photo edits
	- yellow image for philosophers corner
- used photo editor for flavenoids picture, font = fresh
