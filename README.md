# benjaminarndtba1-cell.github.io

Statische Hilfsseiten für private Apps. Keine Daten, kein Tracking, keine externen Ressourcen.

- `tca/` – reicht „Reise übernehmen“-Links an die Android-App TravelCostAssist weiter.
  Die Reisedaten stehen im `#`-Teil des Links und werden nie an den Server übertragen.
- `.well-known/assetlinks.json` – bestätigt Android, dass Links unter `/tca` zur App gehören
  (App Links; enthält nur den öffentlichen SHA-256-Fingerabdruck des Signierzertifikats).
- `.nojekyll` – sonst veröffentlicht GitHub Pages den Ordner `.well-known` nicht.
