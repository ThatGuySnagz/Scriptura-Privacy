# Scriptura privacy policy

**Last updated:** October 29, 2026  
**Operator:** Snagz  
**Email:** Email Coming Soon  
**Support community:** [https://rootapp.gg/ADIrnoSWjAqJWtCq6dA2Vg](https://rootapp.gg/ADIrnoSWjAqJWtCq6dA2Vg)

This policy describes how Scriptura handles information. It covers the Scriptura app inside [Root](https://rootapp.com) and this policy page. Root accounts, communities, messages, and hosting are covered by [Root’s privacy policy](https://www.rootapp.com/privacy-policy).

## Who this covers

Scriptura is a Bible app that runs inside Root, operated by Snagz. Each community that installs Scriptura gets its own copy of the app on Root. Members use it through the Root client. Scriptura does not operate a separate website for reading the Bible, and it does not create accounts of its own.

## What the app is

Scriptura shows the King James Version, the American Standard Version (1901), and the Douay-Rheims. That Bible text ships inside the app package. While the app runs, it does not call a verse API, an analytics service, or an ad network.

A member can read a chapter, see a verse of the day, and, in a community, use channel commands and an optional daily verse post. Community owners and named editors can choose the channel, the time, and the translation used for those community features.

## On the member’s device

The Root client on the member’s device stores two preferences in local storage:

- The chosen translation, under the key `bible-app.translation`.
- The reading place, under the key `bible-app.place`, as book, chapter, and verse.

Those values stay in that Root client. Scriptura does not send them to a server of its own. They are used only to reopen the same translation and place on that device.

## Per community, on Root

For each community, Scriptura stores settings in Root’s app storage for that community:

- The translation used for channel commands and the daily verse.
- The channel chosen for the daily verse.
- The daily verse schedule: hour, minute, and time zone.
- A stamp that records that the day’s verse was already posted to that channel, so the same day is not posted twice.

Root’s own settings store which roles and members may edit those settings, besides the community owner. When someone opens Settings, Scriptura reads that person’s Root user id only to decide whether they are the community owner or a named editor. Scriptura does not save that user id, and it does not build a member list of its own.

To fill the channel picker, Scriptura reads the names and ids of text channels the community has made visible to the app. It keeps only the channel an editor saves.

Root hosts this storage. Snagz does not run a separate database for Scriptura.

## Channel commands

Scriptura receives new messages in channels it can see so it can answer `!verse` and `!compare`. It uses the message text only to decide whether the message is one of those commands and, if it is, to write a reply. The reply is posted in the channel as the app.

Scriptura does not store the message text, the author’s id, or a history of commands. The only channel permission the app asks for is permission to post messages. A community can turn that permission off in Root.

## What Scriptura does not do

Scriptura does not create its own accounts, collect email addresses, set cookies, sell personal information, share data with advertisers, or use third-party trackers. It does not use member content or Bible reading activity to train models.

## This policy page

This page is hosted by GitHub Pages. GitHub may keep ordinary access logs for visits to the page, as described in the [GitHub Privacy Statement](https://docs.github.com/en/site-policy/privacy-policies/github-privacy-statement). The Scriptura app does not embed this site, and opening the app does not send a visit here.

## How information is used

Scriptura uses the information above only to run the app:

- Device preferences restore the member’s translation and reading place.
- Community settings choose the command translation and, when an editor turns it on, post the daily verse in the chosen channel at the chosen time.
- The Root user id check limits Settings to the community owner and named editors.
- Command text is used in the moment to answer `!verse` and `!compare`.

## How long data stays

Translation and reading-place preferences stay on the device until the member clears them or Root client storage for the app is removed. Community settings stay until an editor changes them or the community removes the app. Command text is not kept after the reply is sent.

## Choices

A member can change the translation and reading place in the app, and can clear the Root client’s local storage for Scriptura. The community owner, or a member named as an editor, can change the daily verse channel, schedule, and command translation, or turn the daily post off by clearing the channel. Removing the app from a community is an action in Root. Closing or deleting a Root account is an action in Root, under Root’s own policy.

## Children

Scriptura does not run its own signup and does not knowingly collect personal information from children. Account creation, including any age rules, is handled by Root.

## Changes

When this policy changes, the page will show a new last-updated date. The version on this page is the current policy.

## Contact

Snagz  
Email: Email Coming Soon  
Support community: [https://rootapp.gg/ADIrnoSWjAqJWtCq6dA2Vg](https://rootapp.gg/ADIrnoSWjAqJWtCq6dA2Vg)
