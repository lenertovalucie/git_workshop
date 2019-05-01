1.  
- Vytvořit na GitHubu nový repozitář a naklonovat jej k sobě
- Vytvořit v naklonovaném repozitáři nový soubor.  
- Soubor přidat do Staging area.  
- Provést commit (se správnou commit zprávou).  
- Změny pushnout do remote repozitáře.  

2.  
- Přepnout se do master větve, pokud se na ní nenacházíte.  
- Vytvořit z masteru novou větev (např. feature/exercise).  
- Přepnout se do nové větve.  
- Zkontrolovat, že HEAD se nachází na nové develop větvi.  
- Vytvořit nový soubor.  
- Soubor přidat do Staging area.    
- Provést commit (se správnou commit zprávou).  
- Změny pushnout do remote repozitáře 
- Smazat branch 

3.
- Fork repozitáře: 
- Naklonovat repozitář:
- Přidat repozitář
- Vytvořit feature branch
- Vytvořit v naklonovaném repozitáři nový soubor.  
- Soubor přidat do Staging area.  
- Provést commit (se správnou commit zprávou).  
- Změny pushnout do remote repozitáře.  


### Příkazy:  

git clone <https>  # stáhnutí repozitáře  
git add <cesta k souboru>  # přidání souboru do stage area  
git commit -m <commit zpráva>  # commit změn  
git push <remote> <branch> # push větve na gitlab server (přičemž remote je název repozitáře, defaultní název je origin)

git checkout <branch> # přepnutí se do větve  
git checkout -b <new_branch> # vytvoření nové větve + přepnutí se do této větve  
git branch # seznam větví (hvězdička ukazuje, kde se nachází HEAD)  
git branch -d <branch> # smazaní větve  

git remote –v  # seznam remote repozitářu  
git remote add <zkrácený název> <url> # přidání vzdálených repozitářu

git pull <remote> <branch> # stáhnutí změn a jejich zamergvání do working directory (přičemž remote je název repozitáře)
git fetch <remote> <branch> # stáhnutí změn do local repozitáře
