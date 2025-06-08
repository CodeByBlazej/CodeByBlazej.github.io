---
title: My 468-Day Experience with The Odin Project - Part 2
date: 2025-06-07 12:00:00 -500
categories: [Learning to Code]
tags: [the odin project, ruby, coding challenges, problem solving, beginner programmer, coding motivation]     # TAG names should always be lowercase
image: /assets/img/finished ruby/thumbnail.png
---

Hey there! After spending another 357 days on The Odin Project, I've finally hit a big milestone, I finished the Ruby section!

So why does the title say 468 days then? Well, the Foundations section took me 111 days, and since my last article about that journey was pretty popular, I figured you'd enjoy another update. 

If you haven't checked out [that previous piece](https://codebyblazej.com/posts/the-odin-project-experience/) yet, it's worth having a look! I carefully tracked my progress every day, so counting my total hours was pretty easy. 

Overall, I've spent exactly 686 hours on this journey. My daily routine mostly stayed the same, but recently I started squeezing in an extra 30 minutes to an hour of study each morning. About two months ago, I even started waking up 90 minutes earlier to boost my learning pace. 

On top of that, which not everybody might like, I began to listen to techno music while learning. Why? I have noticed that it helps me with being distracted while going through long articles, where I caught myself reading 1 sentence 15 times over and over again sometimes.

![Time calculation](/assets/img/finished%20ruby/Time%20duration.png)

This post is basically my reflection on learning to code with The Odin Project, what I've picked up during this Ruby section, and what the overall experience was like. 

I still clearly remember sitting on my bed, which has been my unofficial "office chair", thanks to my weird little room, excited to dive into Ruby right after wrapping up the calculator project from Foundations. 

## The Basics

Honestly, the beginning was pretty rough. Diving straight into Ruby documentation? Yeah, I nearly fell asleep more than once. At that point, coming from JavaScript, I started doubting if I'd made the right choice, I mean, wouldn't JavaScript have been easier since I already knew a bit of it? But I'm glad I stuck with Ruby because it turned out to be totally worth it, I’ll explain more about that later!

![Ruby API](/assets/img/finished%20ruby/ruby%20documentation.png)

Every lesson included a lot of material covering all the necessary topics like variables, hashes, arrays, and so on. 

I still struggled with loops at this point and I don’t know why. Now they seem fine after so many projects, but at that moment in the past, I remember I was still getting stuck whenever I had to write something involving loops or more complicated logic that based on them. 

The debugging lesson was also interesting, as it differs a lot from JS, but it was extremely important and useful! It saved me plenty of time later on in many projects.

And finally, there was the lesson about enumerables. Remember, at this point, my brain was pretty much wired to JavaScript syntax. But when I finally grasped what these enumerables were all about, I was hooked! It felt so easy and clever to do something in just one Ruby line that would normally take me 10 lines of JavaScript. I loved it and immediately wondered how often I'd end up using them. It wasn't long before I caught myself squeezing enumerables into every project I tackled. They seem to match exactly how your brain naturally approaches problems, quickly becoming the first tool that pop into your head when coding.

And for you JavaScript folks! Before you call me arrogant for not mentioning an equivalent in JS, just hold on! I simply haven't reached that point yet. If there is something similar, drop it in the comments. I'd genuinely love to check it out and compare. If not, maybe give Ruby's enumerables a try and see what you think!

## Basic Ruby Projects

Finally, it was project time, perfect for testing out all these new Ruby tools.

![Basic Ruby projects](/assets/img/finished%20ruby/basic%20ruby%20projects.png)

The first one, Caesar Cipher, wasn't too bad. Shifting letters back around after Z was the trickiest part.

![Caesar Cipher](/assets/img/finished%20ruby/caesar%20cipher.png)

The substring project was pretty straightforward, dealing mostly with strings, hashes, and enumerables. I probably could've turned it into a one-liner, but I split it up for clarity. Looking back nearly a year later, figuring out ‘reduce’ was probably the biggest hurdle.

![Substring](/assets/img/finished%20ruby/substring.png)

