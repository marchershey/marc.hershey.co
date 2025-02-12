---
title: Let's talk about Jekyll
description: test description
category: blog
tags: test asdf
layout: post
---

<hr data-content="Chapter 1: Wait, what?" />

When I say "static site generator," what comes to mind?

You probably said something like Wix, Squarespace, Weebly, or maybe even Wordpress, right?

Right, site generators are getting more and more popular as time goes on, but what you might have missed is the word, **static**.

"**Static** site generator" still doesn't really define Jekyll, in my opinion, but its getting close. By their homepage, to a beginner it seems like Jekyll is just another website builder, that's super easy to install... and all I need is 4 lines of code, my content, and boom! Website is ready to go!

![Image of Jekyll's homepage installation instructions](https://i.imgur.com/JRvHOpZ.png)

That can not be further from the truth. To install Jekyll, you need to have Ruby installed on your system, and that in itself is a task. I know I know, most developers are screaming at their monitors at me right now, yelling "ITS SUPER SIMPLE!" - But I've been programming for 15+ years, I've never touched Ruby in my life, so it's all brand new to me.

Even with years of expierence with code, Ruby is a mystery to me. I can not fathom how Jekyll works. I mean check this out, this is my `index.html`:

{% highlight ruby %}

# index.html
---
layout: home
---

Hello World.
{% endhighlight %}

Like.. what? What is that? That is my exact `index.html`.

I come from a PHP background so that makes zero sense to me. I understand with PHP, you have [bootstrapping](https://www.binpress.com/php-bootstrapping-crash-course/) but with Ruby, how do the templates / layouts get loaded? When a browser lands on the index, what happens? No clue.

I do notice that we have a `Gemfile`, and inside that Gemfile, there's a few `gem` commands, but again, where does that get bootstrapped into the application?

Well, since it's quite obvious that I don't have a single clue, I wanted to make this post while I start my journey learning how Jekyll works. So sit back, and enjoy watching me pull my hair out as I attempt to teach myself an entire new programming language / framework.

<hr data-content="Chapter 2: Let's go Google'n" />

Okay, so first things first, I'm going to use the **KISS** method _(keep it simple stupid)_. Let's just Google `How does jekyll work`.

![An image of my search results](https://i.imgur.com/a4aW68L.png)

Okay, well we know that, maybe the _KISS_ method isn't the best for this, but let's see what else we have on this result...

Searching a bit, I found this on StackOverflow:

![An image of a StackOverflow question titled "What does Jekyll actually do"](https://i.imgur.com/HAxxskO.png)

Ha. Which funny enough, the only reply to that question kind of agrees with me.

> **Nicol Bolas:** Jekyll's website is poorly structured and is written/designed in marketing speak, so it's hard to understand what it's doing if you don't already have an idea. ...

<hr data-content="to be continued" />
