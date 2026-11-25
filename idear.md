# Virtual Market – Projektplan

**Projekt:** Virtual Market  
**Typ:** Virtuell aktie- och kryptomarknad  
**Syfte:** En simulerad marknad där användare kan handla med aktier, kryptovalutor och fonder med virtuella pengar.

---

# 1. Projektidé

Virtual Market ska vara en virtuell handelsplattform där användare kan skapa egna konton och testa hur det fungerar att investera i aktier, kryptovalutor och fonder.

Plattformen ska använda riktiga marknadspriser från externa API:er, men all handel ska ske med virtuella pengar. Användare ska kunna köpa, sälja, följa sina investeringar och tävla mot andra användare.

Målet är att skapa en realistisk marknad där man kan lära sig om investeringar utan att använda riktiga pengar.

# 2. Problem – Vad är svårt eller tidskrävande idag?

- Att lära sig hur aktiemarknaden fungerar utan att riskera riktiga pengar.
- Att förstå hur aktier, fonder och kryptovalutor förändras i värde.
- Att testa olika investeringsstrategier i en realistisk miljö.
- Att hålla koll på flera olika marknader på samma ställe.
- Att jämföra sina investeringsresultat med andra.

# 3. Målgrupp – Vem ska använda appen?

- Personer som är intresserade av aktier och investeringar.
- Nybörjare som vill lära sig hur marknaden fungerar.
- Personer som vill testa olika investeringsstrategier.
- Vänner som vill tävla mot varandra på en virtuell marknad.

# 4. Nytta – Hur hjälper lösningen användaren?

- Möjlighet att handla utan riktiga pengar.
- Lära sig hur marknaden fungerar genom praktisk erfarenhet.
- Få tillgång till aktuella marknadspriser.
- Följa sin egen utveckling och se hur investeringarna går.
- Jämföra resultat med andra användare.
- Testa olika strategier utan ekonomisk risk.

# 5. Grundfunktioner

## 5.1 Marknadsöversikt
- Visa aktier, kryptovalutor och fonder.
- Visa aktuella priser.
- Visa prisförändringar i procent och kronor.
- Visa vilka tillgångar som ökar och minskar mest.
- Söka efter olika investeringar.

## 5.2 Köp och sälj
- Köpa aktier med virtuella pengar.
- Sälja aktier som användaren äger.
- Köpa och sälja kryptovalutor.
- Köpa och sälja fonder.
- Visa kostnaden innan ett köp genomförs.
- Uppdatera saldot efter varje transaktion.

## 5.3 Personlig portfölj
- Visa användarens innehav.
- Visa totalt portföljvärde.
- Visa tillgängligt saldo.
- Visa total vinst eller förlust.
- Visa utveckling över tid.
- Visa fördelningen mellan olika investeringar.

## 5.4 Diagram och statistik
- Visa historiska priser.
- Visa prisutveckling i diagram.
- Visa procentuell uppgång och nedgång.
- Visa portföljens utveckling.
- Visa användarens historiska resultat.

# 6. Användarkonton och personlig ekonomi

Varje användare ska kunna skapa ett eget konto och få en personlig virtuell ekonomi.

## 6.1 Kontofunktioner
- Registrera konto.
- Logga in och logga ut.
- Personlig användarprofil.
- Visa kontosaldo.
- Visa investeringar.
- Visa köp- och säljhistorik.
- Visa total avkastning.

## 6.2 Välj startkapital

När användaren börjar ska den kunna välja hur mycket virtuella pengar den vill starta med.

Alternativ:

- 10 000 kr
- 50 000 kr
- 100 000 kr
- 1 000 000 kr

Startkapitalet ska användas för att köpa och sälja investeringar på marknaden.

## 6.3 Starta om ekonomin

Det ska finnas en funktion för att starta om sin virtuella ekonomi.

När användaren väljer att starta om:

