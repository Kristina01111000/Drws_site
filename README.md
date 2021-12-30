# Drws_site
everything to do with dr w's wordpress site


 Hours worked 16 may to 16 june: 16 ->  recieved
 
 Hours worked  june 17 to july 16: 12 -> recieved
 
 Hours worked july 17 to august 16: 8 hours 30 min -> recieved
 
 Hours worked august 17 to september 16: 7 hour 20 min -> recieved 
 
  Hours worked september 17 to  october 16: 5 hour 20 min -> recieved
  
  Hours worked october 17 to November 16:  7 hour 50 min -> recieved

Hours worked November 17 to December 31: 7 hour 50 min
 
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
- layout grid block

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
- capitalize the element names everywhere

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





To Do:


- add easier logout to page (header?)



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
	
- archive settings good? categories, unlisting , should I attach the articles(posts) to the home page?

To Do:
- monthly topics are archived as a lesson in a course
	- they can be deleted after a while if he wants (only go back for 3 months)
	- he wants to reuse them each year (unlist them for next year)

- set categories to air, fire, water, earth
- check images that i put in bigstockphot for powerpoint
- make widget about the powerpoint course above score card widget on right watch  dr w's lecture on the four elements
	- make sure all the rightside menu links are correct
- figure out survey so people can figure out elements, find a plugin, add totals up so people can get the breakdown



For Next week:
- see what shows up in credit card statement when you buy stuff


Next call:

	list of survey options/questions
		- want all of the 80 questions in list? maybe it should be shorter -> put all 80 in
		- do you have a list of the q's separated into element groups? no-> separate it out manually (goes fire air water earth in the survey list)
		- maybe hubspot for wordpress plugin? it's free, other ones i've found are quite expensive
		- or maybe quiz and survey master, they have a free version, see what is best
		- i will be trying the quiz option for a learndash class first, might not work b/c they are not graded, they are split into categories
	--------- rank list 1 to 5 for each question
		- likert scale for questions in survey
	
	- put about 6-8 questions in quizzes most of the time
	- separate the course into sections (about 25 slides each), put it on google drive
	- make sure that non admins can't get into wp dashboard, (blocked by memberships app)
	
next meeting on the 2nd
for next call:
	- pay pal issue solved?
	- does the widget for 4 element course need an image?


- shared google doc with tasks for both of us, made it visible to anyone so he can add stephen, videographer etc


to do:
- Make quizzes for the 4 month course after lessons are added
- add new mobile sidebar -> make sure the scroll works better
- For articles always have picture wrapped by text
- mobile sidebar - in notes
- update plugin list


- Make quizzes for the 4 month course after lessons are added
- finish mobile sidebar -> latest update fixed scroll problem
- For articles always have picture wrapped by text
- For widget documentary make the title not hot, just word Documentary
-  Make word documentary be bold
- Make the hot part of the links smaller, so they stick out more, so “they tap into ” is hot , not the whole widget “click here” part be hot
- Make the hot part bold
- Check that the redirect from login goes to the home page
- See why dr w is being sent to the promo page when clicking on logo while logged in, when clicking on the link that says home page he gets sent to the promo page, even the url sends him to the promo page -> resetting the redirect fixed it fixed it

- Try to put the logo underneath the line, if not remove it
- Put the course content into topics for 4 month learning program
- Remove the word introduction from the top of the course content
- 4 element course spacing when window is small fix it
- Check on other account how the course content that we don’t have access to yet looks
- Email him on the 27th if i haven’t heard from him
- sent email on 28th -> no response, assuming no meeting tomorrow

promo page video logo shows
Mangaer of youtube now also

- if theme number and peepso number don't match it looks like an error message gets sent to my email
