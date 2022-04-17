---
author: kjk
navigationItem: Blog
title: Wie können agile Schätzungen mit einem monetärer Wert bewertet werden?
---


## Das Problem
Sie sind von einem klassischen Projektmanagement auf ein agiles Projektmanagement, wie Scrum, umgestiegen und fragen sich nun, wie man Kunden im agile Umfeld Entwicklungen in Rechnung stellen kann?
Dann haben Sie wahrscheinlich bisher Aufwände in Personentagen ermittelt.
Im agilen Umfeld ist die Aufwandsschätzung in Personentagen eher verpönt, daher wird häufig zur agilen Vorgehensweise mit Story Points gegriffen.
Jetzt stellt sich die Frage, wie können mit Story Points bewertete Anforderungen einem monetären Wert zugeschrieben werden, um diese dem Kunden als ein Angebot zu übermitteln und diese in Rechnung zu stellen?

## Agiles Schätzen
Zunächst möchte ich noch einmal klären, weshalb Personentage in der Softwareentwicklung nicht geeignet sind.  
Der wichtigste Aspekt ist, dass ein Personentag nicht einem Arbeitstag entspricht. Team-Mitglieder haben während eines Arbeitstages viele Tätigkeiten zu erledigen, die nicht direkt einen Beitrag zu einer zu entwickelnden Anforderung bietet. Solche Tätigkeiten könnten das Beantworten von E-Mails, jegliche Art von Besprechungen, Pair Programming, Support, Hilfestellung für andere Team-Mitglieder, Code Reviews und viele weitere sein. Eine Schätzung in Personentagen verleitet zudem leicht zu einer Verzerrung der Wahrnehmung für Liefertermine. Woraus wiederum Druck für das Entwicklungsteam entsteht, da diese nicht als schlechte Entwickler gehalten werden wollen. Darüber hinaus sollte darauf geachtet werden, dass Schätzungen von einem Team gemeinsam getroffen werden. Dies soll das Risiko von fehlerhaften Schätzungen durch einzelne verringern. Aus diesen Gründen sollte zu einer agilen Schätzung mit Story Points gegriffen werden.
Für die agile Schätzung muss zunächst bestimmt werden, was überhaupt geschätzt werden soll. Um einige Möglichkeiten zu nennen:
* Aufwand,
* Komplexität,
* und Risiko.

Für dieses Beispiel bleibe ich bei dem Aufwand. Das Team findet sich nun gemeinsam zur Schätzung ein. Die Anforderung wird im Team besprochen, sodass jedes Team-Mitglied ein Gefühl für die Anforderung errungen hat. Anschließend schätzt jedes Team-Mitglied die Anforderung anhand einer definierten Skala ab. In der Praxis wird häufig die Fibonacci-Folge (1, 2, 3, 5, 8, 13, 21, 34, 55, 89) oder eine Abwandlung dieser (1, 2, 3, 5, 8, 13, 20, 40, 100) genutzt. Da Story Points ein relatives Verhältnis darstellt, wird immer in Relation zu einer Referenzanforderung geschätzt. Also z.B. ist der Aufwand doppelt so groß oder evtl. nur die Hälfte des Aufwands. Wichtig ist hier zu beachten, dass Fehlerbehebungen nicht geschätzt werden. Dies hat den Hintergrund, dass an einer anderen Stelle bereits  unberechtigter Weise Story Points von dem Team erwirtschaftet wurde. Die Story Points sind unberechtigt, weil die Funktionalität offensichtlicher Weise nicht korrekt implementiert wurde. Für den Prozess der Schätzung ist die Vorgehensweise des Planning Pokers zu empfehlen. Im Rahmen dieses Blogeintrages werde ich jedoch nicht näher auf diese Thematik eingehen.  
Im Rahmen von Scrum werden nun Anforderungen mit Schätzungen in den Sprint bzw. das Sprint Backlog übertragen. Am Ende eines Sprints in dem Sprint Review wird ermittelt, wie viele Story Points von dem Team erreicht wurde. Und zwar ist dies die Summe der Story Points aller erledigten Anforderungen. Dies wird auch als Velocity bezeichnet. Die Velocity ist also die Entwicklungsgeschwindigkeit des Teams. Diese wird durch den Median aller summierten Story Points von vergangenen Sprints ermittelt. Ein wichtiger Pfeiler der agilen Softwareentwicklung ist der Empirismus. Also anders beschrieben: Wir wissen nur das, was wir wirklich gesehen haben. In unserem Fall ist dies die Velocity, da diese gemessen wurde. Vorteilhaft an der Velocity ist, dass diese viele Faktoren berücksichtigt. So auch die Faktoren, welche ich gegen Personentage angeführt habe [1].
Wir wissen nun, wie Anforderungen geschätzt werden können und wie die Entwicklungsgeschwindigkeit des Teams berechnet werden kann. Als nächstes stellt sich die Frage, was kostet die Anforderung dem Kunden?

## Preisermittlung für Anforderungen
Zunächst einmal müssen die Kosten für den Betrieb des Teams für den zugrunde liegenden Entwicklungszyklus, also dem Sprint, ermittelt werden. Dies lässt sich recht gut ermitteln. Für das Fallbeispiel gehe ich von einem Entwicklungszyklus der Dauer von 4 Wochen aus. Das Team besteht aus 10 Mitgliedern. Gehen wir von einem durchschnittlichen Gehalt von 3.500 € mit Lohnnebenkosten aus. Die Fix- und Nebenkosten für z.B. Büroräume, Hardware wie Laptops, Softwarelizenzen, Fortbildungen, etc. betragen für dieses Beispiel monatlich 5.000 €. Daraus resultieren reine Kosten von 40.000 €. Nun soll das eingesetzte Kapital auch Erträge erwirtschaften. Hierfür legen wir eine Return of Investment von 20 % nieder. Dies führt zu einem Wert des Teams von 48.000 €.

Beschreibung | Wert
-------- | --------
Gehalt   | 35.000 €
Fix- u. Nebenkosten   | 5.000 €
**Kosten**|**40.000 €**
ROI | 20%
**Wert**|**48.000 €**

Wir wissen jetzt, welchen Preis das Entwicklungsteam für 4 Wochen Arbeit hat. Gehen wir dabei von einer Velocity von 100 Story Points aus. Nun würde ein Kunde gerne eine Anforderung beauftragen, welche in Summe auf 30 Story Points geschätzt wurde, so ergibt dies 30 % des Team-Wertes, also 14.400 €. Dabei ist jedoch zu beachten, dass die Velocity des Teams durchaus Schwankungen ausgesetzt ist. Das Vorgehen funktioniert natürlich genauso, wenn eine Anforderung umfangreicher ist und über mehrere Sprints umgesetzt werden muss. Gehen wir von einer größeren Entwicklung mit 240 Story Points, also 240 % des Team-Wertes, aus. Daraus ergibt sich ein Preis von 115.200 €.




## Literatur:
[1] R. Wirdemann und J. Mainusch, Scrum mit User Stories, 3., Erweiterte Auflage. München: Hanser, 2017.
