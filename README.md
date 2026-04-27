KB-005: You're Using AI Wrong (Here's How to Fix That)
Klaus Builds · AI Tooling · Prompting

A practical guide to writing better prompts — with copy-paste templates you can use today.


What This Is
This repo is the companion resource for KB-005, a Klaus Builds blog post on prompt engineering for everyday people — product owners, hobbyists, DIYers, and anyone who wants to get more out of their AI tools.
The post covers the prompting framework that Anthropic's own team uses, broken down into plain language with real examples. No CS degree required.
Read the full post: Klaus Builds on Hashnode

What's In This Repo
kb005-prompting-guide/
├── README.md                   ← you are here
├── kb005-blog-post.md          ← full blog post in markdown
└── templates/
    ├── prompt-general-starter.txt    ← universal starter, adapt to anything
    ├── prompt-user-story.txt         ← vague request → developer-ready user story
    ├── prompt-release-notes.txt      ← clean, customer-facing release notes fast
    ├── prompt-diy-project.txt        ← budget home improvement planning
    └── prompt-restoration.txt        ← systematic restoration plan (bike, car, furniture)

How to Use the Templates
Every template follows the same pattern:

Copy the whole block
Paste it into Claude, ChatGPT, or whatever AI tool you use
Fill in everything inside [brackets]
Send it

That's it. The structure does the heavy lifting.
Quick start
If you're new to this, start with prompt-general-starter.txt. It's the universal template that works for almost any task. Use it for a week, notice what works, refine it, and save your best version. That's your first reusable prompt asset.

The Five-Part Framework (TL;DR)
Every template in this repo is built on the same foundation:
PartWhat It DoesRole + GoalSets the lens — tells the AI who it is and what success looks likeDynamic ContentThe raw material — paste your notes, request, or situation hereStep-by-step instructionsGuides the reasoning — tell it how to think, not just what to produceExamplesShows what good looks like — even one example dramatically improves outputRepeat critical constraintsPrevents drift — your most important rule, said twice
Full breakdown with real examples in the blog post.

Template Previews
User Story Writer
For product owners turning a vague Slack message into a developer-ready story with acceptance criteria and a list of ambiguities to clarify.
Release Notes Writer
For writing clean, customer-facing release notes under 150 words — without exposing internal technical details.
DIY Home Improvement Planner
For planning a budget refresh of any room. Give it your constraints (skill level, budget, renter vs. owner) and get a prioritized action plan with cost estimates.
Restoration Project Planner
For any neglected vehicle, furniture, or equipment. Works for motorcycles, cars, vintage gear — give it the condition, your skill level, and your goal, and get a phased, safety-first restoration plan.
General Starter
The universal template. Role, goal, context, instructions, output format. Adapt it to anything.

Who This Is For

Product owners who want to speed up user story writing and release notes
Hobbyists working on motorcycles, cars, or home projects
Anyone who uses AI regularly and wants more useful, consistent outputs

The framework works regardless of which AI tool you use.

Built By
Klaus Builds — AI tooling and workflow documentation for people who want to build smarter without needing a CS degree.

Portfolio: maximilian-wav.github.io
Blog: klausbuilds.hashnode.dev
LinkedIn: Max Albekier


License
MIT — copy it, fork it, adapt it. If you build something useful from these templates, I'd love to hear about it.

This is part of an ongoing series documenting real AI workflows, tools, and builds. Each KB post ships something you can use the same day.
