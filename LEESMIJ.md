# Hunter Systeem – installeren op je iPhone

Deze map is de complete app. Hij werkt offline en bewaart al je gegevens alleen op je telefoon. Er gaat niets naar een server of een account.

## 1. Zet de map online (eenmalig, ±5 minuten, op een computer)

Een iPhone installeert web-apps alleen vanaf een https-adres. De makkelijkste gratis manier:

1. Pak het zip-bestand uit, zodat je de map `hunter-app` hebt.
2. Ga op je computer naar **app.netlify.com/drop** en maak een gratis account.
3. Sleep de map `hunter-app` naar het vak op die pagina.
4. Je krijgt een adres zoals `https://iets-willekeurigs.netlify.app`. Je kunt de naam later aanpassen onder *Site configuration → Change site name*.

Alternatief: GitHub Pages werkt ook. Zet de bestanden in een repository en zet Pages aan.

De server levert alleen de app-bestanden aan. Je quests, XP en avatar staan nooit op die server.

## 2. Installeer de app op je iPhone

1. Open het adres in **Safari**. Andere browsers kunnen op de iPhone geen apps installeren.
2. Tik op **Deel** (vierkantje met pijl) en kies **Zet op beginscherm**.
3. Open Hunter Systeem vanaf je beginscherm. Hij opent schermvullend, zonder Safari-balken.
4. Open de app één keer terwijl je online bent. Daarna werkt hij ook zonder internet.

## 3. Neem je huidige voortgang mee

Het geïnstalleerde icoon heeft zijn eigen opslag, los van Safari en van de versie in Claude.

1. Open de oude versie en ga naar **Logboek → Kopieer back-up**.
2. Open de geïnstalleerde app en kies je hunter.
3. Ga naar **Logboek**, plak de code bij *Back-upcode* en tik op **Herstel**.

## Goed om te weten

- **Gegevens:** alles staat in de opslag van de app op je telefoon. Verwijder je het icoon van je beginscherm, dan is je voortgang weg. Maak dus af en toe een back-up en bewaar de code bijvoorbeeld in Notities.
- **Hetzelfde adres houden:** de opslag hoort bij het adres. Zet je de app later op een ander adres, gebruik dan de back-upcode om je voortgang over te zetten.
- **Updates:** vervang de bestanden op Netlify door een nieuwe versie en verhoog `VERSION` in `sw.js`. De app werkt zichzelf bij zodra hij online is.
- **Lettertypen:** die worden de eerste keer online geladen en daarna offline bewaard.

## Apple Watch (optioneel)
Tik op het Quests-scherm bij de kaart Apple Watch op **Aanzetten**. Daarna vul je bovenaan elke dag je ringen, stappen, kilometers en workouts in, overgenomen uit de Fitness-app of van je Watch. Sluit je alle drie de ringen, dan groeit je ringstreak.
