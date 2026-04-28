# Drws_site
everything to do with drws site

January 2026: 8 hour 30 min -> recieved

February: 7 hour 45 min -> recieved

March: 8 hour 30 min

April: 11 hour 30 min

plugins im using on site:

- peepso -> auto updates still not working, caused by something in the backend? still not working the way they should
- learndash 
- real simple ssl 
- Forget About Shortcode button 
- aksimet
- total upkeep
- widget context
- siteground security and speed
- code snippets -> needed for google analytics
- autoptimization (not css, messed it up really bad) - not using it anymore
- w3 total cache - not anymore
- layout grid block
- wp-staging -> deactivate when not in use
- wp-forms -> contact page
- File Upload Types -> allows epub to be added to media library
- wpforms
- admin columns

https://www.ssllabs.com/ssltest

copy of redirect exceptions: 5070,frontpage,4222,4507,4460,2080,2627,20,3866,5443,5156,5050,5344,2586,351,5451,6132,6141,350,2611

speed test:
https://developers.google.com/speed/pagespeed/insights/

https://web.dev/measure/:

Notes:

	- with gecko theme in editor main background photo is set in theme -> body settings
		- need to put separate background pictures into additional css
		- figure out how to make pictures scroll -> change to scroll
			- normal pictures can just be put in using image in page builder
	- in peepso logo height has to be in px, not %
	- non-members cannot get access to courses, can view the headings 
	- **make sure to use peepso login and log out, not pmp login and logout**
		- capitalize the element names everywhere
	- using pixlr for basic photo edits
	- used photo editor for flavenoids picture, font = fresh
	- for admin email change "Settings"=>"General"=>"E-Mail Address". set to mine now, hopefully he fixes the other sites email address thing
	- nothing on site can be hidden from administrators
	- current font sizes should continue on through the site
	- Manager of youtube now also -> can change/add etc videos and everything
	- page redirect completely turned off
	- four corners page is a draft now
 	- constant contact test email have the email of the account owner at the bottom, the actual emails don't
	- The 4 vs. fours
		- 4 for 4 element yoga
		- 4 for 4 element lifestyle
		- 4 for 4 element renewal system?
		- Four for four element self assessment
		- Four for Holistic four element course
		- Four for Four element doctor
  	- to change an edited image, after editing go the the page and replace it with another then switch back
   	- recheck that constant contact is connected to the site every month or so, just look at lists in backend
    	- constant contact makes people choose which list to join if there is going to be more than 1 that they are added to, so only add them to one
	- changing the footer not necessary
	- talk about popups again in 3 months
--------------------------------------------------------

- google doc for emails:https://docs.google.com/document/d/1Nc_WVsgZKdhpWaHZyDn81rw4y02Dlj2wB-O-q9ZnJXs/edit?usp=sharing

For Emails:

	- Should focus on links and description, recipe?, seasonal blurb, makes sense to send it once a month
 	- set up the automated emails, only one per list
	- Have 2 email lists,everyone added to both have the wellness check send after one day, then after 2 weeks have the 30 day challenge send
		- With a link or copy of posts from social pilot 
	- Video would have a link
	- Text post could stand alone, or have the beginning (read more) and a link to the rest


When app is ready:

	- The Recalibrating Your Balance App – Phone/PC/Mac compatible – earn redeemable points as you develop a good health-building, life-renewing routine – coming soon
	- Make a slide
	-  put page under programs tab in header
 	- add it to patreon
  	- another site?

list of redirect exceptions:
	- frontpage
 	- nutrition & you
  	- yoga & you
   	- links to dr w's videos
    	- products page
     	- others


 
- For fourelementinstitute and syracuse natural healing the security plugin caused a lockout again, look into getting a new one

- https://www.youtube.com/@LeadingOurOwnWay/videos podcast link

6/27
- Add some lesson chats, at least 2 for each level
- 	6
- 	7
- 	8
- 	9

For next week:

- Fix the footer image -> need a new footer image that is a lot bigger, the width should be as wide as my screen and the height should be as be as long as the footer is in cellphone view

- Think about making the peepso site need people to join for $, not yet but maybe in the future, don’t do it until i get the green light from him
	- Will need to setup the payments
	- Will need to add the lessons
	- Will need to make groups 
- he is considering selling lessons

BOOK STUFF
- He will send me a new copy of the book with the new cover, put it on  https://growingholistically.com/free-book-sample/ 
- When i get the new file have the cover, the copyright page, the preface, the table of contents, then the preface, and all of chapter one of the book
  Add partial book page to the freebies menu
- Make the book sample file longer, so it doesn’t need to scroll on desktop
- Switch the book file in the pdf copy in woocommerce when i get it, he is not selling the old one anymore, i will get in in about 3 weeks
- When I get the new book, remove the old one from the store? Including the physical copies?
- Is it going to be a soft cover for the physical copies? yes
- When it's ready you want me to remove the old book from the site completely, correct? Not keep the physical copies up? Replacing it
- 2 books now, book 1 is a shorter version, 
- Pdf is ready
- Blurb contact?

7/10
- Look at the "Force From Email" setting enabled in the WP Mail SMTP plugin. It makes 4Eins. Emails come from a weird email, figure out why the institute emails aren’t working correctly



11/13
- Add a sentence for each lesson
- Look up what user activity by cohort means on google analytics, 
- add the four element doctor gmail to the google analytics page

1/22
For next week:
- update social media calendar woth emails and the podcast
check and see if the quizzes go through to the info for non adminstrators, new lesson

2/12

For next week:
Fix the margin/spacing on https://syracusenaturalhealing.com/podcasts-with-dr-w/ 

Learndash questions / confirmations
You wanted the learning program available to everybody 
You wanted the learning program quizzes available to only people who are signed in
You wanted the SRS first 3 available to anybody, lessons and quiz
You wanted the SRS 4 + available to only people who are signed in


3/5
For next week:
The php upgrade started causing a problem for the site yesterday, i have put it back to 8.1 to figure out what the issue is. I'm actively working on it. The front end of the site was fine, but it prevented working in the backend of the site. I think it's a plugin update issue? 
 I don’t know if it's related, but is the gecko license is wrong? It says its invalid, that started this morning, im still looking into that https://peepso.com/profile/?hwalsdorf/edd/licenses/ it says that it should still be good until February next year
He just paid for it? 
-> sent in peepso ticket, no response as of 5 pm wednesday
-> tehy said it was caused by paypal communication wrong



See if quizzes are tracked for the SRS, doesn’t appear to be

3/19
For next week:
Adding a paywall back to GH
Make a coupon code for patients, as they sign up they will need to use it
“DrWPatients”

My job is to integrate it into the site, maybe downloadable feature, maybe just on the site


4/9
For next week:
Set up payment processors another time
Fix front page, its not going to be free anymore

4/16
For next week:
Start preparing a page for the app from the site, + slides etc

Fix the front page, it's not going to be free anymore, how much? 
$5 a month $40 a year for the site
Write it everywhere, 
Make sure to remove the frees, except around the code 

PMP still not working


new to do list:
https://docs.google.com/spreadsheets/d/1XZiBz1Z-8vM59BIuiMeroBYs2-pwb8oSRBjm3BCT9go/edit?gid=0#gid=0 
look at otherplugins
