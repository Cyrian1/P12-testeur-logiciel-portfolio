# P12-testeur-logiciel-portfolio
script/script.js:90 — row.apendChild(card) → row.appendChild(card)
Critical typo that prevented all portfolio cards from rendering.

data/skills.json:30 — "title " (with trailing space) → "text"
The last skill entry had a duplicate/malformed key, so its description would never display.

index.html:11 — Removed invalid async attribute from the Bootstrap <link> tag (async is only valid on <script> elements).

index.html:12-13 — Added missing FontAwesome CDN so the contact section icons (phone, email, LinkedIn) actually render.