<img width="1425" height="512" alt="codicon-hello-code-gear" src="https://github.com/user-attachments/assets/6844ae32-b319-4f37-9777-dffc3d39289e" />



# Codicon Letters

Type a word and it's drawn in a pixel font where every square is a VS Code codicon. Save the result as a PNG with a transparent background, or as an SVG.

## Features

- Uppercase A–Z plus ! and -; lowercase letters are automatically capitalized as you type
- Any custom color
- Five export sizes, from Extra small to Extra large
- Optional wipe animation: sweeps change the codicons across the whole design, cycling left to right, bottom to top, right to left, then top to bottom
- Start with 5 default loop icons, click any to replace it, and save the animation as a GIF or MP4

Enable **Codicon wipe loop** under Animation to start the preview animation. Turn it off to return to your selected icon. The setting is remembered, but animation stays off when your system requests reduced motion. The loop stops while the page is hidden and restarts when it becomes visible. PNG and SVG exports remain static and use your selected icon, not an in-progress wipe.

The loop starts with star, heart, flame, gear, and rocket icons. Click any **Loop icon**, then choose its replacement in the icon grid above; **Cancel replacement** leaves it unchanged. Your static PNG/SVG icon is not changed. You can remove icons with × (keeping at least 2), or select an icon and click **Add** to bring the loop back up to 5. Existing saved loops are kept; empty or single-icon loops are filled with defaults.

Check **Codicon wipe loop** to enable **Save GIF** and **Save MP4**. Export also needs non-empty text and loaded loop icons, and is disabled while another animation export is running. Reduced-motion settings keep the preview still without preventing export. The buttons export one seamless loop of your icons at the chosen image size, long enough to show all four wipe directions. Both use the preview's light or dark stage color as an opaque background. The GIF is encoded in the page. The video is recorded in real time with the browser's MediaRecorder, so keep the tab open for the ~10 to 15 seconds it takes. Browsers that can't record MP4 offer **Save WebM** instead. GIFs are limited to 4 million pixels per frame and videos to 4K.

## Run it locally

The page loads its font and icons from separate files, so open it through a local web server rather than double-clicking the file:

```
python3 -m http.server 8000
```

Then visit http://localhost:8000

## Files

- `index.html`: the app, including the spacing rule
- `font/letters.json`: the Customize pixel font, drawn with `#` for each square
- `codicons.json`: icon outlines, one per line

## Credits

Icons: [Codicons](https://github.com/microsoft/vscode-codicons) by Microsoft, licensed under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). The outlines in `codicons.json` were converted from the Codicons font.

Pixel font designed by Nina Shahriaree

## License

- Code: MIT, see `LICENSE`.
- Customize font (`font/letters.json`): SIL Open Font License 1.1, with the Reserved Font Name "Customize". See `font/OFL.txt`.
- Icons (`codicons.json`): Codicons by Microsoft, CC BY 4.0.
