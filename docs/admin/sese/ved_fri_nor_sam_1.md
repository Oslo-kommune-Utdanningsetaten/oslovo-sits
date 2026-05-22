# Fritak fra norsk og samfunnskunnskap

??? quote "Hvorfor gjør vi dette?"
    Integreringsloven § 29.Fritak fra plikt til deltagelse i opplæring i norsk og samfunnskunnskap.

    Personer som kan dokumentere et minimum av kunnskaper i norsk eller samisk kan etter søknad fritas fra plikten til å delta i opplæring i norsk. Personer som kan dokumentere et minimum av kunnskaper om det norske samfunnet kan etter søknad fritas fra plikten til å delta i opplæring i samfunnskunnskap.

    Det kan gis fritak dersom det foreligger særlige helsemessige eller andre tungtveiende årsaker som hindrer deltagelse i opplæringen.

    ??? quote "Hvorfor gjør vi dette?"
        Test2

## Sjekkliste

1. Søknad er mottatt i Websak
2. Søker har en plikt hen kan få fritak fra
3. Søker bor i Oslo


## Behandle fritaket i SITS

??? warning "Deltaker finnes ikke i SITS"
    Dersom deltaker ikke finnes i SITS, men fortsatt har plikter hen kan få fritak fra, må deltaker registreres i SITS. Se egen rutine for dette.

??? warning "Første oppholdsvedtak før 01.01.2016"
    Dersom søker har første oppholdsvedtak før 01.01.2016 gjelder det en egen rutine.

=== "Fritak fra norsk"
    1. Slå opp deltaker i QED [![Preview](../../assets/images/gallery.svg){ width="15" }](../../assets/animation/animation2.gif){.glightbox}
    2. Fyll inn "Fri NO" i første tomme felt under "Interesse..." [![Preview](../../assets/images/gallery.svg){ width="15" }](../../assets/animation/animation2.webm){.glightbox}
    3. Trykk på "Generate/Update" [![Preview](../../assets/images/gallery.svg){ width="15" }](../../assets/animation/animation2.mp4){.glightbox}
    4. Slå opp deltaker i STU
    6. Gå til "Other" "Clearance" "Financial Clearance" og fyll inn

        ??? quote "Brukerinput for Financial Clearance"
            Status

            | Brukerinput | Beskrivelse |
            |------|----------------|
            | INO | Innvilget fritak fra norsk |
            | ANO | Avslått fritak fra norsk |

            Dato

            | Brukerinput | Beskrivelse |
            |------|----------------|
            | `DATO` | Dato for behandling av fritaket |

            Beskrivels

            | Brukerinput | Beskrivelse |
            |------|----------------|
            | `FRITEKST` | Tekst som beskriver grunnlag (f.eks. dokumentasjon som er gitt) |
    
    7. Lagre
    8. Slå opp deltaker i STU
    9. Generer brev til deltaker
        - Fritak innvilges: Generer NOVO FRINOK [![Preview](../../assets/images/gallery.svg){ width="15" }](../../assets/animation/animation2.gif){.glightbox}
        - Fritak avslås: Generer NOVO AVFNOK [![Preview](../../assets/images/gallery.svg){ width="15" }](../../assets/animation/animation2.gif){.glightbox}

            ??? quote "Brukerinput for NOVO AVFNOK"
                Du har levert dokumentasjon som følger:

                | Brukerinput | Beskrivelse |
                |------|----------------|
                | `FRITEKST` | Tekst du har skrevet ord for ord etter setningen: Du har levert dokumentasjon som følger: |

                Dokumentasjonen oppfyller ikke kriteriene for fritak fordi

                | Brukerinput | Beskrivelse |
                |------|----------------|
                | `FRITEKST` | Tekst du har skrevet ord for ord etter setningen: Dokumentasjonen oppfyller ikke kriteriene for fritak fordi |

                Kommentar, f eks råd hva som kan gjøres (valgfritt)

                | Brukerinput | Beskrivelse |
                |------|----------------|
                | `FRITEKST` | Tekst du har skrevet ord for ord som eget avsnitt |

    10. Skriv kommentar om utfall i norsk-SPR som ikke har status "BR"



