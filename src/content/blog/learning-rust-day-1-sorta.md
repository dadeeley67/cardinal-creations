---
title: Learning Rust - Day 1 (sorta)
description: I'm going to be learning the Rust programming language, and I am
  gonna document my progress here on this blog. I am a HTML/CSS/JS developer by
  default, so Rust feels like a big change for me, and I am excited to really
  get into it.
author: Dave Deeley
date: 2023-12-21T05:15:14.557Z
tags:
  - rust
  - programming
  - learning
image: /assets/images/blog/rust_program.png
imageAlt: "A rust program in a terminal that converts fahrenheit to celsius. "
---
Okay, this isn't _technically_ the first day of my Rust journey. It is just the first day that I will begin writing about it. I actually started this learning project a week ago, so I'm not too far ahead, as I work a full-time job and have a lot of other hobbies that take up my time.

## The Inspiration

I will be taking the advice of [No Boilerplate](https://www.youtube.com/@NoBoilerplate), one of my new favorite YouTubers, and I will follow his [recommendations](https://www.youtube.com/watch?v=2hXNd6x9sZs&list=PLZaoyhMXgBzoM9bfb5pyUOT3zjnaDdSEP&index=18) on how to learn Rust. His entire philosophy and aesthetic are very inspiring to me. From his "fast, technical videos" about Rust and his extremely candid conversations about mental health, his very well-made podcasts like [Lost Terminal](https://www.youtube.com/watch?v=p3bDE9kszMc&list=PL95NP4bDITAln7fq-cCqzOFE15UvVthuL&index=1&t=5s) and [Modern Prometheus](https://www.youtube.com/watch?v=_SDnUVHAC44&list=PL95NP4bDITAlpJn8cKpIOEeMPbEudc1OD&index=1), and his dedication to [open sourcing all of his work](app://obsidian.md/%5Bhttps://github.com/0atman/noboilerplate%5D), he makes me want to be more creative again, and he makes me feel excited about learning again.

## The Learning Plan

Okay, so first things first, what does this learning plan look like? No Boilerplate breaks it down as essentially a main quest with a variety of side quests. Obviously, the main quest is to learn Rust. The side quests are as follows (I have slightly changed these, making a few of the suggestions their own side quests that weren't originally, and also throwing in some work I plan to do on top of the suggestions here):

### 1. Read [_Ultralearning_](https://www.scotthyoung.com/blog/ultralearning/) by Scott Young

I've already begun this, and I am about a third of the way through the book. I like it a lot so far. He talks about [Eric Barone](https://www.stardewvalley.net/author/concernedape/), the incredible brain behind _Stardew Valley_, one of the greatest video games of all time, very early on in the book. That was an exciting tie-in for me personally, as I absolutely adore _Stardew Valley_, I'm super excited about _Haunted Chocolatier_, and his story of dedicating himself to learning all the necessary skills to create a video game (music production, script writing, pixel art, programming, etc.) is genuinely inspiring.

In my opinion, he owes a lot of that success to his partner, who was able to cover a majority of their living expenses while he worked a part-time job and spent the rest of his time working on creating _Stardew Valley_ and learning all the skills he would need to do so. Spare time and energy are two things that a lot of people don't seem to have a lot of these days, and to become so proficient in so many different domains simultaneously requires boatloads of both of those things, along with the skills that Young discusses in _Ultralearning_. I don't say this to take anything away from Barone, of course. He's wonderful, he's created a wonderful thing, and I'm sure he would agree with me that the freedom to not spend so much time dealing with the everyday banality of living in our modern world was a huge part of the story of the creation of _Stardew Valley_. I say all of this because, well, I don't have that particular luxury, so my attempt at this will probably be much slower and much less multifaceted than Barone's or many of the examples in _Ultralearning_.

### 2. Read The Rust Book Twice

Building off of a lesson from _Ultralearning_, the second side quest involves reading [_The Rust Programming Language_](https://doc.rust-lang.org/stable/book/), ostensibly the Bible for Rust, twice. _Ultralearning_ references a study that showed students who took an exam before studying, failed it, and then took it again after studying did much better than students who just studied and took the exam once. _No Boilerplate's_ suggestion is to read the book all the way through once without doing any of the coding exercises. Just immerse yourself in the terminology and the concepts, note anything you don't really understand, and then continue reading.

After that, you should read it again using [this version from Brown University](https://rust-book.cs.brown.edu/). This version has interactive quizzes built into it. I don't know if this version has you actually write the code in the book in a browser, but I suspect it doesn't, so I am thinking that I will write the code along with the book as well, as it is never too early to get that muscle memory started.

### 3. Rustlings Katas

[Rustlings](https://github.com/rust-lang/rustlings) is a collection of code exercises designed to get you used to reading and writing Rust code and learning to read and understand Rust compiler messages. Each exercise is a program that fails to run, and your job is to fix it. They get progressively more difficult, and they can provide you with hints (on top of the compiler messages) to help you get going if you get stuck.

They are based on the idea of [katas](https://en.wikipedia.org/wiki/Kata). Katas are, essentially, movements in martial arts that are designed to be practiced alone and repeated regularly to be memorized. It seems that this word has been sort of adopted to refer to the repeatable practice routines of any skill, be it musicians practicing their scales or programmers practicing their code katas. Either way, I'm here for the idea. I don't know how useful practicing the same problem over and over would be if it were a particularly basic problem, but I can see the benefit of practicing more complicated things over and over, spaced out over time, so you actually have to think about the problem again.

Long story short, after I read the book twice, I will begin doing these rustlings code exercises. I believe there are nearly 100 of them, and I am unsure how difficult some of them will get, so I'm not sure how long this will take me exactly. It should be fun, though!

### 4. Learn Haskell

Haskell is another programming language, a "purely functional programming language", that I don't know much about. Again, I am a web developer. I am, frankly, not the most technical software engineer in the world. That is part of the reason I am interested in learning Rust. I want to force myself to almost start from scratch, and Rust is quite different from the language I'm used to, so I think I will have my work cut out for me.

According to _No Boilerplate_, learning how to use Haskell will help you use Rust to its full potential. I don't know anything about functional principles, functional programming languages, or anything like that, honestly. However, if he claims it will be helpful, then I believe it, and I will give it a shot. I'll end up reading one of the books he suggests and maybe doing the read once quickly, read twice and program along method.

## And So We Start

_No Boilerplate_ says something at the end of the video I am using as my guide for this learning plan that really struck a chord with me. I think it might be the single sentence in all of his videos that really pushed me to have this desire to learn Rust so badly. He says;

> Keep in mind through all your early learning, you only have to learn Rust once. JavaScript developers have to keep learning JavaScript **_every_** **_single_** **_day_**. Edge case after edge case after edge case. Framework after framework to try and manage these edge cases. It's exhausting. Rust offers another way, but you have to work for it.

It **_IS_** exhausting! It is **_so_** exhausting. You learn HTML, CSS, and JavaScript, and you should be all set, but then you've got to learn jQuery for your job. Wait, now jQuery is outdated, basically all of its functionality has been built into vanilla JavaScript, but you do need to learn a JavaScript framework, so here is AngularJS. Oh wait, Google just killed AngularJS. Now you have to learn Angular, no, wait, just kidding, Google kills their projects too frequently; try React instead, or maybe Vue.js, or maybe Svelte, no wait, back to React, because that's what companies are looking for experience with, and the whole point of all of this is to get a job, right? Or maybe...

See? Aren't you exhausted after reading that? I know I am exhausted after typing it all and reliving that experience in my head. I really like JavaScript, it has been basically my entire career, but I am _exhausted_ by the entire ecosystem of web development in general. Most people who need websites don't need these complicated frameworks anyway, they just need some HTML, CSS, and a little bit of JavaScript. I've never needed to use React on a client's website—not yet, anyway. I would rather never have to use it, and I would rather use a language that is consistent, fast, and can allegedly get me through the backend and the frontend without sacrificing my potential to get a job at a regular company. Rust appears to be that language, and I hope it delivers on all of those promises.