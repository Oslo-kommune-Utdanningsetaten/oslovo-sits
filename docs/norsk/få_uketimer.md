# Behandle deltakere som ønsker få uketimer

For deltakere med en kort frist for å nå norskmålet sitt er det viktig å dokumentere hvorfor de evt. får tilbud om få uketimer. Kommunen skal tilby norskopplæring i tilstrekkelig omfang til at deltaker kan nå norskmålet innen fristen.

Et tilbud med færre enn 16 uketimer er ikke nødvendigvis utilstrekkelig. For mange deltakere er 8 timer i uka et passende tilbud.

Deltakers ønsker om tid og omfang registreres i SITS slik at de kan dokumenteres i søknadsbekreftelsen og senere i tilbudsbrevet.

## Registrere ønsker om tid og omfang på Servicesenteret

Ved [registrering av søknad](../sese/ny_acd.md){.glightbox} i ACD skiller vi mellom det deltaker helst ønsker og det som er mulig for deltaker.

1. Fyll inn *Tid (MOA)* med det videste tilbudet som er mulig for deltaker.

2. Klikk på *UDF*-knappen [![bilde](../assets/images/gallery.svg){width="15"}](../assets/images/meny_udf.webp){.glightbox}

3. Fyll inn *Tid/omfang første prioritet* (UDF3) med det mest spesifikke ønsket til deltaker, f.eks. en bestemt økt, et bestemt antall uketimer eller bestemte ukedager. [![bilde](../assets/images/gallery.svg){width="15"}](../assets/images/tmp.webp){.glightbox}

    ??? question "Deltaker kan ikke ta imot andre tilbud enn førsteprioriteten"

        Hvis deltaker f.eks. bare har mulighet til å gå på kveld 8 timer i uka, setter du *Tid (MOA)* til NK-08.

        Du trenger da ikke å fylle ut UDF3 med samme kode.

        Skriv gjerne en merknad i feltet *SPR* i ACD om hvorfor deltaker ikke kan ta imot andre tilbud.

    ??? question "Deltaker foretrekker få uketimer, men kan ta imot andre tilbud"

        Hvis deltaker f.eks. foretrekker 8 timer på kveld, men også har mulighet til å gå på dagtid, kan du sette *Tid (MOA)* til NDK og UDF3 til NK-08.

        Skriv gjerne en merknad i feltet *SPR* i ACD om hva som er drøftet med deltaker.

        Skolen kan da vurdere om deltaker bør få et mer intensivt tilbud, f.eks. hvis deltaker har kort frist for å nå norskmålet sitt.

    ??? warning "Deltaker ønsker opplæring i engelsk eller både norsk og engelsk"

        For deltakere fra Ukraina i introduksjonsprogram som har ENG eller N+ENG i *Tid (MOA)*, er det spesielt viktig å fylle ut UDF3. Kodene ENG og N+ENG sier ikke noe om ønsket tid eller omfang.

        Hvis deltaker ønsker opplæring i begge språkene, kan du registrere ønsket samlet omfang av opplæringen i begge språkene.

        Hvis deltaker senere skal gå over til bare norskopplæring, kan skolen bruke det som står i UDF9 i SPR når *Tid (MOA)* skal endres.

        Se også [rutine for kollektiv beskyttelse](../norsk/ukraina.md){.glightbox}

4. Klikk på *Apply* og lagre.

Ønsket om tid og omfang kommer ut som førsteprioritet i søknadsbekreftelsen NSER ENDSOK eller NSER ENDSOKE.

Registrering av deltakers ønsker forplikter ikke skolen til å gi deltaker akkurat det tilbudet den ønsker.

### Overføring av ønsker fra ACD til SPR

Ved [overføring av søknad](../sese/overfør.md){.glightbox} via ATR overføres opplysninger om tid og omfang automatisk til SPR.

| Fra ACD | Til SPR |
| --- | --- |
| Tid (MOA) | Tid (MOA) |
| UDF3 - Tid/omfang første prioritet | UDF9 - Tid/omfang første prioritet |
| Overføringsdato | UDFA - Tid/omfang oppdatert |
| SPR (merknadsfelt) | Merknad |

Hvis UDF3 i ACD er tomt, overføres verdien fra *Tid (MOA)* til UDF9 i SPR. Det vil da stå samme kode i *Tid (MOA)* og UDF9 i SPR.

UDF9 og UDFA må ses i sammenheng. Datoen i UDFA viser når deltaker hadde ønsket som står i UDF9.

**Eksempel: Deltaker ønsker helst 12 timer i uka på dagtid, økt 2**

| Felt | ACD | SPR |
| --- | --- | --- |
| Tid (MOA) | ND | ND |
| Tid/omfang første prioritet | ND2-12 (UDF3) | ND2-12 (UDF9) |

[![bilde](../assets/images/gallery.svg){width="15"}](../assets/images/tmp.webp){.glightbox}

