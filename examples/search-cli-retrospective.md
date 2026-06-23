# Search CLI Naming Retrospective

This example captures reusable lessons from a naming path that moved through `Quaero`, `Findo`, `Searcher`, and `Tanso` for a Chinese internet search CLI.

## Project brief

The first release would aggregate domestic information sources such as Bocha, Volcengine, and Zhihu for:

- web search
- model answers with citations
- Zhihu search, direct answers, and hot lists
- structured CLI and agent workflows

The project needed:

- a memorable GitHub identity
- a natural CLI command
- room to expand beyond the first three providers
- strong `brand + category` discoverability
- credible cross-language meaning

## Quaero: elegant meaning, high transmission tax

`Quaero` has a relevant Latin association with seeking or inquiry. Its problem was not semantic quality but transmission quality.

Likely friction:

- readers may not know how to pronounce it
- listeners may not know whether to spell `quae`, `que`, or another form
- every recommendation may require a spelling lesson
- a CLI command is typed repeatedly, multiplying that cost

Lesson:

> Etymological elegance is not the same as word-of-mouth usability.

## Findo: instant comprehension, weak search ownership

`Findo` feels easy because it resembles the familiar verb `find`. That helps first-use comprehension.

But the same familiarity creates risk:

- the root is extremely common in search products
- the `-o` mutation is common in startup naming
- exact and near collisions are likely
- users may remember “some find tool” rather than the entity
- repository, package, app, and domain collisions become more probable

Lesson:

> Familiarity helps comprehension until it destroys distinctiveness.

## Searcher: descriptor mistaken for brand

`Searcher` describes the category but barely creates an entity.

Typical problems:

- generic exact query
- countless repositories, classes, and tools use it
- weak spoken recall
- likely need for modifiers such as `searcher-cli`
- little narrative or expansion room

Lesson:

> A word that explains the function is not automatically a name users can rediscover.

Use a distinctive brand plus an explicit descriptor instead:

```text
[Brand] — AI search CLI for Chinese internet research
```

## Tanso: strong shape, incorrect linguistic story

`Tanso` has useful formal properties:

- five letters
- two simple syllables for many users
- natural lowercase command form
- more distinctive than `Searcher`

The earlier reasoning, however, incorrectly treated it as Japanese for exploration or as a harmless shortening of `tansaku`.

The linguistic correction is crucial:

- 探索 is ordinarily romanized `tansaku` and means search or exploration.
- `tanso` commonly corresponds to 炭素, meaning carbon.

Therefore it must not be marketed as a direct Japanese translation of exploration. It may still be researched as an invented form or another accurately documented association, but carbon, materials, industrial, scientific, and company collisions become part of the search scope.

Lesson:

> A beautiful false etymology creates credibility debt. Verify the word first; write the story second.

## The deeper decision model

The process improved when it stopped asking only “Which word sounds cool?” and asked:

1. What must the name signal?
2. What must it avoid?
3. Which namespace is truly critical?
4. How will people rediscover it one week later?
5. Can it stretch beyond the first release?

For this project, the likely priority order was:

1. CLI command
2. GitHub repository
3. Go module path
4. exact web query
5. future distribution surfaces

A domain could be useful without being a launch blocker.

## Reusable conclusion

The ideal candidate is not necessarily the most literal or exotic. It is the name that best balances:

```text
clear positioning
+ easy transmission
+ search distinctiveness
+ critical namespace fit
+ future range
```

The final report should use live evidence, identify the cost of every workaround, and choose one winner with a backup rather than hiding behind a long unranked list.

