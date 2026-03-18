---
title: Design systems that actually scale
description: What I've learned from building design systems at fintech companies — and what most teams get wrong.
date: 2025-01-10
tags: [Design Systems, Process]
---

A design system isn't a component library. That's the mistake I see most teams make.

A component library is a collection of UI elements. A design system is the shared language — the decisions, the principles, the documentation — that helps teams build coherently. The components are just the output.

## What gets teams in trouble

When I joined Zeni AI, we had a Figma file with 200+ components and a Storybook with about 60% coverage. Designers were working one way, engineers another, and every new feature created a quiet little fork.

The problem wasn't the components. It was the absence of **decision-making infrastructure**.

Nobody knew why the button had 8px padding. Nobody knew when to use a modal vs. a drawer. Nobody could answer "is this in the design system?" with confidence.

## What actually helps

**1. Document the why, not just the what.**

Every token, every pattern — write down why it exists. Not just `color-primary: #CF4B00` but "this is our action color, used for clickable elements that require user intent." That context is what survives team changes.

**2. Treat inconsistency as a bug, not a style preference.**

If a designer made a one-off component, it's a signal — either the system is missing something, or the use case is genuinely unique. Both need a decision, not silence.

**3. Design systems are living docs.**

The teams I've seen kill their own system do it by treating it as "done." A system that doesn't evolve with the product becomes a constraint instead of an accelerant.

---

These aren't revolutionary ideas. But the gap between knowing them and actually practicing them is where most design systems fall apart.
