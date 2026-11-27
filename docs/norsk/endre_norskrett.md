# Endre norsk-rettighet

Når en deltaker får endret rettighet i NiR, må vi oppdatere rettigheten i SITS, sørge for at deltaker har riktig SPR og sjekke at deltaker har et vedtak som stemmer med den nye rettigheten.

Riktig rettighet på SPR er viktig for økonomirapporter, timebekreftelser, vedtak og tilbudsbrev, og for å beholde historikken til deltaker.

??? warning "Deltaker flytter til eller fra Oslo"

    Se egen rutine for [behandling av deltakere som flytter](../norsk/flytter.md){.glightbox}.

??? warning "Deltaker har utgående eller utgått rett til opplæring"

    Se rutinene for å [finne deltakere med utgående rett](../norsk/utgående_rett.md){.glightbox} og [sluttføre deltaker ved utgått rett](../norsk/utgått_rett.md){.glightbox}.

??? warning "Det ligger allerede timer på SPR"

    Program og rettighet på en SPR det ligger timer på skal ikke endres.

    Det skal finnes én SPR pr. rettighet for hvert fag. Hvis deltaker har hatt den nye rettigheten tidligere, bruker vi SPR-en som finnes fra før.

    Se [rutine for endring av rettighet](../felles/endre_rett.md){.glightbox}.

## Sjekke rettighet i NiR

1. Slå opp deltaker i NiR og sjekk hvilken rettighet deltaker har.

    Rettigheter som ikke lenger er gjeldende vises i kursiv, med en kommentar i parentes, f.eks. *(ikke gjeldende)*. Plikten kan også være markert som *(Gjennomført)* eller *(Fritatt)*. [![bilde](../assets/images/gallery.svg){width="15"}](../assets/images/tmp.webp){.glightbox}

2. Sjekk hvilket lovverk deltaker er omfattet av.

3. Sjekk gjennomførte timer og eventuelle fritak i norsk og samfunnskunnskap.

    ??? warning "Rettighetene i norsk og samfunnskunnskap er forskjellige"

        NiR viser rettighetene for norsk og samfunnskunnskap samlet. Det kan derfor se ut som om deltaker ikke har gjennomført plikten i noen av fagene selv om plikten i ett av fagene er gjennomført.

        Det kan også stå *Rett til norsk/samf kunnskap (Ved behov)* selv om behovsprøvd opplæring bare gjelder norsk.

        Se derfor alltid på gjennomførte timer og eventuelle fritak i tillegg til det som står under *Kategori*. [![bilde](../assets/images/gallery.svg){width="15"}](../assets/images/tmp.webp){.glightbox}

        I SITS behandles fagene hver for seg. En deltaker omfattet av introduksjonsloven kan f.eks. ha REPL i norsk pga. rett til behovsprøvd opplæring, men PLIKT i samfunnskunnskap pga. utgått 3-årsfrist.

        Rettigheten i STU skal stemme med rettigheten på den gjeldende norsk-SPR-en, evt. grunnskole-SPR-en. Rettigheten på samfunnskunnskaps-SPR trenger ikke være den samme.

## Endre rettighet etter integreringsloven

Ved endring av rettighet pga. ny oppholdstillatelse får deltaker nye frister for opplæring. Det må lages SPR med den nye rettigheten, oppdateres informasjon i SAD og fattes nytt vedtak.

Det vanligste er at deltaker går fra PLIKT til REPL, dvs. fra betalt til gratis opplæring, men det motsatte kan også forekomme.

### Oppdatere SAD

