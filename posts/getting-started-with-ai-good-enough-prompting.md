---
title: "▍Getting Started with AI: Good Enough Prompting"
created: 2026-06-12
modified: 2026-06-12
authors: Ethan Mollick
category: Essay
tags:
  - ai
---

# Working with AI is a dialogue, not an order.

「一個指令一個動作」的內容產生器 → 需要耐心教導的「學徒」。

Example: Doctors using GPT-4 for diagnoses performed no better than those without it—and both did worse than GPT-4 alone. Why? They treated the AI like a search engine, asking narrow, factual questions instead of giving it full context and leveraging its ability to synthesize complex information.

> As a [New York Times article on the paper](https://www.nytimes.com/2024/11/17/health/chatgpt-ai-doctors-diagnosis.html) reported: “they were treating \[the AI\] like a search engine for directed questions: ‘Is cirrhosis a risk factor for cancer? What are possible diagnoses for eye pain?’ It was <mark>only a fraction of the doctors who realized they could literally copy-paste in the entire case history into the chatbot and just ask it to give a comprehensive answer to the entire question</mark>.” […] There are many stumbling blocks: people treat AI like Google, asking it factual questions. But AI is not Google, and <mark>do not provide consistent, or even reliable, answers</mark>.

> AIs are inconsistent and weird, and often have different results across different models. For example, they [are sensitive to small changes in spacing or formatting](https://arxiv.org/abs/2310.11324); they get [more accurate when you tell them to “read the question again;”](https://arxiv.org/pdf/2309.06275) they [seem to respond better to politeness (but don’t overdo it)](https://arxiv.org/abs/2402.14531); and they [may get lazier in December, perhaps because they have picked up on the concept of winter break](https://x.com/emollick/status/1734280779537035478). Add to all of this the fact that getting good results out of AI without a lot of formal training is likely growing easier as [larger models are less sensitive to changes in prompting technique than older AIs](https://arxiv.org/abs/2410.12405), and new techniques allow the AI to [improve your prompt for you](https://docs.anthropic.com/en/docs/build-with-claude/prompt-engineering/prompt-generator).

---

Prompt engineering isn’t the place to start. Instead, the key is spending 10 hours using AI on tasks you care about. This hands-on experience helps you naturally develop the intuition needed to prompt effectively.

> You can learn details of prompt engineering and [the basics of how LLMs work](https://www.oneusefulthing.org/p/thinking-like-an-ai), of course, but for most people, that is not a required starting place. You just need to use AI enough to get a feel for what you can use it for in your area of expertise. <mark>The most important thing to do is to get 10 or so hours of use with an advanced AI system.</mark> And to do that you just need to be a good-enough prompter to overcome the barriers that hold many AI users back.

> The single most useful thing you can do to understand AI is to use AI. There are lots of reasons people may decide to give up on using an AI quickly, from early hallucinations (the AI isn’t good enough) to existential discomfort (the AI is _too_ good), but many of those initial reactions are tempered over time. <mark>Your goal is simple: spend 10 hours using AI on tasks that actually matter to you. After that, you’ll have a natural sense of how AI fits into your work and life. You’ll develop an intuition for effective prompting, and you’ll better understand AI’s potential.</mark>

> <mark>Start by using it in areas of your expertise</mark>, where you are able to quickly figure out the shape of the [jagged frontier of its ability](https://www.oneusefulthing.org/p/centaurs-and-cyborgs-on-the-jaggedh). Because you are expert, you will be able to quickly assess where the AI is wrong or right. You do need to be prepared for it to give you plausible but wrong answers, but don’t let the risk of these hallucinations scare you off initially. Though hallucinations may be inevitable, you will learn where they are a big deal, and where they are not, over time. You can reduce the rate of hallucinations somewhat by [giving the AI the ability to be wrong,](https://docs.anthropic.com/en/docs/test-and-evaluate/strengthen-guardrails/reduce-hallucinations#example-analyzing-a-merger-and-acquisition-report) for example, <mark>writing: if you’re unsure or necessary information, say “I don’t have enough information to answer this” can make a big difference</mark>.

---

> I mean literally <mark>treat AI just like an infinitely patient new coworker who forgets [^1] everything you tell them each new conversation</mark>. Two parts of this are analogous to working with humans (being new on the job and being a coworker) and two of them are very alien (forgetting everything and being infinitely patient). We should start with where AIs are closest to humans, because that is the key to good-enough prompting. As it is a coworker, <mark>you want to work with it, not just give it orders, and you also want to learn out what it is good or bad at</mark>.

Instead of treating AI as an intern or new grad hire, treat it like an infinitely patient coworker who:

1. Is highly capable but needs specific guidance.
2. Forgets everything at the end of each conversation.
3. Never gets annoyed and tired of iterating.

	> This introduces something new in intellectual life, **abundance**. You don’t need to ask for one email, ask for three in different tones to inspire you. You don’t need to ask for one way to complete a sentence, ask for 15 options and see if that unlocks your writing. Don’t ask for 5 ideas, ask for 30.

	> Your job becomes one of pushing for <mark>variation</mark> (“give me ideas that are 80% weirder”), <mark>recombination</mark> (“combine ideas 12 and 16”) and <mark>expansion</mark> (“more ideas like number 12”), before selecting one you like.

[^1]: Give it whatever information you have lying around: entire documents, instruction manuals, or even previous conversations are often helpful, [just remember to pay attention to the AI’s memory, its context window.](https://www.oneusefulthing.org/p/thinking-like-an-ai)
