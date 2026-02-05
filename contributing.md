---
layout: page
title: Contributing
permalink: /contributing/
description: Contribute to TransHarbor's open source codebase. Built with Flutter and PocketBase, using test-driven development practices.
---

# Contribute Code

**TransHarbor is open source (AGPL-3.0). We welcome contributions.**

## Tech Stack

**Frontend:** Flutter (iOS, Android, web)  
**Backend:** PocketBase (Go + SQLite)  

## Development Approach

**Test-driven vibe coding:** Write code that works, write tests that prove it works, make sure the vibe is right. Not dogmatic TDD, not cowboy coding. Tests capture what should happen.

## Process

**1. Get set up**
```bash
# Fork the repo
git clone your-fork
# Follow README for setup
```

**2. Make changes**
- Pick an issue or fix a bug
- Write your code
- Write tests
- Make sure it works

**3. Squash your commits**
```bash
git rebase -i HEAD~n
# Squash all commits into one
# Clear commit message
git push --force
```

**One PR = one commit.** Clean history matters.

**4. Open PR**
- Clear title and description
- Reference issues
- We'll review and merge

## Commit Messages

Good: "Add user blocking to moderation tools"  
Bad: "fix stuff"

## What To Work On

- Bug fixes
- UI/UX improvements
- Accessibility features
- New features (discuss first in issues)
- Documentation
- Tests

## Code Style

Follow existing style. We're not strict, just consistent.

**Flutter/Dart:** Standard Dart conventions  
**PocketBase/Go:** Standard Go conventions

## Testing

Test what matters:
- User-facing functionality
- Critical moderation features
- Data integrity
- Security-sensitive code

Don't test trivial stuff.

## What We Provide

- Recognition in CONTRIBUTORS file
- Letters of recommendation for regular contributors
- Real project experience

**What we don't provide:** Pay (we're volunteer-run)

## Get Started

**Repo:** [github.com/transharbor-org/transharbor](https://github.com/transharbor-org/transharbor)  
**Issues:** [github.com/transharbor-org/transharbor/issues](https://github.com/transharbor-org/transharbor/issues)  
**Questions:** [support@transharbor.org](mailto:dev@transharbor.org)

---

*AGPL-3.0 licensed. Your code protects trans people worldwide.*