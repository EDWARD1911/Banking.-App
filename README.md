 
# Banking App MVP

Monorepo containing:
- backend: ASP.NET 8 Minimal API + PostgreSQL
- mobile: .NET MAUI (iOS/Android)

## Prereqs
- .NET 8 SDK
- Docker Desktop

## Run database
docker compose up -d

## Run backend
cd backend/BankingApi
dotnet tool install --global dotnet-ef
dotnet ef migrations add InitialCreate
dotnet ef database update
dotnet run

Swagger: https://localhost:5001/swagger

## Run mobile
Open mobile/BankingMaui in Visual Studio and run Android/iOS.
 # Banking.-App
