Political Sports Cards — Landing Page
A single-page, self-contained landing site (index.html) built for the PSC launch/ad campaign. No build step, no dependencies to install — it's one HTML file with everything inline.
Publish it on GitHub Pages (no git required)
1. Open your repo at github.com/carissadavis1976-creator/PSC.
2. Click Add file → Upload files, and drag in index.html (and this README if you want it there too).
3. Commit the upload directly to your main branch.
4. Go to Settings → Pages, set Source to Deploy from a branch, branch main, folder / (root), then Save.
5. GitHub will give you a live URL (usually https://carissadavis1976-creator.github.io/PSC/) within a minute or two.
What to swap in before launch
Search the file for the word REPLACE — every placeholder is flagged with a comment:


* Logo — the gold star mark in the nav/footer is a stand-in for your real logo.
* Headline & copy — hero title, subtext, and section descriptions are draft copy.
* Trailer — the video block currently opens a "coming soon" popup. Once your 30-second spot is ready, swap the .trailer-box div for a real <video> tag or a YouTube/Vimeo embed.
* The Lineup cards — the four sample cards (The Incumbent, The Challenger, etc.) use generic archetype names and placeholder stats/icons so nothing here implies a real person's likeness. Replace with your actual card names, art, and stat categories.
* Email signup — the form currently just shows a confirmation message in the browser; it isn't connected to anything yet. Wire it to a service like Mailchimp, ConvertKit, or Formspree (all have a simple form-action or API snippet you can drop into the <form> and the JS submit handler).
* Social links — the four icon links at the bottom point to #; update the hrefs to your real profiles.
* The App section — links out to political-sports-cards-072526.ai.studio (your Civic Cards dashboard) in a new tab. If the app ever moves to its own domain, update that one href.
* Contact email / footer — replace hello@example.com and review the disclaimer paragraph with your own wording (see note below).
One legal note
Because the concept riffs on real political figures, it's worth a quick pass by an attorney once you're using real names, photos, or likenesses on the cards — right-of-publicity and trademark rules vary by state and get more relevant the closer the cards get to real people. The placeholder footer includes a generic parody/non-affiliation disclaimer as a starting point, not legal advice.
Style notes
* Fonts: Bebas Neue (headlines) + Inter (body), loaded from Google Fonts.
* Palette: dark charcoal/navy background with a gold-foil accent, meant to read as a premium collectible rather than a campaign site for any one side — red and blue appear only as neutral highlight accents.
* Fully responsive; mobile nav collapses into a full-screen menu.