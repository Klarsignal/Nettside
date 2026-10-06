# Klarsignal – nettside

Den offentlige nettsiden for Klarsignal. Netlify henter siden herfra og publiserer den automatisk når endringer kommer inn på `main`.

| Fil | Hva |
|---|---|
| `index.html` | Forsiden med venteliste |
| `personvern.html` | Personvernerklæring for påmeldingsskjemaet |
| `takk.html` | Siden folk ser etter påmelding |
| `styles.css` | All stil |
| `fonts/` | Skriftene, lokalt lagret (SIL Open Font License), så ingen data sendes til tredjepart |
| `_headers` | Sikkerhetsinnstillinger for Netlify |
| `netlify.toml` | Publiseringsoppsett: ingen byggesteg, hele mappen publiseres |

Påmeldingsskjemaet bruker Netlify Forms. Slå på **Form detection** under **Forms** i Netlify.

Dette kodeområdet er offentlig. Agentplattformen og alt som har med kunder å gjøre, ligger i det private kodeområdet `Klarsignal/klarsignal`.
