---
layout: policy
title: Privacy policy
permalink: /privacy/
---

## Privacy Policy

**Last updated:** 2026-10-06

Pet Med Reminder is built for people who don't want to think about whether their pet app is harvesting their data. Here is exactly what happens, including the usage data the app sends so we can see what works and what doesn't.

### Data we collect about you

**No account and no contact details.** Pet Med Reminder does not require an account, does not ask for your email, does not ask for your name, does not access your contacts, does not use your camera (except when *you* attach a pet photo, which never leaves your device and your iCloud), does not ask for your location, and does not use an advertising identifier. It does send anonymous usage analytics, and it tells Meta when the app is installed and opened, both described below.

### Data the app stores

The app stores the data *you* create: your pet names, the items you schedule, the doses you log, and any photos you attach. This data is stored:

1. **Locally on your iPhone**, in the app's private storage.
2. **In your personal iCloud account**, via Apple's CloudKit framework, if you have iCloud Drive enabled. This is the same mechanism that backs up Apple's own Notes, Reminders, and Health apps. Your data is stored in *your* iCloud — we have no access to it.

We do not have a server. We do not run a backend, and we do not have access to your iCloud data. We never see your photos. We do see some of what you enter in two ways, both described below: the usage analytics include the name you give a care item (for example "Apoquel"), and session recordings show the app's screens, which can include your pets' names and your doses.

### Anonymous usage analytics

The app records anonymous events through [PostHog](https://posthog.com) so we can see which features work and where people get stuck. The events include:

- Which screens you open, and what you do there: adding a pet or a care item, logging, skipping or backfilling a dose, marking a whole round of doses, catching up on missed days, exporting a report
- Counts: how many pets, care items, and caregivers you have, and how many doses were in a round or a catch-up (never who or what they are called)
- Each pet's species (dog or cat) and whether it has a photo (never the pet's name or the photo)
- Each care item's schedule: how often, how many times a day, and whether and how long it runs
- The name you type for a care item, for example "Apoquel" (up to 64 characters)
- Where a dose was logged (a notification, the Today screen, History, or catch-up) and how early or late
- Whether notifications are turned on, and what you do with a reminder: mark it given, skip it, snooze it, open the app from it, or dismiss it
- How far ahead your reminders are scheduled, and how long it has been since you last opened the app
- Repeated quick taps in one spot, which usually mean something isn't working
- Your device model, iOS version, app version, language, region setting, and time zone
- A timestamp, and a random ID the app creates when it is installed, so events from the same install can be grouped

PostHog also receives the IP address of each request and uses it to estimate an approximate location (city, region, and country).

**These events do not contain your name, your email, your Apple ID, your pet's name, your photos, or an advertising identifier, and we do not link the random install ID to you.** We never sell this data or use it for advertising.

### Session recordings

Starting with version 1.12.0, the app records how it is used through PostHog, so we can see where people get stuck. A recording is a series of screenshots of the app's own screens while you use it, with your taps and the app's diagnostic log messages. It shows the text on those screens, which can include your pets' names, your care items, and your doses. Photos, including your pet photos, are blocked out on your iPhone before anything is sent. Recordings never include anything outside the app, are grouped only by the random install ID, and are deleted after 30 days.

### This website

This website uses PostHog, the same analytics service as the app, to count visits. On each page view it records the page address, the referring page, your browser, device type and screen size, and an approximate location (country and city) that PostHog works out from your IP address. When you tap the App Store button, it records that tap, the page it was on and the campaign code in the button's link.

It does not set cookies. It keeps a random session ID in your browser tab's session storage, so that one visit counts once, and the ID is deleted when you close the tab. It does not create a profile for you, does not set an advertising identifier and does not record your session. This page, the privacy policy, records nothing.

One page works differently. `/vet` is the link printed on cards handed out by veterinary clinics. It records a single anonymous event so we can tell how many people that channel reaches: a timestamp, whether the visitor is on an iPhone, and the referring page if there is one. It discards the IP address.

Two pages also work differently. `/go/a` and `/go/b` are the links in our Instagram ads, and they send you straight on to the App Store. Before they do, they record one event: the page, the ad's campaign code and tags, the referring page, your browser, and an approximate location that PostHog works out from your IP address. They set no cookie, store no ID in your browser and create no profile.

### Meta (Instagram and Facebook ads)

Starting with version 1.12.1, the app includes Meta's software development kit (SDK), so we can count how many installs our Instagram and Facebook ads bring. The app sends Meta:

- One event the first time the app opens after it is installed, and one event each time the app opens
- With each event: your device model, iOS version, app version, language, time zone, mobile carrier, screen size, and a random ID that Meta's SDK creates on your iPhone
- The IP address of each request, which Meta receives as part of the connection
- If Meta's SDK itself crashes or hits an error, a report about Meta's own code

Apple also sends Meta an install report through SKAdNetwork, Apple's ad measurement system. That report contains no identifier for you or your device.

Meta does not receive your pets, your care items, your doses, your photos, or anything else you enter in the app. It does not receive your name, your email, your Apple ID, or your device's advertising identifier: the app never reads it. The app never asks for permission to track you. Without that permission, iOS blocks the parts of Meta's SDK that track, and Meta says it uses such events only through privacy-preserving methods (its "Aggregated Event Measurement") to measure ads. Meta handles this data under [its own privacy policy](https://www.facebook.com/privacy/policy/).

### Crash reports

If the app crashes, Apple's TestFlight or App Store Connect may automatically send us a crash report. These reports are anonymous and contain only information about *what* went wrong (stack trace, device model, iOS version) — not who you are or what was in your data.

### Children

Pet Med Reminder is rated 4+ in the App Store and is not directed at children under 13. We do not knowingly collect any data from children.

### Changes to this policy

If we change this policy, we will update the date above and post the new version at this URL. Material changes will also be noted in the App Store release notes for the next version.

*September 27, 2026:* this policy now lists every kind of usage data the app sends. Earlier versions of this page listed only four of them and said PostHog did not collect IP addresses. That was wrong: PostHog receives the IP address and uses it for an approximate location. Care item names, notification responses, reminder scheduling, and session recordings are included starting with version 1.12.0.

*October 6, 2026:* added the Meta section. Version 1.12.1 is the first version that sends anything to Meta.

### Contact

For questions about this policy or how the app handles your data: **dpaola2@gmail.com**.
