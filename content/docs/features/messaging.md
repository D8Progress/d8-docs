---
title: 'Messaging'
linkTitle: 'Messaging'
weight: 11
description: >
  Rich messaging with threads, reactions, polls, and search.
---

> **Note:** Communication features are available starting in version 0.9.

Deliber8 Progress messaging goes beyond basic chat. Organize conversations with threads, make decisions with polls, find anything with search, and keep important messages pinned.

## Basic Messaging

### Composing Messages

Type your message and press **Enter** to send. Messages support:

- **Bold** — `**text**` or Ctrl+B
- **Italic** — `*text*` or Ctrl+I
- **Code** — `` `inline code` `` or ``` for blocks
- **Links** — Paste URLs or `[text](url)`
- **Lists** — Start lines with `-` or `1.`

Maximum message length: 4,000 characters.

### Editing Messages

1. Hover over your message
2. Click the edit icon (pencil)
3. Make changes
4. Press **Enter** to save

Edited messages show "(edited)" indicator.

### Deleting Messages

1. Hover over your message
2. Click the delete icon (trash)
3. Confirm deletion

Messages are removed from view but may be retained for moderation purposes.

---

## Mentions

Get someone's attention or reference channels and entities.

### People Mentions

| Mention   | Who Gets Notified  |
| --------- | ------------------ |
| @username | That specific user |
| @everyone | All space members  |
| @here     | Online members     |

Type `@` and start typing a name to see suggestions.

### Channel References

Type `#channel-name` to link to another channel. Readers can click to jump there.

### Entity References

Reference D8 Progress items directly in messages:

| Reference      | Links To        |
| -------------- | --------------- |
| @goal:name     | A specific goal |
| @task:name     | A specific task |
| @activity:name | An activity     |

Shows a preview card with entity details.

---

## Threading

Keep conversations organized by replying to specific messages.

### Starting a Thread

1. Hover over a message
2. Click **Reply**
3. Type your response
4. Press **Enter**

Your reply appears nested under the original message.

### Viewing Threads

- **Inline** — Replies show directly under the parent
- **Thread View** — Click "View thread" for focused view
- **Reply Count** — Parent shows number of replies

### When to Thread

Use threads when:

- Responding to a specific question
- Having a side conversation
- Multiple discussions happening at once

Don't thread when:

- It's a simple continuation of the main topic
- You want everyone to see the message prominently

---

## Reactions

Express yourself without cluttering the chat.

### Adding Reactions

1. Hover over a message
2. Click the emoji icon
3. Select an emoji
4. Click to add

### Removing Reactions

Click your reaction again to remove it.

### Reaction Counts

Messages show:

- Which emojis were used
- How many of each
- Who reacted (hover to see names)

### Quick Reactions

Common reactions:

| Emoji | Common Meaning      |
| ----- | ------------------- |
| 👍    | Agree / Sounds good |
| ✅    | Done / Confirmed    |
| 👀    | Looking into it     |
| 🎉    | Celebration         |
| ❤️    | Love it             |

---

## Polls

Make group decisions quickly with polls.

### Creating a Poll

1. In the message composer, click **📊** (poll icon)
2. Enter your question (max 300 characters)
3. Add options (2-10 options, max 100 characters each)
4. Configure settings:
   - **Allow Multiple** — Users can vote for multiple options
   - **Anonymous** — Hide who voted for what
   - **Show Results** — Always, after voting, or after poll closes
5. Optional: Set a deadline
6. Click **Create Poll**

### Voting

1. Click an option to vote
2. Results update in real-time
3. Change your vote if allowed

### Poll Results

See:

- Vote counts per option
- Percentage bars
- Voter names (unless anonymous)
- Total votes

### Closing Polls

Poll creators and admins can close polls to prevent further voting.

### Poll Examples

**Quick Decisions:**

> 📊 Pizza or tacos for dinner?
>
> - 🍕 Pizza (4 votes)
> - 🌮 Tacos (3 votes)

**Event Planning:**

