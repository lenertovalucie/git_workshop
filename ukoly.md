1.  
- Vytvořit na GitHubu nový repozitář a naklonovat jej k sobě
- Vytvořit v naklonovaném repozitáři nový soubor.  
- Soubor přidat do Staging area.  
- Provést commit (se správnou commit zprávou).  
- Změny pushnout do remote repozitáře.  

2.  
- Vytvořit z masteru novou větev (např. feature/exercise).  
- Přepnout se do nové větve.  
- Zkontrolovat, že HEAD se nachází na nové develop větvi.  
- Vytvořit nový soubor.  
- Soubor přidat do Staging area.    
- Provést commit (se správnou commit zprávou).  
- Změny pushnout do remote repozitáře 
- Smazat branch 

3.
- Fork repozitáře: https://github.com/lenertovalucie/git_workshop
- Naklonovat repozitář: https://github.com/lenertovalucie/git_workshop.git
- Přidat upstream repozitář: https://github.com/lenertovalucie/git_workshop.git
- Vytvořit z masteru novou větev (např. feature/exercise).
- Vytvořit v naklonovaném repozitáři nový soubor.  
- Soubor přidat do Staging area.    
- Provést commit (se správnou commit zprávou).  
- Změny pushnout do remote repozitáře.  


### Příkazy:  

git add <cesta k souboru>  # přidání souboru do stage area  
git commit -m <commit zpráva>  # commit změn  

git checkout <branch> # přepnutí se do větve  
git checkout -b <new_branch> # vytvoření nové větve + přepnutí se do této větve  
git branch # seznam větví (hvězdička ukazuje, kde se nachází HEAD)  
git branch -d <branch> # smazaní větve  

git remote –v  # seznam vzdálených repozitářu  
git remote add <remote> <url> # přidání vzdálených repozitářu (přičemž remote je zkrácený název repozitáře)  

git clone <https>  # vytvoření lokální kopie vzdáleného repozitáře  
git push <remote> <branch> # push větve na server (přičemž remote je zkrácený název repozitáře)  
git pull <remote> <branch> # stáhnutí změn do working directory (přičemž remote je zkrácený název repozitáře)  
git fetch <remote> <branch> # stáhnutí změn do local repozitáře (přičemž remote je zkrácený název repozitáře)  
