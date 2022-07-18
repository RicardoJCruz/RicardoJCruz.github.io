---
layout: post
title: GameDev.tv - Game Jam 2022
subtitle: Excerpt from Soulshaping by Jeff Brown
tags: [gamejam, 3d modeling, unity]
---

## Introduction

This past May I joined [GameDev.tv](http://GameDev.tv) - Game Jam 2022, I had been away from doing anything related to animation and video games for more than a year, but I felt confident enough to join a Game Jam and see what I could achieve. In this post I’d like to describe my experience in this event.

### What is a Game Jam?

A Game Jam is an event organized by a collective, where you have the goal to release a videogame within a set amount of time, working solo or with a team. This events can be online or in person.

### Who can enter a Game Jam?

Just about anyone! If you are eager to participate in the development of a videogame do not hesitate and join the Game Jam of your preference. If you are new to game development in general a non-competitive Game Jam is a good choice to pick.

### How do I join a Game Jam?

The video games web page [itch.io](http://itch.io) is a popular place to find ongoing Game Jams. Take a look at the ones that have not started yet, check the ones that capture your attention, read the rules and check the rewards, get to know who is organizing the event and why. Finally, pick your choice.

The next step after joining a Game Jam is getting involved in the community, usually you’ll join the Discord server of the organizers. This is the place to go whenever you need to see the news about the event, share your progress, ask for guidence, find a team, etc.

### Lone Wolf or Team Work?

It is a common choice to be in a team with people who have different talents, so anyone can contribute doing the things they are better at. And the game will end up being a much richer product.

Doing a game all by yourself is a challenge, as you have to do many tasks. But you will have complete control on what you are doing, and you will adquire diverse knowledge about the producction of videogames.

Any way you choose to work, you will need a good distribution of the workload to make a good game and have a good time in the process.

### Theme

You can’t just start developing a game for any Game Jam, the game needs to be focused in a Theme that the community votes on. The theme is only revealed when the Game Jam officialy starts.

## Summary

### Set the goals

You need to now what you are doing, before you actually start doing anything. Just after the theme of the Game Jam is revealed take your time to make a plan that explains what you want to achieve and what things you need to do. If you just start working on anything that comes to your mind you may have to redo stuff later to get a playable and fun game, and that takes time.

### Keep the updates coming.

If you already made your plan now it’s time to follow it. The sooner you can get things in the game engine the better, that gives you the opportunity to test the playability, find bugs and get feedback.

### Prioritize time and tasks.

You may have a list of things to do, you must define the things that make the skeleton of your project and find the correct amount of time to make each task. Take into consideration the time, tools and skills you have when you are doing your planning. Remember that building a game and uploading it to the internet takes time.

## Before the Jam

My motivation to join this Game Jam was to work with a team, learn new things, and challenge myself.

I chose this Game Jam because it was the very next one to start, and to receive the free course that [GameDev.tv](http://GameDev.tv) is gifting for everyone who submitted a game.

I joined the Discord server of the organizers to find a team, after a couple of days I got accepted in one.

### Jetlag Game Dev Club

I had the pleasure to work with other 6 talented people. In the team there was a game writter, a music composer, a technical audio designer, two Unity programmers, and two (me included) 3D artists.

The Discord server was very well organized, and everyone already had their roles asigned. There was a presentations channel where one could read the background of every member. I felt very enthusiastic for being part of that team.

## In the Jam

Fast forward to the start of the event, the theme for the Game Jam was revealed to be “Death is only the beginning”. Due to differences in time zones and some personal matters, some team members were not present at the start of the event. Nevertheless, the rest of team had a brainstorm of ideas for the game.

### GDD

I made the proposal to have a shared document where everyone could write their ideas in the form of very small GDDs and later have a meeting to make a definitive plan for the game, some people agreed and I provided the format.

It turns out that writing a single GDD is time consuming, and to have people make one GDD for every idea possible is just not going to work, even if they are very brief.
Thinking of how this could have gone better I would have had a meeting with the available team members to agree on one idea for the game, then with the whole team gathered we could build upon that idea, this way some of us would already have our next tasks in mind.

### Defining the game

We had our first meeting two days after the start of the event. We agreed on making a platformer game with top-down view where you go from the beginning of the map to the end.

The story takes place in hell, the character accidentaly falls to the very last circle of the inferno, where Satan dwells, and the player needs to escape.

The catch is that there are obstacles that you can’t just pass, like a gap that is just to wide to jump over, you need to die to receive help from the Devil himself, who is annoyed that you can’t just get out, and improves you physical abilities; after dying the obstacles become easier to pass.

### First task

My very first task was to make the blocking of a test level in Unity, where the rest of the team could test the mechanics of the game, I worked with my partner 3D Artist and our Game Writer to design this level in Blender. I used ProBuilder and ProGrids to build the level in a Unity scene and then I commited to the main project.

I had one important error in this level, it could not be completed, some falling platforms where too far away from each other, and there where no indications of where some actions had to take place, the end of the level couldn’t be reached; somehow I had completely ignored the fact that the level had to be playable from beginning to end (facepalm). This situation was adressed in a future meeting and the problems had to be fixed to allow the programming team to make more progress.

This test level later became the only available level in the game, and it was formulated as a tutorial level to introduce the mechanic of dying to improve the player’s abilities.

### Second task

My fellow 3D artist and I split the type of 3D assets we were going to make. He got the task to make the main assets for the level, the ones essential for gameplay. I got to do the decorations, which mainly consisted of ice rocks.
Unfortunately my parter had important matters to attend on his side, so he could not participate any further in the production of the game.
One important point here is that we did not have any concept art for the game, and that slowed down our production. The best decision we could have made was to create the concept art ourselves, that would have made it an easier task to create the assets.

### Third task

I got the task to make the main 3D assets for the game, this time I did sketches for these.
****I made a total of 10 main assets for the level. These assets are conformed by meshes, collision meshes and texture maps.

image

### A lot of problems

I took several bad decisions at this point. Two days were left before submission, and I did many sketches for the main menu, some loading icon, buttons, and the character. I didn’t have the time to make assets for any of those elements. I didn’t prioritize modelling the main assets.

My plan was to make the models, make their collisions, do their UV mapping and create their textures, and after all of that was done, add everything to the level at once. As a better procedure, I should have done this workflow per asset, so the rest of the team could test that everything was working correctly as I was adding things to the game engine.

It was at this point that I also realized that, since I was ‘in charge’ of the art, I had almost complete freedom (and full responsability) for the design of the assets, and there wasn’t a big urge to report every progress I made and ask for feedback as I was doing, because everyone was bussy doing their own work. This realization hit like a bucket of cold water thrown to the face, I whish I had known this since the beginning.

Importing the finished assets to Unity was the worst part, it is not difficult, but it does take time, and I only had a couple hours left. I uselessly battled with Blender to export the assets correctly. I still had to create the texture maps and the materials. I am ashamed to admit that my work was the only thing left to add to the game. I managed to do everything and commit just 30 minutes before the end of the Game Jam. But there was a problem with the commits and my changes had to be reversed, the game was finally submited with the ProBuilder geometry.

## After the Jam

But my efforts were not in vain after all. My team was supportive about adding the art for the level past due time, I made the changes and, thankfully, the Lead Programmer took the time to make a new build of the game and update our submission.

### The finished game

[Click here to go to the game](https://anigvit.itch.io/hell-run)

I learned many things participating in this Game Jam and I am looking forward to continue improving my abilities. Thank you for reading.
