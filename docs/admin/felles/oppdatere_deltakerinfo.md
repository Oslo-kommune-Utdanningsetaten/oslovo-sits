# Registrere ny person i SITS

1. Gå til QED
2. Skriv inn fødelsnummer og fødselsdato
    ??? warning "Individ mangler fødselsnummer"
        Dersom personen ikke har et fødselsnummer fylles i stedet et annet felt som DUF eller etternavn.
        Målet er å sørge for at vi ikke dobbeltregistrerer.
3. Trykk på "Find"
4. Se på listen som dukker opp, vurder om en av dem er personen.

=== "Personen er registrert fra før"
    1. Dobbeltklikk på personen i listen

=== "Personen er ikke registrert fra før"
    1. Trykk på "Create New"
    2. Finn dokumentasjon på personalia for personen
        - Folkeregisteret
        - NiR
        - Gyldig identifikasjonskort
    3. Fyll inn personalia
        ??? quote "Brukerinput for personalia i QED"
            Du har levert dokumentasjon som følger:

            | Navn på felt | Brukerinput | Beskrivelse |
            |------|------|----------------|
            |Etternavn| `ETTERNAVN FRA ID` | ID skal eksplisitt vise hva som er etternavn. Fyll inn med eksakt tekst. |
            |Fornavn| `FORNAVN FRA ID` | ID skal eksplisitt vise hva som er fornavn. Fyll inn med eksakt tekst. |
            |Født| `DATO FRA ID` | Fødselsdato fra ID |
            |Fødselsnummer| `DATO FRA ID` | Fødselsdato fra ID |
    4. Fyll inn kontaktinformasjon fra "Address"
        ??? quote "Brukerinput for personalia i QED"
            Du har levert dokumentasjon som følger:

            | Navn på felt | Brukerinput | Beskrivelse |
            |------|------|----------------|
            |Etternavn| `ETTERNAVN FRA ID` | ID skal eksplisitt vise hva som er etternavn. Fyll inn med eksakt tekst. |
            |Fornavn| `FORNAVN FRA ID` | ID skal eksplisitt vise hva som er fornavn. Fyll inn med eksakt tekst. |
            |Født| `DATO FRA ID` | Fødselsdato fra ID |
            |Fødselsnummer| `DATO FRA ID` | Fødselsdato fra ID |
