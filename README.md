# Review Reply Generator

A standalone, zero-dependency HTML tool that helps small hospitality operators
turn guest reviews into ready-to-send replies — fast.

Paste a review → press **Enter** → the tool reads the actual points raised
(room, wifi, breakfast, staff, cleanliness, location, price, power, etc.),
detects the sentiment, and writes a reply that addresses each one in a warm,
on-brand voice. Edit, copy, and post to Booking.com or Google Business Profile.

## Why

Small venues get reviewed on Booking.com, Google, and OTAs but have no clean
place to draft a reply. Copy-pasting from a notes app is slow and inconsistent.
This gives staff one box: paste the review, get a reply, send it.

## Features

- 📥 Paste any review or guest message
- ✨ Detects positive / negative / question + the specific aspects mentioned
- 📝 Generates a reply that answers each point (not a generic "thanks")
- 📋 One-click copy
- ↗ Jump straight to Booking.com / Google to paste
- 🔒 100% client-side — no server, no data leaves the browser

## Usage

Open `reply-tool.html` in any browser. No build step, no install.

## Customising the voice

The reply logic lives in the `ASPECTS` dictionary and the `analyze()` /
`replyFor()` functions near the top of the `<script>` block. Add trigger words
or tweak the phrasing to match your brand.

## License

MIT — use it, fork it, improve it.
