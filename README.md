# Color utils

Color utils is a small library of color manipulating functions.

Most color takes a color object as input. At minimum it looks like this:

`{hue: 10, saturation: 20, lightness: 30}`

However there is helper functions that translates a string of hex color (`#BADA55`) or web hsl (`hsl(10, 20%, 30%)`) into a color object.

`const clrObj = hexToObject('#BADA55')`

## All functions

`autoCssVarOnEvent`,
`cssVarToColorObject`,
`webHslToObject`,
`hexToWebRGB`,
`hexToWebHsl`,
`colorObjToWeb`,
`hexToObject`,
`rgbToObject`,
`hslToObject`,
`rotateHue`,
`getComplementary`,
`getTriadic`,
`saturate`,
`desaturate`,
`lighten`,
`darken`,
`isGrayscale`,
`filterDarkColors`,
`filterlightColors`,
`compareLightness`,
`compareSaturation`,
`compareHue`,
`normalizeSaturation`,
`normalizeLightness`,
`normalizeHue`,

## Commands

| command          | Description             |
| ---------------- | ----------------------- |
| `npx changeset`  | Create a changeset      |
| `pnpm run build` | Build out esm/mjs files |
| `pnpm run lint`  | Check that ts ok        |
