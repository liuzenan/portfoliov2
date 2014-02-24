---
layout: post
title:  "Hacking at Facebook Singapore"
categories: Hackathon
cover_image: hackathon.jpg
---

Last weekend I was at the Facebook Hackathon Singapore event with my friends. I’ve been to a few hackathons before but the environment and participants at Facebook Singapore office is one of the best I’ve seen so far.

We had a bit of a discussion before the hackathon so we got an idea that could be easily built within the span of 24 hours. It is an private chatting iPhone app for lovers named Pair Diary. The feature that sets it apart from Couple and other private chatting apps is that in Pair Diary you can saved memorable and meaningful messages and view them as diaries. Also you can get points for posting messages and photos to each other, which borrows ideas from gamification techniques to encourage communication. Just a fun and simple concept to enjoy our time at the hackathon.

<figure>
	<img src="/img/hackathon/fb_sg.png" alt="">
	<figcaption>Facebook Singapore</figcaption>
</figure>

<figure>
	<img src="/img/hackathon/snacks.png" alt="">
	<figcaption>Great! They have snacks.</figcaption>
</figure>

After a brief tour around the Singapore Hackathon office, which is a quite cozy and artsy place, I started off prototyping the app interface using Sketch. I chose a warm red/pink color to be the app’s theme color. And selected Avenir Next as the primary typeface. Artboards on Sketch is a very useful feature to sketch app screen fast and easy. 

<figure>
	<img src="/img/hackathon/sketch.png" alt="">
	<figcaption>Designing app prototypes using Sketch</figcaption>
</figure>

We use Parse as the backend for Pair Diary since it is quite simple to set up and use for the purpose of hacking. For the app design, I went for the minimalistic approach and use the minimal number of colors and font variations. The result is a clean user interface with unique character.

<figure>
	<img src="/img/hackathon/Login.png" alt="" width="320">
	<figcaption>Login Screen</figcaption>
</figure>

Since the app is for couples, the signup flow is fairly straight forward: A user downloads the app, logins in with Facebook and sent and invitation to a friend to join. The user can directly go into chatting screen and start leaving messages before the partner joins. When the partner joins, he or she will be asked to confirm connecting with the currently paired partner. 

<figure>
	<img src="/img/hackathon/Pair.png" alt="" width="320">
	<figcaption>Signup Screen</figcaption>
</figure>

Chatting screen works just like iMessage, but with a different color scheme. So users will be already pretty familiar with how the interface works. In addition, in the chatting screen, user can save a message or photo to diary by long press on a message, and press save from the contextual menu. This is not obvious to people who just starting to use the app so it still needs to be tested with real users and a UI guide might be necessary to help users find the action.

<figure>
	<img src="/img/hackathon/Message.png" alt="" width="320">
	<figcaption>Chat Screen</figcaption>
</figure>

In the diary screen, user can views statistics from chat history, and saved messages which are consolidated by date.

<figure>
	<img src="/img/hackathon/Diary.png" alt="" width="320">
	<figcaption>Diary Screen</figcaption>
</figure>

Development the iOS app is also quite straight forward with the help of storyboard. I’ve been using storyboard a lot recently and it speeds up the developement for me and also improved code readability by eliminating the need for specifying frames in the source code.

<figure>
	<img src="/img/hackathon/storyboard.png" alt="">
	<figcaption>Storyboarding the app interface</figcaption>
</figure>

The hackathon is an awesome experience to learn new stuff and make friends. We saw many inspiring projects demoed at the session and some are quite impressive in technology. My friends and I will continue improving and iterating on the current MVP and probably launch it to public sometime soon and see how it goes. 