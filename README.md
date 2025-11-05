# Video Demonstration
Will be posted soon (posting this note on Nov 4th)
# Overview
In this portfolio piece, I'll be demonstrating some rudimentary API testing with Postman, using Trello's API. For an OAuth 2.0 demonstration, see [this brief project](https://github.com/mhoepf84/OAuth-2.0-Access-Demo).

I have left brief comments in the code script, as well as in the Comments sidebar within Postman. There is a menu option for "Documentation," but since this doesn't exist for Collections, I decided to just consistently leave these notes in the same general place.

# Installation & Setup
To start with, prepare an installation of Postman, then download the JSON files attached here. First, we'll go through the Trello setup.
1. Go to [Trello's main site and create an account](https://trello.com/). We'll be utilizing a free account, and the only limitation (which shouldn't come up in this test suite) is easy to address. It limits us to 10 boards, but these can be removed manually or via using DELETE API calls (which I've included here).

2. After this is done, go to [Trello's Power-Up Admin Panel](https://trello.com/power-ups/admin/). From the Power-Ups page, select "New" and populate the fields in the subsequent window as you'd like. Be sure to specify the workspace, as that is mandatory.

3. Next, you will be placed on a dashboard for the Power-Up. Click "Generate a new API key," confirm the pop-up, and you will be presented with an API key.
  
4. In my tests here with Postman, I opted to use a token (which has a hyperlink beside the API key). Click this, and copy the token information. This will be plugged into Postman, and is the direct line of communication you will need in order for the test suite to run.
