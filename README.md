# Movie Library Application

## Projektbeskrivning

Detta projekt är en enkel filmhanteringsapplikation som använder TMDb (The Movie Database) API för att hämta information om filmgenrer och filmer baserat på användarens preferenser. Applikationen låter användaren välja en eller flera filmgenrer, och sedan hämtar en slumpmässig film från dessa genrer. Applikationen hanterar TMDb API-nyckeln säkert genom att spara den i en konfigurationsfil (`appsetting.json`), som exkluderas från versionhantering via `.gitignore`.

### Funktioner

- Hämta tillgängliga filmgenrer från TMDb.
- Låta användaren välja genrer genom att ange genrenamn eller ID.
- Hämta och visa en slumpmässig film baserat på användarens val av genrer.
- Hantering av API-nyckeln via en dold konfigurationsfil (`appsetting.json`).

## Installation

### Förutsättningar

- .NET SDK (https://dotnet.microsoft.com/download)
- En giltig TMDb API-nyckel (https://www.themoviedb.org/settings/api)

### Steg för installation

1. **Klona repositoryt:**
   
   ```bash
   git clone https://github.com/<ditt-username>/movie-library-app.git
   cd movie-library-app
