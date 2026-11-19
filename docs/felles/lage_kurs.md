# Lage og slette kurs

## Lage fagtilgjengelighet

??? warning "Jeg vil bare lage kurs for FEIDE-tilgang"

    Da følger du rutinen som beskrevet, men bruker fagkode "FEIDE" og kurstype "FE".
    Disse deltakerne skal ha program "NBET" og rettighet "URETT"

=== "Helt ny fagtilgjengelighet"

    1. Gå til **MAV** og trykk **File** ⇒ **Add** [![bilde](../assets/images/gallery.svg){width="15"}](../assets/images/tmp.webp){.glightbox}
    2. Fyll inn **MAV** [![bilde](../assets/images/gallery.svg){width="15"}](../assets/images/tmp.webp){.glightbox}

        ??? quote "Hvordan fylle ut **MAV**"

            | Fagkode (MOD) | Forekomst | År | Periode | Status | ST | SL | PS | StU | SlU | D | Tid | Lokalisering | MAC | Vurd.mønster | Vurd.skj | TOC | ADM ansvarlig | Module Tutor 2 | Mål | Eleve | Min |
            | ------------- | --------- | -- | ------- | ------ | -- | -- | -- | --- | --- | - | --- | ------------ | --- | ------------ | -------- | --- | ------------- | -------------- | --- | ----- | --- |
            | Fagkoden du ønsker | Forekomstkode brukt av senter | Skoleår for kurset | AA | A | Y | Y | 1 | 4 | 47 |  |  | HHV lokaliseringskode |  |  |  |  | Ditt brukernavn |  | 30 for en EVE, 60 for 2 osv. |  |  |

    2. Lagre

