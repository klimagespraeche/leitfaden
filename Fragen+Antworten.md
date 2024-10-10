grundsätzliche Fragen & Antworten zu diesem Leitfaden
=====================================================

## Ist das hier der _offizielle_ Leitfaden für den "Raum für Klimagespräche"?

Nein. Es gibt keinen offiziellen Leitfaden. Das hier ist nur eine von vielen Arten, wie man es angehen kann. Es ist ein Experiment. Wer mag, kann sich daran beteiligen.

## Ist das nicht viel zu kompliziert für sowas Simples wie einen kleinen Leitfaden?

Vielleicht. Das wird sich noch zeigen. Die Bedienung ist jedenfalls garnicht so kompliziert, wie es zu Beginn vielleicht aussieht. Diese Versionsverwaltung hat Vorteile (siehe unten). GitHub ist aber definitv zu unübersichtlich für unsere Zwecke. Deshalb wollen wir eine passendere Git-basierte Plattform suchen.

## Was ist Git? Was ist GitHub?

[Git](https://git-scm.com) ist ein Werkzeug zur Versionsverwaltung. Während Git in der Softwareentwicklung und in manchen akademischen Bereichen zu den Standard-Anwendungen zählt, die jeder kennt, kommt es außerhalb davon seher selten zum Einsatz und ist kaum bekannt.
Git verwaltet mehrere Dateien gleichzeitig in einem sogenannten _Repository_.

GitHub ist eine Online-Plattform auf der kostenlos Git-Repositories gespeichert und öffentlich zugänglich gemacht werden können. GitHub ermöglicht auch die Online-Bearbeitung der verwalteten Dateien bei gleichzeitiger Versionierung.

## Warum Git?

##### Der unwahrscheinliche Best Case
Es besteht die Möglichkeit, dass die Aktionsform "Raum für Klimagespräche" unter den Teilnehmern viel Anklang findet und dadurch die Anzahl der Teilnehmer und Organisatoren sowie die Häufigkeit der Aktionen stetig anwachsen. Im besten Fall könnte es sogar sein, dass sich die Aktionsform so etabliert, dass sie jahrelang fortgeführt wird und sich mit der Zeit auch andere Gruppen bilden, die das Konzept leicht abgewandelt übernehmen wollen.

##### Die Herausforderung ...
Selbst wenn dieser Best Case nicht eintritt, müssen wir davon ausgehen, dass der Leitfaden immer wieder überarbeitet wird, weswegen eine Versionskontrolle sinnvoll ist. Und wir müssen darauf vorbereitet sein, dass sich zukünftig sehr unterschiedliche Personen an der Weiterentwicklung und Durchführung des Konzepts beteiligen werden. Jede Person wird ihre eigene Vorstellung davon haben, wie der optimale Leitfaden auszusehen hat, und es wird nicht immer möglich sein, alle diese Auffassungen unter einen Hut zu bringen.

##### ... als Chance sehen
Anstatt sich jedesmal aufs Neue in Grundsatz-Debatten zu verlieren, wollen wir diese ***Vielfalt begrüßen und beibehalten***. Deshalb soll es möglich sein, _parallel_ an unterschiedlichen Versionen des Leitfadens zu arbeiten. 

##### Das Beste Tool seiner Art
Genau dies ist die Stärke von Git: Es verwaltet die Versionen des Repositories in einer baumförmigen Historie. Man kann jederzeit von einem existierenden Entwicklugnsstrang abzweigen (_branch_) und somit eine Parallelentwicklung starten. Und man kann bestehende Zweige jederzeit wieder zusammenführen, sodass das Beste aus beiden Zweigen kombiniert wird (_merge_).
Git befähigt uns, sowohl lineare inkrementelle Verbesserungen (_commit_) als auch komplett unabhängige parallele Entwicklungen an den Dokumenten vorzunehmen. Es gibt natürlich auch andere Versions-Kontroll-Werkzeuge mit ähnlichen Funktionen. Aber Git ist das mit Abstand am weitesten Verbreitete. Hunderte kostenlose und kommerzielle Programme und Online-Plattformen sind mit Git kompatibel. Dadurch ist sichergestellt, dass das zugrundeliegende Format des Git-Repositories noch jahrzehntelang Bestand haben wird. Wir setzen also auf einer äußerst skalierbaren und kompatiblen Lösung auf.

## Warum GitHub?

GitHub ist die größte und bekannteste Plattform für Git. Die Anmeldung ist einfach und kostenlos, und man muss sich nichts auf dem Computer oder dem Smartphone installieren.
Allerdings ist GitHub für die Softwareentwicklung ausgelegt und nicht wirklich für unsere Zwecke. Die Oberfläche bietet viel zu viele Optionen und ist nur in Englisch verfügbar.
Deshlab ist GitHub nur eine Übergangslösung, bis wir eine Plattform gefunden haben, die vom Funktionsumfang besser zu uns passt.
Der Umzug des Repositories von der einen Git-Plattform auf die Andere wird dann sehr einfach sein.

## Welche Version des Leitfadens sollen wir bei den Aktionen anwenden?

Verschiedene parallel existierende Versions-Stränge (_branches_) stellen möglicherweise verschiedene Auffassungen dar, wie das Klimagespräch durchzuführen ist oder an welche Regeln man sich im Gespräch halten soll. Das ist eine hervorragende Grundlage zum Experimentieren: Am Besten führt man mehrere Klimagesprächs-Aktionen durch und hält sich dabei mal an die eine Version und mal an die andere Version des Leitfadens. Auf diese Weise lernt die Gruppe dazu und kann vielfältige Eindrücke sammeln, die für die Weiterentwicklung des Leitfadens wertvoll sind. Mit der Zeit wird sich dann herausstellen, welcher Versionsstrang in der Praxis besser funktioniert und häufiger angewendet werden sollte.

## Ich habe keine Lust mich hier anzumelden und mich mit Versionskontrolle zu befassen. Kann ich auch ohne das ganze Git-Zeug mitmachen?

Ja. Es gibt natürlich auch andere Möglichkeiten, seine eigenen Verbesserungsvorschäge oder Leitfaden-Entwürfe einzubringen. Z.B. indem man in der Chat-Gruppe einfach per Nachricht mitteilt, welche Gesprächsregeln man besser fände. Oder indem man ein Word-Dokument in eine Cloud hochlädt und mit der Gruppe teilt. Es wird sich dann sicher jemand finden, der diesen Vorschlag auch hier im Git-Repository als Commit auf einem existierenden oder einem neuen Branch einpflegt.

## Ich will direkt online mitmischen. Was muss ich tun?

Es gibt viele Wege, am Repository mitzuarbeiten. Das hier ist der schnellste Weg:

(Beschrieben ist die Bedienung am Computer. Bei Smartphones könnte die Benutzeroberfläche leicht anders aussehen.)
* Erstelle einen kostenlosen Account auf GitHub.
* Gehe dann auf die Seite des Repositories: (https://github.com/klimagespraeche/leitfaden)
* Mache Dich mit den Dateien vertraut, die im Repository liegen. Die Datei REAMDE.md hat eine besondere Stellung: Sie wird direkt auf der Startseite des Repositories angezeigt.
* Du befindest Dich zunächst auf dem Haupt-Entwicklungspfad 'main' (Siehe **graue Auswahl-Box unter der Überschrift des Repositories**). 'main' ist sowas wie der Stamm des Versionsbaumes. Wir wollen diesen Stamm so wenig wie möglich für die Entwicklung des Leitfadens nutzen. Hier sollten lediglich die fundamentale Dateistruktur und die allgemeingültigen Inhalte von README.md und Fragen+Antworten.md entwickelt werden. Werfe am besten mal einen Blick auf (https://github.com/klimagespraeche/leitfaden/network), um Dir einen Überblick über die bestehenden Branches zu verschaffen. (Auch erreichbar im Menü über den Punkt "Insights")
* Wenn Du Änderungen vornehmen willst, solltest Du sie auf einem separaten Branch durchführen.
  * Falls Du dafür schon einen Branch abgezweigt hast, wähle ihn einfach in der kleinen grauen Auswahlbox unter der Überschrift des Repositories aus.
  * Falls Du noch keinen Branch abgezweigt hast, **klicke auf das Wort "Branches" unter der Überschrift des Repositories**. Auf der dann erscheinenden Seite klickst Du auf den **grünen Button "New branch"**. Wähle einen sinnvollen Namen, z.B. deinen Vornamen. Das Repository wird nun automatisch auf deinen Branch umgestellt. Die Inhalte sind erstmal identisch mit dem was Du vor dem Abzweigen gesehen hast.
* Nun kannst Du einfach die Datei öffnen, die Du verändern willst und dann das **Bleistift-Symbol zum Bearbeiten** klicken.
* Im Bearbeitungs-Modus siehst Du den Inhalt der jeweiligen Datei in einer anderen Form: Formatierungen werden als Text eingegeben. D.h. Man macht z.B. kenntlich, dass eine Zeile eine Überschrift sein soll, indem man sie mit Bindestrichen '-' oder Gleichheitszeichen '=' unterschtreicht. Oder Listen werden mit den Symbolen '*' bzw '1.', '2.', ... angelegt. Diese Schreibweise nennt man _Markdown_. Auf README.md ist eine Übersicht verlinkt, die beschreibt, wie man Formatierungen mit Markdown vornimmt. Wenn Du während der Bearbeitung eine Vorschau Deiner Formatierungen sehen willst, kannst Du oben zwischen den **Buttons "Preview" und "Edit"** hin und her schalten.
* Wenn Deine Bearbeitung fertig ist, klicke oben rechts auf den **Button "Commit changes ..."** und gibt einen kurzen Einzeiler ein, der beschreibt, was Du verändert hast. (_commit message_) Das Feld 'Extended description' kannst Du leer lassen. Stelle in der angezeigten Box nochmal kurz sicher, dass der Commit auf den von Dir angelegten branch erfolgt ('Commit directly to the ... branch') und klicke auf 'Commit changes'.

Das war's schon. :smiley: Du hast soeben eine neue Version (Commit) auf einem Entwicklungszweig (Branch) erstellt!

Unter (https://github.com/klimagespraeche/leitfaden/network) bzw. wenn Du unter dem grünen Button '<> Code' auf 'Commits' klickst, taucht Deine Änderung jetzt als zusätzlicher Punkt auf.

Fortgeschrittenere Aktionen wie Merges kommen etwas seltener vor. Eine entsprechende Beschreibung werden wir hier einfügen, sobald wir sehen, dass mehrere Personen aktiv am Leitfaden mitarbeiten.

---
* zurück zur [Startseite](README.md)
