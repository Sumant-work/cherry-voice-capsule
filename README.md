# Birthday Voice Capsule — For Cherry

A one-day birthday voice capsule.

Behavior:
- Locked before 28 October 2026, 12:00 AM IST.
- After 28 October 2026, it unlocks whenever opened for the first time.
- The first-open time starts a 24-hour listening window in the visitor browser.
- After 24 hours, the audio is hidden and the expiry message appears.

Preview/testing:
- Add `?preview=locked` to test locked view.
- Add `?preview=open` to test audio/unlocked view.
- Add `?preview=expired` to test expired view.

Note: The 24-hour first-open timer uses browser localStorage. If the visitor clears browser data or uses a different device/browser, the timer can reset. True cross-device expiry requires a backend.

## Search Privacy

This package includes:

- `robots.txt` with `Disallow: /`
- `<meta name="robots" content="noindex, nofollow, noarchive, nosnippet, noimageindex">` inside `index.html`

This helps keep the page out of search engines, but GitHub Pages is still a public URL. Keep the link private.