=== "Basert på eksisterende fagtilgjengelighet"

    1. [Filtrer frem kurs du baserer på](../felles/guide.md#filtrere-i-sits) i skjermbildet *MAV*[![bilde](../assets/images/gallery.svg){width="15"}](../assets/images/meny_skjermbilde.webp){.glightbox}

    2. Fra toppmenyen går du til *File* ⇒ *Release* [![bilde](../assets/images/gallery.svg){width="15"}](../assets/images/meny_top.webp){.glightbox}

    3. Oppdater skoleår og evt. annen informasjon som har endret seg

    4. Fjern verdi i *TOC* hvis det står noe der og lagre

    5. Fyll inn *År* (skoleår) og *fag* i skjermbildet *RMA* [![bilde](../assets/images/gallery.svg){width="15"}](../assets/images/meny_skjermbilde.webp){.glightbox}

    6. Trykk på grønn pil ⇒ **Run**

    7. [Filtrer frem kurs du baserer på](../felles/guide.md#filtrere-i-sits) i skjermbildet *MAV*[![bilde](../assets/images/gallery.svg){width="15"}](../assets/images/meny_skjermbilde.webp){.glightbox}

1. Generer [*CREATE_TOC2*](../felles/guide_pdf.md){.glightbox}

2. Trykk *Ctrl*+*R* og se at det er kommet en verdi i feltet *TOC*

## Lage EVE

1. [Filtrer frem kurs du baserer på](../felles/guide.md#filtrere-i-sits) i skjermbildet *GEV*[![bilde](../assets/images/gallery.svg){width="15"}](../assets/images/meny_skjermbilde.webp){.glightbox}

    Følgende felt skal ha data som stemmer med MAV

    | Navn i GEV | Navn i MAV |
    | --- | --- |
    | Academic Year | År |
    | Period Slot | Periode |
    | Module | Fagkode (MOD) |
    | Module Oc. | ?? |

    *Date Range* skal ha datoer for kursperioden

2. Trykk *Generate*

3. Se gjennom beskjed om hvor mange MAV du lager EVE for og trykk *Continue* hvis det ser ok ut

    ??? warning "Det er mange MAV"

        Ser det mange ut kan det hende det er mangler i filtre, eller duplikate MAV.
        Trykk *cancel* og se gjennom, eller kontakt sits-ansvarlig hvis du er usikker.

4. Klikk på *View Messages* for å se hvor mange EVE du har generert

## Legge til en ekstra klasse/EVE med MAV og GEV

1. [Filtrer frem kurs du baserer på](../felles/guide.md#filtrere-i-sits) i skjermbildet *MAV*[![bilde](../assets/images/gallery.svg){width="15"}](../assets/images/meny_skjermbilde.webp){.glightbox}

2. Øk måltallet tilsvarende ekstra klasser du ønsker

    Husk at 30 = 1, 60 = 2 osv.

3. Gjør prosess over med å lage EVE igjen for oppdatert MAV

## Legge til en ekstra klasse/EVE med Modify Event 

1. Start med å finne fram kurset du vil lage en kopi av i EVE og klikk på  
Modify Event (MEV).  [![bilde](../assets/images/gallery.svg){width="15"}](../assets/images/modify_event_knapp.png){.glightbox}

I neste skjermbildet du får opp vil du se detaljer fra kurset til høyre i skjermbildet. Til venstre i skjermbildet kan du klikke på knappe Duplicate. Nå vil meldingslinja nederst vise: *1 events duplicated of which 0 clash.* Oppe i bilde vises det nye reg nummeret for kurset. Kurset blir først opprettet når du har klikket på knappen *Store.* Meldingslinja viser da *Events updated successfully* [![bilde](../assets/images/gallery.svg){width="15"}](../assets/images/modify_event_skjermbilde.png){.glightbox}



Husk også at når vi har flere kurs med samme skoleår, fag og forekomst så skal alle EVE'ene ha unike gruppe-ID. Det nye kurset som du lagde vil arve gruppe-ID fra kurset som du tok utgangspunkt i, og du må gi det en ny og unik gruppe-ID i skjermbildet EVE.

## Legge til kursøkter på EVE


Når du har et nygenerert kurs/EVE med metoden over, så vil den inneholde en kursøkt på en 
lørdag (dag 6) i SITS uke 4. Den kan du fjerne fra EVE ved å klikke på den doble pila ved 
kursøkten og i det neste skjermbildet velge *File* ⇒ *Delete* (evt Alt+D).

1. Trykk på *Ajourhold* [![bilde](../assets/images/gallery.svg){width="15"}](../assets/images/meny_ajourhold.webp){.glightbox}

    ??? quote "Brukerinput for Ajourhold"

    <div class="srl-table">

    |  |  |  |
    | -------------- | ----------------------------- | ---------- |
    | Period Week List | <span>*startuke-sluttuke,startuke-sluttuke*<</span> | SITS-ukene det skal legges til økter på. (f.eks. 4-9,11-20 gir undervisning fra uke 4  til 20 untatt uke 10|
    | Day list | <span>*dag*</span> | Dager det skal være undervisning (f.eks. 2 for tirsdag, eller 2,3 for tir-ons) |
    | Start time | <span>*tt:mm*</span> | Starttidspunkt (f.eks. 10:00) |
    | End time | <span>*tt:mm*</span> | Slutttidspunkt (f.eks. 12:00) |
    | Duration | <span>*tt:00*</span> | Varighet (skal alltid være i hele timer) |

    </div>

    ??? warning "Jeg vil ha forskjellig tid på forskjellige dager"

        Da kjører du Ajourhold to ganger,

    ??? warning "Det var allerede elever på kurset"

        Da må du sjekke at disse ikke kommer som aktive videre.

        1. [Filtrer frem kurs](../felles/guide.md#filtrere-i-sits) i skjermbildet *EVE*[![bilde](../assets/images/gallery.svg){width="15"}](../assets/images/meny_skjermbilde.webp){.glightbox}

        2. Fra toppmenyen går du til *Other* ⇒ *Students* [![bilde](../assets/images/gallery.svg){width="15"}](../assets/images/meny_top.webp){.glightbox}

        3. Fjern markering (grønn) for uker deltakere ikke skal være aktive på.

        4. lagre

## Fjerne kursøkter

Prosess fjerner ikke bare selve kursøkten, men også eventuelle rom-, lærer- og deltakertimer som var knyttet til denne kursøkten. 

1. [Filtrer frem kurs](../felles/guide.md#filtrere-i-sits) i skjermbildet *EVI*[![bilde](../assets/images/gallery.svg){width="15"}](../assets/images/meny_skjermbilde.webp){.glightbox}

    ??? hint "Du kan filtrere på spesifikke ukedager"

        Skriv tall for ukedagen under *Dag*, så kommer bare de kursøktene opp.

2. Marker *EVI sekvensnummer* for hendelsen du ønsker å fjerne

3. Trykk *Alt*+*D* 

4. Trykk *Yes* hvis du er sikker

## Endre tid for kurs med Ajourhold

1. Legg til nye kurs med Legge til kursøkter på EVE

2. Fjern gamle kurs med Fjerne kursøkter

## Endre varighet for kurs

1. [Filtrer frem kurs](../felles/guide.md#filtrere-i-sits) i skjermbildet *EVI* [![bilde](../assets/images/gallery.svg){width="15"}](../assets/images/meny_skjermbilde.webp){.glightbox}

2. Endre varighet for en og en rad

    - Husk at varlighet alltid skal være i hele timer

3. Lagre


## Lage nytt kurs som er likt et eksisterende kurs

1. [Filtrer frem kurs du baserer på](../felles/guide.md#filtrere-i-sits) i skjermbildet *EVE*[![bilde](../assets/images/gallery.svg){width="15"}](../assets/images/meny_skjermbilde.webp){.glightbox}

2. Klikk på *Modify Event (MEV) [![bilde](../assets/images/gallery.svg){width="15"}](../assets/images/men_modify_event.webp){.glightbox}

3. Klikk på *Duplicate*

4. [Filtrer frem nytt kurs](../felles/guide.md#filtrere-i-sits) i skjermbildet *EVE* [![bilde](../assets/images/gallery.svg){width="15"}](../assets/images/meny_skjermbilde.webp){.glightbox}

5. Endre *Gruppe ID* til et unikt, høyere tall og lagre [![bilde](../assets/images/gallery.svg){width="15"}](../assets/images/eve_gruppe_id.webp){.glightbox}
