# CookieMute Privacy Policy

**Effective date: 2026-11-01**

CookieMute is a browser extension that automatically rejects cookie consent banners. It is designed to work entirely on your device.

## Summary

- CookieMute does **not** collect, transmit, sell, or share any user data.
- CookieMute makes **no network requests**.
- There are no analytics, ads, trackers, or remote configuration.

## What the extension processes

To find a cookie consent banner, the content script reads the page's DOM in memory: element text, attributes, and layout. This happens locally on the page you are viewing. Page content is never recorded, stored, or sent anywhere.

## What is stored on your device

The extension stores the following settings in `chrome.storage.local`:

- whether automatic rejection is enabled;
- whether the optional hide fallback is enabled;
- the list of whitelisted site hostnames you added;
- a local count of banners handled.

This data stays in your browser profile. It is not synchronized to a server. Removing the extension deletes it.

## Permissions

- **storage** — save the settings listed above locally.
- **activeTab** — let the toolbar popup identify the current site for the whitelist and send a one-time reject request when you click the extension.
- **Content script on all sites** — cookie banners can appear on any website, so the script must run on the page you are viewing to detect and dismiss them.

## Third parties

CookieMute has no third-party services, SDKs, or data sharing.

## Changes

Any change to this policy will be published in this file at
<https://github.com/chenbin2015/cookiemute-support/blob/main/PRIVACY.md>.

## Contact

Questions or requests: please open an issue at
<https://github.com/chenbin2015/cookiemute-support/issues>.
