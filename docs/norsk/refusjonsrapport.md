# Kjøre refusjonsrapporter

Det er i hovedsak to typer refusjonsrapporter: rapporter for deltakertimer (DTIME) og rapporter for undervisningstimer (UTIME).

De mest aktuelle rapportene for refusjon er *NOVO UTIME5* og *NOVO DTIME5R*.

## Forutsetninger

Rapportene baserer seg på informasjon fra EVE, EVA, EVI, DAR og SPR.

Alle timer beregnes ut fra hvilket VO-senter undervisningen faktisk har foregått på. Dette hentes fra feltet *VO senter* (UDF3) på EVE.

??? warning "Kurs mangler lokalisering"

    Det må være en verdi i feltet *Lokalisering* på EVE for at kurset skal komme med i DTIME-rapportene.

??? warning "Lærer har ikke ført fravær"

    Hvis lærer ikke har ført fravær vil rapportene telle timene som om deltaker var til stede.

    Beregning av deltatte timer baserer seg på totalt planlagte timer minus gyldig fravær.

    Se [rutine for føring av fravær](../felles/føre_fravær.md){.glightbox}.

??? warning "Rapporten inneholder timer som ikke er heltall"

    Dette kan skyldes at det er ført deltimer på fravær. Gå gjennom DAR for å finne feil i fraværsføringen.

??? tip "Kontroller informasjon på kursene"

    Alle kurs skal ha nødvendig informasjon fylt ut i EVE. Sjekk spesielt følgende felt:

    | | |
    | --- | --- |
    | Kurstype | EVE_UDFB.EVE |
    | Uketimer | EVE_VERN.EVE |

## Hente ut undervisningstimer - NOVO UTIME5

Rapporten viser undervisningstimer for alle skoleslag, både norskkurs, FOV og samfunnsfagkurs.

Før 2025 ble rapporten *NOVO UTIME4* brukt til dette.

1. Gå til skjermbildet *EVE* [![bilde](../assets/images/gallery.svg){width="15"}](../assets/images/meny_skjermbilde.webp){.glightbox}

