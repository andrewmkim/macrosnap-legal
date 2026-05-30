# Privacy Policy

_Last updated: 2026-05-30_

MacroSnap ("we", "us", or "the app") is a calorie and meal-planning iOS application. This privacy policy explains what data we collect, why, where it lives, and your rights over it.

## Summary in plain English

- Your meals, weights, fridge inventory, and plans are yours. They live on your device and in your private MacroSnap account.
- We use your email and password (or Sign in with Apple) to authenticate you.
- AI features (meal parsing, plan generation, recipe steps) send the relevant text or photo to our server, which forwards it to Anthropic's API. Your raw API key is never on the device.
- We never sell your data and never use it for advertising.
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

## Where data lives

- **Your device**: all app data is stored locally first (SwiftData) and synced opportunistically.
- **Our backend**: hosted on Supabase. Your row-level data is only accessible by your authenticated session.
- **Anthropic** (AI provider): receives only the text or photo you actively submit for AI features. Anthropic's data handling is governed by their own terms.

## What we do not do

- We do not sell your data.
- We do not use your data for advertising.
- We do not share your data with third parties for marketing.
- We do not run third-party analytics SDKs.

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
