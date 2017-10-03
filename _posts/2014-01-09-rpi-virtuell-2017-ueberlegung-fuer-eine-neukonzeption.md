---
ID: 802
post_title: 'rpi-virtuell 2017: Überlegung für eine Neukonzeption'
author: Joachim Happel
post_excerpt: ""
layout: post
permalink: >
  http://blogs.rpi-virtuell.de/joachim-happel/rpi-virtuell-2017-ueberlegung-fuer-eine-neukonzeption/
published: true
post_date: 2014-01-09 10:27:08
tags: [ ]
categories:
  - Entwicklung
  - Online Lernen
  - Technik
---
<p dir="ltr">Gestern trafen sich in Düsseldorf die Leiter des Comenius-Institutes, ein Vertreter des wissenschaftliches Beirates und eine Vertreterin LearningLab aus Duisburg, um gemeinsam mit dem Leitungsteam über die Weiterentwicklung von rpi-virtuell zu diskutieren. Grundlage für die Diskussion war ein erster Zukunftsentwurf aus Sicht des Leitungsteams von rpi-virtuell:<!--more--></p>

<h2 dir="ltr">Online-Lernbegleiter für die kirchliche Bildungsarbeit</h2>
<p dir="ltr">rpi-virtuell wurde bisher als religionspädagogisches Fach-Portal mit einem umfangreichen integrierten Online-Lern-Instrumentarium und einer virtuellen Fachbibliothek konzipiert. Nutzer/innen mussten dieses Portal im Web aufsuchen und nach der Registrierung den Weg durch das virtuelle Institut mit seinen Werkstätten und Angeboten finden.<img alt="" src="https://lh5.googleusercontent.com/wUJMeSEYIQAwjmGFR38TwSfAvaA_dA5KIUrszrAohAdwMSdD2ACyc9FX58dSFxifK6esBDUn-K1vhCi-prNoT1m7ZLEcLbuJoTgJ-3eA5gIqph5KRcq0a1jU-Q" width="602px;" height="63px;" /></p>
<p dir="ltr">Durch die Weiterentwicklung von rpi-virtuell zur Lernmanagementbegleitung (PLE) könnte mittelfristig das bisherige Lernmanagementsystems (LMS) entfallen bzw. durch andere Dienste ersetzt werden. Denkbar ist künftig ein minimalistisch erscheinendes Angebot in Form einer Navigationsleiste, das Anwender im Web „stets dabei“ haben, das sie mit hilfreichen Inhalten versorgt und das bei Bedarf nützliche Dienste und Werkzeuge (Apps) anbietet. rpi-virtuell würde technisch gesehen, zum Service-Broker, der für verschiedene Anforderungen und Aufgaben zu verschiedenen Web-Applikationen weiter leitet.</p>
Nur <strong>wenige Basis-Dienste</strong> bräuchte rpi-virtuell selbst bereit stellen. Dazu gehören vor allem der <strong>Materialpool</strong> als Unterstützung für die Unterrichtsentwicklung und ein <strong>Multi-Blogsystem</strong>, über das Nutzer alleine oder mit anderen in einer Gruppe Content (z.B.: für den Materialpool) generieren und Aktivitäten verabreden können. Ergänzend werden über einen Benachrichtigungsdienst (<strong>Aggregator</strong>) relevante religions- und medienpädagogischen Nachrichten aus der Netzcommunity sowie aus den Nutzungs- und Lernaktivitäten bereitgestellt. Nutzende können dabei die Auswahl der Apps selbst konfigurieren, im einfachsten Fall auch Links zu bevorzugten Werkzeugen selbst festlegen. Eine Erweiterung der Basis-Dienste kann erwogen werden, wenn dadurch die Funktion von Kommunikations-, Organistations- oder Lernprozessen verbessert wird. Wenn man diese Gedanken konsequent weiter verfolgt, könnte rpi-virtuell vor allem über die "begleitende" Navigationsleiste unabhängig von der gerade geöffneten Webseite und dem verwendeten Gerät (PC, Smartphone, WebPad oder Whiteboard) überall nutzbar sein. Damit steht dem Nutzer bei seinen eigenen Lehr- und Lerntätigkeit im Web stets ein funktionaler "Lern- und Lehrbegleiter" zur Verfügung. Damit könnte den sich veränderten Lernarrangements Rechnung getragen werden, in denen es nicht mehr darum geht, zu bestimmten Themen Informationen zu finden, sondern in verschiedenen Lernaktivitäten mit unterschiedliche Methoden und Lerntechnologien eigene Kompetenzen zu den anstehend Fragen entwickeln. rpi-virtuell als „Service“ verstanden, würde sich nahtlos als Teil der persönlichen Lernumgebung (PLE) verwenden lassen. <span style="color: #000000; font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif; font-size: 23px; font-weight: bold; line-height: 1.5;">Getrennte Entwicklung und Nutzung von Diensten.</span> rpi-virtuell stellt derzeit für unterschiedliche Zielgruppen und Anforderungen Instrumente  bereit, die sich einzeln und unabhängig voneinander beschreiben lassen.  Kernfunktionalitäten dieser Instrumente finden sich auch in alternativen open-source Produkten oder werden durch manche Dienstleister bereit Verfügung gestellt. In der künftigen Ausrichtung ist zu klären welche Instrumente vermittelt (weitergeleitet zu Drittanbietern)  und welche als Basisfunktionen selbst bereit gestellt (Materialbörse &amp;  Communitykommunikation) für den Grundbetrieb notwendig sind. <img alt="" src="https://lh3.googleusercontent.com/lb-lYrecg9RoXZd-paLfPc0F4TA-jyu6nln9mP45nodMiaTSAt_KUzXP9Nr8C2XQvpFpnikiFfWktPTT9pb4L6qoa5W6-6HmJMvSlgihZDnKFnt3RM1F-3Eucg" width="582px;" height="326px;" />
<p dir="ltr">schwarz = bieten wir derzeit an blau = open source Komponenten, die ähnliche Funktionen erfüllen würden</p>
Üblicherweise werden (erst) bei einer fortlaufenden Nutzung weitere wichtige (vielleicht sogar grundlegende)  Funktionalitäten vermisst. Möglicherweise reichen die erweiterbaren Funktionen eines Multi-Blogsystems aus, um diese Bedarfe zu decken (z.B.: um etwa betimmte Lern- oder Kooperationsvorhaben in einer Gruppe zu unterstützen). Darüberhinaus gibt es viele Lern- und Kooperationswerkzeuge im Web von Drittanbietern, die sich direkt oder über eine Datenschnittstelle integrieren lassen. Die oben beschriebene Navigationsleiste muss dafür individuell oder für Lerngruppen anpassbar sein. Darüberhinaus können <strong>Wünsche</strong> entstehen, die die Qualität und Nutzungstiefe eines Dienstes oder des Gesamtangebotes verbessern könnten. Auch können beispielsweise methodische Konzepte spezielle Technologien und weitere Dienste erfordern. <strong>Zu prüfen</strong> ist, ob die<strong> erforderlichen Funktionalitäten durch bereits existierende open-source Komponenten</strong> realisierbar sind und ohne größeren technischen Entwicklungsaufwand im Rahmen der vorhanden Ressourcen als Installation auf den Servern von rpi-virtuell bereit gestellt oder angeschlossen werden können (Beispiel Etherpad) und wenn nicht, worin das besondere (Alleinstellungsmerkmal) eines zusätzlichen Dienstes / Applikation begründet ist und wie diese zur Qualitäts- und Ressourcensicherung von rpi-virtuell beitragen kann. (Beispiele: von oben nach unten zu lesen)
<div dir="ltr">
<table><colgroup> <col width="*" /> <col width="*" /> <col width="*" /></colgroup>
<tbody>
<tr>
<td>
<p dir="ltr"><strong>Kernkomponenten</strong> (global für alle verfügbar) “Standardprodukt”</p>
</td>
<td>
<p dir="ltr"><strong>buchbare Dienste</strong></p>
<p dir="ltr">(z.B.: für ALPIKA Institute)</p>
</td>
<td>
<p dir="ltr"><strong>vermittelte Komponenten</strong></p>
<p dir="ltr">(frei konfigurierbar)</p>
</td>
</tr>
<tr>
<td>
<p dir="ltr">Materialpool + Themenseiten</p>
<p dir="ltr">+ pers. Auswahllisten</p>
</td>
<td>
<p dir="ltr">spezielle Materialfilter (z.B: nur Materialien eines Institutes oder geobasierter Filter: Lernorte der Region)</p>
</td>
<td>
<p dir="ltr">Nachschlagen:</p>
<p dir="ltr">Geistreich</p>
<p dir="ltr">Bibelserver</p>
<p dir="ltr">Bildersuche</p>
</td>
</tr>
<tr>
<td>
<p dir="ltr">Multi-Blogs</p>
</td>
<td>
<p dir="ltr">Branding und Domain-Mapping, Zertifizierungsmodule,</p>
<p dir="ltr">eigene Bloginstallation,</p>
<p dir="ltr">Begleitportale für Tagungen, Kongresse ...</p>
</td>
<td>
<p dir="ltr">Sich austauschen</p>
<p dir="ltr">Facebookgruppe</p>
<p dir="ltr">google+ Community</p>
<p dir="ltr">Twitterwall</p>
</td>
</tr>
<tr>
<td>
<p dir="ltr">Nachrichten-Aggregator</p>
</td>
<td>
<p dir="ltr">Broadcasting:</p>
<p dir="ltr">Erstellung von Videos, Konzept von Podcasts, Newsletter, Newsfeeds</p>
</td>
<td>
<p dir="ltr">Nachrichtenverarbeitung:</p>
<p dir="ltr">Scoop.It</p>
<p dir="ltr">Feedreader</p>
</td>
</tr>
<tr>
<td>
<p dir="ltr">Sonderformate:</p>
<p dir="ltr">Artothek (religiöse Kunst)</p>
<p dir="ltr">Relilex (Lexkon)</p>
<p dir="ltr">...</p>
</td>
<td>
<p dir="ltr">Projektspezifische Anpassungen / Erweiterungen (z.B. Medienbildungsprojekt: NetzeBilden)</p>
</td>
<td>
<p dir="ltr">Planen und Evaluieren:</p>
<p dir="ltr">Umfragen</p>
<p dir="ltr">Organizer</p>
<p dir="ltr">Etherpad</p>
</td>
</tr>
<tr>
<td></td>
<td>
<p dir="ltr">Kurskonzeption und technische Realisierung</p>
</td>
<td>
<p dir="ltr">Präsentieren:</p>
<p dir="ltr">Bildbearbeitung / Prezi / Cacoo /Youtube / Screener</p>
</td>
</tr>
<tr>
<td></td>
<td>
<p dir="ltr">spez. Lerntechnologien &amp;</p>
<p dir="ltr">eTools und Adaptionen wie:</p>
<p dir="ltr">Portfolio</p>
<p dir="ltr">Xpedition</p>
<p dir="ltr">Metaplan-Digital</p>
<p dir="ltr">geobasierte Darstellungen</p>
</td>
<td>
<p dir="ltr">Arbeiten an Dokumenten:</p>
<p dir="ltr">Google Docs / Microsoft Office Web/  Xchange</p>
<p dir="ltr">ZUM-Wiki</p>
</td>
</tr>
<tr>
<td></td>
<td></td>
<td>
<p dir="ltr">Daten austauschen (Filesharing):</p>
<p dir="ltr">Drive / Dopbox / Owncloud</p>
</td>
</tr>
<tr>
<td></td>
<td></td>
<td>
<p dir="ltr">Kirchliche Dienstleistungen:</p>
<p dir="ltr">Termin Dudle</p>
<p dir="ltr">CidoLi</p>
<p dir="ltr">wwwopac</p>
</td>
</tr>
<tr>
<td></td>
<td></td>
<td>
<p dir="ltr">Lernumgebungen nutzen:</p>
<p dir="ltr">P2PU Kurs</p>
<p dir="ltr">studium digitale</p>
<p dir="ltr">iversity</p>
<p dir="ltr">Moodle - Kurs</p>
<p dir="ltr">Lehrer-Online (lo-net)</p>
</td>
</tr>
<tr>
<td></td>
<td></td>
<td>
<p dir="ltr">Aktuelle Lenangebote integrieren</p>
<p dir="ltr">ZDF - Gods’ Cloud</p>
<p dir="ltr">...</p>
</td>
</tr>
</tbody>
</table>
</div>
Die modulare Konzeption von unabhängigen Diensten und Applikationen impliziert, dass institutionelle Kunden einzelne konfigurierbare Dienste oder Plugins buchen oder entwickeln lassen können. Die unabhängige Betrachtung von Diensten ermöglicht eine ungleichzeitige Entwicklung (siehe auch Umsetzungszenario).
<h2 dir="ltr"></h2>
<h2 dir="ltr">Zusammenführende Kommunikation in verteilten Systemen</h2>
<p dir="ltr">Lernen und Arbeiten in offenen und verteilten Diensten erfordert ein gutes Informationsmanagement und technische Hilfen: sogenannte Aggregatoren.</p>
<p dir="ltr">Das bisherige Konzept geht davon aus, dass Community nicht durch ein gemeinsames Portal definiert, sondern durch gemeinsame Interessen, Aufgaben und Aktivitäten, die sich an verschiedenen Orten im Netz manifestieren. Ziel ist es, diese verteilten Aktivitäten über einen zentralen Dienst zugänglich und teilbar zu machen. Der Funktionsbedarf lässt sich aus der Erfahrung mit offenen online  Kursen ableiten: Wenn Online-Kurse und die Lernaktivitäten der Teilnehmenden so wie ihre Projekte nicht mehr auf einer zentralen Lern-Plattform, sondern auf verteilten Systemen mit unterschiedlichen Diensten durchgeführt werden, erfolgen die Mitteilungen über diese Tätigkeiten ebenfalls auf unterschiedlichen Kanälen und unterschiedlichen Plattformen. Diese Vielfalt an Informationen und Kanälen überfordert viele Nutzer.</p>
<p dir="ltr"><img class="alignleft" style="color: #333333; font-style: normal; line-height: 30px;" alt="" src="https://lh5.googleusercontent.com/Iy-QylyhQx8UV06GfIWGQHnQ8GmypHOW4q5AkFdPMifikyOaumhOYtQ-OhIxvlt8zVyNGrViEknICosXNzzJ-xW8iHCC1O-lt7MooLo8XDWJPyljmTz7a2tESA" width="538px;" height="410px;" />Zur Organisation und Strukturierung von Informationen bedarf es deshalb technischer Instrumente, die die Aggregation der verschiedenen Informationen übernehmen, damit die Nutzer nicht fortwährend alle Portale und Dienste auf Aktualisierungen überprüfen müssen.</p>
<p dir="ltr">Ein solcher frei konfigurierbarer Aggregator, der einen individuellen Informationsfilter und für die Weiterarbeit Strukturierungs- und Kommentierungswerkzeuge für die eingehenden Inhalte anbietet (content curation), dürfte zum wichtigsten Instrument für eine im offenen Netz agierende Community und Lernkultur werden. Dieses Instrument sollte deshalb bei der Entwicklung Priorität haben, da es für den Erfolg des Konzeptes evident ist.</p>

