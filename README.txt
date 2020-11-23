
Locale Projekt mit repo in github verbinden
"git remote add origin (COPIERE SSH LINK ODER HTTPS)"
Schritte
1: git init
2: erstelle neue datei lokal
3: erstelle neue repo in git hub
4: verbinde mit oben genante code 
5: folge schritte unten
6: von unten die 4 mit git push -u origin master ersetzen.
   das -u sorgt dafür das ich nur noch git push schreiben mus


So die Schritte sind:git 
1: git status
2:git add . (tut alle Änderungen Local updaten)
3: git commit -m "Kommentar" -m "Genaue Erklärung"
3.5: (Nur einemal, dannach kann es übersprungen werden) 
     git pull -rebase origin main
4: git push origin main (lädt die files in dem jeingen github Repo)

