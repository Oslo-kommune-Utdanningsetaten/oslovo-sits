# Endre rettigheter på en deltaker

??? warning "Deltaker har ikke eksisterende SPR"

    Deltakerer uten eksisterende SPR endrer ikke rettighet, de får en.
    Nye deltakerer med norskrettigheter skal via servicesenteret.
    Nye deltakere uten norskrettigheter skal registreres etter egen rutine.

??? warning "Deltaker har en SPR med det programmet og rettigheten jeg vil sette den på"

    Hvis både Program og rettighet (i UDF) finnes i en SPR kan du bruke den.
    Da setter du Status på SPR du endrer fra til BR og gjør den du vil ha til AP.

## Lage ny SPR ved endring av rettighet

1. Gå til eVision ⇒ *SITS bruker* ⇒ *Lage ny SPR ved endring av program/rettighet*

2. Søk opp deltaker du skal behandle

    ??? warning "Deltaker har flere SPR"

        Har deltaker flere SPR tar vi utgangspunkt i den SPR som deltaker bytter rett fra.
        Oftest er dette den nyeste norsk-spr.

3. Klikk *Fortsett* for SPR du tar utgangspunkt i

4. Fyll inn felt med nye verdier

    ??? question "Skal jeg lage samfo SPR?"

        Hvis deltaker får RETT eller REPL som ny rettighet, og ikke har samfo-spr fra før, skal det lages en ny Samfo-spr.

    ??? question "Skal jeg flytte kursaktivitet?"

        Hvis deltaker gikk en periode på en annen rettighet, og du ønsker å markere denne som del av ny rettighet, velger du ja her.
        Da vil kursaktivitet fom. *Dato fra* flyttes over til ny spr.
        Ikke gjør dette med mindre du er sikker på at aktivitet skal flyttes.

5. Trykk *Fortsett*

6. Se gjennom endringene og trykk *Fullfør*

    ??? warning "Jeg ser at endringene ble feil"

        Da må du registrere en forespørsel i USD for å få dette rettet opp.
        Beskriv situasjonen, og ønsket resultat.


## Fatte vedtak ved endring til NiR-rettighet

1. [Filtrer frem deltaker](../felles/guie.pdf.md#filtrere-i-sits) i skjermbildet *STU*[![bilde](../assets/images/gallery.svg){width="15"}](../../assets/images/meny_skjermbilde.webp){.glightbox}

2. Generer [*NOVO FORVED*](../felles/guide_pdf.md){.glightbox} og vurder om deltaker har et vedtak som passer rettigheten den skal være på

    ??? warning "Deltaker har allerede et vedtak"

        Har allerede deltaker et vedtak som stemmer med rettigheten trenger du ikke å gå videre.

        Hvis deltaker har et vedtak med en annen rettighet må dette markeres som avbrutt i SPD før du går videre.

3. [Filtrer frem deltaker](../felles/guie.pdf.md#filtrere-i-sits) i skjermbildet *STU*[![bilde](../assets/images/gallery.svg){width="15"}](../../assets/images/meny_skjermbilde.webp){.glightbox}

4. Sett feltet *Rettigheter* til ønsket rettighet

5. [Filtrer frem deltaker](../felles/guie.pdf.md#filtrere-i-sits) i skjermbildet *SAD*[![bilde](../assets/images/gallery.svg){width="15"}](../../assets/images/meny_skjermbilde.webp){.glightbox}

6. Fyll inn riktige datoer for deltaker i SAD

    |     |     |
    | --- | --- |
    | NIR Kategori fra | Dato hentes fra NiR |
    | NIR 1.opph.vedt | Dato hentes fra NiR |
    | Integr. Frist fra | Deltakere med Kategori fra før 01.08.2023: Samme dato som NiR Kategori fra.<br>Deltakere med Kategori etter 01.08.2023: Første deltatte time med rettighet |
    | Utd. & norskmål | NI/NG/NV (avhengig av utdanningsnivå) etterfulgt av norskmål |
    | Integr.36/18/300 | Deltakere med plikt skal ha 300. Ellers skal NI og NG ha 36, mens NV skal ha 18. |
    | Integr. Frist NO | Tom for pliktere. Ellers 18 eller 36 måneder etter Integr. Frist fra |
    | Integr. Frist SF | 12 måneder etter Integr. Frist fra |

    ??? warning "Mange verdier her er fylt ut allerede"

        En deltaker som kan få rettigheter vil få mange av disse fylt ut av servicesenteret ved innsøking.
        Se gjennom at de er riktige, og fyll ut mangler.

    ??? warning "Deltaker er i introduksjonsloven"

        Da fyller du ut følgende bokser i stedet:
        |     |     |
        | --- | --- |
        | NIR Kategori fra | Dato hentes fra NiR |
        | NIR 1.opph.vedt | Dato hentes fra NiR |
        | NIR 3-årsfrist | 36 måneder etter NIR 1.opph.vedt |

    ??? hint "SITS kan beregne Frist NO og Frist SF for deg"

        Hvis det bare er de to siste boksene som er tom vil SITS beregne fristene over natten.

7. Generer [*NOVO VEDTAK*](../felles/guide_pdf.md){.glightbox}

8. Generer [*NOVO IPNOR1*](../felles/guide_pdf.md){.glightbox}

    IP skal basere seg på informasjon fra Servicesenteret.
    Er det mangler, må deltaker bli kartlagt etter servicesenterets rutiner.

9. Registrer vedtaket i NiR - Husk å markere samfo-språk hvis de skal ha samfo-spr