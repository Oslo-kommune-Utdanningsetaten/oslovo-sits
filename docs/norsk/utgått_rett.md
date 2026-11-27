# Sluttføre deltaker ved utgått rett

## Kontrollere deltakers rett og timer

1. Finn aktuelle deltakere etter [rutine for å finne deltakere med utgående rett](utgående_rett.md){.glightbox}

2. Ved behov for å kontrollere antall timer kan du [filtrere frem deltaker](../felles/guide.md#filtrere-i-sits) i skjermbildet *SPR* [![bilde](../assets/images/gallery.svg){width="15"}](../assets/images/meny_skjermbilde.webp){.glightbox} og generere [*NOVO TIMETO*](../felles/guide_pdf.md){.glightbox}

    Rapporten viser deltakers timer fordelt på VO-senter.

    ??? quote "Brukerinput for **NOVO TIMETO**"

        <div class="srl-table">

        |  |  |  |
        | --- | --- | --- |
        | Skoleår | <span>*skoleår*</span> | Inneværende skoleår er standard |
        | startdato | <span>*ddmmyyyy*</span> | Første dato i perioden du vil kontrollere |
        | sluttdato | <span>*ddmmyyyy*</span> | Siste dato i perioden du vil kontrollere |
        | Norwegian Hours (N) or Social Science Hours (S)? | <span>N / S</span> | N for norsktimer, S for samfunnsfagtimer |

        </div>

        N er standard når du logger inn i SITS. Sist valgte innstilling huskes så lenge du ikke logger ut eller kjører en annen type rapport.

    ??? warning "Hvordan telles timer i rapporten?"

        Deltatte timer beregnes som totalt planlagte timer minus gyldig fravær.
        Hvis lærer ikke har ført fravær telles timene som om deltaker var til stede.

        Timene fordeles på VO-senter ut fra hvor undervisningen faktisk har foregått.

    Se også [rutine for refusjonsrapporter](refusjonsrapport.md){.glightbox}

## Sluttføre deltaker

Når det er avklart at deltaker skal sluttføres, følg [rutine for sluttføring](../felles/sluttføre.md){.glightbox}

Hvis deltaker skal fortsette opplæring med en annen rettighet, se [rutine for endring av norsk-rettighet](endre_norskrett.md){.glightbox}

## Sluttføre deltakere som har bestått norskprøve 3

??? warning "Dette er en gammel rutine"

    Rutinen gjelder bestått norskprøve 3 muntlig og skriftlig.
    Det må avklares med SITS-ansvarlig om rapporten fortsatt skal brukes før du gjennomfører denne rutinen.

    Rapporten setter sluttårsak til BN (bestått norskprøve), og skal ikke brukes som en generell rapport for sluttføring ved utgått rett.

Rutinen gjennomføres etter at resultatene fra siste norskprøver er oppdatert i SQE.

1. [Filtrer frem senteret](../felles/guide.md#filtrere-i-sits) i skjermbildet *SCL* [![bilde](../assets/images/gallery.svg){width="15"}](../assets/images/meny_skjermbilde.webp){.glightbox}

2. Generer [*NOVO FFOPPL*](../felles/guide_pdf.md){.glightbox} fra SCL

3. Gå til skjermbildet *SPR* og filtrer frem deltakere med følgende verdier [![bilde](../assets/images/gallery.svg){width="15"}](../assets/images/tmp.webp){.glightbox}

    |  |  |
    | --- | --- |
    | SPR Status | ·!FF |
    | Gruppe SPR | Norskprøve3 |
    | VO senter | Ditt senter |

    Se [avansert filtrering](../felles/avansert_filtrering.md#utelukke-enkelte-verdier-fra-filtrering) for hvordan du utelukker deltakere med status FF.

    ??? warning "Deltaker går på eller venter på kurs til Bergenstesten"

        Disse deltakerne skal ikke være med i utvalget som skal sluttføres.
        De kan merkes med BTEST i *Gruppe SPR*.

4. Kontroller utvalget og generer [*NOVO FFOPPL*](../felles/guide_pdf.md){.glightbox} fra *All* i SPR

    ??? warning "Rapporten sluttfører alle deltakere i utvalget"

        Rapporten lager ikke bare sluttbrev, men gjør også følgende endringer:

        - Alle aktive EAD settes til Withdrawn.
        - Alle EAD som hadde status Current får dagens dato som sluttdato.
        - Status på SPR settes til FF.
        - Sluttdato på SPR (SPR_UDF6.SPR) settes til dagens dato.
        - SCJ som hører til SPR får dagens dato som sluttdato og BN som sluttårsak.
        - SCE for nyeste skoleår som hører til SPR får dagens dato som sluttdato og BN som sluttårsak.
        - SMO for alle t-fag slettes.

5. Gi sluttbrevet til de aktuelle deltakerne