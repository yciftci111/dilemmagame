# Dilemma Game – Health Care Management

Online dashboard voor de Dilemma Game (50 dilemma's, Erasmus School of Health Policy & Management).

## Online zetten via GitHub Pages
1. Maak op GitHub een nieuwe repository aan (bijv. `dilemma-game`). Je kunt hem openbaar maken of, met GitHub Pro of als student, privé.
2. Upload `index.html` en deze `README.md` (via **Add file → Upload files**).
3. Ga naar **Settings → Pages** en kies bij *Source*: **Deploy from a branch**, branch `main`, map `/ (root)`. Klik op **Save**.
4. Na ongeveer een minuut staat het spel op `https://<jouw-gebruikersnaam>.github.io/dilemma-game/`. Deel die link met je medestudenten.

## Spelen
- **Spelers**: vul 3 tot 5 namen in. De eerste speler is de eerste dilemmahouder.
- **Spelen**: de app volgt de spelregels stap voor stap:
  1. Trekken: een willekeurig nummer uit 1–50, waarbij al gespeelde dilemma's worden overgeslagen.
  2. Kiezen: ieder kiest in het geheim.
  3. Onthullen: de dilemmahouder eerst.
  4. Discussie: met timer en notities.
  5. Beoordeling: steun voor de dilemmahouder (1–5), herziene keuze, door wie je bent overtuigd en met welk argument.
- **Resultaten**: overzicht per speler en per dilemma, plus export naar CSV (Excel) of JSON.

Het spel wordt bewaard in de browser van het apparaat waarop je speelt. Speel daarom samen op één scherm (dat doorgeven), of op een gedeeld scherm via Zoom of Teams. Een JSON-export kun je op een ander apparaat weer importeren.

## Nederlands / Engels
Met de knop **NL | EN** rechtsboven wissel je de taal van de dilemma's en van het verslag. De vertaling is gemaakt met AI-ondersteuning; het Engelse origineel blijft leidend.

## Verslag (reflectieopdracht A–D)
Onder **Verslag** kies je een speler. De app schrijft per onderdeel automatisch een eerste alinea op basis van het spel:
- **A**: het patroon in je keuzes. Elk antwoord is gelabeld met de waarde die het vooropstelt: patiënt, medewerkers, organisatie, reputatie, integriteit, samenwerking of maatschappij.
- **B**: welke keuzes je herzag, wie je overtuigde en met welk argument.

Medespelers vullen hun observatie over jou direct in (**C**). Jij vult je eigen reflectie aan en de casus St. Bernold's (**D**). Daarna klik je op **Verslag bekijken** en kies je **Afdrukken / PDF** of **Download als Word**.

## Opnemen, transcriberen en AI-schrijfhulp
- **Tijdens het spelen (stap 5, Discussie):** vink toestemming aan en klik op **🎙 Live transcriberen**. Dit werkt in Chrome en Edge; de audio gaat daarbij naar de spraakdienst van Google of Microsoft. Je kunt ook een opname (telefoon-memo, Teams-opname) uploaden via **📁 Audiobestand transcriberen**.
- **Audiobestand transcriberen** gebruikt Whisper en draait volledig in je eigen browser, er gaat niets naar een server. De eerste keer wordt het model gedownload (enkele honderden MB). Op een laptop zonder snelle grafische kaart duurt het transcriberen ongeveer even lang als de opname zelf, of langer.
- **Onder Verslag:** de transcripties per dilemma en van de hele sessie zijn te bewerken. De **AI-schrijfhulp** maakt er een gestructureerd concept (A–D) van:
  - **Route 1 (gratis):** kopieer de opdracht, plak hem in claude.ai, plak het antwoord terug en klik op **Overnemen in verslag**.
  - **Route 2:** met een eigen Anthropic API-sleutel genereer je het concept direct in de app.
- Vraag altijd toestemming aan je medespelers voordat je opneemt. Controleer het AI-concept en maak het je eigen.
