# Testplan – SauceDemo

## 1. Zielsetzung
Überprüfung der Kernfunktionen der Website [SauceDemo](https://www.saucedemo.com/): Login, Warenkorb und Checkout.

## 2. Umfang (Scope)
- Im Scope: Login, Produkte, Warenkorb, Checkout, Logout.
- Außerhalb des Scopes: Performance, erweiterte Sicherheit, Mobile-Tests.

## 3. Anforderungen (Requirements)
- **ANF-001**: Login mit gültigen Daten funktioniert.
- **ANF-002**: Login mit ungültigen Daten schlägt fehl mit Fehlermeldung.
- **ANF-003**: Produkte können in den Warenkorb gelegt und entfernt werden.
- **ANF-004**: Checkout kann erfolgreich abgeschlossen werden.
- **ANF-005**: Logout bringt den Benutzer zurück zur Login-Seite.

## 4. Testumgebung
- Browser: Chrome, Firefox
- Betriebssystem: Windows / macOS
- Testdaten: standard_user / secret_sauce

## 5. Ergebnisse (Deliverables)
- Testfälle (CSV)
- Bug Reports (Markdown + Screenshots)
- Traceability Matrix (CSV)
