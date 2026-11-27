# Kontrollere overføringer til NiR

SITS-forvaltning overfører gjennomførte timer fra SITS til NiR tre uker etter at undervisningen er gjennomført. Dette gir lærere og deltakerkontor to uker til å føre fravær før timene overføres.

Etter overføringen sender SITS-forvaltning en rapport med feillogg til sentrene. Ansvarlig superbruker i NiR skal gjennomgå feilloggen og gjøre nødvendige korrigeringer i SITS og NiR.

Det er viktig at feilene rettes opp raskt slik at de ikke får konsekvenser for senere overføringer.

## Kontrollere opplysninger i SITS mot NiR

SITS og NiR følger ikke alltid de samme reglene. Feil ved overføring kan også skyldes at det er ulike opplysninger om deltaker i de to systemene, f.eks. bostedskommune, rettighet eller manglende vedtak.

1. Slå opp deltaker i NiR

    Det skal også sjekkes om deltaker er registrert i NiR ved inntak og ved nytt inntak på sentrene.

2. Sjekk deltakers rettighet, vedtak, frister og registrerte timer mot tilsvarende opplysninger i SITS

    Ved endring av rettighet må deltaker behandles etter [rutine for endring av norsk-rettighet](../norsk/endre_norskrett.md){.glightbox}.

