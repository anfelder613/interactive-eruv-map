# Interactive Eruv Map

A small, self-contained, playable explainer for how a halachic eruv gets built — based
entirely on the sources collected in five Halachipedia articles:
[Introduction to the Modern Eruv](https://halachipedia.com/index.php?title=Introduction_to_the_Modern_Eruv),
[Hotzaah](https://halachipedia.com/index.php?title=Hotzaah),
[Eruvin](https://halachipedia.com/index.php?title=Eruvin),
[Sechirut Reshut](https://halachipedia.com/index.php?title=Sechirut_Reshut) and
[Eruv Chatzerot](https://halachipedia.com/index.php?title=Eruv_Chatzerot). A PDF snapshot of
each is included here as `source - <article> (Halachipedia).pdf`.

## What's in it

Open `index.html` in any browser — no build step, no server, no dependencies.

- **Start Here** — the three things every eruv needs (a border, a rental, shared food),
  why a string border only works outside a true reshut harabbim, four ways a city can avoid
  being one, and a step-through version of the Chazon Ish's "chain of streets" diagram.
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

- **Rental Builder (Step 3)** — set the terms of a *sechirut reshut* (who you rent from, spoken
  or signed, payment, term) and see whether it holds up, plus flip-cards on who can rent it to you.
- **Make the Eruv (Step 4)** — put the steps of making an *eruv chatzerot* in order, plus
  flip-cards on when one is needed (apartments, dorms, hotels, hospitals).

Every scenario carries a source tag matching Halachipedia's own footnote numbering, so you
can trace any claim back to the original article. Plain `[N]` and `Eruvin [N]` tags point to
the Eruvin article; `Hotzaah [N]`, `Intro [N]`, `Sechirut [N]` and `Chatzerot [N]` tags point to
the other four.

## What it isn't

This is a learning game, not a halachic ruling and not a map of any real eruv. Several
scenarios are simplified to a single "correct" choice for playability where the sources
actually disagree — the explanations flag that explicitly. Whether you may carry in any
real neighborhood depends on that community's actual eruv committee and your own rav.
