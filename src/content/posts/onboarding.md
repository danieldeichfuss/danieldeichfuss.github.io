---
title: onboarding
description: humans and agents
published: 2026-09-08
category: AI
tags:
  - ai
  - engineering
---

I'm currently onboarding a new colleague. As with many things in the age of agents, this has changed quite a bit, much more than I anticipated. In the before-times when you onboarded a colleague you just had to onboard that person. You answered questions, gave them some documentation and provided feedback. Now I have to onboard them and their agents.

When I say onboarding, I mean sharing knowledge, mindsets, expectations, justifications (yes, I know this code is horrible but here is the reason). The point of all of it is alignment. Sharing is the easy half.

What's new is that I noticed that I don't just need to convince the new colleague, but now I also need to convince their agents. An agent with missing information and an engineer who lacks it can create an echo chamber that only leads to confusion and frustration.

One concrete example is our E2E test setup. The tests create and delete data in the production application. That is perfectly safe, because we isolate it at the infrastructure level and use dedicated test users. The agent doesn't know that and freaks out. My colleague lacks the arguments to convince the agent and the agent slowly convinces him that he uncovered a huge problem. Both end up building sophisticated mechanisms solving problems that don't exist.

But here is the good news. The thing we've all been waiting for. There is finally someone who actually reads the documentation. And that makes all that alignment work such a high-value exercise.

There are countless ways to get that context in front of an agent. I prefer agent skills, because they are flexible, portable and every major harness supports them. I know there are companies building elaborate systems, but I would rather give everyone room to experiment than dictate the tools and workflows. One good skill file in the right place aligns every agent that reads it, which is more than I can say for humans and documentation.
