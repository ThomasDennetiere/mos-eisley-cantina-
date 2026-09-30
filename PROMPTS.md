## Features section (inline edit Cmd+K)

**Prompt used:**

Stack: HTML + Tailwind Play CDN.
Add a three-column features section inside #features for the Mos Eisley Cantina landing page.
Layout: grid-cols-1 md:grid-cols-3 gap-6.
Each card: <article>, icon box (size-12 rounded-xl bg-violet-500/10 ring-1 ring-violet-400/20), <h3>, one short paragraph.
Palette: bg-white/[0.03], border border-white/10, ring-1 ring-white/5, backdrop-blur.
Hover: hover:-translate-y-1, hover:border-violet-400/30.
focus-visible on any link.
Copy (exact):
- Live music nightly. Sunset to sunrise, loud enough to drown out a bounty hunter.
- Smugglers welcome. No questions asked. Back booths, no records kept.
- Droids: see house policy. Limits on the floor. Power-down recommended.

**What I corrected after generation:**
- Replaced a hallucinated `text-primary-500` with `text-violet-300`.
- Added `aria-labelledby="features-title"` on the section to match the h2 id.
- Renamed a generic "Feature 1" heading the AI inserted back to the exact Cantina copy.
