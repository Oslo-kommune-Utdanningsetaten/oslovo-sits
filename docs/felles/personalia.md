# Endre personalia for deltaker

## Endre addresse

1. [Filtrer frem deltaker](../felles/guie.pdf.md#filtrere-i-sits) i skjermbildet *STU* [![bilde](../assets/images/gallery.svg){width="15"}](../../assets/images/meny_skjermbilde.webp){.glightbox}

2. Klikk på *Home Address* [![bilde](../assets/images/gallery.svg){width="15"}](../../assets/images/stu_address.webp){.glightbox}

3. Endre eller slett verdier

4. Trykk *Apply* [![bilde](../assets/images/gallery.svg){width="15"}](../../assets/images/men_apply.webp){.glightbox}

## Håndtere fødselsnummer

### Bestille fiktivt fødselsnummer

1. Opprett sak i USD til *Vigilo*

2. Oppgi følgende:
    - Fullt navn
    - Fødselsdato
    - Kjønn
    - Adresse
    - Senter

3. Vent til du mottar nummer

### Registrere fødselsnummer i SITS (inkludert fiktivt)

1. [Filtrer frem deltaker](../felles/guie.pdf.md#filtrere-i-sits) i skjermbildet *STU* [![bilde](../assets/images/gallery.svg){width="15"}](../../assets/images/meny_skjermbilde.webp){.glightbox}

2. Sett inn fødelsnummer i *Fødselsnummer*

    Skriv "FIKTIVT" hvis hvis det er et fiktivt nummeri *Fnr-merknad*

3. Lagre

??? warning "Det står noe som fødselsnummer allerede"

    Aldri gjør endringer i feltet hvis det allerede står noe der.
    Opprett forespørsel i USD der du beskriver situasjonen.

### Endring av registrert fødselsnummer (inkludert fiktivt)

1. Opprett forespørsel i USD til SITS fagsystemer

2. Legg ved:

    - STU-nummer
    - Nytt fnr

??? warning "Jeg får ikke lagret fødselsnummer"

    Det gjøres en kontrollsjekk.
    Her er feilmeldingene:

    | Melding | Beskrivelse | Løsning |
    | National identity number is invalid – incorrect date of birth | Fødselsdato stemmer ikke med fnr. (for fiktive er det +4 på det første tallet) | Sjekk at fnr er riktig. Hvis ja: "Lyg" på fødselsdato og kommenter i SAD og SPR |
    | National identity number is invalid – incorrect date of birth | Kjønn stemmer ikke med fnr. | Sett riktig kjønn. Ta kontakt med Vigilo dersom det er mottat feil i fnr |
    | National identity number is invalid – already in use | Det finnes en STU med denne fnr. | Ta kontakt med sits-ansvarlig, avklar sak og beskriv i USD-sak |
    | National identity number is invalid – Wrong length or invalid characters | Ugyldig format | Fiks format |