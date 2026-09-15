# Privacy Policy

**Applies to:** Tangelo (global) and Долька / Dolka (select regional markets) — the same grocery list application, published under different names and localizations for different markets.

**Effective date:** 16.09.2026 **Last updated:** 16.09.2026

This Privacy Policy describes how the developer of Tangelo / Долька (“we,” “our,” or “us”) collects, uses, and protects information when you use our Android application, in any of its branded/localized versions (the “App”).

By using the App, you agree to the collection and use of information in accordance with this Privacy Policy.

## Who We Are

The App is developed and operated by:

Denys Arkharov
Virolahti, Finland

Contact: product.list.supp@gmail.com

If you are a resident of the European Economic Area, the developer named above acts as the data controller for the purposes of the GDPR.

## Important Notice About How This App Works

The App is designed to display your grocery list on the lock screen of your device for convenience. **This means the content of your list may be visible to anyone who can see your device’s screen, even when it is locked**, including other people nearby, in shared living spaces, or with physical access to the device. Please avoid adding sensitive or confidential information to your grocery list. This visibility is a function of the App’s core feature, not a data breach or third-party disclosure, but you should be aware of it before use.

## Information We Collect

### 1. Analytics Data

We use Firebase Analytics, a service provided by Google LLC, to understand how users interact with the App and to improve its functionality and performance. Analytics data may include:

- App usage events (screen views, button interactions, feature usage)
- Device information (device model, OS version, language, general region derived from IP address)
- Advertising identifiers (Google Advertising ID)
- IP address (used for approximate location and technical/anti-fraud purposes, not stored in identifiable form beyond what Firebase retains)

This data does not include your name, email address, or phone number, or the app-assigned emoji icon for an item — but it may include the text of item names, which can contain emoji characters you typed or pasted yourself (see “Item Names (for Emoji Dictionary Improvement)” below for details). It also does not include list names or purchased/not-purchased status.

You can turn analytics collection on or off at any time using the **Analytics toggle** in the App’s **Settings → Privacy** screen — see “How to give or withdraw consent” below for details.

Analytics events, including item names described below, are associated with a Firebase-generated installation identifier tied to your specific copy of the App on your device (not to your name or any account). This identifier lets us distinguish one installation’s events from another's, including over time. This means the data is **pseudonymized rather than fully anonymous**: while we cannot directly identify you from it, someone with access to the underlying analytics data could, in principle, see the pattern of events (including item names) associated with a single installation. We do not attempt to re-identify individuals from this data, and we have no name, email, or other directly identifying information to link it to.

### 2. Crash and Diagnostic Data

If crash reporting is enabled (e.g., via Firebase Crashlytics), we may collect technical diagnostic data such as crash logs, stack traces, device state at the time of a crash, and app version, to help us fix bugs and improve stability. This data is not linked to your identity.

**Crash diagnostics are collected regardless of the Analytics toggle described below** — they are necessary for us to keep the App functioning correctly and are not part of the consent-based analytics/item-names/advertising-ID collection described elsewhere in this policy (see “Legal Basis for Processing” below).

### 3. Advertising Identifier

The App may collect and use the Advertising ID provided by your device for analytics and measurement purposes only, subject to the same consent screen and Analytics toggle described in “Legal Basis for Processing” below — it is not collected unless you have allowed analytics. It is not used to build an advertising profile of you or to serve personalized ads within the App unless separately disclosed. You can also independently reset or limit the use of the Advertising ID at any time in your device settings (Settings → Privacy → Ads, or equivalent), regardless of your in-app choice.

### 4. Local Reminders/Notifications

If you enable reminders or notifications within the App, they are scheduled and triggered entirely on your device by the operating system (e.g., via Android’s local notification/alarm system). **The App does not use a push notification service, does not generate any push token, and does not have a server capable of sending or receiving notifications.** No data related to reminders is transmitted to us.

### 5. Item Names (for Emoji Dictionary Improvement)

The App automatically displays an emoji next to items on your list by matching keywords in the item’s name against an **internal, on-device keyword dictionary** (e.g., an item named “red apples” is automatically matched to an apple emoji). This matching happens entirely on your device — the emoji dictionary is only updated through App updates, not remotely or in real time, and you cannot edit or override the assigned emoji.

To help us identify item names that are **not yet recognized** by this dictionary, so we can decide whether to add support for them in a future App update, the **name/title of items you add to your lists** may be sent to our analytics service (Firebase) and processed together with the same item names submitted by other users.

