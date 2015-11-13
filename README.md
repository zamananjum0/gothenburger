## What's This All About?

Learning by doing!  Specifically, by trying to remember and put into practice the things covered during my time at Makers Academy.  And to keep pushing and extending my learning!

## What's Gothenburger?

Gothenburger is a proprietary project of mine that I am working on individually while a student at Makers Academy.  The ultimate purpose of Gothenburger is to help people find the “best” burger (for them) in Gothenburg, Sweden (for now).

Since I want to maximize (1) learning and (2) quality, and I won't be able to complete the application in one week, which is the time I have to work on it before my parents come to Sweden to visit us, I will only try to complete one part of the app, the administrative part of the application.  Why?  Because admin-facing apps important (even if they're not sexy).  And I've already worked on multiple customer-facing apps, so why not.  Plus, I like to be different (even though it entails costs)!

## Key MMVP Features -- NEW

* Sign-up and Sign-in Restaurant Owners.
* Restaurant Owners can create Restaurants.
* Restaurants have profiles.
* Only Restaurant Owners can edit Restaurant Profiles (only ones that they own).
* Restaurants have many Burgers (and Burgers belong to Restaurants).
* Restaurant Owners can create Burgers
* Burgers have profiles.
* Anyone can search for and view Burger profiles.
* Restaurant Owners can edit Burger Profiles (only ones that they own).

## Key MMVP Features -- OLD

* Sign-up and Sign-in Customers
* Customers have profiles.
* Customers can Like, Rate, and Comment on Burgers and Restaurants.
* CRUD Admin Users (via Rails console).

## User Types

While the MMVP will only have two types of Users, future versions of the app will a more complete set, such as:

1. Site Owner: Can do everything, plus CRUD/assign/revoke Site Admins.
2. Site Admins: Can do “everything” except things that only the Site Owner can do (money, etc.).
3. Restaurant Owners: Can do everything Restaurant Admins can do, plus CRUD Restaurants and CRUD/assign/revoke Restaurant Admins.
4. Restaurant Admins: Can edit the Restaurant-related data for their Restaurant (profile info, menu info, etc.).
5. Moderators: Can moderate User Generated Content (UGC) and block/unblock Users and IPs.
6. Customers: Can do everything Visitors can do, plus do things such as rate and comment on burgers and restaurants.
7. Visitors (i.e., unregistered users): Can search, filter, sort, and sign up as Users.

## Bonus Feature Ideas

* Customers can Follow Burgers, Restaurants, and other Customers.
* Automated anti-spam feature(s).
* Integrate Maps and Reservations, such as using Google Maps API and OpenTable API.
* Integrate other APIs, such as Yelp, FourSquare, Facebook, Twitter, Instagram, SnapChat.
* Settings and options.
* Internationalization.
* Recommendations (algorithmic).
* “Editor” reviews, ratings, and photographs.
* Beefed up profiles, such as details about ingredients and practices, such as if they grind their own meet on premises, where they get it, is it ecological, etc.  Ability to search/filter.
* Deals and Groupons.
* Advertising and Promotions (brand and targeted, including re-targeting, poaching, etc.):
  * Site-wide.  Example: Sponsored Listings at top of Search Results page.
  * To Followers.  Example: coupons via email, push, or SMS to Followers.
  * To nearby people.  Example: Restaurant Admins create, activate/deactivate location-based promotions to fill empty tables, such as at off-peak times.

## Good, Fast, or Cheap?  Pick Two.

The plan for this project is to hold Time, Budget, and Quality constant while letting the Scope vary.  That makes sense here because Time *is* fixed (November 20th deadline) and Budget *is* fixed ($0.00).  The quality target is also fixed (High), bearing in mind that "High" is a subjective and relative term (i.e., High for a beginner is different than High for an Olympian, and High for one person or company is low for another).  That leaves Scope to vary.  And so it will!

## Project Management / Software Development

A lightweight, lean/agile approach that I call "Scrum-flavored Kanban sprinkled with XP, with a side of Lean Startup."  What's that mean?  Kanban that's influenced by parts of Scrum, XP, and Lean Startup:

* Scrum: Cross-functional, self-organizing teams.  Conversations and retrospectives.  No sprints or story estimation (i.e., story points or time).
* Kanban: Flow, limited WIP, and card counting.
* XP: User stories, test-first, pair programming, refactoring, and continuous integration.
* Lean Startup: Build, measure, learn cycles (multiple overlapping cycles of various lengths).

## Project Management / Software Development Tooling

While I typically prefer paper, pen, and a physical board, for this project I will test out www.kanbanflow.com, a tool made by a local guy I met at the excellent [Brewing Agile](https://brewingagile.org/) conference.

I am using Blue and Green cards for User Stories, Yellow cards for Tasks, and Red cards for Bugs.

The columns are as follow:

* Icebox: One-line ideas for "maybe someday."
* Backlog: Semi-prioritized list of one-line things we want to get done before the project's Finish Date.
*On Deck: Discuss and write User Stories that meet the [INVEST](https://en.wikipedia.org/wiki/INVEST_(mnemonic)) criteria.  Assign to team member.
* In Process: What's being worked on right now.
* Verification: Pull requests, code reviews, CI, staging, customer acceptance, etc.
* Done: Deployed to production

## Key Project Dates

* Start Data: Thursday, November 12, 2015
* Finish Date: Friday, November 20, 2015

## Key Technologies Used

* Backend: Node.js
* Backend: Ruby on Rails
* Database: PostgreSQL
* Frontend: AngularJS
* Hosting: Probably Bluemix or Heroku
* Styling: Bootstrap
* Testing: RSpec, Capybara, Jasmine, Protractor, maybe Teaspoon

## Tests and Continuous Integration (coming soon)

TDD/BDD with unit tests, integration tests, and CI.

## Run Gothenburger Locally (coming soon)

````
$ git clone git@github.com:chrisco/gothenburger.git && cd gothenburger
$ bower install
$ npm install
$ open index.html
````

## Try It Online

Coming soon

## Get the App

Coming later
