# Finn deltakere med utgående rett

Rapporten NOVO UTGNIR gir en oversikt over deltakere som nærmer seg eller har nådd de ytre grensene for gratis norskopplæring etter introduksjonsloven:

- 2950 tilbudte norsktimer
- 5-årsfristen
- 67 år

## Finne deltakere med utgående rett

1. [Filtrer frem senteret](../felles/guide.md#filtrere-i-sits) i skjermbildet *SCL* [![bilde](../assets/images/gallery.svg){width="15"}](../assets/images/meny_skjermbilde.webp){.glightbox}

2. Generer [*NOVO UTGNIR*](../felles/guide_pdf.md){.glightbox}

3. Se gjennom rapporten [![bilde](../assets/images/gallery.svg){width="15"}](../assets/images/tmp.webp){.glightbox}

    Rapporten viser deltakere som:

    - Har fått tilbud om mer enn 2850 norsktimer (har færre enn 100 timer igjen)
    - Har to måneder eller mindre igjen til 5-årsfristen går ut
    - Har to måneder eller mindre igjen til de fyller 67 år

    ??? question "Hva regnes som tilbudte timer?"

        Tilbudte timer er summen av deltatte timer og ugyldig fravær.

    Rapporten sorterer på *Status*, med AP øverst. Det er disse deltakerne som er aktive og skal varsles.

    ??? question "Hvorfor kommer deltakere med status BR, LA og SL med i rapporten?"

        Rapporten brukes også til å finne NIR-SPR som ikke er satt til FF etter at retten til gratis norskopplæring har gått ut.

        Se [rutine for sluttføring av deltaker ved utgått rett](../norsk/utgått_rett.md){.glightbox}.

        SPR med status FF kommer ikke med i rapporten.

    ??? question "Hvorfor kommer samme deltaker med flere ganger?"

        Hvis deltaker har endret rettighet underveis i opplæringen, f.eks. fra REPL til RETT eller fra REPL til PLIKT pga. utgått 3-årsfrist, kan flere NIR-SPR komme med i rapporten.

        Deltaker kan da komme med én gang med status AP på aktiv SPR, og én eller flere ganger med status BR eller SL på tidligere SPR.

4. Vurder hvilken grense deltaker er i ferd med å nå, eller allerede har nådd.

    | Felt i rapporten | Hva du skal sjekke |
    | --- | --- |
    | Alder og Født | Hvis deltaker er 66 eller 67 år, sjekk fødselsdatoen for når deltaker fyller eller fylte 67 år. |
    | 5-årsfrist | Sjekk om fristen nærmer seg eller allerede har gått ut. Rapporten sorterer med eldste frist først innenfor hver status. |
    | Gjenst. timer | Sjekk om deltaker har færre enn 100 timer igjen, eller allerede har minustimer. |

    ??? warning "Deltaker nærmer seg flere av grensene"

        Vurder hvilken av grensene deltaker når først. Dette avgjør hvilken begrunnelse du skal bruke i varselsbrevet.

    ??? warning "Deltaker har nådd målet for norskopplæringen"

        Deltakere som har nådd målet for norskopplæringen fanges ikke opp av NOVO UTGNIR på grunnlag av nådd nivå.

        Se [rutine for sluttføring av deltaker ved utgått rett](../norsk/utgått_rett.md){.glightbox}.

## Varsle deltaker om utgående rett

1. Sjekk feltet *Varselbrev* i NOVO UTGNIR.

    Her vises arkiveringsdatoen for siste NOVO STAVAR.

    ??? warning "Deltaker har allerede fått et varselsbrev"

        NOVO STAVAR brukes også til å varsle om andre grenser for gratis opplæring.

        Hvis deltaker har fått et brev tidligere, sjekk at brevet gjelder det du skal varsle om nå. Hvis brevet gjelder noe annet må du sende et nytt varselsbrev.

        Se [oversikt over brev til deltaker](../norsk/oversikt_brev.md){.glightbox}.

2. [Filtrer frem deltaker](../felles/guide.md#filtrere-i-sits) i skjermbildet *SPR* [![bilde](../assets/images/gallery.svg){width="15"}](../assets/images/meny_skjermbilde.webp){.glightbox}

    Ta utgangspunkt i norsk-SPR deltaker er aktiv på.

3. Generer [*NOVO STAVAR*](../felles/guide_pdf.md){.glightbox}

    ??? quote "Brukerinput for **NOVO STAVAR**"

        Velg riktig begrunnelse i første boks [![bilde](../assets/images/gallery.svg){width="15"}](../assets/images/tmp.webp){.glightbox}.

        | Begrunnelse | Verdi |
        | --- | --- |
        | 5-årsfrist | 5 |
        | 3000 timer | 3000 |
        | 67 år | 67 |

        Merk at verdien 3000 brukes selv om grensen for tilbudte norsktimer er 2950.

## Følge opp varslingen

Med varselsbrevet får deltaker en frist på 14 dager til å dokumentere at forholdene det er varslet om er feil.

??? question "Deltaker mener den har flere timer igjen"

    Hvis deltaker har mye ugyldig fravær kan det være grunnen til at deltaker har færre timer igjen enn forventet.

    Generer [*NOVO TIMBEK*](../felles/guide_pdf.md){.glightbox} med fravær for å vise deltaker dette.

??? tip "Deltaker ønsker å fortsette mot betaling"

    Noter dette slik at deltaker ikke får et opphold i norskopplæringen når retten går ut.

Kjør NOVO UTGNIR jevnlig for å følge med på:

- Når varselsbrevet ble sendt
- Hvor mange av de 2950 timene som gjenstår
- Hvor lang tid det er igjen til 5-årsfristen går ut
- Når deltaker fyller 67 år

Når det er ca. én uke igjen til deltaker når en av grensene skal sluttbrevet NOVO STAVED sendes.

Se [rutine for sluttføring av deltaker ved utgått rett](../norsk/utgått_rett.md){.glightbox} for videre behandling.

## Kontrollere deltatte timer

For at NOVO UTGNIR skal vise riktig antall gjenstående timer må alle deltatte norsktimer være registrert i SPRS.

Norsktimer fra og med 2007 er registrert automatisk. Timer fra før 2007 og timer fra andre kommuner som man finner i NiR skal ligge i feltet *SATS/NIR/ Utenbys timer* i SPRS-UDF.

Hvis disse timene ikke er registrert fra før må du etterregistrere dem.

1. [Filtrer frem deltaker](../felles/guide.md#filtrere-i-sits) i skjermbildet *SPRS* [![bilde](../assets/images/gallery.svg){width="15"}](../assets/images/meny_skjermbilde.webp){.glightbox}

2. Klikk på *UDF*-knappen [![bilde](../assets/images/gallery.svg){width="15"}](../assets/images/meny_udf.webp){.glightbox}

3. Registrer timene i feltet *SATS/NIR/ Utenbys timer* [![bilde](../assets/images/gallery.svg){width="15"}](../assets/images/tmp.webp){.glightbox}

4. Klikk på *Apply*

Timene teller med i *Deltatte timer* og reduserer *Gjenstående* tilsvarende.