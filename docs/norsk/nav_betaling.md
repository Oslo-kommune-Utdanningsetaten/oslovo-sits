# Behandle NAV-betal (samarbeidsavtalen)

Denne rutinen gjelder deltakere som er bosatt i Oslo og hvor deltakers NAV-kontor ønsker å betale for norskopplæringen.

Det er to grupper deltakere som omfattes av rutinen:

| | Program | Rettighet |
| --- | --- | --- |
| Deltakere uten NiR-rettigheter | NBET | BETAL |
| Deltakere med plikt, men uten rett | NNIR | PLIKT |

Begge gruppene må i utgangspunktet betale for norskopplæringen selv.

Rutinen beskriver registrering i SITS. For andre deler av prosessen, se samarbeidsavtalen mellom Oslo VO og NAV Oslo.

??? warning "Hvem gjelder ikke denne rutinen for?"

    - Deltakere med NiR-rett i en annen kommune hvor hjemkommunen ønsker å betale for opplæringen.
    - Deltakere som får betalt opplæringen av andre enn sitt NAV-kontor, f.eks. arbeidsgiver, selv om det finnes en avtale om fakturering.

## Registrere søknad

Inntakskonsulenten på Servicesenteret skal være informert om hvilket NAV-kontor som ønsker å betale for opplæringen.

Vanlige rutiner for [registrering av søknad](../sese/ny_acd.md){.glightbox}, [kartlegging](../sese/ny_kart.md){.glightbox} og evt. [vedtak](../sese/vedtak.md){.glightbox} følges.

I tillegg må følgende registreres i ACD før søknadsbekreftelsen genereres:

1. Klikk på *UDF*-knappen [![bilde](../assets/images/gallery.svg){width="15"}](../assets/images/meny_udf.webp){.glightbox}

2. Fyll inn anbefalt antall måneder med norskopplæring som NAV bør kjøpe i *UDF4* [![bilde](../assets/images/gallery.svg){width="15"}](../assets/images/tmp.webp){.glightbox}

    Når dette feltet er fylt ut vil søknadsbekreftelsen inneholde tilpasset betalingsinformasjon til søker og anbefaling om antall måneder med opplæring til saksbehandler i NAV.

3. Fyll inn følgende informasjon i feltet *SPR* i ACD [![bilde](../assets/images/gallery.svg){width="15"}](../assets/images/tmp.webp){.glightbox}

    - Hvilket NAV-kontor som ønsker å betale
    - Navn og kontaktinformasjon til saksbehandler i NAV
    - Inntakskonsulentens initialer og dato

    Initialer og dato gjør at skolen vet hvem på Servicesenteret de kan kontakte ved spørsmål.

    Informasjonen i feltet overføres til *Merknad* i SPR når søknaden overføres.

## Registrere betalingsinstans og kontaktinformasjon

