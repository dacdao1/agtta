# AGTTA.org new and improve website

This is the new version of AGTTA.org (Atlanta Georgia Table Tennis Association) which was created with WordPress as the front end framework. The goal is to move the current website information and data over to a newer design with the use of Vue.js framework. The information and data will be easily updated for future users that are maintaining the website for the organization.

## What need to be fix with end user requirement

The last person that created the website use a WordPress plugin to create the layout and then input in the information. The website itself is responsive but there are several flaws within some of the functionality of the website. Below will be the requirement for the end use and also fixes on some of the functionality for the website.

**Fix and end user requirement**

-- HOME PAGE
- The search bar is currently not working
- On the homepage, the "follow us on Facebook is not linking to the Facebook group"
- The ticker on the home page is moving slowly with several different sentences, this need to be shortened or appear different to the user (UI fix)
- YouTube video need to be an iframe on the website so that the user doesn't have to click the link and then transfer to YouTube.
- Stories event are appearing closely to each other and there is not a date for each stories.
- Pictures are close together and there isn't any separation. (UI fix)
- Certification logo is small and not located high enough on the page.
- Donate logo is too small and at the bottom of the page.
- End user would like to have a signup option so that people can register for league plays on Tuesday and Sunday. Once the number of registers are at 45, then the system will close out. After a certain time, user will not be able to register but giving a phone number to contact Brian Crisp.
- Archive each years of information and user can click at certain YEARS to see events happening within those years.

-- ABOUT PAGE
- The google map is not working correctly, it is showing "for development purpose only" and not showing how user can use it to get direction to the facility.
- Make sure the information is clearly shown and not cluster (UI fix)

-- LEAGEUE PAGE
- Retrieve data from tabletennisleague.com to display on the AGTTA website, so user doesn't have to click to a different website.
- NOTE TO SELF, ASK BRIAN CRISP ABOUT TABLETENNISLEAGUE.COM, mostly how to retrieve data from that dataset.

-- TABLE TENNIS COACHING PAGE
- Have a better layout for the coaches, (maybe a design were each coach will have their picture, once the mouse hover over them, then a text box will appear with their description.) (UI fix)
- Have a MEETUP link to schedule free coaching on Sunday for beginner or have free play for players to come and play.

-- LINKS PAGE
- Have a better layout for each links on this page, or have it at a different page. I don't know where to put it yet, but will find a place for all of these useful links.

-- LEADERSHIP PAGE
- Let have pictures and useful information for each person within the organization.
- Have this page merge with the ABOUT PAGE, so that we can have a lot less pages link on NAVIGATION

-- TOURNAMENTS PAGE
- This page is not organize correctly, there is just links and flyers and entry form but not anything that the user can work with.
- ASK BRIAN CRISP ABOUT OMNIPONG WEBSITE, who runs it, can user create their own account through AGTTA website and register through AGTTA.

-- SPONSORSHIP PAGE
- Have a better sponsorship page that separate each sponsorship. For sponsor to register or send an email, let them use a contact form so that sponsors can send email directly to Brian Crisp.

## The development process

Each page will be develop per fixes and user requirement. Each fixes will go through the "feature" branch, once a page is done, it will be merge into the "dev" branch. Each "dev" branch version should be a page completed. Once each "dev" version are tested, then it can be merge back into the main or "master" branch. "Bug" branch will be created ad hoc as bugs should be fix as the developer are creating each requirement/fix.

## Development.

July 29th - Creating README for information page, fixes and requirement, development process, development and testing. Create different branch for developer to work on. __Future task__: install Vue.js in local machine to start working on the overall template of the website. 

## Testing.
