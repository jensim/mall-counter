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
  * Manage number of allowed customers in total in the mall
  * [stretch] each level in the hierarchy can manage invite new users to it's own level in the store-hierarchy
  * [stretch] only users above another may delete/revoke another
  * [stretch] reverse tree-view of who invited who
  * [stretch] tree view of users and and number of invites made
  * [stretch] tree-revoke users, in case unauthorized users manage to get a hold of a account
* Time customer
* Limit number of stores
* Anonumus enter
* Anonumus exit
* Work with any bar code or QR
* Guest feaures
  * queue system
    * [stretch] Queue outside store feature that allows people to spread out over greater area or do other chores "in line"  
    Also a thing for queue to shops inside the mall
      * Place in line
      * Guess time based on
      * Exit line
      * Push notification
  * List all shops and length of queue 
* Conserve battery on phones
  * Dark mode by default
  * ? photo mode > video mode scanner  
    Might not be quick enough!


# In practice
<a href="docs/scan barcode.svg">
  <img src="docs/scan barcode.svg" width="250" />
</a>

## Customer perspective
* Customer arives at store
* Attendant scanns a sticker with a random/sequence barcode on it  
and hands it to the customer with instructions to wear it visibly, it is mandatory to enter any butique or be served at café.
* At each store, there may be a queue, each entered customer may stand in one line, by scanning his/her code with the store attendee or mounted device  
or by entering the queue with the guest page
* Warn consumer when time is soon up

## Attendant perspective
* Get link sent by store owner
* or scan coworkers qr-share-link
* Next customer in line comes 
* Scan
* Give barcode 
* Inform
* Smile & wish a merry pandemic
* Repeat
