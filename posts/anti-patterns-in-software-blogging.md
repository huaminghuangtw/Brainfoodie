---
title: Anti-Patterns in Software Blogging
created: 2026-10-14
modified: 2026-10-14
authors: Michael Lynch
category: Essay
---

# Give the reader a reason to continue reading

* Meandering is the most common mistake in software blogging.
* When a developer starts reading a blog post, they’re trying to answer two questions:

	1. Did the author write this for someone like me?
	2. How will I benefit from reading it?

	Give yourself the title and the first three sentences to answer both questions.

* Preamble (e.g., a subtitle, a bio, an image, or a quote) still counts as meandering.
* Remember: _Everything you put in the reader’s path is extra work that chips away at their finite supply of focus._ Give the reader a compelling reason to continue reading. Make it in the **title** and the **first three sentences** of your blog post.

# Never assume the reader knows everything you do

* Minimize assumptions about the reader’s background knowledge, especially for a technical term.
* Tip: _Think of a person you know in real life. Read your article as that person and identify which terms feel unfamiliar._

# Do not over-rely on links

❌ Assign [firewall](https://docs.freebsd.org/en/books/handbook/firewalls/) rules to prevent external traffic from reaching your database.

✅ A [firewall](https://docs.freebsd.org/en/books/handbook/firewalls/) is a system that restricts how hosts and networks communicate with an app. You can increase your web app’s security by configuring firewall rules to only allow inbound requests to your database server when they originate from your app server.

Instead of relying on a link to do the work for you, summarize the relevant information _behind_ a link. Namely, link to useful resources, but make them a **bonus** rather than a **prerequisite**. Keep the reader on the page. Your target reader should be able to enjoy and understand your article from start to end _without clicking any links (or even hovering for tooltips)_!

# Avoid the sequel injection bug

❌ In part one, we learned about quintuply linked lists and how they can 100x your daily LOC output. In today’s post, I’ll show you how `goto` statements let you scrunkmax (a term I invented in part one — remember?).

It’s fine to refer to your previous posts, but never do it in the very beginning. Assume most readers haven’t read your previous articles. _Summarize what was relevant_ rather than expecting the reader to go read all your prior posts.
