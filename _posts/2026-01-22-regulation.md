---
layout: post
title:  "Regulation"
date:   2026-01-21
categories: AI
---

Power markets regulation has been a nightmare of mine for long. Whenever you think about setting up an energy business, what a supplier must bill his customers or how to participate in wholesale power markets there is a regulatory text waiting for you to delve through its dull pages. All the answers are there. Unsufferable streaks of definitions that follow legal preambles. If only the annexes, where the important stuff is, was provided by regulators in a concise and separate piece so that we could keep up with them. We the small can't compete with the big industry players and their regulation experts teams.

With all its addendums, you have to find out with which was the last one. Is it one?, two?, five? Bits of seemingly outdated rules from 30 years ago that still apply must be coherent with rules from a few months ago. And you must make sense of it. What procedures should I follow to provide demand side response? How do I certify it? How's the matching between supply and demand done in France? What's the procedure in Spain? What are control zones? Where is price data available? How are control zones related to frequency and technical constraints management? And it changes throughout Europe. How can I help myself?

When ChatGPT appeared I thought I should give it a try. Maybe it could ingest pdfs and html and let me know what was important. I was wrong. It never found the paragraphs that mattered to me. Was it the headings of that chapter that made the whole thing invisible to ChatGPT? I spent whole days trying to make it useful. I learnt it was not there yet.

About a year and half later, on a trip to Madrid to see my brother, I wanted to read a tutorial(ish) from a Machine Learning business in Paris called .probabl[^1]. I like and hate the French for the same reason: their math education is so good, but that also makes them so arrogant. Engineers from Grandes Écoles can be assholes. However, all polytechniciens that I have met are great people. Smart, fun, succesful. Accomplished. The thing is it was an article on how to build a RAG[^2]. It seemed kind of exciting because I liked algebra at uni and that vector database thing could be fun. Also I had an interest in AI not just as user but how to code it. I had watched and coded through some of the video's from Karpathy's from zero to hero[^3].

_.probabl_ wanted an improved search bar, where the user would write what he/she is looking for in scikit-learn's documentation site[^4]. The LLM would retrieve an answer instead of providing a back and forth interaction as in conversational LLMs. It is called "zero-shot prompting".


[^1]: [https://blog.probabl.ai/weldon/a-rag-from-scratch-to-query-the-scikit-learn-documentation-0][.probabl]
[^2]: [Retrieval augmented generation][RAG]
[^3]: [https://youtube.com/playlist?list=PLAqhIrjkxbuWI23v9cThsA9GvCAUhRvKZ](https://youtube.com/playlist?list=PLAqhIrjkxbuWI23v9cThsA9GvCAUhRvKZ)
[^4]: [scikit-learn][sklearn]

[.probabl]: https://blog.probabl.ai/weldon/a-rag-from-scratch-to-query-the-scikit-learn-documentation-0
[RAG]: https://en.wikipedia.org/wiki/Retrieval-augmented_generation
[sklearn]: [https://scikit-learn.org/stable/index.html]
