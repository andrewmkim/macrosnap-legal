# Privacy Policy

_Last updated: 2026-07-20_

MacroSnap ("we", "us", or "the app") is a calorie and meal-planning iOS application. This privacy policy explains what data we collect, why, where it lives, and your rights over it.

## Summary in plain English

- Your meals, weights, fridge inventory, and plans are yours. They live on your device and in your private MacroSnap account.
- We use your email and password (or Sign in with Apple) to authenticate you.
- AI features (meal parsing, plan generation, recipe steps) send the relevant text or photo to our server, which forwards it to Anthropic's API. Your raw API key is never on the device.
- We never sell your data and never use it for advertising.
- We count which features get used so we know what to improve. Those counts never include what you ate, your photos, or your weight, and you can turn them off in Settings.
- You can delete your account and all your data at any time from Settings.

## What we collect

### Account data
- Email address (for sign-in and account recovery).
- Apple Sign in identifier (when used).
- Account creation date.

### Application data (synced to your account)
- Profile: name, sex, age, height, weight history, activity level, dietary goals.
- Meals you log: ingredients, photos (if you add them), macros, timestamps.
- Inventory: foods you have on hand, quantities, expiration dates.
- Plans: generated meal plans, approvals, swaps, shopping lists.
- Preferences: cuisines, ingredient likes / dislikes, planning settings.

### Health data (optional)
- If you enable Apple Health integration, we read:
  - Body mass (to refine weight tracking).
  - Active energy burned today (to refine your deficit calculation).
- We may write your morning weight back to Apple Health.
- HealthKit data is never sent to our server. It stays on your device.

### AI processing
When you use voice input, photo logging, plan generation, or other AI features:
- The relevant text, image, or context is sent to our Supabase backend.
- Our backend forwards it to Anthropic's Claude API for processing.
- The response is returned to your device. We do not retain the inputs or outputs beyond what is required to deliver the response.

### Product analytics

To decide what to build and fix, we record which features get used. This is
deliberately narrow, and we would rather have less data than have data we have to
apologise for:

- **What we send**: counts and categories only. Which screens opened, how long a
  meal took to log, how many items a meal had, whether an AI-parsed meal needed
  correcting and by roughly what percentage, whether a plan generated
  successfully, and error and crash counts.
- **What we never send**: your meal names, ingredients, photos, notes, voice
  transcripts, captions, search queries, username, email, or **any body weight**.
  Calories are recorded only as a coarse band (for example "400-699"), never as
  an exact figure.
- **Who processes it**: PostHog, acting as our processor. Events are tied to a
  random account identifier, not to your name or email.
- **Opting out**: Settings > Data > Share usage analytics. Turning it off stops
  collection immediately, and the app keeps working exactly the same.

## Where data lives

- **Your device**: all app data is stored locally first (SwiftData) and synced opportunistically.
- **Our backend**: hosted on Supabase. Your row-level data is only accessible by your authenticated session.
- **Anthropic** (AI provider): receives only the text or photo you actively submit for AI features. Anthropic's data handling is governed by their own terms.
- **PostHog** (analytics provider): receives only the anonymous usage counts described above.

## What we do not do

- We do not sell your data.
- We do not use your data for advertising.
- We do not share your data with third parties for marketing.
- We do not use analytics to profile you or to target you with anything.

## Your rights

- **Access**: see everything in the app itself. Settings > Export your data.
- **Correction**: edit any field on your profile, meals, weights, or inventory.
- **Deletion**: Settings > Delete account. This permanently removes your account and all associated data from our backend and your device.
- **Portability**: Settings > Export gives you a JSON file of your data.

## Children

MacroSnap is not directed to children under 13 and we do not knowingly collect data from them.

## Changes to this policy

If we change this policy materially, we will post the updated version here and note the change in-app.

## Contact

Questions or concerns: amkim2003@gmail.com
