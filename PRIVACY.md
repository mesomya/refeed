# Encore — Privacy Policy

_Last updated: June 2026_

Encore is a browser extension that brings the posts you have liked and bookmarked on X
(x.com / twitter.com) back into your Home timeline, and keeps a private archive of them.
This policy explains exactly what data Encore touches and what it does with it.

## The short version

Everything Encore does happens **on your own device**. Encore has no server, no account, and
no analytics. It never sends your data anywhere, never sells or shares it, and never accesses
your X password or login token.

## What data Encore accesses

- **Your liked and bookmarked posts** — their text, images, author, and links. This is the
  content Encore is built to re-surface, and it is stored locally so it can be shown back to
  you in your own feed.
- **The shape of the requests your browser already makes to X** for your Bookmarks and Likes.
  Encore reads these on a read-only basis (via the `webRequest` permission) only to learn how
  to ask X for your own posts, then replays that request using your existing logged-in session.
  It does not record your browsing and does not observe any site other than X.

## What Encore never accesses

- Your X password or login cookie — the `auth_token` session cookie is never read.
- Any website other than x.com / twitter.com.
- Your name, email, location, payment details, browsing history, or any personally identifying
  information.

## Where your data is stored

Your collected posts and settings live in the browser's own local storage on your device
(`chrome.storage.local` and IndexedDB, on the extension's private origin). Nothing is ever
uploaded to Encore or to any third party. The only network requests Encore makes go to X's own
servers — the same ones your browser already talks to — to fetch your own posts.

## Data sharing, sale, and use

Encore does not sell or transfer your data to anyone. It does not use your data for advertising,
creditworthiness, lending, or any purpose other than showing your own saved posts back to you.
It performs no action on your account — it never likes, follows, posts, replies, or messages on
your behalf.

## Removing your data

Use "Empty the library" in the Encore popup to wipe your local archive at any time, or remove
the extension to delete everything it stored.

## Permissions, and why they are used

- `storage` / `unlimitedStorage` — keep your archive and settings on your device.
- `scripting` — attach Encore to an x.com tab that was already open when the extension was
  enabled, without forcing a reload.
- `webRequest` — read-only; learn the shape of your own Bookmarks/Likes request so it can be
  replayed. It never blocks, modifies, or redirects any request.
- Host access to `x.com` / `twitter.com` — Encore runs only on X.

## Open source

Encore's full source code is public, so anyone can verify exactly what it does:
https://github.com/mesomya/encore

## Contact

Questions or concerns: open an issue at https://github.com/mesomya/encore/issues

---

Encore is an independent project and is not affiliated with, endorsed by, or sponsored by X Corp.
