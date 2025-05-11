---
title: My Journey Through The Odin Project’s Chess Game
date: 2025-05-11 12:00:00 -500
categories: [Learning to Code]
tags: [the odin project, ruby, coding challenges, problem solving, beginner programmer, coding motivation]     # TAG names should always be lowercase
image: /assets/img/chess game/chess game.png
---

Hey everyone! It's been a while since my last article, as life got pretty busy after wrapping up my [Connect Four project](https://codebyblazej.com/posts/connect-four-project/). Anyway, I’ve been making slow but steady progress on the Chess Game, which is the final Ruby project from The Odin Project's curriculum. Honestly, it's been quite the journey: fun, massive, intense, and sometimes really frustrating. I figured I'd share my experience to help anyone else gearing up to tackle it, trust me, it’s not as scary as it seems!

## Starting the Chess Project

Believe it or not, I started mentally preparing for Chess long before even beginning Connect Four. I'd caught snippets of conversations on Discord, and people kept saying how huge and complicated it was. What really caught my eye was how everyone seemed stuck around the 70% completion mark. Another thing is that many folks skipped Test Driven Development because of how huge this project was. That was enough info for me at this point, I didn’t want any spoilers, so I stopped reading!

When I finally got around to starting, my first step was drafting some pseudocode and getting the basic logic straight in my head. I had a few ideas, but I couldn’t shake the memory of the Knight Travails project, which I’d thought would help me solve the Chess challenge.

![pseudocode](/assets/img/chess%20game/pseudocode.jpg)_my pseudo, pseudocode_

## Why I Paused TDD (and Why You Might Too)

Initially, I focused on designing the chessboard and creating all the chess pieces to display them clearly in the console, no moves yet, just the basics. At first, being a good student, I wanted to follow TDD right from the start. But pretty quickly, I realized why everyone had warned it was tough. 

I managed to write some basic tests for early methods, but soon enough, I was staring at my screen overwhelmed. Each problem I solved seemed to spawn two more, like some frustrating spiderweb. Eventually, I set TDD aside just to focus on making progress. I felt a bit guilty ditching tests because I genuinely liked them during Connect Four. 

However, I promised myself I'd circle back once everything was up and running smoothly.

## Navigating Chess Piece Logic (and the Headaches It Caused)

At this stage, I had a rough game class, a method to handle rounds, and my board displaying nicely but zero moves programmed. It was time to roll up my sleeves and start coding chess moves. I knew I'd need special pawn moves and king-rook castling eventually, but decided to start with basic movements first. Knight Travails was helpful, or so I thought.

![knight-travails](/assets/img/chess%20game/knight_travails.png)_knight travails method_

It didn’t take long to hit another snag: chess isn’t just about movement, but also about dealing with other pieces. So I had to go back, refactor the code, and figure out how to handle situations like taking opponent pieces or preventing moves onto spaces already occupied by your own pieces. 

Honestly, that refactoring part was a total pain, especially after finishing the knight’s moves only to realize the knight "jumps" rather than slides, forcing yet another rewrite.

![knight-moves](/assets/img/chess%20game/knight_moves.png)_knight moves after correction_

Once basic moves were finally done, I tackled the special pawn moves like advancing two squares on their first move, which was tricky but manageable. Castling, though, was another beast altogether! I actually took a break to clear my head, switching back to refining the game class, adding clarity, extra variables, and cleaning things up.

By this point, things were coming together, and castling started to look less intimidating. But now I knew JSON serialization was looming, and frankly, that scared me even more than castling did!

After a few intense hours, I finally conquered castling, minus a couple of debugging sessions that nearly drove me nuts. Once sorted, I realized my prompts to the player were broken, so I fixed those too.

![castling](/assets/img/chess%20game/castling.png)_bit of castling movement_

## A Short Break and Battling JSON in Poland

Right after this, I took a much-needed holiday in Poland. It was my first trip abroad in three years, delayed by waiting for settled status. I'd ambitiously promised myself I’d code every morning from 6:30 to 11, but you know how it goes… 

Friends called, family invited me over for coffee and cake, and suddenly coding turned into just an hour per day. But honestly, the downtime helped me recharge, even though it completely wrecked my sleep schedule!

![trip-to-poland](/assets/img/chess%20game/poland.png)_trip to Poland_

While in Poland, I tackled JSON serialization because I’d struggled with it before and needed to get comfortable with it. Honestly, it was incredibly frustrating. Everyone online seems to talk casually about JSON, but organizing everything into hashes, especially nested ones for chess pieces, was brutal. Maybe my design made things harder than necessary. Anyway, after three tough weeks, I finally nailed it!

![JSON](/assets/img/chess%20game/JSON.png)_a bit of JSON implementation_

Back in the UK, my final week was dedicated to tests (yes, I finally returned to TDD!) and polishing prompts with some colorful console messages to make gameplay clearer and more enjoyable. And guess what? It’s DONE!

![RSPEC](/assets/img/chess%20game/RSPEC.png)_now a bit of RSPEC dopamine hit_

I'm genuinely thrilled to be finished this project felt like it took forever! Now, I can finally move forward. No rush, obviously, but I'm excited for what's next.

## My Best Tips for Tackling the Chess Project

If you're about to tackle this Chess Game, my main advice is patience. Take your time upfront to really map out your design. Grab a pen and paper, jot down your ideas, and plan thoroughly. Trust me, skipping proper planning landed me in a mess of redundant code and wasted effort. A couple more hours of preparation could’ve saved me heaps of trouble.

Good luck, and more importantly, have fun with it!




