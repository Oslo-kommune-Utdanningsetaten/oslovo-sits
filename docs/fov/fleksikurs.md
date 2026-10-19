# Fleksible kurs i FOV

??? warning "Jeg er usikker på om en deltaker skal registreres til fleksibelt kurs"
    
    Per dags dato er fleksible kurs et forsøk på Rosenhof VO. Det er i en forsøksfase, og gjelder da bare fleksimatte på Rosenhof VO.


## Plassere deltaker på fleksibelt kurs

=== "Deltaker fra Fram"

    1. Sjekk at adresse og kontaktinformasjon stemmer med STU

        ??? warning "Deltaker er ikke registrert i SITS"

            Hvis deltaker ikke er i SITS må du først registrere den gjennom [Ny deltaker utenfor SeSe](../felles/ny_stu.md)
    
    2. Lag ny SPR med program *NGSK* og rettighet *UA* via [Lag nytt studieløp for deltaker](../felles/ny_spr.md)

        ??? warning "Deltaker har allerede en NGSK-SPR"

            Hvis deltaker allerede har en NGSK-SPR tar du utgangspunkt i den og følger rutine for [Endre rettighet på deltaker](../felles/endre_rett.md)
            Ny rettighet skal da fortsatt være *UA*.
            Viktig at du ikke gjør dette hvis den er **AP**, da følger du "Deltaker fra annet senter"

    3. Behandle deltaker som vanlig FOV-deltaker for kursplassering, fraværsføring etc.

=== "Deltaker fra annet senter"

    Vi kan registrere disse, men det er ingen funksjoner tilknyttet dette per i dag.
    Dette er en forsøksfase, og det gjennstår å få avklart om disse får samme tilganger som deltakere på deres senter.

    1. [Filtrer frem deltaker](../felles/guie.pdf.md#filtrere-i-sits) i skjermbildet *SPR*[![bilde](../assets/images/gallery.svg){width="15"}](../../assets/images/meny_skjermbilde.webp){.glightbox}

    2. Fra toppmenyen går du til *Other* ⇒ *Module* ⇒ *Selections* [![bilde](../assets/images/gallery.svg){width="15"}](../../assets/images/meny_top.webp){.glightbox}

    3. Endre **Fagstatus** for faget som skal tas på ditt senter til

        |     |     |
        | --- | --- |
        | Rosenhof | RE_ROS |
        | Helsfyr | RE_SME |
        | Skullerud | RE_SKU |
        | Nydalen | RE_ASE |
    
    4. Behandle deltaker som vanlig FOV-deltaker for kursplassering, fraværsføring etc.

    5. Sørg for å opprettholde kontakt med senteret deltaker hører til, da det er viktig at de er informert om endringer i studieløpet for deltaker.


## Flytte deltaker over til vanlig FOV-løp

1. Registrer på excel-skjema dato deltaker ble vurdert til å kunne gå over til FOV

2. Vent til deltaker er behandlet av Servicesenteret

    1. All kursaktivitet som skjer fra og med dato du registrerer vil komme med på ny NGSK-SPR for FOV


??? info "For servicesenteret"

    Lag ny SPR med utgangspunkt it UA-spr, ta med kursaktivitet fra dato registrert i skjema.
    Sørg for at modulplassering ligger på ny SPR.
    Ellers behandles ny SPR som vanlig FOV-spr.
