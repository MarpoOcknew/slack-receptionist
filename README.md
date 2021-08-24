# slack-receptionist

A simple sign in and user notification system for slack.

## Setup

You will need to create a slack app online at https://api.slack.com/apps and it will need incoming webhooks and permissions setup. 

You should then be able to install it on any slack you have permissions to install plugins to. 

This should give you the OAUTH token and webhook ends you require to update the scripts in index.html

You need to set the Slack ID for each user in the card for them and in the array for checking the status. You can find this by selecting the User in slack, viewing their profile, then in the More option you can copy their ID.