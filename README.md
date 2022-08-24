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

Hours worked June: 8 hour 50 min -> recieved

Hours worked July: 7 hour 20 min -> sent

Hours worked August: 6 hour 45 min
 
plugins im using on site:

- peepso -> auto updates still not working
- learndash 
- paid memberships pro
- real simple ssl 
- Forget About Shortcode button 
- aksimet
- total upkeep
- widget context 
- code snippets -> needed for google analytics
- autoptimization (not css, messed it up really bad) - not using it anymore
- w3 total cache - not anymore
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
		- join 30 day challenge page
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


- monthly topics are archived as a lesson in a course -> he if going to reuse them
	- they can be deleted after a while if he wants (only go back for 3 months)
	- he wants to reuse them each year (unlist them for next year)
- set categories to air, fire, water, earth
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
- Make chats for other people that sound good, 2 to 3 people

- is there a contact form on the site? -> wp forms is on the site, but i don't have it set up or anything, does he want a contact form for it?

- ask him about the site linked in his book -> 4elementyoga.com does not exist, link to 4elifestyle instead, growing instead? 
- I don't think having a site specifically for just yoga is a good idea -> you already have so many sites, you don't want people who want to learn to have to go to 10 different sites
- look at the alt text on the images -> avoid lawsuits, I think we're in the clear images are used for window dressing, check on free web tester
- check login attempts 

- add a hover color to buttons -> the css isn;t working for some reason :( could it be a problem with the customize page in general?

- still doesn't automatically update :(, is it a problem with peepso?

- Add tiny habits section on why it works scorecard page, into read more section -> not a seperate page


On scorecard page
See if links have to be underlined all or nothing, or if links on scorecard page can be underlined, use inline text decoration, make it stand out on the page
Try a button?

See if there is a way to see how many people downloaded the scorecard, use google for site analytics - he needs a google workspace account for this


---- After meeting with Donovan, I’m thinking this:

People might respond better to a 30 day program; "Dr. W's 30 day program will help you jumpstart your holistic journey.”


We need link to our Youtube channel very present on home page and perhaps the promo page.
Perhaps in Youtube descriptions of each Quick Minute videos we’ll put in”Join up and get access to Dr. W’s free 30 day Holistic Learning Program.”

He felt that the Home page was a bit overwhelming to a first time person. Maybe put August’s Topic: on the top right and move the current right sided widget to below the left side’s 4E Story widget. -> i made different changes

-> Added score card to header, removed “have you downloaded your score card” widget
-> Added documentary to header under holistic growth, made that widget only visible on the promo page
-> Add a widget that links to the youtube channel?
- fix weeks away from learning program

---- Any thoughts?
30 day challenge stuff is on a new page /join, add a new button when ready


- Make quizzes optional, see if we can add some sort of reward for people who finish it
- Can we have people sign up to get an email once a day and other people once a week, different groups, email lists, starting at different times, chronological order when they join, everyday, every week , have them choose that, through peepso or learndash, or through a mailing thing, maybe constant contact, see if at allows chronological emails when you sign up
- https://www.constantcontact.com/blog/automated-welcome-series/ 15 emails every 2 days, look at core vs plus
- Promo page button switch ‘join our 30 day challenge’

- We will email you every other day with a link to a quick minute on youtube
- Put an image of the score card in so they can see it, on this page include the short lists of activities, with one paragraph of how to use it
completely changing promo page


- Figure how to add him to google analytics5
- THINK ABOUT moving the part above practical benefits into the first lesson
- 30 day challenge what makes it interesting is how we include the four elements into it 
- Work on 30 day challenge page, figure out how to put the 4 elements into it
- Make the learning program part of the challenge? Can be taken all in one day
- THINK ABOUT 4 corners page, is it necessary ? maybe remove pictures, put the topics in the monthly topics section?
- text for lessons maybe? side pages? from the promo page? 
--------------------------------------------------------
30 day challenge potential sentences:
****paragraph about why using the score card will help you live a more holistic life**** I'm not sure what parts to take from the intro on the scorecard page, it all seems useful ---- what makes our holistic program interesting is how we include the four elements into it---- our 30 day challenge is built upon each of the four elements---- as you move through the 30 day challenge you will learn
--------------------------------------------------------

- need to figure out the wordage of the challenge page to get people to sign up
- need to set up email, constant contact account + plugin, needs to be bought
- should fix section with 30 day challenge content on promo page
- set up analytics for other sites if he is admin for growing


Add spaces between bullet points on promo page bullets
For topic pages make first letter be capitalized, remove italics, nutrition already done
 analytics add him as an admin for other sites
Fix spacing and sizing of video
See if i can embed the arrow in practical benefits into the bullet list
still gettign emails for 4elifestyle