2. [Filtrer frem kursene](../felles/guide.md#filtrere-i-sits) ved å fylle inn ønsket skoleår og *VO senter* i UDF [![bilde](../assets/images/gallery.svg){width="15"}](../assets/images/meny_udf.webp){.glightbox}

3. Generer [*NOVO UTIME5*](../felles/guide_pdf.md){.glightbox} fra *All*

    ??? quote "Brukerinput for **NOVO UTIME5**"

        <div class="srl-table" markdown="1">

        | | | |
        | --- | --- | --- |
        | Startdato | <span>*ddmmyyyy*</span> | Første dato i perioden (f.eks. 01012025) |
        | Sluttdato | <span>*ddmmyyyy*</span> | Siste dato i perioden |

        </div>

4. [Kopier rapporten til Excel](#kopiere-rapport-til-excel) hvis du ønsker å bearbeide den videre

    ??? tip "Jeg vil bare se timer for ett skoleslag eller en kurstype"

        Etter at rapporten er kopiert til Excel kan du bruke kolonnen *Fag* til å skille ut de fagene du ønsker å se.

        Rapporten har også en egen kolonne for kurstype som du kan sortere på.

## Hente ut deltakertimer - NOVO DTIME5R

Rapporten viser totale deltakertimer per program, spor, rettighet og lokalisering for et VO-senter, samt summen av undervisningsøkter for kursene som er talt.

Rapporten brukes som grunnlag for refusjon av deltakertimer, og for å vise kurs som er unntatt fra aktivitetsplanen. Kurstype vises i kolonnen helt til høyre.

Før 2025 ble rapporten *NOVO DTIME4R* brukt til dette.

1. [Filtrer frem senteret](../felles/guide.md#filtrere-i-sits) i skjermbildet *SCL* [![bilde](../assets/images/gallery.svg){width="15"}](../assets/images/meny_skjermbilde.webp){.glightbox}

    Bruk en av senterkodene ROS, SME, SKU eller SER.

2. Generer [*NOVO DTIME5R*](../felles/guide_pdf.md){.glightbox} fra *Current*

    ??? quote "Brukerinput for **NOVO DTIME5R**"

        <div class="srl-table" markdown="1">

        | | | |
        | --- | --- | --- |
        | Startdato | <span>*ddmmyyyy*</span> | Første dato i perioden |
        | Sluttdato | <span>*ddmmyyyy*</span> | Siste dato i perioden |
        | Type timer | N / E / S | Norsktimer (N), engelsktimer (E) eller samfunnsfagtimer (S) |

        </div>

        Du må rulle ned for å komme til feltet der du velger type timer. [![bilde](../assets/images/gallery.svg){width="15"}](../assets/images/tmp.webp){.glightbox}

    ??? warning "Sjekk hvilken type timer du tar ut rapport for"

        N er standardinnstilling når du logger inn i SITS.

        SITS husker sist valgte verdi frem til du logger ut eller kjører en annen type rapport.

3. Rapporten forhåndsvises i nettleseren. Lagre rapporten på din maskin eller [kopier rapporten til Excel](#kopiere-rapport-til-excel) for videre behandling

    ??? tip "Jeg vil hente frem en rapport jeg har generert tidligere"

        Rapportene arkiveres og kan hentes frem igjen fra *Current* ⇒ *View Generated Letters* i SCL.

        Du kan bare hente frem rapporter for ett senter om gangen.

??? tip "Samlet oversikt over deltakertimer og aktiviteter"

    Rapporten [*NOVO DTIME4*](../felles/guide_pdf.md){.glightbox} kan genereres fra SCL, og gir en samlet oversikt over deltakertimer og aktiviteter for hvert VO-senter.

    Denne rapporten kjøres vanligvis sentralt for alle skolene.

    Undervisningsøkter er summen av økter for alle kursene som er talt, mens timer er deltakertimer.

## Kontrollere timer for en deltaker - NOVO TIMETO

Rapporten viser totale timer for en deltaker fordelt på VO-senter, og kan brukes til å kontrollere deltakers timer.

1. [Filtrer frem deltaker](../felles/guide.md#filtrere-i-sits) i skjermbildet *SPR* [![bilde](../assets/images/gallery.svg){width="15"}](../assets/images/meny_skjermbilde.webp){.glightbox}

    Du kan også filtrere frem flere SPR hvis du ønsker å se timer for flere deltakere.

2. Generer [*NOVO TIMETO*](../felles/guide_pdf.md){.glightbox} fra *Current* for den SPR som vises på skjermen, eller fra *All* for alle SPR du har filtrert frem

    ??? quote "Brukerinput for **NOVO TIMETO**"

        <div class="srl-table" markdown="1">

        | | | |
        | --- | --- | --- |
        | Skoleår | <span>*skoleår*</span> | Inneværende skoleår er standardinnstilling |
        | Startdato | <span>*ddmmyyyy*</span> | Første dato i perioden |
        | Sluttdato | <span>*ddmmyyyy*</span> | Siste dato i perioden |
        | Norwegian Hours (N) or Social Science Hours (S)? | N / S | Norsktimer (N) eller samfunnsfagtimer (S) |

        </div>

        Du må rulle ned for å komme til feltet der du velger type timer. [![bilde](../assets/images/gallery.svg){width="15"}](../assets/images/tmp.webp){.glightbox}

    ??? warning "Sjekk hvilken type timer du tar ut rapport for"

        N er standardinnstilling når du logger inn i SITS.

        SITS husker sist valgte verdi frem til du logger ut eller kjører en annen type rapport.

3. Rapporten forhåndsvises i nettleseren. Lagre rapporten på din maskin eller [kopier rapporten til Excel](#kopiere-rapport-til-excel) for videre behandling

## Hente ut timer for deltakere fra andre kommuner - FOVO UTENBY

Rapporten viser totalt antall undervisningstimer, og brukes som grunnlag for refusjon av undervisningstimer for deltakere fra andre kommuner.

1. [Filtrer frem deltakerne](../felles/guide.md#filtrere-i-sits) i skjermbildet *SPRS* [![bilde](../assets/images/gallery.svg){width="15"}](../assets/images/meny_skjermbilde.webp){.glightbox}

    En mulig kombinasjon er å filtrere på VO-senter og sluttdato større enn startdato for inneværende skoleår.

    Se [avansert filtrering](../felles/avansert_filtrering.md) for filtrering på datoer.

2. Generer [*FOVO UTENBY*](../felles/guide_pdf.md){.glightbox} (FE UTENBY ELEV) fra *All*

## Kopiere rapport til Excel

Rapportene kan kopieres over til Excel for videre bearbeiding.

1. Trykk *Ctrl*+*A* i rapporten for å markere hele teksten

2. Trykk *Ctrl*+*C* for å kopiere

3. Gå til Excel og trykk *Ctrl*+*V* for å lime inn

## Månedlige refusjonsrapporter

??? note "SITS Forvaltning"

    *NOVO UTIME5* og *NOVO DTIME5R* produseres månedlig etter initiativ fra økonomiavdelingen rett etter månedsskiftet.

    Det lages normalt ikke rapporter for juni, juli og desember. Det lages i stedet rapporter for følgende perioder:

    | Periode | Dato fra | Dato til | Rapport kjøres |
    | --- | --- | --- | --- |
    | 1. halvår | 01.01 | 31.07 | Begynnelsen av august |
    | 2. halvår | 01.08 | 31.12 | Begynnelsen av januar |

    **Før generering av rapportene**

    1. Kontroller at det ikke er ført deltimer på fravær i DAR

    2. Kontroller at nødvendig informasjon er fylt ut på alle kurs i EVE, spesielt *Kurstype* og *Uketimer*

    3. Ta kontakt med aktuelle VO-sentre hvis det er mangler eller feil som må rettes i EVE

    **NOVO UTIME5**

    Kopier rapporten til Excel og legg hvert VO-senter på eget ark.

    **NOVO DTIME5R**

    Hent ut rapporter for følgende sentre og typer timer:

    | VO-senter | Type timer |
    | --- | --- |
    | SKU | N |
    | SME | N |
    | ROS | N |
    | SER | S |

    Legg hvert VO-senter på eget ark i Excel. Sorter på kurstype på hvert ark og marker de forskjellige kurstypene med farger for lesbarhet.

    **Lagring og oversending**

    Rapporter formatteres som tidligere rapporter og lagres på SITS-området under *Økonomirapporter/åååå-mm*.

    Rapportene sendes til Geir Brendlien innen gitt frist.