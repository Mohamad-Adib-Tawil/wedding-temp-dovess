# Wedding Invitation

A static Arabic wedding invitation built from the supplied Doves template assets.

## Edit the invitation

Update `wedding.config.js` to change the couple, event details, venue, copy, contact links, and asset paths. The original gallery, dove sprite, and emblem are stored under `media/` and `templates/doves/assets/`.

The invitation is a static GitHub Pages site. RSVP details are composed into a WhatsApp message because GitHub Pages does not provide the original invitation site's RSVP backend.

## Local preview

Run a local static server from this folder, then open `http://localhost:8000`.

```sh
python3 -m http.server 8000
```
