---
author: kjk
navigationItem: Blog
title: User Story Mapping - Vision eines Produktes
---

Eine User Story Map dient zur Darstellung der Vision eine Produktes im agilen Projektmanagement wie z.B. Scrum. Sie beschreibt auf der horizontalen Ebene die Geschichte des Produktes. Also denn Fluss von Tätigkeiten die Benutzer durch das Produkt führen. Die vertikale Ebene zeichnet dabei die Details zu verschiedenen Aufgabe, welche ein Benutzer erfüllen will.

Dieses Tool hilft Teams dabei gute Software zu entwickeln. Es liefert, wie wir sehen werden, Ansätze um ein kleinstmögliche Releaseversion zu indentifizieren. Außerdem ist die User Story Map ein wundervolles Tool, um die Transparenz für Stakeholder zu steigern.

Die User Story Map lässt sich auf der vertikalen Ebene in 4 Abschnitte unterteilen. Ganz oben steht die Benutzerrolle. Diese möchte bestimmte Aktivitäten bewältigen. Dabei sind die Aktivitäten als eine Gruppierung von Aufgaben zu verstehen. Jede Aufgabe wiederrum besteht auf der untersten Ebene aus Details. Diese definieren, was eine Aufgabe im Kern ausmacht.

## Fallbeispiel

![User Story Map](/assets/img/user-story-map.svg)
<div id="user-story-map" class="figure-title">Abb. 1: User Story Map</div>

Im Rahmen dieses Posts wollen wir uns die User Story Map und den Weg zu solch einer User Story Map anhand eines konkreten Fallbeispiels anschauen. Dazu soll eine Anwendung entwickelt werden, welche es Kunden erlaubt per App im Restaurant zu bestellen. Dafür muss der Restaurant Inhaber natürlich auch mit der Anwendung interagieren und seine Karte verwalten. Des Weiteren sieht die Roadmap des Produktes zwei Release vor, einmal ein *Minimal Viable Product (MVP)* und eine Erweiterung des MVPs.  Das Resultat der User Story Map ist in [Abb. 1](#user-story-map) dargestellt.

## Der Weg zur User Story Map

Der Weg zur User Story Map ist recht simpel und besteht aus 5 Schritten. Diese 5 Schritte führen zu User Stories, bereit zur Umsetzung. Die folgende Abbildung ([Abb. 2](way-user-story-map)) zeigt die 5 Schritte auf.

![Der Weg zur User Story Map](/assets/img/way-to-user-stpry-map.svg)
<div id="way-user-story-map" class="figure-title">Abb. 2: Der Weg zur User Story Map</div>

## Benutzeraufgaben ermitteln (Schritt 1)
Zunächst einmal muss man sich Gedanken machen, was das Produkt überhaupt ermöglichen soll. Dazu müssen die Benutzeraufgaben ermittelt werden. Diese sind konkrete Aufgabe oder auch Aktionen, die ein Benutzer ausführt um sein Ziel zu erreichen. Nehmen wir hierzu unser Fallbeispiel zur hilfe. Das Ziel des Gastronomen ist es, dass seine Kunden Gerichte bestellen können. Dazu müssen die Kunden natürlich Gerichte auswählen. Damit ein Gericht gewählt werden kann muss dieses erst einmal erfasst werden könnnen. Um Benutzeraufgaben zu finden, bietet sich das Brainstorming an. Dazu versetzt man sich in die Rollen der Anwender und sammelt die Benutzeraufgaben, welche einem in den Sinn kommen. Wichtig ist dabei natürlich die nähe zu den Stakeholdern. Diese sollten in dem Prozess involviert werden.

Eine weitere Frage, welche beantwortet werden muss ist die Frage nach der Größe von Benutzeraufgaben. Dazu kann auf das Konzept Sea Level von Alistair Cockburn zurückgegriffen werden. Benutzeraufgaben befinden sich auf dem Meeresspiegel (auf Sea Level). Alles unter dem Sea Level sind Unteraufgaben, welche erfüllt werden müssen, um die Aufgabe auf dem Meeresspiegel zu bewältigen. Alles über dem Meeresspiegel sind grobe Zusammenfassungen von mehreren Benutzeraufgaben, also ein übergeordnetes Ziel. Ralf Wirdemann beschreibt es als Aufgaben, welche abgeschlossen werden, bevor die nächste Aufgabe angegangen wird. In unserem Fallbeispiel haben wir die Benutzeraufgabe *Gericht erfassen* definiert. Dies ist eine Aufgabe auf dem Sea Level. Darunter liegen Subaufgaben, welche zum erreichen des Ziels führen. Darüber ist die Benutzeraktivität *Karte verwalten* gegliedert. Diese beinhaltet jedoch auch die Benutzeraufgabe *Gericht entfernen* und ist somit nicht auf dem Sea Level.

## Benutzeraktivitäten bilden (Schritt 2)
Nachdem man im Brainstorming die Benutzeraufgaben ermittelt hat, müssen diese zu Benutzeraktivitäten gruppiert werden. Dazu nimmt man sich die verschiedenen Benutzeraufgaben, gruppiert diese und eliminiert duplikate. Dabei kann auch festgestellt werden, das man Aufgaben ermittelt hat, welche unter dem metaphorischen Meeresspiegel liegen. Diese werden zu Benutzeraufgaben zusammen gefasst. Jede Gruppe bekommt einen Namen, dies sind unsere Benutzeraktivitäten. Im Fallbeispiel haben wir die Benutzeraktivitäten *Gericht bestellen* und *Rechnung bezahlen* zu der Benutzeraktivität *Essen gehen* zusammengefasst. 

## Benutzeraktivitäten ordnen (Schritt 3)
Die gruppierten Benutzeraktivitäten werden im dritten Schritt in eine Reihenfolge, entlang der horizantalen Ebene, gebracht. Diese beschreibt den Fluss der Benutzer durch die Anwendung. Damit hat man den wichtigsten Bestandteil der User Story Map erschaffen. Es beschreibt die Vision des Produktes und enthält alle wichtigen Teile dessen. Es fehlen nur noch die genauen Details, welche im 5. Schritt definiert werden.

## User Story Map durchlaufen (Schritt 4)
Nun folgt einer der wichtigsten Schritte zur Erstellung einer User Story Map. Der Product Owner, im Scrum Umfeld, erzählt anhand der User Story Map die Geschichte des Produktes. Dabei nutzt er die gebildeten Benutzeraktivitäten und Benutzeraufgaben. Er durchläuft dabei die User Story Map von links nach rechts. Er erzählt den Stakeholdern, wie Benutzer die Anwendung durchlaufen. Dabei wird validiert, dass alles bedacht wurde und Lücken können geschlossen werden.

## User Stories definieren (Schritt 5)
Der letzte Schritte besteht daraus die Details zu erarbeiten und User Stories zu definieren. Dazu wird konkret beschrieben, was alles erledigt werden muss, um eine Benutzeraufgabe zu erfüllen. Diese Details können dann zu formalen User Stories konvertiert werden und in das Product Backlog übernommen werden.

## Fazit
Ich denke, dass die User Story Map im agilen Umfeld ein sehr hilfreiches Tool ist und bei der Entwicklung von Awendungen behilflich sein kann. Es hilft allen Beteiligten einen Überblick über das Produkt und der Vision zu erhalten.