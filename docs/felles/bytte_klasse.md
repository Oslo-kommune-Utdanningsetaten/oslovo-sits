# Bytte klasse på en deltaker

## Melde en deltaker av og på kurs i Live

1. Slå opp deltaker i SPR [![bilde](../../assets/images/gallery.svg){width="15"}](../../assets/images/tmp.webp){.glightbox}
2. Gå via **Current**, **Schedule Timetable** til **Exchange module** [![bilde](../../assets/images/gallery.svg){width="15"}](../../assets/images/tmp.webp){.glightbox}

    === "Melde deltaker på kurs"
        3. Fyll inn **Fag**, **Forekomst** og **Fra dato** under *Legg til* og gå videre [![bilde](../../assets/images/gallery.svg){width="15"}](../../assets/images/tmp.webp){.glightbox}
        4. Huk av hvilken klasse deltaker skal meldes på og trykk på **Apply**[![bilde](../../assets/images/gallery.svg){width="15"}](../../assets/images/tmp.webp){.glightbox}

            ??? question "Jeg vet ikke hvilket kurs jeg skal velge"

                Er du usikker på hvilket kurs du skal velge trykk på >> for de forskjellige. Da får du mer informasjon om kursene.

            ??? warning "Deltaker er på et overlappende kurs"

                Hvis deltaker er på et kurs som overlapper det du skal melde den på, må du melde deltaker av eksisterende kurs først.

    === "Melde deltaker av kurs"
        3. Fyll inn **År**, **Periode** og **Fag** under *Fjern* [![bilde](../../assets/images/gallery.svg){width="15"}](../../assets/images/tmp.webp){.glightbox}
        4. Fyll inn sluttdato i **Fra og med dato** og trykk på pilen nederst til høyre [![bilde](../../assets/images/gallery.svg){width="15"}](../../assets/images/tmp.webp){.glightbox}

            ??? question "Hvilken dato skal jeg velge som sluttdato?"

                Feltet er fra **og med** en dato. Dermed vil kursaktivitet på den datoen du skriver også fjernes.
                For eksempel: Ola har kurs 1., 2. og 3. august. Skriver du sluttdato 2. august forsvinner den, og bare 1. august blir igjen.

3. Se gjennom **Message buffer** og trykk **Clear and close** [![bilde](../../assets/images/gallery.svg){width="15"}](../../assets/images/tmp.webp){.glightbox}

    ??? warning "Det kommer en feil i Message buffer"

        ??? warning "ERROR WHEN CREATING SMO"
            
            Får du denne feilmeldingen er det oftest fordi det er kollisjon med et eksisterende kurs.
            For å sjekke dette kan du gjøre følgende:

            1. Sett inn STU-nummer + **·*** i SPR og trykk **F5**
            2. Generer FOVO KUROVR fra **All** [![bilde](../../assets/images/gallery.svg){width="15"}](../../assets/images/tmp.webp){.glightbox}
            3. Se gjennom kurs deltaker er aktiv på for kollisjoner

        ??? warning "Problemer med EVE"

            Disse kommer ofte av to grunner:

            - Antall deltakere på en EVE overskrider antall deltakere i feltet **Maks antall** i **EVE**
            - Kombinasjonen av **Fag**, **Forekomst**, **Skoleår** og **Gruppe-id** er ikke unik.

            Begge disse må da rettes med riktig informasjon.

        ??? warning "Problemer med MAV"

            Disse kommer ofte av to grunner:

            - Antall deltakere har nådd maks antall beskrevet i **MAV**-feltet **Mål**.
            - **MAV** er ikke korrekt.

            Begge disse må da rettes med riktig informasjon.

        ??? warning "Deltakeren har faget fra før i SMO"

            Det ligger en hindring i å sette samme deltaker to ganger på samme fag samme skoleår.
            Hvis man må gjøre dette, f.eks. hvis en deltaker har to økter på samme dag med samme fag, må man:
            1. Plasser deltaker på det ene faget
            2. Søk opp SPR-nummer i SMO [![bilde](../../assets/images/gallery.svg){width="15"}](../../assets/images/tmp.webp){.glightbox}
            3. Marker linjen du vil slette SMO for og trykk **File**, **Delete** [![bilde](../../assets/images/gallery.svg){width="15"}](../../assets/images/tmp.webp){.glightbox}
            3. Plasser deltaker på det andre faget

## Melde flere deltakere på kurs samtidig i Live

