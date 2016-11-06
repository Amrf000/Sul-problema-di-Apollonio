---
title: Sul problema di Apollonio
layout: common/singlepage
---

*Sulle rive di uno stagno, passò un satiro e La vide,*
*Reginella sempre bella, è la musica di Euclide.*
*È all'identità, il riflesso, ciò a cui diede movimento,*
*ben tre sassi egli lanciò, distribuendoli nel vento.*
*Poi dall'ombra nacque un fiore,*
*tre fu il fischio della voce.*


Prova tex {% include math/inline/for-any-real.html %}.

Prova tex {% include math/display/matrix.html %}.

Apollonio da Perga (terzo secolo a.C.) fu, assieme ad Euclide e al nostro Archimede, uno dei più grandi matematici dell'antichità. In un'opera chiamata **Tangenze**, propone un problema molto interessante:

> Dati tre cerchi tangenti a due a due, trovare un cerchio tangente a tutti e tre


<!-- figura con i tre cerchi tangenti -->

Purtroppo gli scritti originali sono persi nella storia e la soluzione data da Apollonio non è pervenuta fino a noi, ma, conosciamo il problema solo grazie ad una citazione di [Pappo](https://it.wikipedia.org/wiki/Pappo_di_Alessandria). Studierò questo problema e la sua iterazione muovendomi lungo il sentiero che l'ispirazione mi ha tracciato.

## Soluzione Euristica

Siano tre cerchi tangenti a due a due, se si espandono come le onde di tre sassi lanciati in uno stagno, c'è un instante nel quale i tre cerchi passano per lo stesso punto.
Questo punto si trova all'interno della zona detta *triangolo curvilineo*, delimitata dai tre cerchi iniziali ed è il centro del cerchio da trovare!
Infatti se ho due cerchi tangenti di raggi *R* ed *r* e voglio trovare un cerchio di raggio *ρ* tangente ai due, li espando fino a che i raggi siano *R + ρ* e *r + ρ*. Uno dei punti in comune dei nuovi cerchi può essere il centro del cerchio di raggio *ρ*.

<!-- Animazione con i tre cerchi tangenti che si espandono
     ... come tre sassi lanciati in uno stagno -->

Se esiste una soluzione del *Problema di Apollonio* (PdA), si può applicare questa espansione ai tre cerchi tangenti a due a due per trovare il cerchio richiesto.
Ma l'espansione di cui si parla non è una trasformazione del piano in se stesso, non è neanche bigettiva.
Per andare avanti userò la geometria che sembra essere la più naturale per questo argomento: la *geometria inversiva* nel piano.
Inoltre esistono due soluzione del PdA: oltre al cerchio che si trova all'interno del triangolo curvilineo ce n'è anche uno esterno che è tangente ai tre cerchi iniziali.

<!-- figura con le due soluzioni del PdA -->

# Soluzioni del Problema di Apollonio

## Introduzione alla Geometria Inversiva

## Soluzione inversiva

## Soluzione classica

## La retta proiettiva complessa

### Cerchi reali e rette

## Trasformazioni di Möbius sulla sfera

## Soluzione proiettiva

# Modello dello spazio iperbolico

## Classificazione delle matrici hermitiane

## Estensione di Poincarè

## Altri modelli dello spazio iperbolico

# Iterazione

## Iterazione naturale

## Anatema: definizione costruttiva

## Proprietà dell'Anatema

## Un altro Anatema

# Frazioni continue complesse e orosfere nello Spazio Iperbolico

