# Plume

A markdown editor for Discord roleplay. You write on the left, you see exactly what Discord will render on the right.

**Live at [plume.ale.ski](https://plume.ale.ski)**

## What it does

- **Faithful preview.** Follows Discord's actual parsing rules, not generic markdown: `_` stays literal inside a word, `>` needs its space, nothing is interpreted inside a code block, `####` is not a heading.
- **Toolbar** for every tag Discord supports, plus `Ctrl+B` / `Ctrl+I` / `Ctrl+U`.
- **A writing convention loaded on arrival**, so a newcomer sees which tag does what without reading a manual.
- **Up to three character profiles**, each with an avatar, a display colour, its own starting template and its own Tupperbox tag. Switching character switches all of it at once.
- **Tupperbox toggle.** Your proxy tag is added to the copied text, never to the preview. Both `Name:text` and bracket formats like `[text]` work.
- **Automatic draft saving.** Close the tab, come back, your message is still there.
- **Character counter** against the 2000 limit, tag included when it is active.

Everything lives in your browser. No account, no server, no tracking, nothing leaves the page. One HTML file, no build step, no dependency.

## Status

Built for my own use and shared as it is. Use it, copy it, fork it, host your own version, no need to ask.

What I will not do is maintain it for anyone else. There is no roadmap, no support, no issue triage. It changes when I need it to change, and only then. Bug reports and pull requests may sit unread for a long time, or forever. If you need something different, forking is the right move.

## Language

The interface, the loaded template and the code comments are in French, and that is not going to change. The code itself is readable regardless, and translating is exactly the kind of thing a fork is for.

## Running it yourself

Download `index.html` and open it in a browser. That is the whole procedure.

To put it online, drop that single file on any static host: GitHub Pages, Cloudflare, Netlify, or a folder on a web server. Profiles and drafts use `localStorage`, so they are per browser and per device, and clearing your browsing data wipes them.

## Credits

Most of the code was written with an AI assistant, then tested and adjusted by hand.

The feather is a clipart I did not draw. The preview mimics Discord's interface for accuracy; this project is not affiliated with Discord in any way, and Tupperbox is a third-party bot I have no connection to.
