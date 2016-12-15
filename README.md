![Landing Page](/screenshots/landing.png)

# What is Manoa: The Gathering?

Manoa: The Gathering is a free, fun, and functional online simulator of the trading card game Magic: The Gathering. But wait, it gets better! As the name implies, MtG (Manoa: The Gathering) is unique from Magic as it focuses on the lore and monuments of the University of Hawaii at Manoa.

## Current site

[Click here](https://manoathegathering.meteorapp.com/) to play!

## Okay, what do I need to know to play MtG?

First and foremost, you'll need a University of Hawaii account to sign in and play, so if you don't attend or work at UH, then sorry, this isn't the app for you. In order to use our soon-to-be super awesome app, you need an internet browser (preferably a Chromium-based one), a strong internet connection, and knowledge of how to play Magic: The Gathering. MtG doesn't have a system to check the rules, as it is entirely based on the players' actions in what they choose to do. You can break the rules and play your entire hand on the first turn, but your opponent will most likely report you and you will be banned. So don't do that please.

## Guided Tour

If you see the above screen, that means you've clicked on the link above and you are now on Manoa: The Gathering. Congratulations!
<br>
<br>
The footer at the bottom is how you'll navigate our site. First and foremost, let's look at the _about_ page so you know what we're all about.
<br>
<br>
**About Page**
![About Page](/screenshots/about.png)
<br>
<br>
Once you're done reading about how awesome, our app is, head on over to the _tutorial_ page, so you can get a quick refresher on how MtG plays, and so you don't accidentally break our rules and get banned.
<br>
<br>
**Rules Page**
![Rules Page](/screenshots/rules.png)
<br>
<br>
When you first arrive at the tutorial page, there will be a list of links you can click to access the specific rules. The first, and most important, one is our _Code of Conduct_ (pictured above). This details the rules of our app, so read carefully.
<br>
<br>
Alright, let's get back to our _home_ page. If you click on the _Play now_ button, you'll be prompted to sign in using your UH account. Upon doing so, you'll notice that the _Play now_ button has changed to _Find a Match_. This is what you'll want to press if you actually want to use our app.
<br>
<br>
**Chat Page**
![Chat Page](/screenshots/chat.png)
<br>
<br>
Now you're in our _chat_ page! You can interact with other online users (listed on the right) by typing your messages into the text box below the chat. If you click on an online user, it replaces the chat with a DM between the two of you. If you want to go back to the general chat, click on the button labeled _General Chat_. **Awesome chat cheat: type "_rainbows_" without the quotes and be amazed!** If you're super lame and don't like it, type in "_no rainbows_".
<br>
<br>
Once you're done chatting and making friends, you can start playing a game with someone else. If you click on someone's username and click on the button labeled _Match Request_, it sends them a match request. You'll notice messages appearing in the box below the chat. Once it tells you that the requested person has accepted the match request, click on _Accept_ and you'll get into the game. On the other hand, if someone sends you a match request, you can click on their name and then the _Accept_ button to accept their request.
<br>
<br>
**Battle Page**
![Battle Page](/screenshots/battle.png)
<br>
<br>
Now that you're in the battle page, you'll see in the chat box who was randomly assigned to go first. That person can draw and play their turn through the steps of Magic (detailed in the tutorial page). You can click on your cards to tap them! Isn't that awesome?
<br>
There is another chat box within the battle page for you to communicate with your opponent, and buttons that are intuitively labeled with what they do. For instance, _Draw_ has you draw a card from your deck. On the left, you'll see the Life Points of both players and you can add or subtract from the LP.
<br>
<br>
Note that when you're playing, it tells you who is on the green side and who is on the blue side. Please only play and interact with the cards on your proper side, or that will be a violation of our rules. Furthermore, your initial hand will be laid face-down. Clicking on the cards in your hand will flip them face-up to be seen only by you.
<br>
<br>
Have fun!

## Developer Guide

If you are a developer that would like to modify our app, you can click on the above button leading to our GitHub repo and clone it. The `master` branch is what is currently deployed to Galaxy. Our `kadira` branch is like our testing branch, in which we test functionalities before merging to `master`. The other branches are pretty self-explanatory, and our app follows the recent ES6 Meteor app structure.

When you want to test out your changes, while you're in the _app_ directory, type the following command into your terminal: _meteor --settings ../config/settings.development.json_

If you'd like to make changes, do what you want and then submit a pull request. We'll look it over and either merge it, or let you know about what should be changed!


## Initial User Study

Our users found that they didn't have a problem navigating the site as a whole. All but one immediately went to the about page, then logged in. As soon as they logged in, they all played with the chat feature for quite a while.

At that point, we didn't have the battling working, so they briefly looked through the tutorial. All of our users knew how to play already, so they didn't spend much time there.

All of them seemed to get the most enjoyment out of cosmetic details, such as the day/night loading page with the swinging Log In button and rainbows on the chat page.

One mentioned that the "Hello, name" on the home page is a little hard to see, and a few other small things. But overall, they all loved the site.


## Contributors

[Irene Fang](https://irene-f.github.io/), [Creighton Chan](https://creightonchan.github.io/), [John Headland](https://jheadland.github.io/), [Lexa Mink-Flacco](https://acvmf.github.io/)

## Milestones

[Milestone 1](https://github.com/manoa-the-gathering/ManoaTheGathering/projects/1)

[Milestone 2](https://github.com/manoa-the-gathering/ManoaTheGathering/projects/2)

[Milestone 3](https://github.com/manoa-the-gathering/ManoaTheGathering/projects/3)
