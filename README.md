# PT+ ToolDeck | PenTest+ PT0-003

A mobile-first, installable flashcard-style web app created from the attached **Master Tool List** and **Attack · Exploit · Tool Correlation** PDFs, with the official PT0-003 objectives for named-tool coverage.

- **113 cards**, including **97 explicitly named tool/tool-family study cards** and **16 supplemental cards** from the master list.
- Two directions: **scenario → tool** and **tool → purpose**.
- Each card contains **what it does**, a **likely exam clue**, a custom **memory hook**, and a **look-alike distinction**.
- Review filters: official, supplemental, missed, starred, due, unseen, topic.
- Tap card to flip. Mark **Got it** or **Review again**. Progress and favorites save in the browser's local storage.
- Compare tab: 21 close-call tool pairings. Study progress by topic, with JSON progress export.

## Open on iPhone

### Simple file option
Download `PenTest_Plus_ToolDeck_iPhone.html`, save it in Files, and open it. It runs as a single HTML page. Some file-preview applications restrict local storage, so for **reliable saved progress** and Home Screen installation, use the HTTPS option below.

### Recommended: install as a web app
1. Unzip `PenTest_Plus_ToolDeck_PWA.zip`.
2. Upload the **contents** of the `PenTest_Plus_Flashcards_App` folder to any static HTTPS host (for example, GitHub Pages or Netlify). Do not upload just the ZIP unless your host unpacks it.
3. On iPhone, open the hosted link in **Safari**. Tap **Share → Add to Home Screen → Add**.
4. Launch from the Home Screen once while online. After that, the app shell works offline.

The app doesn't need an account or an external database. Results stay in the browser / installed web app on that device. Export progress before resetting or changing browsers. Host-installed app storage and Safari tab storage can be distinct.

### Notes
- An official label means the tool or tool family is explicitly named in the PT0-003 objectives, not that CompTIA endorses this app.
- The PDF sources group some tools together (for example, `nslookup/dig`); the app sometimes separates them to make recall easier.
- The official objectives call out **tcprelay**, while the reference PDF also discusses **tcpreplay**. They are separate study entries.
- Memory phrases are original study aids rather than official definitions.
- All attack-related content assumes authorization and defined scope.
