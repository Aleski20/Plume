# Plume

A markdown editor for Discord roleplay. You write on the left, you see exactly what Discord will render on the right.

**Live at [plume.ale.ski](https://plume.ale.ski)**

## What it does

- Live preview that follows Discord's actual parsing rules, not generic markdown: `_` stays literal inside a word, `>` needs its space, nothing is interpreted inside a code block
- Toolbar for every tag Discord supports, plus keyboard shortcuts
- A writing convention loaded on arrival, so a newcomer sees which tag does what without reading a manual
- Character counter against the 2000 limit
- One HTML file. No build step, no dependency, no server, no tracking, nothing leaves your browser

## Status

Built for my own use and shared as it is. Use it, copy it, fork it, host your own version, no need to ask.

What I will not do is maintain it for anyone else. There is no roadmap, no support, no issue triage. It changes when I need it to change, and only then. Bug reports and pull requests may sit unread for a long time, or forever. If you need something different, forking is the right move.

## Language

The interface, the loaded template and the code comments are in French, and that is not going to change. The code itself is readable regardless, and translating is exactly the kind of thing a fork is for.

## Running it yourself

Download `index.html` and open it in a browser. That is the whole procedure.

To put it online, drop that single file on any static host: GitHub Pages, Cloudflare, Netlify, or a folder on a web server.

## Credits

Most of the code was written with an AI assistant, then tested and adjusted by hand.

The feather is a clipart I did not draw. The preview mimics Discord's interface for accuracy; this project is not affiliated with Discord in any way.
