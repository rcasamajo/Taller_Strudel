### Taller introducció al live coding amb Strudel

- Presentació

- Què és el live coding

[https://blog.toplap.org/about/](https://blog.toplap.org/about/)

- Qui som TOPLAP Barcelona

[https://toplap.cat/](https://toplap.cat/)

[https://social.toplap.org/@toplap_bcn](https://social.toplap.org/@toplap_bcn)

[https://www.instagram.com/toplap_bcn/](https://www.instagram.com/toplap_bcn/)

[https://www.youtube.com/c/TOPLAPBARCELONA](https://www.youtube.com/c/TOPLAPBARCELONA)

- Eina/Llenguatge que usarem avui: Strudel

[https://strudel.cc/](https://strudel.cc/)

- Documentació oficial

[https://strudel.cc/workshop/getting-started/](https://strudel.cc/workshop/getting-started/)

# Introducció

[https://strudel.cc/workshop/getting-started/](https://strudel.cc/workshop/getting-started/)

- Què és Strudel?

- Entorn, primer so

[https://strudel.cc/workshop/first-sounds/](https://strudel.cc/workshop/first-sounds/)

- Samples, operador “:” o “n”, bank (drum sounds) => Notació JS usant el “.”

- Tempo: cicles, cps, cpm

- Mininotation (notació per definir patrons): coma, corchete, multi, silenci (~), <>

- Ajuda visual: punchcard() o _punchcard()

[https://strudel.cc/learn/visual-feedback/#visual-feedback](https://strudel.cc/learn/visual-feedback/#visual-feedback)

# Melodies (notes)

[https://strudel.cc/workshop/first-notes/](https://strudel.cc/workshop/first-notes/)

- Notes: nota amb piano (notes midi o notació int.)

- Veure exemples de la doc

[https://strudel.cc/workshop/first-notes/#longer-sequences](https://strudel.cc/workshop/first-notes/#longer-sequences)

- Escales

[https://strudel.cc/workshop/first-notes/#scales](https://strudel.cc/workshop/first-notes/#scales)

- Executar més d’una instrucció a la vegada: “$:”

- Parar una instrucció: hush() o “_$:”

- Comentaris: //  o  /* … */

- Més operadors: ! @ /

[https://strudel.cc/workshop/first-notes/#recap](https://strudel.cc/workshop/first-notes/#recap)

# Efectes

[https://strudel.cc/workshop/first-effects/](https://strudel.cc/workshop/first-effects/)

- Veure exemples i com combinar-los usant notació JS

- Tots els efectes d'àudio:

[https://strudel.cc/learn/effects/](https://strudel.cc/learn/effects/)

# Sintetitzadors

[https://strudel.cc/learn/synths/](https://strudel.cc/learn/synths/)

- Provar diferents sintes

- Visualitzador de la ona de so: scope() / _scope()

# Modulació amb senyals

[https://strudel.cc/workshop/first-effects/#modulation-with-signals](https://strudel.cc/workshop/first-effects/#modulation-with-signals)

- sine, rand, …

- range

# Altres efectes i modificadors

- Modificació de patrons: [https://strudel.cc/workshop/pattern-effects/](https://strudel.cc/workshop/pattern-effects/)

- Modificació de temps: [https://strudel.cc/learn/time-modifiers/](https://strudel.cc/learn/time-modifiers/)

- Aleatorietat: https://strudel.cc/learn/random-modifiers/

# Miscel·lània

- Cada vegada que executem el codi es crea un “pattern” que podem **compartir** (privat amb la URL o públic amb l'opció “Share” del REPL”.

- A la secció “**patterns**” tenim els nostres patrons a “user” i els compartits públicament a “community”.

- L’aplicació també funciona “**offline**” perquè es descarrega la primera vegada que la usem (les mostres usades també els tindrem disponibles “offline”).

- Podem carregar a l’aplicació **mostres de so** des d’un repositori públic o des del mateix dispositiu local: [https://strudel.cc/learn/samples/](https://strudel.cc/learn/samples/)
