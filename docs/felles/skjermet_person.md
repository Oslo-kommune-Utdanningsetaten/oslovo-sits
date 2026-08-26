# Behandle skjermede personer og personer med fortrolig addresse


## Behandle skjermede deltakere ved registrering

1. Sjekk om deltaker er registrert i SITS fra før

    1. Spør deltaker om den har vært i kontakt med Oslo VO før
    2. Søk opp som vanlig i SITS
    3. Søk i SITS med DUF-nr og **SKJERMET** som etternavn

=== "Kategori 6 - Strengt fortrolig adresse"

    ??? "Hva om deltaker allerede er i SITS?"

        Da må du først Fjern alt som kan identifisere personen fra STU, QED, SAD, ACD og SPR.
        Så kan du endre på samme måte som rutine under.


    1. Registrer deltaker etter rutine ([utenfor Servicesenteret](../felles/ny_stu.md) [for Servicesenteret](../felles/ny_stu.md))

        1. **Etternavn** og **Fornavn** skal være **"SKJERMET"**
        2. **Fødselsdato** skal være 010870
        3. **Fødselsnummer** skal være tomt
        4. **Adresse** skal være **Drammensveien 1, 0001 OSLO**
        5. **E-post** og **Mobil** skal være tomt

    2. Hvis deltaker har et ønsket alias settes dette som **Navn i bruk** i STU [![bilde](../../assets/images/gallery.svg){width="15"}](../../assets/images/tmp.webp){.glightbox}

    3. Gå til **SPD** og legg inn et nytt **SKJ**-vedtak [![bilde](../../assets/images/gallery.svg){width="15"}](../../assets/images/tmp.webp){.glightbox}

        ??? warning "Det finnes allerede en SPD"

            Hvis **Sekvensnr** allerede eksisterer, jekk hvilke **Sekvensnr** som finnes ved å filtrere frem STU-nummeret og lag så en ny der **Sekvensnr** er en over det høyeste eksisterende.
    
    4. Fyll inn reell informasjon i **Merknad**

        1. **Etternavn** og **Fornavn** 
        2. **Fødselsnummer** eller **D-nummer**
        3. **DUF** hvis deltaker har dette
        4. **Adresse**, **Mobil** og **e-post**
        5. Deltakers ønske om kontaktform
        6. Evt. en tillitsperson som kan kontaktes, m/kontaktinformasjon

    5. Lagre slik at det skjules

        ??? warning "Dobbeltsjekk før du lagrer"

            Når du lagrer her kan du ikke lengre endre på det. Er uhellet ute må du ta kontakt med SITS-ansvarlige på ditt senter.



=== "Kategori 7 - Fortrolig adresse"

    ??? "Hva om deltaker allerede er i SITS?"

        Da må du først fjerne adresse fra STU.

    1. Registrer deltaker etter rutine, men med adresse som **Drammensveien 1, 0001 OSLO**

        [utenfor Servicesenteret](../felles/ny_stu.md) 
        [for Servicesenteret](../felles/ny_stu.md)

    2. Gå til **SPD** og legg inn reell addresse [![bilde](../../assets/images/gallery.svg){width="15"}](../../assets/images/tmp.webp){.glightbox}

    3. Lagre slik at det skjules

        ??? warning "Dobbeltsjekk før du lagrer"

            Når du lagrer her kan du ikke lengre endre på det. Er uhellet ute må du ta kontakt med SITS-ansvarlige på ditt senter.


## Særbehandling av skjermede deltakere i studieløp

### Finne kontaktinformasjon til skjermede personer

1. Ta kontakt med SITS-ansvarlig ved ditt senter og etterspør passord.
2. Bruk passordet for å låse opp kontaktinformasjon i SPD [![bilde](../../assets/images/gallery.svg){width="15"}](../../assets/images/tmp.webp){.glightbox}

### Sende brev og vedtak til skjermede personer

??? warning "Husk at brev til skjermede personer ikke sendes til Websak!"

1. Generer brevet som vanlig
2. Fra samme skjermbilde går du til **Goto**, **Related Documents** [![bilde](../../assets/images/gallery.svg){width="15"}](../../assets/images/tmp.webp){.glightbox}
3. Let deg frem til riktig brev via **Preview**
4. Skriv ut brevet [![bilde](../../assets/images/gallery.svg){width="15"}](../../assets/images/tmp.webp){.glightbox}
5. Distribuer til deltaker på den måten deltaker ønsker

    ??? tip "Hvordan kan vi gi brevet til deltaker?"

        Her er det åpent etter evne og deltakers ønske.
        Noen sender til en adresse ønsket av deltaker.
        Andre tar kontakt med deltaker og overrekker brev i person.