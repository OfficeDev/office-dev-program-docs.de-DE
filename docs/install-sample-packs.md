---
title: Verwenden von Beispieldatenpaketen mit Ihrem Abonnement für das Microsoft 365-Entwicklerprogramm
description: Hier erfahren Sie, wie Sie Beispieldatenpakete in Ihrem Entwicklerabonnement für einen schnellen Einstieg in Ihre Sandboxumgebung installieren.
localization_priority: Priority
ms.openlocfilehash: 3802c1c1e02c7be9ccb322561189ee0d085e8ce0
ms.sourcegitcommit: 3d50606496bd0bdbbcf892d2d18de6343a44c576
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 04/19/2021
ms.locfileid: "51890148"
---
# <a name="use-sample-data-packs-with-your-microsoft-365-developer-program-subscription"></a>Verwenden von Beispieldatenpaketen mit Ihrem Abonnement für das Microsoft 365-Entwicklerprogramm

Sie können Beispieldatenpakete in Ihrem Abonnement für das Microsoft 365-Entwicklerprogramm installieren. Mit Beispieldatenpaketen sparen Sie Zeit, indem automatisch Daten und Inhalte installiert werden, die Sie zum Erstellen und Testen Ihrer Lösungen benötigen. Dies umfasst Beispielbenutzer, Metadaten und Fotos, um eine kleine Unternehmensumgebung zu simulieren. Die Beispieldaten lassen sich schnell installieren, sodass Sie sich auf ihre Lösungen konzentrieren können, statt Zeit für die Erstellung von Beispieldaten aufzuwenden.

