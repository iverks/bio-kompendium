# Kapittel 10: Rekombinante Proteiner

For å lage [rekombinante](rekombinant) proteiner blir genen isolert og klonet til en [uttrykking](genuttrykking)s[vektor](vektor). Det vanligste i praksis er å sette menneskegener inn i en annen organisme som f.eks. en bakterie eller i gjærsopp.

Proteiner som blir produsert av rekombinant tekonlogi ligger ofte i en av fire kategorier:

1. Erstatninger for proteiner som er mangelfulle eller defekte.
2. Økning av mengden av et protein som allerede er til stede.
3. Inhibering av skumle saker som bakterier eller virus.
4. Bærere for andre molekyler (fortsatt i utvikling).

I industrien er det ønskelig å lage så mye protein som mulig så billig som mulig. Da kan man bruke en plasmid med mange kopier av den samme genen for å få mange kopier av proteinet per transkripsjon-translasjon-syklus. Et problem med dette er at DNA med mye repetisjon (som disse plasmidene har) er svært ustabilt. En løsning på det igjen er å gjøre plasmidet antibiotikaresistant og drepe alt annet i miljøet med antibiotika, men antibiotika er dyrt.

## Eukaryotiske gener i prokaryotiske vektorer

En vil ofte uttrykke [eukaryotiske](eukaryot) gener (forskjellige grunner, men deg gir mening ettersom vi er eukaryoter). Det går an å gro eukaryotiske gener i eukaryotiske celler (som gjær), men vi har bedre kjennskap til [prokaryotiske](prokaryot) celler (bakterier), så de er enklere å manipulere. For å produsere eukaryotiske gener i prokaryotiske vektorer må man gjøre et par inngrep:

(cDNA)=

### cDNA

Eukaryotisk DNA inneholder i tillegg til kodende DNA promoter-sekvenser og [introner](introner). cDNA er det samme DNAet, men uten disse tingene. cDNA brukes ofte også i eukaryotiske vektorer rett og slett fordi du får en kortere gensekvens.

```{admonition} Promoter-sekvenser
Prokaryoter forstår ikke eukaryotiske promoter-sekvenser, så vi må ta de ut og erstatte de med prokaryotiske promoter-sekvenser. Disse kommer gjerne fra vektoren vi skal bruke.
```

(redundant-kodon-historie)=

## Valg av (redundant) kodon

Det er kjent at mange [kodoner](kodon) korresponderer til den samme aminosyren. Noen celler bruker gitte sekvenser mer enn andre. F.eks. e. coli bruker AAA oftere enn den bruker AAG til å enkode aminosyren lysin. Det som oversetter et kodon til en aminosyre er T-RNA, og om en celle har lite av det spesifikke tRNA som oversetter en sekvens kan dette være en begrensende faktor for [translasjon](translasjon) av dette.

```{admonition} Virus-immune celler
Forskere har laget celler som er immune mot virus ved å bytte ut alle variasjoner av en type kodon med et spesifikt et (altså at alle AAA + AAG -> AAA). De har så fjernet alt av tRNA som oversetter alle de andre kodonene. Dette betyr at når det kommer et fremmed gen (virus) inn i cellen, som etter all sannsynlighet inneholder minst en av den andre typen kodon, blir ikke virusgenene uttrykt. Cellen er dermed immun mot alle typer virus.

~Jeg har mistet kilden min for dette så ikke ta meg på ordet~
```

Dette er ikke et problem i naturen fordi naturlig utvalg har gjort slik at mengden tRNA og de valgte kodoner stemmer godt overens. I rekombinante vektorer kan det derimot være et problem. Det finnes to løsninger:

1. Bytte ut disse kodonene med kodoner der det finnes mye tilhørende tRNA. Dette er arbeidsomt, og DNAet må produseres kunstig.
2. Tilfør tRNA som hører til det begrensende kodonet. Gir litt dårligere resultater enn det andre forslaget.
