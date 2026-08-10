---
source: Simon Willison
category: ai-agent
title: SQLite compressed text-history prototypes
url: https://simonwillison.net/2026/Aug/9/sqlite-text-history-prototype/#atom-everything
published: '2026-08-09T22:05:00+00:00'
score: 5
ingested: '2026-08-10'
status: unread
---

# SQLite compressed text-history prototypes

> Source: [Simon Willison](https://simonwillison.net/2026/Aug/9/sqlite-text-history-prototype/#atom-everything)

<p><strong>Research:</strong> <a href="https://github.com/simonw/research/tree/main/sqlite-text-history-prototype#readme">SQLite compressed text-history prototypes</a></p>
        <p>I'm perennially interested in options for storing revision histories in relational databases. While out on a dog walk I had a new idea: how about taking the full text of every prior version in a big JSON array of strings and then applying zlib or zstd compression to the whole thing? Surely that would compress really
