# Kirk West-Sooby T3A2-Part A

## R1 Description of website, including

### - Purpose

The purpose of this app is to fill a need Adamstown Community Early Learning and Preschool (I'll refer to them as ACELP from here on in the documentation) had with how they operate their buy/sell service for days. To go to ACELP you sign on to send your child on organised days until they graduate or the parents leave the service. This means that if you choose to go on a holiday or for have some absence medical or otherwise the parent will be charged their daily fee regardless. ACELP has a procedure where parents can put up a day or more for sale where other parents may wish to buy and send their child for some extra days and taking over the financial responsibility. Usually this will be handled using word of mouth notifying the admin/director/assistant director of their wish to put a day up for sale or to buy one. By creating an app for ACELP that can handle this process it would show a more professional front whilst also making it cleaner and more efficient for the admin/directors to organise and keep track of.

### - Functionality / features

Here is the most up to date functionality and features section, I have left the previous two versions at the bottom with a heading of "outdated functionality / features to show how this app has gone through some changes over time as I have kept in constant communication with the client involving their ideas and wishes.

### - Up to date funcitonality / features

#### Landing page

Admin login -

* admin users can log in using their credentials which will be authenticated through JWTs.

Non-admin users (parents) -

* Non-admin users can bypass the login section and proceed straight to the calendar page.

#### Calendar Page

Non-admin -

View calendar

* All users can view the calendar on the this page

Buy Button

* Certain days will have a "buy" button displayed on them.
* Users can click on the "buy" button which opens an email input with the subject of "Buy" and a prefill of the information they would be required to input such as "please state you name, child, email, and wish to buy this day in here please". This will email the admin at ACELP with their wish to buy this day.

Selling a day

* All days will have the option of being clicked on which will open an email input exactly like the buy button function except this wiull have the subject of "Sell". This will email the admin at ACELP with the parents desire to sell this day.

Admin -
View calendar

* Admin once logged in will view the same display of the calendar as non admin users.
* Admin will have additional functions on the page, which will involve the ability to add in buy days they have reviewed and accepted from parents wishing to sell, as well as the ability to remove buy days they have reviewed and accepted from parents wishing to buy.

#### - Outdated functionality / features

* Login as user or admin, both will require authentication to access.
* Create new user in the database that has to be reviewed by admin, this contains information on the days you currently go, the room your child is in, and also the parents information.
* Buy page with a calendar, the calendar will have a buy button on days that are for sale that will display the room that is for sale but no further information for provicy reasons. This button when clicked will remove the buy option and send an email to admin with the what user has bought this day for them to process.
* Display page with the ability to sell your available days (this info will be different depending on the user logged in) your days will have a sell button that removes the day and sends an email to admin to process.

#### UPDATE

ACELP has requested the buy and sell pages be combined onto one calendar, this will display a calendar that has a "buy" button on days that are optional to be bought.
At this point they have requested to have full control on removing and adding the buy days once reviewed and removing the parents log in. As such the design will now have the function of clicking on a day to buy or sell, this will open up an email box where the parent can write in their information and their wish to buy/sell a day. We have talked about the possibility of adding back in parents as users at a later date if they are happy with how the app runs and feel like expanding on the capabilities.

### - Target audience

The target audience for the app is both Early childhood centres as well as the parents of children at these services. Whilst this app will be personalised to ACELP, it could be used by any early education centre with some customisation to the front end design.

### - Tech stack

* Git
* Github
* HTML5
* CSS
* ReactJS
* Express
* Node
* MongoDB
* Mongoose
* Trello
* Netlify
* Heroku

## R2 Dataflow Diagram

Please see below links for the Dataflow Diagram, local is in the docs folder and external is to lucid.app link website where the diagram was made.
[daysale DD local link](docs/Dataflow%20Diagram.png)
[daydale DD external link](https://lucid.app/lucidchart/2fb5c618-884e-4232-9ce3-d152ba344f5b/edit?viewport_loc=-1974%2C-424%2C2889%2C1488%2C0_0&invitationId=inv_ef818bee-6dee-40d4-b1b3-c6b90f26377e)

## R3 Application Architechure Diagram

Please see below links for the Application Architechure Diagram, local is in the docs folder and external is my google drive link.
[daysale ADD local link](docs/daysale_ADD.png)
[daydale ADD external link](https://drive.google.com/file/d/1HKSgHBO7ufA4vtlGnjLPExuKqPw_Sc1i/view?usp=sharing)

## R4 User Stories

### Persona 1 - Deborah

* Age - 54
* Role - Admin/secretary
* Wishes - Lighter workload

What:
Deborah is the admin for ACELP, among her many tasks is overseeing the requests to buy and sell days before passing them onto the assitant director to ok as well as update the payments from one parent to another.
She would like a system in place that can take care of her role as the middle man receiving these requests and sending them onto the assitant director.

Why:
By having her section automated it would free up her day for addition tasks or to take more time off work to spend with her family.

### Persona 2 - Sarah

* Age - 31
* Role - Assitant Director
* Wishes - A more professional way to keep track of days to be sold

What:
Sarah shares everyday tasks with the director, one of these tasks is to ok the buying and selling of days and organising the rooms around children numbers and staffing.

Why:
Sarahs main interest in this app is to have a safer more secure system of keeping track of the buying and selling of days as atm the it is passed on by word of mouth. By moving this online it creates a smoother workflow not having to rely on Deborah to pass on the wishes of parents to buy/sell a day.

Updates to Sarahs User Story

Sarah has asked for some changes to how the app will work.

What:
First she would like the buy and sell pages to be one page, second she has requested that we remove parents log in for now and leave it as just an admin log in. Sarah would like to see how the base app runs for a while before potentially adding in user logins and other future functions like automatic removal of a day once bought.

Why:
Her reasoning is ACELPs staffing and organising of rooms is a delicate process, with staff going on holidays or being away sick ratios of teachers to students have to be kept at a lawful standard and the ability to not fill a day of a child being away might be necessary on occasion.

### Persona 3 - April

* Age - 34
* Role - Parent of Jack whom goes to ACELP
* Wishes - An easier and more convenient way to inform ACELP of wanting to buy/sell a day.

What:
April would like a more convenient way to inform ACELP of her wishes without having to remember at drop off or pickup.

Why:
Drop off and Pickup can be a chaotic experience, April finds that she often will forget to inform admin of a holiday coming up so she can put a day up for sale, and she almost never remembers to read the board at ACELP that gets updated with days that are for sale to potentially buy.

## R5 Wireframes for multiple standard screen sizes, created using industry standard software

The wireframes for this app have been created on figma, please see below links to pdf version as well as figma link.

[Daysale local landing page](docs/wireframe%20landing%20page%20view.png)
[Daysale local calendar page](docs/wireframe%20desktop%20calendar%20page.png)
[Daysale local email popup](docs/wireframe%20email%20popup%20view.png)
[DaySale Figma link](https://www.figma.com/file/dj7vzg7QrmdbqyP7YoKwIx/DaySale-Wireframe?type=design&node-id=0%3A1&mode=design&t=tF4algAzgBIe4Dnq-1)

## R6 Screenshots of your Trello board throughout the duration of the

### Planning methedology

The planning of this project has been tracked through Trello, I created 4 lists:

* To-do,
Here I put in the 6 cards of the rubric to keep track of each section, inside these cards I put a short description of what is to be done with a basic rundown. Each card starts in the to-do list until I proceed to start each section.

* Doing
Here I moved each card as I began work on them, I would update the cards with a short comment on what I have done and and what may need my attention to alter in the future. I also added in comments whenever a change has been requested to keep a track of what is being done or changed and why.

* To review
Here I would add in my cards as I had completed them, this isn't the final stage as this list will prompt me to give cards closer scrutiny a few days later with fresh eyes. I may have added in commments if things have moved back into doing from the review section if I found any issues or things I needed to tidy up.

* Complete
Here I have moved each card to once I had completed them and had gone through the review process. Things shouldn't be moved from complete to any previous section unless something in the design and of the app had changed since completing.

Links to Trello screenshots as well as my trello board below:

[Trello progress screenshots folder](docs/Trello%20screenshots/)
[Trello board external link](https://trello.com/invite/b/FobzW5wT/ATTId65705f188e72cf20b9fc54996141c5dD69B2B13/preschooldaysale-documentation)