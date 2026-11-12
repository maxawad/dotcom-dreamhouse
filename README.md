# dotcom dreamhouse

A single-page, pink Y2K "Tumblr blog" theme. It looks like a 2000s blog inside retro browser windows, with a scrolling marquee, a fake music player, a visitor counter and a working guestbook. It is a design experiment, not a real blog engine.

## What it does

- Shows a blog feed with photo, text, quote, chat (AIM style) and "ask me anything" posts.
- Sidebar with a profile card, navigation, a toy music player (it only changes the song title and animates a bar, no audio plays), tags and blinking badges.
- Like buttons that toggle, a live clock and a sparkle trail that follows the mouse.
- Visitor counter and guestbook that store their data in the visitor's own browser (`localStorage`). Nothing is sent to a server.

## Tech stack

- Plain HTML, CSS and JavaScript in one file (`index.html`), no framework and no build step.
- Google Fonts (Baloo 2, Playfair Display, VT323), loaded from the web. The page still works offline with fallback fonts.
- Images in `img/`.

## Run it

No install is needed. Either open `index.html` in a browser, or serve the folder:

```sh
python3 -m http.server 8000
# then open http://localhost:8000
```

## Live demo and hosting

The project is already static files without secrets. To host it, publish the repository root (for example GitHub Pages or any static host). There is no build command, and the entry point is `index.html`.

## Status

Working prototype. It is a preview theme: the posts, counts and song names are placeholder content, and it has not been packaged as a real Tumblr theme.

## Credits

Design and code by Max Awad. The images in `img/` are collage and mockup pictures used as placeholder content. Their original sources are not recorded here, so check their rights before reusing them in anything public.
