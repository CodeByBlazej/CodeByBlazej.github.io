---
title: How to Understand IO and TTY in Linux for Begginers
date: 2024-11-11 12:00:00 -500
categories: [Learning to Code]
tags: [the odin project, ruby, coding challenges, problem solving, beginner programmer, coding motivation]     # TAG names should always be lowercase
image: /assets/img/tty session/IO and TTY in Linux for Beginners.png
---

After I finished Mastermind project which was the most difficult project so far I moved to Files and Serialization lesson in [The Odin Project](https://www.theodinproject.com/) curriculum. 

I stumbled upon a lot of long articles full of technical language that for me, non-English native speaker were quite difficult to understand. Especially after coming back from my 9-5. 

When I was reading the last one, many things clicked and I thought it all could have been explained in a little easier way. I came up with an idea of how to make it in 6 simple steps and the results are below.

This is a nice funky graph for you to visualize it: 

![img-description](/assets/img/tty%20session/TTY%20session.png)_Linux TTY session and IO flowchart for beginners_


## STEPS 1 - 2
Let’s start from the input. When you are typing something, input (IO) is taken from your keyboard and sent to TTY virtual device. TTY in Linux is the interface that handles input/output. 

## STEP 3
The input is then passed to the TTY session (the terminal interface you interact with).

## STEP 4
From there, the TTY virtual device forwards it to the line discipline inside the kernel. Line discipline is the place where magic happens. For example, pressing BACKSPACE will clear the last character we typed in or process special keys, signals, and interpret commands.

## STEP 5
After processing, the line discipline sends the input to the foreground process (like a shell) via STDIN.

## STEP 6
When the process generates output, it then sends it to STDOUT or STDERR if it’s an error, which goes back through the TTY virtual device and then displays on the TTY session again.

## Final thoughts

Don’t you think these processes are really interesting? Since I started learning how to code I was always curious about how everything works under the hood. What happens when you press some buttons, what kind of signals are sent, where they are going, and so on. 

Maybe in the future, I will make a similar graph visualizing something else. We will see what I will get stuck at soon. 

If you have more questions, drop a comment below! I’d love to hear what topics you’re struggling with or find intriguing. Your feedback helps me decide what to break down next. Happy learning!
