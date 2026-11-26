<img width="1425" height="512" alt="codicon-hello-code-gear" src="https://github.com/user-attachments/assets/6844ae32-b319-4f37-9777-dffc3d39289e" />



# Codicon Letters

One type family with inputs and outputs: Express what you want to say with letters built from VS Code codicons, then save a PNG, download a font, or save a GIF of your animation.

## Features

- Uppercase A–Z plus ! and -; lowercase letters are automatically capitalized as you type
- Any custom color
- Five export sizes, from Extra small to Extra large
- Optional wipe animation that cycles through up to 5 icons, saved as a GIF or MP4
- Download your chosen icon as an installable font (.ttf)

## Animation

Check **Codicon wipe loop** to play the animation. Click any loop icon to swap it for another, then use **Save GIF** or **Save MP4**.

## Download

Select an icon and download its font to install and use in apps like Figma or Word. After installing, restart the app, then select the Customize Codicon font in Regular.

## Open the app with Copilot in VS Code

After cloning the repository, ask Copilot:

PROMPT:
> Please check whether this repo has a live build and open it. Open the latest running app in the browser

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
