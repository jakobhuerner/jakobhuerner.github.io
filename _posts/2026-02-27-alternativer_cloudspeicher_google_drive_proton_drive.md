---
layout: post
title: Die bessere Alternative für Cloudspeicher
categories: [General]
excerpt: Der Umstieg bei Cloudspeicher zu einer datenschutzfreundlichen Alternative geht einfach, erfordert aber etwas Aufwand
image: /images/general/20260206_celebrate_digital_sovereignty_2.jpg
---

*Dieser Beitrag ist  Teil einer Serie über meinen Umstieg von Google & Co zu datenschutzfreundlichen und bevorzugt europäischen Diensten, [zur Übersicht](../digitale-souveraenitaet_email_kalender_cloud/).*


Egal ob Urlaubsfotos, Diplomarbeiten, Zeugniskopien oder die Dokumentation der Wohnungsübergabe: Derartige Dateien dauerhaft und sicher zu archivieren ist für eines der zentralen Themen des digitalen Lebens.

Ohne zu viel in [Backupstrategien](https://de.wikipedia.org/wiki/Datensicherung#3-2-1_Backup-Regel) einzusteigen liegt es auf der Hand, dass die einfache Speicherung wichtiger Daten nur am Computer oder Smartphone nicht empfehlenswert ist. Ein Cloudspeicher ist meist eine sinnvolle zusätzliche Säule in der eigenen Sicherungsstrategie. Cloudspeicher stellt einerseits einen eigenständigen Typ von Speichermedium dar, andererseits ist er in jedem Fall räumlich getrennt von anderen - lokalen - Speicherungen. Damit ist er eine sinnvolle Ergänzungen zur klassischen externen Festplatte, die wohl viele im Einsatz haben.

Wenn es um wichtige persönliche Daten und Cloud geht, ist die Datensicherheit ein Thema: Wo liegen meine Daten? Wer hat Zugriff? Welches Unternehmen steckt hinter dem Clouddienst?

Diesen Überlegungen folgend kommt man schnell zum Thema *Verschlüsselung* der eigenen Daten. Soll es umfassende Verschlüsselung sein, ist man als Otto-Normal-Verbraucher in technisch herausforderndem Territorium. Insbesondere sollten auch keine Anwender:innenfehler passieren, die das ganze Archiv unbrauchbar machen - geht es doch um die langfristige Sicherung!

Für mich eine gute Lösung ist, auf Dienste zurückzugreifen, die Verschlüsselung und entsprechende Datensicherheit für Endanwender nahtlos in das Produkt eingebaut haben. In meinem Fall setze ich hierbei auf Proton Drive.

## Die Vor- und Nachteile

Positiv

- Hauptargument für Proton Drive ist das Thema Sicherheit: Daten sind Ende-zu-Ende verschlüsselt, sodass weder der Anbieter selbst noch sonstige Akteure darauf zugreifen können, außer eine explizite Freigabe durch den Besitzer wurde erteilt.
- Andere würden diesen Punkt unter Nachteil anführen, für mich ist es aber ein Kernargument für den Dienst: Es gibt keine KI-Zusammenfassung der eigenen Dokumente, keine Suche nach Inhalten von Bildern und Videos und dergleichen. Aufgrund der Datenschutz- und Verschlüsselungprämissen sind bei Proton Drive das Scannen der Daten und KI-Auswertungen durch den Anbieter und damit auch die genannten Komfortfunktionen nicht möglich.
- Der Funktionsumfang umfasst alles was ich brauche. Einerseits was die reine Dateispeicherung betrifft, andererseits bietet Proton auch wie die Konkurrenz von Google und Microsoft die Möglichkeit, Dokumente und Tabellenkalkulationen online zu erstellen und zu bearbeiten (wenn auch im Vergleich mit eingeschränktem Funktionsumfang).

Negativ

- Die Kosten sind im Vergleich zu Google und Co höher. Im Bereich von 2 TB Speicher zum Zeitpunkt des Verfassen dieses Artikels liegt die Preisdifferenz bei +80 EUR pro Jahr. 
- Ich führe meine Backups bewusst manuell basierend auf einer chronologischen Ordnerstruktur durch und lasse keine automatischen Backuproutinen laufen. Betreffend Interoperabilität mit anderen Tools und betreffend Automatisierbarkeit ist Proton Drive eingeschränkt.
- Der Proton Drive Client für MacOS funktioniert bei mir prinzipiell, jedoch ist das Hochladen großer Datenmengen langsam, da es zwischen dem Upload einzelner Dateien immer Sekunden „Leerlauf“ gibt. Das kann an Proton, aber auch an meinem Gerät und anderer laufender Software liegen. Für mich die beste Lösung war es, für den initialen Upload auf ein altes Windows-Gerät zurückzugreifen. Der Proton Drive Client für Windows funktioniert einwandfrei und schnell.

## Die Umstellung

Der Wechsel auf einen neuen Anbieter erfordert hier im Vergleich zu Email oder Suchmaschine sicher mehr Aufwand und Zeit, müssen doch alle Daten erst einmal in den neuen Cloudspeicher geladen werden.

Dazu verwendete ich den Proton Drive Client am Windows-Computer, der auch für große Datenmengen im TB-Bereich zuverlässig funktioniert. Die hochzuladenden Dateien kopiert man in den entsprechenden Ordner am Computer, der Client synchronisiert den gesamten Inhalt dieses Ordners dann automatisch und im Hintergrund mit dem Proton Drive. Je nach Internetverbindung und Datenmenge kann dieser erstmalige Uploadvorgang durchaus stunden- bis tagelang laufen.

Die zukünftigen Backups der neu hinzugekommenen Daten kann man dann ebenfalls mit dem Client, oder je nach Datenmenge auch einfach über die Weboberfläche durchführen.

## Zwei Empfehlungen zum Schluss

Nummer eins: Wenn man den Cloudspeicher als Backup nutzt, halte ich es für ratsam, die Verbindung dazu bewusst getrennt zu halten, wenn man kein Backup oder keine Wiederherstellung durchführt. Konkret heißt das, den Client am Computer nicht permanent laufen zu lassen. Damit schließt man aus, dass man im Alltag versehentlich Änderungen an den lokalen Daten durchführt, die dann automatisch in die Cloud synchronisiert werden und den Backup-Datenstand verändern.

Nummer zwei: Ich empfehle auch sicherzustellen, dass die Daten wieder aus dem Cloudspeicher korrekt exportiert werden können. Im Zuge der initialen Beladung empfehle ich testweise zumindest mehrere Ordner und möglichst auch nennenswerte Datenmengen wieder zu exportieren und auf Korrektheit und Vollständigkeit zu prüfen.

Ein Backup nützt einem nur etwas, wenn im Fall des Falles auch alle Daten im Backup vorhanden sind und sich korrekt wiederherstellen lassen.