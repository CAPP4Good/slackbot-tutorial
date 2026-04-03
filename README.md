# :sparkles: How to Build a Slack App!

**C4G: In order to do this project, you will need to create your own Slack Workspace — one outside of CAPP**
We recommend [creating one as a group](https://slack.com/help/articles/206845317-Create-a-Slack-workspace#create-a-workspace) and give everyone. Slack's default is to give everyone permission to add an [outside app](https://slack.com/help/articles/1500009181142-Manage-app-settings-and-permissions). 

You can walk through one or more of the tutorials below and create all the bots you want. In Libby's mind, you will do the following: 
1) Start with option 1 and work through steps 1-4. Skim step 5. 
2) Figure out how to adapt option 1 to run on Bolt
3) Proceed to option 2 and learn javascript
4) If time -- move to option 3

Good luck and happy coding! 

## Option 1: Python & Flask 
**Pros**: 
- Lots of documentation through this repo
- Relies on Python — which we already know!

**Cons**:
- Example app is based on a COVID API that may not be helpful

This repo is largely based on option 1 since we are more familar with Python and should offer a good starting point. This repo walks through how to program a slack app using **Python** and **Flask**. Specifically, it demonstrates the types of Slack apps you can build with Slack's Python SDK, [**python-slackclient**](https://github.com/slackapi/python-slackclient), and [**Slack Events Adapter**](https://github.com/slackapi/python-slack-events-api), which facilitates the handling of data from the Slack Events API in Python. Forked from [here](https://github.com/MaayanLab/slackbot-tutorial?tab=readme-ov-file).

We'll cover all the basic steps you'll need to have a fully functioning app that can listen and respond to events in slack, handle slash commands, and so much more!
- First, we will cover the basics about how to handle **events** and create **slash commands**. :desktop_computer: :speech_balloon:

### Table of Contents
- **[1. Creating the Slack App](1-create-slack-app.md)**
- **[2. Setting Up](2-setting-up.md)**
- **[3. Responding to Slack Events](3-responding-events.md)**
- **[4. Integrating Slash Commands](4-slash-commands.md)**
- **[5. Example App: COVID-Bot](5-covid-bot.md)** --> Unknown if this is working properly since it's been a minute since this was created

### Video Presentation
[<img width="550" alt="Screen Shot 2020-07-18 at 8 38 14 AM" src="https://user-images.githubusercontent.com/66278476/87852687-1d63f980-c8d2-11ea-8970-22b016d41a8a.png">](https://youtu.be/tEH-x1TmGVE)

### Credits (Option 1)
This tutorial was originally created by @juliekaram and The Ma'ayan Laboratory at the Icahn School of Medicine at Mount Sinai.

## Option 1.5
Rather than using Flask, try Bolt. 

You can learn more about Bolt in either Javascript or Python here: [https://docs.slack.dev/quickstart/](https://docs.slack.dev/quickstart/)

## Option 2: Javascript 
**Pros**:
- lots of Slack bots are built on Javascript

**Cons**:
- no internal documentation (pointing you to some websites that should be helpful, but nothing specific)

[https://medium.com/codex/building-a-slack-bot-using-node-js-part-1-7b3e7d54e9b6
](https://medium.com/codex/building-a-slack-bot-using-node-js-part-1-7b3e7d54e9b6)

[https://docs.slack.dev/tools/bolt-js/getting-started/
](https://docs.slack.dev/tools/bolt-js/getting-started/)

[https://dev.to/isaksolheim/creating-a-slackbot-with-javascript-bolt-1kp7
](https://dev.to/isaksolheim/creating-a-slackbot-with-javascript-bolt-1kp7)

**Video**: [https://www.youtube.com/watch?v=QBRHcGGTRCY](https://www.youtube.com/watch?v=QBRHcGGTRCY)

## Option 3: JavaScript & Github Actions
**Pros**:
- A useful app!
- Learning Github Actions too

**Cons**:
- tutorial is more Github Actions focussed and not necessarily Slack bot focussed 

[Weather Slack Bot](https://github.com/jkeefe/weather-newsrooms-nicar25/tree/main) (Github Actions & Weather Slack Bot)
- Specific Slack Bot instructions are in the [warnings-slack.js](https://github.com/jkeefe/weather-newsrooms-nicar25/blob/main/warnings-slack.js)
