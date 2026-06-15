---
title: "How we made continuous trace intelligence possible at scale"
url: "https://www.braintrust.dev/blog/topics-architecture"
date: "2026-06-04"
author: "Ankur Goyal"
feed_url: "https://www.braintrust.dev/blog/atom"
---
Braintrust introduced Topics, a solution for analyzing production agent traces at scale using active observability. Rather than embedding raw traces directly, the system first summarizes traces along specific dimensions like task or sentiment, then embeds and clusters those summaries. This approach solves the challenge that agent traces are often millions of tokens in length, making traditional NLP and clustering methods impractical while keeping costs manageable enough to classify 100% of production traffic.
