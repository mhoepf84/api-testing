NOTE: Video will be uploaded next week (Nov 10-14). Draft Postman JSON is uploaded for now. Will finalize it prior to recording video demo.

# Video Demonstration

# Overview
In this portfolio piece, I'll be demonstrating some rudimentary API testing with Postman, using Trello's API. For an OAuth 2.0 demonstration, see [this brief project](https://github.com/mhoepf84/OAuth-2.0-Access-Demo).

I have left brief comments in the code script, as well as in the Comments sidebar within Postman. There is a menu option for "Documentation," but since this doesn't exist for Collections, I decided to just consistently leave these notes in the same general place.

# Installation & Setup
To start with, prepare an installation of Postman, then download the JSON files attached here. First, we'll go through the Trello setup.
1. Go to [Trello's main site and create an account](https://trello.com/). We'll be utilizing a free account, and the only limitation (which shouldn't come up in this test suite) is easy to address. It limits us to 10 boards, but these can be removed manually or via using DELETE API calls (which I've included here).

2. After this is done, go to [Trello's Power-Up Admin Panel](https://trello.com/power-ups/admin/). From the Power-Ups page, select "New" and populate the fields in the subsequent window as you'd like. Be sure to specify the workspace, as that is mandatory.

3. Next, you will be placed on a dashboard for the Power-Up. Click "Generate a new API key," confirm the pop-up, and you will be presented with an API key.
  
4. In my tests here with Postman, I opted to use a token (which has a hyperlink beside the API key). Click this, and copy the token information. This will be plugged into Postman, and is the direct line of communication you will need in order for the test suite to run.

5. In Postman, import the environment and collection files provided here, then click the "Trello Test Env" environment. In here, you will see two environments: "token" and "api_key". Fill in the details from your Trello API (steps 3 & 4). Make sure the "Trello Test Env" is chosen in the top-right.
