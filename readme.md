# Rutiner for bruk av SITS i Oslo VO

## Hva skal være med her?

Steg for steg rutiner for prosessene ansatte i Oslo VO som bruker SITS Live og/eller SITS eVision møter.

## Hva skal ikke være med her?

Følgende skal ikke og er ikke med i bruksrutinene:

- Persondata (heller ikke som eksempel)
- Beskrivelse av dataprosesser for systemansvarlige
- Navn på databasefelt


## Krav

Rutinene bygger på mkdocs.
Har man Python kan man åpne mappen i terminalen og hente nødvendig programvare med:

```
pip install -r krav.txt
```

Kan og gjerne sette følgende i PoweShell (holder med en gang.)
```
[Environment]::SetEnvironmentVariable("NO_MKDOCS_2_WARNING", "1", "User")
```

## Kommandoa

py -m mkdocs serve

py -m mkdocs gh-deploy

git pull

git add .

git commit -m "Hva har du endret?"

git push origin main