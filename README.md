# Drws_site
everything to do with drws site


Hours worked 16 may to 16 june: 16 ->  recieved 

Hours worked  june 17 to july 16: 12 -> recieved 

Hours worked july 17 to august 16: 8 hours 30 min -> recieved 

Hours worked august 17 to september 16: 7 hour 20 min -> recieved  

Hours worked september 17 to  october 16: 5 hour 20 min -> recieved  

Hours worked october 17 to November 16:  7 hour 50 min -> recieved

Hours worked November 17 to December 31: 8 hour 50 min -> recieved

Hours worked January: 5 hour 30 min -> received

Hours worked February: 7 hours 15 min -> recieved

Hours worked March: 5 hour 30 min -> recieved

Hours worked April: 12 hour 40 min -> recieved

Hours worked May: 8 hour 20 min -> recieved

Hours worked June: 8 hour 50 min

Hours worked July: 2 hour 45 min
 
plugins im using on site:

- peepso -> auto updates still not working
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
- wp-staging -> deactivate when not in use
- wp-forms -> contact page

https://www.ssllabs.com/ssltest


speed test:
https://developers.google.com/speed/pagespeed/insights/

https://web.dev/measure/:

TO do in future:
	- Come up with a prompt for the chat page for all lessons, not too long
	- Make chats for other people that sound good, 2 to 3 people
	- make quizzes for each lesson 

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
	- **make sure to use peepso login and log out, not pmp login and logout**
	- forward comment emails to him
	- all youtube videos need to be on the matching youtube page
	- .customclass is the class name to add a border around a group
	- capitalize the element names everywhere
	- wants some posts that visible always, some that are unlisted that he uses other sources
		- meta tags: don'treuse, taken from another source, copied, drwwritten, 
		- put in categories instead, unlist the ones from other sources, put them in unlisted category
		- all posts should have comments turned off -> for now
			- comments need to be removed manually if they are turned off after comments have been added
	-using pixlr for basic photo edits
		- yellow image for philosophers corner
	- used photo editor for flavenoids picture, font = fresh
	- for admin email change "Settings"=>"General"=>"E-Mail Address". set to mine now, hopefully he fixes the other sites email address thing
	- nothing on site can be hidden from administrators
	- current font sizes chould continue on through the site
	- Manager of youtube now also -> can change/add etc videos and everything
	
To Do:

- change default user image
	-https://www.peepso.com/documentation/assets-overrides-customizing-peepso-images/ 
	- explains how to do it, need to figure out the default images we want
- emails every week? multiple times a week?
- add cancel course early section to page and get prior month free
- see if users who don't join in with email confirmation can automatically be deleted after a week



To Do:

- make them use paypal when checking out, shows up as credit card possible
- at payment, say you will not be charged again after 4 months, "this learning program ends in four months, and your monthly payments will stop after your fourth month"
- monthly topics are archived as a lesson in a course -> he if going to reuse them
	- they can be deleted after a while if he wants (only go back for 3 months)
	- he wants to reuse them each year (unlist them for next year)
- set categories to air, fire, water, earth
- see what shows up in credit card statement when you buy stuff
- put about 6-8 questions in quizzes most of the time

Survey stuff:

	list of survey options/questions:
		- want all of the 80 questions in list? maybe it should be shorter -> put all 80 in
		- do you have a list of the q's separated into element groups? no-> separate it out manually (goes fire air water earth in the survey list)
		- maybe hubspot for wordpress plugin? it's free, other ones i've found are quite expensive
		- or maybe quiz and survey master, they have a free version, see what is best
		- i will be trying the quiz option for a learndash class first, might not work b/c they are not graded, they are split into categories
	--------- rank list 1 to 5 for each question
		- likert scale for questions in survey
		- wpforms pro does not work the way he wants
		- tryuquiz does not work
		- he is taking care of the quiz
		- 
	


to do now:

- check text color settings, he wants "say what you think" to be a different color
- Color issue in forms, text boxes are too similar to background color, to pale green, or creamy color
- hide lessons so they can't be seen by users until available?

- Show my mom the video, ask a few other people about it, have them make comments?
- Make chats for other people that sound good, 2 to 3 people


- check that contact page works -> it gets sent to administrator email, image + frowarded email to him

See if I can change the color of the download button


- is there a contact form on the site? -> wp forms is on the site, but i don't have it set up or anything, does he want a contact form for it?

- ask him about the site linked in his book -> 4elementyoga.com does not exist, link to 4elifestyle instead, growing instead? 
- I don't think having a site specifically for just yoga is a good idea -> you already have so many sites, you don't want people who want to learn to have to go to 10 different sites
- look at the alt text on the images -> avoid lawsuits, I think we're in the clear images are used for window dressing
- check login attempts 

Look at the youtube channel for links, will be back soon
Check site for other spots where we say there's a charge

- add a hover color to buttons
- DR W pic promo soften or round edges
- add button at top that says "its free to join today"
- add section with link to how to use google docs?
he is still annoyed with how it works on mobile -> check again after dinner, otherwise wait til next week
fix mobile view on buttons -> wierd issue, leaving it for now, css not working the way it should
- think of things for beta testers to think about -> four so far, putting them in the to do list google doc
- figure out why buttons on promo page aren't going away when full screen 
- 	make a new class to see if that works, the button css class still works, something with the screensize class is the issue
- 	maybe the new update messed with how that works? 
- 	get confirmation on the button text then manually put the css class in the button
- 	still there, that fix did not work update him tomorrow
- he likes the scorecard button in the middle
- still doesn't automatically update :(, is it a problem with peepso?

- Switch yearly scorecard to weekly, switch weekly to daily everywhere
- Concert next wednesday, hes advertising then
- Add tiny habits section on why it works scorecard page, into read more section -> not a seperate page
- Leave scorecard on promo page, hide the login button for only mobile
- Make sure it is ‘your ‘ scorecard instead of our
- Make button text green brighter, maybe change background color
- need this done by wednesday mid day so its set for his ad

- i have the most recent scorecard copy on the site as of 7/12, he will probably update it again
