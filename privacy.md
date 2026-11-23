---
layout: policy
title: Privacy policy
permalink: /privacy/
---

## Privacy Policy

**Last updated:** 2026-11-21

This page lists what Pet Med Reminder collects and why. The app sends detailed usage data so that we can see what works, find problems and improve it.

This policy covers the app for iPhone and iPad. The Android app has its own policy: [Pet Med Reminder for Android privacy policy](/android-privacy/).

### Data we collect about you

**No account and no contact details.** Pet Med Reminder does not require an account, does not ask for your email or your name, does not access your contacts, does not ask for your location, and does not use an advertising identifier. The app sends usage analytics that include what you enter in it, it tells Meta when the app is installed and opened, and it asks Apple whether an Apple ad brought the install. All three are described below.

### Data the app stores

The app stores the data you create: your pets, the items you schedule, the doses you log, and any photos you attach. This data is stored:

1. **Locally on your iPhone**, in the app's private storage.
2. **In your personal iCloud account**, through Apple's CloudKit framework, if iCloud is on. We have no access to your iCloud data.

We do not run a server for your records. A copy of much of what you enter reaches us through the usage analytics and the session recordings described below.

### Usage analytics

The app sends events to [PostHog](https://posthog.com). They include:

- The screens you open and what you do there: adding, changing, stopping or deleting a pet or a care item; logging, skipping or backfilling a dose; marking a round of doses; catching up on missed days; sharing a report or a care sheet
- Starting with version 2.0.3, when you tap Share Pet Med Reminder in Settings, and the app you chose in the share sheet
- What you enter: each pet's name and species, each care item's name, dose amount, the vet's instructions and the food rule, its schedule and how long it runs, and the scheduled and actual time of each dose
- When a course ends or is stopped, and how many doses were given, skipped or missed
- Counts of pets, care items and caregivers, and a random ID for each pet and each care item
- Whether notifications are on, where the app asked, and what you do with each reminder (mark it given, skip it, snooze it, open the app from it or dismiss it)
- When the app is installed, updated, opened and closed, and links that open it
- Crashes and errors in the app, with technical details of what went wrong
- Your device model, iOS version, app version, language, region setting and time zone
- A timestamp, and a random ID the app creates when it is installed. PostHog keeps a profile for that ID with your number of pets and care items, their species, your notification setting and your app version

PostHog also receives the IP address of each request and uses it to estimate an approximate location (city, region and country).

The analytics do not contain your name, your email, your Apple ID or an advertising identifier. We use this data to improve the app. We do not sell it or use it for advertising.

### Session recordings

The app records how it is used through PostHog. A recording is a series of screenshots of the app's own screens while you use it, with your taps, the app's log messages and its network requests. Starting with version 2.0.2, nothing on the screen is blocked out: recordings show the text and the photos on the app's screens, including your pets' names and photos, your care items and your doses. Recordings never include anything outside the app, are grouped by the random install ID, and are deleted after 30 days.

### This website

This website uses PostHog, the same analytics service as the app, to count visits. On each page view it records the page address, the referring page, your browser, device type and screen size, and an approximate location (country and city) that PostHog works out from your IP address. When you tap a link to the App Store, it records that tap, the page it was on, which link on the page you tapped and the campaign code in the link.

It does not set cookies. It keeps a random session ID in your browser tab's session storage, so that one visit counts once, and the ID is deleted when you close the tab. It does not create a profile for you, does not set an advertising identifier and does not record your session. This page, the privacy policy, records nothing.

One page works differently. `/vet` is the link printed on cards handed out by veterinary clinics. It records one event so we can tell how many people that channel reaches: the page address (which can name the clinic that handed out the card), whether the visitor is on an iPhone, the referring page, your browser, and an approximate location that PostHog works out from your IP address. It sets no cookie, stores no ID in your browser and creates no profile.

Two pages also work differently. `/go/a` and `/go/b` are the links in our Instagram ads, and they send you straight on to the App Store. Before they do, they record one event: the page, the ad's campaign code and tags, the referring page, your browser, and an approximate location that PostHog works out from your IP address. They set no cookie, store no ID in your browser and create no profile.

### Meta (Instagram and Facebook ads)

Starting with version 1.12.1, the app includes Meta's software development kit (SDK), so we can count how many installs our Instagram and Facebook ads bring. The app sends Meta:

- One event the first time the app opens after it is installed, and one event each time the app opens
- With each event: your device model, iOS version, app version, language, time zone, mobile carrier, screen size, and a random ID that Meta's SDK creates on your iPhone
- The IP address of each request, which Meta receives as part of the connection
- If Meta's SDK itself crashes or hits an error, a report about Meta's own code

Apple also sends Meta an install report through SKAdNetwork, Apple's ad measurement system. That report contains no identifier for you or your device.

Meta does not receive your pets, your care items, your doses, your photos, or anything else you enter in the app. It does not receive your name, your email, your Apple ID, or your device's advertising identifier: the app never reads it. The app never asks for permission to track you. Without that permission, iOS blocks the parts of Meta's SDK that track, and Meta says it uses such events only through privacy-preserving methods (its "Aggregated Event Measurement") to measure ads. Meta handles this data under [its own privacy policy](https://www.facebook.com/privacy/policy/).

### Apple Ads

Starting with version 1.13.0, the first time the app opens after it is installed, it asks Apple whether the install came from an ad on the App Store (Apple Ads, formerly Apple Search Ads). It uses Apple's AdServices framework: the app gets a token from iOS and sends it to Apple, and Apple answers yes or no. If the answer is yes, Apple adds ID numbers for the ad's campaign, ad group, keyword and ad, the country or region, and how the ad was shown. The app sends that answer to PostHog with the usage analytics described above, so we can see which search words bring people who use the app.

The token contains no identifier for you, and the app does not read your device's advertising identifier. Nothing you enter in the app goes to Apple for this. Apple handles its side under [its own privacy policy](https://www.apple.com/legal/privacy/).

### Crash reports

If the app crashes, Apple may send us a crash report through App Store Connect, with technical details of what went wrong (stack trace, device model, iOS version). Starting with version 2.0.2, the app also sends crash and error reports to PostHog, as described under usage analytics.

### Children

Pet Med Reminder is rated 4+ in the App Store and is not directed at children under 13. We do not knowingly collect any data from children.

### Changes to this policy

If we change this policy, we will update the date above and post the new version at this URL. Material changes will also be noted in the App Store release notes for the next version.

*September 27, 2026:* this policy now lists every kind of usage data the app sends. Earlier versions of this page listed only four of them and said PostHog did not collect IP addresses. That was wrong: PostHog receives the IP address and uses it for an approximate location. Care item names, notification responses, reminder scheduling, and session recordings are included starting with version 1.12.0.

*October 6, 2026:* added the Meta section. Version 1.12.1 is the first version that sends anything to Meta.

*November 1, 2026:* added the Apple Ads section and the new usage events in version 1.13.0: a random ID for each pet and care item, changes and deletes, the end of a set-length care item, and where the app asked for notifications.

*November 21, 2026:* version 2.0.2 sends more usage data: pet names, care item names, dose amounts, the vet's instructions, food rules and dose times on its events; a profile for each install; crash and error reports. Session recordings no longer block out photos. This page now describes that.

*November 11, 2026:* corrected the `/vet` section. It said the page discards the IP address. That was wrong: PostHog receives the IP address from that page too, and uses it for an approximate location, as on the other pages of this site.

### Contact

For questions about this policy or how the app handles your data: **dpaola2@gmail.com**.