1. Marker deltakerne du ønsker å plassere med lik **Gruppe SPR** [![bilde](../../assets/images/gallery.svg){width="15"}](../../assets/images/tmp.webp){.glightbox}

    ??? tip "Du kan gjøre dette i EVE for en hel klasse samtidig"
            
        Kjør rapporten **FOVO OPPSPR** fra **EVE** etter manual LENKE TIL MANUAL
        
2. Filtrer de aktuelle deltakerne i **SPR** med **Gruppe SPR** [![bilde](../../assets/images/gallery.svg){width="15"}](../../assets/images/tmp.webp){.glightbox}

    ??? tip "Du kan se hvor mange du jobber med"
            
        Etter filtrering vil SPR vise **X av Y** SPR i øvre venstre jkørne.

3. Trykk på **All**, **Exchange module** [![bilde](../../assets/images/gallery.svg){width="15"}](../../assets/images/tmp.webp){.glightbox}

4. Fyll inn **År**, **Forekomst** og **Fag** under *Fjern*, og huk av for **Spesifiser** før du trykker grønn pil nederst til høyre[![bilde](../../assets/images/gallery.svg){width="15"}](../../assets/images/tmp.webp){.glightbox}

    ??? warning "Jeg kommer ikke videre etter å trykke grønn pil"

        Dette er antageligvis fordi deltakerne har SMO for faget allerede.
        Hvis du vil plassere dem må du først slette SMO for disse.

5. Huk av hvilken klasse deltakerne skal meldes på og trykk på **Apply**[![bilde](../../assets/images/gallery.svg){width="15"}](../../assets/images/tmp.webp){.glightbox}

    ??? question "Jeg vet ikke hvilket kurs jeg skal velge"

        Er du usikker på hvilket kurs du skal velge trykk på >> for de forskjellige. Da får du mer informasjon om kursene.

6. Huk av for de som skal komme med og trykk **Schedule Students** [![bilde](../../assets/images/gallery.svg){width="15"}](../../assets/images/tmp.webp){.glightbox}

    ??? tip "Du kan trykke på den grønne haken øverst for å velge alle"

        [![bilde](../../assets/images/gallery.svg){width="15"}](../../assets/images/tmp.webp){.glightbox}

    ??? warning "Ikke alle SPR kommer med"

        Hvis ikke alle SPR kommer med må du sjekke opp de som mangler.
        Ta kontakt med SITS ansvarlig på ditt senter hvis du ikke klarer å se hva som mangler for disse SPR-numrene.

7. Les gjennom sluttmeldingen og trykk **Clear & close** [![bilde](../../assets/images/gallery.svg){width="15"}](../../assets/images/tmp.webp){.glightbox}

    ??? warning "Det dukker opp *ERROR* i sluttmeldingen"

        Hvis det dukker opp feil her, og du ikke vet hva som er grunnen, må du ta kontakt med SITS-ansvarlige på ditt senter.


## Melde en deltaker av og på kurs i eVision

1. Klikk på **Deltaker kursbehandling** under **Deltakerbehandling** [![bilde](../../assets/images/gallery.svg){width="15"}](../../assets/images/tmp.webp){.glightbox}
2. Fyll inn minst **Gruppe SPR** eller **SPR-kode** for å finne deltaker eller deltakerne du skal behandle [![bilde](../../assets/images/gallery.svg){width="15"}](../../assets/images/tmp.webp){.glightbox}

    ??? tip "Jeg ønsker å definere en gruppe deltakere å behandle"

        Dette kan gjøres via å redigere **Gruppe SPR** på disse deltakerne. Det kan gjøres via å finne en klasse i EVE og generere FOVO OPPSPR.

    ??? tip "Du kan finne flere gjennom avansert filtrering"

        Vi aksepterer bruk av * som filtrering her. Da kan du for eksempel ha gruppeSPR K32 og K33 og finne begge ved å filtrere på K3*.

3. Huk av alle SPR du ønsker å sette på kurs og trykk **Fortsett** [![bilde](../../assets/images/gallery.svg){width="15"}](../../assets/images/tmp.webp){.glightbox}

    ??? tip "Se alltid gjennom, og kanskje endre, gruppe SPR her"

        Her får du lov til å se og endre GruppeSPR for deltakere (Lagres bare når du trykker fortsett). Det kan være nyttig å ha disse like, da dette kan gjøre det enklere å lage brev og slikt for klassen videre.

