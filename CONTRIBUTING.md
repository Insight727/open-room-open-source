# Contributing to Open Room

Open Room is a community building where each room is a real contribution from a real person. Thank you for being part of it.

## How to contribute a room

1. **Reserve your spot** — visit [open-room-open-source.vercel.app](https://open-room-open-source.vercel.app), click **+ Add Room** on the floor plan, and fill out the form. You'll get a room ID (e.g. `warm-harbor`). A GitHub issue is automatically opened with your room ID and username — you can find it with `gh issue list --label room`.
2. **Fork this repo** on GitHub.
3. **Copy the template** *[AI-assisted]* — duplicate `public/registry/_template/` and rename it to `public/registry/your-room-id/`.
4. **Build your room** *[AI-assisted]* — add a background image (JPEG or WebP, max 200KB) and edit `config.json` to define your hotspots. See the [template README](public/registry/_template/README.md) for the full schema. There's a Claude skill that walks you through this from start to finish.
5. **Open a Pull Request** *[AI-assisted]* — a Vercel preview is generated automatically so you can verify your room looks right before it goes live. Once approved and merged, your tile appears on the floor plan.

See `public/registry/_template/README.md` for the full schema reference.

## Edit an existing room

Go to your room on the floor plan, click the **i** button (bottom-right corner), and hit **Open a Task**. Fill in a title and description of what you want to change — a GitHub issue is created automatically. Then fork the repo, make your edits to `public/registry/your-room-id/`, and open a Pull Request.

## Content policy

All rooms must follow these guidelines:

- **No hate speech** — content that attacks or dehumanizes people based on race, ethnicity, religion, gender, sexual orientation, disability, or national origin is not allowed
- **No harassment** — content targeting or threatening specific individuals is not allowed
- **No NSFW content** — explicit sexual or graphic violent content is not allowed
- **No spam or advertising** — rooms should be genuine personal expressions, not promotional material
- **No illegal content** — content that violates applicable law is not allowed

## Moderation

The maintainer reserves the right to reject or remove any room at their discretion, with or without explanation. This includes rooms that violate the content policy above, as well as rooms that are disruptive to the community in other ways.

## Content ownership

You retain ownership of everything you contribute — your background images, artwork, and any other assets in your room folder.

By submitting a Pull Request, you grant the Open Room project a perpetual, non-exclusive, royalty-free license to display your content on the site. If your room is removed, this license ends.

## Building codes

- Every image in the room, including background images: JPEG or WebP, max 200KB
- Total room folder: max 5MB
- One room per builder. Exceptions by request.
