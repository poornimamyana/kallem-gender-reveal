# Kallem Family Gender Reveal Website

A responsive, single-page invitation website with an elegant pastel luxury style.

## Preview locally
1. Extract the ZIP.
2. Open `index.html` in a browser.

## Publish with GitHub Pages
1. Create a new GitHub repository (or use an existing one).
2. Upload `index.html` to the repository root.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Choose `main` and `/ (root)`, then save.
6. Wait for GitHub Pages to publish the site.

## Customise event information
Open `index.html` and find `const CONFIG = {` near the bottom. Update:
- `eventDate`: ISO date/time, e.g. `2026-11-08T15:00:00+01:00`
- `eventDateText`: display date
- `eventTimeText`: display time
- `venueName` and `venueNote`
- `mapUrl`: optional Google Maps link
- `rsvpEmail`: email address for mailto-based RSVP

The countdown stays inactive while `eventDate` is blank. Do not publish until the date, time, venue and RSVP method are correct.

## RSVP note
The included RSVP form prepares an email in the guest's email app. For automatic collection without relying on the guest's email app, connect a service such as Google Forms or Formspree, or add a backend.

## Privacy
This is a static website. It does not store RSVP submissions or track visitors by itself.
