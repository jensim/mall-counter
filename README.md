# Mall counter
Just an idea!
Count people in a mall, to reduce queueing and crowding

In the time of covid-19, crowding is a real issue. And the branch org of swedens retail stores just annonced that they will make zero adaptions for 2020 xMas sales in regargs to lessening the spread of the pandemic classed virus known as covid-19.

The goal for a project of these ideas are the following

* one-click to create a new deployment of a mall using heroku deploy-button feature  
  * It has to be DEAD simple to get a mall owner to test this. 
  * Each mall will own its own data
  * It has to fit in a free-tier of heroku
  * Its a safety-aspect as well - no need to put all the eggs in one basket for hackers to have a field day
  * The ease of setup and slim start-up should make this tolerant, if the system got hacked, it should be easy to toss out and make a new installation
* set up for admin in landing page on first enter
* one-time-password links to create stores, send to store-owners in mall
  * one-time-password links to create attendee accounts
* admin pages
  * [stretch] each level in the hierarchy can manage invite new users to it's own level in the store-hierarchy
  * [stretch] only users above another may delete/revoke another
  * [stretch] reverse tree-view of who invited who
  * [stretch] tree view of users and and number of invites made
  * [stretch] tree-revoke users, in case unauthorized users manage to get a hold of a account
  * 
