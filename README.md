# Nova – Open-Source-Plugins für Shopware 6

[![Spendier mir einen Kaffee](https://img.shields.io/badge/☕_Spendier_mir_einen_Kaffee-PayPal-0070ba?style=for-the-badge&logo=paypal&logoColor=white)](https://paypal.me/DrdotHouse)

*[English version](README.en.md)*

**Nova** ist eine Reihe freier Plugins für Shopware 6.6 und 6.7 – entstanden im täglichen Betrieb mehrerer eigener Shops in einer Shopware-Installation. Alle Plugins sind quelloffen, kostenlos und werden über den **Nova Updater** direkt aus GitHub installiert und aktualisiert.

---

## Warum es Nova gibt

Ich betreibe selbst mehrere Onlineshops – vor allem für Ersatzteile – und habe über die Jahre viele kommerzielle Plugins eingesetzt. Immer wieder dieselben Erfahrungen: Abos für Kleinigkeiten, Funktionen, die fast passen, aber eben nur fast, Daten, die über fremde Server laufen, und Plugins, die nach einem Shopware-Update monatelang nicht mehr funktionieren – ohne dass man selbst eingreifen kann.

Irgendwann habe ich angefangen, die Dinge, die ich wirklich brauche, selbst umzusetzen: schlank, datenschutzfreundlich, ohne Abo und offen, sodass jeder sie prüfen und anpassen kann. Programmieren ist nicht mein Beruf – entstanden sind die Plugins mit Unterstützung von KI (Claude von Anthropic): Ich bringe die Anforderungen aus dem täglichen Shopbetrieb mit, teste alles in meinen eigenen Shops und entscheide, was hineinkommt.

**Ich bin ein großer Freund von Open Source.** Mein Shop, mein Server, fast jedes Werkzeug, mit dem ich arbeite, beruht auf freier Software, die andere Menschen geteilt haben. Mit Nova möchte ich meinen Teil zurückgeben: Was mir hilft, soll auch anderen Shopbetreibern helfen – kostenlos, offen, zum Mitlesen, Mitverbessern und Weiterentwickeln.

> Ich bin kein Profi-Entwickler, die Plugins sind ein Hobby neben dem eigentlichen Geschäft. Sie laufen in meinen eigenen Shops im Echtbetrieb, aber ohne Garantie und ohne Support-Anspruch. Fehlermeldungen und Verbesserungsvorschläge sind trotzdem jederzeit willkommen – am liebsten als Issue im jeweiligen Repository.

---

## Die Plugins

| Plugin | Wofür | Repository |
|---|---|---|
| **Nova Updater** | Installiert und aktualisiert Shopware-Plugins direkt aus GitHub-Releases – ohne Plugin-Store, mit Prüfungen, Sicherung und automatischem Zurückrollen. Die Basis für alle anderen Nova-Plugins. | [SW6-Nova-Updater](https://github.com/DrdotHouse2106/SW6-Nova-Updater) |
| **Nova Theme** | Schnelles, modulares Storefront-Theme mit fertigen Gestaltungsklassen für Erlebniswelten, konfigurierbarem Header, Footer und Newsletter je Verkaufskanal. | [SW6-Nova-Theme](https://github.com/DrdotHouse2106/SW6-Nova-Theme) |
| **Nova Suche** | Großes Suchfenster mit Bildern, Filtern und Sortierung, das aus Suchen, Klicks und Käufen lernt, Tippfehler und Wortteile versteht, Synonyme und Weiterleitungen verwaltet und auf Wunsch Begriffe ohne Treffer mit KI verbessert – ohne externen Suchdienst. | [SW6-Nova-Suche](https://github.com/DrdotHouse2106/SW6-Nova-Suche) |
| **Nova Rechtstexte** | Impressum, Datenschutz, AGB und Widerruf einmal pflegen und in allen Shops nutzen – mit Platzhaltern je Verkaufskanal, Bausteinen, die sich nach den genutzten Diensten richten, und zeitgesteuerten Abschnitten. | [SW6-Nova-Rechtstexte](https://github.com/DrdotHouse2106/SW6-Nova-Rechtstexte) |
| **Nova 2FA** | Zwei-Faktor-Anmeldung per Authenticator-App für die Administration und optional für Kundenkonten. | [SW6-Nova-2FA](https://github.com/DrdotHouse2106/SW6-Nova-2FA) |
| **Nova Upload** | Geschützte Datei-Uploads im Kontaktformular und an Artikeln (z. B. Logos, Zeichnungen, 3D-Dateien) plus Download-Bereich im Kundenkonto. | [SW6-Nova-Upload](https://github.com/DrdotHouse2106/SW6-Nova-Upload) |
| **Nova Dezimal** | Verkauf nach Meter, Quadratmeter & Co. mit Dezimalwert, Platten mit festem Maß zum m²-Preis. | [SW6-Nova-Dezimal](https://github.com/DrdotHouse2106/SW6-Nova-Dezimal) |
| **Nova Kategorie-Automatik** | Ordnet Artikel über einen Code fest den passenden Kategorien zu – ohne langsame dynamische Produktgruppen. | [SW6-Nova-Kategorie-Automatik](https://github.com/DrdotHouse2106/SW6-Nova-Kategorie-Automatik) |
| **Nova Termine** | Veranstaltungen und Messen im Admin pflegen, als Terminliste anzeigen, Treffen melden lassen – und Abholung auf Treffen als Versandart. | [SW6-Nova-Termine](https://github.com/DrdotHouse2106/SW6-Nova-Termine) |
| **Nova Captcha** | Unsichtbarer Spam-Schutz ohne Google: Rechenaufgabe im Browser statt Bilderrätsel, keine Cookies, keine externen Anfragen. | [SW6-Nova-Captcha](https://github.com/DrdotHouse2106/SW6-Nova-Captcha) |
| **Nova Tag Manager** | Google Tag Manager datenschutzkonform erst nach Zustimmung laden, mit E-Commerce-Ereignissen und erweiterten Conversions. | [SW6-Nova-Tag-Manager](https://github.com/DrdotHouse2106/SW6-Nova-Tag-Manager) |
| **Nova Lieferzeiten** | Feste monatliche Versandtermine mit Bestellschluss je Lieferant – angezeigt von der Produktseite bis zur E-Mail. | [SW6-Nova-Lieferzeiten](https://github.com/DrdotHouse2106/SW6-Nova-Lieferzeiten) |
| **Nova Versandkosten** | Versandkosten aus den eigenen Einkaufstarifen berechnen: Pakete bilden, Warenpost/Kleinpaket/DPD/DHL, Sperrgut, Peak und Ausland – mit Spedition über Cargoboard, Zustelldatum in der Kasse und Margenkontrolle an der Bestellung. | [SW6-Nova-Versandkosten](https://github.com/DrdotHouse2106/SW6-Nova-Versandkosten) |
| **Nova GoCardless** | SEPA-Lastschrift über GoCardless: Mandat auf der sicheren GoCardless-Seite, Zahlungsstatus automatisch per Webhook – ohne IBAN im Shop. | [SW6-Nova-GoCardless](https://github.com/DrdotHouse2106/SW6-Nova-GoCardless) |
| **Nova Nachfrage** | Einige Tage nach dem Versand eine freundliche Nachfrage: Bitte um Produkt- und Google-Bewertung plus ähnliche Produkte – als Bestandskundenwerbung mit dauerhaft gespeicherter Abmeldung. | [SW6-Nova-Nachfrage](https://github.com/DrdotHouse2106/SW6-Nova-Nachfrage) |
| **Nova Fahrzeugauswahl** | Horizontale Fahrzeug-Schnellauswahl im Header für Shops mit fahrzeugbezogenem Sortiment. | [SW6-Nova-Fahrzeugauswahl](https://github.com/DrdotHouse2106/SW6-Nova-Fahrzeugauswahl) |

Alle Plugins stehen unter der **MIT-Lizenz**. Jede README gibt es auf Deutsch und Englisch.

### Rund um ERPNext

Wer Shopware mit [ERPNext](https://erpnext.com) verbinden möchte: Mein Fork von [ecommerce_integrations](https://github.com/DrdotHouse2106/ecommerce_integrations) ergänzt die Frappe-App um eine vollständige Shopware-6-Anbindung (Artikel, Bestellungen, Bestand, Preise).

---

## Installation

1. **Nova Updater** einmalig als ZIP aus dem [neuesten Release](https://github.com/DrdotHouse2106/SW6-Nova-Updater/releases/latest) unter *Erweiterungen → Meine Erweiterungen → Erweiterung hochladen* installieren.
2. Danach erscheinen alle Nova-Plugins im **Plugin-Katalog** des Updaters und lassen sich mit einem Klick installieren und aktualisieren.
3. Alternativ: jedes Plugin als ZIP aus den Releases des jeweiligen Repositorys hochladen.

## Grundsätze

- **Kein Abo, keine Lizenzschlüssel, keine Telemetrie.**
- **Datenschutz zuerst:** externe Dienste nur, wenn es nicht anders geht – und dann abschaltbar und in der Datenschutzerklärung beschrieben.
- **Schlank und schnell:** keine Abhängigkeit von großen Frameworks, keine Fremd-Skripte im Shop.
- **Deutsch zuerst:** Oberflächen und Dokumentation auf Deutsch, Englisch zusätzlich.
- **Offen für alle:** Forks, Pull Requests und Ideen sind ausdrücklich erwünscht.

---

## Unterstützen

Wenn dir eines der Plugins Arbeit oder Geld für ein Abo erspart, freue ich mich über einen Kaffee – freiwillig, ohne Support-Anspruch, einfach eine nette Geste:

[![Spendier mir einen Kaffee](https://img.shields.io/badge/☕_Spendier_mir_einen_Kaffee-PayPal-0070ba?style=for-the-badge&logo=paypal&logoColor=white)](https://paypal.me/DrdotHouse)

**Für Unternehmen:** Ihr setzt Nova im Betrieb ein und möchtet die Weiterentwicklung unterstützen? Gern auch **mit Rechnung** – einmalig oder monatlich. Auf Wunsch nenne ich euch hier als Unterstützer mit Firmenname und Link. Meldet euch einfach über ein Issue.

Genauso wertvoll: **ein Stern ⭐ auf GitHub**, eine Fehlermeldung oder ein kleiner Pull Request.

Danke! 💙
