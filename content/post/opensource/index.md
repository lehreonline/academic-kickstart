---
title: Warum Open Source?
subtitle: Und was das Ganze mit der Freiheit von Wissenschaft und Lehre zu tun hat.
summary: Und was das Ganze mit der Freiheit von Wissenschaft und Lehre zu tun hat.
authors:
- admin
- guido
tags: []
categories: []
date: "2020-03-21T00:00:00Z"
lastMod: "2020-03-21T00:00:00Z"
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# image:
#   caption: ""
#   focal_point: ""

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references 
#   `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
---

Warum sollten gerade öffentliche Bildungseinrichtungen wie Universitäten und Schulen für ihren Online-Lehrbetrieb auf sogenannte Open Source Softwarelösungen anstelle von proprietärer Software wie Zoom oder Google Classroom setzen, selbst wenn letztere oftmals auch kostenlose Produktversionen anbieten? Neben der kostenlosen Anwendung stellt insbesondere der einfache Aufbau von dezentraler (Server-) Infrastruktur, den wir auf dieser Webseite beschreiben, einen wichtigen Vorteil dar. Zunächst gilt es aber zu klären, was wir mit Open Source Lösungen meinen.

## Was ist Open Source?

Der [Open Source Initiative](https://opensource.org/osd) zufolge wird Software als Open Source bezeichnet, wenn deren Quellcode öffentlich zugänglich ist und von Dritten geändert und genutzt werden kann. Bekannte Open Source Projekte sind beispielsweise das Betriebssystem [Linux](https://www.linuxfoundation.org), die Versionsverwaltungssoftware [Git](https://git-scm.com/) oder die Programmiersprache [R](https://www.r-project.org/). Auch das hier vorgestellte [BigBlueButton (BBB)](https://bigbluebutton.org) ist eine frei zugängliche Open Source Software, die für Web-Konferenzen und Fernstudien entwickelt wurde.

## Was sind die Vorteile?

Open Source Software steht sogenannten proprietären Systemen gegenüber, also Software, die auf einen Urheber lizensiert ist. Dies sind in der Regel Unternehmen, die die Lizenzen zur Nutzung der Software an einen Endkunden verkaufen, z.B. an Lehrende, Studierende, Schülerinnen und Schüler, Schulen oder Universitäten. Insbesondere mit Blick auf die Bereitstellung von Unterrichts- und Lehrformaten an Schulen und Universitäten ergeben sich daher drei wesentliche Vorteile einer Open Source Softwarelösung.

Ein erster Vorteil von Open Source Software ist, dass die **Anwendung von der Software kostenlos ist und bleibt**. So können auch langfristig keine Gebühren von Lizenzinhabern erhoben werden. Dies ist anders im Fall von proprietärer Software, deren anfängliche Nutzung zunächst oftmals kostenlos sein mag, für die langfristig aber dennoch immer noch Kosten anfallen können.

Ein zweiter Vorteil von Open Source Software ist, dass es in der Regel eine große Zahl (freiwilliger) Entwickler\*innen gibt, die im Internet im **Austausch miteinander** stehen, um sich **bei Problemen zu helfen**. (z.B. im [Community Support von BBB](https://bigbluebutton.org/support/community/)). Außerdem fallen so nicht nur Fehler in der Software schnell auf (da der Code offen ist), sondern sie lassen sich meist auch schnell lösen. Allerdings steht für Open Source Software normalerweise **kein klassischer technischer Support** auf Abruf zur Verfügung. Hier ist der oder die Anwender\*in von der Community abhängig. Dennoch gibt es viele Unternehmen, die Unterstützung für Open Source Software anbieten. Diese Dienstleistungen erfolgen jedoch gegen Bezahlung, auch wenn die Nutzung der Software auch in diesem Fall weiterhin kostenlos bleibt. Ein Beispiel ist die Firma [Blindside Networks](https://blindsidenetworks.com/services/), die kommerzielle Unterstützung für BigBlueButton anbietet.

Wie jede andere Software benötigt auch Online-Lehrsoftware Rechenkapazitäten (Hardware), auf denen sie laufen kann. Zuhause ist das der eigene Computer, im Internet laufen Programme auf sogenannten Servern, d.h. leistungsstarken Netzwerkrechnern. Ein dritter Vorteil von Open Source Software ist, dass es die fehlenden Lizenzen erlauben, die Software problemlos auf **eigenen Servern** laufenzulassen, sodass eine **dezentrale Struktur** aufgebaut werden kann (wie genau erklären wir [hier](../bbb)).  Auf diese Weise bleibt die Nutzung unabhängig von der (Über-) Lastung von zentralen (Server-) Strukturen, wie sie beispielsweise auftreten kann, wenn zu viele Nutzer\*innen gleichzeitig eine Software über die gleichen Server nutzen wollen. Gerade in Zeiten, in denen viele Bildungseinrichtungen (weltweit) auf Online-Lehrformate umstellen, ist dies kein unwahrscheinliches Szenario.  


## Ist die Anwendung Open Source Lösungen komplett kostenlos?

Jein. Die Nutzung von Open Source Software selbst ist wie bereits erwähnt kostenlos. Dies gilt auch für die hier vorgestellte Lösung für Online-Lehrformate, die Nutzung von BigBlueButton. 

Allerdings wissen wir nicht erst durch Robert A. Heinlein, dass sinngemäß "nichts umsonst ist" (**"there ain’t no such thing as a free lunch"**). Denn selbst wenn die **Nutzung der Software kostenlos** ist, werden **Rechnerstrukturen (Server)** benötigt, auf denen sie laufen kann. Und die Bereitstellung dieser **Infrastruktur kostet Geld**. 

Hier gibt es nun verschiedene Möglichkeiten, wie und von wem diese Infrastruktur bereitgestellt (und letztendlich bezahlt) werden kann. 

1. Selbst wenn proprietäre Softwarelösungen, wie Google Classroom oder Zoom, teilweise kostenlos und werbefrei sind, so ist es letztendlich dennoch Ziel der Unternehmen, durch die Nutzung Geld zu verdienen, denn auch sie müssen für die Serverinfrastruktur zahlen. Eine Möglichkeit besteht darin, Informationen aus dem Nutzerverhalten zu erhalten und für Werbemittel zu nutzen. Beispielsweise stand Google bereits in der Kritik, Nutzerdaten auszuspionieren, auch wenn dies [mitterweile eingestellt worden zu sein scheint](https://techcrunch.com/2014/04/30/google-stops-mining-education-gmail-and-google-apps-accounts-for-ad-targeting/)). Auch empfiehlt der Datenschutzbeauftragte von Rheinland-Pfalz für die Nutzung von Google Classroom u.a. aus diesen Gründen [ausschließlich anonyme/pseudonyme Google-Accounts](https://www.datenschutz.rlp.de/fileadmin/lfdi/Dokumente/Orientierungshilfen/anforderungen-google-classroom.pdf) zu verwenden. Inwieweit das in der Praxis umgesetzt werden würde, darf angezweifelt werden. Ähnliches gilt für Zoom, die vielleicht bekannteste Online-Conferencing Software. Sie erlaubt es nicht nur dem oder der Administrator\*in einer Online-Sitzung zu [verfolgen, wie sich andere Teilnehmer\*innen verhalten](https://support.zoom.us/hc/en-us/articles/115000538083-Attendee-attention-tracking), sondern das [Unternehmen selbst sammelt ebenfalls Daten](https://zoom.us/privacy), wie Name und Adresse, aber auch Kreditkarteninformation und Facebook-Profil. Was genau Zoom mit diesen Informationen macht, bleibt [unklar](https://www.inputmag.com/tech/zooms-attention-tracking-is-ripe-for-misuse-abuse).  Eine alternative Einnahmequelle für Unternehmen ist die Erhebung von Lizenzgebühren für größere Nutzerzahlen oder die Kosten bei einer langfristigen Nutzung, wenn ein Umstieg auf Open Source aufgrund von Pfadabhängigkeiten für die Bildungseinrichtungen mit großem Aufwand verbunden ist. Denn die Lizenz für die Nutzung liegt zu jedem Zeitpunkt beim Urheber(-unternehmen). Dies erscheint uns **weder kurzfristig noch langfristig eine überzeugende Lösung** für die Bereitstellung von Bildung. 
2. Wesentlich besser, wenn auch nicht ideal, ist im Vergleich die Nutzung von Open Source Programmen, die darüber hinaus kostenlos Serverkapazitäten bereitstellen. Ein gutes Beispiel hierfür ist [Jitsi Meet](https://meet.jit.si/). Solche Lösungen stellen eine relativ einfache und schnelle Möglichkeit dar, Lehre online anzubieten, wie wir [hier](../jitsi) erläutern. Doch auch wenn keine Daten gespeichert werden oder Benutzerkonten angelegt werden müssen, ist es für eine stabil laufende und langfristige Lösung notwendig, eigene Serverkapazitäten bereitzustellen, um unabhängig von anderem Nutzerverhalten und damit überlasteten Servern zu bleiben.  
3. Damit kommen wir zur dritten und von uns bevorzugten Möglichkeit, nämlich **Open Source Software auf eigenen Server laufen zu lassen**. Die Server sind im Idealfall bereits an Universitäten und Schulen vorhanden oder können von Drittanbietern kostengünstig beschaffen werden. Anders als bei Software-Lizenzgebühren sind Kostenstrukturen- und entwicklungen jedoch besser absehbar. 

Unserer Meinung nach ist es letztendlich Aufgabe von Universitäten, Schulen, bzw. den Bildungsministerien für diese (Server-) Infrastruktur zu zahlen. Denn für die Präsenzlehre stellt die **öffentliche Hand** ebenfalls Klassenzimmer, Seminarräume und Vorlesungssäle bereit --- Infrastruktur, die nicht kostenlos ist. Und es sind bzw. sollten **keine Unternehmen** sein, die Räume für Bildung im Gegenzug für Werbefläche und der Beobachtung von (Konsumenten-) Verhalten zur Verfügung stellen --- auch um die **Freiheit von Wissenschaft und Lehre** zu wahren. Das Gleiche sollte also auch für Online-Lehrformate gelten. Ebenfalls kann es nicht Aufgabe von Lehrpersonen sein, für diese Infrastruktur aus eigener Tasche zu zahlen. So findet Präsenzlehre ebenfalls nicht in privaten Räumen statt. Und als Bildungseinrichtung darauf zu setzen, dass es immer ausreichend Serverkapazitäten für kostenlose Open Source Anwendungen gibt, ist analog einer Strategie, die darauf setzt, mit der Klasse, dem Seminar oder der ganzen Vorlesung in die Nachbaruni oder Nachbarschule zu gehen und zu hoffen, dass dort schon noch ein Raum frei sein wird. Aufgrund der relativ geringen Kosten und des geringen Aufwands eigene Serverkapazitäten aufzubauen, sehen wir wenig Gründe, weshalb öffentliche Bildungsträger **Open Source Software auf eigenen Servern**  daher nicht nur selbst laufen lassen können, sondern sogar sollten.