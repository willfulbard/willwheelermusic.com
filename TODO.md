# TODO

Outstanding items for willwheelermusic.com.

## Content

### Project descriptions

- [ ] Refine description in `src/content/projects/forgery.md`
- [ ] Refine description in `src/content/projects/dance-dinos.md`
- [ ] Refine description in `src/content/projects/punch-party.md`
- [ ] Refine description in `src/content/projects/the-flagstones.md` (and reconcile frontmatter `ensemble: Trio` with body text calling it a "quartet")
- [ ] Refine description in `src/content/projects/will-and-holly.md`
- [ ] Refine description in `src/content/projects/yellowfoot.md`
- [ ] Refine description in `src/content/projects/starry-plough-ceili-band.md`

### Photos

- [ ] Add hero photo for **Will and Holly** (frontmatter still says `# TODO: add photo`)
- [ ] Add hero photo for **Punch Party** (frontmatter still says `# TODO: add photo`)
- [ ] Collect photographer credits for any photos used

## Operational

### Calendar (ongoing)

- [ ] Add upcoming gigs to the public Google Calendar as they're booked
- ⚠️ Reminder: every event on this calendar appears publicly on the site — keep private notes (pay, contact, etc.) on a separate calendar

## Design refinement (lower priority)

- [ ] Review color palette once more real photos are in place — accent color may want to be drawn from photography
- [ ] Confirm font choices (currently Lora + Source Sans 3); swap if they don't feel right
- [ ] Mobile testing pass once content is filled in

## Future phases (not scoped now)

### Phase 2 — Enrichment

- [ ] EPK page (short bios, high-res photos, tech rider, press quotes)
- [ ] Bandsintown integration (alternative to Google Calendar if it becomes useful)

### Phase 3 — Optional growth

- [ ] Teaching/lessons page (when offering them)
- [ ] Music/Discography page (when there are recordings)
- [ ] Blog (tune of the week, session notes, travel writing)
- [ ] Patreon integration

## Resolved

Major decisions and milestones for reference:

- ✅ Tagline: "Living music from old roots"
- ✅ Tech stack: Astro
- ✅ Domain: willwheelermusic.com
- ✅ Hosting: Cloudflare Pages with nightly cron rebuild via GitHub Actions
- ✅ Newsletter: not doing one (Instagram for gig updates)
- ✅ Lark Camp / Starry Plough: mentioned in About bio, no dedicated section
- ✅ Contact form: FormSubmit with hashed endpoint, FormSubmit-handled thank-you redirect
- ✅ About page written, with side-image stack and gallery/videos infrastructure
- ✅ All 7 project pages stubbed; cover-style hero on each
- ✅ Calendar integration: public Google Calendar, fetched at build with 3-attempt retry, build fails on total failure
- ✅ Recurring events expanded to next 4 occurrences with correct timezone handling
- ✅ Project-slug links in event descriptions
- ✅ Click-to-zoom gallery modal
