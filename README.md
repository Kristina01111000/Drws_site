# Drws_site
everything to do with dr w's wordpress site

 Hours worked 16 may to 16 june: 16 ->  recieved
 
 Hours worked  june 17 to july 16: 12 -> recieved
 
 Hours worked july 17 to august 16: 7 hours 05 min
 
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
- redirection -> removed it, not needed anymore

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


Still Check:

-  peepso  for email issue

Next Call:

- different picture of him for front page? - torso or body shot
- ssl update
- does he have the front page video 
- will be adding my mom as user for testing
- might need google account for google docs
	- works for me with a seperate google account
	- made the changes to the document

- write out directions for downloading googledoc
-  see if default 0 can be removed from excel file
-   add monthly totals for each element at the bottom
- change logo click to go to homepage, not frontpage


Next call:

- does he want search on the header?
- need to change logo link in header file, will need to rechange it every time theme upgrades, is this what he wants?
	- can switch activity page to frontpage? -> would not work b/c then frontpage will not be visible
		- maybe force front page to load for people not logged in?
		- make a landing page that redirects to a learn more page?
- make patients page visvle to people not logged in -> think the redirects in gecko theme got it done
