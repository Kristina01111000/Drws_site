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

Hours worked July: 7 hour 20 min -> recieved

Hours worked August: 9 hour 15 min -> recieved

Hours worked September: 11 hour 15 minutes

Hours worked October: 5 hour 15 min
 
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
	- make quizzes for each lesson need to do lesson 2 and 3

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
	- yearly scorecard ink: https://docs.google.com/spreadsheets/d/1IxK22ihszAVXQgxLD9di-MhoP3kERT8SlfXiGddOmhc/edit
	- check names of lessons on promo page when new youtube video is dropped
	- Monthly topics will be articles now, not a class
	- page redirect completely turned off, might be that way now for sure
	- four corners page is a draft now


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
	


to do now:

- Make chats for other people that sound good, 2 to 3 people
- look at the alt text on the images -> avoid lawsuits, I think we're in the clear images are used for window dressing, check on free web tester
- check login attempts 


See if there is a way to see how many people downloaded the scorecard, use google for site analytics - he needs a google workspace account for this

- Can we have people sign up to get an email once a day and other people once a week, different groups, email lists, starting at different times, chronological order when they join, everyday, every week , have them choose that, through peepso or learndash, or through a mailing thing, maybe constant contact, see if at allows chronological emails when you sign up
- https://www.constantcontact.com/blog/automated-welcome-series/ 15 emails every 2 days, look at core vs plus
- We will email you every other day with a link to a quick minute on youtube

--------------------------------------------------------
 analytics add him as an admin for other sites -> check

scorecard link:
https://docs.google.com/spreadsheets/d/1boqAM_8NBEV09Uq_KDDhTZ4vUAS0WwAquNfRpROXE64/edit#gid=1517792507
He is making more changes to the scorecard

After finalizing scorecard :
- Put 31 days in the months not the first one on scorecard, he’s going to put tips in
- Fill in the days of the week in the monthly calendar for the scorecard months
- Change it to date in column 3 row 1 for the monthly one
- put the months in the other tabs

- go through the pages and delete the old/extra ones
- need to buy constant contact -> then set up the emails for the 30 day challenge

- need final check for the score card


Feedback from client

- Add a question with a bunch of answers that match up to the elements is this possible in peepso
- Try it in quiz 1 first to see if it is good

- See how to see all member data from peepso at one time -> is it even possible? -> look under users, or under manage 
- Will be emailed other questions for quizzes from ben
- he wants 10 questions per quiz
	- quizzes that have 10 questions: # 1,

- he is having an issue with the link to the scorecard on membership signup page -> chrome and safari only, he needs to clear cookies, maybe turn off sitegroudn? clearing cookies didn't work, try to fix the issue one more time, then try peepso, didn't work for me in chrome, started  aa ticket with peepso
still waiting on them, update him didn't have a pmp shortcode on the registration page


- he wants to make access to the scorecard easier
	- added a new scorecard widget
	- added link to scorecard page to registration email
	- this will be partially fixed by the constant contact email chain


maybe check ssl? it looks like it doesn't work in chrome -> server test says its ok, grade: a


- Get a book on amazon with pictures and see what it like, do they give options, if so get epub look at the options they offer, small places,big difference is that the words on the page change when the screen is flipped, pictures kind of move with them, if the picture is on a wierd place on the page is makes the text go to the next page.
- See if i can edit the shortcode[pmpro_confirmation] to get rid of the multiple thank yous
- Update on promo page video
- Ccholistic1! For constant contact hwalsdorf@earth
- Get the constant contact stuf fset up
- Fourissimo club email + page editing
- check on bens account confirmation
- make sure he understands why we need a google doc

for constant contact call:
site premise is giving users skills and information so they can liv a healthier life
the first thing we want users to do is try the "30 Day challenge"
when they join the challenge we will use the automated email series to keep them on track with the challenge
the emails will be everyother day for the 30 days, and will include links to videos on the youtube channel as well as brief advice snippets 
- he wants me to be on the call :(

still getting emails from 4elifestyle
