---
title: "NFC Hacker Card"
author: "revati"
description: "A PCB hacker card (kind of in the name)"
created_at: "2026-07-29"
---

# July 29: Created the journal & set up repo

I recently heard abotu Forge and was browsing through projects and noticed that a lot of people were making their own hacker cards. Naturally, I wanted to make one for myself, maybe even add some PCB art to it if I can figure out how to lol.

The dimensions of a standard credit card are 85.6 mm x 53.98 mm x 0.76 mm so that's the size I want my card to be. I started by making a new project in kiCad. Rather than just having it be a plain PCB board, I wanted to add some leds and fake footprints to make it look a bit cooler. And ofc decorate the silkscreen to be pretty.

I was looking through Pinterest for some inspiration and found this image, which looks pretty cool! I think I want to have somet artwork on the back and then attach an NCF tag and antenna on the front with some LEDs and a port for power.

![inspo image](/img/inspo.jpg)

I started by figuring otu what I needed in the schematic for kicad. Just a heads up I'm I total beginner in PCB design, the only one I've created was the blinky board from Stasis, so it took me a while to figure out what I needed. I found this tutorial ([https://jams.hackclub.com/jam/hacker-card](https://jams.hackclub.com/jam/hacker-card)) from Hack Club where they used EasyEDA but I'm more familiar with kiCad from the blinky board tutorial so I just stuck to that. Something I realized after quickly reading through this writeup was that if I wanted what is called "energy harvesting", where the LEDs would light up once the phone was brought close to the NFC, I couldn't just use a regular tag, instead I would need something like a NXP NT3H2111 (a fancier NFC chip).

Anyways I made a mockup of what I wanted it to look like on Canva and then also brainstormed the parts list. Here's what I'll need:

1 ncf chip
1 antenna
3 small warm yellow LEDs
3 resistors
1 100 muf cap

And the mockup, which I'll probably end up changing as I go.

![inspo image](/img/mockup.png)

TLDR I mostly spent today figuring out what parts I need (since this is the first time I'm picking out custom ones for a project rather than following one of the Hack Club guides) and setting stuff up. Tomorrow my goal is to actually finish up the schematic. I'm still a bit confused on how to pick out the exact resistor values & cap values but I'll save that for tomorrow.

**Total time spent: 0.75 hours**