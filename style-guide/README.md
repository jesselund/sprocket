# Sprocket — brand and design system

Sprocket Financial Services, Inc. ("Sprocket") provides real-time cross-border payments and foreign exchange to businesses and financial institutions: corporate treasury and cash management, international tuition payments, and cross-border B2B and B2C commerce. Sprocket operates through the banking licenses of TS Banking Group, a Federal Reserve–regulated bank holding company based in Trainer, Iowa, which is also a part-owner of Sprocket.

The idea behind the brand: money should move as fast as information. Today it doesn't. Sprocket removes the friction of settling transactions across borders and currencies.

This system is version 3 of the brand. It keeps the 2022 logo, the coral signature and the Manrope and Public Sans pairing, and moves the palette to a midnight-and-electric-indigo direction that suits a B2B payments company.

## Tagline

**Money, at the speed of thought.**

Approved variations, for headlines and campaigns:

- Moving money at the speed of thought.
- Money should move like information.
- Every border. Every currency. No friction.
- Think it. Send it. Settled.

## Voice

Confident, precise and calm. Sprocket speaks to treasurers, finance teams and partner banks, and they want clarity, not hype.

- Do: short sentences, concrete outcomes ("Funds arrive in minutes, not days"), plain words for complex things, sentence case for headings and buttons.
- Don't: exclamation marks, crypto or consumer-app slang ("wallet", "tokens", "to the moon"), superlatives you can't prove, emoji.
- Numbers are a feature. Show real rates, corridors and times, set in the mono face.

### Claims and required language

Sprocket is not a bank. Banking services are provided by TS Banking Group's chartered banks. Every public page carries a disclosure to that effect; use the exact wording that counsel and the partnership agreement approve.

Never use "FDIC insured", "bank account", "guaranteed", "instant" or a specific settlement time (such as "2 seconds") unless compliance has approved that wording and it can be backed up. "Real-time" and "in minutes" need the same review.

## Logo

The logo is the coral symbol beside the Sprocket wordmark. Use the files in Logos; never retype the wordmark in any font.

- On light grounds: `sprocket-logo-color.svg` (coral symbol, midnight wordmark).
- On midnight, surface-inverse or photography: `sprocket-logo-reversed.svg` (coral symbol, white wordmark).
- One-color uses (stamps, embossing, partner co-branding): `sprocket-logo.svg` in ink or white.
- The symbol stays coral in color applications, including next to indigo. Indigo is never used for the logo.
- Don't stretch, rotate, outline, add effects to, or recolor the logo beyond these versions.

## Color

The palette is led by **midnight** and **electric indigo**, with **coral** as Sprocket's warm signature and **velocity mint** as the signal for speed.

| Role | Token | Use |
|---|---|---|
| Ground | `surface`, `surface-subtle` | Pages and alternating sections |
| Dark brand panel | `surface-inverse` | Heroes, footers, feature bands |
| Text | `ink`, `ink-muted`, `ink-on-inverse` | All copy |
| Primary accent | `indigo`, `indigo-hover`, `indigo-text`, `on-indigo` | Primary buttons, links, active states |
| Signature | `coral`, `coral-text` | Logo symbol, brand moments, illustration |
| Speed signal | `velocity`, `velocity-text`, `on-velocity` | Live, real-time and settled indicators |
| Status | `success`, `warning`, `danger` | Transaction and form states only |

Rules:

- One indigo primary action per view. Secondary actions are outlined pills in `ink` with a `line` border.
- Coral is never a status color. A failed payment is `danger`, which is deliberately darker so the two can't be confused.
- Coral is never body text on light grounds (2.9:1). Use `coral-text` for short coral labels.
- Velocity is a signal, not a decoration: use it for things that are actually live or complete.
- Keep accents scarce. A typical page is about 70% ground, 20% midnight and ink, and 10% indigo, coral and velocity together.

All text tokens pass WCAG AA (4.5:1) on their stated grounds in both light and dark themes; each token's usage note gives the ratio.

## Typography

| Family | Font | Role |
|---|---|---|
| `display` | Manrope (Medium 500, SemiBold 600, Bold 700) | Headlines and headings |
| `sans` | Public Sans (Light 300, Regular 400, SemiBold 600) | Body copy, navigation, buttons, forms |
| `mono` | IBM Plex Mono (Regular 400) | FX rates, amounts, currency codes, reference numbers |

All three are free, open-licensed fonts on Google Fonts. Calibre, the font the wordmark is based on, is a commercial font; it is not used for web text unless Sprocket buys a web license.

- Headlines are Manrope Medium with slightly tight letter-spacing, in sentence case, usually ending with a period: "Moving money at the speed of thought."
- Body copy is Public Sans at 16px or larger on the web; large intro paragraphs use Public Sans Light at 18px.
- Buttons and labels are Public Sans SemiBold.
- Rates and amounts use IBM Plex Mono so digits line up: `USD → EUR 0.9184`.

## Layout and shape

- Spacing follows a 4px base: `space-1` to `space-24`. Sections are separated by `space-16` to `space-24` on desktop.
- Content max width 1200px; text columns no wider than 680px.
- Buttons, badges and status pills are always fully rounded (`radius-pill`), as in the 2022 guide.
- Cards and panels use `radius-md`; images and large brand blocks use `radius-lg` or `radius-xl`, echoing the soft corners of the symbol's blades.
- Borders over shadows: a 1px `line` hairline separates cards. Use a shadow only for floating elements like menus.
- Motif: thin angled hairlines and horizontal "speed streaks" (short pills at varied widths) suggest motion. Use them sparingly behind heroes and section breaks, never over text.

## Imagery

Sprocket now serves businesses and institutions, so photography moves away from the 2022 guide's consumer lifestyle shots.

- Use: global cities and trade (ports, skylines, transit at dusk), modern workplaces with real finance teams, campuses for the tuition use case, and abstract motion (light trails, long exposures).
- Treatment: cool, natural color; frame images with `radius-lg` or `radius-xl`; a thin coral or indigo hairline may cross the frame edge, as in the original guide.
- Avoid: piles of cash, coins, crypto imagery, handshake clichés, and stock photos of people pointing at screens.

## Iconography

Line icons with a 1.5px stroke, rounded caps and joins, drawn on a 24px grid, in `ink` or `indigo-text`. Tabler Icons or Lucide match this style. Icons never carry meaning alone; pair them with a label.

## Using this system

Colors are semantic tokens with a light and a dark theme; the light theme is the primary one. Use the token, not the hex value. Load the fonts from Google Fonts: Manrope 500/600/700, Public Sans 300/400/600, IBM Plex Mono 400. Logos are in the Logos asset group. Components (buttons, navigation, rate cards, forms) will be added as the website is built.
