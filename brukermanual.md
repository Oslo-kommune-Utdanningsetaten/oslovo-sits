Test git: git --version
Tilgang til org 
VSCode med Python extension

Fra CMD (per maskin)
git config --global user.name "Brukernavn"
git config --global user.email "your.email@example.com"

Fra VSCode Terminal
kjør: git clone https://github.com/Oslo-kommune-Utdanningsetaten/oslovo-sits.git



Kjør før hvær endring: git checkout -b feature/setup-mkdocs
Skal si: Switched to a new branch 'feature/add-readme'

Eller hvis vi ikke ønske en ny branch: git checkout feature/setup-mkdocs

Lag filer i mappen (cd MAPPE)

legg til alt: git add .

Se status: git status

Sjekk: git remote -v

Klargjør: git commit -m "Kommentar"

Send til Github: git push origin NAVNpåBRANCHellerMAIN

Fix med gh-deploy