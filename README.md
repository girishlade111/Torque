# Torque

An educational commit-history walkthrough for building an email-marketing platform ("Torque"), organized as conventional-commit style learning logs.

## What it is

This repo documents, commit by commit, how a campaign/email-marketing system could be developed — features, fixes, refactors, perf work, CI, and tests — expressed through realistic conventional-commit messages and learning notes. It's a study/reference resource, not a runnable application.

## Contents

- **`data.txt`** — 1,321-line timestamp log of commit points (Oct 2024 – Sep 2025), used as practice material for commit-history analysis.
- **`edu-commit-log.txt`** — structured educational commit log initialized March 2026: batches of conventional commits (`feat`, `fix`, `test`, `ci`, `perf`, `style`, `refactor`, `chore`) describing the development of:
  - Email campaign scheduling system
  - Automation workflows
  - Subscriber management dashboard
  - Subscriber segmentation
  - Email template tests and rendering fixes
  - Bounce rate tracking and analytics tracking
  - Unsubscribe handling
  - Email delivery monitoring (SPF/DKIM, queue optimization, throughput tuning)

## Who it's for

Learners practicing Git workflows, conventional commits, and feature-planning breakdowns for a SaaS/email-marketing domain. Each commit line can be used as an exercise prompt ("implement this commit").

## Env vars / build

None — no code, no dependencies. Any file viewer or text editor works:

```bash
cat edu-commit-log.txt
```

## Credits

Built by Girish Lade — [https://ladestack.in](https://ladestack.in)
