# English login flow presentation boards

Three visual boards follow the supplied reference style: white canvas, navy phone frames, cyan step numbers, arrows and English screen captions.

- `01-mobile-number`: Splash -> Sign in -> SMS verification -> Home.
- `02-google`: Splash -> Sign in -> Google authentication -> Home if already linked; otherwise Link number -> SMS verification -> Home.
- `03-automatic-network`: Splash -> secure company-network verification -> Home. Failed verification falls back to Sign in. The verification card is a process annotation, not an additional screen.

Each board is supplied as PNG and PDF. Google UI is illustrative; the provider controls its actual authentication screen. Account and package data are illustrative. Dimension footers describe intended implementation specifications; these generated boards are visual concepts, not pixel-exact component specifications. Use the separate `../english-wireframes/` SVG/PDF screens and `dimensions.json` for element measurements.
