GitHub Pages 404 – bitte genau prüfen

Diese ZIP funktioniert mit zwei GitHub-Pages-Einstellungen:

VARIANTE A: /root
1. Lade den INHALT dieses Ordners in dein Repository hoch.
2. Im Repository muss index.html direkt sichtbar sein.
3. Settings > Pages:
   Source: Deploy from a branch
   Branch: main
   Folder: /root
4. Save, danach 1-5 Minuten warten.

VARIANTE B: /docs
1. Lade den INHALT dieses Ordners in dein Repository hoch.
2. Der Ordner docs muss im Repository sichtbar sein.
3. Settings > Pages:
   Source: Deploy from a branch
   Branch: main
   Folder: /docs
4. Save, danach 1-5 Minuten warten.

Wichtig:
- Nicht die ZIP selbst hochladen.
- Nicht den äußeren Ordner als Unterordner hochladen, sondern dessen Inhalt.
- index.html muss klein geschrieben sein.
- GitHub Pages kann einige Minuten brauchen.
- Prüfe unter Actions, ob der Pages-Build erfolgreich war.
- Wenn dein Repository z. B. kanada2026 heißt, lautet die Adresse meistens:
  https://DEINNAME.github.io/kanada2026/
- Bei einem User-/Org-Repository muss der Repositoryname exakt DEINNAME.github.io heißen.

Falls es weiter 404 zeigt:
Bitte schicke mir:
1. den GitHub-Pages-Link
2. einen Screenshot von Settings > Pages
3. einen Screenshot der obersten Dateiebene im Repository
