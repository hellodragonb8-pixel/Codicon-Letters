<img width="1449" height="522" alt="codicon-press-start-attach" src="https://github.com/user-attachments/assets/f334e766-0d4e-43c4-980a-c3d39bd4d426" />

# Codicon Letters

Type a word and it's drawn in a pixel font where every square is a VS Code codicon. Save the result as a PNG with a transparent background, or as an SVG.

## Features

- Uppercase A–Z plus ! and -; lowercase letters are automatically capitalized as you type
- Any custom color
- Five export sizes, from Extra small to Extra large

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
