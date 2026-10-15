# Sonique

Community for AI-generated art & music where creators post their work and get tipped directly by fans.

**Live:** https://sonique-art-love.lovable.app

## What it is

Sonique lets AI creators (Suno music, Midjourney art, etc.) post their work to a public feed. Fans discover fresh AI art and music and tip the creators they love.

## MVP Features

- Auth (sign up / login)
- Create post: title, description, media URL, AI tool tag (e.g. Suno)
- Home feed sorted newest first with like + tip buttons
- Post detail with tipping (currently mock $1-$10, moving to real Stripe Connect payouts)
- Profile pages with user posts and lifetime tip stats
- Dark theme, purple-to-teal branding, mobile responsive

## Tech Stack

- React + Tailwind CSS + shadcn/ui
- Supabase (auth + database: profiles, posts, likes, tips)
- Built on Lovable

Lovable project: https://lovable.dev/projects/3d197c90-79ac-4ef5-b5a2-f8bbe1cb7ebd

## Tipping

Tips are currently mock. Proper marketplace model planned with Stripe Connect:
- Creators connect their own Stripe Express accounts
- Tips go directly to creators via destination charges
- Platform can take an optional application fee

Stripe account: Sonique (connected)

## Run locally

This repo currently holds project docs and branding. The app itself runs on Lovable — open the preview URL above in your browser (works on mobile too).

## Branding

Logo: sound wave merging with AI spark, purple (#7C3AED) to teal (#2DD4BF) gradient. See `logo.webp` (to be added).

---
Built by Tony Williams / Loaded
