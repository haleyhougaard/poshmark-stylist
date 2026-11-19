# poshmark-stylist

Your Poshmark likes are a closet you haven't bought yet. This Claude skill styles them.

It reads the likes in your own signed-in browser, keeps only what is still for sale in your size and your price range, checks every piece against your color season and your Pinterest board, then builds a lookbook. Every look has shoes and a bag, and no piece shows up twice.

## What you set

Fill in [my-style.md](poshmark-stylist/my-style.md) once. Claude reads it before every run.

- **Sizes:** tops, bottoms, dresses, shoes, and anything you want flagged instead of dropped.
- **Coloring:** your color season, plus colors you love and colors you never wear near your face.
- **Price range:** the most you'll pay per piece.
- **Taste:** a Pinterest board and how many of its newest pins to read.
- **Never:** the cuts, fabrics and trends you're done with.
- **Occasions:** where you're going, so a trip gets weather-checked looks.

## How it runs

1. Reads your Pinterest board for the style bar.
2. Reads your Poshmark likes fresh, in your browser, and filters them.
3. Searches Poshmark for the gaps, across your whole palette and by shape and fabric.
4. Styles the looks, names the pins behind each one, and flags anything off-size.
5. Publishes the lookbook as a page you can keep editing with Claude.

## Safety

It only reads. It never likes, buys, offers, comments or follows, and it never asks for your Poshmark or Pinterest password. You stay signed in to your own browser and Claude reads what you already see. Your sizes and preferences live in your copy of `my-style.md`, so keep that copy private.

## Use it

It needs Claude with a browser tool that can see your signed-in Chrome, such as Claude in Chrome.

- **Claude Code:** copy the `poshmark-stylist` folder into `~/.claude/skills/`.
- **Claude app:** zip the folder and add it as a custom skill in your settings.

Then ask in plain words: "Build me a lookbook for a long weekend in Lisbon."

Poshmark and Pinterest are trademarks of their owners. This project isn't affiliated with either.

## Who made this

Haley Hougaard, a brand marketer who builds her own AI. I run And/Also Studio, a Fractional AI Officer practice for founder-led brands.

[haleyhougaard.com](https://haleyhougaard.com)

## License

MIT. Use it, change it, make it yours. Keep the license file with any copy.