- This allows us to see which item names are commonly added but not yet matched to an emoji (for example, if a number of users independently add the same unrecognized item name, we may consider adding a matching keyword and emoji to the dictionary in a future update).
- **Adding new keywords to the dictionary is a manual decision made by us** — it is not an automated or algorithmic process, and it does not involve automated decision-making that produces legal or similarly significant effects on you.
- Item names are processed on an **aggregated basis** — we look at patterns across many users’ submissions (e.g., how frequently a given item name appears) rather than reviewing any single user’s complete list as a whole.
- **Item names are not linked to your name, email address, account, or any other information that directly identifies you** — the App has no accounts or sign-in. However, as described in “Analytics Data” above, item names are technically associated with a per-installation identifier generated by Firebase, so they are **pseudonymized, not fully anonymous**: it is technically possible to see which item names came from the same App installation over time, even though we cannot tell who that installation belongs to.
- Other fields — list names, purchased/not-purchased status, and the **separate emoji icon automatically assigned by the App** to each item — are **not** sent for this purpose and remain local to your device, as described in “Local Data Storage” below. This exclusion applies only to that app-assigned emoji field: if you type or paste an emoji as part of an item’s name itself (e.g., naming an item “🍎 apples”), that emoji is part of the item name text and is sent along with the rest of the name, as described above — it is not filtered out.
- **Do not add sensitive, confidential, or prohibited categories of information to your lists** (see our Terms of Use, “Prohibited Content”), since item name text may be processed as described in this section and is not fully anonymous, unless you have turned off the Analytics toggle described below.
- You can stop this processing at any time by turning off the **Analytics toggle** in the App’s **Settings → Privacy** screen — see “How to give or withdraw consent” below.

### 6. Local Data Storage

With the exception of item names processed as described above, your grocery lists and app preferences (list names, the emoji icon automatically assigned to each item by the App, and purchased/not-purchased status) are stored, computed, and matched entirely locally on your device and are **not** transmitted to our servers. This content remains on your device until you delete the App or clear its data.

## Legal Basis for Processing (EEA/UK Users)

Where the GDPR applies, we process your data on the following legal bases:

- **Consent** — for analytics, advertising identifier collection, and item name processing for emoji-keyword dictionary improvement. On first launch, the App shows a **consent screen** asking whether you want to allow analytics. This screen is shown to **all users, regardless of location** — not only those in the EEA/UK. **No analytics events, item names, or the Advertising ID are collected or sent until you explicitly tap "Allow"** on this screen; if you decline, the App works normally, but nothing described in this bullet point is collected. You can change this choice at any time afterward using the Analytics toggle described below. (This does not affect crash diagnostics — see “Crash and Diagnostic Data” above and “Legitimate interests” below.)
- **Legitimate interests** — for crash diagnostics and basic technical logs necessary to keep the App functioning and secure. Crash diagnostics are collected regardless of your analytics consent choice, as they are limited to technical data needed to fix bugs and are not linked to your identity.

**How to give or withdraw consent:** On first launch, the App asks whether you want to allow analytics before any consent-based collection begins, as described above. You can change this decision at any time afterward using the **Analytics toggle** in the App’s **Settings → Privacy** screen, accessible by tapping the **gear (⚙) icon** in the top-right corner of the toolbar on the App’s main/home screen. Turning the toggle off tells the App to stop sending analytics events, item names, and the Advertising ID to Firebase. This takes effect immediately, without needing to uninstall the App, and you can turn analytics back on at any time in the same screen. Withdrawing consent this way does not affect the lawfulness of processing carried out before you turned the toggle off, and it does not affect crash diagnostics, which continue regardless (see above).

If you prefer, you can also withdraw consent by uninstalling the App entirely, which stops all data collection described in this policy (since there is no account or identifier tied to you that would allow us to continue collecting data afterward) and also removes your locally stored list data.

For the Advertising ID specifically, you can independently limit or delete it at any time directly in your device settings (Settings → Privacy → Ads), regardless of the in-app Analytics toggle.

Emoji matching itself always runs locally on your device regardless of your analytics choices — turning the Analytics toggle off (or uninstalling) only stops us from seeing your item names to help decide on future dictionary additions; it does not change how the App matches emojis or otherwise behaves while installed, and it does not stop crash diagnostics, which are collected on a separate, legitimate-interest basis (see “Crash and Diagnostic Data” above).

We do not use your data for automated decision-making or profiling that produces legal or similarly significant effects on you.