1. [Filtrer frem deltaker](../felles/guide.md#filtrere-i-sits) i skjermbildet *SAD* [![bilde](../assets/images/gallery.svg){width="15"}](../assets/images/meny_skjermbilde.webp){.glightbox}

2. Finn datoene for den nye rettigheten i NiR og oppdater *NIR Kategori fra* og *NIR 1.opph.vedt* i SAD. [![bilde](../assets/images/gallery.svg){width="15"}](../assets/images/tmp.webp){.glightbox}

    | Felt | Hvor finner jeg datoen? |
    | --- | --- |
    | NIR Kategori fra | Gå til *NIR* ⇒ *Norsk timer/norskmål* eller *Samfunnskunnskap* i NiR og finn datoen som står under *Kategori fra*. [![bilde](../assets/images/gallery.svg){width="15"}](../assets/images/tmp.webp){.glightbox} |
    | NIR 1.opph.vedt | Gå til *Grunndata* ⇒ *Grunndata detaljer* i NiR. Klikk på *Vis alle endringer* under *Oppholdstillatelser*. Finn vedtaksdatoen for den første oppholdstillatelsen som utløste den nye rettigheten. [![bilde](../assets/images/gallery.svg){width="15"}](../assets/images/tmp.webp){.glightbox} |

    ??? warning "Deltaker har flere oppholdsvedtak"

        Det er vedtaksdatoen for den første oppholdstillatelsen som utløste den aktuelle rettigheten som skal registreres, ikke nødvendigvis datoen for det første eller det siste oppholdsvedtaket.

        Ved endring av rettighet overskrives datoene fra den gamle rettigheten.

    ??? warning "Ankomstdato eller effektueringsdato i NiR er forskjellig fra Kategori fra"

        Bruk datoen som står under *Kategori fra* i NiR.

        Ankomstdato og effektueringsdato under Grunndata kan være misvisende, f.eks. hvis oppholdstillatelsen er søkt om fra Norge av en arbeidsgiver eller et familiemedlem, eller hvis oppholdstillatelsen er fornyet.

        Feltet *NIR Kategori fra* i SAD het tidligere *Ankomstdato* og deretter *Opph. effektuert*.

3. Oppdater informasjonen som gjelder opplæring med den nye rettigheten.

    | Felt | Verdi |
    | --- | --- |
    | Integr.36/18/300 | 300 for PLIKT. For REPL avhenger det av medbrakt utdanning: 36 for NI og NG, og 18 for NV. |
    | Obl. prøver - NIR | Oppdateres iht. ny rettighet. Ved overgang fra PLIKT til REPL får deltaker også rett og plikt til å ta prøve i norsk og samfunnskunnskap. |
    | Ant. timer SF | Sjekk at riktig timetall er registrert. |

    ??? warning "Deltaker hadde et NiR-relevant oppholdsvedtak før 01.01.2022"

        Deltaker beholder plikten til 50 timer samfunnskunnskap selv om den nye rettigheten gjelder fra etter 01.01.2022.

        Fra 01.01.2022 ble timetallet for samfunnskunnskap endret fra 50 til 75 timer.

4. Oppdater fristene iht. når deltaker fikk oppholdstillatelsen som utløste den nye rettigheten.

    === "Ny oppholdstillatelse før 01.08.2023"

        Fristene beregnes fra *NIR Kategori fra*.

        | Felt | Verdi |
        | --- | --- |
        | Integr. Frist fra | Samme dato som NIR Kategori fra |
        | Integr. Frist NO | 18 eller 36 måneder etter Integr. Frist fra, avhengig av medbrakt utdanning. Tom for PLIKT. |
        | Integr. Frist SF | 12 måneder etter Integr. Frist fra |

        [![bilde](../assets/images/gallery.svg){width="15"}](../assets/images/tmp.webp){.glightbox}

    === "Ny oppholdstillatelse fra 01.08.2023"

        Fristene skal beregnes fra oppstart av det første tilbudet om opplæring med den nye rettigheten.

        Tøm følgende felt:

        - Integr. Frist fra
        - Integr. Frist NO
        - NO oppd.dato
        - Integr. Frist SF
        - SF oppd.dato

        [![bilde](../assets/images/gallery.svg){width="15"}](../assets/images/tmp.webp){.glightbox}

        Datoene vil bli fylt ut automatisk når tilbudsbrevet lages etter at deltaker er plassert på kurs på SPR med den nye rettigheten.

        Dette forutsetter at datofeltene er tomme når tilbudsbrevet lages.

    ??? warning "Deltaker har hatt permisjon med den gamle rettigheten"

        Sjekk sluttdatoen for siste permisjon i NiR eller SPD.

        Hvis permisjonen er avsluttet før den nye rettigheten begynner å løpe, påvirker den ikke de nye fristene.

        Hvis deltaker fortsatt har permisjon når den nye rettigheten begynner å løpe, utvides de nye fristene med de dagene som gjenstår av permisjonen.

        NiR skal kunne beregne dette. Hvis de nye fristene er beregnet i NiR, registreres de i SAD.

        Hvis NiR foreløpig ikke kan beregne fristene fordi oppstartdato for opplæring ikke er kjent, skal fristfeltene i SAD fortsatt være tomme.

        Se også [rutine for permisjon fra opplæring](../norsk/permisjon_norsk.md){.glightbox}.

5. Lagre.

### Lage SPR med ny rettighet

1. Spør deltaker om ønsket tid og omfang for nytt tilbud ved overgang fra betalt til gratis opplæring, eller motsatt.

2. Lag SPR med den nye rettigheten etter [rutine for endring av rettighet](../felles/endre_rett.md#lage-ny-spr-ved-endring-av-rettighet){.glightbox}.

    Det skal lages SPR med den nye rettigheten for både norsk og samfunnskunnskap.

    ??? warning "Deltaker har allerede fullført ett av fagene"

        Hvis deltaker har fullført opplæringen i ett av fagene, trenger du ikke lage ny SPR for dette faget.

3. Sjekk at *Rettigheter* i STU stemmer med rettigheten på den nye norsk-SPR-en.

4. Registrer deltakers ønsker for nytt tilbud i UDF på den nye norsk-SPR-en. [![bilde](../assets/images/gallery.svg){width="15"}](../assets/images/meny_udf.webp){.glightbox}

    | Felt | Verdi |
    | --- | --- |
    | Tid/omfang første prioritet (SPR_UDF9) | Deltakers ønske for tid og omfang |
    | Tid/omfang oppdatert (SPR_UDFA) | Dato for oppdatering av ønsket |

    [![bilde](../assets/images/gallery.svg){width="15"}](../assets/images/tmp.webp){.glightbox}

    Hvis det er laget ny søknad på servicesenteret, kommer verdiene automatisk over fra ACD til SPR. På skolene må feltene fylles ut manuelt.

5. Behandle deltaker videre ut fra om deltaker skal ha nytt tilbud eller fortsette i samme tilbud.

    === "Deltaker står på søkerliste eller skal ha nytt tilbud"

        Sett deltaker på søkerliste med *SPR status* L1. Dette kan gjøres både på servicesenteret og på skolen.

        Hvis deltaker er aktiv på den gamle SPR-en, avsluttes opplæringen der.

        Timetellingen på den nye SPR-en starter med det nye tilbudet.

    === "Deltaker fortsetter i samme tilbud"

        Timer og fravær fra og med rettighetsendringen skal ligge på SPR med den nye rettigheten.

        [Flytt timer og fravær mellom SPR-ene](../felles/flytte_timer.md){.glightbox}.

    ??? warning "Hvilken kursstart setter i gang fristene?"

        For deltakere som har fått ny rettighet fra 01.08.2023 beregnes fristene fra første kursdag på SPR med den nye rettigheten.

        Dette gjelder også hvis tilbudsbrevet lages med en senere oppstartdato.

        Hvis deltaker får tilbud om samfunnskunnskap med oppstart før norskkurset, er det oppstart av samfunnskunnskap som setter i gang fristene.

        Foreldreveiledning og kurs i livsmestring setter ikke i gang fristene.

### Fatte nytt vedtak ved endring av rettighet

1. [Filtrer frem deltaker](../felles/guide.md#filtrere-i-sits) i skjermbildet *SPD* [![bilde](../assets/images/gallery.svg){width="15"}](../assets/images/meny_skjermbilde.webp){.glightbox}

2. Sett vedtaket med den gamle rettigheten til status AVBRUTT_RP/P/R, avhengig av rettigheten på vedtaket.

    ??? warning "Jeg kan ikke fatte nytt vedtak ennå"

        Det gamle vedtaket skal settes til avbrutt selv om det nye vedtaket ikke kan fattes ennå.

        Hvis det gamle vedtaket fortsatt ligger som gyldig i SPD, vil det ikke bli fanget opp at deltaker mangler gyldig vedtak med den nye rettigheten.

3. Sjekk om fristene for den nye rettigheten er beregnet i SAD.

    === "Fristene er beregnet"

        Vedtak kan fattes med en gang, enten av servicesenteret eller av skolen.

    === "Fristene er ikke beregnet"

        Vedtak kan først fattes etter at deltaker har fått tilbud og fristdatoene er lagt inn i SAD.

4. Fatt vedtak med den nye rettigheten i NiR etter [rutine for NiR-vedtak](../norsk/vedtak.md){.glightbox}.

5. Sjekk at fristene i SAD stemmer med fristene i NiR etter at vedtaket er registrert.

    Sjekk spesielt om fristene er utvidet pga. permisjon som fortsatt gjelder, og oppdater fristene i SAD ved behov.

6. Sjekk hvilke norskmål deltaker har i den gjeldende norskplanen.

    Du kan finne disse i SPD eller ved å generere [*FOVO VEDOVR*](../felles/guide_pdf.md){.glightbox} fra STU.

7. Generer [*NOVO VEDTAK*](../felles/guide_pdf.md){.glightbox} fra STU med den nye rettigheten.

    ??? warning "Deltaker skal også endre norskmål"

        Endring av norskmål skal være en bevisst endring etter avtale med deltaker.

        Da bør du også generere ny [*NOVO IPNOR1*](../felles/guide_pdf.md){.glightbox}.

        Se [rutine for endring av norskplan](../norsk/endre_norskplan.md){.glightbox}.

??? tip "Fange opp deltakere som ikke har fått vedtak etter rettighetsendring"

    Deltakere som mangler vedtak etter rettighetsendringen vil komme med i rapporten NSER FRIST som servicesenteret tar ut.

    Servicesenteret kan da fatte vedtak i NiR og SITS eller be skolen om å gjøre det.

## Endre rettighet etter introduksjonsloven

Rettighetene ASYL, REPL, RETT og PLIKT i UDF på SPR (SPR_UDF1) er knyttet til programmet NNIR.

For norskopplæring brukes *Kursnivå* N. For asylnorsk brukes Studieløp AN* i stedet for N*.

??? tip "Deltaker får opplæring tilrettelagt som spesialundervisning"

    Følgende rettighetskoder brukes tilsvarende:

    | Ordinær rettighet | Tilrettelagt opplæring |
    | --- | --- |
    | ASYL | ASYL42 |
    | REPL | REPL42 |
    | RETT | RETT42 |
    | PLIKT | PLIK42 |

Bruk [rutine for endring av rettighet](../felles/endre_rett.md){.glightbox} for å lage SPR med ny rettighet eller aktivere en SPR som deltaker har fra før.

Sjekk at rettigheten i STU stemmer med rettigheten på den gjeldende norsk-SPR-en.

### Fra ASYL til REPL

1. Sjekk om deltaker har gjennomført asylnorsk.

    | Gjennomført asylnorsk | SPR status på gammel ASYL-SPR | Ny rettighet |
    | --- | --- | --- |
    | 175 timer | FF | REPL |
    | Under 175 timer | BR | REPL |

2. Lag eller aktiver NNIR/REPL-SPR for deltaker som har fått oppholdstillatelse som utløser rett og plikt.

    Se også [rutine for behandling av asyl-deltakere](../norsk/asyl.md){.glightbox}.

### Fra PLIKT til REPL

1. Sjekk i NiR om deltaker har fått endret rettighet pga. ny oppholdstillatelse.

2. Sjekk om 3-årsfristen er gått ut.

    === "3-årsfristen er ikke gått ut"

        Sett *SPR status* på gammel PLIKT-SPR til BR, også hvis den allerede har status FF.

        Lag eller aktiver NNIR/REPL-SPR.

    === "3-årsfristen er gått ut"

        Deltaker må betale for opplæringen og fortsetter på PLIKT-SPR til 550 timer norsk er gjennomført.

3. Sjekk i SPD om deltaker allerede har gyldig vedtak om 600 timer.

    Hvis deltaker har et vedtak om 300 timer og skal ha et vedtak om 600 timer, settes det gamle vedtaket til AVBRUTT og det fattes nytt vedtak.

    Se [rutine for NiR-vedtak](../norsk/vedtak.md){.glightbox}.

    ??? warning "Deltaker har begynt på grunnskole"

        Hvis deltaker har begynt på grunnskole og ikke har permanent oppholdstillatelse, må deltaker informeres om at det er viktig å fullføre den nye plikten til norskopplæring.

### Fra REPL til PLIKT pga. utgått 3-årsfrist

Fra august 2020 kan deltaker fortsette på REPL-SPR selv om 3-årsfristen er gått ut og plikten til norskopplæring ikke er gjennomført.

Forutsetningen er at:

- Deltaker har søkt eller resøkt opplæring før 3-årsfristen går ut.
- Deltaker ikke avslår tilbud om opplæring etter 3-årsfristen før plikttimene er gjennomført.
- Deltaker ikke har ugyldig fravær før plikttimene er gjennomført.

=== "Deltaker oppfyller vilkårene"

    Deltaker fortsetter på REPL-SPR med status AP eller aktuell søkerlistestatus (L*).

=== "Deltaker oppfyller ikke vilkårene"

    1. Sett *SPR status* på gammel REPL-SPR til BR.
    2. Lag eller aktiver NNIR/PLIKT-SPR.

    Deltaker fortsetter på PLIKT-SPR til 550 timer norsk er gjennomført, eller til deltaker får fritak fra norskopplæring.

### Fra PLIKT til REPL ved rett til behovsprøvd opplæring

Hvis deltaker har gått på PLIKT-SPR pga. utgått 3-årsfrist og nå har gjennomført plikten, enten ved å ha deltatt 550 timer norsk eller ved å ha fått fritak, kan deltaker ha rett til behovsprøvd norskopplæring.

1. Sjekk i NiR om deltaker har rett til behovsprøvd norskopplæring.

2. Sett *SPR status* på PLIKT-SPR til BR.

3. Aktiver REPL-SPR som deltaker hadde fra før, eller lag ny NNIR/REPL-SPR hvis deltaker ikke har en fra før.

    ??? warning "Deltaker har REPL og har gjennomført plikttimene"

        Rettigheten REPL beholdes ved overgang til behovsprøvd norskopplæring. Deltaker skal ikke ha ny SPR med RETT bare fordi plikttimene er gjennomført eller deltaker har fått fritak.

### Fra REPL til RETT ved fylte 55 år

Dette gjelder deltakere som fikk sin første oppholdstillatelse som utløste rettigheter etter introduksjonsloven før 2017.

Når disse deltakerne fyller 55 år, faller plikten bort. Dette gjelder også deltakere som allerede har gått over til behovsprøvd opplæring.

1. Sett *SPR status* på gammel REPL-SPR til BR.

2. Lag eller aktiver NNIR/RETT-SPR.

    ??? warning "Deltaker fikk sin første NiR-relevante oppholdstillatelse fra 2017"

        Disse deltakerne har plikt frem til fylte 67 år.

    ??? question "Deltaker har PLIKT og fyller 55 år"

        Deltakere med PLIKT og første NiR-relevante oppholdstillatelse før 2017 kan fortsette på PLIKT-SPR til 250 timer norsk er gjennomført.

        Deretter sluttføres deltaker med status FF.

        Ønsker deltaker mer norskopplæring, lages eller aktiveres NBET/BETAL-SPR.

## Endre rettighet i samfunnskunnskap etter introduksjonsloven

For samfunnskunnskap brukes *Kursnivå* SF. For norsk kultur og norske verdier for asyl-deltakere brukes *Kursnivå* KUL.

Rettigheten på samfunnskunnskaps-SPR kan være forskjellig fra rettigheten på norsk-SPR.

### Fra ASYL til REPL

| Gjennomført norsk kultur og norske verdier | SPR status på gammel ASYL-SPR (KUL) | Ny SPR |
| --- | --- | --- |
| 50 timer | FF | NNIR/REPL med Kursnivå SF |
| Under 50 timer | BR | NNIR/REPL med Kursnivå SF |

Ny SPR med REPL lages når deltaker har fått oppholdstillatelse som utløser rett og plikt.

### Fra PLIKT til REPL

Hvis deltaker får rett og plikt pga. ny oppholdstillatelse før 50 timer samfunnskunnskap er gjennomført, må du sjekke om deltaker allerede har betalt for opplæringen.

=== "Deltaker har betalt for resten av opplæringen"

    Deltaker fullfører opplæringen på PLIKT-SPR.

=== "Deltaker har ikke betalt"

    Sett *SPR status* på gammel PLIKT-SPR til BR og lag eller aktiver REPL-SPR.

=== "Det er ikke sendt ut tilbudsbrev"

    Hvis det ikke ligger timer fra Oslo VO på PLIKT-SPR, kan rettigheten på SPR endres fra PLIKT til REPL.

Sjekk i SPD om deltaker har et gyldig vedtak om 600 timer.

Hvis ikke, sett 300-timersvedtaket til AVBRUTT og fatt nytt vedtak om 600 timer ved å generere [*NOVO FORVED*](../felles/guide_pdf.md){.glightbox} fra STU.

Informer også deltakers norsksenter om endringen av rettighet.

### Fra REPL til PLIKT pga. utgått 3-årsfrist

=== "Deltaker er aktiv eller venter på tilbud"

    Hvis deltaker er aktiv når 3-årsfristen går ut, eller har søkt innen fristen går ut og ennå ikke har fått tilbud, fortsetter deltaker på REPL-SPR med status AP eller SG.

=== "Deltaker oppfyller ikke vilkårene"

    Hvis deltaker ikke oppfyller vilkårene, eller slutter før plikten er gjennomført, settes *SPR status* på gammel REPL-SPR til BR.

    Lag eller aktiver PLIKT-SPR.

    Deltaker fortsetter på PLIKT-SPR til 50 timer samfunnskunnskap er gjennomført eller deltaker har fått fritak.

### Fra REPL til RETT ved fylte 55 år

For deltakere med første NiR-relevante oppholdstillatelse før 2017 faller plikten bort ved fylte 55 år.

1. Sjekk om det ligger timer fra Oslo VO på REPL-SPR.

    === "Det ligger timer på SPR"

        Sett *SPR status* på gammel REPL-SPR til BR og lag eller aktiver RETT-SPR.

    === "Det ligger ikke timer på SPR"

        Rettigheten på REPL-SPR kan endres til RETT.

    ??? question "Deltaker har PLIKT og fyller 55 år"

        Deltaker kan fortsette på PLIKT-SPR til 50 timer samfunnskunnskap er gjennomført.

        Deretter settes status til FF. Etter at de siste timene er overført til NiR, settes *Studieløp* til FSAM.

### Deltaker har fått fritak fra samfunnskunnskap

1. Sett *SPR status* på alle samfunnskunnskaps-SPR til FT.

2. Hvis deltaker fortsatt har rett til opplæring og ønsker å fullføre 50 timer samfunnskunnskap, aktiveres REPL- eller RETT-SPR med status SG, LS eller AP.

    ??? warning "Deltaker har gått på PLIKT-SPR pga. utgått 3-årsfrist"

        Hvis deltaker har fått fritak, men fortsatt har rett til å fullføre opplæringen og ønsker dette, settes PLIKT-SPR til BR.

        Aktiver REPL-SPR som deltaker har fra før, eller lag ny hvis deltaker ikke har en fra før.

3. Når 50 timer samfunnskunnskap er gjennomført settes *SPR status* til FF.