# Lage NiR vedtak

Fremgangsmåtene under gjelder førstevedtak på 300/600 timer og behovsprøvde vedtak.

Hvis deltaker skal ha nytt vedtak som følge av endring av rettighet, se også [rutine for endring av rettigheter](../felles/endre_rett.md){.glightbox}.

## Se eksisterende vedtak

1. [Filtrer frem deltaker](../felles/guide.md#filtrere-i-sits) i skjermbildet *STU* [![bilde](../assets/images/gallery.svg){width="15"}](../assets/images/meny_skjermbilde.webp){.glightbox}

2. Fra toppmenyen går du til *Other* ⇒ *Personal Details* for å komme til *SPD* [![bilde](../assets/images/gallery.svg){width="15"}](../assets/images/meny_top.webp){.glightbox}

3. Se gjennom eksisterende vedtak [![bilde](../assets/images/gallery.svg){width="15"}](../assets/images/tmp.webp){.glightbox}

    Her kan det ligge både førstevedtak, behovsprøvde vedtak og vedtak for spesialundervisning.
    Feltet *Type vedtak* angir hvilken type vedtak det er.

    ??? tip "Du kan også få en oversikt over vedtak fra STU"

        Generer [*FOVO VEDOVR*](../felles/guide_pdf.md){.glightbox} fra STU.

## Lage førstevedtak på 300/600 timer

1. [Filtrer frem deltaker](../felles/guide.md#filtrere-i-sits) i skjermbildet *STU* [![bilde](../assets/images/gallery.svg){width="15"}](../assets/images/meny_skjermbilde.webp){.glightbox}

    ??? warning "Deltaker har et førstevedtak fra før"

        En deltaker skal bare ha ett aktivt førstevedtak.

        Hvis deltaker allerede har et førstevedtak som skal erstattes, f.eks. ved overgang fra 300 til 600 timer, må det gamle vedtaket markeres som avbrutt før du lager et nytt.

        1. Fra toppmenyen går du til *Other* ⇒ *Personal Details* [![bilde](../assets/images/gallery.svg){width="15"}](../assets/images/meny_top.webp){.glightbox}

        2. Finn vedtaket som skal avbrytes og klikk på *UDF*-knappen [![bilde](../assets/images/gallery.svg){width="15"}](../assets/images/meny_udf.webp){.glightbox}

        3. Endre *Vedtak Status* til "NO300_AVBRUTT" for et vedtak på 300 timer eller "NO600 AVBRUTT" for et vedtak på 600 timer.

        4. Klikk på *Apply* og lagre.

        5. Gå tilbake til STU.

2. Generer [*NOVO FORVED*](../felles/guide_pdf.md){.glightbox}

3. Svar "Ja" på spørsmålet om du vil registrere vedtak [![bilde](../assets/images/gallery.svg){width="15"}](../assets/images/tmp.webp){.glightbox}

    ??? question "Jeg vil bare se vedtaksbrevet uten å registrere vedtak"

        Svar "Nei" på spørsmålet. Da får du opp vedtaksbrevet uten at det lages et vedtak i SPD.

    Vedtaksbrevet åpnes som et HTML-dokument i nettleseren uavhengig av om du svarer ja eller nei. Du kan skrive ut brevet herfra.

4. Se gjennom vedtaket i SPD.

    Når det lages vedtak med *Vedtak Status* "NO300_INNV" eller "NO600_INNV" oppdateres timer i SPRS automatisk.

5. [Overfør vedtaket til NiR](#overfore-vedtak-til-nir).

## Innvilge behovsprøvd vedtak

Når deltaker har 50 timer eller færre igjen på eksisterende vedtak får lærer en melding om dette i e:Vision.

Lærer og deltaker søker om flere timer ved hjelp av søknadsskjemaet for behovsprøvd opplæring som finnes i IP i e:Vision.

Søknaden leveres til deltakerkontoret for behandling og arkivering. Når lærer lager søknaden opprettes det også et vedtak i SPD med status som søknad.

1. [Filtrer frem deltaker](../felles/guide.md#filtrere-i-sits) i skjermbildet *STU* [![bilde](../assets/images/gallery.svg){width="15"}](../assets/images/meny_skjermbilde.webp){.glightbox}

2. Generer [*NOVO BEHVED*](../felles/guide_pdf.md){.glightbox}

3. Svar "Ja" på spørsmålet om du vil registrere behovsprøvd vedtak [![bilde](../assets/images/gallery.svg){width="15"}](../assets/images/tmp.webp){.glightbox}

    ??? question "Jeg vil endre søknadsdato"

        Fyll inn ønsket søknadsdato på formen ddmmyyyy.

        Hvis du lar feltet stå tomt beholdes søknadsdatoen som ligger i SPD. Dette er datoen lærer lagde søknaden.

    ??? tip "Du kan få opp brevet uten å innvilge vedtaket"

        Svar "Nei" på spørsmålet om du vil registrere vedtak hvis du bare vil ha opp vedtaksbrevet.

    Vedtaksbrevet åpnes som et HTML-dokument i nettleseren uavhengig av om du svarer ja eller nei.

4. Se gjennom vedtaket i SPD.

    Ved innvilgelse endres *Vedtak Status* i UDF fra "NOBEH_SOEK" til "NOBEH_INNV".

    Innvilgede timer og gjenstående timer i SPRS oppdateres automatisk.

5. [Overfør vedtaket til NiR](#overfore-vedtak-til-nir).

### Finne deltakere som mangler behovsprøvd vedtak

1. [Filtrer frem senteret](../felles/guide.md#filtrere-i-sits) i skjermbildet *SCL* [![bilde](../assets/images/gallery.svg){width="15"}](../assets/images/meny_skjermbilde.webp){.glightbox}

2. Generer [*NOVO MANBEH*](../felles/guide_pdf.md){.glightbox}

3. Se gjennom oversikten over deltakere som mangler vedtak.

    Nederst i rapporten finner du en forklaring på kolonnene.

## Lage vedtak manuelt i SPD

??? warning "Bruk helst vedtaksbrevene for å lage vedtak"

    Dette er den gamle måten å registrere vedtak på. Det anbefales å lage vedtak ved å generere brev fra STU som beskrevet over.

1. [Filtrer frem deltaker](../felles/guide.md#filtrere-i-sits) i skjermbildet *STU* [![bilde](../assets/images/gallery.svg){width="15"}](../assets/images/meny_skjermbilde.webp){.glightbox}

2. Fra toppmenyen går du til *Other* ⇒ *Personal Details* [![bilde](../assets/images/gallery.svg){width="15"}](../assets/images/meny_top.webp){.glightbox}

3. Fra toppmenyen i SPD går du til *File* ⇒ *Add* [![bilde](../assets/images/gallery.svg){width="15"}](../assets/images/meny_top.webp){.glightbox}

4. Fyll inn datoer for vedtaket [![bilde](../assets/images/gallery.svg){width="15"}](../assets/images/tmp.webp){.glightbox}

    | | |
    | --- | --- |
    | Dato fra | Dato for kursstart, evt. dagens dato |
    | Dato til | Kan være 3-årsfrist eller 5-årsfrist |

5. Klikk på *UDF*-knappen [![bilde](../assets/images/gallery.svg){width="15"}](../assets/images/meny_udf.webp){.glightbox}

    === "Førstevedtak"

        6. Fyll inn følgende felt [![bilde](../assets/images/gallery.svg){width="15"}](../assets/images/tmp.webp){.glightbox}

            - *Aktivitet*
            - *Vedtak Status*
            - *Vedtaksdato*

            Timer på første vedtak settes automatisk til 300 eller 600 timer ut fra verdien i *Vedtak Status* (UDF2).

            ??? warning "Deltaker har flere aktive førstevedtak"

                En deltaker skal bare ha ett aktivt førstevedtak. Vedtak som erstattes må markeres med status "NO300_AVBRUTT" eller "NO600 AVBRUTT".

    === "Behovsprøvd vedtak"

        6. Fyll inn følgende felt [![bilde](../assets/images/gallery.svg){width="15"}](../assets/images/tmp.webp){.glightbox}

            - *Aktivitet*
            - *Vedtak Status*
            - *Vedtaksdato*
            - *Timer behov (N) eller innv (SU)*

7. Klikk på *Apply* og lagre med F6 eller Ctrl + S.

8. [Overfør vedtaket til NiR](#overfore-vedtak-til-nir).

## Overføre vedtak til NiR { #overfore-vedtak-til-nir }

Vedtak kan registreres direkte i NiR eller overføres fra SITS via skjermbildet DNI (DSF / NIR Interface).

??? warning "Overføring fra DNI kan feile"

    Overføring av vedtak via DNI har ofte feilet. Se [rutine for kontroll av overføringer til NiR](../norsk/kontroll_nir.md){.glightbox}.

1. Gå til skjermbildet *DNI* [![bilde](../assets/images/gallery.svg){width="15"}](../assets/images/meny_skjermbilde.webp){.glightbox}

2. Fyll inn følgende felt [![bilde](../assets/images/gallery.svg){width="15"}](../assets/images/tmp.webp){.glightbox}

    - *Program*
    - *Studieløp*
    - *VO Senter*
    - *Elev Nr (STU)* eller *DUF Nr*

    ??? tip "Du kan overføre vedtak for flere deltakere samtidig"

        Bruk ·| mellom STU-numrene, f.eks. 06300223·|08000144·|09000512.

        Se [avansert filtrering](../felles/avansert_filtrering.md#filtrering-pa-flere-verdier-i-samme-felt) for hvordan du får frem eller-tegnet i SITS.

    ??? warning "Førstevedtaket er tidligere registrert manuelt i NiR"

        Hvis du skal overføre et behovsprøvd vedtak kan også førstevedtaket bli overført dersom det ikke har en verdi i feltet *NIR referanse* i SPD.

        Hvis du har kontrollert at førstevedtaket allerede ligger i NiR kan du fylle inn en verdi, f.eks. 1, i *NIR referanse* på førstevedtaket i SPD for å unngå dobbeltregistrering.

        Vedtak med en verdi i dette feltet blir ikke forsøkt overført på nytt.

3. Velg "Journal" fra nedtrekksmenyen ved punkt 3, *Kjør NIR upload prosess*, og trykk på den grønne pilen [![bilde](../assets/images/gallery.svg){width="15"}](../assets/images/tmp.webp){.glightbox}

4. Klikk på *Run now* [![bilde](../assets/images/gallery.svg){width="15"}](../assets/images/tmp.webp){.glightbox}

5. Kontroller at vedtaket er overført etter [rutine for kontroll av overføringer til NiR](../norsk/kontroll_nir.md){.glightbox}.