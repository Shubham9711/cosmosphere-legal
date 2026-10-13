---
title: Privacy Policy
permalink: /privacy/
---

# CosmoSphere Privacy Policy

*Last updated: 2026-10-13*

CosmoSphere is a free educational app about the universe, published by **Shubham Agarwal**. It has
**no accounts, no ads, no analytics and no tracking**. This policy explains the little data the app
handles.

**Contact:** Shubham Agarwal, shubham9711781832@gmail.com

## 1. Data that stays on your phone
CosmoSphere saves a few things on your device so the app remembers where you were:
- your progress in each journey (last step and whether you finished it);
- your settings (graphics quality, read-aloud on or off);
- copies of recent AI answers and encyclopedia summaries, so they load faster and work offline.

This data never leaves your phone and is never sent to us. Uninstalling the app, or clearing its
storage in your phone's settings, deletes it.

Read-aloud uses your phone's built-in text-to-speech, which runs on the device.

## 2. "Ask why?"
"Ask why?" has two kinds of answers.

**Checked answers (quick questions).** The three quick questions on every step have pre-written,
fact-checked answers that are built into the app. Tapping one sends nothing anywhere, and it works
offline. If you tap "Read more on Wikipedia", the app downloads that topic's summary from Wikipedia
(see section 3).

**Typed questions (AI answers).** When you type your own question, the app sends:
- the **question text**, and
- the **name and caption of the journey step** (or Explore object) you are looking at,

to our server, a Cloudflare Worker, which uses **Cloudflare Workers AI** to check the question and
write the answer. Cloudflare runs the AI models on its own network; the question is not sent to any
other AI company.
- We do **not** send your name, account, contacts, location, or any device identifier. There are no
  accounts.
- Our server does not store questions or answers, and never logs question text. Cloudflare briefly
  processes your IP address to deliver the request and to apply a rate limit (to stop abuse). We do
  not log it.
- Cloudflare says it does not use Workers AI content to train AI models
  ([Workers AI data usage](https://developers.cloudflare.com/workers-ai/platform/data-usage/),
  [Cloudflare Privacy Policy](https://www.cloudflare.com/privacypolicy/)).
- **Please don't type personal information into questions.**
- AI answers are written by an AI with safety filters and can be wrong. The app says so, and shows
  checked answers with a "Checked answer" label so you can tell them apart.

**Report this answer:** if you report an AI answer, the question, the answer and the step name are
sent to our server and kept in our server logs so we can review them. No IP address or device data
is included in that log entry.

"Ask why?" typed questions are the only journey feature that needs the internet. Everything else,
including the checked answers, works offline.

## 3. Explore mode
- **Encyclopedia summaries** (also "Read more on Wikipedia" in "Ask why?") are downloaded from
  Wikipedia. Wikipedia receives the topic name and your IP address, as with any website
  ([Wikimedia privacy policy](https://foundation.wikimedia.org/wiki/Policy:Privacy_policy)).
- **Live Earth** images are downloaded from NASA GIBS, which receives your IP address as with any website.
- The **map tab** ("Google Maps" on Android, "Apple Maps" on iPhone/iPad) in Live Earth shows a satellite map. On Android the map comes from
  Google Maps (through Google Play services), so Google receives map requests and your IP address
  under the [Google Privacy Policy](https://policies.google.com/privacy). On iPhone and iPad it comes
  from Apple Maps under [Apple's privacy policy](https://www.apple.com/legal/privacy/). The map is
  only loaded when you open that tab.
- **Place search** on the map: when you type a place name and press search, the app sends **only the
  text you typed** to OpenStreetMap's Nominatim service to find matching places. Nominatim (run by the
  OpenStreetMap Foundation) receives that text and your IP address, as with any website
  ([OSMF privacy policy](https://osmfoundation.org/wiki/Privacy_Policy)). Your location is never
  included. Results are kept in memory only until you close the app. The "Famous places" list is built
  into the app and sends nothing.
- **My location** on the map: the app asks for location permission **only when you tap "My
  location"**, and only "while using the app" (never in the background). Your position is used **on
  your phone only** to move the map to you and show a dot. It is not saved, not sent to us, and not
  sent to OpenStreetMap or any other service by CosmoSphere. (The Google or Apple map itself works
  the same whether or not you allow location.) You can say no and the map still works; you can
  change the permission at any time in your phone's settings.
- **Open in Google Maps / Apple Maps** hands the selected place's coordinates to your phone's maps
  app, which then works under its own privacy policy.

## 4. Children and age
CosmoSphere is rated for ages **13 and up**. It is written in simple language and contains no
personal-data collection, accounts, ads or chat with other people. We do not knowingly collect
personal information from anyone, including children.

Typed questions go through several guardrails before and after the AI writes an answer:
- a topic check that only lets space and science questions through;
- Llama Guard, a safety classifier, which checks every question and refuses unsafe ones;
- a fixed tutor instruction that keeps answers short, friendly, accurate and on science;
- a second Llama Guard check on every answer, which replaces anything unsafe with a safe message;
- a rate limit, and a "Report this answer" button on every AI answer.

## 5. Your choices
- You can use every journey, and every checked answer, without typing a question.
- You can delete all locally saved data by clearing the app's storage or uninstalling it.
- Questions about this policy: shubham9711781832@gmail.com.

## 6. Changes
If this policy changes, we will update the date at the top and the copy linked from the app stores.
