# Collision and Discoverability Research

Use this reference before making availability, collision, SEO/GEO, or preliminary trademark claims.

## 1. Research order

Research cheap, decisive failures first:

1. exact web query
2. exact name plus product category
3. GitHub or primary product ecosystem
4. critical package registry, app store, or distribution surface
5. realistic spelling and phonetic variants
6. target-language and local-market usage
7. domain and social handles when launch-critical
8. official trademark databases for commercial or high-risk projects

Stop when a critical red collision makes a candidate non-viable, unless it remains useful as an example.

## 2. Core query matrix

For `NAME` and `CATEGORY`, use the relevant subset:

```text
"NAME"
"NAME" CATEGORY
"NAME" software
"NAME" CLI
"NAME" library
"NAME" package
"NAME" app
"NAME" API
"NAME" agent
"NAME" open source
"NAME" GitHub
```

Search in English and the target market's language when the project is international.

## 3. Ecosystem checks

### GitHub

Inspect:

- exact repository names
- active same-category projects using the display name
- archived or low-activity projects
- organization or account names that dominate the identity
- stars and recency only as activity signals, not as automatic legal conclusions

An abandoned repository is still evidence, but it is not an automatic veto.

### Package and distribution surfaces

Choose only the ecosystems relevant to the project:

- npm
- PyPI
- crates.io
- pkg.go.dev and Go module paths
- RubyGems
- Packagist
- Maven Central
- NuGet
- Homebrew formulae and casks
- Docker Hub
- VS Code or JetBrains marketplaces
- browser extension stores
- Apple App Store or Google Play

Inspect the official registry directly. Search both canonical spelling and registry-normalized spelling.

### Normalization hazards

Different strings can collapse into the same package identity.

Examples to inspect manually:

- lowercase conversion
- hyphen, underscore, and period equivalence
- Rust crate hyphen versus import underscore
- scoped versus unscoped packages
- plural and singular forms
- joined versus spaced forms

Do not assume a visually different string is a distinct namespace.

## 4. Near variants

Search variants that a real person may type or hear:

- joined, spaced, and hyphenated forms
- singular and plural
- likely suffixes such as `-cli`, `-sdk`, `-app`, or `-labs`
- one-character insertions, deletions, substitutions, or transpositions
- likely keyboard errors
- homophones and spoken spellings
- transliteration alternatives

Do not create dozens of theoretical variants. Prioritize plausible user behavior.

## 5. Collision taxonomy

### Critical namespace collision

The exact required package, command, app listing, module path, or other essential surface is occupied.

Ask whether a scoped package or alternate slug is acceptable. Do not hide the adoption cost of a workaround.

### Same-category collision

An active project or company uses the same or a confusingly close name for a similar job or audience.

This is normally more serious than an unrelated surname or dictionary result.

### Search domination

A major company, celebrity, place, medicine, protocol, or common word controls the exact query.

A technically unused package name can still be a poor brand when search ownership is unrealistic.

### Orthographic collision

The candidate is visually confusable with another entity through one missing vowel, transposed letters, `rn` versus `m`, `l` versus `I`, or punctuation-only differences.

### Phonetic collision

The candidate sounds like another product or common word. This matters for podcasts, word of mouth, talks, voice input, and customer support.

### Semantic or cultural collision

The name has a dominant meaning, slang use, political association, medical use, or cultural implication that conflicts with the project.

### Preliminary legal concern

A relevant active mark or established commercial use appears in the target territory and product class.

This is a risk signal, not legal advice.

## 6. Risk labels

### Green

Use only when the checks performed found:

- no obvious active same-category exact collision
- workable critical namespaces that were checked
- no dominant conflicting entity
- no obvious target-language problem

Recommended wording:

> Green in the checks performed on YYYY-MM-DD; no obvious active same-category exact collision was found. This is not trademark clearance.

### Yellow

Use for:

- unrelated exact entities
- old or weak projects
- a non-critical occupied namespace
- close spellings or phonetic neighbors
- ambiguous language associations
- incomplete evidence

Explain the workaround and its cost.

### Red

Use for:

- active same-category exact or confusingly close product
- blocked critical namespace
- dominant conflicting entity
- serious target-language issue
- strong preliminary trademark concern

### Unverified

Use when a required source could not be checked. Never silently treat unknown as green.

## 7. Naming difficulty

### Low

- distinctive exact query
- easy spelling and pronunciation
- few meaningful collisions
- critical checked namespaces workable

### Medium

- some ambiguity or unrelated exact entities
- one manageable workaround
- minor spelling or language friction

### High

- generic query
- search dominated by another entity
- several occupied namespaces
- confusing pronunciation or normalization
- serious same-category or legal risk

## 8. Evidence quality

### High confidence

- official registry or database
- exact result page inspected
- current date recorded
- category relevance checked
- more than one independent source agrees

### Medium confidence

- strong web evidence but not every critical source
- registry result exists but activity or relevance is uncertain
- dictionary meaning verified but native usage is limited

### Low confidence

- search snippets only
- third-party availability checker
- one search engine
- model memory without external verification

For each finalist record query, source, date, exact/near status, category relevance, activity signal, and confidence.

## 9. Cross-language research

For a non-English or invented candidate:

1. identify original script and dictionary form
2. verify literal meaning with a reputable dictionary
3. inspect modern native-language use
4. confirm part of speech or inflection
5. use a standard romanization
6. search both original script and romanized form
7. search slang, medicine, company, surname, and place associations when relevant
8. explain whether the candidate is direct, clipped, derived, or merely root-inspired

Never invent an etymology to rescue a preferred sound.

## 10. Domain and handle checks

Check domains and handles only when they matter to the launch plan.

- Do not let `.com` availability become the sole criterion for an open-source developer tool.
- Check whether a practical alternative creates confusion or spelling debt.
- Record the date because status changes quickly.
- Do not claim reservation until the user has actually registered the asset.

## 11. Preliminary trademark screening

For commercial or high-risk projects, inspect:

- WIPO Global Brand Database
- appropriate national or regional registers such as USPTO, EUIPO/TMview, UKIPO, CNIPA, or J-PlatPat
- relevant goods and services classes
- exact and confusingly similar marks
- owner, status, territory, and category

State:

> This is a preliminary naming-risk screen, not legal advice or trademark clearance.

Do not state that no trademark exists merely because a quick search found none.

## 12. SEO and GEO research

Evaluate discoverability through actual query behavior:

```text
Brand
Brand category
Brand GitHub
Brand product type
Brand primary capability
```

Look for:

- exact-query domination
- stable canonical spelling
- ambiguity with major entities
- category-descriptor clarity
- consistency opportunities across README, package metadata, docs, and website

A strong name makes the entity distinguishable. A strong descriptor makes the product understandable. Neither guarantees ranking.

