# Drws_site
everything to do with dr w's wordpress site

 Hours worked this month: 14
 
plugins im using on site:

- peepso
	- removed video plugin (it had malware in it), maybe put back in the future 
	- maybe remove email plugin?, it doesn't appear to add anything that we need 
		- if it does I can't get it to work
- learndash 
- paid memberships pro
- real simple ssl -> would upgrading fix the issue?
- Forget About Shortcode button 
- aksimet
- total upkeep
- widget context 
	- for choosing which pages widgets appear/ not appear on -> really like it

https://web.dev/measure/:
- resize images
- check image loading
- server response time

Currently working on Dr. W's site

- with gecko theme in editor main background photo is set in theme -> body settings
	- need to put separate background pictures into additional css
	- figure out how to make pictures scroll -> change to scroll
		- normal pictures can just be put in using image in page builder
- in peepso logo height has to be in px, not %
- he uses inmotion web hosting
- auto updates work now
	- not wordpress itself -> probably want to keep it this way 
- non-members cannot get access to courses, can view the headings 
 	- fixed it in learndash settings, still can't figure out peepso setting

To Do:

- ssl not working in safari, silk browsers
	- works in firefox
	- certificate chain issue -> fixed (ssllabs.com)
	- right now, no sni, looks like inmotion issue?
	- waiting on check
- change default user image
	-https://www.peepso.com/documentation/assets-overrides-customizing-peepso-images/ 
	- explains how to do it, need to figure out the default images we want
- test email plugin -> set it to go out @ 4 today, 
	- did not go out, need to check whats up
	- figure out how to force send one, peepso confirmation email works
	- error shows up in the site health status page, still not working
	- will need to contact peepso support
	- maybe set learndash email system instead?
		- on opening of new section and update to weekly topics?
	- talk it over with dr w
	- automatic one for sign up works
- figure out how to get patients into it using pmp -> main focus
	- see if there is a link system or something else
- add picture to wordrs from dr w
-  new email topics:
	- does he want articles in monthly course? or as articles? 
	- talk about button shape -> starburst a bad idea looks old


Need from Dr. W:
- to check ssl on his computer
- using paid membershippro 
	- set up free account for plugin -> in his emails name, need to pay for a support license fee
	- set up 2 groups (patients + paid) $29
	- still in testing only mode, change when ready for site to open
	- change email associated with checkout, what does he want? -> set it to admin for now
	- check on auto generated emails from pmp
	- ?make different url for patients group?
- score card stuff(added sentence to monthly topics, need info on everything else)
	- just an excel file i think? google doc?
- sent email to him with what he needs to do to get site running (he says he will get back to me tomorrow)
	- ssl still not working right on his old computer?
	- a video for the beginning of the front page 
	- patients page video
	- a video for words from dr w section, do you still want one here?
	- Do you want another picture of yourself for the  words from dr wsection? or just the video
	- list of what month each monthly topic will be in
	- do you have a video for the beginning of the front page
	- do you have a video for words from dr w section, do you still want one here?


From Dr. W:
     




The green hot links work for me

How does the membership plug into the registration? Is there a discount code that a patient could have to allow them to use the existent registration form, or should we have a different page that they could be linked to from an email from me?
