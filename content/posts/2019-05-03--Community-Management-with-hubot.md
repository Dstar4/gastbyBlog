---
title: 'Managing your Slack Community With a Custom Bot'
date: '2019-04-03T22:12:03.284Z'
template: 'post'
draft: false
slug: '/posts/community-management-with-hubot'
category: 'Typography'
tags:
  - 'Open source'
  - 'Gatsby'
  - 'Typography'
description: ''
---

If you have a growing community and are starting to feel a little overwhelmed by administrative tasks it may be time to start thinking about solutions to help your community continue to grow. By finding a way to automate some tasks we can be more efficient with our time, provide a better onboarding experience from new members, and create a community project that can excite your community. The main goals for creating this bot is to engage members of the community, provide some consistency to a growing community, and to help automate tasks that start to get out of control as your community grows. While this article is geared towards an online community using Slack as their main communication tool, this information can be applied to many different communication platforms.

## Why use a bot?

In my community, we found that as the member count grew, at a certain point people were not getting on-boarded consistently. New members would receive an email after requesting to join with some relevant information, but once you read over that and joined the community's Slack workspace there was not a clear protocol for next steps. As a new member to the community, it may be tough to find a place to get started, to know where to ask questions, or who is willing to lend a hand, or even where to find the channel you need in a list of hundreds of options. This is where some automation can start to help. By creating a bot you can address all of these issues with one solution, and that solution will actually save you valuable time you can then spend doing more important things in your community.

### The Welcome Message

A welcome message is a powerful tool that will help set the tone for someone joining your community. If someone joins and is unclear on how they can get involved then their interest could diminish and you may never see them again. By creating a clear welcome message with a simple path to getting started you can inform someone of current policies, ways to get started, and where to go for assistance. As your community grows across timezones you may find yourself unable to keep up, by giving the responsibility of welcoming all new members with everything they need to get started.

![](/media/welcome-message.png)

### Commands

You can create many different commands for your bot that listens to specific keywords, these commands can be a powerful tool to make sure the most up to date, important information is always available. These commands can be things like "?help" or "!conduct". You typically want to keep the keywords to things that will not trigger a response when it is not needed, which is why they generally start with a special character such as a "?" or "!". Generally, the "?help" command will display all available commands with a short description. You can direct members towards this command via the welcome message. Once you can create commands you will need to create the information they provide.

![](/media/commands.png)

## Content Hosting

Your organization may already have things such as an onboarding procedure or code of conduct in a google drive somewhere. Our goal is to make sure people know how to find it. There is one big factor to consider here since your community will evolve over time it is important your bot can adapt. You could go into the code for your bot and update the text your commands return whenever you make a change, but this could be an often difficult and forgotten step that may be overlooked as changes are made. A great alternative would be to create this content on a platform such as Notion, Google Docs, or Github. By hosting your documents on one of these platforms you can simply link to them with your bot commands and continue to edit them as you please, knowing all new members will always see the most up to date version.

![](/media/github-resources.png)

### New Features

Once you are able to create a welcome message and a few basic commands you may be thinking about all the new ways your bot can help. Some common ways are to create a list of keywords the bot listens for and then messages the sender to re-examine the language they used. Or you can create some fun features to liven up the chat such as keywords that evoke witty responses from the bot.

## Bot Options

There are lots of options out there as far as bots go. If you are on slack I would suggest looking into the default slackbot. Information can be found here [https://get.slack.help/hc/en-us/articles/202026038-An-introduction-to-Slackbot](https://get.slack.help/hc/en-us/articles/202026038-An-introduction-to-Slackbot). This slackbot is very easy to get set up and supports more basic features like commands and custom automatic responses. This can be a good option if you just need a few basic features. If this is something that will suit you, I would recommend the tutorial found here [https://zapier.com/blog/how-to-build-chat-bot/](https://zapier.com/blog/how-to-build-chat-bot/) If you are looking for a bot with the ability to grow and do more I would recommend looking into a framework like Hubot. [https://hubot.github.com/](https://hubot.github.com/). Hubot is very easy to get running with some basic tech knowledge and has an amazing community that has built hundreds of functions you can import and use in your own bot.

### External Scripts

There are also many tools that have been created by different communities that have been opened to the public. These can vary in complexity, some are as simple as copy and pasting a line of code, others may require much more configuration. You can find a list of hubot's external scripts here. [https://www.npmjs.com/search?q=keywords:hubot-scripts](https://www.npmjs.com/search?q=keywords:hubot-scripts)

## Next Steps

Now that you have seen the benefits a slackbot can provide, it is time to get it set up. In part 2 I will take you from start to finish through the process of getting these starting commands working. We will be using a popular bot framework called hubot to get us started, and then adding a welcome message and a few simple commands. We will then deploy our bot and add it to slack. Getting started doesn't take long and can be a great project for your community to undertake together.
