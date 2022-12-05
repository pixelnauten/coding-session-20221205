# shopping-cart

- Umsetzung erfolgt in
  - PHP 7.4 oder 8.x

- Folgende PHP Klassen sollen erstellt werden:
  - Einen Warenkorb mit den folgenden Funktionen
    - Neues Item in den Warenkorb packen
    - Ein Item wieder aus dem Warenkorb entfernen
    - Kosten der Items berechnen
  - Eine Bestands Klasse
    - Hier werden alle Items die es zu kaufen gibt hinterlegt
    - Folgende Funktionen sollen bereitgestellt werden
      - Ein Item hinzufügen
  - Eine Item Klasse
    - Mit den folgenden Attributen
      - Name
      - Preis
    - Folgende Funktionen sollen bereitgestellt werden
      - Preis zurückgeben
  - Eine Klasse die den User repräsentiert
      - Mit den folgenden Attributen
        - E-Mail
        - Vorname
        - Nachname
        - Warenkorb (siehe Klasse Warenkorb)
      - Folgende Funktionen sollen bereitgestellt werden
        - Setter / Getter für alle Attribute

- Es soll ein lauffähiger Code mit den vorgebenen Klasse erstellt werden
  - Ein neuer User wird inialisiert 
  - Die Bestandsklasse wird mit 5 beliebigen Items gefüllt
  - Der Warenkorb des User wird mit 3 zufälligen Items aus dem Bestand gefüllt
  - Der User überprüft die Kosten seines Warenkorbs
  - Sind die Kosten höher als X werden solange Items entfernt und hinzugefügt bis die Kosten unter / gleich X sind und es genau 3 Items sind

- Zusätzliche Anmerkungen
  - Die Bestands-Items sollten so gewählt sein das bei der Kostenüberprüfung beide Fälle eintreten können
  
- Optional
  - Instanzieren der Klassen über Factories
  - Warenkorb mit einem Singelton schützen
  - Exception Handling
  - Das Speichern / Laden des Warenkorb mit einem Memento ermöglichen
  - PHP Session mit einbinden damit der User / Warenkorb aus der Session kommt



    
