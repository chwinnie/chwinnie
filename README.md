# Winnie Cheng

Product manager and ex–frontend engineer who builds. Since Feb 2026: **2,879 commits** and **571 merged PRs** across my private AI projects, built with Claude Code. The repos are private, so these are the stats.

![Commits per day over the last year, across all my GitHub accounts](contributions.svg)

## Motor accessibility projects

Apps for people with motor challenges. Motor challenges are common in autism: a large U.S. study found [~87% of autistic children at risk for motor impairment](https://pmc.ncbi.nlm.nih.gov/articles/7297441). They can make it hard to speak clearly, type fast, or even point: a person may intend to point at one thing, but their body points at something else. That makes daily living and communication difficult.

### Faber

AI-adaptive courses for adults with apraxia, who can't use typical online courses because they can't reliably type.

- **Impact:** in beta with 8 families; 5 adults engaged for 30+ minutes vs. ~5 minutes with online courses
- ~1,413 commits, ~272 merged PRs (May–Nov 2026), including V1 course generation built in an earlier repo
- 591 product and design decisions logged in specs, with rationale
- 31 eval reports gating AI prompt changes
- A weekly scheduled cloud routine finds news stories for lessons
- [Live site](https://vhelper-staging.vercel.app/about)

### SpeechBridge

Generates speech exercises and a conversation guide from photos of the person's day, so they practice using speech to describe it. Also turns speech-therapy session transcripts into step-by-step prompting guides, so untrained aides can run speech practice between sessions.

- **Impact:** helped my previously nonverbal brother use 1–2 words spontaneously; used by 2 autistic adults
- ~924 commits, ~185 merged PRs (May–Nov 2026)
- 195 product and design decisions logged in specs, with rationale
- Bake-off harness comparing a local LLM against Claude

### DailyLivingGuides

Generates short lessons for daily-living skills, like safety and post-lunch cleanup, answered on choiceboards adapted for apraxia. For example: "A big spill gets a ___ towel first, so it doesn't soak into the table." → hamster · **paper** · tickle · xylophone

- ~163 commits, ~21 merged PRs (May–Oct 2026)

### InstructionsBridge (abandoned)

The original vHelper prototype: a React app that walked aides through tasks step by step.

- **Impact:** learning project; discovered that step-by-step help works better as one-off AI generations that a human aide edits
- ~311 commits, ~87 merged PRs (Mar–Jun 2026)

### ChoiceBoard (paused)

Choiceboards, where people tap one choice out of large tap targets in randomized positions, help with reliable communication.

- **Status:** on pause until we can build a dynamic, AI-driven communication app, now specced as Faber's "Decide" feature
- ~35 commits, ~5 merged PRs (Feb–Jun 2026)

## Business automation workflows

### vHelper

Claude Code jobs that manage scheduling, billing, invoice checks and budget tracking for my autistic brother's state-funded services across 8 vendors, plus a nightly brief that pulls the day program's email and texts into one summary.

- **Impact:** caught 10 incorrect invoices and avoided 10+ weeks of payment delays
- Runs as 3 scheduled cloud routines (monthly invoicing, hourly inbox triage, nightly daily brief) and a nightly local job that collects iMessages
- ~16 commits, ~1 merged PR (Apr–Sep 2026) across the repos that collect the data and book rooms

## Personal automation workflows

### BillCheck

Six Claude Code skills that check medical bills against insurance. They read UMR insurance claims plus bills (photos and PDFs), and flag any bill that charges more than the claim says we owe. They also track payment and reimbursement status for claims we file ourselves: when a provider doesn't bill insurance directly, we submit the claim and insurance pays us back.

- **Impact:** saved $9–15K in billing errors
- ~17 commits (Apr–Jul 2026)
