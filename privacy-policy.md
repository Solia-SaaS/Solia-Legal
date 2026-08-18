---
layout: default
title: Privacy Policy
---

# Solia Privacy Policy

_Version 2.0 — last updated 2026-08-17. Effective upon first in-app acceptance._

**Operator:** Solia ([OPERATOR LEGAL NAME]), Ontario, Canada — contact **privacy@getsolia.com**. We plan to incorporate; this policy will be reissued under the incorporated entity with notice to you.

## What Solia is

Solia is a personal life-planning app: you schedule your day, track workouts and meals, and receive AI-generated coaching reports, scores, and rankings. This policy describes what data we collect, how it is used, who processes it, and your rights. Solia is for users **16 and older**; we do not knowingly collect data from anyone under 16, and we delete such accounts when discovered.

## Data we collect

Everything below is collected **from you, in the app** — we do not buy data, pull from data brokers, or track you across other apps or websites.

| Category | Examples | Why |
|---|---|---|
| Account | Email (via Google or Apple sign-in), username, birthdate | Sign-in, unique identity, age verification |
| Profile | Goals, constraints, notes to your coach, lifestyle (sleep pattern), body weight, height, biology, fitness preferences | Personalizes coaching |
| Schedule | Planned and actual time blocks, templates, recurring patterns, sleep times, day anchors | Core product function |
| Fitness | Workouts, exercises, sets/reps/loads, weigh-ins, workout photos | Core product function |
| Nutrition | Logged meals, meal photos, food searches | Calorie/macro tracking |
| Voice | Microphone audio when you speak to the agent | Transcribed to text to execute your command; **audio is not stored on our servers** (see AI processing) |
| Location | Places you explicitly save (when-in-use permission only) | Attach locations to blocks; commute estimates. We never collect background location |
| Social | Follows, follow requests, profile header (avatar, bio), stories you post | Social features you choose to use |
| Device | Push token, platform, timezone (including any in-app timezone override), app version | Deliver notifications at the right local time |
| Reports & scores | AI coaching reports, LifeScores, ranks, match results | Core product function |
| Support | Bug reports you submit | Fixing problems |

We do **not** collect contacts, browsing history, advertising identifiers, or analytics/crash telemetry (if we add crash reporting later, this policy will be updated first).

## How data is processed

- **Supabase** hosts our database, authentication, file storage, and server functions. Data is stored on Supabase infrastructure located in the United States. If this is outside Canada, your data is subject to the laws of that jurisdiction while stored there.
- **OpenAI (United States)** processes, via API: your voice audio (speech-to-text — the audio is sent for transcription and is not retained on our servers), your typed and transcribed agent commands, meal photos (macro estimation), and your day's data — schedule, fitness, nutrition, goals, notes — to generate coaching reports, scores, and suggestions. Per OpenAI's API terms, API data is not used to train their models.
- **Google and Apple** provide sign-in (Google OAuth and Sign in with Apple). We receive your email and a basic profile identifier; we never receive your password. If you use Apple's **Hide My Email**, we receive a private relay address instead of your real one.
- **Expo, Apple, and Google push services** route notifications to your device.
- **Apple Maps** powers commute estimates and directions links for places you save (when that feature is active).
- **Payments (future):** when subscriptions launch, payment will be processed by Apple In-App Purchase and/or Stripe. We will never store full card numbers; this policy will be updated before payments go live.

**AI-generated content:** reports, scores, suggestions, and estimates are automated outputs, **not professional, medical, or nutritional advice**.

We do **not** sell or rent your data. We do not show ads. Data goes to the processors above only to provide the product.

## Social visibility and leaderboards

- Your **profile header** (username, avatar, bio, follower counts) is visible to other users; your account can be public (anyone may follow) or private (you approve followers).
- **Stories** you post are visible only to your followers and leave the feed after 24 hours (we then remove them from circulation).
- **Leaderboards are automatic**: every account is scored and ranked from its own activity data. Other users can see your **username, rank, tier, scores, and match results** (including in their match slips against you). Underlying details of your day are not shown — only scores and AI-written summary drivers. If you deactivate your account, scoring pauses and you leave the visible ladder.

## Retention, deactivation, and deletion

- **Retention:** your data is kept while your account is active, to power your history, reports, and progress views.
- **Deactivation (temporary):** Profile → Deactivate account hides your profile, stories, and leaderboard presence and pauses coaching, scoring, and notifications. Signing back in reactivates.
- **Deletion (permanent):** Profile → **Delete account** permanently deletes your data across our database — profile, schedule, fitness, nutrition, photos, social graph, reports, scores — and your authentication record. Match-history rows that belong to *other* users (a past opponent's record that they played someone) are retained on their side without your profile. You can also request deletion by emailing **privacy@getsolia.com** from your account email.
- **Backups:** deleted data may persist in encrypted database backups for a limited period (up to ~30 days) before those backups expire.

## Security

Data is encrypted in transit (HTTPS). Database access is enforced per-user with row-level security. On your device, session tokens are stored encrypted using the operating system keychain. No system is perfectly secure; if we learn of a breach affecting your data we will notify you as required by law.

## Legal bases (where the law requires one)

Where laws such as the EU/UK GDPR apply, we process your data on these bases: **contract** (everything needed to run the product you signed up for — schedule, coaching, scores, notifications); **consent** (optional permissions: microphone, camera/photos, location, push; health-related data — weight, fitness, nutrition — which you provide by choosing to use those features; you can withdraw any of these at any time by disabling the permission or feature, or deleting your account); and **legitimate interests** (service security, abuse prevention, bug fixing). We make no decisions about you with legal or similarly significant effects — scores and coaching are informational only.

## International transfers

We operate from Canada and our processors (Supabase, OpenAI, Google, Apple, Expo) store or process data in the United States / the United States. Where transfer rules apply (EEA/UK/Switzerland and similar), transfers rely on the processors' standard contractual clauses and/or applicable adequacy frameworks (e.g., the EU–US Data Privacy Framework for certified processors). By using Solia you understand your data is processed in these locations.

## Your rights

Depending on where you live (Canada under PIPEDA and provincial laws; the EEA/UK under GDPR; US states with privacy laws; Brazil under LGPD; and similar regimes), you may have the right to:

- **Access** the personal information we hold about you, and receive a **portable copy** on request;
- **Correct** inaccurate information (most profile data is editable in-app);
- **Delete** your data (in-app: Profile → Delete account — this is the fastest path — or by email);
- **Withdraw consent** at any time (disable a permission, stop using a feature, deactivate, or delete);
- **Object to or restrict** certain processing;
- **Not be discriminated against** for exercising any of these rights.

Exercise any of these at **privacy@getsolia.com** from your account email; we respond within the time your local law requires (30 days in most places). You may also complain to your data-protection authority — in Canada, the Office of the Privacy Commissioner (priv.gc.ca); in the EEA/UK, your national supervisory authority; elsewhere, your local regulator. We do not sell or share personal information for advertising in any jurisdiction's sense of those words.

## Permissions

The app asks for microphone (speak to your agent), camera and photo library (meal, workout, story, and profile photos; label scanning), location while-in-use (save places), and notifications (block check-ins and coaching). Every permission is optional; denying one disables only its feature.

## Changes

We will update this policy as the product evolves (including before payments or any analytics tooling launch), note the version and date at the top, and notify you in-app of material changes, with re-acceptance where required.
