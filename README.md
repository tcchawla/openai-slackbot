# Slack-OpenAI Project

This repository explains on how to connect Slack-chatbot with OpenAI's GPT model to automate sending responses using MindsDB.

## To get started

* [Create an account on MindsDB cloud](https://cloud.mindsdb.com) (if you don’t have one yet).
    
* [Create a Slack Account](https://slack.com/get-started#/createnew) (if you don't already know about Slack.)
    
* Go to your [MindsDB SQL Editor](https://cloud.mindsdb.com/editor)

## Prerequisites

For this proejct we need Slack API token, If you already have the API token of a Slack Bot, feel free to skip the following steps.

To generate a new API Bot token, please follow below instructions:

Here are the steps to generate the Slack API token:

1. Follow this [Link](https://api.slack.com/apps) and sign in/create your Slack Account.
2. Create a new `App` or select an existing `App`. 
3. In the app settings, go to the `OAuth & Permissions` section. 
4. Under the `Bot Token Scopes` section, add the necessary scopes for your application. You can add more later as well. 
5. Install the bot to your workspace. 
6. In the `OAuth Tokens & Redirect URLs` Section, copy the the `Bot User OAuth Access Token` (This is the API token which we need). 
7. Open your Slack, in order to use the bot which we created, we have to add the bot into the channel where we want to use this. 
   - Go to the channel where you want to use the bot. 
   - Right Click on the `channel` and select `View Channel Details`. 
   - Select `Integrations`. 
   - Click on `Add an App`. 
   - You can see the name of the bot under the `In your workspace` Section, Go ahead and add the app to the channel.

Now, we can use the token from *Step 6* to initialize the Slack Handler in MindsDB.


## Usage

Please head over to the `queries.sql` file. You can directly execute the commands mentioned in that file to interact with your Slack Channel.

Enjoy!