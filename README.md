# Drupal Module: sogintegration

Dieses Modul ist in unserer CiviCRM Drupal Installation aktiviert und klinkt sich über Hooks in die Abläufe von CiviCRM ein um zusätzliche Integration in die SOG-spezifischen Systeme zu bieten.

## Registrierung neuer aktiver Mitglieder
Wenn sich ein neuer Nutzer über das Mitgliederformular von CiviCRM anmeldet, das in der öffentlichen Website eingebunden ist:
Erstellt einen LDAP User und fügt diesen zu den relevanten Gruppen hinzu (für Verteiler und andere SOG-Dienste).
Zudem benachrichtigt das Modul sowohl den neuen Nutzer als auch den zuständigen Lokalkoordinator.

## Registrierung mit Lastschrifteinzug
Das Modul generiert/setzt automatisch entsprechende Felder der Mitgliedschaft (Beitragshöhe, Mandatsreferenz) im CiviCRM Membership Eintrag und aktualisiert die Zuwendung (CiviCRM Contribution).
