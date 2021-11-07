---
layout: page
title: Teoria del so
permalink: /teoria/
---

# Teoria del so

## Introducció
El so és la percepció del cervell d’una vibració que es transmet mitjançant un determinat medi com l’aire, aigua, un fil, etc.

La vibració de l’aire descriu un moviment ondulatori que es caracteritza per unes magnituds físiques: freqüència, amplitud, longitud d’ona, etc.

![Representació del so](resources/unitat1/imatge1.png)

Aquestes magnituds físiques permeten definir les qualitats del so: diferents tons, timbres i duració dels sons.


![Qualitats dels sons](../imatges/imatge2.png)

## Magnituds físiques del so
Les principals magnituds físiques que permeten diferenciar i classificar les ones sonores són: l’amplitud, la longitud d’ona, la freqüència i el període.

![Qualitats físiques dels sons](../imatges/imatge3.png)


* **L’amplitud**: és la distància entre el punt més alt de l’ona fins la base (o línia d’equilibri).

![Exemple amplitud sons](../imatges/imatge4.png)
* **La longitud d’ona**: és la distància entre dos crestes o dos valls.

![Diferents longituds d'ona](../imatges/imatge5.png)

* **La freqüència**: és la quantitat de vegades que es produeix la vibració per cada segon. Es mesura en Herz (Hz) que és una vibració per segon.

    Com més freqüència (més vibracions) tinga un so més agut és mentre que com menys freqüència tinga és més greu.

    ![Freqüència del so](../imatges/imatge6.png)

    Els humans escoltem freqüències que van des dels 20Hz fins els 20.000 Hz. La veu humana va de 1000 a 2000 Hz.

    ![L'espectre sonor](../imatges/imatge7.png)

    Les notes musicals tenen la següent freqüència:

    ![Freqncies notes musicals](../imatges/imatge8.png)


* **El període**: temps transcorregut entre dos punts equivalents de la ona. És la inversa de la freqüència.

## Relació entre les magnituds físiques de l’ona sonora i les qualitats del so
* **Altura**: indica si és agut o greu. Està relacionat amb la freqüència.
* **Duració**: indica el temps que es manté una ona sonora completa. Es pot diferenciar entre sons curts i llargs.

  ![Duració ona](../imatges/imatge10.png)

* **Intensitat**: és equivalent al volum. Es diferencia entre sons forts i fluixos.
* **Timbre**: qualitat que ens permet distingir dos sons d’igual freqüència i intensitat emesos per dos focus sonors diferents. Permet identificar què està sonant (un objecte, un instrument o la veu d’una persona).

    ![Relació entre les magnituds físiques i les qualitats del so](../imatges/imatge9.png)

## Digitalització del so
El so es transmet mitjançant ones analògiques que poden prendre infinits valors. En canvi, els ordinadors treballen amb informació digital, de manera que s’ha de transformar el senyal analògic a un senyal digital mitjançant un procés anomenat **digitalització del so**.

Consisteix en prendre mostres del senyal sonor (mostreig). Ho fa a intervals constants de temps (freqüència de mostreig) per mesurar la intensitat del senyal analògic i aquest valor ho expressa en binari.

![Mostreig senyal digital](../imatges/imatge11.png)

Com més vegades es mesure el senyal analògic (freqüència de mostreig alta), el so tindrà major qualitat.

![Freqüència de mostreig i qualitat del so](../imatges/imatge12.png)

Després de fer el mostreig es fa la quantificació que consisteix en assignar a cada mostra un únic valor d’eixida. Com més bits usem per representar els valors de la mostra, més valors es podran representar i més qualitat tindrà el so digital. El nombre de bits que s’usa per representar cada mostra s’anomena **resolució o mida de la mostra**.

Finalment es codifica cadascun dels valors d’eixida en llenguatge binari en un procés anomenat codificació.

El nombre de pistes que composen un so digital s’anomenen **canals**. Si consta d’un únic canal s’anomena mono i si en té dos s’anomena estèreo.


## Formats d’àudio
El format dels arxius d’àudio digital indiquen la forma en què s’emmagatzemen les dades d’un arxiu de so perquè puguen ser interpretats per un ordinador o dispositiu similar.

Es classifiquen en formats amb compressió o sense compressió. Els arxius sense compressió ocupen molt d’espai, per això, s’usen algoritmes de compressió per reduir la seua mida.

Comprimir un àudio implica reduir la mida i la forma de l’ona que conforma el senyal acústic, per la qual cosa s’ometen certs valors del seu rang de freqüència i per tant, es produeixen pèrdues.


Com es pot comprovar en l’anterior imatge, es produeixen pèrdues per estalviar espai d’emmagatzemament.
| Format | Característiques |
| :--: | :-- |
| MIDI   | No es guarden sons reals sinó ordres perquè un sintetitzador digital generen la música. Ocupen menys espais que els arxius de so real. però tenen pitjor qualitat. |
| WAV  | Conté tota la informació del so analògic per la qual cosa té molta qualitat i ocupa molt d’espai.|
| MP3 | És el format més usat en la web i es pot escoltar en la majoria dels reproductors. Realitza la compressió eliminant les freqüències que no poden percebre per l’oït humà, per la qual cosa es redueix la seua mida obtenint fitxers de gran qualitat. |
| OGG | Té un grau de compressió similar al MP3 però la qualitat de reproducció és lleugerament superior. Pot contenir àudio i vídeo. Spotify l’usa. |
| AAC | El nivell de compressió és major que l’mp3 sense quasi perdre qualitat. És el format usat per iTunes i per Youtube per enviar l’àudio en streaming. |

Per conéixer més sobre formats d'àudio pots visitar [la següent web](https://www.culturasonora.es/blog/formatos-de-audio/)
