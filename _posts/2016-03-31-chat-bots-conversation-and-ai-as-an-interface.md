---
inFeed: true
hasPage: true
inNav: false
inLanguage: null
starred: false
keywords: []
description: ''
datePublished: '2016-03-31T18:27:12.805Z'
dateModified: '2016-03-31T18:24:17.971Z'
title: 'Chat bots, conversation and AI as an interface'
author: []
authors: []
publisher:
  name: null
  domain: null
  url: null
  favicon: null
sourcePath: _posts/2016-03-31-chat-bots-conversation-and-ai-as-an-interface.md
published: true
url: chat-bots-conversation-and-ai-as-an-interface/index.html
_type: Article

---
# Chat bots, conversation and AI as an interface

Chat bots tap into two very current preoccupations. On one hand, the hope that they can actually work is a reflection of the ongoing explosion of AI, and on the other, they offer a way to reach users without having to get them to install an app. 

One way to look at any given AI problem, in the crudest terms, is to ask whether solving this needs 'general AI' or whether your domain is narrow enough and your solution broad and flexible enough that you can deal with a wide enough percentage of potential scenarios without having HAL 9000\. That is, we're clearly pretty close to making a car that can handle highway driving with no human input, since the range of possible events is pretty small, but driving in central Rome or Moscow is an entirely different matter that needs an entirely different level of decision-making: what does that hand gesture mean? 

Hence, the challenge in plugging an AI into a 'conversational' chat bot interface is that you don't have HAL 9000 but are in some sense pretending to the user that you do. You speak to it, it speaks back, and it uses natural language (either in voice or text), but it isn't general AI at all. So, how likely is it that the users can ask something that breaks it? How badly? How narrow is the domain of questions that they might ask, and how can you define the users' expectations such that they understand the domain? Perhaps more importantly, can you get people to accept the domain?

A good way to see this problem in action is to compare Siri and Google Now, both of which are of course bots_avant la lettre_. Google Now is push-based - it only says anything if it thinks it has something for you. In contrast, Siri has to cope with being asked anything, and of course it can't always understand. Google Now covers the gaps by keeping quiet, whereas Siri covers them with canned jokes, or by giving you lists of what you can ask. The actual intelligence might (for the sake of argument) be identical, but you_see_Siri failing. 

To invert this, the Siri 'this is what you can ask' screen is essentially a command line help prompt, whereas the whole point of a GUI was that you didn't have to know what you could type anymore. Though natural language processing means you don't need to know a specific syntax for Siri or a bot, there's still a basic discovery issue - what can I ask, given I can't ask anything?

All of this means that for now, it seems that a bot or conversational UI might work best for something very specific - where the user knows what they can ask, and where those are the only things that they will ask. However, when it does work, it becomes very interesting indeed, particularly now because it happens to align pretty well with the second preoccupation - getting around the app-installation problem. 

Instead of going through all the pain of persuading someone to install your app, what if you could have an immediate, fluid and easy way to engage through a conversational interface? Could you make chat bots a third runtime, after the web and native apps, that gives you a new interaction model? And, of course, could that have a new way to acquire users that works better than the App Store? (In other words, 'never mind the dream of artificial intelligence - will this let me stop giving so much money to Facebook?')

That is, the immediate promise of a conversational UI is less something that you do within your own app than that it might make it much easier to interact with your users without having to get an app installed in the first place. 

The practical question here, of course, is, well, what runtime? We had the smartphone OS with its APIs, and we have the web browser, but what's the local target for a bot? If a bot is a command line UI, what's the terminal? How does it get onto the phone? And does it have its own meta-mechanisms for user acquisition and discovery of services as well as the runtime itself? Where are those?

One pretty obvious smartphone trend has been for interaction models not just to proliferate but to move up and down the stack - up the stack into new apps that themselves act as platforms (Facebook, WeChat, maps etc) and down into the OS (Siri, Now, deep links etc). So too with bots: Apple has not opened up Siri to developers (yet), but Google is selectively opening Now, and it would certainly seem to be strategically desirable for the OS provider to be the one creating any new runtimes. 

