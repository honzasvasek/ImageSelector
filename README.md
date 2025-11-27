# ImageSelector

Een lichte, statische webviewer voor portretfoto's die perfect op mobiele schermen past. Swipe omhoog/omlaag of links/rechts voor een nieuwe random afbeelding, en ga met de omgekeerde richting terug door je geschiedenis.

## Gebruik
1. Open `index.html` lokaal in je browser (of serveer de map via een eenvoudige webserver).
2. Voeg je eigen portretfoto's toe aan de map `images/` en vul het `images`-array in `index.html` aan met de bestandsnamen.
3. Swipe of gebruik de knoppen om willekeurige beelden te verkennen terwijl eerdere keuzes bewaard blijven voor terugscrollen.

## Testen
1. Start in de projectmap een eenvoudige server: `python -m http.server 8000`.
2. Open `http://localhost:8000` in een mobiele browser of in de mobiele weergave van de devtools.
3. Test het swipen/scrollen en de knoppen links/rechts/omlaag/omhoog; bij terug swipen krijg je de eerder getoonde afbeelding.

## Code naar GitHub pushen
1. Controleer de huidige status: `git status`.
2. Stel de remote in als dat nog niet gebeurd is: `git remote add origin <jouw-github-url>` (sla over als het al bestaat).
3. Voeg wijzigingen toe en commit ze:
   ```bash
   git add .
   git commit -m "Jouw beschrijvende commit message"
   ```
4. Push naar de `main`-branch (of een andere branchnaam die je gebruikt): `git push origin main`.
5. Als authenticatie nodig is, gebruik een GitHub-token in plaats van je wachtwoord wanneer daarom gevraagd wordt.
