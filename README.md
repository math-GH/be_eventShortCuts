# be_eventShortCuts (Contao-Erweiterung)

Erleichtert die Eingabe von Start- und Enddatum bei Events/Kalender-Einträge durch Shortcuts. Gleichzeitig wird bei der Datumseingabe der Kalender geöffnet.

##Shortcuts:
* "#": löscht Datum
* "=": Datum aus dem Nebenfeld übernehmen
* "++": Nebenfeld plus 1 Tag
* "--": Nebenfeld minus 1 Tag
* "+1" .... "+9": Nebenfeld plus x Tage
* "-1" .... "-9": Nebenfeld minus x Tage
* "t": heutiges Datum
* "l" (kleines L): letztes Datum eintragen*
* "y1970" .... "y2050": 1. Januar des Jahres XXXX
* "+d001" .... "+d999": Nebenfeld plus xxx Tage
* "-d001" .... "-d999": Nebenfeld minus xxx Tage
* [Shift]+[Pfeiltaste nach oben]: Felddatum +1
* [Shift]+[Pfeiltaste nach unten]: Felddatum -1

Hinweis zu "l": Über ein kleines Cookie wird das Datum gemerkt, dessen Datumeingabefeld zuletzt aktiv war.

##Beispiele
* Startdatum "31.12.2014", Enddatum "1.1.2015":
 * Eingabe:
  * Startdatum: "31.12.2014" (Ergebnis: "31.12.2014")
  * Enddatum: "++" oder "+1" oder ("=" und "[Shift]+[Pfeiltaste nach oben]") (Ergebnis: "1.1.2015")
* möchte man dann das Datum vom letzten Eintrag für das nächste Event verwenden (Startdatum "1.1.2015", Enddatum "10.1.2015"):
 * Eingabe:
  * Startdatum: "l" (Ergebnis: "1.1.2015")
  * Enddatum: "+9" oder "+d009" (Ergebnis: 10.1.2015)
