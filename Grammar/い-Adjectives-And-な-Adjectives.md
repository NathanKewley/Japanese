# い-Adjectives And な-Adjectives

Japanese has 3 types of Adjectives.

* `い-Adjectives`
* `な-Adjectives`
* `Exceptions` -- Of Course 🙃

## い-Adjectives

`い-Adjectives` are Adjectives as the name suggests always end with `い`. However NOT ALL adjectives that end in `い` are `い-Adjectives`.

The general rule to identify if an adjective ending in `い` is an `い-Adjectives` is to check the Kanji the word is written with. A `い-Adjective` will either have `い` or `しい` appended with `hiragana` to the end of the Kanji.

Some examples of `い-Adjectives`:

| Adjective With Kanji | Reading    | Notes                                                                                                                                   |
| -------------------- | ---------- | --------------------------------------------------------------------------------------------------------------------------------------- |
| 暑い 　　　　　　　　　| あつい     | Has `い` appended to the Kanji makup of the word so is a `い-Adjectives` |
| 難しい                | むずかしい | Has `しい` appended to the Kanji makup of the word so is a `い-Adjectives` |
| 美味しい              | おいしい   | おいしい is almost always writted with Hiragana, but the Kanji version of the word is still relevant when identifying the adjective type |

If the adjective ends in `えい` than it is NEVER an `い` adjective and always a `な-Adjective`. (きれい for exmaple)

If an Adjective is not an `い-Adjective` it is almost deffiantly an `な-Adjective` (barring the `exceptions` later in this page 🙃)

## な-Adjectives

In Short if an Adjective is not an `い-Adjective` or one of the `exceptions` it is a `な-Adjective`.

However there are ways to identiy a `な-Adjective` directly:

* Loan Words - These are almost always `な-Adjectives` even when ending with `イ`. You can identify these easily as they will be written with Katakana.
* Any adjectives that end in `えい` are always `な-Adjectives`
* An Adjective that ends in `い` but the ending `い` is part of the Kanji makeup of the word are also `な-Adjectives`

Some examples of `な-Adjectives`:

| Adjective With Kanji | Reading    | Notes                                                                                                                                   |
| -------------------- | ---------- | --------------------------------------------------------------------------------------------------------------------------------------- |
| ドライ 　　　　　　　　| ドライ      | ドライ (dry) is a loan work from english written with Katakana |
| 有名                 | ゆうめい    | End with an `い` Sound but the `い` sound is part of the Kanji makeup of the word and not appended as Hiragana |
| きれい               | きれい      | きれい ends in `えい` |

## Exceptions

Of course there are some special exemptions to the rules 🙃

### Exception いい

`いい` (`いいです`) is an exception to the rules. `いい` is generally treated as an `い-Adjective` but is conjugated differently in many cases.

## Visual Explanation

```mermaid
---
title: Adjective Types
---
flowchart TD;
    classDef question stroke:#f00

    Start[Start] --> Except(Is the word いい?)
    IsIt:::question(Is it a loan Word)
    NotLoan:::question(Ends With)
    KanjiEnds:::question(Is the い part of the words Kanji or appended as Hiragana)

    い-Adjective[い-Adjective]
    な-Adjective[な-Adjective]
    Exception[Exception]

    Except -->|Yes| Exception
    Except -->|No| IsIt
    IsIt -->|Yes| な-Adjective
    IsIt -->|No| NotLoan
    NotLoan -->|えい| な-Adjective
    NotLoan -->|い| KanjiEnds
    NotLoan -->|しい| KanjiEnds
    KanjiEnds -->|Kanji| な-Adjective
    KanjiEnds -->|Hiragana| い-Adjective
```
