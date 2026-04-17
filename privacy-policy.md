---
layout: default
title: Privacy Policy
permalink: /privacy-policy/
---

# Etch Privacy Policy

Last updated: April 17, 2026

## Overview

Etch is a browser extension that lets users bookmark moments in supported AI conversations and jump back to them later.

This version of Etch stores data locally in the user's browser. It does not sync bookmark data to Etch-operated servers.

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

## Where Data Is Stored

Etch stores data in the browser's extension storage area on the user's device.

Etch does not sell user data.

Etch does not use user data for advertising, profiling, or creditworthiness decisions.

Etch does not transmit bookmark data to Etch-operated servers in this release.

## Sharing

Etch does not share bookmark data with third parties in this release.

If a user chooses to copy a bookmark link, Etch writes that link to the clipboard at the user's request.

## Permissions

Etch uses these Chrome extension permissions:

- `storage` to save bookmarks, settings, and temporary navigation state
- `clipboardWrite` to copy bookmark links when the user requests it
- `tabs` to open the welcome page, return the user to the previous tab after onboarding, and open bookmarked conversations from the popup
- Host permissions on supported AI chat domains so Etch can run its content script where bookmarking features are available

## Data Retention and Control

Users control the data stored by Etch through the extension UI and browser controls.

Removing bookmarks or uninstalling the extension may remove locally stored extension data, subject to browser behavior.

## Security

Because this release stores data locally, Etch relies on the browser's extension storage and permission model for local data handling.

If a future release transmits user data over the internet, Etch will update this policy and use secure transport for those transmissions.

## Changes

If Etch's data practices change, this policy will be updated before or with the relevant product release.

## Contact

For support or privacy questions, contact the developer through the support channel listed on the Chrome Web Store page or the project's public issue tracker.
