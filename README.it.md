# copywriting

🌐 [English](README.md) | [Español](README.es.md) | [Français](README.fr.md) | [Italiano](README.it.md) | [Português](README.pt.md) | [Deutsch](README.de.md)

Uno skill Claude Code che ti aiuta a scrivere copy che non si può copiare — titoli, slogan, hook, proposte di valore, annunci, landing page e newsletter — con un metodo concreto, verificabile e inimitabile.

## Skill complementare

- [tone-of-voice](https://github.com/entpnomad/tone-of-voice) — definisce *con quale voce* parla il copy.

Questo skill costruisce la frase; tone-of-voice fa sì che suoni come te. Due lavori: copywriting è l'argomento e il mestiere, tone-of-voice è l'identità. Scrivi il copy qui, poi passalo per tone-of-voice.

## Perché

Quasi tutti i consigli sul copywriting sono o psicologia da imbonitore o la pappa vaga del "scrivi contenuti accattivanti". Nessuno dei due ti aiuta a trasformare una pagina bianca in una frase che colpisce. Questo skill è il mestiere della comunicazione semplice, distillato dai framework di [Harry Dry](https://marketingexamples.com): fai in modo che ogni frase sia qualcosa che puoi *visualizzare*, *verificare*, e che *nessun altro potrebbe firmare*.

## Il test centrale

Per ogni frase che deve reggere del peso, fatti tre domande:

1. **Posso visualizzarla?** — "worn by supermodels in London and dads in Ohio"
2. **Posso verificarla?** — "reads on the tube", non "intelligent"
3. **Nessun altro può dirla?** — non scrivere mai un annuncio che un concorrente possa firmare

Tre no, hai scritto spazzatura. Tre sì, sei sulla strada giusta.

## Cosa contiene

- Il test delle 3 frasi e il test dei 2 secondi
- Concreto > astratto: l'esercizio dello zoom ("regain fitness" → "Couch to 5K")
- Copy verificabile: indica, non parlare — fatti invece di aggettivi
- Il processo a chi → cosa → come (dall'atteggiamento attuale a quello desiderato)
- Il conflitto come motore (approcci / convinzioni / concorrenti)
- Posizionamento: cosa sostituisci, cosa puoi fare che nessun altro
- Riscrivere fino al semplice: tagliare ogni parola che non lavora, il test del paragrafo, scrivere versioni
- Copy e design come una cosa sola — scrivi nel mezzo
- Il mestiere della newsletter, e un esempio di riscrittura

## Installazione

```bash
mkdir -p ~/.claude/skills/copywriting
curl -sL https://raw.githubusercontent.com/entpnomad/copywriting/main/SKILL.md \
  -o ~/.claude/skills/copywriting/SKILL.md
```

## Uso

Chiedi a Claude di scrivere o criticare qualsiasi copy di marketing — un titolo, uno slogan, una landing page, un annuncio, una newsletter — e lo skill applica il metodo. Prova:

```
scrivi un titolo per [prodotto]
questo slogan è piatto, affilalo
critica questo copy di landing page
```

## Crediti

Framework di Harry Dry (Marketing Examples) su *How I Write* di David Perell:
https://www.youtube.com/watch?v=TUMjnmfsPeM

## Licenza

MIT
