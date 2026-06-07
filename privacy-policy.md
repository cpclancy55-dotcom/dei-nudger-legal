# DEI Nudger — Privacy Policy

*Last updated: June 2026*

## What DEI Nudger does
DEI Nudger is a Chrome extension that provides real-time inclusive language 
coaching during video calls. It listens to your microphone and identifies 
language patterns worth reconsidering, then shows a brief, research-grounded 
nudge to help you course-correct in the moment.

## What data is processed

### Speech transcripts
Short snippets of your speech are analyzed to detect non-inclusive language 
patterns. The vast majority of detection happens instantly and entirely on 
your device using a local pattern library — no data leaves your browser.

For patterns not matched locally, a short text snippet is sent to a secure 
cloud function for semantic analysis. This text is processed ephemerally: 
it is never logged, stored, or retained on any server after the analysis 
is complete.

### Session history
A record of nudges from each call (category, suggestion, and trigger phrase) 
is stored locally in your browser using Chrome's built-in storage. This data 
never leaves your device and is fully under your control.

## What data is NOT collected
- Your name, email address, or any account information
- Audio recordings of any kind — only text transcripts
- Information about other call participants
- Browsing history or activity outside supported video call platforms
- Any data from calls when the extension is paused or disabled

## Your microphone
DEI Nudger does not independently request microphone access. It operates 
within the video call tab where you have already granted microphone 
permission to the call platform (Google Meet, Zoom, or Microsoft Teams). 
It only processes your own microphone input — not other participants.

## Third-party services
When local pattern matching does not find a result, short transcript 
snippets are sent to:
- **Anthropic** (claude.ai) for natural language analysis

All third-party processing is ephemeral. No transcript data is retained.

## Your controls
- **Pause/resume** the extension at any time using the toggle in the popup
- **Clear session history** at any time from the extension popup
- **Uninstall** the extension at any time — this removes all locally 
  stored data immediately

## Changes to this policy
If this policy changes materially, the updated date at the top of this 
page will reflect it.

## Contact
Questions or concerns? Reach out at [cpclancy55@gmail.com]
