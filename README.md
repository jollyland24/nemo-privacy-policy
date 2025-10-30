# Privacy Policy

**Last Updated:** October 2024

## Overview

nemo is a smart bookmark search extension that prioritizes your privacy. We are transparent about what data we collect and how it's used.

## Core Principle: Local-First Processing

By default, nemo works completely offline:
- ✅ Fuzzy search runs on your device, not on our servers
- ✅ Your bookmarks are read from your browser's local storage
- ✅ No data leaves your computer unless you enable sync

## Data Collection & Usage

### What We DON'T Collect (Default Behavior)
When using fuzzy search locally, nemo does **NOT** collect:
- ❌ Personal information (names, emails, addresses)
- ❌ Browsing history or visited websites
- ❌ Analytics, telemetry, or usage data
- ❌ Cookies or tracking pixels
- ❌ Search queries or bookmark titles*

*Bookmark data is read locally and never sent anywhere by default.

### What We DO Collect (Optional: Sync Feature Only)

**If you choose to enable bookmark sync**, you will:
- Log in with an email address
- Send your bookmarks to our servers for cloud sync
- Store an authentication token on your device

**What data is sent during sync:**
- Your email address (for account identification)
- Your bookmark titles, URLs, and folder structure
- A hash of your bookmarks (to track changes)
- Session/authentication tokens (httpOnly cookies)

**How we use this data:**
- Store your bookmarks on our servers (nemo-bookmark.vercel.app)
- Enable cross-device bookmark sync
- Authenticate your account for future sessions
- Track which bookmarks changed since last sync

**What we DON'T do with sync data:**
- ❌ We do NOT share your bookmarks with third parties
- ❌ We do NOT use your data for advertising or marketing
- ❌ We do NOT analyze or sell your bookmark data
- ❌ We do NOT track your browsing behavior

### Semantic Search Feature (AI Search)

When you click "AI Search":
- A new tab opens to our semantic search website
- Your search query is sent to our server for processing
- Your bookmarks can be uploaded for better search results
- Results are shown on the website (not stored on our servers)
- This feature is completely optional and separate from sync

## Browser Permissions Explained

| Permission | Why We Need It | Data Shared |
|------------|---|---|
| **Bookmarks** | To read and display your bookmarks | Only local access, never sent unless sync enabled |
| **Active Tab** | To capture current page when adding a bookmark | Only your current tab's title & URL |
| **Tabs** | To open bookmarks and search in new tabs | No data collected |
| **Scripting** | To inject search UI and enable communication | No data collected |
| **Storage** | To save auth tokens (sync feature) | Only if sync is enabled |
| **Host Permissions** | To make the extension work on all websites | No data collected |

## Security

- All data transmission to our servers uses **HTTPS encryption**
- Authentication tokens are stored in **httpOnly cookies** (safe from scripts)
- We do not store plaintext passwords
- Sync feature is completely optional

## Your Control

You can:
- ✅ Use nemo entirely offline (fuzzy search only)
- ✅ Disable sync at any time (your data is deleted from our servers)
- ✅ Use semantic search without bookmark sync
- ✅ Delete your account and all associated data

## Changes to This Policy

We may update this privacy policy occasionally. Continued use of nemo after changes means you accept the updated policy. We will notify users of significant changes via the extension.

## Questions or Concerns?

- 🐙 GitHub Issues: https://github.com/jollyland24/markie/issues
- 📄 View our code: https://github.com/jollyland24/markie

---

**Bottom Line:** nemo respects your privacy by default. Sync and AI Search are powerful optional features, but you never have to use them. Your bookmarks are yours alone.
