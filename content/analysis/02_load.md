---
Title: Load
Description: This is our load page.
Template: technologies
---

Laddningstid och andvändbarhet på hemsidor.
=====================



Urval
----------------------
Jag har valt tre olika hemsidor jag tänkte göra en analys på.
Svenska bryggriket är min första hemsida jag har valt att analysera och det är dessutom min fars egna hemsida han har skapat själv så den var ett självklart val.
Den andra hemsidan jag har valt är warcraftlogs som jag använder relativt frekvent, det är en hemsida man kan mäta spelares prestation i world of warcraft.
Sen kommer vi till den tredje och det blev youtube. Youtube kan nog alla relatera till att man besöker relativt ofta, det är dessutom den jag antar har högst budget. Presterar de bäst? 


<ul>
    <li><a href="https://www.bryggriket.se/?lang=en">Svenska Bryggriket</li>
    <li><a href="https://www.warcraftlogs.com/">Warcraftlogs</li>
    <li><a href="https://www.youtube.se/">Youtube</li>

</ul>

Metod
-----------------------
Jag använder i rapporten PageSpeed Insights från Google för att mäta prestandan på webbsidorna. Jag använder devtools i Mozilla Firefox för att mäta laddningstiden och antal resurser på de olika sidorna. Datan sparar jag ner i ett Google Kalkylark.

Resultat
-----------------------

Rådata från mätningarna:
<iframe class="iframe" src="https://docs.google.com/spreadsheets/d/e/2PACX-1vS_cusUsM6DRF7HRpT1W-0t-pV61cVW71ln3UVrV1uT0RPxe5XPdSr4JILahGfBUdpzUY0Syxa2m0UW/pubhtml?gid=0&single=true" width="600" height="200"  ></iframe>


Svenska Bryggriket
-------------------

Mobile (31p) Desktop (73p)

[![Alt text](%base_url%/image/bryggriket.png?w=600)](%base_url%/image/bryggriket.png)

Svenska bryggriket's hemsida har en laddningstid på 3.15s. Den har 301 resurser och laddar in material allt eftersom man scrollar på hemsidan. Webbplatsen skulle kunna förbättra sig genom att minska antalet resurser och minska antalet resurser som laddas in. Det verkar finnas en del css som inte används samt javascript. Hemsidan verkar vara uppbygd i wix så det är svårt att säga exakt vad som händer. För att sammanfatta så ligger de flesta förbättringsförlsagen i att minska antalet javascript och css. Samt att möjligtvis minska antalet "onödiga" bilder.

Svenska bryggrikets hemsida är absolut bäst optimerad för dekstop med 71p och mobil med 31p. De tre största förbättringsförslagen är "Reduce JavaScript execution time, Minimize main-thread work, Reduce the impact of third-party code.

Svenska bryggriket får godkänt på 

Warcraftlogs
-------------------------

Mobile (25p) Dekstop (22p)

[![Alt text](%base_url%/image/warcraft.png?w=600)](%base_url%/image/warcraft.png)

Warcraftlogs hemsida har en laddningstid på 2.95s. Den har 582 resurser och laddar också in material allt eftersom man scrollar på hemsidan. Webbplatsen skulle kunna förbättra sig genom att minska antalet resurser och minska antalet resurser som laddas in. Vid de tester som utförts så har hemsidan en (FCP) First contentful paint på 2s, (LCP) Largest contentful paint på 2s samt (TTFB) Time to first byte på 1s.Hemsidan presterar bra på mobile men tyvärr så blir den inte godkänd på desktop. Den största kritiken är "Eliminate render-blocking resources".

Warcraftlogs får icke godkänt på desktop men går igenom på mobile.


Youtube
--------------------

Mobile (42p) Desktop (36p)

[![alt text](%base_url%/image/youtube.png?w=600)](%base_url%/image/youtube.png)

Youtubes hemsida har en laddningstid på 2.08s vilket är den bästa av de tre som analyserats. Den har 69 resurser. Webbplatsen skulle kunna förbättra sig genom att minska antalet javascript samt minska antalet javascript som inte används. Vid de tester som utförts så har hemsidan en (FCP) First contentful paint på 1.4s, (LCP) Largest contentful paint på 4.9s samt (TTFB) Time to first byte på 0.4s.
Den största kritiken är "Reduce JavaScript execution time". 

Enligt pagespeed får hemsidan inte godkänt.


Analys
----------------------

Om vi kollar på de vanligaste förbättringsförslagen så verkar de vara att reducera antalet javascript och minska antalet javascript som inte används samt användandet av bilder. Det är dock viktigt att ta till hänsyn att jag som "student" möjligtvis inte har den kunskap som krävs för att ge ett godtyckligt uttalande kring webbplatsens prestanda. Datan jag har baserat min analys på är från verktyg som PageSpeed Insights och devtools. Det kan mycket möjligt vra så att jag har läst fel vilket skulle kunna resulterat i ett felaktigt resultat.

Enligt min analys så är sambandet mellan hur snabbt en hemsida laddas in beroende på hur snabbt samt hur långa javascript som laddas in samt blockeras. Det beror dessutom på hur många resurser som ska laddas in med andra ord rådata.

Poäng
---------------

Rankningen baseras på hemsidornas poäng som (desktop/mobil)/2 för att ge ett snittbetyg.


1. Svenska Bryggriket (52p)
3. Youtube (39p)
2. Warcraftlogs (23.5p)

Svenska bryggriket är den utav de hemsidor som tar hem vinsten på följd kommer youtube samt warcraftlogs. Alla hemsidor har en laddningstid på runt 2-3 sekunder vilket är bra.

Google rekommenderar att sidor laddas på under 2 sekunder vilket dessa hemsidor i stort sett gjorde.

Övrigt
----------------

Denna rapporten är skriven av mig, Alexander Wittenby.
