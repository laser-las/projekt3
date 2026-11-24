# Virtual Market – Planering

## 1. Problem
Det kan vara svårt att lära sig aktie- och kryptohandel utan att riskera riktiga pengar. Det tar också tid att följa marknaden och hålla koll på sin utveckling.

## 2. Målgrupp
Personer som vill lära sig om investeringar, testa strategier och tävla med andra.

## 3. Nytta
Användaren kan öva på att köpa och sälja med virtuella pengar och följa hur portföljen utvecklas utan ekonomisk risk.

## 4. Grundfunktioner
* Skapa konto och logga in.
* Se aktier, fonder och kryptovalutor med aktuella priser.
* Köpa och sälja med virtuella pengar.
* Se saldo, innehav och vinst eller förlust.
* Delta i tävlingar och jämföra resultat.

## 5. Data – vad ska sparas?

### Tabeller och kolumner
| Tabell | Exempel på kolumner |
| :--- | :--- |
| **Users** | `Id`, `Username`, `Email`, `PasswordHash` |
| **Assets** | `Id`, `Name`, `Type`, `Price` |
| **Portfolios** | `Id`, `UserId`, `Balance`, `Currency` |
| **Holdings** | `Id`, `PortfolioId`, `AssetId`, `Quantity` |
| **Transactions** | `Id`, `PortfolioId`, `AssetId`, `Type`, `Quantity`, `Price` |
| **Competitions** | `Id`, `Name`, `StartDate`, `EndDate` |
| **CompetitionUsers** | `Id`, `CompetitionId`, `UserId` |

### Relationer
* **Users** har en **Portfolio**.
* **Portfolios** har flera **Holdings** och **Transactions**.
* **Holdings** och **Transactions** hänvisar till **Assets**.
* **CompetitionUsers** kopplar ihop **Users** och **Competitions**.

## 6. Backend – vad ska kontrolleras?
* Att användaren har tillräckligt saldo för ett köp.
* Att användaren äger tillräckligt många tillgångar för en försäljning.
* Att köp och försäljning räknas ut korrekt.
* Att användaren bara kan ändra sin egen ekonomi.
* Att tävlingsresultat beräknas utifrån procentuell utveckling.

## 7. Testbara krav och arbetslista

### Måste fungera
- [ ] Användaren kan skapa konto och logga in.
- [ ] Användaren får ett valt startbelopp.
- [ ] Köp och försäljning uppdaterar saldo och innehav.
- [ ] Transaktioner sparas i databasen.
- [ ] Felaktiga köp stoppas med felmeddelande.

### Nästa steg
- [ ] Visa portföljens värde och utveckling.
- [ ] Skapa och delta i tävlingar.
- [ ] Visa topplista.

### Extra
- [ ] Prisvarningar.
- [ ] Favoritlista.
- [ ] Mer avancerad statistik och diagram.


## Resurser och API:er

* Twelve Data

* Aktier, ETF:er, kryptovalutor och marknadsdata.

* https://twelvedata.com/

* Dokumentation: https://twelvedata.com/docs

* CoinMarketCap

* Kryptovalutor, priser och marknadsvärden.

* https://coinmarketcap.com/

* Dokumentation: https://coinmarketcap.com/api/

* Alpha Vantage

* Aktier, fonder, valutor och kryptovalutor.

* https://www.alphavantage.co/

* Dokumentation: https://www.alphavantage.co/documentation/