# Contributing

Thanks for helping make this list great! Please follow these rules so we stay consistent and pass `awesome-lint`:

## How to add a link
- One entry per PR.
- Use the format: `- [Name](https://example.com) — Short description in one sentence.`
- Prefer **official docs or repos**. Avoid paywalled or dead links.
- Make sure the resource is **active** and the description is accurate.
- Keep scope **AI chaos engineering** (evals, experiments, guardrails, observability, governance) or **foundational chaos**.
- Alphabetize within a section when it’s not obviously ordered by concept.

## Local checks (optional)
```bash
# Lint Awesome style
npx awesome-lint

# Check links
npx lychee --no-progress --accept 200,206 .
```

## Acceptance criteria
- Clear value for practitioners.
- Not vendor spam / thin content.
- Description ends with a period.
- No tracking querystrings in URLs.