<h2 dir="ltr">Beteiligung der Community am Migrationsprozess</h2>
Die nächsten Schritte hin zu der skizzierten Konzeption sind bereits in der bestehenden Version von rpi-virtuell angelegt und lassen sich in einem organischen Procedere erschließen, zumal eine zentrale technologische Komponente (Multi-Blogsystem) bereits Anwendung findet. So können im laufenden Entwicklungsprozess miteinander die Bedingungen für eine Systemumstellung ermittelt und die Hürden für den nächsten Entwicklungsschritt durch die aktive Beteiligung der Community am Entwicklungsprozess deutlich verringert werden. Das bestehende LMS wird mittelfristig zugunsten eines offenen Systems plattformübergreifender Applikationen und Dienste überführt. Sehr aufwendige Komponenten, wie der Explorer (Filesharing Service), sollen am Ende dieses Prozesses durch andere Verfahren kollaborativen Arbeitens oder Drittanbieter vollständig ersetzt werden. Die Entwicklung vom “Portal” zum “Lernbegleiter“ ist jedoch nicht als Reduktion des Angebotes zu verstehen. Tatsächlich begleitet es die Nutzer in einen sehr viel größeren Raum und hilft dabei die vielen Dienste und Werkzeuge des gesamten Internets wahrzunehmen und deren Nutzen für die eigene Arbeit zu erschließen. Reduziert wird lediglich die Bereitstellung von aufwendigen technischen Diensten zu denen es geeignete Alternativen im Web gibt.
<p dir="ltr">Damit würden die Unterhaltskosten für das laufende Grundsystem erheblich reduziert.</p>
&nbsp;
<h2 dir="ltr">Umsetzungsszenario</h2>
<p dir="ltr">Das folgende Szenario geht von einer Umsetzung des beschriebenen Konzepts mit den genannten Kernkomponenten (Multi-Blogsystem, Materialpool und News-Aggregatoren) aus. Es folgt dem Prinzip der eigenständigen und modularen Entwicklung von implementier-/abbonierbaren Diensten/Applikationen. Der Prozess sieht dabei ein Wechselspiel zwischen der Community und den technischen Realisierungsschritten vor.</p>
&nbsp;
<div dir="ltr">
<table><colgroup> <col width="*" /> <col width="*" /></colgroup>
<tbody>
<tr>
<td>
<p dir="ltr"><strong>Entwicklungsprozess in der Community</strong></p>
</td>
<td>
<p dir="ltr"><strong>Schritte in der technischen Realisierung</strong></p>
</td>
</tr>
<tr>
<td>
<p dir="ltr"><span style="color: #ff0000;">Vorbereitung</span></p>
</td>
<td>
<p dir="ltr"><span style="color: #ff0000;">Start Mitte 2014</span></p>
</td>
</tr>
<tr>
<td>
<p dir="ltr">Sukzessive Verlagerung aller von rpi-virtuell gesteuerten Aktivitäten  von bisherigen Gruppenräumen in das Blogssystem</p>
</td>
<td>
<p dir="ltr">Vereinheitlichung gemischter Ausgaben unter einem System (im Falle von Wordpress geringer Aufwand)</p>
<p dir="ltr">Erstellung einer (systemunabhängigen!) konfigurierbaren “begleitenden Navigationsleiste”</p>
<p dir="ltr">(Prototyp)</p>
</td>
</tr>
<tr>
<td></td>
<td>
<p dir="ltr">vorhergehende Schritte beinhalten: Aktualisierung bezüglich der Gerätekompatibilität (responsive Design)</p>
</td>
</tr>
<tr>
<td>
<p dir="ltr">Online-Lernangebote auf der Basis von Blogs konzeptionieren (wir selbst machen das schon. Beratung, Tutorials usw. müssen das für die Community erstellen)</p>
</td>
<td>
<p dir="ltr">Wo es möglich ist: techn. unterstützte Vereinfachung der Arbeitsvorgänge (Komplexitätsreduktion)</p>
</td>
</tr>
<tr>
<td>
<p dir="ltr">Verlagerung von Community-Aktivitäten in das Blogsystem (Nutzung von Buddypress Plugin)</p>
</td>
<td>
<p dir="ltr">sukzessive Umleitung auf die neuen Maßnamen. Optische und technische Anpassungen und der Navigation.</p>
</td>
</tr>
<tr>
<td>
<p dir="ltr">Aggregation von Inhalten auf der Basis von existierenden Plugins/CMS-Modulen</p>
</td>
<td>
<p dir="ltr">Entwicklung oder Integration eines pers. News-Aggregators (Prototyp)</p>
</td>
</tr>
<tr>
<td>
<p dir="ltr">Testgruppe:</p>
<p dir="ltr">(Zusammengestzt aus verschied. Zielgruppen)</p>
<p dir="ltr">Rückmeldung zu Design, Usability, empfundene Performance …</p>
</td>
<td>
<p dir="ltr">Migration von noch nicht migrierten öffentlichen zugänglichen Inhalten (relilex, reliweb, religionsunterricht.net...) in das CMS  (geringer Aufwand bei  Wordpress )</p>
<p dir="ltr">(Anschl. Evaluation: Perfomance ausreichend?, falls nicht, technische Alternativen klären)</p>
</td>
</tr>
<tr>
<td>
<p dir="ltr"><span style="color: #ff0000;">Meilenstein 1  (Materialpool)</span></p>
</td>
<td>
<p dir="ltr"><span style="color: #ff0000;">Frühjahr 2015</span></p>
</td>
</tr>
<tr>
<td></td>
<td>
<p dir="ltr">Entwicklung von Tests, die die Lauffähigkeit des Systems nach Aktualisierung oder Erweiterung durch Komponenten sicher stellt. (Reduziert die Administrationskosten)</p>
</td>
</tr>
<tr>
<td>
<p dir="ltr">Konstruktion von (interaktiven) Unterrichtsmaterialien (OER) auf der Basis von Blogs (Gelingen ist Voraussetzung für den Verzicht auf bisherigen Dokumenthaltung)</p>
</td>
<td>
<p dir="ltr">Erstellung von Use-Cases für die Softwareanforderung</p>
</td>
</tr>
<tr>
<td>
<p dir="ltr">Überprüfung der Leistung des MP ausgehend von konkreten Anwendung (für den (ko) Unterricht, für Fortbildungen., für die Nutzung in online Kursen ..)</p>
</td>
<td>
<p dir="ltr">Recoding für CMS:  Materialpool + Themenseiten, Themensammlungen, Begriffsfelder  (Herausforderung: inhaltsbezogenes Ranking der Suchergebnisse)</p>
<p dir="ltr">(sehr hoher Aufwand)</p>
</td>
</tr>
<tr>
<td>
<p dir="ltr">Testgruppe: Prüfung der Usability,</p>
<p dir="ltr">Ermittlung des redaktionellen und techn. Pflegeaufwands</p>
</td>
<td>
<p dir="ltr">Nachbesserungen, Optimierungen</p>
</td>
</tr>
<tr>
<td>
<p dir="ltr"><span style="color: #ff0000;">Meilenstein 2 (Explorer)</span></p>
</td>
<td>
<p dir="ltr"><span style="color: #ff0000;">Start Herbst 2015</span></p>
</td>
</tr>
<tr>
<td>
<p dir="ltr">Was fehlt, wenn wir den Explorer abschalten?</p>
</td>
<td>
<p dir="ltr">Erstellung von Use-Cases</p>
<p dir="ltr">Kompensation:</p>
<p dir="ltr">Schnittstellen zu Web-Diensten: oder z.B.: “OwnCloud” (open-source Komponente)</p>
</td>
</tr>
<tr>
<td>
<p dir="ltr">Ermittlung des Bedarfs anhand von</p>
<p dir="ltr">typischen / exempl. Projekten</p>
</td>
<td>
<p dir="ltr">Integration notwendiger Apps  in CMS und Navigation</p>
</td>
</tr>
<tr>
<td>
<p dir="ltr">Entwicklung von Tutorials, Online-Kursen für die versch. Zielgruppen</p>
</td>
<td>
<p dir="ltr">Deklaration der jetzigen Version als auslaufende Version für 6 Monate</p>
</td>
</tr>
<tr>
<td>
<p dir="ltr"><span style="color: #ff0000;">Meilenstein 3 (Release)</span></p>
</td>
<td>
<p dir="ltr"><span style="color: #ff0000;">Frühjar 2016</span></p>
</td>
</tr>
<tr>
<td>
<p dir="ltr">Barcamp</p>
</td>
<td>
<p dir="ltr">Projektierung und Integration wünschenswerter Applikationen und Dienste</p>
<p dir="ltr">(Realisierung erfolgt ggf. später)</p>
</td>
</tr>
<tr>
<td>
<p dir="ltr">StartUp: Auftaktveranstaltungen</p>
<p dir="ltr">Nutzerbefragung</p>
</td>
<td>
<p dir="ltr">“begleitenden Navigationsleiste”</p>
<p dir="ltr">Release</p>
<p dir="ltr">News-Aggregator mit Curator Funktionalität Release</p>
<p dir="ltr">Nacharbeiten: nochmalige Optimierung und Vereinheitlichung der im Entwicklungs- Prozess entstanden Module.</p>
</td>
</tr>
<tr>
<td></td>
<td>
<p dir="ltr"><span style="color: #ff0000;">Anfang 2017:</span></p>
<p dir="ltr">Abschalten aller nicht mehr weiterentwickelten  Funktionen aus der jetzigen Version (Explorer, Wiki, Gruppenforen, Portfolios  ...)</p>
</td>
</tr>
</tbody>
</table>
</div>