1. En bekräftelseruta visas.
2. Användaren får välja nytt startkapital.
3. Det nuvarande saldot återställs.
4. Alla aktuella innehav återställs.
5. En ny investeringsperiod börjar.
6. Tidigare resultat och transaktioner sparas i historiken.

Användaren ska alltså kunna börja om utan att förlora sin tidigare historik.

# 7. Leaderboard – Tävling mellan användare

Användare ska kunna tävla mot varandra och jämföra hur bra deras investeringar går.

## 7.1 Funktioner
- Gemensam leaderboard.
- Skapa egna tävlingar.
- Gå med i befintliga tävlingar.
- Se andra deltagares resultat.
- Se sin egen placering.
- Se användarnas procentuella avkastning.
- Se tävlingens deltagare.
- Kunna lämna en tävling.

## 7.2 Tävlingsalternativ

Tävlingar ska kunna vara:

- Öppna för alla användare.
- Privata med inbjudningskod.
- Tidsbegränsade, exempelvis 30 dagar.
- Obegränsade.

## 7.3 Rättvisa tävlingar

- Alla deltagare ska börja med samma startkapital inom en tävling.
- Resultaten ska baseras på procentuell avkastning.
- Användarnas resultat ska uppdateras automatiskt.
- Placeringarna ska ändras när resultaten förändras.

# 8. Adminpanel

Det ska finnas en separat adminpanel där administratörer kan hantera och övervaka plattformen.

## 8.1 Användarhantering
- Se alla registrerade användare.
- Söka efter användare.
- Öppna användarprofiler.
- Se användarnas virtuella saldo.
- Se användarnas portföljer.
- Se köp- och säljhistorik.
- Stänga av och återaktivera konton.

## 8.2 Statistik och administration
- Se antal registrerade användare.
- Se hur många som är aktiva.
- Se statistik över genomförda transaktioner.
- Hantera tävlingar.
- Övervaka plattformens funktioner.

## 8.3 Behörigheter
- Vanliga användare ska inte kunna komma åt adminpanelen.
- Endast administratörer ska ha administratörsbehörighet.
- Backend ska kontrollera alla behörigheter.

# 9. Realtidsuppdateringar

En viktig del av Virtual Market är att informationen ska uppdateras automatiskt i realtid eller så nära realtid som datakällorna tillåter.

## 9.1 Marknadsuppdateringar
- Aktiekurser.
- Kryptovalutakurser.
- Fondkurser när ny data finns tillgänglig.
- Prisförändringar.
- Marknadens största uppgångar och nedgångar.

## 9.2 Användaruppdateringar
- Aktuellt saldo.
- Portföljens värde.
- Vinst och förlust.
- Köp och försäljningar.
- Leaderboard och placeringar.
- Andra användares tävlingsresultat.

## 9.3 Teknik
- SignalR för realtidskommunikation.
- ASP.NET Core för backend.
- Externa API:er för marknadspriser.
- Automatisk uppdatering av information utan att sidan behöver laddas om.

# 10. Teknik och program

Projektet ska byggas med följande tekniker och program.

| Del | Teknik / program | Användningsområde |
|---|---|---|
| Frontend | Next.js, React, TypeScript | Sidor, komponenter, formulär och dashboard |
| API | ASP.NET Core | HTTP-anrop och JSON-svar |
| Backend | C# och .NET | Regler, validering, beräkningar och felhantering |
| Databas | SQLite och EF Core | Tabeller, relationer och beständig lagring |
| Design | Figma | Skisser och klickbar prototyp |
| Modellering | UML | Klassdiagram och sekvensdiagram |
| Versionshantering | Git och GitHub | Små commits och dokumenterad utveckling |

**Programmeringsprincip:** All viktig affärslogik, handel, beräkningar och validering ska hanteras i C#-backend. Frontend ska främst ansvara för användargränssnittet och kommunikation med API:et.

# 11. Hur systemet ska fungera tillsammans

