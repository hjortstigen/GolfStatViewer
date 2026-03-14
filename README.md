# Hooks Golf Stats – Dashboard

En webbaserad statistikdashboard för golfrundor spelade på Hooks GK.

## Funktioner

- **Översikt** – scoreutveckling, fairway- och GIR-statistik, puttning, greenträff- och misszoner
- **Runda** – välj en specifik runda och se scorekort, hål-för-hål statistik och zonkartor
- **Bana** – scoreutveckling per bana, snitt per hål, enklaste/svåraste hålen, rekord och eclectic
- **Rekord** – 16 rekordrutor, hålstatistik, bästa snitt per par-typ och rundstreaks
- **Inställningar** – anslut till GitHub Gist för synkronisering med mobilappen

## Datakälla

Dashboarden hämtar data från ett **GitHub Gist** som mobilappen ([Hooks Golf Stats](https://github.com)) synkar till automatiskt efter varje runda.

Du kan också importera data manuellt via en JSON-fil exporterad från mobilappen (Inställningar → Exportera data).

## Kom igång

1. Öppna dashboarden på `https://<dittnamn>.github.io/GolfStatViewer`
2. Klicka på ⚙️ i övre högra hörnet
3. Klistra in ditt **Gist ID** och klicka **Anslut och ladda data**

## Färgkodning

| Färg | Betydelse |
|------|-----------|
| 🔴 Röd | Under par |
| 🟢 Grön | Exakt par |
| ⚫ Svart | Över par |
| 🟡 Guld | Eagle eller HIO |

## Teknik

Byggd med ren HTML, CSS och JavaScript – inga externa ramverk eller beroenden. All data lagras i ett GitHub Gist och laddas direkt i webbläsaren.
