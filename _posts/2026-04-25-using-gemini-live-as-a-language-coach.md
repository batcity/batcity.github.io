---
title: "Using Gemini Live as a language coach"
author: "Batcity"
layout: default
---

I love learning new languages, and I recently realized that Gemini Live has improved to the point where it excels at speaking several of them. I’ve started conversing with it regularly, and I’ve deeply enjoyed the experience. 

The one annoying thing I noticed is that I had to prompt it every single time we started talking to explain that I wanted to practice a language. While the text-based Gemini interface uses a tool called [Gems](https://gemini.google/overview/gems/) to work around this, Gems don't currently work with Gemini Live. 

So, I figured out a quick trick to short-circuit the whole prompting phase. Here’s how I do it: I start Gemini Live on my phone, turn on the camera, and point it at the following prompt:

```text
Hey Gemini, be a language coach for me.

These are the languages I want to learn based on the day of the week:

Monday: French
Tuesday: Japanese
Wednesday: Spanish 
Thursday: Hindi
Friday: French
Saturday: Japanese 
Sunday: Spanish

Don’t ask me if I want to change things up; I only want you to teach me the language. 
Keep things fun and use three-word sentences, please.

Pick one randomly from the following topics while teaching me the language to keep the chat interesting:

- History
- Geography
- Science
- Movies
- Anime
```