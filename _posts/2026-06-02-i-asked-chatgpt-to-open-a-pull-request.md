---
title: "I Asked ChatGPT to create a Pull Request"
author: "Batcity"
layout: default
---

I’m pretty wary of running AI agents locally on my machine for security reasons, but I recently found a way to get similar functionality without giving an LLM direct access to my system.

I installed the [ChatGPT GitHub connector](https://help.openai.com/en/articles/11145903-connecting-github-to-chatgpt) and gave it permission to write to a repository. Now, I can just ask the ChatGPT web app for changes in the chat, and it creates a Pull Request directly on GitHub.

> ⚠️ **Heads Up:** Just a quick disclaimer—this feature is still super buggy at the moment (as of June 2026). During my testing, it frequently refused to create PRs claiming it didn't have permissions (even when it did). Worse, when trying to update existing feature branches, it occasionally wiped out chunks of essential code entirely. Proceed with caution!