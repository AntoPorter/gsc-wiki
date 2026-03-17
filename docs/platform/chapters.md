# Chapters

The Chapters page lists all active GSC chapters around the world.

## URL

`/chapters/`

## Features

![Chapters Page](screenshots/03-chapters.png)

- **Chapter listing** — Displays all approved chapters in a card grid with the GSC shield logo, "Official Chapter" badge, chapter name, and city/country
- **Chapter detail pages** — Each chapter has a dedicated page at `/chapters/{city-slug}/` showing:

    ![Chapter Detail Page](screenshots/04-chapter-perth.png)

    - Chapter leads with profile photos (via Gravatar) and social links (GitHub, LinkedIn)
    - Upcoming events hosted by the chapter
    - Link to the chapter's Discord channel
- **Apply to lead** — Call-to-action for community members to apply to start a new chapter

## How New Chapters Are Created

Chapters are created through the [Chapter Lead Application](chapter-application.md) process. When an application is approved, a chapter page is automatically generated and added to the chapters listing.

## Setting Up Your Profile Photo (Gravatar)

Chapter lead profile photos are powered by [Gravatar](https://gravatar.com) (Globally Recognized Avatar). Gravatar links an avatar image to your email address, and it's used across many platforms (WordPress, GitHub, Stack Overflow, etc.).

### How it works

1. Your email address is converted to an MD5 hash (the actual email is **never exposed** in the page source)
2. The chapter page requests your avatar from `gravatar.com/avatar/{hash}`
3. If you have a Gravatar account with that email, your photo is displayed
4. If not, a generic silhouette placeholder is shown

### Setting up your photo

1. Go to [gravatar.com](https://gravatar.com) and create a free account
2. **Use the same email address** you used in your chapter application
3. Upload a profile photo
4. Your photo will automatically appear on your chapter page — no code changes needed

### Troubleshooting

- **Photo not appearing?** — Make sure the email on your Gravatar account exactly matches the one you applied with (case doesn't matter)
- **Photo is a silhouette?** — You may not have a Gravatar account yet, or it's registered under a different email
- **Want to change your photo?** — Update it on gravatar.com and it will refresh automatically

## Related Pages

- [Chapter Lead Application](chapter-application.md) — Apply to start a chapter
- [Events](events.md) — Events hosted by chapters
- [Dashboard](dashboard.md) — Chapter lead management tools
