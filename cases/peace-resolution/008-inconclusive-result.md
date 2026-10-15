---
id: PR-008
title: Inconclusive Result, what can anyone do?
status: rules-derived
printing: third-2026
rules: ["§10.2 Neither Side is Victorious p.29", "table p.29"]
tags: [peace-resolution, inconclusive, white-peace, negotiated-peace, bot, npr]
source: ""
contributors: []
---

# Inconclusive Result: what can anyone do?

## Setup
A is at war and Provinces have changed hands, so it isn't an Automatic White Peace, but nobody meets Partial or Total Victory.

## The question
Can A still force terms?

## Resolution
| Enemy | What happens |
|---|---|
| **Human PR** | Only **White Peace** or a **Negotiated Peace** (both must agree). Nobody can enforce terms **unless a player Surrenders**. |
| **NPR** | NPR **always accepts** a White Peace if offered. |
| **Bot** | A Bot **might** accept a White Peace (§10.1 step 3). On an Inconclusive Result, it will accept one offered **if you have captured Provinces of greater Tax Value from it than it has captured from you** (pp.29-30). |

Otherwise the war simply continues. You aren't obliged to end a war (§10.1 step 3).

## Status notes
Straight from §10.1 and §10.2. The White Peace term text (p.30) says occupied Provinces return to their Lawful Owners and "any PRs involved lose 1 [Prestige] each". The official flow chart (Player Aid B) confirms the Prestige loss also applies to an **Automatic** White Peace: each PR loses 1 Prestige per White Peace it enters ([Q8](../../docs/open-questions.md), now answered).
