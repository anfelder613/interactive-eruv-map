# Interactive Eruv Map

A small, self-contained, playable explainer for how a halachic eruv gets built — based
entirely on the sources collected in Halachipedia's
[Eruvin](https://halachipedia.com/index.php?title=Eruvin) and
[Hotzaah](https://halachipedia.com/index.php?title=Hotzaah) articles (snapshots are included
here as `source - Eruvin (Halachipedia).pdf` and `source - Hotzaah (Halachipedia).pdf`).

## What's in it

Open `index.html` in any browser — no build step, no server, no dependencies.

- **City Inspector (Step 1)** — a town map with seven spots (a fenced yard, a covered
  entranceway, Main Street, an open field, a river, and the same stone post in two
  places). Click each one and sort it into the four Shabbat domains: reshut hayachid,
  reshut harabbim, karmelit or makom patur. Below it, the **City Meter** lets you change a
  street's width, the city's population and its surrounding walls, and shows how four
  approaches (Mishkenot Yakov, Rashi, Rav Moshe Feinstein, Chazon Ish) rule on whether
  it's a reshut harabbim. Six **real-city cards** (Manhattan, Brooklyn, Kew Garden Hills,
  Detroit, West Rogers Park, Los Angeles) summarize the actual rulings.
- **Build the Block** — a city-block map with two sides already walled (buildings, a
  fence) and two open gaps. Click each gap and pick the construction that forms a kosher
  *tzurat hapetach*, drawn from the article's real edge cases: a swaying wire, a wire
  fastened into a pole, and a tzurat hapetach detached from an existing wall. Close all
  three and the loop "seals" with a little confetti.
- **Kosher or Pasul? flashcards** — seven more tzurat hapetach edge cases (uneven
  doorposts, skipping poles, a sagging wire, a blocked opening, a slanted pole) as
  flip-cards. Several of these are genuine, unresolved machloket among the poskim, and
  the cards say so rather than pretending there's one clean answer.
- **Slope geometry lab** — an interactive slider exploring the "10 tefachim within 4
  amot" rule for when a natural slope counts as a halachic wall, including the
  majority/minority dispute over whether that distance is measured along the slope or
  along the ground.
- **Karpef explorer** — six sample plots (yard, empty field, garden, pond, grove, karpef)
  showing when an enclosed area still isn't "fit for dwelling" under the karpef rules.

Every scenario carries a source tag matching Halachipedia's own footnote numbering, so you
can trace any claim back to the original article. Plain `[N]` and `Eruvin [N]` tags point to
the Eruvin article; `Hotzaah [N]` tags (Step 1) point to the Hotzaah article.

## What it isn't

This is a learning game, not a halachic ruling and not a map of any real eruv. Several
scenarios are simplified to a single "correct" choice for playability where the sources
actually disagree — the explanations flag that explicitly. Whether you may carry in any
real neighborhood depends on that community's actual eruv committee and your own rav.
