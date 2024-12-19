# MigratieTool

## Overzicht
De **MigratieTool** is een krachtig hulpmiddel ontworpen om de migratie van bestanden naar SharePoint te vereenvoudigen. Deze tool ondersteunt een efficiënt proces van bestandsoverdracht, met ondersteuning voor grote bestanden via chunk-based uploads. Het is een oplossing die gebruik maakt van moderne webtechnologieën en een gebruiksvriendelijke interface biedt.

## Functionaliteiten

- **Bestandsoverdracht:** Upload meerdere bestanden tegelijkertijd naar SharePoint.
- **Chunk-gebaseerde uploads:** Grote bestanden worden opgesplitst in kleinere delen (chunks) voor betrouwbaardere uploads.
- **Voortgangsindicator:** Realtime weergave van de uploadvoortgang met een visuele balk en tekstuele updates.
- **SharePoint-validatie:** Controleert automatisch de ingevoerde SharePoint-URL op juistheid.
- **Feedback voor gebruikers:** Geeft duidelijke meldingen bij fouten of succesvolle overdracht.

## Technische Details

- **Frontend:** 
  - HTML, CSS, JavaScript
  - Voortgangsbalk die groen kleurt bij voltooiing
  - Dynamische validatie en meldingen

- **Backend:**
  - ASP.NET Core MVC (C#)
  - Ondersteunt API's voor chunk-gebaseerde uploads

- **Integraties:**
  - Microsoft SharePoint REST API voor bestandsoverdracht

## Installatie

Volg deze stappen om de tool te installeren en lokaal uit te voeren:

1. **Clone de repository:**
   ```bash
   git clone https://github.com/AhmadAlhajAsaad/MigratieToolGraphAPI.git
   ```


2. **Herstel afhankelijkheden:**
   Installeer de vereisten voor het project met .NET CLI:
   ```bash
   dotnet restore
   ```

3. **Start de applicatie:**
   ```bash
   dotnet run
   ```

4. **Open de applicatie:**
   Ga naar (http://localhost:44334) in je browser.

## Gebruik

1. Upload bestanden via de interface door bestanden te selecteren en een geldige SharePoint-URL in te voeren.
2. Bekijk de voortgangsbalk om de status van de upload te volgen.
3. Controleer meldingen voor succes of fouten na voltooiing.

## Contributie

We verwelkomen bijdragen van de gemeenschap! Om bij te dragen:

1. Fork de repository.
2. Maak een nieuwe feature branch:
   ```bash
   git checkout -b nieuwe-feature
   ```
3. Commit je wijzigingen:
   ```bash
   git commit -m "Voeg nieuwe feature toe"
   ```
4. Push naar je branch:
   ```bash
   git push origin nieuwe-feature
   ```
5. Open een pull request.


---
Dank voor het gebruik van de MigratieTool!