## Frontend
Next.js, React och TypeScript ska användas för att bygga det användaren ser.

Exempel:
- Startsida.
- Marknadsöversikt.
- Användarkonton.
- Portfölj.
- Diagram.
- Leaderboard.
- Adminpanel.

## API
ASP.NET Core ska ta emot förfrågningar från frontend och skicka tillbaka information i JSON-format.

## Backend
C# och .NET ska hantera:
- Köp och försäljningar.
- Saldo.
- Portföljberäkningar.
- Användarkonton.
- Behörigheter.
- Tävlingar.
- Validering och felhantering.

## Databas
SQLite och Entity Framework Core ska användas för att spara:
- Användare.
- Kontoinformation.
- Virtuellt saldo.
- Investeringar.
- Transaktioner.
- Tävlingar.
- Tävlingsresultat.
- Historik.

# 12. Regler och beräkningar i backend

Backend ska kontrollera och beräkna all viktig information.

- Kontrollera att användaren har tillräckligt med virtuella pengar.
- Kontrollera att användaren äger tillgången innan försäljning.
- Beräkna kostnaden vid köp.
- Beräkna intäkten vid försäljning.
- Uppdatera användarens saldo.
- Uppdatera portföljens totala värde.
- Beräkna vinst och förlust.
- Beräkna procentuell avkastning.
- Uppdatera användarnas tävlingsplaceringar.
- Förhindra att samma transaktion registreras flera gånger.
- Kontrollera användarens behörighet vid varje skyddad åtgärd.

# 13. Säkerhet

- Säker registrering och inloggning.
- Lösenord ska lagras på ett säkert sätt.
- Kontroll av användarbehörigheter.
- Skydd av administratörsfunktioner.
- Backend ska kontrollera köp och försäljningar.
- API-nycklar ska inte exponeras i frontend.
- Användardata ska skyddas.

# 14. Utvecklingsplan

Projektet ska utvecklas stegvis så att varje del kan testas innan nästa byggs.

1. Planera projektet och skapa design i Figma.
2. Skapa projektstrukturen.
3. Bygga backend med C# och ASP.NET Core.
4. Skapa databasen med SQLite och EF Core.
5. Bygga registrering och inloggning.
6. Skapa systemet för virtuella pengar och startkapital.
7. Koppla in externa API:er för marknadspriser.
8. Bygga marknadsöversikten.
9. Skapa köp- och säljsystemet.
10. Bygga portföljen och diagrammen.
11. Skapa leaderboard och tävlingssystem.
12. Bygga adminpanelen.
13. Implementera realtidsuppdateringar med SignalR.
14. Testa, felsöka och förbättra systemet.
15. Dokumentera projektet och versionshantera med GitHub.

# 15. Framtida utvecklingsmöjligheter

Möjliga funktioner att lägga till senare:

- Fler valutor.
- Fler typer av investeringar.
- Avancerad statistik.
- Fler diagraminställningar.
- Notiser vid stora prisförändringar.
- Egna investeringsmål.
- Fler tävlingsformat.
- Utökad adminpanel.
- Fler historiska jämförelser.

# 16. Resurser och API:er

Följande externa tjänster kan användas för att hämta marknadsdata.

## Twelve Data
Aktier, ETF:er, kryptovalutor och annan finansiell marknadsdata.

https://twelvedata.com/

API-dokumentation:
https://twelvedata.com/docs

## CoinMarketCap
Kryptovalutor, priser, marknadsvärden och historisk data.

https://coinmarketcap.com/

API-dokumentation:
https://coinmarketcap.com/api/

## Alpha Vantage
Aktier, fonder, valutor och kryptovalutor.

https://www.alphavantage.co/

API-dokumentation:
https://www.alphavantage.co/documentation/

**Observera:** API-tjänsterna har olika begränsningar för gratisanvändning, antal förfrågningar och realtidsdata. Vilka tjänster som ska användas bestäms under utvecklingen.