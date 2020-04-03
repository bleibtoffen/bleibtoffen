# caresteouvert-de

This repository is used to organise the expansion of [caresteouvert](https://github.com/osmontrouge/caresteouvert) to Germany.

## What shops are open or closed? 

### Baden-Württemberg

Source: https://corona.karlsruhe.de/content/downloads/200328_CoronaVO_Konsolidierte_Fassung.pdf

#### Open

- Supermärkte (`shop=supermarket`)
- Bäckerreien (`shop=bakery`)
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

### Bayern

Sources:

- https://www.stmwi.bayern.de/coronavirus/
- https://www.gesetze-bayern.de/Content/Document/BayIfSMV-2

#### Offen

> Ladengeschäfte des Einzelhandels jeder Art sind geschlossen. Ausgenommen davon sind der Lebensmittelhandel (`shop=supermarket`, `shop=convenience`), Getränkemärkte (`shop=beverages`), Banken (`amenity=bank`) und Geldautomaten (`amenity=atm`), Apotheken (`amenity=pharmacy`), Drogerien (`shop=chemist`), Sanitätshäuser (`shop=medical_supply`), Optiker (`shop=optician`), Hörgeräteakustiker (`shop=hearing_aids`), Verkauf von Presseartikeln (`shop=newsagent`), Filialen des Brief- und Versandhandels, Post (`amenity=post_office`), Tierbedarf (`shop=agrarian;agrarian=feed`), Tankstellen (`amenity=fuel`), Kfz-Werkstätten, Reinigungen (`shop=dry_cleaning`) und der Online-Handel (`delivery=true`). Sonstige Dienstleistungen, etwa Friseurbetriebe, sind nicht zulässig.

> Sämtliche gastronomische Betriebe (`amenity=restaurant`) müssen geschlossen bleiben. Erlaubt bleiben Angebote „to go“ (`pickup=yes`) und die Lieferung (`delivery=yes`) mitnahmefähiger Speisen und Getränke.


#### Geschlossen

> Alle Freizeiteinrichtungen (u. a. Sauna- und Badeanstalten, Kinos, Veranstaltungs- und Tagungsräume, Clubs, Bars, Diskotheken, Spielhallen, Theater, Vereinsräume, Bordellbetriebe, Museen, Stadtführungen, Sporthallen, Sport- und Spielplätze, Fitnessstudios, Bibliotheken, Wellnesszentren, Thermen, Tanzschulen, Tierparks, Vergnügungsstätten, Fort- und Weiterbildungsstätten, Volkshochschulen, Musikschulen, Jugendhäuser) müssen geschlossen bleiben. 

### Berlin

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

### Brandenburg

### Bremen

### Hamburg

### Hessen

### Mecklenburg-Vorpommern

### Niedersachsen

### Nordrhein-Westfalen

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

### Rheinland-Pfalz

### Saarland

### Sachsen

### Sachsen-Anhalt

### Schleswig-Holstein

### Thüringen

