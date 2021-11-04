# Drws_site
everything to do with dr w's wordpress site


 Hours worked 16 may to 16 june: 16 ->  recieved
 
 Hours worked  june 17 to july 16: 12 -> recieved
 
 Hours worked july 17 to august 16: 8 hours 30 min -> recieved
 
 Hours worked august 17 to september 16: 7 hour 20 min -> recieved 
 
  Hours worked september 17 to  october 16: 5 hour 20 min -> recieved
  
  Hours worked october 17 to November 16:  6 hour 45 min

 
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
		- sale page for redirect from weekly topic?
	
- .customclass is the class name to add a border around a group


- wants some posts that visible always, some that are unlisted that he uses other sources
	- meta tags: don'treuse, taken from another source, copied, drwwritten, 
	- put in categories instead, unlist the ones from other sources, put them in unlisted category
	- all posts should have comments turned off -> for now
		- comments need to be removed manually if they are turned off after comments have been added

To Do:

- ssl not working in safari, silk browsers
	- certificate using old ip address, needs to be deleted from that server and it will use inmotion 
	- waiting on passwords/ usernames etc. 
	- he is taking the lead on this
	- work around? remove growing from syracuse, get new one
- change default user image
	-https://www.peepso.com/documentation/assets-overrides-customizing-peepso-images/ 
	- explains how to do it, need to figure out the default images we want
- fix cellphone view of menus
- does he want articles in monthly course? or as articles? 
- emails every week? multiple times a week?
- excess pages deleted, check every month or so
- add cancel course early section to page and get prior month free
- stop users from accessing wordpress login/logout page
- write out directions for downloading googledoc
- add pdf of scorecard directions
- see if users who don't join in with email confirmation can automatically be deleted after a week



To Do:


- see if we can take away website ask from from comment section, leave name and email
- make them use paypal when checking out, shows up as credit card possible
- at payment, say you will not be charged again after 4 months, "this learning program ends in four months, and your monthly payments will stop after your fourth month"
- put down included with membership under courses, monthly and 4 month??

3 things caused the problem:
wrong login link, pmp, not peepso
cache issue, needed to opt out of caching for peepso shortcodes
nonce check was also an issue with caching
-server speed made it worse b/c if it took too long it wouldnt go through instead of showing the crash



To Do:


- add easier logout to page (header?)

- check the new membership process - kinda screwy right now, he can login without paying, weird, make some new users, they can't join a membership level
	 - I found that it worked when I tried it with a different account (already made)
	 	- select the membership level
	 	- then press select
	 	- then click to add the discount code 
	 	- then click apply
	- for a new account: try with other email account
		- does it let you pick a membership level?

Next call:
- home page:
	- archive system for the home page articles -> i think making them posts would be the best bet
		- have not linked the articles yet b/c waiting on archive system

- the powerpoint course is really long, how should i separate it?
	- do you have the rights to the photos in it? -> they're good, 
	- intro slide 1 to 27 -> how to separate intro slides?
	- why slide 28 - 35?
	- chakras 36 - 44
	- definitely needs a voice over or to be reorganized if we want it on the site
	- try separating it into 2-3 courses, 


-using pixlr for basic photo edits
	- yellow image for philosophers corner
- used photo editor for flavenoids picture, font = fresh

current call:


- start putting the powerpoint into the site first quarter of the course, break it up so it is less overwhelming
	- break it up in the way that seems best
	- try to get ~ 10 slides per lesson
	- should he do voice over? probably
	
Next call:

- removed dates from posts in settings, all or nothing way to do it
- no way to remove the author from the post, switched it to dr w, 
	- if you really want the author removed them I can edit the theme code, it will need to be reedited every time it updates (which is every week)

- welcome page deleted, any changes to home page?
	- made the background of the quote image lighter, is that light enough/too light?

-added first lesson to 4 element course 
	- i think we need a voice over for it
	- is 25 slides too long for the first lesson?
	
- I am going on a trip from saturday to wednesday, do you want to have a call next week?

- do you want the homepage to be what the redirect is set to?
- archive settings good? categories, unlisting , should I attach the articles(posts) to the home page?

To Do:
- monthly topics are archived as a lesson in a course
	- they can be deleted after a while if he wants (only go back for 3 months)
	- he wants to reuse them each year (unlist them for next year)

- corners are posts 
	- no comments allowed on corner posts

- see if 'published' can be changed on post page
- make a GrowingHolisticallyStaff account for publishing

- home page
	- straighten out the boxes
	- switch sides of earth and water
	- try air image without the black box
	- get background from bigstock and put quote on top
	- make earth image text bigger
	- set this page to home page
- set categories to air, fire, water, earth

- send email about 4 element powerpoint course
- put password stuff at bottom menu
- make widget about the powerpoint course above score card widget on right watch  dr w's lecture on the four elements
- add some images to the first section of the slides
	- upload to google drive by tomorrow @ 3, email him about it when done

- figure out survey so people can figure out elements, find a plugin, add totals up so people can get the breakdown

- when he does the voiceover, look at timing of course, decide where breaks in the powerpoint should be
