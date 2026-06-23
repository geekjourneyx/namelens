# Naming Patterns and Linguistic Playbook

Use this reference when generating candidates or evaluating pronunciation, cross-language meaning, and metaphor quality.

## 1. Candidate quality model

A useful project name balances:

```text
meaning × transmission × distinctiveness × platform fit × future range
```

A name can be semantically elegant and still fail because nobody can spell it. A familiar name can be easy to understand and still fail because the exact query is impossible to own.

## 2. Independent naming lanes

### Clear compound

Combine two familiar concepts with a natural relationship.

Examples of structures:

- outcome + object
- process + place
- signal + tool
- source + motion

Strengths: easy initial comprehension and good descriptor potential.

Risks: generic compounds are crowded; avoid simply joining two category keywords.

### Suggestive real word

Use a real word that evokes the experience or result without describing the entire product.

Good fields include:

- discovery: trace, trail, clue, beacon, lens, probe
- trust: anchor, proof, witness, origin, source
- aggregation: weave, loom, braid, mesh, prism
- workflow: relay, bridge, gate, channel, conduit
- clarity: light, focus, signal, outline, reveal

Strengths: memorable narrative and easier explanation.

Risks: dictionary words may be dominated by existing entities or common meanings.

### Pronounceable coined construction

Create a new form from familiar sound or semantic fragments.

Good coined names usually:

- have an obvious stress pattern
- avoid dense consonant clusters
- do not depend on unusual capitalization
- can be reconstructed after hearing once
- retain enough familiar sound to feel intentional

Avoid random vowel deletion, decorative `-ly`, `-ify`, `-io`, `-ora`, or `-ai` suffixes unless they serve the product identity.

### Cross-language root

Use another language only when it creates real meaning and can be verified.

For every candidate record:

- language and original script
- dictionary form
- literal meaning
- pronunciation
- standard romanization
- modern usage
- whether the proposed name is a direct word, shortened form, or root-inspired invention

Never invent an etymology after choosing the sound.

### Concrete metaphor

Choose an object, craft, role, process, or natural phenomenon whose behavior mirrors the product.

Useful families:

- navigation: compass, path, waypoint, bridge
- visibility: lens, prism, lamp, beacon
- collection: net, basket, loom, braid
- verification: anchor, seal, witness, ledger
- motion: relay, current, stream, orbit
- exploration: scout, probe, trail, map

The metaphor should explain the product in one sentence. If it requires a mythology lecture, it is too expensive.

### Contrarian technical form

A terse, tool-like form can work for CLI and infrastructure projects.

Test it in realistic commands:

```bash
name search "query"
name scan ./src
name init
```

A short command that is generic, visually noisy, or impossible to search is not an improvement.

### Myth and literature

Use only when:

- the character, object, or story has a meaningful product mapping
- the name is not already saturated in software
- pronunciation works in target markets
- the story does not create unwanted moral or cultural baggage

Famous software-saturated names deserve an initial penalty: Atlas, Apollo, Athena, Hermes, Loki, Odin, Thor, Prometheus, Phoenix, Titan, Oracle, and Nexus.

## 3. Linguistic exploration seeds

These are semantic starting points, not pre-cleared names. Reverify every actual candidate.

### Latin fields

- light and clarity: `lumen`, `lux`
- trace and evidence: `vestigium`, `signum`
- source and origin: `fons`, `origo`
- key and access: `clavis`
- road and route: `via`, `iter`
- inquiry: roots related to `quaerere`

Common risks: inflected forms, variable pronunciation, and heavy software saturation.

### Greek fields

- sign or signal: roots related to `sēma`
- seeing or examining: roots related to `skopein`
- road or method: `hodos`
- mind or understanding: `nous`, `noesis`
- memory: `mnēmē`

Common risks: academic tone, transliteration variants, and famous-root saturation.

### Japanese fields

- 探す (`sagasu`): to look for
- 探索 (`tansaku`): search or exploration
- 調べる (`shiraberu`): to investigate or look up
- 見つける (`mitsukeru`): to find
- 灯り (`akari`): light or illumination
- 道 (`michi`): road or way
- 鍵 (`kagi`): key

Verify whether a form is natural as a noun or brand. Do not clip a Japanese word and claim the original meaning survives automatically.

A cautionary example:

- `tansaku` commonly corresponds to 探索, exploration/search.
- `tanso` commonly corresponds to 炭素, carbon.

Therefore `Tanso` must not be presented as a direct Japanese translation of “exploration.” At most it may be an invented form or another explicitly documented association.

### Other languages

Use Old Norse, Finnish, Sanskrit, Arabic, Welsh, Basque, Māori, or other languages only when reliable dictionaries and native usage can be checked. Exoticism is not a naming strategy.

## 4. Transmission tests

### Read-once pronunciation

Show the name without explanation. Ask what pronunciation a target user would infer.

### Hear-once spelling

Imagine hearing it in a podcast. List the two or three spellings a listener might type.

### Command test

Place it in three realistic shell commands. Check rhythm, ambiguity, typos, and collisions with common system commands.

### Support-conversation test

Say:

> Install ___, then run ___ init.

If the listener immediately asks for spelling, the name carries a recurring transmission tax.

### Search reconstruction test

Ask what a user would search a week later. Strong names preserve a stable query such as:

```text
Brand
Brand CLI
Brand category
Brand GitHub
```

### Three-year test

Check whether the name still works after new sources, platforms, models, or product lines are added.

## 5. Common failure modes

- direct category nouns such as `Searcher`, `Finder`, or `Manager`
- generic `omni`, `meta`, `super`, or `universal` constructions in crowded categories
- trendy suffix mutations with no semantic role
- names that require capitalization to be understood
- one-letter spelling distinctions from a strong competitor
- famous mythology chosen only for grandeur
- a foreign-language story that native speakers will immediately dispute
- names tied to one provider when the product is meant to aggregate many
- stuffing `AI`, `search`, `cloud`, or `agent` into the brand instead of the descriptor

## 6. Brand and descriptor pairing

The brand creates a distinct entity. The descriptor explains the category.

```text
[Brand] — [category] for [audience or outcome]
```

Examples of descriptor structures:

- AI search CLI for Chinese internet research
- local-first screenshot deduplication tool
- podcast shadowing app for language learners
- source-aware research gateway for agents

Keep the descriptor factual, current, and consistent across repository About text, README, package metadata, documentation, and website.

