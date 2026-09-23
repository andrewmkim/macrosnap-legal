# Privacy Policy

_Last updated: 2026-09-22_

MacroSnap ("we", "us", or "the app") is a calorie and meal-planning iOS application operated by Andrew Kim. This policy explains what data we collect, why, where it lives, who processes it, how long we keep it, and your rights over it.

## Summary in plain English

- Your meals, weights, fridge inventory, and plans are yours. They live on your device and in your private MacroSnap account.
- We use your email and password (or Sign in with Apple) to sign you in.
- AI features (meal parsing, photo logging, plan generation, recipe steps) send the text or photo you submit to our server, which forwards it to Anthropic's API.
- If you join the optional social feed, what you choose to post (a meal, its photo, calories and macros, a caption, and how far into your goal you are) is visible to the people allowed to see your profile.
- We never sell your data and never use it for advertising.
- We count which features get used so we know what to improve. Those counts never include what you ate, your photos, or any body weight, and you can turn them off in Settings.
- You can export all your data, and delete your account and all your data, at any time from Settings.

## Who we are

MacroSnap is operated by Andrew Kim, the data controller for the data described here, publishing as an individual developer. If MacroSnap moves to a company, this section will name it. Contact: amkim2003@gmail.com.

## What we collect

### Account data
- Email address (for sign-in and account recovery).
- Sign in with Apple identifier (when used). If you use Apple's "Hide My Email", we only ever see the relay address.
- Account creation date and last-active date.

### Application data (synced to your account)
- Profile: name, sex, age, height, weight history, activity level, goal and target date, dietary targets.
- Meals you log: ingredients, amounts, macros, timestamps, notes, and photos you attach.
- Goal history and its progress photos. **Progress photos stay on your device** and are never uploaded.
- Inventory: foods you have on hand, quantities, expiration dates.
- Plans: generated meal plans, approvals, swaps, shopping lists.
- Preferences: cuisines, ingredient likes and dislikes, planning settings.

### Social feed (optional)
Only if you turn on the social feature:
- A public or private profile: username, display name, bio, avatar.
- Posts you choose to share: meal name, photo, calories and macros, caption, and your goal progress ("day 12 of 35, on pace"). **Never your body weight.**
- Comments, likes, follows and follow requests, challenges you join, and your standing in them (days logged, not weight).
- Reports you file and accounts you block.

Private profiles are visible only to followers you approve. Public profiles are visible to any signed-in MacroSnap user.

### Health data (optional)
If you turn on Apple Health:
- We read **active energy burned** to show your burned calories for the day.
- We may write the weigh-ins you enter to Apple Health.
- Data read from Apple Health is never sent to our server or to any third party, and is never used for advertising or analytics.

### AI processing
When you use text, voice or photo logging, receipt scanning, plan generation or recipe steps:
- The text, image or context you submit is sent to our backend and forwarded to Anthropic's Claude API.
- The response comes back to your device. We do not store the AI inputs or outputs on our servers beyond the meal or plan you choose to save.

### Food lookups
Food searches are sent from our backend to the U.S. Department of Agriculture's FoodData Central API. Only the search text is sent, never your identity.

### Product analytics
To decide what to build and fix, we record which features get used:
- **What we send**: counts and categories only. For example, which screens opened, how long a meal took to log, how many items it had, whether an AI-parsed meal needed correcting and by roughly what percentage, whether you set a loss, maintain or gain goal, and error counts.
- **What we never send**: meal names, ingredients, photos, notes, voice transcripts, captions, search queries, username, email, **any body weight or weight change**, or anything read from Apple Health. Calories are recorded only as a coarse band (for example "400-699").
- **Who processes it**: PostHog, as our processor. Events are tied to a random account identifier, not to your name or email.
- **Opting out**: Settings > Data > Share usage analytics. Turning it off stops collection immediately.

### Crash and performance reports
When the app crashes or hangs, iOS gives the app a diagnostic report (MetricKit): technical call stacks, device model, OS and app version. We upload these to our own backend to fix bugs. They contain no meal, health or account content beyond your account identifier.

## Where data lives and who processes it

| Processor | What | Why |
|---|---|---|
| Your device | All app data, first | Works offline |
| Supabase (USA) | Account, synced app data, social content, crash reports | Our backend and database |
| Anthropic (USA) | Text and photos you submit to AI features | AI processing |
| PostHog (USA) | Usage counts described above | Product analytics |
| USDA FoodData Central (USA) | Food search text | Nutrition lookups |
| Apple | Sign in with Apple; App Store; Apple Health (on device) | Platform services |

## Retention
- App and social data: until you delete it or delete your account.
- Crash reports: 180 days.
- Analytics events: up to 7 years under PostHog's default retention. They are keyed only to a random identifier and are deleted on request.
- Backups: deleted data can remain in encrypted database backups for up to 30 days before it is overwritten.

## What we do not do
- We do not sell your data.
- We do not use your data for advertising or share it for marketing.
- We do not track you across other companies' apps or websites.

## Your rights
Wherever you live, you can:
- **Access and portability**: Settings > Data > Export gives you a JSON file of all your data.
- **Correction**: edit any field on your profile, meals, weights or inventory.
- **Deletion**: Settings > Delete account permanently removes your account, your data and your uploaded photos from our backend and your device.
- **Objection to analytics**: turn it off in Settings.
- **Complaints**: contact us first. EU/UK residents may also complain to their data protection authority. California residents have the rights described above under the CCPA; we do not sell or share personal information as those terms are defined there.

Our lawful bases (EU/UK): performing our contract with you (running the app), your consent (Apple Health, the social feed, AI photo logging), and our legitimate interest in keeping the app working (crash reports, product analytics you can opt out of).

## Children
MacroSnap is not for children under 13, and the app does not let anyone under 13 sign up. Users under 18 cannot set weight-loss goals.

## Changes to this policy
If we change this policy materially, we will post the updated version here and note the change in the app.

## Contact
amkim2003@gmail.com
