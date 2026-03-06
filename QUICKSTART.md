# Naggler — Quick Start Guide

## What is Naggler?

Naggler is an **attention ledger** — a lightweight desktop app that pings you every few minutes and asks one simple question: *what are you actually working on right now?*

It's not a to-do app. It's not a time tracker. It's a behavioral mirror that shows you where your focus really goes vs. where you think it goes.

## Getting Started

### 1. Launch & Add Your Priorities

When you open Naggler, you'll see the **Priorities** list. Add 3-5 things you're working on today. Drag to reorder — #1 is your top priority.

### 2. Start a Session

Click **Start Session** when you sit down to work. This starts the check-in timer and shows the edge tab at the top of your screen.

### 3. Respond to Check-ins

Every few minutes (default: 5), a small prompt pops up asking what you just worked on. One click on the matching task — that's it. Takes under 2 seconds.

**Your options:**
- **Click a task** — logs that you were working on it
- **Other** — for unplanned work (meetings, distractions, etc.)
- **Snooze** — skip this check-in (still logged as data)

### 4. Watch the Patterns

The **Time Snapshot** panel shows a pie chart of where your time actually went. The **gap analysis** compares your actual time distribution against your priority ranking — the delta between intention and reality is the insight.

### 5. End Your Session

Click **End Session** when you're done working. Your data is saved locally and preserved across sessions.

## Key Features

### Edge Tab
The thin strip at the top of your screen shows Naggler is running. Click to toggle the main window. Double-click to bring it to front. Right-click for snap options and to display your top task name.

### Task Snooze
Hover over a task and click 💤 to snooze it (1 hour, 4 hours, 1 day, or 1 week). Snoozed tasks disappear from your list and check-in prompts. Click the "snoozed" count in the header to restore them.

### Done Tasks
Click ✓ on a task to mark it done. Done tasks appear as a count you can click to restore or archive all.

### Focus Gap Analysis
After a few check-ins, the gap analysis shows whether your time matches your priorities:
- **Green** = aligned with your ranking
- **Amber** = over-invested relative to rank
- **Red** = under-invested relative to rank

### Auto-Promote
If you're spending more time on a lower-ranked task, Naggler will suggest promoting it up in your list.

### Export
File > Export lets you save your data as CSV or JSON for any date range.

## Tips

- **Keep your list short.** 3-5 active tasks is the sweet spot. Use snooze for things you're not touching today.
- **Be honest.** The value is in accurate data, not aspirational answers. If you were on Twitter, pick "Other."
- **Check the gap.** The daily summary shows where your stated priorities diverge from your actual behavior. That's the insight.
- **Don't overthink it.** One click, move on. The check-in should take less than 2 seconds.

## Data & Privacy

- All data is stored **locally** on your machine at `~/.naggler/naggler.db`
- **Nothing is sent anywhere.** No accounts, no cloud, no telemetry.
- Use File > Export to back up your data anytime.

## Keyboard Shortcuts

- **Close window** — hides to background (click edge tab to reopen)
- **File > Quit** — fully exits the app

## Need Help?

Found a bug or have feedback? Reach out to the developer — your input shapes what gets built next.
