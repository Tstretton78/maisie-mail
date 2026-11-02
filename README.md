# Maisie Mail — the app

A web app that runs on your phone. No Mac, no Dropbox, no accounts.

You pick a photo, type one line about it, and it makes a storybook page with
her age and the date on it. Pages stack into a feed you scroll back through.

This is step one: everything stays on your phone. Step two adds sharing so the
grandparents get their own copy; step three adds push notifications.

---

## Try it right now (no GitHub needed)

Open `index.html` on your computer and it works. But to use it on your phone
the way it's meant to be used, put it online — see below.

## Put it on GitHub Pages

Same as you did with Kippax:

1. Make a new repository, e.g. `maisie-mail`.
2. Upload every file in this folder, keeping the `fonts` folder intact.
3. Settings → Pages → Source: Deploy from a branch → `main` / `(root)` → Save.
4. Wait a minute, then open the URL it gives you on your iPhone.

**Nothing private is in these files.** The pages you make never leave your
phone, so a public repo is fine at this stage. That changes at step two, and
we'll put a login in front of it then.

## Add it to your home screen

On the iPhone, open the URL in Safari → share button → **Add to Home Screen**.

It gets the amber "M" icon, opens full screen with no browser bars, and works
with no signal.

---

## Using it

**First run** asks her name and birthday. The birthday is what calculates the
age badge on every page, forever. Stored on your phone only.

**Add today** opens your camera roll. Pick one photo or several — it walks you
through them one at a time.

**The caption** is the part that matters. One specific detail beats a
description: the thing she made, named, chose, or insisted on. That's what
gives a grandparent something to ask her about on a phone call. "She found the
sprinkler" is a door; "playing outside" is not.

**Send** shares a finished page through the normal iOS share sheet — Messages,
Mail, anything. On a computer it downloads instead.

**The age in the header** follows whatever page you're looking at. Scroll back
through the feed and it counts down. That's the thing email can never do.

---

## Things worth knowing

**Dates come from the photo, not from today.** Each page is stamped with when
the picture was actually taken, read out of the photo's own data. Add a photo
from 2024 and it files itself under March 2024 with her age at the time.

**Colours follow the season** the photo was taken in — warm amber for summer,
pale olive for spring, cool slate for winter. A year of pages won't look
monotone.

**Everything is stored in your browser**, which means: pages survive closing
the app and restarting the phone, but they are *not* backed up anywhere, and
clearing Safari's website data would delete them. Until step two exists, use
**Send** on anything you'd be upset to lose.

**The original photos aren't touched.** The app reads a copy. Deleting a page
here does nothing to your camera roll.