1. [Filtrer frem deltaker](../felles/guide.md#filtrere-i-sits) i skjermbildet *STU* [![bilde](../assets/images/gallery.svg){width="15"}](../assets/images/meny_skjermbilde.webp){.glightbox}

2. Sett feltet *Tiltak* til NAV

3. Velg deltakers NAV-kontor i feltet *Betalingsinstans* [![bilde](../assets/images/gallery.svg){width="15"}](../assets/images/tmp.webp){.glightbox}

    ??? tip "Hvor finner jeg fakturaadresse til NAV-kontoret?"

        Etter at NAV-kontoret er registrert i *Betalingsinstans* kan du klikke deg inn i feltet for å finne mer informasjon om NAV-kontoret, som postadresse, fakturaadresse og bankkonto.

    ??? warning "Ikke registrer deltakers saksbehandler på kortet for betalingsinstans"

        Det kan være flere saksbehandlere som kjøper opplæring ved samme NAV-kontor.

        Kontaktinformasjon på kortet for betalingsinstans kan evt. tilhøre den som behandler fakturaer ved NAV-kontoret, og må i så fall vedlikeholdes.

        Informasjon om deltakers saksbehandler skal ligge i SPR og SAD.

4. [Filtrer frem deltaker](../felles/guide.md#filtrere-i-sits) i skjermbildet *SAD* [![bilde](../assets/images/gallery.svg){width="15"}](../assets/images/meny_skjermbilde.webp){.glightbox}

5. Fyll inn e-post og telefonnummer til deltakers saksbehandler i feltet *NAV e-post mobil* [![bilde](../assets/images/gallery.svg){width="15"}](../assets/images/tmp.webp){.glightbox}

    Informasjonen i dette feltet blir tilgjengelig for lærer i en rapport i e:Vision.

    Hvis kontaktinformasjonen endres må feltet i SAD oppdateres.

## Behandle SPR etter overføring av søknad

1. Overfør søknaden etter [rutine for overføring av søknad](../sese/overfør.md){.glightbox}

2. [Filtrer frem deltaker](../felles/guide.md#filtrere-i-sits) i skjermbildet *SPR* [![bilde](../assets/images/gallery.svg){width="15"}](../assets/images/meny_skjermbilde.webp){.glightbox}

3. Sett *SPR status* til LN (SØKT INN AV NAV) i stedet for L5/L6 eller L1/L2 [![bilde](../assets/images/gallery.svg){width="15"}](../assets/images/tmp.webp){.glightbox}

    Hvis *Tiltak* er satt til NAV i STU vil dette automatisk overføres til *Tiltak* i SPR. Informasjon om NAV-kontoret og saksbehandler kommer fra ACD til feltet *Merknad*.

??? tip "Hvordan finner jeg deltakere som får opplæring betalt av NAV?"

    I SPR kan deltakerkontoret filtrere på *SPR status* LN og/eller *Tiltak* NAV for å finne aktuelle deltakere.

    Detaljer om kjøp av timer, ønsket opplæring mm. skal ligge i deltakers mappe i WebSak.

## Registrere betalingsperiode og generere tilbudsbrev

Skolen avtaler med bydelen hvor mange kursperioder NAV skal betale for.

1. [Filtrer frem deltaker](../felles/guide.md#filtrere-i-sits) i skjermbildet *SPR* [![bilde](../assets/images/gallery.svg){width="15"}](../assets/images/meny_skjermbilde.webp){.glightbox}

2. Sett feltet *Skyss/SF/NAVBet* til den siste kursperioden NAV har godkjent å betale for [![bilde](../assets/images/gallery.svg){width="15"}](../assets/images/tmp.webp){.glightbox}

    P1 er første kursperiode i inneværende skoleår, og P6 er sjette kursperiode.

    ??? warning "Feltet må vedlikeholdes av skolen"

        Hvis NAV godkjenner betaling for flere kursperioder må feltet oppdateres.

    ??? tip "Feltet brukes også til andre formål"

        Feltet *Skyss/SF/NAVBet* brukes også til registrering av skyss i FOV og til samfunnskunnskap, men på andre SPR.

3. Generer [*NOVO TILBUD*](../felles/guide_pdf.md){.glightbox}

    Når det står NAV i feltet *Tiltak* i SPR vil betalingsinformasjonen i tilbudsbrevet tilpasses.

    ??? quote "Brukerinput for **NOVO TILBUD**"

        Endre *Sluttdato for betalingsperiode (ddmmåååå)* slik at den stemmer med siste kursperiode NAV har godkjent å betale for. [![bilde](../assets/images/gallery.svg){width="15"}](../assets/images/tmp.webp){.glightbox}

        Brevet vil automatisk beregne prisen for hele betalingsperioden.

## Fakturering

Skolene velger selv hvor ofte de vil fakturere NAV. Det kan f.eks. utstedes delfaktura etter hver avsluttet kursperiode, hvert halvår eller faktura for hele perioden til slutt.

Se også rutine N15 Registrering av betaling i SITS.

## Når NAV ikke lenger betaler for opplæringen

1. [Filtrer frem deltaker](../felles/guide.md#filtrere-i-sits) i skjermbildet *SPR* [![bilde](../assets/images/gallery.svg){width="15"}](../assets/images/meny_skjermbilde.webp){.glightbox}

2. Endre feltet *Tiltak* fra NAV til NAVS [![bilde](../assets/images/gallery.svg){width="15"}](../assets/images/tmp.webp){.glightbox}

    Dette vil fjerne NAV fra feltet *Tiltak* i STU.

3. Sluttfør deltaker etter [rutine for sluttføring](../felles/sluttføre.md){.glightbox}

    ??? question "Deltaker ønsker å betale for videre opplæring selv"

        Deltaker kan fortsette i opplæring på samme SPR ved å betale selv.