# Les 1

- blabla
- blablabla
- blablablabla

# Les 2

- blablablabla
- blablabla

# Les 3

- blabla
- blablabla
- bla

<div id="table-of-contents">
<h2>Table of Contents</h2>
<div id="text-table-of-contents">
<ul>
<li><a href="#orgheadline12">1. Les 2 <span class="timestamp-wrapper"><span class="timestamp">&lt;2016-09-05 ma&gt;</span></span></a>
<ul>
<li><a href="#orgheadline1">1.1. Text editors</a></li>
<li><a href="#orgheadline2">1.2. Het belang van text-files en de extensie</a></li>
<li><a href="#orgheadline3">1.3. Extensies bij afbeeldingen</a></li>
<li><a href="#orgheadline4">1.4. Extensies bij audio-bestanden</a></li>
<li><a href="#orgheadline5">1.5. De D-schijf en de H-schijf</a></li>
<li><a href="#orgheadline6">1.6. De inhoud van Office-bestanden : gezipte XML-bestanden</a></li>
<li><a href="#orgheadline10">1.7. Mail-accounts (Oef.)</a>
<ul>
<li><a href="#orgheadline7">1.7.1. De opdracht (<b>algoritmisch</b> en <b>exact denken</b> en het gebruik van <b>variabelen</b>)</a></li>
<li><a href="#orgheadline8">1.7.2. Controle</a></li>
<li><a href="#orgheadline9">1.7.3. Nabeschouwing (Wat is parsen?)</a></li>
</ul>
</li>
<li><a href="#orgheadline11">1.8. TAAK: Aanmaak github-account</a></li>
</ul>
</li>
</ul>
</div>
</div>

# Les 2 <span class="timestamp-wrapper"><span class="timestamp">&lt;2016-09-05 ma&gt;</span></span><a id="orgheadline12"></a>

## Text editors<a id="orgheadline1"></a>

-   notepad
-   notepad++
-   vi / vim
-   emacs
-   spacemacs
-   Visual Studio

## Het belang van text-files en de extensie<a id="orgheadline2"></a>

-   extensies tonen in Windows Explorer
-   mapping van extensies met programma's tonen in Windows Explorer
-   Laten zien welk programma met welke bestandsextensies overweg kan en welke
    daarvan momenteel effectief gekoppeld (gemapt) zijn

## Extensies bij afbeeldingen<a id="orgheadline3"></a>

-   `bmp` : rauwe pixel-data, grootste bestanden, b.v. voor FULL HD = 1920 \* 1080
    pixel \* 3 (bytes per kleur)
-   `gif` : enkel voor afbeeldingen met max. 256 kleuren
-   `jpg` : jpeg compressie, er zijn **artefacten** te zien (als je inzoomt) =
    verlies van kwaliteit
-   `png` : idem als `jpg` maar ondersteunt ook transparante achtergrond

## Extensies bij audio-bestanden<a id="orgheadline4"></a>

-   `wav` : ongecomprimeerd geluid
-   `flac` : gecomprimeerd maar lossless (zonder verlies van kwaliteit)
-   `mp3` : gecomprimeerd met verlies van kwaliteit (vergelijk met `jpg` voor afbeeldingen)

## De D-schijf en de H-schijf<a id="orgheadline5"></a>

-   De H-schijf is een server-map waar je van eender welke PC in het school-netwerk aan kan.
-   De D-schijf (op de PC's in B2.09) wordt o.a. gebruikt voor:
    -   grote bestanden zoals virtuele machines
    -   C#/Visual Studio-projecten omdat die niet altijd goed werken op een netwerkschijf
-   OPMERKING: Sla belangrijke bestanden altijd op, b.v. op Google Drive,
    OneDrive, DropBox, Github, &#x2026;

## De inhoud van Office-bestanden : gezipte XML-bestanden<a id="orgheadline6"></a>

`docx`-, `xlsx`- en andere office-bestanden zijn eigenlijk .zip-files.
Oefening:

-   Verander de extensie van een Office-bestand naar `.zip` en pak het uit.
-   Bekijk de inhoud van een `xml`-bestand. Verklaar de begrippen:
    -   openings-tag
    -   sluitings-tag
-   Open een `xml`-bestand en Chrome en kijk hoe het **geparset** worden
-   Verklaar **parsen**

## Mail-accounts (Oef.)<a id="orgheadline10"></a>

### De opdracht (**algoritmisch** en **exact denken** en het gebruik van **variabelen**)<a id="orgheadline7"></a>

De leerkracht verstuurt een mail naar de gmail-groep **5itn@immalle.be**. 
Elke leerling antwoordt de leerkracht met "OK EOM" in de subject-line met :

-   het @immalle.be-adres van de leerling met klasnummer `mijnKlasnummer + 1` in **Cc**;
-   het @immalle.eu-adres van de leerling met klasnummer `mijnKlasnummer + 2` in **Cc**;
-   het @immalle.be-adres van de leerling met klasnummer `mijnKlasnummer + 2` in **Bcc**;
-   het @immalle.eu-adres van de leerling met klasnummer `mijnKlasnummer + 1`
      in **Bcc**;
-   als `mijnKlasnummer + x > laatsteKlasnummer` gebruik je
    `(mijnKlasnummer + x) - laatsteKlasnummer`

(`EOM` betekent **End Of Message** en wordt gebruikt wanneer er geen inhoud in de
body van de mail aanwezig is en alle info dus vervat zit in het onderwerp.)

### Controle<a id="orgheadline8"></a>

Leerlingen controleren bij elkaar hoe de hoofding van de mail:

-   op mail.google.com:
    -   klik op het kleine pijltje naast de ontvanger
    -   klik op **origineel bericht weergeven** uit het drop-down-menu van de gehele mail
-   op live.com:
    -   klik op de dubbele pijl naast de ontvanger
    -   rechts-klik op het bericht in het bericht-overzicht en kies **berichtbron weergeven**

### Nabeschouwing (Wat is parsen?)<a id="orgheadline9"></a>

Merk op hoe een e-mail bericht eigenlijk een **text-file** is!

Een e-mail programma of web-applicatie moet deze text-file dus **parsen** om het
mooi weer te geven, b.v. om de verschillende velden (zender, ontvanger, Cc, Bcc,
&#x2026;) correct in te vullen in de UI (User Interface).

## TAAK: Aanmaak github-account<a id="orgheadline11"></a>

Ga naar <http://vbrh-immalle.github.io/> en gebruik de 
AccountNaamGenerator-web-applicatie om de gebruikersnaam te genereren die je zal
gebruiken om een account aan te maken op Github.

