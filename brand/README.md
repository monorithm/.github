# The Monorithm icon

The icon of Monorithm is an open ring with a cube in its core. A pointy-top hexagon ring opens at its top vertex. In the opening sits a cube, which three faces and a Y-shaped gap make. The icon is signal blue on a graphite tile. Use it for the organization, the websites, and the repositories.

![The Monorithm icon](monorithm-app-icon-1024.png)

## The construction

The grid is 256 × 256, and the centre of the mark is at (128, 128). All corners are sharp. Crisp edges are necessary for the cube illusion.

| Item | Master | Small cut (32 to 48 px) | Plain cut (16 px) |
| --- | --- | --- | --- |
| Outer hexagon, circumradius | 118 | 118 | 118 |
| Ring thickness, across an edge | 38 | 40 | 42 |
| Gap between the ring and the core | 14 | 22 | 24 |
| Opening at the top vertex, width | 28 | 34 | 36 |
| Core | Cube, Y gap 14 | Cube, Y gap 22 | Plain hexagon |
| File | `monorithm-mark.svg` | `monorithm-mark-small.svg` | `monorithm-mark-16.svg` |

One gap width separates the ring from the core and the faces of the cube from each other. Each face of the cube moves out from the centre by the gap ÷ 1.732. All openings are real gaps between shapes, not shapes in the color of the ground.

On a tile, the mark is 11/16 of the tile height.

## The colors

| Use | Mark | Ground |
| --- | --- | --- |
| Primary: the tile | `#5ca3ff` | `#181818` |
| On a light ground, one color | `#1f6fe0` | The light ground |
| One color, black | `#000000` | A light ground |
| One color, white | `#ffffff` | A dark ground |

`#5ca3ff` on `#181818` gives a contrast of 6.9 : 1.

## The files

| File | Use |
| --- | --- |
| `monorithm-mark.svg` | The master: the mark in black, on a transparent ground |
| `monorithm-mark-small.svg`, `monorithm-mark-16.svg` | The masters of the two small cuts |
| `monorithm-app-icon.svg`, `monorithm-app-icon-1024.png` | The tile with rounded corners |
| `monorithm-avatar.svg`, `monorithm-avatar-1024.png` | The GitHub avatar: a full square. GitHub rounds the corners |
| `monorithm-social.svg`, `monorithm-social-1280x640.png` | The social preview of a repository or a page |
| `monorithm-black`, `-white`, `-mono-1f6fe0`, `-mono-5ca3ff`, `-square` | The one-color versions, in SVG and in PNG at 1024 px |
| `favicon.svg`, `favicon.ico`, `favicon-16/32/48.png` | The favicon. The ICO has the plain cut at 16 px and the small cut at 32 and 48 px |
| `apple-touch-icon.png`, `icon-192.png`, `icon-512.png`, `maskable-512.png`, `site.webmanifest` | The web icons of a site |

## The rules

- Use the tile when the ground is not graphite.
- Keep clear space around the mark of a minimum of the width of the opening.
- At 32 to 48 px, use the small cut. At 16 px, use the plain cut.
- Do not change the colors, the proportions, or the corners. Do not add a shadow, an outline, or a gradient.
- Do not put text in the mark.

## The source

On 15 November 2026, the user selected the open ring from two rounds of concepts. The concepts combined a hexagon with a cube illusion in the centre and a hexagon with an open vertex. The earlier favicon of the language site (a hexagon ring in `#5ca3ff` on `#181818`) gave the ring and the colors.