Stock Picker was next. The trick there was matching two arrays, one with prices and another with days to buy and sell for the best profit.

![Stock Picker](/assets/img/finished%20ruby/stock%20picker.png)

Then came Bubble Sort, the hardest of the bunch. Luckily, some extra reading and an awesome video from the lesson cleared things up.

![Bubble Sort](/assets/img/finished%20ruby/bubble%20sort.png)

Whew! These four projects weren't super long, but they sure felt intense!

## OOP Section

I have to say, I couldn't wait for the OOP section to start! At that time, I had been reading tons of posts and articles about it because I knew the entire process of designing apps would rely heavily on OOP. 

Everybody seemed to be talking about it, and I kept trying to picture how it actually worked. I even compared it to a car engine in my head, imagining that each part of the app would somehow depend on another, all working smoothly together. Turns out, I wasn't that far off! 

A lot of what I imagined turned out to be true, and I really liked it. In fact, I even wrote [another article comparing debugging code to fixing cars](https://codebyblazej.com/posts/why-learning-to-code-is-like-fixing-a-car/), there are more similarities than you'd expect.

There were two projects in this section: Tic Tac Toe and Mastermind. These were actually pretty enjoyable because they were a bit longer and more advanced than the earlier ones. I had a great time figuring out different ways to solve them. Honestly, who knew programming could be this much fun?

Here are the repo links if you're interested:

- [Tic Tac Toe](https://github.com/CodeByBlazej/Tic-Tac-Toe)

- [Mastermind](https://github.com/CodeByBlazej/Mastermind)

## Files and Serialization

This part took longer than expected because I really wanted to get it right. File handling basics were straightforward, but TTY (terminal devices) was tricky. It confused me enough to motivate me to [write another article](https://codebyblazej.com/posts/how-to-understand-tty-in-linux/), complete with a simple diagram to clear things up.

![TTY Graph](/assets/img/finished%20ruby/GRAPH%20TTY.png)

## A Bit of Computer Science

This section was sooo long! It was packed with tough, demanding projects and tons of information you probably hadn’t even thought about until now. Like how RAM actually works under the hood which I found super interesting, especially when you imagine all that data zooming around under your fingertips, completely invisible to the eye. Pretty wild, right?

You also learn how to calculate the speed of different algorithms, when to use which one, and why it even matters.

Oh! And I definitely can’t forget the Knight Travails project at the end. That one was brutal. Honestly, I think it was the hardest project so far in the whole curriculum. Most projects give you a few different ways to solve a problem, but here? Not really. As far as I remember, there were only one or two valid approaches, and you had to use a proper algorithm to get it done. It’s not even a lot of code, but the mental effort? Next level.

- [Knight Travails repo](https://github.com/CodeByBlazej/Knights-Travails)

## Intermediate Git

Bookmark these lessons, seriously! They're easily among the best in the entire curriculum. Git and GitHub can feel weird and confusing, but these lessons clarified everything perfectly. Up until now, every Git issue had me wondering when we’d cover it properly. Well, here it finally was.

## Testing Everything with RSpec

Another long but rewarding section. Learning RSpec felt almost like tackling another programming language entirely. It was tough at first because I’m still more comfortable writing code first and tests afterward. 

My last project, the massive Chess game, was so big I couldn't manage tests upfront. I'm still practicing, though, and improving bit by bit.I'm thinking of writing another article specifically about an interesting ‘real life’ project I recently did for a friend stay tuned!

If you stuck around till the end - seriously, thank you! I hope reading this was helpful, or at least cured your boredom for a bit. 

Oh, and one last thing, remember earlier when I said I'd come back to Ruby docs? Well, they're not exactly thrilling when you first start out, but trust me, the deeper you go, the more useful they become. Sure, you can quickly get answers from ChatGPT or a speedy Google search, but when you kinda know what you're looking for, say, something specific like enumerables, and decide to peek into the docs, you'll often stumble onto extra gems that make your code way better. I've found myself rewriting whole methods a couple of times after spotting an elegant one-liner in the docs. This happened recently during the Chess project and my friend's app, and honestly, it felt pretty awesome!
