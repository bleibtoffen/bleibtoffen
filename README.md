# caresteouvert-de

This repository is used to organise the expansion of the COVID19 opening hours map https://www.caresteouvert.fr/ ([osmontrouge/caresteouvert](https://github.com/osmontrouge/caresteouvert)) to Austria, Germany and Switzerland.

The three main tasks are:

1. [Record types of open places](#orte).
1. [Record rules for chains](#handelsketten).
1. [Translate blog articles](#blog).

See details below (in German only).

---

In diesem Repository organisieren wir die Erweiterung der COVID19-Öffnungszeiten-Karte https://www.caresteouvert.fr/ ([osmontrouge/caresteouvert](https://github.com/osmontrouge/caresteouvert)) auf den deutschsprachigen Raum (Deutschland, Österreich, Schweiz).

Die drei Hauptaufgaben sind:

1. [Erfassung der Arten geöffneter Orte](#orte).
1. [Erfassung von Regeln für Handelsketten](#handelsketten).
1. [Übersetzung von Blog-Artikeln](#blog).

## Orte

Die CSV-Datei [laender.csv](./laender.csv) enthält alle Informationen zu geöffneten Orten:

* Die erste Zeile ist die Kopfzeile. Sie enthält den [ISO-3166-1](https://de.wikipedia.org/wiki/ISO-3166-1-Kodierliste)- bzw. [ISO-3166-2](https://de.wikipedia.org/wiki/ISO_3166-2)-Code der jeweiligen Region.
* Jede weitere Zeile bezieht sich auf den OSM-Selektor in der ersten Spalte, z.B. `shop=supermarket` oder `delivery=yes`.
* Eine Zelle (Region-Spalte x Selektor-Zeile) enthält die Bezeichnung aus der Rechtsnorm, die die Öffnung des jeweiligen Orts erlaubt, z.B. `Lebensmittelhandel` (für `shop=bakery`, `shop=convenience`, `shop=supermarket` usw.).

## Handelsketten

Die CSV-Datei [ketten.csv](./ketten.csv) enthält Regeln für Orte, die zu einer Handelskette gehören. Dies sorgt für eine hilfreiche Anzeigung bei Orten der Handelskette, auch wenn noch keine `covid19`-Daten erfasst sind.

Die Daten für Handelsketten in D-A-CH übertragen wir regelmäßig in die [rules.csv](https://github.com/PanierAvide/Covid_enseignes/blob/master/rules.csv) des offiziellen Repositorys ([PanierAvide/Covid_enseignes](https://github.com/PanierAvide/Covid_enseignes/)).

Die CSV-Datei besteht aus 9 Spalten:

| Spalte | Erklärung |
|--------|-----------|
| `country` | [ISO-3166-1](https://de.wikipedia.org/wiki/ISO-3166-1-Kodierliste)-Code. Werte: `AT`, `CH` oder `DE` |
| `category` | z.B. `bakery`, `bank`, `books`, `car`, `car_rental`, `car_repair`, `chemist`, `doityourself`, `fuel`, `garden_centre`, `optician`, `stationery`, `supermarket` |
| `brand_name` | Name der Handelskette. Beispiel: `ALDI` |
| `wikidata_id` | Wikidata-ID der Handelskette. Beispiel: `Q125054` für [ALDI](https://www.wikidata.org/wiki/Q125054)
| `opening_rule` | Regel auf Englisch. Werte: `open` (offen, reguläre Öffnungszeiten), `open_adapted` (offen, abweichende Öffnungszeiten), `partial` (teilweise offen) oder `closed` (geschlossen) |
| `opening_hours` | Öffnungszeiten für alle Orte der Kette (falls zutreffend). Format siehe OSM-Wiki: [https://wiki.openstreetmap.org/wiki/DE:Key:opening_hours:covid19](opening_hours:covid19) |
| `description` | Beschreibung auf Deutsch. Beispiele: `Termin erforderlich.`, `Nur Post-Dienstleistungen.` oder `Nur telefonisch.` |
| `source_url` | URL der Webseite, von der die Information stammt. Beispiel: `https://www.tegut.com/newsticker-corona` |
| `opening_hours_url` | URL zur Webseite mit den aktuellen Öffnungszeiten. Beispiel: ` 	https://kamps.de/standorte` |

## Blog

Wichtige Artikel aus dem offiziellen Blog (https://blog.caresteouvert.fr/) werden im Verzeichnis [blog/](./blog) übersetzt. Wir verwenden einen Ordner je Artikel, um Anhänge mitabzulegen.
