# Taller introducció al live coding amb Strudel

- Presentació

&emsp; &emsp; [Júlia Múgica](https://www.instagram.com/jujmg/)

&emsp; &emsp; [Ramon Casamajó](https://www.instagram.com/rcasamajo/) - [callitanything.org](http://callitanything.org/)


- Què és el live coding

&emsp; &emsp; [blog.toplap.org/about/](https://blog.toplap.org/about/)

- Qui som TOPLAP Barcelona

&emsp; &emsp; [toplap.cat/](https://toplap.cat/)

&emsp; &emsp; [social.toplap.org/@toplap_bcn](https://social.toplap.org/@toplap_bcn)

&emsp; &emsp; [www.instagram.com/toplap_bcn/](https://www.instagram.com/toplap_bcn/)

&emsp; &emsp; [www.youtube.com/c/TOPLAPBARCELONA](https://www.youtube.com/c/TOPLAPBARCELONA)

- Eina/Llenguatge que usarem avui: Strudel

&emsp; &emsp; [strudel.cc/](https://strudel.cc/)

- Documentació oficial

&emsp; &emsp; [strudel.cc/workshop/getting-started/](https://strudel.cc/workshop/getting-started/)

<br />


# Introducció

&emsp; &emsp; [strudel.cc/workshop/getting-started/](https://strudel.cc/workshop/getting-started/)

- Què és Strudel?

- Entorn, primer so

&emsp; &emsp; [strudel.cc/workshop/first-sounds/](https://strudel.cc/workshop/first-sounds/)

- Samples, operador “:” o “n”, bank (drum sounds) => Notació JS usant el “.”

- Tempo: cicles, cps, cpm

- Mininotation (notació per definir patrons): coma, corchete, multi, silenci (~), <>

- Ajuda visual: punchcard() o _punchcard()

&emsp; &emsp; [strudel.cc/learn/visual-feedback/#visual-feedback](https://strudel.cc/learn/visual-feedback/#visual-feedback)

<br />


# Melodies (notes)

&emsp; &emsp; [strudel.cc/workshop/first-notes/](https://strudel.cc/workshop/first-notes/)

- Notes: nota amb piano (notes midi o notació int.)

- Veure exemples de la doc

&emsp; &emsp; [strudel.cc/workshop/first-notes/#longer-sequences](https://strudel.cc/workshop/first-notes/#longer-sequences)

- Escales

&emsp; &emsp; [strudel.cc/workshop/first-notes/#scales](https://strudel.cc/workshop/first-notes/#scales)

- Executar més d’una instrucció a la vegada: “$:”

- Parar una instrucció: hush() o “_$:”

- Comentaris: //  o  /* … */

- Més operadors: ! @ /

&emsp; &emsp; [strudel.cc/workshop/first-notes/#recap](https://strudel.cc/workshop/first-notes/#recap)

<br />


# Efectes

&emsp; &emsp; [strudel.cc/workshop/first-effects/](https://strudel.cc/workshop/first-effects/)

- Veure exemples i com combinar-los usant notació JS

- Tots els efectes d'àudio:

&emsp; &emsp; [strudel.cc/learn/effects/](https://strudel.cc/learn/effects/)

<br />


# Sintetitzadors

&emsp; &emsp; [strudel.cc/learn/synths/](https://strudel.cc/learn/synths/)

- Provar diferents sintes

- Visualitzador de la ona de so: scope() / _scope()

<br />


# Modulació amb senyals

&emsp; &emsp; [strudel.cc/workshop/first-effects/#modulation-with-signals](https://strudel.cc/workshop/first-effects/#modulation-with-signals)

- sine, rand, …

- range

<br />


# Altres efectes i modificadors

- Modificació de patrons: [strudel.cc/workshop/pattern-effects/](https://strudel.cc/workshop/pattern-effects/)

- Modificació de temps: [strudel.cc/learn/time-modifiers/](https://strudel.cc/learn/time-modifiers/)

- Aleatorietat: [strudel.cc/learn/random-modifiers/](https://strudel.cc/learn/random-modifiers/)

<br />


# Miscel·lània

- Cada vegada que executem el codi es crea un “pattern” que podem **compartir** (privat amb la URL o públic amb l'opció “Share” del REPL”.

- A la secció “**patterns**” tenim els nostres patrons a “user” i els compartits públicament a “community”.

- L’aplicació també funciona “**offline**” perquè es descarrega la primera vegada que la usem (les mostres usades també els tindrem disponibles “offline”).

- Podem carregar a l’aplicació **mostres de so** des d’un repositori públic o des del mateix dispositiu local: [strudel.cc/learn/samples/](https://strudel.cc/learn/samples/)
