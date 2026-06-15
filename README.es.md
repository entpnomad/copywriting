# copywriting

🌐 [English](README.md) | [Español](README.es.md) | [Français](README.fr.md) | [Italiano](README.it.md) | [Português](README.pt.md) | [Deutsch](README.de.md)

Un skill de Claude Code que te ayuda a escribir copy que no se puede copiar — titulares, eslóganes, ganchos, propuestas de valor, anuncios, landing pages y newsletters — con un método concreto, verificable e irrepetible.

## Skill complementario

- [tone-of-voice](https://github.com/entpnomad/tone-of-voice) — define *con qué voz* habla el copy.

Este skill construye la línea; tone-of-voice hace que suene a ti. Dos trabajos: copywriting es el argumento y el oficio, tone-of-voice es la identidad. Escribe el copy aquí y luego pásalo por tone-of-voice.

## Por qué

Casi todo el consejo sobre copywriting es o psicología de vendehúmos o la papilla vaga de "escribe contenido atractivo". Ninguno te ayuda a convertir una página en blanco en una línea que aterrice. Este skill es el oficio de la comunicación simple, destilado de los frameworks de [Harry Dry](https://marketingexamples.com): haz que cada línea sea algo que puedas *visualizar*, *verificar* y que *nadie más pueda firmar*.

## El test central

Para cualquier línea que tenga que cargar peso, hazte tres preguntas:

1. **¿Puedo visualizarlo?** — "worn by supermodels in London and dads in Ohio"
2. **¿Puedo verificarlo?** — "reads on the tube", no "intelligent"
3. **¿Nadie más puede decirlo?** — nunca escribas un anuncio que un competidor pueda firmar

Tres noes, escribiste basura. Tres síes, vas por buen camino.

## Qué contiene

- El test de 3 líneas y el test de 2 segundos
- Concreto > abstracto: el ejercicio de zoom ("regain fitness" → "Couch to 5K")
- Copy verificable: señala, no hables — hechos en vez de adjetivos
- El proceso a quién → qué → cómo (de la actitud actual a la deseada)
- El conflicto como motor (enfoques / creencias / competidores)
- Posicionamiento: a qué reemplazas, qué puedes hacer que nadie más
- Reescribir hasta lo simple: cortar toda palabra que no trabaja, el test del párrafo, escribir versiones
- Copy y diseño como una sola cosa — escribe en el medio
- Oficio del newsletter, y un ejemplo de reescritura

## Instalación

```bash
mkdir -p ~/.claude/skills/copywriting
curl -sL https://raw.githubusercontent.com/entpnomad/copywriting/main/SKILL.md \
  -o ~/.claude/skills/copywriting/SKILL.md
```

## Uso

Pídele a Claude que escriba o critique cualquier copy de marketing — un titular, un eslogan, una landing page, un anuncio, un newsletter — y el skill aplica el método. Prueba:

```
escribe un titular para [producto]
este eslogan suena plano, afílalo
critica este copy de landing page
```

## Crédito

Frameworks de Harry Dry (Marketing Examples) en *How I Write* de David Perell:
https://www.youtube.com/watch?v=TUMjnmfsPeM

## Licencia

MIT
