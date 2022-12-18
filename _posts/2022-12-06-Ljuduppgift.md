---
layout: post
title:  "Ljuduppgift"
tag: [musik, uppgift]
categories: [digitaltskapande]
---
___
## Introduktion - Oogway Ascends
Jag har valt att göra om ljudet i "Oogway Ascends"-scenen i **Kung Fu Panda 1**.  

### Scenen:
> <iframe width="560" height="315" src="https://www.youtube.com/embed/hYAQtEs2Img" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
  
### Låten:
> <audio controls style="width: 100%;"> <source src="/Inner_Peace.wav"> </audio>

***

<h1 style="background-color: var(--mask-bg); padding: 0.75em; border-radius: 6px;"><b>Min arbetsprocess inom FL Studio</b></h1>

När vi fick ljuduppgiften så fick jag idén om att producera något lugnt, i form av en orkester.  
Jag funderade över vilka filmer som oftast har vackra scener, och tänkte på Kung Fu Panda.  
För att få inspiration för vad jag skulle producera så tittade jag på scenen utan ljud och inbillade mig vad som skulle spelas i bakgrunden.

En orkester består oftast utav en ensemble av olika *stråkinstrument*.
I min återgivning av en full orkester så utnyttjade jag en mängd olika instrument, alla med speciella utsedda syften.  
Känslan jag strävar efter att uppnå med orkestern är svårt att översätta till ord..  
När jag skrev ackorden så siktade jag efter något ***upplyftande*** och ***glatt***, men även något ***sorgligt***. 


Ett passande ord skulle kunna vara... ***sursöt.***  
Oogways yttrar sina allra sista ord med vishet till Shifu, i förberedelse för sin avgång. Oogway överlämnar sin plikt till Shifu, som nu har i sitt ansvar att sätta stopp för Tai-Lung.
Ackorden följer därmed ett enkelt mönster som alternerar mellan dur och moll, och bryts av den sista delen för en mer majestätisk effekt då Oogway försvinner.

> ### **Exempel på instrument som användes och deras syften i min låt**
>
> - **Violin & viola** - *bra fundament, täcker ackorden samt en del av melodin*
> - **Cello** - *perfekt för en stark melodi som bygger på violinerna*
> - **Kontrabas** - *mörka samt tydliga bastoner, väldigt starkt fundament som ger det hela ett oöverträffat djup*
> - **Valthorn** - *mörka men mjuka bastoner, passar som bakgrundsljud som gör allt mer storslaget*
> - **Piccolo & flöjt & klarinett** - *mjuka, luftiga melodier som passar in i stämningen för scenen*
> - **Stämda slagverk** - *följer ackorden och gör allt mer magiskt med oregelbundna notplaceringar*
> - **Mjukt piano** - *vackert piano ljud med mycket eko och efterklang, bidrar med mycket djup och ger kompositionen volym*

# Röstinspelning
För att få ett bra ljud på rösten som passar in i scenen så använde jag ett par verktyg i FL Studio samt en AI-röstprocessor.
Det första jag gjorde var att lägga på en *noise-gate*, vilket tar bort allt ljud under en viss decibelnivå.  
Det andra var att använda en compressor och applicera lite distortion på rösten, vilket gör det mer tydligt.  
Det tredje och sista steget i FL-Studio var att lägga på en liten EQ för att höja diskanten lite samt klippa röstena så de matchar med scenen.

Sedan så lade jag in ljudfilen i en [AI-röstprocessor från Adobe](https://podcast.adobe.com/enhance) vilket gör rösten extremt tydlig och får bort allt övrigt oljud.

> **Compressor** - ett verktyg som minskar dynamiken (skillnaden i ljudnivå) genom att trycka ihop signalen.
{: .prompt-tip }
> **Distortion** - ett verktyg som används för att amplifiera ljudsignalen, men kan även användas som benämning för andra orelaterade förvrängningar till ljudsignalen.
{: .prompt-tip }
> **Parametrisk equalizer** - ett grafiskt gränssnitt på alla frekvenser med 3-7 band som låter en öka eller minska volymen på respektive frekvenser.
{: .prompt-tip }

## Övriga ljudeffekter

När äpplena faller ned och träffar marken så använde jag generiska "thud" ljudeffekter som jag hittade på nätet. De flesta ljudeffekterna var av låg kvalité, men det kan man oftast åtgärda med hjälp av lite "*compression & distortion*" -plugins.