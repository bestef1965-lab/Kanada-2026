GitHub Pages Upload – einfache Variante

Diese ZIP ist speziell fuer GitHub Pages vorbereitet:
- index.html liegt direkt im Hauptverzeichnis.
- 404.html ist eine Kopie der Startseite.
- .nojekyll ist enthalten.

So verwenden:
1. ZIP entpacken.
2. In GitHub ein Repository erstellen.
3. Den INHALT des entpackten Ordners hochladen, nicht den Ordner selbst.
   Wichtig: index.html muss direkt auf oberster Ebene im Repository sichtbar sein.
4. Repository > Settings > Pages.
5. Source: Deploy from a branch.
6. Branch: main, Folder: /root.
7. Speichern.
8. 1–5 Minuten warten und die GitHub-Pages-URL erneut öffnen.

Typische 404-Ursachen:
- der komplette Ordner wurde hochgeladen, sodass index.html eine Ebene zu tief liegt
- GitHub Pages steht auf /docs statt /root
- Branch ist nicht main
- Deployment ist noch nicht fertig
- Repository ist privat ohne passenden Pages-Tarif