> 📊 Which weekend works for the BBQ?
>
> - ☑️ Allow multiple selections
> - May 15-16 (5 votes)
> - May 22-23 (3 votes)
> - May 29-30 (6 votes)

**Anonymous Feedback:**

> 📊 How are you feeling about the project?
>
> - 👁️ Anonymous voting
> - 🟢 Great (?)
> - 🟡 Okay (?)
> - 🔴 Struggling (?)

---

## Pinned Messages

Save important messages for easy access.

### Pinning a Message

1. Hover over the message
2. Click the menu (⋮)
3. Select **Pin**

### Who Can Pin

- Authors can pin their own messages
- Owners and admins can pin any message

### Viewing Pinned Messages

1. Click the **📌 Pinned** button in the channel header
2. See all pinned messages with:
   - Original content
   - Who pinned it and when
   - Click to jump to original location

### Unpinning

1. Open Pinned panel
2. Click **Unpin** on the message

### When to Pin

- Important announcements
- Final decisions
- Reference information
- Event details
- Rules or guidelines

---

## Search

Find any message across channels and spaces.

### Basic Search

1. Click the search icon or press **Ctrl+K**
2. Type your search terms
3. View results

### Search Scope

| Scope        | Searches                  |
| ------------ | ------------------------- |
| This Channel | Current channel only      |
| Entire Space | All channels in the space |

### Filters

Narrow results by:

| Filter     | Options                              |
| ---------- | ------------------------------------ |
| Author     | Select specific user                 |
| Date Range | Today, Past week, Past month, Custom |

### Search Results

Results show:

- Author with avatar
- Channel name (for space-wide search)
- Timestamp
- Message snippet with highlights

### Jump to Message

Click a result to:

1. Navigate to the channel
2. Scroll to the message
3. Highlight it briefly

### Search Tips

- Use quotes for exact phrases: `"meeting notes"`
- Combine with filters: author:alex + past week
- Check space-wide for thorough searches

---

## Attachments

Share files directly in messages.

### Uploading Files

1. Click the attachment icon (📎) or drag files into the composer
2. Add up to 10 files per message
3. Each file max 10MB

### Supported Formats

| Category  | Formats                   |
| --------- | ------------------------- |
| Images    | JPEG, PNG, GIF, WebP, SVG |
| Documents | PDF, Word, Excel          |
| Media     | MP3, WAV, MP4, WebM       |
| Archives  | ZIP, RAR                  |
| Text      | TXT, CSV                  |

### Viewing Attachments

- Images display inline with lightbox view
- Documents show preview or download link
- Media plays inline

---

## Link Previews

When you paste a URL, Deliber8 Progress generates a preview:

- **Title** — Page title
- **Description** — Page summary
- **Image** — Thumbnail if available
- **Site** — Favicon and domain

Helps provide context without leaving the conversation.

---

## Direct Messages

Private conversations outside of spaces.

### 1:1 Messages

Start a direct conversation:

1. Click **Direct Messages** in sidebar
2. Click **+ New Conversation**
3. Select a person
4. Start chatting

### Group Messages

Create a group chat:

1. Click **+ New Conversation**
2. Select multiple people (up to 9)
3. Name your group (optional)
4. Choose an icon (optional)
5. Start chatting

### DM Features

Direct messages support:

- Text and attachments
- Reactions and mentions
- Message search
- All the same rich content as channels

Direct messages do NOT support:

- Threads (channels only)
- Polls (channels only)
- Pinning (channels only)

---

## Tips for ADHD Brains

### Use Reactions Instead of Replies

Instead of typing "sounds good!" to every message, just react with 👍. Less noise, same acknowledgment.

### Pin Everything Important

Don't trust yourself to remember where that important message is. Pin it immediately.

### Search First, Ask Second

Before asking "did we decide on X?", search for it. Past you probably documented it.

### Thread Aggressively

When a conversation goes on a tangent, move it to a thread. Keeps the main channel focused.

### Mute Noisy Channels

If a channel distracts you but you still need access:

1. Right-click the channel
2. Select **Mute**
3. Check it when you're ready

No notifications, but still accessible.
