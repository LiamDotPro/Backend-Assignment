# Backend Assignment

Welcome to your assignment,

Let's start with some general house rules for this assignment:

1) This assignment should take no longer than 4 hours, in general it is completable in much less time but if you require longer please take your time.
2) You should follow the specification as much as possible, if you decide to modify or change something please make a note of it and submit it alongside your code in this read me under `Comments & Modifications`.
3) Please try to keep in mind this assignment is scored based on good well documented production ready code, please don't include anything experimental or obviously not production worthy.
4) Anything you submit might come back in a code review, so be ready to defend anything you submit (This doesn't include code copied from stackoverflow to aid in finishing the assignment).

Once you've finished the assignment please email a link to the *publicly accessible code*, so a team member can check it out.

**The final submitted code must work by default, if there are any additional setup steps required to run the project please make notes under comments & modifications telling the reviewer how to run the project**

# The Assignment

You'll be creating a small minimal poc repository that loosely matches the kind of projects you might end up working on. You'll be setting up crucial dependencies inside your project and then you will be required to create two endpoints that perform different operations.

### Part 1 - Configuration

1. Fork or Clone this repo into your own account on https://github.com

2. Run a local sql database using docker, include docker setup commands in a separate file or add a compose for bonus points.

3. Setup the Serverless Framework https://www.serverless.com/

4. Setup the Serverless Offline Utility https://github.com/dherault/serverless-offline

5. Add compilation for Typescript to your project.

Note: The requested endpoints should work locally and no cloud provider is required for completion of this assignment.

### Part 2 - Development

Hopefully by this point you can verify that your workspace is setup correctly your ready to move onto constructing the endpoints:

### Endpoint 1

We require you to create an endpoint that given a user entered integer representing euros gets the current amount of bitcoin purchasable from bitvavo with the entered amount and stores it into the database. Following this you should return a response to the requester notifying them of the outcome.

Here's a link to help you get started: https://api.bitvavo.com/v2/BTC-EUR/book

**When getting the current amount of purchasable bitcoin you can ignore the fee or presume it's currently set to 0%.**

### Endpoint 2

We require an endpoint that retrieves the last queried amount.

# Comments & Modifications 