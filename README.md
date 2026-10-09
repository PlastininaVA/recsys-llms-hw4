# LLM4Rec — Homework 4 (Association Rules)

Week 4 assignment for the LLM4Rec course (HSE University, instructor Seungmin Jin).

This repository contains `week4/` — the modified starter for the association-rule
mining task over the **UCI Online Retail** dataset (dataset 352):

- `week4/script.js` — implementation of the `TODO(hw4)` stubs:
  `findFrequentItemsets` (Apriori with downward-closure pruning) and
  `generateRules` (both-direction rule generation);
- `week4/transactions.js` — dictionary-encoded, cleaned dataset (17,080 baskets,
  3,653 items); provided, unmodified;
- `week4/index.html`, `week4/style.css`, `week4/readme.md` — provided scaffold.

Open `week4/index.html` in a modern browser. No build, no server, no install:
the page works from a `file://` URL and runs the browser self-check harness
(11/11 PASS).

Course repository: <https://github.com/dryjins/RecSys-LLMs>