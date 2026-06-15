# copywriting

🌐 [English](README.md) | [Español](README.es.md) | [Français](README.fr.md) | [Italiano](README.it.md) | [Português](README.pt.md) | [Deutsch](README.de.md)

A Claude Code skill that helps you write copy that can't be copied — headlines, taglines, hooks, value propositions, ad copy, landing pages, and newsletters — using a concrete, falsifiable, ownable method.

## Companion Skill

- [tone-of-voice](https://github.com/entpnomad/tone-of-voice) — enforces *whose voice* the copy speaks in.

This skill builds the line; tone-of-voice makes it sound like you. Two jobs: copywriting is the argument and the craft, tone-of-voice is the identity. Write the copy here, then run it through tone-of-voice.

## Why

Most copywriting advice is either huckster psychology-gaming or vague "write compelling content" mush. Neither helps you turn a blank page into a line that lands. This skill is the craft of simple communication, distilled from [Harry Dry's](https://marketingexamples.com) frameworks: make every line something you can *visualize*, *falsify*, and that *nobody else could sign*.

## The core test

For any line that has to carry weight, ask three questions:

1. **Can I visualize it?** — "worn by supermodels in London and dads in Ohio"
2. **Can I falsify it?** — "reads on the tube," not "intelligent"
3. **Can nobody else say it?** — never write an ad a competitor can sign

Three nos, you've written rubbish. Three yeses, you're onto something.

## What's inside

- The 3-line test and the 2-second test
- Concrete > abstract: the zoom-in drill ("regain fitness" → "Couch to 5K")
- Falsifiable copy: point, don't talk — facts over adjectives
- The who → what → how process (current attitude to desired attitude)
- Conflict as the engine (approaches / beliefs / competitors)
- Positioning: what do you replace, what can nobody else do
- Rewrite-to-simple: cut every word that isn't working, the paragraph test, writing versions
- Copy and design as one thing — write in the medium
- Newsletter craft, and a worked rewrite example

## Install

```bash
mkdir -p ~/.claude/skills/copywriting
curl -sL https://raw.githubusercontent.com/entpnomad/copywriting/main/SKILL.md \
  -o ~/.claude/skills/copywriting/SKILL.md
```

## Use

Ask Claude to write or critique any marketing copy — a headline, a tagline, a landing page, an ad, a newsletter — and the skill applies the method. Try:

```
write a headline for [product]
this tagline feels flat, sharpen it
critique this landing page copy
```

## Credit

Frameworks from Harry Dry (Marketing Examples) on David Perell's *How I Write*:
https://www.youtube.com/watch?v=TUMjnmfsPeM

## License

MIT
