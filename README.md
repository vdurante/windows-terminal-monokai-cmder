# Monokai Cmder for Windows Terminal

Attempt to recreate Cmder color scheme as close as possible on Windows Terminal.

## Comparison

![Comparison](./comparison.png "Comparison")

## Installing

1. Open Windows Terminal Settings
2. Paste the following inside `schemes`

```json
{
  "name": "Monokai Cmder",

  "cursorColor": "#FFFFFF",
  "selectionBackground": "#cccc81",

  "background": "#272822",
  "foreground": "#cacaca",

  "black": "#272822",
  "red": "#a70334",
  "green": "#74aa04",
  "yellow": "#b6b649",
  "blue": "#01549e",
  "purple": "#89569c",
  "cyan": "#1a83a6",
  "white": "#cacaca",
  "brightBlack": "#7c7c7c",
  "brightRed": "#f3044b",
  "brightGreen": "#8dd006",
  "brightYellow": "#cccc81",
  "brightBlue": "#0383f5",
  "brightPurple": "#a87db8",
  "brightCyan": "#58c2e5",
  "brightWhite": "#ffffff"
}
```

3. Add the following to `profile > defaults`

```json
"colorScheme": "Monokai Cmder"
```
