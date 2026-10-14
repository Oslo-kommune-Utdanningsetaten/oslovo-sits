# Analyse - Quick Analysis

*Quick Analysis* er et verktøy i SITS:Vision som lar deg analysere og sammenligne data direkte fra et utvalg poster uten å eksportere dem først. Funksjonen er tilgjengelig fra Misc-menyen når mer enn én post er hentet.

## Matematiske analyser

*Quick Analysis* kan utføre en rekke statistiske beregninger på et valgt felt, blant annet:

	Antall poster
	Antall unike verdier
	Minimums- og maksimumsverdi
	Sum og gjennomsnitt
	Median
	Modus (mest vanlige verdi)
	Standardavvik

## Analyse av et felt. 


**Eksempel: Finne antall aktive på de ulike programmene**

Filtrer fram alle aktive på ditt VO-senter.
Deretter markerer du feltet med program og gå så til menyen Misc og velg Quick Analysis. [![bilde](../assets/images/gallery.svg){width="15"}](../../assets/images/quick_analysis_1.png){.glightbox}

Som standard er det valgt Matematisk analyse og feltet du vil analysere er fylt inn.
Klikk på OK for å få fram analysen. [![bilde](../assets/images/gallery.svg){width="15"}](../../assets/images/quick_analysis_2.png){.glightbox}

I skjermbildet som du nå har fått fram vil du se de ulike verdiene i program.
Resultatene kan presenteres både som tabeller og grafiske fremstillinger.
Til høyre i skjermbildet kan du velge ulike grafer som kakediagram, søylediagram eller linjediagram.



## Kryssanalyser (Cross Reference)

Verktøyet kan også lage krysstabeller mellom to felt.

**Eksempel: Finne antall aktive på de ulike programmene og derers rettighet**

Filtrer fram alle aktive på ditt VO-senter.
Deretter markerer du feltet med program og gå så til menyen Misc og velg Quick Analysis.
Her velger du *Cross reference* [![bilde](../assets/images/gallery.svg){width="15"}](../../assets/images/quick_analysis_3.png){.glightbox}

I feltet for kolonne (Col. Field) kan du skrive inn koden for feltet der rettighetene er lagret (SPR_UDF1)
Klikk på OK for å få fram analysen. [![bilde](../assets/images/gallery.svg){width="15"}](../../assets/images/quick_analysis_4.png){.glightbox}

I skjermbildet som du nå har fått fram vil du se de ulike verdiene i program.
Til høyre i skjermbildet kan du velge ulike grafer; kakediagram, søylediagram, linjediagram.

??? warning "Jeg finner ikke koden for feltet som jeg vil analysere"

    Gå tilbake til skjermbildet du vil analysere i fra. Velg feltet du ønsker å kjøre analyse på ved å klikke i det feltet (en gang).
	Trykk F1 for å få opp Hjelpmenyen.
	Kopier koden fra FIELD. Feks SPR_UDF1.SPR
	Nå kan du lukke hjelpmenyen og når du er tilbake i skjermbildet for Analyse kan du lime inn verdien fra feltet som du kopierte.



## Eksport av analyse
Diagrammer kan ikke eksporteres direkte, men kan lagres som skjermbilder.

Analyseresultatene kan eksporteres til f.eks *HTML* ved å klikke på *Export*-knappen og deretter skrive inn HTML i feltet for *Exchange Format*.
Velg mappen du vil eksportere til og klikk OK.
Dette gjør det enkelt å lime inn resultatene i for eksempel Excel, e-post eller rapporter.