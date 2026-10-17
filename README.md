# EU:PoP Community Rules Companion

A community-written, example-driven companion to the rulebook for **Europa Universalis: The Price of Power**.

The rulebook is precise but terse, and the trickiest parts (especially **Peace Resolution**) are easiest to understand through worked examples. This project collects those examples in one place, reviewed and corrected by people who know the rules well.

> **Unofficial fan project.** Not affiliated with or endorsed by Paradox Interactive or the game's publisher. You need the rulebook to play. We paraphrase and cite page numbers; we do not copy the rulebook, card text or artwork. See [CONTRIBUTING.md](CONTRIBUTING.md).

Rule references in this repo are to the **third printing (2026) multiplayer rulebook**. If your printing differs, note it in your contribution. The publisher's own **Peace Resolution flow chart (Player Aid B, v1.3, 2026)** is the official companion: use it alongside this guide. We cite it but don't reproduce it.

## Where to start

| I want to... | Go to |
|---|---|
| Understand Peace Resolution in plain English | [docs/peace-resolution/00-overview.md](docs/peace-resolution/00-overview.md) |
| See worked examples | [cases/peace-resolution/](cases/peace-resolution/) |
| Wars, Truces and other general rules | [docs/general/](docs/general/README.md) |
| See what we are still unsure about | [docs/open-questions.md](docs/open-questions.md) |
| Known chart and printing issues | [docs/known-issues.md](docs/known-issues.md) |
| Add an example or ask a question | [CONTRIBUTING.md](CONTRIBUTING.md) |

## How much to trust each example

Every case carries a status so nobody mistakes a guess for an official ruling.

| Status | Meaning |
|---|---|
| 🟢 `confirmed` | Confirmed by the designers or an official FAQ (link required) |
| 🟡 `consensus` | Agreed by experienced players in the community discussion (link required) |
| 🔵 `rules-derived` | Follows directly from the rulebook text; page references given |
| 🔴 `disputed` | The rules are unclear or players disagree; see the open question |
| 🟣 `houserule` | A table houserule some groups use. **Not** an official rule |

Seed examples start as 🔵 or 🔴.

**Whose word counts.** A ruling from the game's designer (Eivind at Aegir Games) is the top tier and earns 🟢. Mikhs (developer) is usually the correct answer and also earns 🟢 when the ruling is explicit. Experienced community players (for example Atlas, Miroku20X6, damifoe) are 🟡 unless a designer confirms. Dates are shown beside community rulings, because answers can be superseded. Moving a case up to 🟡 or 🟢 requires a link to the discussion or ruling.

## Maintainers

Reviewers (people who approve pull requests) should be players with a solid grip on the rules. Suggested process:

1. Contributors open an Issue (no Git knowledge needed) or a pull request.
2. A reviewer checks the page references and the step-by-step resolution.
3. Anything the reviewer is unsure of is merged as `disputed` and added to the open questions list, not quietly dropped.

Recommended repository settings: enable **Discussions** (for "is this how it works?" threads) and require one approving review on pull requests.

## Licence

Choose a licence before publishing. For a community text resource, [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/) is a common fit. Add a `LICENSE` file once decided. The licence covers contributors' own words only, not the game's rules text or artwork.
