# Scriptura privacy policy

This page is an outline, not the finished policy.

**Last updated:** not set  
**Operator:** [Your name]  
**Contact:** [contact email]

## Who this covers

Scriptura is a Bible app that runs inside [Root](https://rootapp.com), operated by [Your name]. This page will be the privacy policy for Scriptura. Root accounts, communities, and hosting are Root’s, not Scriptura’s.

## What the app is

Scriptura is a Root app. Each community that installs it gets its own server instance. Bible text for the King James Version, the American Standard Version, and the Douay-Rheims ships inside the app package. The app does not call a verse API, an analytics service, or an ad network while it runs.

## On the member’s device

The Root client on the member’s device stores two preferences in local storage: the chosen translation (`bible-app.translation`) and the reading place (`bible-app.place`, as book, chapter, and verse). Those values stay in that Root client. Scriptura does not send them to a server of its own.

## Per community, on Root

For each community, Scriptura stores settings on Root: the translation used for channel commands, the channel and schedule for the daily verse, and a stamp that records that the day’s verse was already posted. Root’s own settings store which roles and members may edit those settings. When someone opens Settings, the app reads that person’s Root user id only to decide whether they are the community owner or a named editor.

## Channel commands

The app sees new messages in channels it can read so it can answer `!verse` and `!compare`. It replies in the channel as the app. It does not store the message text, the author’s id, or a history of commands. The only channel permission the app asks for is permission to post messages.

## What Scriptura does not do

Scriptura does not create its own accounts, collect email addresses, set cookies, sell or share data with advertisers, or use third-party trackers.

## This GitHub Pages site

This policy page is hosted by GitHub Pages. GitHub may keep ordinary access logs for visits to the page. The app does not embed this site.

## How long data stays

Translation and reading-place preferences stay on the device until the member clears them or Root client storage for the app is removed. Community settings stay until an editor changes them or the community removes the app. Command text is not kept.

## Choices

A member can change the translation and reading place in the app. The community owner, or a member named as an editor, can change the daily verse and the command translation. Removing the app from a community is an action in Root.

## Children

Scriptura does not run its own signup. Account creation, including any age rules, is handled by Root.

## Changes

When the finished policy is published, and when it later changes, this page will show a real last-updated date.

## Contact

[Your name]  
[contact email]