=== "Fritak fra samfunnskunnskap"
    1. Slå opp deltaker i QED [![Preview](../../assets/images/gallery.svg){ width="15" }](../../assets/animation/animation2.gif){.glightbox}
    2. Fyll inn "Fri SAM" i første tomme felt under "Interesse..." [![Preview](../../assets/images/gallery.svg){ width="15" }](../../assets/animation/animation2.webm){.glightbox}
    3. Trykk på "Generate/Update" [![Preview](../../assets/images/gallery.svg){ width="15" }](../../assets/animation/animation2.mp4){.glightbox}
    4. Slå opp deltaker i STU
    6. Gå til "Other" "Clearance" "Academic Clearance" og fyll inn

        ??? quote "Brukerinput for Academic Clearance"
            Status

            | Brukerinput | Beskrivelse |
            |------|----------------|
            | ISA | Innvilget fritak fra samfunnsfag |
            | ASA | Avslått fritak fra samfunnsfag |

            Dato

            | Brukerinput | Beskrivelse |
            |------|----------------|
            | `DATO` | Dato for behandling av fritaket |

            Beskrivels

            | Brukerinput | Beskrivelse |
            |------|----------------|
            | `FRITEKST` | Tekst som beskriver grunnlag (f.eks. dokumentasjon som er gitt) |
    
    7. Lagre
    8. Slå opp deltaker i STU
    9. Generer brev til deltaker
        - Fritak innvilges: Generer NOVO FRISAK [![Preview](../../assets/images/gallery.svg){ width="15" }](../../assets/animation/animation2.gif){.glightbox}
        - Fritak avslås: Generer NOVO AVFSAK [![Preview](../../assets/images/gallery.svg){ width="15" }](../../assets/animation/animation2.gif){.glightbox}

            ??? quote "Brukerinput for NOVO AVFSAK"
                Du har levert dokumentasjon som følger:

                <div class="srl-table">
                
                | Boks | Brukerinput | Beskrivelse |
                |------|----------------|----------------|
                | **Du har levert dokumentasjon som følger:** | `FRITEKST` | Tekst du har skrevet kommer ord for ord etter setning: "Du har levert dokumentasjon som følger:"|
                | **Dokumentasjonen oppfyller ikke kriteriene for fritak fordi** | `FRITEKST` | Tekst du har skrevet kommer ord for ord etter setning: "Dokumentasjonen oppfyller ikke kriteriene for fritak fordi"|
                | **Du har levert dokumentasjon som følger:** | `FRITEKST` | Tekst du har skrevet kommer ord for ord etter setning: "Du har levert dokumentasjon som følger:"|

                </div>

                Dokumentasjonen oppfyller ikke kriteriene for fritak fordi

                | Brukerinput | Beskrivelse |
                |------|----------------|
                | `FRITEKST` | Tekst du har skrevet ord for ord etter setningen: Dokumentasjonen oppfyller ikke kriteriene for fritak fordi |

                Kommentar, f eks råd hva som kan gjøres (valgfritt)

                | Brukerinput | Beskrivelse |
                |------|----------------|
                | `FRITEKST` | Tekst du har skrevet ord for ord som eget avsnitt |

    10. Skriv kommentar om utfall i samfunnskunnskap-SPR som ikke har status "BR"


=== "Fritak grunnet helse"
    1. Slå opp deltaker i STU
    2. Gå til "Other" "Clearance" "Financial Clearance" og fyll inn

        ??? quote "Brukerinput for Financial Clearance"
            Status

            | Brukerinput | Beskrivelse |
            |------|----------------|
            | INH | Innvilget fritak fra norsk og samfunnsfag grunnet helse |
            | ANO | Avslått fritak fra norsk og samfunnsfag grunnet helse |

            Dato

            | Brukerinput | Beskrivelse |
            |------|----------------|
            | `DATO` | Dato for behandling av fritaket |

            Beskrivels

            | Brukerinput | Beskrivelse |
            |------|----------------|
            | `FRITEKST` | Tekst som beskriver grunnlag (f.eks. dokumentasjon som er gitt) |
    
    3. Lagre
    4. Slå opp deltaker i STU
    5. Generer brev til deltaker
        - Fritak innvilges: Generer NOVO FRISAK [![Preview](../../assets/images/gallery.svg){ width="15" }](../../assets/animation/animation2.gif){.glightbox}
        - Fritak avslås: Vi genererer ikke brev får avslåtte søknader om fritak grunnet helse

    6. Skriv kommentar om utfall i samfunnskunnskap-SPR som ikke har status "BR"

??? warning "Søker er aktiv på kurs i norsk eller samfunnskunnskap"
    Dersom søker er aktiv på et kurs burde sentret bli informert om fattet fritak.

## Behandle fritaket i NiR

??? warning "Deltaker finnes ikke i NiR"
    Dersom deltaker ikke finnes i NiR er det sannsynlig at hen ikke har en plikt å søke fritak fra.
    Finnes det derimot grunnlag for fritak burde saken løftes til IMDi support.

Fritak skal registreres i NiR som vedtak for kurstypen det gjelder (norsk eller samfunnskunnskap) med samme datoer som i SITS.