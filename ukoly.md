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

### Příkazy:  

git clone <gitlab project directory>  # stáhnutí repozitáře  
git add <path to file>  # přidání souboru do stage area  
git commit -m <correct commit message>  # commit změn  
git push <remote> <branch> # push větve na gitlab server (přičemž remote je název repozitáře, defaultní název je origin)  

git checkout <branch> # přepnutí se do větve  
git checkout -b <new_branch> # vytvoření nové větve + přepnutí se do této větve  
git branch # seznam větví (hvězdička ukazuje, kde se nachází HEAD)  
git branch -d <branch> # smazaní větve  

git fetch # stáhnutí změn na remote repozitáři
