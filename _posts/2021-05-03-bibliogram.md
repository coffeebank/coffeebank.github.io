---
layout: post
title:  "How to Use Bibliogram on Windows 10"
date:   2021-05-03 12:00:00 -0700
categories: tutorial
---

Instagram -- owned by Facebook -- is a crazy beast. When you aren't signed in, it's impossible to see even public Instagram accounts. This is unacceptable, because of how many public services post updates to Instagram these days. Not only that, but signing in is also a hassle in itself, with Facebook always asking about new locations or suspicious activity.

There's [Invidious for YouTube](https://invidio.us), [Teddit for Reddit](https://teddit.net), and [Nitter for Twitter](https://nitter.net). And luckily, there's also [Bibliogram for Instagram](https://bibliogram.art). This means you can view any public Instagram post you want!

However, using Bibliogram like the other services above [will start becoming a challenge](https://cadence.moe/api/urls/b1781c) thanks to Instagram's shenanigans.

As the developer says, running Bibliogram off your own computer as a Linux user is easy, but I've come to like using Bibliogram, and would like to make the process buttery smooth for my Windows friends as well. So here we go:

# Requirements

- Maybe like 500 MB
- A good attitude
- The ability to click with a mouse and to copy-paste


# Step 1: Turn on some Settings

In Windows 10, you first need to turn on "Windows Subsystem for Linux".

[Here's a picture guide for how to turn it on >](https://www.wikihow.com/Enable-the-Windows-Subsystem-for-Linux#Turning-on-Windows-Subsystem-for-Linux)


# Step 2: Get Ubuntu

Then, jump into the Microsoft Store and click "Install"

[Get Ubuntu from the Microsoft Store >](https://www.microsoft.com/en-us/p/ubuntu-2004-lts/9n6svws3rx71?rtc=1&activetab=pivot:overviewtab)


# Step 3: Copy-Paste some Stuff

When Ubuntu is installed, click it in the Start Menu, and you're in!

Now, copy and paste, then click enter, and wait for the text to stop flashing before continuing, for each line below:

```
sudo apt-get update
sudo apt-get -y install fish
sudo apt-get -y install graphicsmagick
git clone https://git.sr.ht/~cadence/bibliogram-updater
```

# Step 4: You're done!

Yes, it was that easy.

To start Bibliogram, type `./run.fish`

Next time you want to run Bibliogram, just click the Ubuntu button, then type `./run.fish` inside it.

Bibliogram will automatically update when you run it, if there's an update.
