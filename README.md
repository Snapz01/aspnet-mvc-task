# ASP.NET Core MVC – Assignment & Showcase

En webbapplikation byggd i **ASP.NET Core MVC** som demonstrerar grundläggande MVC-arkitektur, tillståndshantering via sessioner/cookies och formulärhantering med C# och Razor Views[cite: 8].

## Funktioner & Moduler

- **Doctor-modul:** En feber- och hälsokontroll som tar emot kroppstemperatur via formulär och returnerar ett diagnostiskt resultat[cite: 8].
- **Gissningslek (Guessing Game):** Ett interaktivt spel där användaren gissar ett slumpmässigt genererat tal, med tillståndshantering över förfrågningar via session/cookies[cite: 8].
- **Portfoliosidor:** Statiska och dynamiska vyer som presenterar projekt, kontaktvägar och profilinformation (`About`, `Contact`, `Projects`)[cite: 8].
- **Responsiv Layout:** Byggd med ASP.NET Core MVC:s standardmall med Bootstrap och partials för formulärvalidering[cite: 8].

## Projektstruktur

- `Controllers/`:
  - `Doctor.cs`: Logik och åtgärder för feberkontrollen[cite: 8].
  - `GuessingGame.cs`: Spelmekanik och sessionshantering för gissningsspelet[cite: 8].
  - `HomeController.cs`: Navigering och generella informationssidor[cite: 8].
- `Views/`: Razor-vyer (`.cshtml`) och gemensamma layouts (`_Layout.cshtml`)[cite: 8].
- `wwwroot/`: Statiska tillgångar inklusive Bootstrap, jQuery, CSS och presentationsmaterial[cite: 8].

## Teknikstack

- **Backend:** C#, .NET / ASP.NET Core MVC[cite: 8]
- **Frontend:** Razor Views, HTML5, CSS3, Bootstrap, jQuery[cite: 8]
- **State Management:** ASP.NET Core Session / Cookies[cite: 8]
