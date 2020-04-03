# caresteouvert-de

This repository is used to organise the expansion of [caresteouvert](https://github.com/osmontrouge/caresteouvert) to Germany.

## What shops are open or closed? 

### Baden-Württemberg

<details>
Source: https://corona.karlsruhe.de/content/downloads/200328_CoronaVO_Konsolidierte_Fassung.pdf

#### Open

- Supermärkte (`shop=supermarket`)
- Bäckereien (`shop=bakery`)
- Metzgereien (`shop=butcher`)
- Getränkehandlungen (`shop=beverages`)
- Wochenmärkte  (`amenity=marketplace`)
- Hofläden (`shop=farm`)
- Apotheken (`amenity=pharmacy`)
- Drogerien (`shop=chemist`)
- Sanitätsbedarf (Hör- und Sehhilfen) :arrow_right: `shop=medical_supply` and `shop=hearing_aids` and `shop=optician`
- Tankstellen (`amenity=fuel`)
- Banken (`amenity=bank`)
- Waschsalons (`shop=laundy`)
- Buch- und Zeitungsverkauf (`shop=books` and `shop=newsagent`)
- Baumärkte (`shop=hardware`) sowie Einzelhandel für Gartenbau (`shop=doityourself`)
- Geschäfte für Tiernahrung (`shop=agrarian;agrarian=feed`)

#### Closed

- Museen (`tourism=museum`)
- Theater (`amenity=theatre`)
- Schulen (`amenity=school `)
- Schwimm- und Hallenbäder (`leisure=swimming_pool`)
- Saunen (`leisure=sauna`)
- Spielplätze (`leisure=playground`)
- Friseure (`shop=hairdresser`), Kosmetikstudios (`shop=beauty`), Tattoo-Studios (`shop=tattoo`), Massagesalons (`shop=massage`)
- Hotels (für touristische Übernachtungen) :arrow_right: `amenity=hotel`
- Campingplätze (``)
- Wein- und Spirituosenhandlungen (`shop=alcohol`)
- Restaurants (Liefer- und Abholservice aber erlaubt) :arrow_right: `amenity=restaurant` except `pickup=yes` and/or `delivery=yes`
- Fahrradläden (`shop=bicycle`) (Werkstatt teilweise geöffnet)
- Shisha-Bars (`amenity=bar`)
</details>

### Bayern

<details>
Sources:

- https://www.stmwi.bayern.de/coronavirus/
- https://www.gesetze-bayern.de/Content/Document/BayIfSMV-2

#### Offen

> Ladengeschäfte des Einzelhandels jeder Art sind geschlossen. Ausgenommen davon sind der Lebensmittelhandel (`shop=supermarket`, `shop=convenience`), Getränkemärkte (`shop=beverages`), Banken (`amenity=bank`) und Geldautomaten (`amenity=atm`), Apotheken (`amenity=pharmacy`), Drogerien (`shop=chemist`), Sanitätshäuser (`shop=medical_supply`), Optiker (`shop=optician`), Hörgeräteakustiker (`shop=hearing_aids`), Verkauf von Presseartikeln (`shop=newsagent`), Filialen des Brief- und Versandhandels, Post (`amenity=post_office`), Tierbedarf (`shop=agrarian;agrarian=feed`), Tankstellen (`amenity=fuel`), Kfz-Werkstätten, Reinigungen (`shop=dry_cleaning`) und der Online-Handel (`delivery=true`). Sonstige Dienstleistungen, etwa Friseurbetriebe, sind nicht zulässig.

> Sämtliche gastronomische Betriebe (`amenity=restaurant`) müssen geschlossen bleiben. Erlaubt bleiben Angebote „to go“ (`pickup=yes`) und die Lieferung (`delivery=yes`) mitnahmefähiger Speisen und Getränke.


#### Geschlossen

> Alle Freizeiteinrichtungen (u. a. Sauna- und Badeanstalten, Kinos, Veranstaltungs- und Tagungsräume, Clubs, Bars, Diskotheken, Spielhallen, Theater, Vereinsräume, Bordellbetriebe, Museen, Stadtführungen, Sporthallen, Sport- und Spielplätze, Fitnessstudios, Bibliotheken, Wellnesszentren, Thermen, Tanzschulen, Tierparks, Vergnügungsstätten, Fort- und Weiterbildungsstätten, Volkshochschulen, Musikschulen, Jugendhäuser) müssen geschlossen bleiben. 
</details>

### Berlin

<details>
Source: https://www.rbb24.de/politik/thema/2020/coronavirus/beitraege/ausgangsbeschraenkung-kontaktverbot-berlin-was-ist-erlaubt.html

#### Open

- Supermärkte (`shop=supermarket`), Abhol- (`pickup=yes`) und Lieferdienste (`delivery=yes`), Spätverkaufstellen (...) (`shop=convenience`)
- Baumärkte (`shop=hardware`) sowie Einzelhandel für Gartenbau (`shop=doityourself`)
- Geschäfte für Tiernahrung (`shop=agrarian;agrarian=feed`)
- Tankstellen (`amenity=fuel`)
- Waschsalons (`shop=laundy`)
- Buch- und Zeitungsverkauf (`shop=books` and `shop=newsagent`)
- Banken (`amenity=bank`)
- Apotheken (`amenity=pharmacy`)
- Drogerien (`shop=chemist`)
- Sanitätsbedarf (Hör- und Sehhilfen) :arrow_right: `shop=medical_supply` and `shop=hearing_aids` and `shop=optician`
- Fahrradläden (`shop=bicycle`)

#### Closed

- Restaurants (Liefer- und Abholservice aber erlaubt) :arrow_right: `amenity=restaurant` except `pickup=yes` and/or `delivery=yes`
- Shisha-Bars (`amenity=bar`)
- Hotels (für touristische Übernachtungen) :arrow_right: `amenity=hotel`
- Friseure (`shop=hairdresser`), Kosmetikstudios (`shop=beauty`), Tattoo-Studios (`shop=tattoo`), Massagesalons (`shop=massage`)
</details>

### Brandenburg

### Bremen

### Hamburg

### Hessen

<details>
Source: https://www.hessen.de/sites/default/files/media/lesefassung4.coronavo.pdf

#### Offen

> (7) Die Beschränkungen nach Abs. 1 gelten nicht für

1. den Lebensmitteleinzelhandel (`shop=convenience`, `shop=supermarket`),
2. den Futtermittelhandel (`shop=pet`, `shop=pet_food`, `shop=pet_supply`),
3. die Wochenmärkte (`amenity=marketplace`),
4. den Direktverkauf vom Lebensmittelerzeuger (`?`),
5. die Reformhäuser (`shop=convenience`),
6. die Feinkostgeschäfte (`shop=deli`),
7. die Geschäfte des Lebensmittelhandwerks (`shop=bakery` etc.),
8. die Getränkemärkte (`shop=beverages`),
9. die Banken und Sparkassen (`amenity=bank`),
10. die Abhol- (`pickup=yes`) und Lieferdienste (`delivery=yes`),
11. die Apotheken (`amenity=pharmacy`),
12. die Drogerien (`shop=chemist`),
13. die Sanitätshäuser (`shop=medical_supply`), Optiker (`shop=opticien`), Hörgeräteakustiker (`shop=hearing_aids`),
14. die Poststellen (`shop=post_office`),
15. die Waschsalons (`shop=laundry`),
16. die Tankstellen (`shop=fuel`) und Tankstellenshops,
17. die Reinigungen (`shop=dry_cleaning`),
18. die Kioske (`shop=kiosk`), Tabak- (`shop=tobacco`) und E-Zigarettenläden, den Zeitungsverkauf (`shop=newsagent`),
19. die Blumenläden (`shop=florist`),
20. die Tierbedarfsmärkte (`shop=pet`, `shop=pet_food`, `shop=pet_supply`),
21. die Bau- (`shop=hardware`, `shop=doityouself`) und Gartenbaumärkte (`shop=garden_centre`);

> entscheidend  ist  der  Schwerpunkt  im  Sortiment. Die  Beschränkungen  nach  Abs.  1 gelten auch nicht für den Großhandel und den Online-Handel
</details>

### Mecklenburg-Vorpommern

### Niedersachsen

<details>
Source: https://www.niedersachsen.de/download/153804/Positivliste_Welche_Geschaefte_duerfen_weiterhin_oeffnen_bzw._welche_sozialen_Kontakte_sind_noch_zulaessig_Hinweise_des_Niedersaechsischen_Gesundheitsministeriums_vom_25.03.2020_.pdf

#### Offen

- Einzelhandel für Lebensmittel (`shop=convenience`), z.B. Supermärkte (`shop=supermarket`), Bäckereien (`shop=bakery`), Discounter (`shop=supermarket`), Teefachgeschäfte (`shop=tea`),
- Sonderpostenmärkte/ „Mischmärkte“
- Wochenmärkte (`amenity=marketplace`)
- Abhol- (`pickup=true`) und Lieferdienste (`delivery=true`)
- Online-Handel: Buchläden (`shop=books`) o.ä.
- Restaurationsbetriebe mit einem Außer-Haus-Verkauf (`pickup=true`)
- Getränkemarkte (`shop=beverages`)
- Einrichtungen/Leistungserbringer des Gesundheitswesens: Apotheken (`amenity=pharmacy`), Sanitätshäuser (`shop=medical_supply`), Optiker (`shop=opticien`), Hörgeräteakustiker (`shop=hearing_aids`), Physiotherpiepraxien, Psychotherapie, Logopädie, Podologie
- Heilpraktiker/Chiropraktiker
- Drogerien (`shop=chemist`)
- Tankstellen (`amenity=fuel`)
- Banken und Sparkassen (`amenity=bank`)
- Poststellen (`amenity=post_office`): DHL, Hermes, GLS, DPD, UPS, etc. (inkl. Paketstationen)
- Reinigungen (`shop=dry_cleaning`)
- Waschsalons (`shop=laundry`)
- Zeitungsverkauf: Kioske (`shop=newsagent`)
- Baumärkte (`shop=doityourself`, `shop=hardware`): Spezialisierte Geschäfte z.B. Farbe- oder Bodenfachgeschäfte (Abgabe von Waren an nicht-gewerbliche Kunden ist untersagt.)
- Gartenbaumärkte (`shop=garden_centre`): Blumenläden (`shop=florist`), Gärtnerei
- Tierbedarfsmärkte (`shop=pet`, `shop=pet_food`, `shop=pet_supply`)
- Großhandel
- Geschäfte des Landhandels mit Dünger, Pflanzenschutz, Saatgut, landwirtschaftlichen Maschinen, Ersatzteile usw. (`shop=agrarian`)
- KFZ - Werkstätten (`shop=car_repair`) und Ersatzteilhandel (`shop=car_parts`) und Landmaschinenreperatur und Landmaschinenersatzteile
- Fahrradreparatur, Fahrradersatzteilhandel (`shop=bicycle`)
- Autovermietungen (`amenity=car_rental`)
- Taxigewerbe (`amenity=taxi`)
- Verkauf von Fahrkarten für den ÖPNV
- Lieferung und Montage von Waren
- Campingbetriebe soweit nur für Dauercamper, teilweise ohne anderen Wohnsitz, beherbergt werden.
- Betriebliche Tätigkeiten bei geschlossen Läden
- KFZ-Schilderläden
- Imbisse in Tankstellen (`amenity=fast_food`)
</details>

### Nordrhein-Westfalen

<details>
(Source: https://www.land.nrw/sites/default/files/asset/document/2020-03-30_coronaschvo_idf_der_aendvo.pdf)

#### Open

> § 5 Handel
> Zulässig bleiben der Betrieb von 

1. Einrichtungen des Einzelhandels für Lebensmittel (`shop=convenience`), Direktvermarktungen von landwirt-schaftlichen Betrieben (`shop=agrarian`), Abhol- (`pickup=yes`) und Lieferdiensten (`delivery=yes`) sowie Getränkemärkten (`shop=beverages`), 
2. Apotheken, Sanitätshäusern und Drogerien, (`amenity=pharmacy` and `shop=medical_supply` and `shop=chemist`)
3. Tankstellen, Banken und Sparkassen sowie Poststellen, (`amenity=fuel` and `amenity=bank` and `amenity=post_office`)
4. Reinigungen und Waschsalons,  (`shop=dry_cleaning` and `shop=laundry`)
5. Kiosken und Zeitungsverkaufsstellen, (`shop=newsagent`)
6. Tierbedarfsmärkten, (`shop=agrarian;agrarian=feed`)
7. Einrichtungen des Großhandels. (`shop=supermarket`)
</details>

### Rheinland-Pfalz

<details>
Source: https://corona.rlp.de/fileadmin/rlp-stk/pdf-Dateien/Corona/Upload_3-4-2020_3._Corona-Bekaempfungsverordnung_RL_konsolidierte.pdf

#### Offen

> 2) Absatz 1 gilt nicht für

1. Einzelhandelsbetriebe für Lebensmittel, Getränkemärkte, Drogerien,
2. Verkaufsstände auf Wochenmärkten, deren Warenangebot den zulässigen Einzelhandelsbetrieben entspricht,
3. Apotheken, Sanitätshäuser,
4. Tankstellen,
5. Banken und Sparkassen, Poststellen,
6. Reinigungen, Waschsalons,
7. Zeitungs- und Zeitschriftenverkauf,
8. Bau-, Gartenbau- und Tierbedarfsmärkte,
</details>

### Saarland

### Sachsen

<details>
Source: https://www.coronavirus.sachsen.de/download/Fassung-RV-SaechsCoronaSchVO_31032020.pdf

* Versorgungswege  für  die  Gegenstände  des  täglichen  Bedarfs  (
  * Einzelhandel für  Lebensmittel (`shop=convenience`, `shop=supermarket`), 
  * der selbstproduzierenden und vermarktenden  Baumschulen  und  Gartenbaubetriebe,
  * der Hofläden (`shop=farm`), 
  * der Getränkemärkte (`shop=garden_centre`),
  * Tierbedarfsmärkte (`shop=pet`, `shop=pet_food`, `shop=pet_supply`),
  * Apotheken (`amenity=pharmacy`),
  * Drogerien (`shop=chemist`),
  * Sanitätshäuser (`shop=medical_supply`),
  * Optiker (`shop=opticien`),
  * Hörgeräteakustiker (`shop=hearing_aids`),
  * Banken, Sparkassen (`amenity=bank`) sowie Geldautomaten (`amenity=atm`),
  * Poststellen (`amenity=post_office`),
  * Tankstellen (`amenity=fuel`),
  * Kfz- (`shop=car_repair`) und Fahrradwerkstätten (`shop=bicycle`)
  * Reinigungen (`shop=dry_cleaning`),
  * Waschsalons (`shop=laundry`),
  * des Zeitungsverkaufs (`shop=kiosk`, `shop=newsagent`) sowie 
  * die Abgabe von Briefwahlunterlagen) und
* den Großhandel,
</details>

### Sachsen-Anhalt

### Schleswig-Holstein

<details>
Source: https://www.schleswig-holstein.de/DE/Schwerpunkte/Coronavirus/Erlasse/positivliste_verordnung_corona.html

#### Offen

> Diese Geschäfte dürfen geöffnet bleiben:

- Abhol- und Lieferdienste einschließlich solche des Online-Handels (Logistiker, Lieferunternehmen)
- Retouren- und Lieferdienste, die von nicht zulässigen Verkaufsstellen des Einzelhandels angeboten werden (...)
- Apotheken
- Augenoptiker
- Außer-Haus-Verkauf von Gaststätten nach vorheriger telefonischer oder elektronischer Bestellung (...)
- Autovermietung, Car-Sharing
- Bäckereien
- Banken und Sparkassen
- Baumärkte
- Baustoffhandel
- Beherbergungsbetriebe, Ferienwohnungen, sofern sie nicht für touristische Zwecke genutzt werden.
- Bestatter
- Brennstoffhandel
- Denkmal-, Fassaden- und Gebäudereiniger
- Drogerien
- Ersatzteilverkauf in Werkstätten, Autoteile- und Zubehörverkauf
- Fahrradwerkstätten
- Freie Berufe
- Gärtnereien
- Gartenbaubedarf
- Getränkemärkte
- Goldankauf
- Großhandel
- Hofläden
- Hörakustiker
- Hundefrisöre, wenn sichergestellt ist, dass die Tierbesitzer sich nicht in den Räumlichkeiten aufhalten
- Kfz-Werkstätten
- Kioske
- Krematorien
- Landhandel mit Dünger, Pflanzenschutz, Saatgut, landwirtschaftlichen Maschinen, Ersatzteilen usw.
- Landmaschinenreparatur, Landmaschinenersatzteile
- Lebensmitteleinzelhandel
- Metzgereien
- Mischbetriebe des Handwerks, die daneben auch verkaufen
- Orthopädieschuhmacher
- Orthopädietechniker
- Personal Trainer, Ernährungsberater und ähnliche Dienstleister in Einzelberatung
- Pfandleiher
- Poststellen, Postagenturen und Paketstationen
- Raiffeisenmärkte
- Recyclinghöfe, Annahmestellen der Kreislaufwirtschaft
- Reisebüros, wenn kein direkter Kundenkontakt besteht
- Sanitätshäuser
- Schädlingsbekämpfer
- Schornsteinfegerbetriebe
- Schuh- und Schlüsselreparatur
- Servicestellen von Telekommunikationsunternehmen
- Spezialisierte Baustoffhändler für Farben, Bodenflächen usw.
- Spezialisierter Lebensmitteleinzelhandel (z.B. Süßwaren, Tee, Kaffee, Wein, Spirituosen)
- Stördienste aller Art, insbesondere Schlüsseldienste
- Tankstellen
- Textilreinigung
- Tierbedarf
- Verkauf von Jägereibedarf
- Verkehrsdienstleistungen aller Art einschließlich Taxi
- Warenlieferung und Montage
- Waschsalons
- Wochenmärkte
- Zahntechniker
- Zeitungs- und Zeitschriftenverkauf
</details>

### Thüringen

