---
layout: post
title: 'Wie bearbeite ich die #caresteouvert-Hinweise?'
source: https://blog.caresteouvert.fr/contributeurs-openstreetmap-comment-traiter-les-notes-caresteouvert/
---

OpenStreetMapper\*innen, aufgepasst: Bei der Meldung von Änderungen über „Bleibt offen“ werden teilweise OSM-Hinweise erzeugt. Dieser Artikel erklärt, wann dies der Fall ist und wie diese Hinweise bearbeitet werden können.

## Automatische Übernahme oder OSM-Hinweis?

„Bleibt offen“ zeigt bei allen Geschäften eine Schaltfläche „Änderung melden“, über die **jeder ganz einfach** melden kann, ob und wann das Geschäft geöffnet hat und ob es Lieferung oder Abholung anbietet.

Diese **strukturierten Daten** werden normalerweise **automatisch nach OpenStreetMap übernommen**, und zwar über den Proxy-User [CaResteOuvert_visitor](https://www.openstreetmap.org/user/CaResteOuvert_visitor).

![Bild](https://blog.caresteouvert.fr/wp-content/uploads/2020/04/image-2.png)
<br />(Bild: *Schaltfläche „Änderung melden“ auf „Bleibt offen“*)

Es gibt jedoch auch ein **Freitextfeld für weitere wichtige Angaben**, etwa fehlende Kontaktdaten oder ob ein vorheriger Anruf erforderlich ist. Das Feld wird auch teilweise genutzt, um auf Namensänderungen, dauerhaft geschlossene Geschäfte oder fehlende Geschäfte in unmittelbarer Nähe hinzuweisen.

Wird dieses Kommentarfeld ausgefüllt, werden die strukturierten Daten **nicht automatisch übernommen**, sondern es wird **stattdessen ein OSM-Hinweis erstellt**. Somit sind die Änderungen nicht sofort in der Karte verfügbar, sondern erst, wenn der OSM-Hinweis von OpenStreetMapper\*innen bearbeitet und die Angaben manuell übernommen wurden.

In diesem Beitrag erfährst du in **drei Schritten**, wie du dabei mitmachen kannst, ohne das Haus zu verlassen.

## Schritt 1: Hinweise finden

Um offene Hinweise zu finden, rufe zunächst [NotesReview](https://ent8r.github.io/NotesReview/?query=%23caresteouvert) auf.

![Bild](https://blog.caresteouvert.fr/wp-content/uploads/2020/04/image-3.png)
<br />(Bild: *Ein Hinweis aus „Bleibt offen“ in „NotesReview“.*)

Die verschiedenen Marker auf der Karte zeigen **offene Hinweise** an. Wähle einen Marker aus, um loszulegen.

Wenn du keine Marker siehst, liegt das wahrscheinlich daran, dass alle Hinweise bereits abgearbeitet wurden! Warte einfach ein paar Stunden ab und versuche dein Glück erneut… 😉

## Schritt 2: OpenStreetMap bearbeiten

Alle OSM-Hinweise von „Bleibt offen“ sind gleich aufgebaut und bestehen aus fünf Abschnitten:

* Die 1. Zeile enthält vor allem Hashtags, die die Filterung erleichtern, z.B. `#caresteouvert`**`DE`** (statt `#caresteouvert`) für Hinweise aus Deutschland.
* Im 2. Abschnitt findest du den Namen des Objekts und einen Direktlink zum Objekt in OpenStreetMap.
* Der 3. Abschnitt enthält den Status (entweder „derzeit geschlossen“ oder „weiterhin geöffnet”) und die Anmerkungen aus dem Freitextfeld.
* Der 4. Abschnitt listet alle strukturierten Daten (Öffnungszeiten, Abholung, Lieferung) als Tags auf und ermöglicht die einfache Übernahme per „Copy & Paste“ nach JOSM.
* Im 5. Absatz wird auf die Wiki-Dokumentation hingewiesen.

Um andere Angaben in nützliche Tags zu übersetzen, schaue am besten in der [Wiki-Dokumentation](https://wiki.openstreetmap.org/wiki/DE:Key:opening_hours:covid19#Verwendung) nach. Diese enthält eine Übersicht aller derzeit verwendeten Tags mit dem `covid19`-Suffix und ihre Bedeutung.

## Schritt 3: Hinweis schließen

Sobald du die Änderung in OpenStreetMap hochgeladen hast, denke daran, die Notiz zu schließen, damit sie nicht länger in der Liste auftaucht:

* Klicke in **NotesReview** auf den *OpenStreetMap*-Link, um die Notiz auf OpenStreetMap.org zu öffnen.
* Klicke dort auf die Schaltfläche „Erledigt“.

![Bild](https://blog.caresteouvert.fr/wp-content/uploads/2020/04/image-5.png)
<br />(Bild: *Hinweis auf OpenStreetMap.org als „Erledigt“ markieren*)

**Herzlichen Glückwunsch!** Jetzt braucht es nur noch etwas Geduld, bis die Änderungen auch auf der Karte von „Bleibt offen“ berücksichtigt werden! (In der Regel weniger als eine Stunde.)

## Tipp: Editor in NotesReview konfigurieren

Um effektiver zu sein, kannst du in der NotesReview-Oberfläche den relevanten Kartenausschnitt direkt in einem OpenStreetMap-Editor deiner Wahl laden. Öffne dazu die Einstellungen über das Zahnrad rechts oben, treffe anschließend deine Wahl und speichere die Einstellungen.

![Bild](https://blog.caresteouvert.fr/wp-content/uploads/2020/04/image-4.png)
<br />(Bild: *Editor-Auswahl in den Einstellungen von NotesReview*)