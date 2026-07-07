# Global Healing Network

**Heal the World. Earn Karma.**

The Global Healing Network (GHN) is a worldwide community of healers united by love, intention and the [OASIS Web4 Karma API](https://oasisomniverse.one). It is one of the core applications within the [OASIS Omniverse](https://oasisomniverse.one) ecosystem — a Web4 platform built around universal avatars, karma and a shared mission to make the world a better place.

---

## What is GHN?

GHN allows anyone to:

- **Submit a Love Beam request** — ask the global community to send healing energy to a person, animal, place or situation in need
- **Join live healing sessions** — synchronised group distance-healing events open to all
- **Register as a healer** — build a public profile, attract clients and earn karma for every session
- **Form healing groups** — permanent groups that accumulate shared karma and reputation over time
- **Browse the Healing Archive** — a community knowledge base of healing content
- **Post in the Healing Forum** — an open discussion space for healers and seekers

Every meaningful action on GHN earns **OASIS karma** — a persistent score that carries across every app in the OASIS Omniverse.

---

## Tech Stack

| Layer | Detail |
|---|---|
| Front-end | Single-file `index.html` — inline CSS + vanilla JS, no build step |
| Fonts | Orbitron, Rajdhani, Share Tech Mono (Google Fonts) |
| Animations | Canvas 2D — Earth globe with healing beam radiation, love beam pulse rings, star field |
| OASIS API | `@oasisomniverse/web4-api@2.0.2` via esm.sh |
| Forms | formsubmit.co — no server required |
| Hosting | Static — deployable to any CDN or static host |

---

## Karma Actions

| Action | Karma Earned |
|---|---|
| Join a public Love Beam | +250 |
| Join a private Love Beam | +300 |
| Register as a healer | +500 |
| Submit a healing article | +100 |
| Post in the Forum | +50 |

---

## Sections

- **Hero** — canvas globe animation, headline CTAs
- **Stats Band** — live platform statistics
- **Six Pillars** — Directory, Love Beam, Healing Groups, Love Archive, Healing Forum, Karma
- **Submit a Love Beam** — request form for public or private healing sessions
- **Live Beam Sessions** — active beams with join functionality
- **Healing Groups** — example groups with karma totals and Create/Browse CTAs
- **Healing Archive** — community articles with ratings and read counts
- **Healing Forum** — discussion threads with reply counts
- **Healer Directory** — searchable preview with filter pills (full directory coming)
- **Violet Karma** — 8 karma-earning actions explained
- **Noah's Ark Integration** — cross-app animal healing connection
- **OASIS Integration** — universal avatar and karma system
- **Footer** — links, ecosystem navigation

---

## OASIS Ecosystem

GHN is one of several interconnected apps in the OASIS Omniverse:

- **GraceBook** — Web4 social network
- **Noah's Ark ARN** — global animal rescue network
- **Justice League Academy** — free learning platform
- **Our World** — immersive Web4 world
- **OPORTAL** — avatar creation and management

---

## Running Locally

No build step required. Open `index.html` directly in a browser, or serve with any static server:

```bash
npx serve .
# or
python -m http.server 8080
```

---

*Part of the [OASIS Omniverse](https://oasisomniverse.one) · Powered by OASIS Web4*
