# Herald Network — Privacy Policy

Last updated: October 23, 2026

## 1. Who we are

Herald Network ("Herald Network," "we," "us") operates the Herald Network mobile application and associated services (the "Service"), a platform for discovering, organizing, and participating in living-history and historical-reenactment events.

Data controller: Takács László egyéni vállalkozó (László Takács, sole trader), 7013 Cece, Bethlen Gábor u. 116., Hungary
Contact for privacy questions: whiterabbitgames85@gmail.com
Data Protection Officer (if applicable): Not applicable (we are not required to appoint one)

## 2. What data we collect

We collect only what the Service actually needs to work. Specifically, today:

**Account data**
- Email address and password (password is handled entirely by our authentication provider, Supabase Auth, using industry-standard hashing — Herald Network never sees or stores your plaintext password).
- If you choose "Continue with Google": your Google account email address and name, which Google passes to us through Supabase Auth. We do not receive your Google password and we do not access any other Google data.

**Profile data (visible to you; some fields visible to other users depending on your settings)**
- Display name
- Region (a free-text field you enter yourself, e.g. "Budapest, HU" — this field is only a label on your profile)
- Bio / short description
- Profile photo
- Privacy preferences (currently: whether you appear on the public Rankings leaderboard)

**Preferences**
- Historical eras, event types, and participation roles you're interested in
- Maximum distance and region preferences, used to personalize which events are shown to you

**Activity data**
- Events you follow or apply to, including your chosen participation role and any free-text notes you add (e.g. kit/camp logistics notes) — visible to you and to that event's organizer(s)
- Company/group memberships (if you join or create a company/team profile)
- Tournament participation, match results, and the resulting rating/ranking — **match results and ratings are public** once recorded, as part of the Service's verified-results system
- Reports you submit about an event, company, marketplace listing or gallery photo (visible to you and to Herald Network administrators only)
- The list of users you have blocked (visible only to you; it is used to hide their listings and photos from you)

**Company/group data**
- If you create or manage a company (team) profile: its name, region, bio, and photo, plus its member list and roles

**Content you upload**
- Photos for your profile, a company, or an event you organize
- Photos you add to an event's public gallery (anyone signed in can view them)
- Marketplace listings you post: title, description, category, price, region, an optional photo, and **the contact details you choose to put in the listing (for example an email address or phone number) — these are visible to every signed-in user**, so only enter contact details you are happy to share. Listings can be posted under your name or on behalf of a company you manage.

**Device data (only if you enable push notifications on a physical device)**
- A push notification token issued by Apple/Google via Expo's push service, and your device platform (iOS/Android). We use this solely to deliver notifications about events and applications you've opted into; we do not use it for advertising.

**Approximate location (only if you tap "Use my location")**
- If you allow it, the app reads your phone's approximate location once, rounds it to about 1 km, and keeps it **only on your phone** to work out how far events are from you. It is never sent to our servers or shared with anyone, and we never track your movements. You can revoke the permission in your phone's settings at any time; the app then simply stops showing distances.

**What we do *not* collect**
- We do not use any third-party analytics or crash-reporting SDKs. (We do use Google AdMob for advertising — see "Advertising" below.)
- We do not collect or store your location on our servers (see "Approximate location" above).
- We do not sell your personal data to anyone.

## 3. How we use your data

- To provide the core Service: showing you relevant events, letting you apply to events, managing company/team pages, running tournaments, calculating ratings, and running the community marketplace.
- To send you notifications about events and applications you've engaged with (in-app, and via push notification if you've enabled it on a device).
- To keep the Service safe: reviewing reports submitted about events, profiles, companies, listings or photos, and removing content or suspending accounts that break our Terms.
- To communicate with you about your account (e.g. password reset emails).

**Advertising.** The Service shows ads served by Google AdMob: banners in the Events and Marketplace lists, and an occasional full-screen ad right after you publish an event (at most once every few minutes). We do not use your account data (profile, applications, preferences) for ad targeting and we do not share it with advertisers. AdMob itself, as an independent controller, may collect device identifiers (such as the advertising ID), IP address, and ad-interaction data to serve and measure ads, and — only if you consent — to personalise them. See Google's own policy: https://policies.google.com/technologies/ads. If you are in the EEA/UK (or a US state that requires it) you are asked for your choice when you first open the app, and you can change or withdraw it any time from Profile → Ad choices. On iOS, personalised ads additionally require your permission via Apple's tracking prompt; saying no still lets you use the whole app, you just see non-personalised ads.

## 4. Who we share data with

- **Supabase** (our database, authentication, and file-storage provider) processes all the data described above on our behalf, under its own data processing terms. Our project is hosted in Europe (Amazon Web Services data centre).
- **Expo** (`exp.host`) relays push notifications to Apple/Google on our behalf, if you've enabled them. Expo receives only your push token and the notification content, not your other account data.
- **Other users of the Service** see whatever your privacy settings and the nature of the feature make visible — for example, an event organizer sees applications made to their event; anyone (including people without an account, since the live tournament page is public) can see verified match results, ratings, and tournament participant names.
- **Google (AdMob)** receives the device/ad-interaction data described under "Advertising" when ads are shown.
- Apart from the above, we do not share your data with any other third party, and we do not sell it.
- We may disclose data if required by law, or to protect the rights, safety, or property of Herald Network, our users, or the public.

## 5. Your rights

Depending on where you live, you may have the right to:
- Access the personal data we hold about you
- Correct inaccurate data
- Request deletion of your data
- Object to or restrict certain processing
- Request a copy of your data in a portable format

You can delete your account yourself in the app (Profile → Edit Profile → Danger zone). For access, correction, portability or objection requests, contact whiterabbitgames85@gmail.com.

## 6. Data retention

We retain your account and activity data for as long as your account is active. When you delete your account in the app, your profile, applications, reports, block list and any marketplace listings posted under your own name are deleted immediately; gallery photos you uploaded and events or companies you created remain, no longer linked to your account. Backups held by our hosting provider are kept only for a limited time under its own retention schedule. Verified match results and ratings, once recorded, are part of the platform's public historical record and may be retained even if the individual participant's account is later deleted, shown thereafter under the name recorded at the time (this mirrors how the current tournament_participants data model works — a display name is captured at entry time, independent of the live profile).

## 7. Children's privacy

The Service is not directed at children under 16, and we do not knowingly collect data from them. If you believe a child under 16 has created an account, contact us and we will delete it.

## 8. International users

Herald Network is designed to be used internationally. If you access the Service from outside the country where our servers are located, your data will be transferred to and processed in that country. Where data is transferred outside the European Economic Area (for example to Google or Expo, which operate globally), this relies on the providers' standard contractual clauses or an adequacy decision.

## 9. Changes to this policy

We may update this policy as the Service changes. The current version is always available in the app and on our website, with its date at the top. If we make a material change, we will tell you in the app before it takes effect.

## 10. Contact us

Questions about this policy or your data: whiterabbitgames85@gmail.com

