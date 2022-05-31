# Definisjoner

Denne siden er ikke ment for å bli lest fra topp til bunn, men inneholder en samling av definisjoner som jeg syntes var vanskelige å huske.

(prokaryot)=

## Prokaryot celle

Pro: før, karyot: kjerne. Førkjerne celle. En prokaryot er et vesen som har celler uten cellekjerner. Kjente prokaryoter er bakterier.

(eukaryot)=

## Eukaryot celle

Eu: bra, karyot: kjerne. Bra-kjærne-celle. En celle som har kjerne. Er mer avanserte enn prokaryoter, og det meste av det du tenker på som "liv" er eukaryoter. Gjærsopp er ofte brukt innen forskning på eukaryoter fordi de har så korte generasjoner, og dermed tillater raskere forsøk.

(antiparallell)=

## Antiparallell

Antiparallell vil si parallell men med omvendt retning. De to følgende tallsekvensene er antiparallelle dersom retningen er bestemt av endringen i tallverdi.  
1-2-3-4-5-6-7-8-9  
9-8-7-6-5-4-3-2-1  
I DNA og RNA er det retningen til bindinger som definerer retningen, vi leser dem fra 5' til 3'. [Les mer.](dna)

(komplementaer)=

## Komplementær

At to ting er komplementære betyr at de utfyller hverandre.
I DNA og RNA betyr dette for eksempel at Guanin og Cytosin er komplementære baser i DNA-molekylet, fordi de danner stabile hydrogenbindinger sammen i dobbeltheliksen.

(dna)=

## DNA

DNA består av to tråder. Trådene er [antiparallelle](antiparallell) og [komplementære](komplementaer)

```{figure} ./images/dna.png
---
name: dna
width: 400px
---
Watson-Crick modellen av DNA-strukturen. (a) Skjematisk representasjon av strukturen. (b) Kule-pinnemodell. (c) Kalottmodell.
```

I DNA og RNA er retningen til en tråd definert av hvilket karbonatom i pentosen som er bundet i hvilken retning. DNA-ryggmargen er nemlig bygget opp slik: pentose - fosfat - pentose - fosfat...

```{figure} ./images/dna-ryggmarg.jpg
---
name: single-strand-dna
width: 400px
---
Strukturen til en enkeltrådet DNA/RNA.
```

I pentosen er 1' bundet til basen, 3' og 5' bundet til en fosfatgruppe. Vi leser alltid sekvensene fra 5' til 3'.

```{figure} ./images/pentoses.jpg
---
name: pentoses
width: 400px
---
Tellesystemet for pentosene ribose og deoksyribose. Merk her at grunnen til at vi teller i den retningen er at den aktive gruppen - A, T, G eller C - binder seg ved kondensasjonsreaksjon på plasseringen 1'. Det er dermed naturlig å kalle den for 1'.
```

### Eukaryotisk DNA

Eukaryotisk DNA er mer komplisert enn prokaryotisk DNA. Det består av [introner](introner) og [eksoner](eksoner).

(introner)=

#### Introner

Introner er sekvenser med DNA som ikke koder for noe som helst som skiller [eksoner](eksoner) fra hverandre.

(eksoner)=

#### Eksoner

Eksoner er sekvenser med DNA som koder for gener. I eukaryotisk DNA koder et ekson for ett gen (stemmer ikke men det var et eller annet om at prokaryoter har flere gener i en sekvens)

(RNA)=

## RNA

todo

(virus)=

## Virus

Et virus er en sammensetning av arvestoff pakket inn i en proteinkapsel som kalles kapsid. Virusets arvestoff kan enten være [DNA](dna) eller [RNA](RNA). Viruset er ikke i stand til å reprodusere alene, og det er derfor noen som mener at virus ikke er en levende organisme. Virus formerer seg ved å infisere en vertscelle og lure den til å produsere mer virus.

(adenovirus)=

### Adenovirus

Adenovirus er en familie av virus med [DNA](dna) som arvestoff. Man vet mye om adenoviruset, og de skaper ikke alvorlige infeksjoner. Problemet med adenovirus som vektor er at de bare får uttrykt genet i noen uker før immunforsvaret stopper infeksjonen og man blir immun ut livet.

(retrovirus)=

### Retrovirus

Retrovirus er en familie av virus med [RNA](RNA) som arvestoff. I tillegg til RNA inneholder viruspartikkelen enzymet revers transkriptase. Dette gjør at retrovirus kan sette arvestoffet sitt inn i [DNAet](dna) til vertscellen, og endrer dets genom permanent. Å gå fra RNA til DNA på den måten er det omvendte av det som er vanlig for virus, derav navnet. Et eksempel på retrovirus er HIV.

