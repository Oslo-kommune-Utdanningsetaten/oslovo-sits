# Avansert filtrering

Bruker bestemmer hvor mange felt skal være med avhengig av målet med filtrering. UDF feltene kan også være med i filtreringen. Man kan også hente delverdier fra et felt ved å bruke ·\* (golden star) foran, bak eller mellom symbolene i feltet. Man kan fylle inn Gold star ved å bruke stjernetegnet på det numeriske tastaturet. Hvis du ikke har tastatur med de nummeriske tallene til høyre kan du i stedet høyreklikke i feltet du vil filtrere i og velge Insert wildcard og derette velge f.eks Any character (\*). 

## Bruk av flere felt til henting av poster


**Eksempel: filtrering av alle deltakere fra Rosenhof med status AP eller LA** [![bilde](../assets/images/gallery.svg){width="15"}](../../assets/images/spr_filtrere.png){.glightbox}

Forklaring:
Det er to felt som er i bruk for å få hentet alle aktive fra Rosenhof. VO-senter = ROS og status = AP eller LA. Eller-tegnet mellom AP og LA får du inn ved å taste plusstegnet på det numeriske tastaturet og deretter "bartegnet" (|) øverst til venstre på det vanlige tastaturet. Du kan også høyreklikke i feltet etter at du har skrevet AP og deretter velge Insert wildcard og deretter velge Or (|).

**Eksempel: finne alle deltakere på nivå med utdanningsbakrunn = NG med skriftlig nivå = SA10** [![bilde](../assets/images/gallery.svg){width="15"}](../../assets/images/spr_filtrere_nivaa.png){.glightbox}

Forklaring: 
Vi bruker først NG med gold stjerne bak for å skille ut alle som har utdanningsbakgrunn NG og definert skriftlig nivå SA1. Slik vil systemet finne alle som har disse to verdier i sin anbefalte opplæring uavhengig av andre verdiene de har i koden. Felt som består av samlede verdier, som f eks feltet Anb opplæring i SPR som inneholder både utdanningsbakgrunn, muntlig- og skriftlig nivå, har mange muligheter for filtrering.

Det kan være flere Gold star i et og samme felt under filtrering. Hvis du f.eks skriver inn NG·*SA1·* i feltet Anbefalt opplæring og trykker F5 får du hentet alle med utdanningsbakgrunn = NG med skriftlig nivå SA1 samt de med nivå SA1 R, SA1+ og SA1+ R

**Eksempel: få fram alle som søkte NORSK i løpet av mai 2026** [![bilde](../assets/images/gallery.svg){width="15"}](../../assets/images/acd_filtrere_dato.png){.glightbox} 

Forklaring: Vi velger innsøking NORSK, ikke noe status fordi vi vil ha både overførte og ikke overførte. Vi kan også begrense slike søk til bestemt studieløp, program eller begge deler. Vi tar i bruk datofelt for søknadsdato og fyller inn følgende tekst i feltet: ·>·=01/May/2026·&·<·=30/May/2026. I klartekst står det at dato skal være større enn eller lik 01 mai 2026 og mindre enn eller lik 30 mai 2026. For å velge en dato i SITS som er større enn/ mindre enn en bestemt dato, går du via Insert Wildcard ved å høyreklikke i feltet. Da får du opp alternativene som hjelper oss å definere søket. Du kan enten begrense et søk/ utelukke verdier fra et søk eller kombinere verdier i et søk i samme felt. 

## Filtrering på flere verdier i samme felt

	a.	Velg/skriv inn verdien i aktuelt felt
	b.	Høyreklikk bak første verdien 
	c.	Gå via Insert Wildcard og velg Or (|)
	d.	Skriv inn en annen verdi
	e.	Trykk F5 eller klikk på filtreringsknappen

Det er også mulig å bruke flere verdier 

**Eksempel: Finn alle SPR med rettighet REPL og PLIKT** 
Det gjør du ved å skrive inn REPL·|PLIKT i feltet for rettighet i UDF på SPR og deretter trykke F5 for å hente postene.

## Utelukke enkelte verdier fra filtrering
	a.	Høyreklikk i det aktuelle feltet
	b.	Gå via Insert Wildcard og velg Not (!)
	c.	Skriv inn aktuelle koden med blokkbokstaver
	d.	Trykk F5 eller klikk på filtreringsknappen

**Eksempel: Finn alle aktive SPR på ditt senter som ikke har Program NBET**
Det gjør du ved å velge Status = AP, VO-senter = "Ditt senter" og i feltet Program velger du wildcard Not og skriver NBET slik at det står dette i feltet ·!NBET før du trykker på F5

## Fjerne utvalg av poster som du har filtrert fram - Drop records
Med Drop records som du finner fra menyen Misc, kan du utelate eller beholde poster fra en hentet liste ved hjelp av ulike kriterier, inkludert intervaller eller postverdier. De postene som du utelater blir ikke slettet; de er bare ikke tilgjengelige for visning eller behandling i det gjeldende skjermbildet.

Dette kan være nyttig dersom du arbeider med en stor liste og ønsker å utelate de postene som allerede er gjennomgått eller endret. Ved bruk av alternativet velg etter verdi er det også mulig å søke i ett enkelt felt eller i alle feltene i det gjeldende skjermbildet for å definere hvilke poster som skal utelates eller beholdes.

Denne kommandoen er bare tilgjengelig når mer enn én post er hentet.

