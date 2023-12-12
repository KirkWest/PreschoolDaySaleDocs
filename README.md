# Kirk West-Sooby T3A2-Part A

## Links

## R1 Description of website, including

### - Purpose

The purpose of this app is to fill a need Adamstown Community Early Learning and Preschool(I'll refer to them as ACELP from here on) had with how they operate their buy/sell service for days. To go to ACELP you sign on to send your child on organised days for the duration of their [insert better word], this means that if you choose to go on a holiday or for have some absence that is pre planned the parent will be charged their daily fee regardless. ACELP has a procedure where parents can put up a day or more for sale where other parents may wish to buy and send their child for some extra days and taking over the financial responsibility. Usually this will be handled using word of mouth notifying the director/assistant director of their wish to put a day up for sale. By creating an app for ACELP that can handle this process would minimise their involvment and make this option far more accessible to parents whilst also making the process....[add in more].

### UPDATE:
Some small changes have been requested in how this will be set out, ACELP would prefer if possible to combine the buy and sell pages into one page, this should be possible and makes sense as the calendar would be able to hold both buy or sell buttons easily enough. 

### - Functionality / features

* Login as user or admin, both will require authentication to access.
* Create new user in the database that has to be reviewed by admin, this contains information on the days you currently go, the room your child is in, and also the parents information.
* Buy page with a calendar, the calendar will have a buy button on days that are for sale that will display the room that is for sale but no further information for provicy reasons. This button when clicked will remove the buy option and send an email to admin with the what user has bought this day for them to process.
* Display page with the ability to sell your available days (this info will be different depending on the user logged in) your days will have a sell button that removes the day and sends an email to admin to process.

### UPDATE:
ACELP has requested the buy and sell pages be combined onto one calendar, this will display a calendar that will display "sell" on the days their child goes to ACELP and "buy" on days that are optional to be bought.
At this point they have requested to have full control on removing and adding the buy days once reviewed and removing the parents log in. As such the design will now have the function of clicking on a day to buy or sell, this will open up an email box where the parent can write in their information and their wish to buy/sell a day. We have talked about the possibility of adding back in parents as users at a later date if they are happy with how the app runs after is has been in use.

### - Target audience

The target audience for the app is both Early childhood centres as well as the parents of children at these services. Whilst this app will be personalised to ACELP, it could be used by any early education centre with some customisation to the front end design.

### - Tech stack

* Git
* Github
* HTML5
* CSS
* ReactJS
* ExpressJS
* Node
* MongoDB
* Trello

## R2 Dataflow Diagram

## R3 Application Architechure Diagram

## R4 User Stories

* Persona 1 - Deborah, Admin for ACELP:
Deborah is the admin for ACELP, among her many tasks is overseeing the requests to buy and sell days before passing them onto the assitant director to ok as well as update the payments from one parent to another. She would like a system in place that can take care of her role as the middle man receiving these requests and sending them onto the assitant director. By having her section automated it would free up her day for addition tasks or to take more time off work to spend with her family.

* Persona 2 - Assistant director Sarah:
Sarah shares everyday tasks with the director, one of these tasks is to ok the buying and selling of days and organising the rooms around children numbers and staffing. Sarahs main interest in this app is to have a safer more secure system of keeping track of the buying and selling of days as atm the it is passed on by word of mouth. By moving this online it creates a smoother workflow not having to rely on Deborah to pass on the wish for selling/buying a day.

### UPDATE:
Sarah has asked for some changes to how the app will work, first she would like the buy and sell pages to be one page, second she has requested that we remove parents log in for now and leave it as just an admin log in. Sarah would like to see how the base app runs for a while before potentially adding in user logins and other future functions like automatic removal of a day once bought. Her reasoning is ACELPs staffing and organising of rooms is a delicate process, with staff going on holidays or being away sick ratios of teachers to students have to be kept at a lawful standard and the ability to not fill a day of a child being away might be necessary on occasion.

* Persona 3 - Parent of Jack, April:
As a parent sometimes it can be chaotic remembering this on pickup/drop-off, by making this app she would be able to log on and sell or buy a day at anytime instead of trying to catch Deborah or check the board at work notifying parents of possible days to buy. Although this will still have to come under review it would then be up to the ACELP assitant director to follow up with the parent thus taking the pressure of the parent to remember.

## R5 Wireframes for multiple standard screen sizes, created using industry standard software

## R6 Screenshots of your Trello board throughout the duration of the project