4. Skriv inn **Reg nr.** for klassen, samt eventuell **startdato** og **sluttdato**

    ??? question "Når skal jeg ha med startdato eller sluttdato?"

        Hvis du bare fyller inn regnr og lar start- og sluttdato være tomme felt så legges deltakeren på alle datoene som kurset går. Hvis en av start- eller sluttdato er fylt inn så vil deltakerene få kursdatoer slik du skriver. Skal du sluttføre fra et kurs **MÅ** du skrive inn Startdato.

    ??? warning "Endringer i **Gruppe SPR** er gjort selv om du trykker **Avbryt**"

        Disse må da eventuellt endres til noe annet hvis du har gjort en feil.

5. Velg **Legg på kurs** for å melde deltaker på, og **Sluttfør fra kurs** for å melde deltaker av [![bilde](../../assets/images/gallery.svg){width="15"}](../../assets/images/tmp.webp){.glightbox}

6. Les gjennom og trykk **Neste** [![bilde](../../assets/images/gallery.svg){width="15"}](../../assets/images/tmp.webp){.glightbox}

    ??? warning "Listen er ikke slik jeg forventet"

        Dette er sansynligvis fordi du har gjort en endring i **Gruppe SPR** for noen, og SITS henter da bare ut det originale utvalget.
        Du kan fikse dette med å sette **Gruppe SPR** til det samme for hele gruppen du vil jobbe med.

        Har du ikke endret **Gruppe SPR** burde du ta kontakt med din SITS-ansvarlige.

7. Les gjennom prosessrapport for deltakerene og trykk **Avslutt** [![bilde](../../assets/images/gallery.svg){width="15"}](../../assets/images/tmp.webp){.glightbox}

    ??? warning "Status er ikke **OK** for en eller flere deltakere"

        Hvis noen deltakere ikke kan bli plassert må du sjekke opp hvorfor før du evt. fikser.

        *Clash* betyr at deltakeren har andre kurs som går til samme tid. Da må deltaker meldes av et av kursene.

        Fulle kurs kan oppstå når deltakertallet overstiger det som står enten i **MAV** eller **EVE**. Da må det gjøres en vurdering om hva som skal gjøres.

        Er du usikker på hva som er galt, noter ned SPR-koder det ikke gikk for, hva som var ønsket og send en forespørsel til SITS-ansvarlige ved ditt senter.


## Bytte klasse for en deltaker i eVision

??? warning "Denne prosessen sluttfører deltaker på alle kurs den er på i en gitt SPR"

    Bare bruk denne prosessen dersom en deltaker skal bytte alle kurs. Det er ikke nødvendig å ta hensyn til kurs for andre SPR-nummer til deltaker utenom at det kan clashe på tid.

1. Trykk på **Bytte klasse** i **Deltakerbehandling** [![bilde](../../assets/images/gallery.svg){width="15"}](../../assets/images/tmp.webp){.glightbox}
2. Fyll inn **SPR-kode**, **Fra dato** og **Reg. nr.** for kurs deltaker skal begynne på før du trykker **Fortsett** [![bilde](../../assets/images/gallery.svg){width="15"}](../../assets/images/tmp.webp){.glightbox}

    ??? warning "Det må være for det gjeldende skoleåret"
        
        Endringer av kurs utenom gjeldende skoleår skal en være forsiktig med, og gjøres i samråd med SITS-ansvarlige.

3. Se gjennom rapporter for hvilke kurs deltaker vil bli sluttført fra og satt på til før du trykker **Bekreft og gå videre** [![bilde](../../assets/images/gallery.svg){width="15"}](../../assets/images/tmp.webp){.glightbox}

4. Se gjennom resultatsrapport for hver kursendring og trykk **Ferdig** hvis alt er OK [![bilde](../../assets/images/gallery.svg){width="15"}](../../assets/images/tmp.webp){.glightbox}

    ??? warning "Status er ikke **OK** for en eller flere endringer"

        *Clash* betyr at deltakeren har andre kurs som går til samme tid. Da må deltaker meldes av et av kursene.

        Fulle kurs kan oppstå når deltakertallet overstiger det som står enten i **MAV** eller **EVE**. Da må det gjøres en vurdering om hva som skal gjøres.

        Er du usikker på hva som er galt, noter ned SPR-koder det ikke gikk for, hva som var ønsket og send en forespørsel til SITS-ansvarlige ved ditt senter.



