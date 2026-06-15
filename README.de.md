# copywriting

🌐 [English](README.md) | [Español](README.es.md) | [Français](README.fr.md) | [Italiano](README.it.md) | [Português](README.pt.md) | [Deutsch](README.de.md)

Ein Claude Code Skill, der dir hilft, Copy zu schreiben, die niemand kopieren kann — Headlines, Slogans, Hooks, Wertversprechen, Anzeigen, Landing Pages und Newsletter — mit einer konkreten, ueberpruefbaren und unverwechselbaren Methode.

## Begleit-Skill

- [tone-of-voice](https://github.com/entpnomad/tone-of-voice) — bestimmt, *mit welcher Stimme* die Copy spricht.

Dieser Skill baut den Satz; tone-of-voice sorgt dafuer, dass er nach dir klingt. Zwei Aufgaben: Copywriting ist das Argument und das Handwerk, tone-of-voice ist die Identitaet. Schreib die Copy hier und schick sie dann durch tone-of-voice.

## Warum

Die meisten Copywriting-Ratschlaege sind entweder Schausteller-Psychologie oder der vage Brei von "schreib fesselnde Inhalte". Keiner davon hilft dir, eine leere Seite in einen Satz zu verwandeln, der sitzt. Dieser Skill ist das Handwerk der einfachen Kommunikation, destilliert aus den Frameworks von [Harry Dry](https://marketingexamples.com): mach jeden Satz zu etwas, das du *visualisieren* und *ueberpruefen* kannst und das *niemand sonst unterschreiben* koennte.

## Der zentrale Test

Bei jedem Satz, der Gewicht tragen muss, stell dir drei Fragen:

1. **Kann ich es visualisieren?** — "worn by supermodels in London and dads in Ohio"
2. **Kann ich es ueberpruefen?** — "reads on the tube", nicht "intelligent"
3. **Kann es sonst niemand sagen?** — schreib nie eine Anzeige, die ein Konkurrent unterschreiben koennte

Drei Nein, du hast Mist geschrieben. Drei Ja, du bist auf etwas gestossen.

## Was drin ist

- Der 3-Satz-Test und der 2-Sekunden-Test ("One Mississippi")
- Konkret > abstrakt: die Zoom-Uebung ("regain fitness" → "Couch to 5K")
- Ueberpruefbare Copy: zeig, statt zu reden — Fakten statt Adjektive
- Der Prozess wer → was → wie (von der aktuellen zur gewuenschten Haltung)
- Konflikt als Motor (Ansaetze / Ueberzeugungen / Konkurrenten)
- Positionierung: was ersetzt du, was kannst du, das sonst niemand kann
- Umschreiben bis zum Einfachen: Kaplans Gesetz der Worte, der Absatz-Test, Versionen schreiben
- Copy und Design als eins — schreib im Medium
- Newsletter-Handwerk, und ein vollstaendiges Beispiel mit 25 Umschreibungen

## Installation

```bash
mkdir -p ~/.claude/skills/copywriting
curl -sL https://raw.githubusercontent.com/entpnomad/copywriting/main/SKILL.md \
  -o ~/.claude/skills/copywriting/SKILL.md
```

## Verwendung

Bitte Claude, eine beliebige Marketing-Copy zu schreiben oder zu kritisieren — eine Headline, einen Slogan, eine Landing Page, eine Anzeige, einen Newsletter — und der Skill wendet die Methode an. Probier:

```
schreib eine Headline fuer [Produkt]
dieser Slogan ist flach, schaerf ihn
kritisiere diese Landing-Page-Copy
```

## Credit

Frameworks von Harry Dry (Marketing Examples) bei David Perells *How I Write*:
https://www.youtube.com/watch?v=TUMjnmfsPeM

## Lizenz

MIT
