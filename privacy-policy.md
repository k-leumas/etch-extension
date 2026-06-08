---
layout: default
title: Privacy Policy
permalink: /privacy-policy/
---

# Etch Privacy Policy

Last updated: June 7, 2026

## Overview

Etch is a browser extension that lets you bookmark moments in supported AI conversations and jump back to them instantly.

Etch stores your bookmarks locally in the browser. It does not sync bookmark data to Etch-operated servers.

## Data Etch Handles

Etch may store the following data locally in the browser:

- Bookmark text selected from supported AI conversation pages
- Bookmark identifiers used to relocate saved items
- Conversation URLs and hostnames needed to reopen or jump within the same conversation
- Extension settings such as onboarding state and UI preferences
- Temporary jump state used to restore navigation inside a conversation

## How Etch Uses Data

Etch uses this data only to provide its core functionality:

- Save bookmarks inside supported AI conversation pages
- Show saved bookmarks in the extension popup
- Reopen a bookmarked conversation
- Jump back to a saved location in the current conversation
- Remember user preferences and onboarding state

## Analytics

Etch sends anonymous usage events to PostHog (EU) to understand how the extension is used. No bookmark content, conversation text, or page URLs are included in any event.

Each installation is assigned a random identifier that is not linked to any account, name, or personal information. It is stored locally and used to deduplicate event counts and associate an uninstall event with the prior install.

If you remove Etch, the browser opens a single PostHog tracking URL so the uninstall can be counted. No other data is sent at that point.

There is no in-extension opt-out. Removing the extension stops all data collection.

**Events sent:**

| Event | Properties |
|---|---|
| `extension_installed` | — |
| `extension_updated` | update reason |
| `extension_uninstall` | — (via uninstall URL) |
| `welcome_open` | — |
| `tour_step` | step id, step index |
| `onboarding_complete` | — |
| `onboarding_abandon` | last step id, last step index |
| `bookmark_create` | whether a scroll ratio was captured |
| `bookmark_delete` | remaining bookmark count, source |
| `conversation_delete` | bookmark count |
| `clear_all` | bookmark count |
| `collections_open` | total bookmarks, total conversations |
| `panel_open` | bookmark count, whether bookmarks existed, source |
| `panel_close` | bookmark count |
| `panel_scroll` | surface (panel or popup), scroll depth bucket |
| `jump_attempt` | jump source |
| `jump_succeed` | jump source, visit number |
| `jump_fail` | jump source, AI service hostname, provider name |

PostHog's privacy policy is available at https://posthog.com/privacy.

## Where Data Is Stored

Bookmark data is stored in the browser's extension storage area on your device and is not transmitted to Etch-operated servers.

Etch does not sell user data.

Etch does not use user data for advertising, profiling, or creditworthiness decisions.

## Sharing

Etch does not share bookmark data with third parties.

Anonymous usage events are sent to PostHog as described above.

## Permissions

### Required permissions

| Permission | Why it is needed |
|---|---|
| `storage` | Save bookmarks, settings, analytics identifier, and temporary jump state to the browser's local extension storage |
| `tabs` | Open the welcome page on install, return you to your previous tab after onboarding, and open bookmarked conversations from the popup |

### Site access

Etch requests access to the following AI services so it can run the bookmarking interface on those pages:

- chatgpt.com / chat.openai.com
- gemini.google.com / aistudio.google.com
- claude.ai
- copilot.microsoft.com
- perplexity.ai
- grok.com
- chat.mistral.ai
- poe.com
- huggingface.co
- you.com
- character.ai
- chat.deepseek.com
- pi.ai
- groq.com

Etch also requests access to `eu.i.posthog.com` to send analytics events.

Etch does not read or transmit the content of your conversations.

## Data Retention and Control

Users control the data stored by Etch through the extension UI and browser controls.

Removing bookmarks or uninstalling the extension removes locally stored extension data, subject to browser behavior.

## Security

Etch relies on the browser's extension storage and permission model for locally stored bookmark data. Analytics events are transmitted to PostHog over HTTPS.

## Changes

If Etch's data practices change, this policy will be updated before or with the relevant product release.

## Contact

For support or privacy questions, contact the developer through the support channel listed on the Chrome and Firefox store pages or the project's public issue tracker.
