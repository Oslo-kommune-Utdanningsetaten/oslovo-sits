# Fram

??? quote "Hvem er denne rutinen for?"
    Rutinen er ment for de som henter deltakere fra VO/SITS inn til Fram.

## Ta ut venteliste fra SITS

1. Gå til skjermbildet *SCL*

2. Skriv inn skolekoden *SOV*

3. Generer *NOVO VENT*

    Den åpner seg i EXCEL

## Behandle en deltaker på ventelisten

1. Gå til skjembildet *SPR*

2. Lim inn deltakernummer for deltaker du vil behandle

    Deltakernummer ligger i ventelisten

3. Trykk **F5**

4. Marker deltaker som overført til fram ved å skrive *OF* i feltet *SPR status*

    ??? warning "Her tas deltaker bort fra oversikter i SITS"

        Fra og med dette stadiet er det bare Fram som har oversikt over nåværende status på disse deltakerne.
        Viktig at oversikt er klar i annet system først.

5. Lagre med CTRL + S

??? info "Hvis deltaker skal ha norskvedtak"

    1. Gå til skjermbildet *SAD*
    
    2. Lim inn deltakernummer og fjern **/** og alt til høyre for den

    3. Trykk **F5**

    ??? hint "Hvis du vil sjekke at deltaker er passende"

        - *NIR Kategori fra* & *NIR 1.opph.vedt* skal ha dato.
        - *Integr.36/18/300* skal vise 18, 36 eller 300
        
    4. Skriv dagens dato i feltet *Integr. Frist fra*

    5. Lagre med CTRL + S