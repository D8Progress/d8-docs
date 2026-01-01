---
title: 'Linked Channels'
linkTitle: 'Linked Channels'
weight: 12
description: >
  Channels automatically connected to goals, tasks, and activities.
---

> **Note:** Communication features are available starting in version 0.9.

Linked channels bridge the gap between tracking and communication. They automatically connect to goals, tasks, activities, and other entities—posting updates when things change and keeping all related discussion in one place.

## What Are Linked Channels?

A **linked channel** is a special channel type that:

1. Connects to a specific D8 Progress entity (goal, task, activity, etc.)
2. Automatically posts system messages when the entity changes
3. Provides a dedicated space for discussing that entity

This means your team can see progress and discuss it without switching contexts.

## Supported Entity Links

| Entity Type | What Gets Posted                        |
| ----------- | --------------------------------------- |
| Goals       | Progress updates, milestone completions |
| Tasks       | Created, assigned, completed            |
| Activities  | Completions logged                      |
| Lists       | Items added, checked off                |
| Health Logs | New entries, updates                    |

## Creating a Linked Channel

### From the Channel List

1. Open a space
2. Click **+ New Channel**
3. Set type to **Linked**
4. Choose the entity type (Goal, Task, Activity, etc.)
5. Select the specific entity to link
6. Name the channel (often auto-suggested)
7. Click **Create**

### From the Entity

1. Open any goal, task, or activity
2. Click **Create Linked Channel** (in the actions menu)
3. Choose which space to create it in
4. Confirm

The channel is created and linked automatically.

## Automatic System Messages

When linked entities change, the channel receives automatic updates:

### Task Updates

> 📋 **Alex** created task: _Design homepage mockups_

> ✅ **Chris** completed task: _Design homepage mockups_

> 🔄 **Alex** updated task: _Design homepage mockups_ — changed deadline to May 15

### Goal Progress

> 📊 Goal progress updated: ████░░░░░░ **40%**

> 🎯 Milestone completed: _Phase 1 - Research_

> 🏆 **Goal completed!** Marketing Campaign is now 100% complete!

### Activity Completions

> 🎮 **Sarah** completed activity: _Weekly date night_
> ⭐⭐⭐⭐⭐ "Tried that new Italian place!"

### List Updates

> ➕ **Alex** added: _Buy groceries_

> ✅ **Chris** checked off: _Buy groceries_

### Health Logs

> 🏥 **Alex** logged health update for _Mom_

## Discussion in Linked Channels

Beyond automatic updates, team members can:

- **Discuss progress** — "Nice work on the mockups!"
- **Ask questions** — "What's blocking the API integration?"
- **Share updates** — "I'll have the revised design by tomorrow"
- **Coordinate work** — "Can someone review my PR?"
- **React to updates** — 🎉 on completions

All the regular messaging features work:

- Threads for focused discussion
- Reactions for quick feedback
- Mentions to notify specific people
- Search to find past conversations

## Example Workflows

### Family Goal: Plan Summer Vacation

**Goal:** Plan Summer Vacation (linked to #vacation-planning)

The channel shows:

> 📋 **Mom** created task: _Research destinations_

Team discusses in thread:

> "I vote for beach! Anyone else?"

> 🔄 **Dad** updated task: _Research destinations_ → assigned to Alex

> ✅ **Alex** completed task: _Research destinations_

> "Here are the top 3 options: [link]"

> 📊 Goal progress updated: ██░░░░░░░░ **20%**

### Work Project: Website Redesign

**Goal:** Website Redesign Q2 (linked to #website-redesign)

> 🎯 Milestone started: _Phase 1 - UX Research_

Discussion:

> "I've scheduled user interviews for next week"

> 📋 **PM** created task: _Conduct user interviews_

> 📋 **PM** created task: _Analyze competitor sites_

> ✅ **UX Lead** completed task: _Conduct user interviews_
> "Key insights: users want simpler navigation"

> 🎯 Milestone completed: _Phase 1 - UX Research_

> 📊 Goal progress updated: ████░░░░░░ **33%**

### Shared Shopping List

**List:** Groceries (linked to #shopping)

> ➕ **Alex** added: _Milk_

> ➕ **Alex** added: _Eggs_

> ➕ **Sarah** added: _Coffee_

> "I'm heading to the store in 20 min, anything else?"

> ➕ **Alex** added: _Bread_

> ✅ **Sarah** checked off: _Milk_

> ✅ **Sarah** checked off: _Eggs_

> ✅ **Sarah** checked off: _Coffee_

> ✅ **Sarah** checked off: _Bread_

> "All done! 🛒"

## Best Practices

### One Channel Per Major Goal

Don't create linked channels for every tiny task. Use them for:

- Major projects with multiple collaborators
- Goals that need ongoing discussion
- Activities the whole family/team cares about

### Keep Discussion Relevant

The channel is for discussing the linked entity. For off-topic chat:

- Use the main #general channel
- Start a new thread
- Move to direct messages

### Review Before Completing

Before marking a goal/task complete, check the linked channel:

- Any open questions?
- Everyone aligned?
- Documentation needed?

### Archive When Done

When a goal completes, consider archiving the linked channel:

1. Keeps sidebar clean
2. Preserves all history
3. Can be unarchived if needed

## Linked Channels vs Regular Channels

| Feature             | Regular Channel | Linked Channel |
| ------------------- | --------------- | -------------- |
| Manual posting      | ✅              | ✅             |
| Automatic updates   | ❌              | ✅             |
| Entity connection   | ❌              | ✅             |
| Progress visibility | ❌              | ✅             |
| Thread support      | ✅              | ✅             |
| Reactions           | ✅              | ✅             |
| Search              | ✅              | ✅             |

## Tips for ADHD Brains

### Let the System Update

Don't duplicate the system. If you complete a task, the linked channel posts it automatically. Just add context if needed:

**Good:** "Finally done! That last bug was tricky."

**Redundant:** "I completed the Design Homepage task."

### Use for Accountability

Linked channels create natural accountability. When you see:

> 📋 **You** created task: _Finish report_ — deadline: Tomorrow

...the whole team sees it. Built-in body doubling!

### Pin Important Decisions

When the team makes a decision in a linked channel, pin it:

> 📌 "We're going with Option B: blue color scheme"

Later, check pinned messages instead of scrolling through history.

### One Place for Everything

Before linked channels, you might have:

- Task tracker for status
- Chat app for discussion
- Email for updates
- Notes for decisions

Now it's all in one channel. Less context switching = less cognitive load.