Fordelen med retrovirus som vektor er at genomet blir i cella for alltid, til og med når den formerer seg.

Et av problemene med å bruke retrovirus i genterapi er at de kan sette inn arvestoffet sitt på feil plass i cellen og forårsake kreft.

(adeno-assosiert-virus)=

### Adenoassosiert virus

Adenoassosiert virus er små virus som ikke forårsaker sykdom. De skaper bare en mild immunrespons, og er derfor perfekte å bruke i genterapi. De har også evnen til å stabilt sette inn genomet sitt på spesifikke plasser. Det gjør dem mer forutsigbare enn [retrovirus](retrovirus).  
Navnet adenoassosiert virus kommer av at de først ble oppdaget som det man trodde var forurensing i prøver med [adenovirus](adenovirus).

Fordelene med å bruke aav som vektor i genterapi er at i likhet med retrovirus blir genen værende i cella for evig, og at det ikke fremprovoserer immunrespons.

(transkribering)=

## Transkribering

Transkribering \(må ei blandes med [translasjon](translasjon)\) er prosessen å oversette DNA til RNA.

(translasjon)=

## Translasjon

Translasjon \(må ei blandes med [transkribering](transkribering)\) er prosessen å oversette RNA til proteiner

(genuttrykking)=

## Genuttrykking

Genuttrykking er en prosess der informasjonen i et gen kommer til uttrykk. Selve prosessen innebærer både [translasjon](translasjon) og [transkribering](transkribering), men betegnelsen genuttrykking brukes ofte der man ikke trenger å forstå mekanismen bak det.

(kodon)=

## Kodoner

Kodoner er sekvenser på tre i DNA eller RNA som tilsvarer enten en aminosyre eller en stoppsekvens.

```{admonition} Hvorfor tre?
Det finnes 20 aminosyrer, pluss en stoppsekvens blir 21. Dersom et kodon var 2 langt, hadde vi hatt $4^2=16$ mulige koder, som ikke holder til alle aminosyrene. Det vi har i stedet er $4^3=64$ muligheter. Dette åpner åpenbart for "redundancy", altså koder som betyr det samme. For cellene betyr det at de er litt mer feiltolerante.
```

(hybridisering)=

## Hybridisering

Hybridisering betyr generelt sett å blande to ting for å få en hybrid.  
DNA-hybridisering er paring mellom to enkelttrådede DNA-biter som er [komplementære.](komplementaer) Hybridisering kan også skje i DNA-tråder som ikke er fullstendig komplementære, men de basene som ikke passer overens vil ikke binde seg og det er derfor ikke like stabilt. Bitene vil derfor falle fra hverandre \([denaturere](denaturere)\).

(rekombinant)=

## Rekombinant

Rekombinant er en betegnelse på noe der to biter [DNA](dna) fra forskjellige organismer er satt sammen. Det er ofte en interessant gen som er satt inn i en [vektor](vektor) som er praktisk å jobbe med.

(vektor)=

## Vektor

En vektor er en beholder som kan holde gener. De er helt essensielle for [rekombinant](rekombinant) genteknologi. Eksempler på vanlige genvektorer er [virus](virus), [plasmider](plasmid) eller kunstige kromosomer.

(denaturere)=

## Denaturering

Denaturering er fullstendig eller delvis ødeleggelse av et proteins tertiærstruktur. Denaturerte proteiner har ikke sin vanlige struktur, og kan dermed ikke gjennomføre sin vanlige funksjon, de er biologisk inaktive.

(palindromsk)=

## Palindromsk

Det at en gen er palindromsk betyr ikke helt det samme som at et ord er palindromsk. Når et ord er palindromsk er den ene enden av ordet lest framlengs lik den andre enden av ordet lest baklengs, f.eks. returruter: (retur)-(ruter).  
Når et gen er palindromsk er den ene enden av ordet lest framlengs [komplementær](komplementaer) med den andre enden av ordet lest baklengs, f.eks. TGACGTCA (TGAC)(GTCA)  
Gener er gjerne ikke fullstendig palindromsk, men har enkelte sekvenser som korresponderer. Da danner de "hairpin"-struktur (hårspenne).

```{figure} ./images/hairpin.png
---
name: hairpin-struktur
width: 400px
---
Her kan vi se et eksempel på en hairpin-struktur. Som du ser er det ikke fullstendig palindromsk. De komplementære delene danner hydrogenbindinger og stabiliserer strukturen.
```

(lenker)=

## Lenker

Dette kompendiet baserer seg på lenker for å kjapt finne definisjonene til kompliserte konsepter som brukes mye. Da slipper vi å kludre til tekstene med masse bisetninger, og du slipper å google annethvert ord.
