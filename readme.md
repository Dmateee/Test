#Hello
or create a new repository on the command line
echo "# Test" >> README.md  #Fájl létrehozása,az első sorban "#teszt" kerül
git init   #a git mappa inicializálása
git add README.md   #starting, changes azaz a változtatások mentése
git commit -m "first commit"   #változtatások jóváhagyása
git branch -M main        #fejlestési ág átnevezése main-re
git remote add origin https://github.com/Dmateee/Test.git     #távoli repo hozzáadása origin néven 
git push -u origin main       #a fejlesztési ág feltöltése első alkalommal 
…or push an existing repository from the command line
git remote add origin https://github.com/Dmateee/Test.git
git branch -M main
git push -u origin main #feltölti az origin nevű távoli repo-ba a commitokat

További terminal parancsok:
git origin main #a friss repo letöltése 
gi remote -v    #aktuális távoli repo létrehozása
git status    #change, stage, commit állapotának létrehozása
git config --global --list    #globális beálítások listázása
cd  #Change Direktory
cd..  #egy mappával feljebb lép
mkdir <directory name>   #Make directory
mkdir <directory name>    #remove directory
ls    #list - könyvtár listázása