Beispieldatenpakete finden Sie im [Dashboard des Microsoft 365-Entwicklerprogramms](https://developer.microsoft.com/office/profile) am unteren Rand der Kachel für Ihr Abonnement.

![Screenshot der Kachel für Ihr Abonnement auf der Dashboardseite](images/sample-data-pack-ux-tile-users-beginning.PNG)

Die folgenden Beispieldatenpakete sind zurzeit verfügbar:

- Benutzer: Installiert 16 Beispielbenutzer mit Lizenzen, Postfächern und Metadaten, einschließlich Namen und Fotos für jeden Benutzer. Mit Microsoft Graph-APIs können Sie auf folgende Weise mit Benutzerbeispieldaten arbeiten:
  - Bestimmte Benutzerdetails abrufen
  - Benutzer aktualisieren
  - Mitarbeiter abrufen
  - Organigramm vorbereiten  
  - Benutzer nach Abteilung abrufen

- E-Mails und Ereignisse: Fügt Outlook E-Mail-Unterhaltungen und Kalenderereignisse für jeden der 16 Beispielbenutzer hinzu. Mit Microsoft Graph-APIs können Sie auf folgende Weise mit Mail- und Ereignisbeispieldaten arbeiten:
  - E-Mails nach Benutzer abrufen
  - E-Mails nach Datum gefiltert abrufen
  - Bevorstehende Ereignisse abrufen
  - Bevorstehende Ereignisse aktualisieren/löschen

> [!NOTE]
> Sie müssen das Beispieldatenpaket "Benutzer" installieren, bevor Sie "E-Mails und Ereignisse" installieren.

## <a name="what-do-the-sample-data-packs-add-to-my-subscription"></a>Welche Elemente werden durch die Beispieldatenpakete zu meinem Abonnement hinzugefügt?

Das Beispieldatenpaket "Benutzer" erstellt in Ihrem Abonnement 16 Beispielbenutzer, einschließlich der Lizenzen sowie Postfächer, Namen, Metadaten und Fotos für jeden Benutzer.

Das Beispieldatenpaket "E-Mails und Ereignisse" fügt Outlook E-Mail-Unterhaltungen und Kalenderereignisse für jeden der 16 installierten Benutzer hinzu.

## <a name="how-do-i-install-the-users-sample-data-pack"></a>Wie installiere ich das Beispieldatenpaket "Benutzer"?

Bevor Sie das Beispieldatenpaket "Benutzer" installieren, stellen Sie sicher, dass Sie über ein Microsoft 365 Developer-Abonnement verfügen, und weisen Sie sich selbst eine Administratorlizenz zu.

> [!NOTE]
> Stellen Sie sicher, dass in Ihrem Abonnement 16 Benutzer verfügbar sind. Ihr Abonnement umfasst 25 Benutzer. Wenn Sie bereits mehr als 10 Benutzer konfiguriert haben, entfernen Sie zuerst einige Benutzer, damit die Installation erfolgreich durchgeführt werden kann.

So installieren Sie das Beispieldatenpaket "Benutzer":

1. Aktivieren Sie am unteren Rand der Kachel für Ihr Abonnement das Kontrollkästchen **Benutzer**.
2. Kopieren Sie Ihre Administrator-ID. Sie benötigen diese, um sich bei Ihrem Abonnement anzumelden.
3. Geben Sie Ihre Administrator-ID und das Kennwort auf der Anmeldeseite ein.
4. Stimmen Sie den Berechtigungen als Administrator Ihres Microsoft 365 Developer-Abonnements zu.

![Screenshot mit dem Dialogfeld zum Zustimmen zu den Berechtigungen](images/sample-data-pack-ux-tile-users-consent-with-permissions-combined.PNG)

5. Konfigurieren Sie die Kennwörter für alle Beispielbenutzer. Sie sollten ein gemeinsames Kennwort verwenden, um die Verwaltung ihrer Beispielbenutzer zu erleichtern.

![Screenshot des Dialogfelds zum Hinzufügen eines gemeinsamen Benutzerkennworts](images/sample-data-pack-ux-tile-users-fake-user-password-creation.PNG)

6. Die Daten werden installiert. Die Installation dauert ca. fünf Minuten.

![Screenshot des Installationsvorgangs auf der Dashboardkachel anzeigt](images/sample-data-pack-ux-tile-users-installing-status.PNG)

7. Nach Abschluss der Installation werden Sie per E-Mail benachrichtigt, und das Feld auf der Kachel für Ihr Abonnement wird grün angezeigt. Jetzt können Sie das Beispieldatenpaket "E-Mails und Ereignisse" installieren.

![Screenshot der Dashboardkachel, bereit zur Installation von "E-Mails und-Ereignisse"](images/sample-data-pack-ux-tile-users-installed.PNG)

## <a name="how-do-i-install-the-mail-and-events-sample-data-pack"></a>Wie installiere ich das Beispieldatenpaket "E-Mails und Ereignisse"?

Nachdem Sie das Beispieldatenpaket "Benutzer" installiert haben, können Sie "E-Mails und Ereignisse" installieren.

1. Wählen Sie auf der Kachel für Ihr Abonnement das Feld **E-Mails &amp; Ereignisse** aus.
2. Wählen Sie **Installieren** aus, um mit der Installation zu beginnen.

![Screenshot des Dialogfelds zum Installieren](images/sample-data-pack-ux-tile-mail-and-events-begin-install.PNG)

> [!NOTE]
> Wenn Sie Ihr Abonnement soeben erstellt haben, muss es vollständig bereitgestellt sein, bevor die Installation beginnen kann. Dies kann bis zu einigen Stunden dauern. Nach Beginn der Installation kann es bis zu 20 Minuten dauern, bis der Vorgang abgeschlossen ist.

3. Nach Abschluss der Installation werden Sie per E-Mail benachrichtigt, und das Feld auf der Kachel für Ihr Abonnement wird grün angezeigt.

## <a name="how-do-i-install-the-sharepoint-sample-data-pack"></a>Wie installiere ich das Beispieldatenpaket "SharePoint"?

Das SharePoint-Beispieldatenpaket enthält sieben verschiedene SharePoint-Sitevorlagen, aus denen Sie wählen können, um SharePoint-Lösungen für Zusammenarbeit, Kommunikation, Engagement und Wissensmanagement zu nutzen und zu modellieren.

Dies sind einige der beliebtesten Vorlagen aus dem [SharePoint PnP-Look Book](https://provisioning.sharepointpnp.com/). Heute ist es einfach, Beispiellösungen für schöne, schnelle Sites und Seiten zu erstellen, die auf jedem Gerät oder Bildschirm perfekt dargestellt werden. Lassen Sie sich von diesen Designs inspirieren, oder fügen Sie sie Ihrem Sandkasten-Mandanten hinzu, um mit dem Erstellen Ihrer nächsten Site zu beginnen.

Die Vorlagen können im Rahmen Ihres Abonnements installiert werden. Nachdem Sie eine Vorlage installiert haben, haben Sie die Möglichkeit, die anderen zu installieren. Der Installationsprozess umfasst die folgenden Schritte:

1. Wählen Sie im Dropdownmenü die Vorlage aus, die Sie verwenden möchten.

  ![Screenshot des SharePoint-Bildschirms für die Vorlagenauswahl](images/select-sharepoint-template.jpg)

2. Konfigurieren Sie benutzerdefinierte Optionen für Ihre Sites, oder übernehmen Sie die Standardwerte.
3. Verwenden Sie die Administrator-ID Ihres Sandkasten-Mandanten und das Kennwort für die Authentifizierung und zum Erteilen von Installationsberechtigungen. 

Die Installation wird automatisch durchgeführt.

>**Hinweis:** Die Bereitstellung dieser Sitevorlagen ist nur mit der englischen Version von Office 365 E3- oder Microsoft 365 E5-Entwickler-Abonnements möglich, und alle enthaltenen Inhalte sind ausschließlich in Englisch verfügbar.

## <a name="what-sharepoint-templates-are-available"></a>Welche SharePoint-Vorlagen sind verfügbar?

Das SharePoint-Beispielpaket enthält sieben verschiedene Vorlagen.

### <a name="team-site-with-data"></a>Teamsite mit Daten

Diese Teamsite mit Datenvorlage umfasst mehrere Listen und Dokumentbibliotheken, die automatisch einer SharePoint-Teamsite zugeordnet sind, um Ihnen dabei zu helfen, Lösungen mithilfe von SharePoint-Framework, Power Apps und Microsoft Graph zu entwickeln.

Diese Vorlage umfasst die folgenden Daten:

- Eine Kontaktliste mit voraufgefüllten Kontakten
- Eine mit mehr als 6.000 Elementen aufgefüllte Liste
- Dokumentbibliotheken mit PowerPoint-, Excel-, Word- und OneNote-Beispieldokumenten
- Eine Ereignisliste mit Ankündigungselementen

Diese Vorlage ist in die Benutzer-Beispieldaten integrierbar.

### <a name="work--contoso"></a>Work @ Contoso
Die Vorlage “Work @ Contoso” besteht aus mehreren Sitesammlungen, die alle automatisch der Hubwebsite zugeordnet sind, um zu zeigen, wie alle standardmäßigen Aggregationsfunktionen angewendet werden.

Diese Vorlage enthält folgende Strukturen und Objekte:

- Hauptwebsitesammlungssatz als Hubwebsite
- Zwei Kommunikationswebsites, die der Hubwebsite zugeordnet sind – Vorteile und Charity-Websites
- Eine Gruppenteamwebsite, die der Hub-Website zugeordnet ist – Teamwebsite
- Beispiele für Nachrichtenartikel in den Unterwebsitesammlungen
- Beispiele für Word-, Excel- und PowerPoint-Dateien
- Beispielbildinhalte, die in den Websitesammlungen verwendet werden

Unterwebsitesammlungen verwenden dieselben Beispielvorlagen, die Sie auch separat über diesen Dienst bereitstellen können.

>**Hinweis:** Wenn diese Vorlage auf eine vorhandene Kommunikationswebsite angewendet wird, wird der Inhalt der Willkommensseite der Site überschrieben.

### <a name="leadership-connection-leadership-news-events-engagement"></a>Leadership Connection: Nachrichten, Ereignisse und Engagement zu Führungsqualitäten

Diese Site für Führungskräfte bietet Erkenntnisse zu den Zielen und Prioritäten des Führungsteams, und fördert das Engagement durch Veranstaltungen und Unterhaltungen.

Wenn Sie dieses Design zu Ihrem Mandanten hinzufügen, werden folgende Inhalte erstellt:

- Beispiel für eine Willkommensseite mit Demonstration von Webparts
- Beispiele für News-Artikel, mit deren Hilfe verschiedene moderne Seitendesigns veranschaulicht werden

Diese Vorlage ist in die Benutzer-Beispieldaten integrierbar.

### <a name="the-landing-news-resources-personalized-content"></a>Die Zielsite: Neuigkeiten, Ressourcen, personalisierte Inhalte

Auf dieser Kommunikationswebsite sollen Ihre Mitarbeiter die Neuigkeiten und Ressourcen finden können, die sie benötigten, sowie personalisierte Inhalte, die genau auf sie zugeschnitten sind.

Wenn Sie dieses Design zu Ihrem-Mandanten hinzufügen, wird der folgende Inhalt erstellt:

- Struktur für die Startseite des Portals zu Demonstrationszwecken
- Struktur einer benutzerdefinierten Willkommensseite
- Sechs weitere Beispiele für moderne Seiten und News-Artikel
- Beispiele für Bilder und Office-Dokumente

### <a name="the-perspective-news-video-personalized-content"></a>Die Perspektive: Neuigkeiten, Videos, personalisierte Inhalte

Diese Website soll Neuigkeiten und personalisierte Inhalte bieten und umfasst auch Videos, um das Engagement noch stärker zu fördern.
Wenn Sie dieses Design zu Ihrem-Mandanten hinzufügen, wird der folgende Inhalt erstellt:

- Designs für benutzerdefinierte Willkommensseiten
- Beispiele für Vorlagenseiten für Nachrichtenartikel
- Zwölf Beispiele für News-Artikel

### <a name="new-employee-onboarding-hub-connect-engage-inform"></a>Neuer Hub für das Mitarbeiter-Onboarding: vernetzen, motivieren, informieren

Optimieren und verfeinern Sie das Onboarding neuer Mitarbeiter mit vorgefertigten Vorlagen, die das Pre-Onboarding, das Onboarding auf Unternehmensebene und das Onboarding auf Abteilungsebene abdecken. Diese digitale Lösung bietet vier verschiedene Sitevorlagen mit vorausgefülltem Inhalt, der an die Ziele Ihrer Organisation angepasst werden kann.

Wenn Sie dieses Design zu Ihrem Mandanten hinzufügen, werden folgende Inhalte erstellt:

- Pre-Onboarding-Website, Unternehmens-Onboarding-Website und zwei abteilungsübergreifende Onboarding-Websites
- Benutzerdefinierte und vorausgefüllte Startseiten für jede Website
- Konfigurierte Hub-Website für Unternehmens-Onboarding und zugehörige Websites für Abteilungs-Onboarding
- Checkliste für das erfolgreiche Onboarding neuer Mitarbeiter, die auf SharePoint-Listen basiert
- Beispielinhalte für die Webparts "Personen", "Yammer", "Neuigkeiten" und "Quicklinks"
- Vorgefertigte FAQS für jede Website
- Empfehlungen zur Erstellung von Social Media- und motivierenden Erfahrungen, beispielsweise eines Willkommensvideos mithilfe des YouTube-Webparts auf der Pre-Boarding-Website

### <a name="crisis-communications-announcements-news-resources-communities-and-calls-to-action"></a>Krisenkommunikation: Ankündigungen, Neuigkeiten, Ressourcen, Communities und Calls-to-Action

Sorgen Sie dafür, dass die Menschen in Krisensituationen wie Naturkatastrophen oder Notfällen hinsichtlich der Gesundheit und Sicherheit informiert und engagiert bleiben, und den Blick nach vorne richten. Mit dieser Vorlage wird eine zentrale Ressource für Führungskräfte und Kommunikatoren erstellt, um wichtige Neuigkeiten und Ankündigungen zu veröffentlichen; eine zentrale Informationsquelle, damit alle auf dem neuesten Stand bleiben können, und ein Ort, an dem Personen in der gesamten Organisation miteinander in Kontakt treten können.

Wenn Sie dieses Design zu Ihrem Mandanten hinzufügen, werden folgende Inhalte erstellt:

- Benutzerdefinierte Willkommensseite, die mithilfe eines Webparts erstellt wird
- Vier News-Artikel mit Beispielinhalten

Diese Vorlage ist in die Benutzer-Beispieldaten integrierbar.

## <a name="are-more-sample-data-packs-coming"></a>Werden weitere Beispieldatenpakete folgen?

Ja. Wir erwägen, in Zukunft Beispieldatenpakete für weitere Produkte und Technologien hinzuzufügen, z. B. Microsoft Teams. Wenn Sie Vorschläge für Beispieldatenpakete haben, die Sie sich wünschen würden, [teilen Sie uns diese mit](https://officespdev.uservoice.com/forums/224641-feature-requests-and-feedback?category_id=171306).

## <a name="can-i-install-sample-data-packs-on-my-other-microsoft-365-subscriptions"></a>Kann ich Beispieldatenpakete unter meinen anderen Microsoft 365-Abonnements installieren?

Nein. Diese Beispieldatenpakete sind nur mit dem im Rahmen des Microsoft 365-Entwicklerprogramms bereitgestellten Microsoft 365 Developer-Abonnement kompatibel.

## <a name="how-can-i-see-the-sample-data-in-my-subscription"></a>Wie kann ich die Beispieldaten in meinem Abonnement anzeigen?

Nachdem Sie das Beispieldatenpaket "Benutzer" installiert haben, wechseln Sie zum Anzeigen der hinzugefügten Benutzer in Ihrem Microsoft 365 Developer-Abonnement zum [**Microsoft 365 Admin Center**](https://admin.microsoft.com/). Wählen Sie unter **Benutzer** die Option **Aktive Benutzer** aus. Es wird eine Liste mit 16 Benutzern angezeigt. Sie können einen Benutzer auswählen, um die zugehörigen Metadaten anzuzeigen, z. B. Fotos und Lizenzen.

![Screenshot von 16 Benutzern im Microsoft 365 Admin Center, mit Metadaten für einen ausgewählten Benutzer](images/content-packs-07.PNG)

Wählen Sie nach dem Installieren des Beispielpakets "E-Mail und Ereignisse" zum Anzeigen der Beispieldaten im [**Microsoft 365 Admin Center**](/microsoft-365/admin/admin-overview/about-the-admin-center?view=o365-worldwide) die Option **Alle anzeigen** und dann **Exchange** aus. Wenn Sie im Exchange Admin Center die Option **Empfänger** auswählen, können Sie sehen, dass jedem der 16 Benutzer Postfächer mit E-Mail-Nachrichten und Ereignissen hinzugefügt wurden.
![Screenshot der 16 Benutzer, die zum Exchange Admin Center hinzugefügt wurden](images/content-packs-08.PNG)

## <a name="see-also"></a>Weitere Artikel

- [Einrichten eines Microsoft 365 Developer-Abonnements](microsoft-365-developer-program-get-started.md)
