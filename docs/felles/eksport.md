# Eksportfunksjonen

Man kan eksportere fra de fleste skjembildene i SITS. Her er et par eksempler.

**Forutsetning**

Før eksport må vi ha noe data å eksportere som for eksempel alle aktive elever ved din skole:
Gå til SPR og hent for eksempel alle med på ditt VO senter og med Status AP


**Eksport gjøres fra Fil --> Export.**

Hvis du ikke får fram valget Export fra fil er det fordi du mangler rettigheter til det. Helpdesk fikser det hvis du mangler rettigheter.

**Eksportformat**

Man finner frem ulike formatene for eksport ved å først tømme og deretter dobbelklikke i feltet Data Format. [![bilde](../assets/images/gallery.svg){width="15"}](../assets/images/eksport_1.png){.glightbox}. Mest aktuelle typer er trolig HTML som ser greit ut og er lett å kopiere inn i eposter og worddokumenter. Også EXCEL er et greit format som gir bedre mulighet til å behandle dataene i etterkant.

**Rekkefølge/Sortering.**

Standard sortering er rekkefølgen postene ligger i før du tar eksport, men du kan også velge å sortere alfabetisk Hvis du velger sorter alfabetisk fra SPR vil den sortere på feltet som heter Sorter navn.

**Filnavn/lagring**

Klikk på mappeesymbolet og velg hvor du vil lagre, og skriv evt. inn filnavn. [![bilde](../assets/images/gallery.svg){width="15"}](../assets/images/eksport_1.png){.glightbox}

Klikk OK for å gå videre til å velge hvilke felt som skal med. [![bilde](../assets/images/gallery.svg){width="15"}](../assets/images/eksport_2.png){.glightbox}

Etter at du har kommet til skjermbildet kan du velge hvilke felt du vil ha med. For å slippe å ta med alle felt er det greit å klikke på knappen Invert for å fjerne merking ved alle felt og heller aktivt merke de feltene du vil ha.
Her ønsker vi f.eks Deltakernr/SPR og etternavn. Sett da hake ved disse feltene. Gjør eventuell lagring (se neste avsnitt) og klikk OK for å eksportere.

## Lagre eksporten

Hvis du vil bruke eksporten du nettopp har laget en gang til senere kan du lagre utvalget ved å skrive inn et navn i feltet Template [![bilde](../assets/images/gallery.svg){width="15"}](../assets/images/eksport_2.png){.glightbox} og klikke på Save. Da er dette valget og eksportformatet lagret til neste gang du vil kjøre den samme eksporten. 

## Hente opp og kjøre en lagret eksport

Skriv inn navnet på en lagret eksport i feltet Template i Figur 1 for å hente frem en lagret eksport og klikk OK for å komme til neste skjermbilde. Gjør evt endringer og klikk OK for å kjøre.

??? tip "Finne igjen feltkode"

    Gå til skjermbildet du vil eksportere i fra. Det er kjekt å ha to instanser av SITS kjørende når man skal gjøre dette. Dvs start SITS en gang til uten å avslutte programmet du allerede har oppe og la den ene instansen ha eksportskjermbildet og den andre ha skjermbildet som du vil eksportere fra.Velg feltet du ønsker å kjøre analyse på ved å klikke i det feltet (en gang).
	Trykk F1 for å få opp Hjelpmenyen.
	Kopier koden fra FIELD. Feks SPR_UDF1.SPR
	Nå kan du lukke hjelpmenyen og når du er tilbake i skjermbildet for Analyse kan du lime inn verdien fra feltet som du kopierte.


## Endre feltnavn

For å endre overskriften for et felt i eksportfilen kan du klikke på den lille dobbeltpila til høyre for avkrysningsboksen [![bilde](../assets/images/gallery.svg){width="15"}](../assets/images/eksport_2.png){.glightbox} og endre det som står i Heading [![bilde](../assets/images/gallery.svg){width="15"}](../assets/images/eksport_3.png){.glightbox}.

## Formattere et felt

Etter å ha klikket på dobbeltpila [![bilde](../assets/images/gallery.svg){width="15"}](../assets/images/eksport_2.png){.glightbox}, kan du også formattere felt. Nyttige formatteringer kan være datoformattering og endring av store og små bokstaver. Et klikk på den røde knappen ved Export format kan hjelpe deg gjenom formatteringen.

Her er noen eksempler på formattering

	&W gir store forbokstaver OLA blir Ola 
	&DD2-M2-Y formatterer dato slik 24-12-2007
	&DD2M2Y2 formatterer dato slik 241207
	&S kan erstatte verdier.  Koder kan erstattes med navn f.eks slik: &S"ROS"="Lene Almqvist";"SKU"="Ingrid Walbye";"SME"="Torunn Thomassen";"ASE"="Merete Skolla";"SER"="Einar Landmark" slik at det kommer rektors/leders navn i stedet for VO-senterkode


## Hente en verdi fra et felt i en annen tabell  - &G

Det er også mulig å hente verdier fra en annen tabell som f.eks STU til en  SPR eksport.
For å hente noe fra STU må vi benytte en nøkkel som knytter SPR til STU. Nøkkelen er som oftes feltet øverst til venstre i en tabell. (Her finnes unntak)

**Eksempel med å hente språk fra STU til eksporten fra SPR**

Hent først deltakernummeret SPR_STUC.SPR og klikk på dobbeltpila. 
I skjermbildet for å velge feltegenskaper [![bilde](../assets/images/gallery.svg){width="15"}](../assets/images/eksport_4.png){.glightbox} skriver vi inn først &G (and Get) i feltet Eksportformat etterfulgt av feltkoden for feltet du vil hente i STU. 

For å hente feltet med *Førstespråk 1* henter du feltkoden (med metode beskrevet over i avsnittet *Finne igjen feltkode* over) og setter inn det sammen med &G i feltet Exportformat slik: &GSTU_UDF2.STU.SRS 

Merk etter feltkoden må vi også ha med en ”besvergelse” som sier hvilken del av sits vi vil hente data i fra. Det er en del tabeller i SITS som finnes flere steder. Vi må derfor angi hvilken del av SITS vi skal hente data fra.  Det er i hovedsak tre slike deler

	1. SRS – her er elevdata
	2. CAMS her er kursdata
	3. MENSYS – her er systemdata

Aller øverst til høyre i et hvilket som helst skjermbilde ser man hvilke del av SITS skjermbildet tilhører. [![bilde](../assets/images/gallery.svg){width="15"}](../assets/images/eksport_5.png){.glightbox}

**Eksempel med å hente Adresse fra STU til eksporten fra SPR**

For å få inn adressen tar vi et felt for hver adresselinje.
Gjør som i forrige eksempel med å hente elevnummeret slik at du kommer til skjembildet som i Figur 3 . 

Adressefeltene kan du finne riktig databasenavn for fra skjermbildet STUT:

	* Gateadresse	STU_HAD1.STU.SRS
	* Postboks		STU_HAD2.STU.SRS
	* C/O adresse	STU_HAD3.STU.SRS
	* Postnr Sted	STU_HAD4.STU.SRS
	* Telefon		STU_HTEL.STU.SRS
	* Mobil			STU_HAT3.STU.SRS
	* Epost			STU_HAEM.STU.SRS

For gateadressen skriver du da Gateadresse i feltet Heading og &GSTU_HAD1.STU.SRS og klikk Apply.
Gjenta for de andre adressefeltene du vil ha med.
 
NB! Husk nå å lagre (se avsnittet Lagre eksporten) hvis du vil ta vare på denne eksporten til en annen gang 