## International Data Transfers

Firebase and Google infrastructure may process and store data outside your country of residence, including in the United States. Where this involves a transfer of personal data from the EEA/UK, such transfers rely on Google’s Standard Contractual Clauses and other safeguards as described in Google’s own privacy and data processing terms (linked below). By using the App, you acknowledge this transfer where applicable.

## How We Use Information

We use the collected information to:

- Understand and analyze how the App is used
- Improve app performance, features, and user experience
- Diagnose and fix bugs and crashes
- Trigger local reminders you have enabled (handled entirely by your device’s operating system)
- Maintain the security and integrity of the App

## Data Sharing and Third-Party Services

We do not sell your personal data. We also do not “share” your personal data for cross-context behavioral advertising as defined under the CCPA/CPRA, beyond the limited transmission of the Advertising ID to Google/Firebase for analytics purposes described above.

Third-party services used by the App, and their own privacy policies:

- Firebase (Google LLC): https://firebase.google.com/support/privacy
- Google Play Services: https://policies.google.com/privacy

These providers process data according to their own privacy policies and applicable law. We do not control and are not responsible for their independent data practices beyond the services we’ve configured.

## Data Retention

- **Analytics and crash data:** retained by Firebase according to Google’s default retention settings (currently up to 14 months for Google Analytics for Firebase event data, unless changed by Google), or until no longer necessary for the purposes described in this policy.
- **Item names (for emoji-keyword dictionary improvement):** retained by our analytics provider on the same basis as other analytics data, or until reviewed for potential dictionary additions in a de-identified, non-attributable form, after which the underlying individual submissions are no longer needed.
- **Advertising ID:** retained only as long as needed for analytics purposes, or until you reset/limit it in device settings.
- **Other locally stored list data** (list names, the app-assigned emoji icon for each item, purchased/not-purchased status): stays on your device indefinitely until you delete it or uninstall the App; we never receive a copy. (Note: the text of item names themselves — which may include emoji you typed — is handled separately; see “Item Names” retention above.)

## Your Rights

### Users in the European Union / EEA / UK (GDPR)

You have the right to:

- Access the data we hold about you
- Request correction or deletion of your data
- Object to or restrict processing
- Request data portability, where applicable
- Withdraw consent at any time
- Lodge a complaint with your local data protection authority

We will respond to verified requests within **30 days**, or as required by applicable law.

### Users in the United States (CCPA/CPRA)

You have the right to:

- Know what personal information is collected
- Request deletion of your personal information
- Opt out of the “sale” or “sharing” of personal information (see Data Sharing above)
- Not be discriminated against for exercising these rights

To exercise any of these rights, contact us at the email below.

### Users Outside the EEA/UK/US Covered by Other Local Data Protection Regimes

If you are located in a country outside the EEA, UK, or US, additional local personal data laws may apply to you, including data localization and registration rules for local data operators.

- We do not knowingly collect or process personal data that would trigger local data-operator registration or localization requirements, as the App does not require account registration and does not transmit personally identifying information to our servers.
- If you believe the App’s processing of your data falls under a specific local personal data regime and you wish to exercise rights recognized under that regime (access, correction, deletion, withdrawal of consent, or restriction of processing), please contact us at the email below and we will respond consistent with applicable local law.
- Where required by local law, a localized (e.g., Russian-language) version of this policy will be made available for the “Долька” branded version of the App.

## Children’s Privacy

The App is not intended for use by children under 13 years of age (or under 16 in the EEA/UK, where a higher age of consent applies). We do not knowingly collect personal data from children below the applicable age. If you believe a child has provided us with personal information, please contact us so we can delete it.

## Data Security

We take reasonable technical and organizational measures to protect the limited information collected through the App. However, no method of transmission or storage is completely secure, and we cannot guarantee absolute security.

## Changes to This Privacy Policy

We may update this Privacy Policy from time to time to reflect changes in the App, our practices, or legal requirements. Material changes will be indicated by an updated “Last updated” date at the top of this page, and, where required by law, we will provide additional notice (e.g., an in-app notice) before the change takes effect.

## Contact Us

If you have questions about this Privacy Policy, our data practices, or wish to exercise your rights, please contact us:

Email: product.list.supp@gmail.com

---

*This policy applies equally to the App regardless of the store listing name (“Tangelo” or “Долька”) or the language/region in which it is distributed. This Privacy Policy should be read together with our [Terms of Use](https://tangelo-grocery-list.github.io/terms-of-use/).*