??? question "Deltaker søker norskopplæring på nytt på Servicesenteret"

    Det lages en ny søknad i ACD og en ny søknadsbekreftelse.

    Søknaden overføres med [*NSER OVERF*](../felles/guide_pdf.md){.glightbox}. Tid (MOA), UDF9 og UDFA i SPR blir oppdatert på samme måte som ved overføring via ATR.

    Hvis deltaker har endret rettighet, må det lages en ny SPR før søknaden overføres.

    Se [rutine for endring av rettigheter](../felles/endre_rett.md){.glightbox}

## Endre deltakers ønsker om tid og omfang

Skolen gir vanligvis tilbud ut fra det som står i *Tid (MOA)* i SPR, og hvis mulig ut fra deltakers førsteprioritet i UDF9.

Hvis deltaker endrer ønsker om tid eller omfang, enten før eller etter oppstart, må den som tar imot beskjeden oppdatere dette i SPR.

1. [Filtrer frem deltaker](../felles/guide.md#filtrere-i-sits) i skjermbildet *SPR* [![bilde](../assets/images/gallery.svg){width="15"}](../assets/images/meny_skjermbilde.webp){.glightbox}

2. Klikk på *UDF*-knappen [![bilde](../assets/images/gallery.svg){width="15"}](../assets/images/meny_udf.webp){.glightbox}

3. Endre *Tid/omfang første prioritet* (UDF9) til koden som tilsvarer deltakers nye ønske. [![bilde](../assets/images/gallery.svg){width="15"}](../assets/images/tmp.webp){.glightbox}

    ??? warning "Bruk en kode som spesifiserer antall uketimer"

        Hvis du bare bruker NK eller ND, kan vi ikke dokumentere i tilbudsbrevet at deltaker selv har ønsket få uketimer.

        På kveldstid bør du velge en kode som spesifiserer antall uketimer.

        På dagtid er det viktig å velge en slik kode hvis deltaker ønsker færre enn 16 uketimer.

        Eksempler på koder:

        | Kode | Tid og omfang |
        | --- | --- |
        | NK-08 | Kveld, 8 timer per uke |
        | NK-12 | Kveld, 12 timer per uke |
        | NK3 | Kveld mandag og onsdag, 8 timer per uke |
        | NK4 | Kveld tirsdag og torsdag, 8 timer per uke |
        | ND-08 | Dag, 8 timer per uke |
        | ND-12 | Dag, 12 timer per uke |
        | ND2-12 | Dag økt 2, 12 timer per uke |
        | NDK-12 | Dag eller kveld, 12 timer per uke |

4. Klikk på *Apply* og lagre.

    Ved lagring oppdateres *Tid/omfang oppdatert* (UDFA) automatisk med dagens dato.

5. Klikk på *UDF*-knappen igjen og kontroller at UDF9 og UDFA er riktig utfylt.

    ??? question "Deltaker ga beskjed om nytt ønske på en annen dato"

        Endre *Tid/omfang oppdatert* (UDFA) til datoen da deltaker ga beskjed om sitt nye ønske.

        Klikk på *Apply* og lagre.

## Dokumentere ønsker om få uketimer i tilbudsbrevet

1. [Filtrer frem deltaker](../felles/guide.md#filtrere-i-sits) i skjermbildet *SPR* [![bilde](../assets/images/gallery.svg){width="15"}](../assets/images/meny_skjermbilde.webp){.glightbox}

2. Klikk på *UDF*-knappen og kontroller at *Tid/omfang første prioritet* (UDF9) og *Tid/omfang oppdatert* (UDFA) er riktig utfylt.

3. Generer [*NOVO TILBUD*](../felles/guide_pdf.md){.glightbox}

4. Kontroller avsnittet *Omfang av tilbudet* i tilbudsbrevet.

    Antall uketimer i tilbudet oppgis for alle deltakere.

    For deltakere som er omfattet av integreringsloven, har en frist og får tilbud om færre enn 16 uketimer, oppgis i tillegg det registrerte ønsket om tid og omfang og datoen da ønsket ble registrert.

    **Eksempel:**

    > **Omfang av tilbudet**
    >
    > Tilbudet har 12 undervisningstimer per uke.
    >
    > Vi noterte 18.03.2022 at du ønsker tilbud på: Kveld, 12 timer per uke.

    ??? question "Hvorfor kommer ikke deltakers ønske med i tilbudsbrevet?"

        Kontroller at UDF9 inneholder en kode som spesifiserer omfanget, og at UDFA er riktig utfylt.

        Deltakers ønsker om tid og omfang kommer ikke med hvis:

        - Tilbudet har 16 uketimer eller mer
        - Deltaker ikke er omfattet av integreringsloven
        - Deltaker ikke har en frist
        - Deltaker er i introduksjonsprogram
        - Deltaker får tilrettelagt norskopplæring

        For deltakere i introduksjonsprogram er omfanget av norskopplæringen avklart med bydelen.

Se også [oversikt over brev til deltaker](../norsk/oversikt_brev.md){.glightbox}

## Deltaker endrer rettighet fra BETAL/PLIKT til REPL

Deltakere som må betale for norskopplæring, har ofte valgt et tilbud med få uketimer. Når deltaker får rett og plikt til gratis norskopplæring, må vi avklare på nytt hva deltaker ønsker av tid og omfang.

Dette gjelder både aktive deltakere og deltakere på søkerliste som går på eller venter på et tilbud med få uketimer.

Selve endringen av rettighet gjøres etter [rutine for endring av norsk-rettighet](../norsk/endre_norskrett.md){.glightbox}

1. Snakk med deltaker om muligheten for å få tilbud om flere uketimer nå som deltaker har fått rett til gratis opplæring og en frist.

    Bruk gjerne [*NOVO VEDTAK*](../felles/guide_pdf.md){.glightbox} i samtalen. Der står det hvilket norskmål deltaker skal nå og informasjon om fristen.

2. [Filtrer frem deltaker](../felles/guide.md#filtrere-i-sits) i skjermbildet *SPR* [![bilde](../assets/images/gallery.svg){width="15"}](../assets/images/meny_skjermbilde.webp){.glightbox}

3. Klikk på *UDF*-knappen på SPR med rettighet REPL. [![bilde](../assets/images/gallery.svg){width="15"}](../assets/images/meny_udf.webp){.glightbox}

4. Fyll inn *Tid/omfang første prioritet* (UDF9) med tid og omfang som deltaker nå ønsker.

    Hvis deltaker fortsatt ønsker samme tid og omfang, kan du la den gamle koden stå.

5. Sett *Tid/omfang oppdatert* (UDFA) til datoen da du snakket med deltaker om tid og omfang. [![bilde](../assets/images/gallery.svg){width="15"}](../assets/images/tmp.webp){.glightbox}

    ??? warning "Datoen må oppdateres selv om deltaker ikke endrer ønske"

        Vi må kunne dokumentere at deltaker har ønsket få uketimer også etter å ha fått rett til gratis opplæring.

6. Klikk på *Apply* og lagre.

7. Generer nytt [*NOVO TILBUD*](../felles/guide_pdf.md){.glightbox} hvis deltaker får eller fortsetter på et tilbud med færre enn 16 uketimer.

    Det lages nytt tilbudsbrev selv om deltaker fortsetter på samme kurs. Hensikten er ikke å innkalle deltaker på nytt, men å dokumentere deltakers ønsker etter endring av rettighet.

    Hvis deltaker fortsetter på et kurs med minst 16 uketimer, trenger du ikke å lage nytt tilbudsbrev.

??? question "Deltaker ønsker flere uketimer senere, men vil foreløpig fortsette på samme kurs"

    1. Sett *SPR status* til LA.

    2. Klikk på *UDF*-knappen og oppdater *Tid/omfang første prioritet* (UDF9) til det deltaker ønsker fremover, f.eks. ND-16 for dagtid med 16 uketimer.

    3. Kontroller at *Tid/omfang oppdatert* (UDFA) viser datoen da ønsket ble satt frem.

    4. Klikk på *Apply* og lagre.

    Koden ND-16 kan også legges inn i *Tid (MOA)* foran i SPR.

    Vær oppmerksom på at hvis deltaker senere får et tilbud med færre enn 16 uketimer, vil tilbudsbrevet vise at deltaker har ønsket et tilbud med flere uketimer.

## Tilrettelagt norskopplæring

Deltakere som ikke kan nyttiggjøre seg ordinær norskopplæring, kan få tilrettelagt norskopplæring på NNIR-SPR med rettighet REPL42, RETT42, PLIK42 eller evt. ASYL42.

Disse deltakerne velger ikke selv tid og omfang på samme måte som deltakere i ordinær norskopplæring.

Omfanget av opplæringen fremgår som oftest av [*SOVO VEDTAK*](../felles/guide_pdf.md){.glightbox}, som også beskriver hvordan opplæringen skal tilrettelegges og viser til sakkyndig vurdering.

Hvis det er behov for å bruke [*NOVO TILBUD*](../felles/guide_pdf.md){.glightbox}, f.eks. som supplement til vedtaket eller ved oppstart før det foreligger en sakkyndig vurdering, tilpasses brevet når *Kursnivå* i SPR er S.

Tilbudsbrevet får da overskriften *Tilbud om tilrettelagt opplæring i norsk*.

Antall uketimer oppgis i tilbudsbrevet, men deltakers ønsker om tid og omfang og avsnittet om frist for gratis opplæring kommer ikke med.

??? warning "Deltaker får norskopplæring i og på tegnspråk ved Skullerud"

    For disse deltakerne finnes det en egen variant av NOVO TILBUD.

    Forutsetningen er at følgende felt i SPR er utfylt:

    | Felt | Verdi |
    | --- | --- |
    | Kursnivå | S |
    | Avdeling | STO1 |

    Tilbudsbrevet får overskriften *Tilbud om opplæring i norsk, i og på tegnspråk*.

    I denne varianten av tilbudsbrevet oppgis også fristen for gratis språkopplæring.