3. Sjekk at eventuelle timer fra andre kommuner er registrert i SITS

    ??? question "Hvor skal timer fra andre kommuner registreres?"

        1. [Filtrer frem deltaker](../felles/guide.md#filtrere-i-sits) i skjermbildet *SPRS* [![bilde](../assets/images/gallery.svg){width="15"}](../assets/images/meny_skjermbilde.webp){.glightbox}

        2. Klikk på knappen for detaljer om timer nederst til høyre [![bilde](../assets/images/gallery.svg){width="15"}](../assets/images/tmp.webp){.glightbox}

        3. Fyll inn antall norsktimer fra andre kommuner i feltet *SATS/NIR/Utenbys timer* på deltakers norsk-SPR

        4. Klikk på *Apply* og lagre

        Samfotimer registreres på deltakers samfo-SPR.

4. Sjekk at fristene i skjermbildet *SAD* stemmer med opplysningene i NiR

    Se [rutine for endring av rettigheter](../felles/endre_rett.md){.glightbox} for hvilke felt som skal være fylt ut.

    ??? warning "Deltaker nærmer seg utløp av rettighet"

        Se [rutine for å finne deltakere med utgående rett](../norsk/utgående_rett.md){.glightbox}.

## Kontrollere vedtak i NiR

Se [rutine for å lage NiR vedtak](../norsk/vedtak.md){.glightbox} dersom deltaker mangler vedtak eller skal ha nytt vedtak.

1. [Filtrer frem deltaker](../felles/guide.md#filtrere-i-sits) i skjermbildet *STU* [![bilde](../assets/images/gallery.svg){width="15"}](../assets/images/meny_skjermbilde.webp){.glightbox}

2. Fra toppmenyen går du til *Other* ⇒ *Personal Details* for å komme til skjermbildet *SPD* [![bilde](../assets/images/gallery.svg){width="15"}](../assets/images/meny_top.webp){.glightbox}

3. Se gjennom vedtakene deltaker har registrert i SITS

    Feltet *Type vedtak* angir om det er et vedtak for norskopplæring eller annen opplæring.

    ??? tip "Jeg ønsker en oversikt over vedtakene til deltaker"

        Generer [*FOVO VEDOVR*](../felles/guide_pdf.md){.glightbox} fra *STU*.

4. Sjekk at vedtakene også er registrert i NiR

    Vedtak som er overført fra SITS til NiR via *DNI* får en verdi i feltet *NIR referanse* i *SPD* [![bilde](../assets/images/gallery.svg){width="15"}](../assets/images/tmp.webp){.glightbox}.

    Vedtak med en verdi i dette feltet vil ikke bli forsøkt overført på nytt.

    ??? warning "Feltet NIR referanse er tomt"

        Dette betyr ikke nødvendigvis at vedtaket mangler i NiR. Vedtaket kan være registrert direkte i NiR.

        Sjekk derfor i NiR før du evt. registrerer vedtaket på nytt.

    ??? warning "Vedtak er tidligere registrert manuelt i NiR"

        Ved bruk av *DNI* til å overføre behovsprøvde vedtak kan et tidligere førstegangsvedtak uten verdi i *NIR referanse* også bli forsøkt overført.

        Dette kan føre til at førstegangsvedtaket blir liggende dobbelt i NiR.

        Tidligere kunne man hindre dette ved å legge inn en verdi, f.eks. 1, i feltet *NIR referanse* på førstegangsvedtaket. Dette forutsetter at vedtaket allerede er registrert i NiR. Sjekk med SITS-ansvarlig før du benytter denne fremgangsmåten.

    ??? warning "Jeg har fått feilmelding ved overføring av vedtak fra DNI"

        Ved overføring av vedtak med *DNI* sendes eventuelle feilmeldinger på e-post. Du kan også se gjennom *Message buffer* for å se hvordan overføringen gikk.

        Overføring av vedtak med *DNI* har tidligere ofte feilet. Sjekk derfor alltid vedtaket direkte i NiR.

### Feil ved overføring av vedtak

Følgende feil kan oppstå ved overføring av vedtak etter introduksjonsloven:

- Deltaker har brukt mindre enn halvparten av timene på forrige vedtak i NiR.
- Feltet *Dato fra* i SPD er tomt.
- Feltet *Dato til* i SPD er tomt.
- Et førstegangsvedtak har verdi i feltet *Timer behov (N) eller innv (SU)* i UDF.
- Et behovsprøvd vedtak har verdi i feltet *Timer på første vedtak (N)* i UDF.
- Perioden mellom startdato og sluttdato på vedtaket er lengre enn 3 år (NORA-20217).

Sjekk vedtaket i *SPD* og NiR og se om det er manglende eller feil opplysninger.

Ved manglende registrering av timer på vedtak, se [rutine for kontroll av egen datakvalitet](../felles/datakvalitet.md){.glightbox}.

## Kontrollere timer i NiR mot timer i SITS

1. [Filtrer frem deltaker](../felles/guide.md#filtrere-i-sits) i skjermbildet *SPR* [![bilde](../assets/images/gallery.svg){width="15"}](../assets/images/meny_skjermbilde.webp){.glightbox}

2. Generer [*NOVO NIRTIM*](../felles/guide_pdf.md){.glightbox}

    Rapporten viser deltakers timer uke for uke på tilsvarende måte som timene ligger i NiR.

3. Slå opp deltaker i NiR og sammenlign timene med rapporten fra SITS

    ??? warning "Deltaker har timer fra andre kommuner"

        Timene som er registrert av andre kommuner i NiR må også tas med når du sjekker deltakers samlede antall timer og når deltaker har fullført timene på et vedtak.

        Rapporten *NOVO NIRTIM* alene vil ikke vise når deltaker har fullført timene på vedtaket.

4. Gjør nødvendige korrigeringer i SITS og NiR

## Behandle feillogg fra timeoverføring

Feilmeldingene fra NiR gir ikke alltid nok informasjon til å se hva som er galt. I de fleste tilfeller må du derfor slå opp deltaker direkte i NiR.

1. Se gjennom feilloggen fra SITS-forvaltning

2. Slå opp deltaker det er meldt feil på i SITS og NiR

3. Sjekk vedtak, rettighet, datoer og eventuelle andre opplysninger som kan ha ført til feilen

    I noen tilfeller må opplysningene også sjekkes mot folkeregisteret (DSF).

4. Rett opp eventuelle feil i SITS

5. Korriger eller suppler registrerte timer og vedtak direkte i NiR

    ??? warning "Feilen skyldes opplysninger i NiR som jeg ikke kan endre"

        Send en sak til support hos NiR der du beskriver hva som er feil.

        Dette kan f.eks. gjelde manglende vedtak, manglende datoer på adresser eller adresser som ikke stemmer med folkeregisteret.

    ??? warning "Jeg ønsker å overføre timene på nytt fra SITS"

        Korrigering av timer i NiR skal gjøres direkte i NiR.

        Ved bruk av skjermbildet *DNI* i SITS til ny timeoverføring risikerer man å generere ytterligere feil dersom man ikke også sjekker registreringene i NiR.

### Vanlige feilmeldinger ved timeoverføring

??? warning "Ikke rettighet til å endre/opprette rader"

    Denne feilen skyldes som regel at deltaker ikke har en adresse i Oslo registrert i NiR for perioden timene gjelder.

    Ved forsøk på å registrere timer manuelt i NiR kan du få meldingen *Timer kan kun føres av oppfølgingskommune på tidspunktet*.

    1. Sjekk deltakers adresse i NiR

        Hvis aktiv adresse er i en annen kommune må du sjekke om deltaker fortsatt skal ha NiR-timer i Oslo, om deltaker skal være på et annet program eller om deltaker ikke lenger skal ha et tilbud i Oslo.

        Se [rutine for behandling av deltakere som flytter](../norsk/flytter.md){.glightbox}.

    2. Sjekk at *Fra dato* og *Til dato* på adressen i NiR omfatter uken det skal registreres timer for [![bilde](../assets/images/gallery.svg){width="15"}](../assets/images/tmp.webp){.glightbox}

        Det er ikke nok at deltaker har en aktiv adresse i Oslo og at feltet *Endret dato* er fylt ut.

        Hvis datoene på adressen ikke omfatter uken det skal overføres timer for, kan deltaker mangle oppfølgingskommune for denne uken.

    3. Send en sak til support hos NiR dersom datoer på adressen mangler eller må rettes

    4. Etterregistrer timer direkte i NiR for alle uker som ikke ble overført etter at adressen eller datoene er rettet opp

??? warning "Kan ikke registrere flere timer på perioden"

    Dette kan skyldes at det allerede er registrert timer manuelt i NiR for samme uke, eller at deltaker er satt på flere kurs slik at summen av timene overstiger maks antall timer for en uke (38 timer etter tidligere regler).

    1. Sjekk at deltaker er på riktige kurs i SITS for uken det gjelder

        Gjør evt. korrigeringer etter [rutine for å melde på eller av kurs](../felles/bytte_klasse.md){.glightbox}.

    2. [Filtrer frem deltaker](../felles/guide.md#filtrere-i-sits) i skjermbildet *SPR* [![bilde](../assets/images/gallery.svg){width="15"}](../assets/images/meny_skjermbilde.webp){.glightbox}

    3. Generer [*NOVO NIRTIM*](../felles/guide_pdf.md){.glightbox}

    4. Slett timene som allerede er registrert feil i NiR for den aktuelle uken før du registrerer riktige timer fra rapporten

??? warning "NORA-20611 Ugyldig tall"

    Denne feilen har tidligere oppstått for deltakere med rettighet ASYL eller UA. Timer for disse deltakerne måtte registreres manuelt i NiR.

    1. Slå opp deltaker i NiR

    2. Gå til *Deltakelse Asylnorsk* [![bilde](../assets/images/gallery.svg){width="15"}](../assets/images/tmp.webp){.glightbox}

    3. Registrer antall deltatte timer

        Fravær skal ikke registreres her, bare deltatte timer.

    ??? warning "Kan ikke registrere timer etter kategoriens utløpsdato"

        Denne meldingen kan komme dersom du forsøker å registrere flere timer enn deltaker har fått tildelt.

    Se også [rutine for behandling av asyl-deltakere](../norsk/asyl.md){.glightbox}.

??? warning "Web service-feil: Finner ingen personer med dufnummer"

    Deltaker du forsøker å overføre timer for har ikke et gyldig DUF-nummer i NiR.

    1. Sjekk at deltaker er registrert med riktig DUF-nummer i SITS og rett opp eventuelle feil

    2. Send en sak til support hos NiR dersom opplysningene i SITS er riktige og deltaker skulle vært registrert i NiR

    Hvis deltaker ikke har timer som skal overføres for den aktuelle uken kan feilmeldingen ses bort fra.

??? warning "Web service-feil: Person er skjermet"

    Denne feilen har tidligere oppstått både for aktive og sluttførte deltakere som er skjermet.

    1. Gå gjennom feilloggen og finn aktive deltakere på program NNIR som har fått denne feilmeldingen

    2. Registrer timer manuelt i NiR for aktive, skjermede deltakere

    For ikke-aktive skjermede deltakere kunne man tidligere sette en P foran studieløpet for å unngå at deltaker ble forsøkt overført på nytt neste uke.

    Se [oversikt over gyldige SPR](../felles/gyldig_spr.md){.glightbox} og [rutine for behandling av skjermede personer](../felles/skjermet_person.md){.glightbox}.

??? warning "Kan ikke registrere kortvarig fravær når obligatorisk norsktimer er gjennomført"

    Fravær må føres som dokumentert eller udokumentert.

    Denne feilmeldingen tyder på at det ikke er i orden med vedtakene i NiR.

    1. Slå opp deltaker i NiR

    2. Se gjennom deltakers vedtak og oppholdstillatelser

    3. Send en sak til support hos NiR dersom opplysningene ikke stemmer

??? warning "Deltaker med PLIKT har fullført timene i NiR"

    Deltakere med program NNIR og rettighet PLIKT etter introduksjonsloven som har tatt ut sine 250/550 norsktimer kan gi feil ved timeoverføring.

    Slike deltakere kunne tidligere utelukkes fra overføring til NiR ved å sette en P foran sporkoden i *SPR*. Program og rettighet ble da ikke endret.

    Se [oversikt over gyldige SPR](../felles/gyldig_spr.md){.glightbox} før du evt. endrer studieløp.

    Deltakere med program NNIR og rettighet PLIKT ble rapportert på samme måte som deltakere med program NBET i økonomirapportene.

    Dersom deltaker faktisk har endret rettighet må deltaker behandles etter [rutine for endring av norsk-rettighet](../norsk/endre_norskrett.md){.glightbox}.

## Registrere timer i NiR før sentral overføring

Dersom deltaker trenger en bekreftelse på antall gjennomførte timer som også omfatter nyere uker enn det som er overført til NiR, anbefales det å gi deltaker en bekreftelse fra SITS.

??? warning "Det frarådes å registrere timer i NiR før sentral overføring"

    Registrering av timer før den sentrale overføringen kan føre til dobbeltregistrering av timer og feil beregning av fravær i NiR.

    Dersom deltakerkontoret likevel registrerer timer før sentral overføring, **MÅ** registreringene sjekkes på nytt etter den sentrale overføringen, uavhengig av om deltaker kommer med i feilloggen eller ikke.

1. Sjekk med lærer at alt fravær er ført i SITS for ukene det gjelder

    Timer skal ikke registreres i NiR før fraværsføringen er gjennomført.

2. [Filtrer frem deltaker](../felles/guide.md#filtrere-i-sits) i skjermbildet *SPR* [![bilde](../assets/images/gallery.svg){width="15"}](../assets/images/meny_skjermbilde.webp){.glightbox}

3. Generer [*NOVO NIRTIM*](../felles/guide_pdf.md){.glightbox}

4. Registrer timer direkte i NiR for de aktuelle ukene

    Hvis deltaker også har samfotimer må disse registreres for samme uke som norsktimene. Ellers kan det bli feil i beregningen av fraværsgrenser.

5. Sjekk de registrerte timene på nytt etter at SITS-forvaltning har gjennomført den sentrale overføringen

6. Rett opp eventuelle dobbeltregistreringer og feil i fordelingen av timer og fravær

    ??? warning "Deltaker passerer 250/550 norsktimer i perioden"

        For deltakere med førstegangsvedtak på 300/600 timer etter introduksjonsloven kan det bli dobbeltregistrering når deltaker går over til behovsprøvd opplæring.

        Timer som allerede er registrert på førstegangsvedtaket kan bli registrert på nytt som behovsprøvde timer.

        1. Generer [*NOVO NIRTIM*](../felles/guide_pdf.md){.glightbox} fra *SPR*

        2. Finn uken der deltaker passerer 250/550 norsktimer

            Hvis deltaker har timer fra andre kommuner må disse også tas med i beregningen.

        3. Finn ut hvor mange timer i denne uken som hører til førstegangsvedtaket og hvor mange som hører til behovsprøvd vedtak

        4. Slett eventuelle dobbeltregistrerte timer i NiR slik at summen av timene for uken stemmer med *NOVO NIRTIM*

        5. Sjekk at fraværet er fordelt riktig på vedtak og fraværstyper for alle ukene som både er registrert manuelt og overført sentralt

    ??? warning "Summen av timene overstiger maks antall timer for uken"

        Dersom summen av manuelt registrerte timer og timer som forsøkes overført sentralt overstiger maks antall timer for uken, må de manuelt registrerte timene som er feil slettes og riktige timer registreres i NiR.

        Bruk *NOVO NIRTIM* for å finne riktig antall timer.