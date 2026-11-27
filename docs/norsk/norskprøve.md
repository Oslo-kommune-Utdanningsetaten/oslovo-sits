# Melde på norskprøve

Lærere melder på deltakere til norskprøver i e:Vision etter egen brukermanual (*Påmelding norskprøver*). Påmeldingene ligger deretter i skjermbildet *SQE* i SITS.

Administrasjonen ved hvert senter kontrollerer påmeldingene, registrerer eventuelle manglende påmeldinger og overfører disse til PAD (prøveadministrasjonssystemet).

## Melde på deltaker manuelt i SITS

Etter at påmeldingsperioden for lærere er over kan administrasjonen legge inn nye påmeldinger direkte i SQE.

1. [Filtrer frem deltaker](../felles/guide.md#filtrere-i-sits) i skjermbildet *STU* [![bilde](../assets/images/gallery.svg){width="15"}](../assets/images/meny_skjermbilde.webp){.glightbox}

2. Fra toppmenyen går du til *Other* ⇒ *Quals & Experience* [![bilde](../assets/images/gallery.svg){width="15"}](../assets/images/meny_top.webp){.glightbox}

    ??? warning "Deltaker har påmeldinger fra før"

        Trykk *Ctrl*+*N* for å opprette en ny post i SQE slik at du ikke overskriver en tidligere påmelding.

3. Fyll inn følgende felt i SQE [![bilde](../assets/images/gallery.svg){width="15"}](../assets/images/tmp.webp){.glightbox}

    | Felt | Verdi |
    | --- | --- |
    | SPR-kode | SPR for deltaker |
    | Ansv Instans | Ansvarlig instans for prøven |
    | Prøvetype | Kode for prøven deltaker skal ta |
    | Periode | Perioden deltaker skal ta prøven |
    | Påmeldingsdato | Dagens dato |
    | Registrert av | Din brukerkode |
    | Privatist (betaler) | Huk av hvis deltaker skal betale for prøven |

    Når du trykker *TAB* ut av feltene *Ansv Instans*, *Prøvetype* og *Periode* fylles henholdsvis VO Senter, Prøvenavn og periodenavn ut automatisk.

    ??? question "Hvilken prøvetype skal jeg velge?"

        | Kode | Prøvetype |
        | --- | --- |
        | A1A2MUN | Norsk muntlig - Nivå A1-A2 (tidligere NP2M) |
        | A1A2SKR | Norsk skriftlig - Les/Lytt A1-B1, Skriv A1-A2 |
        | A2B1MUN | Norsk muntlig - Nivå A2-B1 (tidligere NP3M) |
        | A2B1SKR | Norsk skriftlig - Les/Lytt A2-B1, Skriv A2-B1 |
        | B1B2MUN | Norsk muntlig - Nivå B1-B2 |
        | B1B2SKR | Norsk skriftlig - Delprøve skriftlig produksjon B1-B2 |

    ??? question "Deltaker skal ta skriftlig prøve"

        Klikk på *UDF*-knappen [![bilde](../assets/images/gallery.svg){width="15"}](../assets/images/meny_udf.webp){.glightbox} og fyll inn hvilke delprøver deltaker skal ta i feltene *Oppmeld Lytt*, *Oppmeld Les* og *Oppmeld Skriv*.

    ??? question "Skal jeg fylle inn rettighet og DUF-nr i SQE?"

        Det er egne felt for dette i SQE, men ved eksport til PAD hentes disse verdiene fra SPR.

    ??? question "Skal deltaker meldes på som privatist?"

        Se [Kontrollere hvem som skal betale](#kontrollere-hvem-som-skal-betale).

4. Lagre

## Filtrere frem påmeldinger

Før overføring til PAD er det vanlig å ta ut hver prøvetype for seg, og privatister og ikke-privatister hver for seg.

1. Gå til skjermbildet *SQE* [![bilde](../assets/images/gallery.svg){width="15"}](../assets/images/meny_skjermbilde.webp){.glightbox}

2. Fyll inn *Prøvetype*, *Skoleår*, *Periode* og *Ansv Instans* for ditt senter [![bilde](../assets/images/gallery.svg){width="15"}](../assets/images/tmp.webp){.glightbox}

3. Velg om du vil hente frem privatister eller ikke-privatister

    === "Privatister"

        Huk av i feltet *Privatist (betaler)*.

    === "Ikke-privatister"

        Huk først av i feltet *Privatist (betaler)* og fjern deretter haken igjen.

        Ved å først huke av og deretter fjerne haken sier du fra til SITS at du vil hente frem poster der feltet ikke er huket av.

4. Trykk *F5* for å hente frem påmeldingene

## Kontrollere hvem som skal betale

Ved påmelding i e:Vision sjekker SITS automatisk om deltaker har fått en gratisprøve tidligere, og gir lærer tilbakemelding dersom deltaker må betale for prøven.

Interne privatister registreres på samme måte som andre deltakere, men har hake i feltet *Privatist (betaler)* i SQE.

1. [Filtrer frem påmeldingene](#filtrere-frem-påmeldinger) i skjermbildet *SQE*

2. Generer [*TOVO SJEKKE*](../felles/guide_pdf.md){.glightbox}

3. Se gjennom rettighet, treårsfrist og tidligere prøveresultater i rapporten og kontroller at *Privatist (betaler)* er riktig på påmeldingene

    ??? question "Hvilke deltakere skal betale ut fra rettighet?"

        Deltakere med følgende rettigheter (UDF1 på SPR) skal betale for prøven:

        - BETAL
        - PLIKT
        - URETT

        Unntaket er deltakere som har PLIKT på grunn av utgått treårsfrist. Disse har en dato i feltet for 3-årsfrist.

        Deltakere med PLIKT uten dato i feltet for 3-årsfrist skal betale.

    ??? question "Deltaker har tatt norskprøve tidligere"

        Deltaker skal betale dersom den tidligere har tatt en gratisprøve med en av følgende prøvetyper:

        | Muntlig | Skriftlig |
        | --- | --- |
        | NP2M | NP2S |
        | NP3M | NP3S |
        | A1A2MUN | A1A2SKR |
        | A2B1MUN | A2B1SKR |
        | B1B2MUN | B1B2SKR |

        Tidligere prøver med resultat GF (gyldig fravær) eller UAV (uavklart) regnes ikke med.

        Tidligere prøver som er tatt som privatist regnes heller ikke med.

        Muntlig og skriftlig prøve vurderes hver for seg. En deltaker som bare har tatt muntlig gratisprøve tidligere kan fortsatt få skriftlig prøve gratis, dersom deltaker har rett til gratisprøve.

4. Rett eventuelle feil i feltet *Privatist (betaler)* og lagre

SITS drift gjennomgår også prøvepåmeldingene etter at påmeldingsperioden for lærere er over.

## Behandle påmeldinger for interne privatister

Lærer skal informere deltakere som meldes på som privatister om at påmeldingen ikke er endelig før deltaker har betalt for prøven på deltakerkontoret/resepsjonen.

Det settes av en periode etter påmeldingsvinduet der deltakerne kan betale for prøven.

1. [Filtrer frem påmeldingene](#filtrere-frem-påmeldinger) for privatister i SQE

2. Generer [*NOVO PADEKSP*](../felles/guide_pdf.md){.glightbox}

3. Marker hvem som har betalt på listen

    Betalingene registreres i PAD, og deltaker flyttes over til en prøvegruppe i PAD.

    ??? tip "Jeg ønsker å registrere betalinger i SITS"

        Det er et eget avkryssingsfelt *Betalt for prøve* i SQE som deltakerkontoret kan bruke til dette [![bilde](../assets/images/gallery.svg){width="15"}](../assets/images/tmp.webp){.glightbox}.

4. Marker eventuelle avvik på skriftlige delprøver i listen

    ??? warning "Deltaker skal ikke ta alle delprøvene i skriftlig prøve"

        Lærer kan bare melde på deltaker til komplett prøve i e:Vision.

        Hvis deltaker bare skal ta en eller to av delprøvene melder lærer deltaker på til hel prøve og gir beskjed til deltakerkontoret om hvilke delprøver deltaker skal ta.

        Avvikene skal også registreres i merknadsfeltet i SQE.

5. Når betalingsperioden er over og senteret har oversikt over alle innbetalinger, slettes påmeldinger i SQE for privatister som ikke har betalt

    ??? warning "Deltaker har ikke betalt for prøven"

        Manglende betaling betyr at deltaker ikke skal meldes på til prøven.

6. Generer en ny [*NOVO PADEKSP*](../felles/guide_pdf.md){.glightbox} med de privatistene som har betalt for prøven

7. Overfør påmeldingene til PAD på samme måte som for deltakere som får prøven gratis. Se [Overføre påmeldinger til PAD](#overføre-påmeldinger-til-pad)

    ??? tip "Jeg ønsker å registrere privatister fortløpende i PAD"

        Som alternativ til felles innlasting kan privatister registreres enkeltvis i PAD etter hvert som betalingene kommer inn.

Videre behandling av påmelding, prøvegrupper og rom gjøres i PAD på samme måte for interne privatister som for andre deltakere ved senteret.

## Overføre påmeldinger til PAD

1. [Filtrer frem påmeldingene](#filtrere-frem-påmeldinger) i skjermbildet *SQE*

2. Fra toppmenyen går du til *All* ⇒ *Gen + print letter* [![bilde](../assets/images/gallery.svg){width="15"}](../assets/images/meny_top.webp){.glightbox}

3. Generer [*NOVO PADEKS*](../felles/guide_pdf.md){.glightbox} ved å velge *Create HTML file*

    ??? tip "Andre varianter av NOVO PADEKS"

        | Rapport | Beskrivelse |
        | --- | --- |
        | NOVO PADEKS | Uttrekk med verdier som PAD trenger |
        | NOVO PADEKSL | Uttrekk som også har med lærer |
        | NOVO PADEKSP | Uttrekk med privatister |

4. Last ned Excelmalen for import av kandidater fra PAD

5. Marker alt unntatt overskriftene i rapporten *NOVO PADEKS* og trykk *Ctrl*+*C*

6. Høyreklikk i celle A2 i Excelmalen fra PAD og velg *Lim inn utvalg* og deretter *Bruk målformatering* [![bilde](../assets/images/gallery.svg){width="15"}](../assets/images/tmp.webp){.glightbox}

    ??? warning "Bruk målformatering ved innliming i Excelmalen"

        Ved å lime inn med målformatering sikrer du at DUF-nr og fødselsnr får med alle sifrene.

7. Last inn kandidatene i PAD