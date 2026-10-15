# Contributing

You don't need to know Git. The easiest route is an **Issue form**: click *Issues → New issue* and pick "Submit a case" or "Ask a rules question".

## Ground rules

1. **Paraphrase, don't paste.** Describe the rule in your own words and cite section + page (e.g. "§10.3, p.30"). Don't copy rulebook paragraphs, card text, tables or artwork. This keeps the project on the right side of the publisher's IP.
2. **Name the printing.** We use the third printing (2026). If yours differs, say so.
3. **Be honest about status.** Use `rules-derived` for "this follows from the text", `consensus` only with a link to the discussion, `confirmed` only with a link to a designer or official ruling, and `disputed` when you aren't sure.
4. **Show your working.** Put numbers in examples and check the arithmetic. Say which parts of the setup are invented for illustration.
5. **Don't guess icons.** The rulebook uses icons heavily. If you aren't sure what one is, say "[icon]" and flag it.

## Adding a case with a pull request

1. Copy `cases/_TEMPLATE.md` to `cases/<topic>/NNN-short-name.md`.
2. Fill in the front matter and sections. Tags are lowercase, hyphenated, so tools can index them.
3. Add a row to the topic's `README.md`.
4. Open a pull request. A reviewer checks the page references and the step-by-step resolution.

## Reviewers

Merge when you can reproduce the resolution from the cited pages. If you can't tell, merge as `disputed` and add a row to `docs/open-questions.md`. Don't quietly drop it.

## Official answers

This is an unofficial fan project. A designer's or publisher's ruling beats anything here: link it and upgrade the case to `confirmed`.