However, the challenge for both Apple and Google here is the other end. They can put a bot terminal on the phone, but for anything in the cloud to talk to you on your phone, that service has to know where to look. Both companies have some form of cloud identity platform, but Apple's privacy strategy precludes many uses of this, and neither Apple nor Google have a platform today that Gap or Instacart might ask you to log into when you place your order, such that they can talk to you about it afterwards. Of course, this could change - in particular, the rumour that Apple will extend Apple Pay (and by implication Touch ID) to the web opens up lots of possibilities in this direction. 

Moving up the stack, Facebook has both ends - the terminal, in Messenger (which now has 1bn mobile MAUs), and the web identity platform. Facebook's challenge is in a different place: would publishers want to give it so much control, and would they trust it to continue the platform into the future, given its track record? 

Meanwhile, I found Microsoft's heavy focus on bots and associated tools at 'Build' pretty interesting, because of course Microsoft has neither end - it doesn't have a mass-market smartphone platform or a web identity platform that could be the connective glue. (It does have Skype, with 300m MAUs, but I'm not at all clear that that has the right market positioning to be a viable terminal in this sense.) But a lot of Microsoft's narrative is about building cloud platforms to enable other people to create bots that could then run between any two other end-points - between FB Messenger or Slack at one end and Gap at the other, logged in through a Facebook identity, but with the actual capabilities coming from Microsoft. That is, Microsoft as, well, a development platform. Naturally, this is Google's self-image too - what is Google if not a platform for understanding and communicating data at massive scale? 

I've deliberately been using the rather retro term 'terminal' to describe the place a bot UI lives in on the phone because that seems to be the way many people think about it - there's an AI in the cloud and you talk to it through a dumb text or voice UI on the phone or PC. That also reflects the way Now works - the device is mostly dumb glass. This is an extension of the shifting of interaction layers up and down the stack I mentioned earlier - here you're in some senses shifting the interaction up off the device entirely. Coincidentally, 'terminal' is the word telcos used to use to refer to mobile phones before smart happened at all, and indeed many of the sample use cases I've seen for chat bots could be done with SMS, or perhaps USSD. 

But that's not the only potential model. WeChat uses messaging as a platform but doesn't push interaction down to the level of 'dumb text' - it provides its own social and acquisition model but much of the actual interaction with third party services happens in rich UIs (mostly built as web views, as it happens). And after all, if you're offering a user a question to which there are only two options, should you tell them 'you can reply 'red' or 'green'', or should you give them two buttons within the chat? What if there are five options? Should you perhaps construct some sort of on-screen interface for your users that lays out, graphically, the options? You could call, it, perhaps, a 'GUI'. You could have 'links' that you tap on, that load new 'pages'... And indeed, if you've got your chat bot working, does that need to be in Facebook, or could it be on your own website too? It depend what kind of interactions you're looking for, and maybe whether you're solving your own problems or your users'. 

There's an old computer science idea that a computer should never ask a question that it should be able to work out the answer to. One promise of AI is that you can get, not so much a computer that you can talk to like a person, but one that you don't need to talk to at all, or much less - that you can remove the mental load and friction and maintenance of engaging with a computer or online service. The computer can ask fewer questions and work out more by itself. (This is somewhat analogous to the reduction in mental load involved in moving to iOS or Android from Windows or Mac). Instead of going back to the website and logging into your order and editing it, you can just send a message: 'cancel the shirt and get me the green bag instead of the grey one'. A computer ought to be able to work that out, and will probably be able to. You ought to be able to use AI, and chat, in some way, to achieve the same aims with much less work. But it doesn't follow that that's a great way to do everything. If it takes you more time to work out what you can ask the AI assistant than to drag the meeting to a new slot on your calendar, you're doing it wrong. An AI shouldn't be more mental load than just tapping the damn button - an IVR with better buzzwords. That might be a better user acquisition model for you, but that's tough. And so this comes back to my opening point - is this a domain where you can just tell it what to do and move on, or one where the 'general intelligence' still needs to be between the chair and the screen?