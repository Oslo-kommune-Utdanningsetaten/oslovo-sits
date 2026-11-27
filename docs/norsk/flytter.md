# Behandle deltakere som flytter

Når en deltaker med NiR-rettigheter flytter fra Oslo til en annen kommune, endres ikke nødvendigvis rettigheten i NiR. Oslo er derimot ikke lenger ansvarlig kommune, og Oslo VO kan derfor ikke lenger overføre deltatte timer og fravær til NiR.

## Deltaker flytter fra Oslo

1. Sluttfør deltaker på aktuell NNIR-SPR etter [rutine for sluttføring](../felles/sluttføre.md){.glightbox}

2. Sett *SPR status* til SL

    Deltaker skal ha status SL fordi deltaker kan flytte tilbake til Oslo og fortsette opplæringen på samme SPR.

3. Oppdater eventuelt adresse etter [rutine for endring av personalia](../felles/personalia.md){.glightbox}

## Deltaker ønsker å fortsette opplæring i Oslo etter flytting

??? warning "Ikke endre program eller rettighet på eksisterende SPR med timer"

    Program og rettighet på en SPR det allerede ligger timer på skal ikke endres.
    Bruk en eksisterende SPR med riktig program og rettighet, eller lag en ny etter [rutine for endring av rettighet](../felles/endre_rett.md#lage-ny-spr-ved-endring-av-rettighet){.glightbox}.

=== "Norskopplæring"

    ??? question "Den nye hjemkommunen ønsker å betale for opplæringen"

        Det må foreligge en avtale med hjemkommunen om kjøp av timer for deltaker.

        Aktiver deltaker på en SPR med *Program* NBET og rettighet KOMM.

    ??? question "Deltaker ønsker å betale selv"

        Aktiver deltaker på en SPR med *Program* NBET og rettighet BETAL.
        Deltaker får da tilbud om norskopplæring mot betaling.

=== "Samfunnskunnskap"

    Det må foreligge en avtale med den nye hjemkommunen om kjøp av de resterende timene i samfunnskunnskap.

    Aktiver deltaker på en SPR med *Program* NBET og rettighet KOMM.

    ??? warning "Deltaker ønsker å betale selv"

        Deltaker kan ikke selv kjøpe timer i samfunnskunnskap i Oslo etter å ha flyttet til en annen kommune.

## Deltaker flytter tilbake til Oslo

1. Sjekk hvilken rettighet deltaker har i NiR.

2. Aktiver deltaker på eksisterende NNIR-SPR med aktuell rettighet.

    ??? warning "Deltaker har endret rettighet"

        Se [rutine for endring av norsk-rettighet](endre_norskrett.md){.glightbox} dersom deltaker har fått en annen rettighet i NiR.

    ??? question "Deltaker har fullført samfunnskunnskap i en annen kommune"

        For deltakere omfattet av introduksjonsloven der NiR viser at 50 timer samfunnskunnskap er gjennomført i en annen kommune, settes følgende verdier på SPR for samfunnskunnskap:

        | Felt | Verdi |
        | --- | --- |
        | SPR status | FU |
        | Studieløp | FSAM |