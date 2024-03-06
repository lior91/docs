---
title: "Erste Schritte"
linkTitle: "Erste Schritte"
type: "docs"
weight: 30
---

### An der IAM - Keycloak WebUI anmelden

Mit Ihren Admin-User [Zugangsdaten](/de/identity-access-management/keycloak/tutorials/retrieve_login_credentials/#anmeldedaten) können Sie sich an der WebUI Ihres *IAM - Keycloak* Instanz anmelden. Die Verbindung ist SSL/TLS gesichert, rufen Sie im Adressenfeld Ihres Internetg-Browsers **https://*<DNS-Name_Ihres_IAM-Keycloak_Servers>*/** auf, z.b.: *https://node-65e84464310368a571551616.ps-xaas.io*

![WebUI](/images/content/04-msl/de/iam_keycloak/web_ui/01_connect_webui.png)

#### WebUI Login

Klicken Sie auf die Schaltfläche *Administration Console* und tragen Sie Ihre Anmeldedaten im Login-Fenster ein.

![WebUI-Login](/images/content/04-msl/de/iam_keycloak/web_ui/02_webui_login01.png)

Sie gelangen zum Master-Realm, hier können sie die weiteren Realms anlegen.

![WebUI-MasreRealm01](static/images/content/04-msl/de/iam_keycloak/web_ui/03_master01.png)

{{% alert title="Wichtig!" %}}
Master Realm wird automatisch angelegt, hier werden **NUR** die weiteren Realms angelegt und verwaltet.
{{% /alert %}}

#### Arbeiten mit Realms

Wir haben für Sie einen ersten Realm angelegt, der genauso heißt wie Ihre Kundenname, z.B. *"kd500986"*. 
Sie gelangen zu diesem Realm wenn Sie auf die Schaltfläche "master" klicken und passenden Realm auswählen (unter dieser Schaltfläche ist auch die Funktion zum Anlegen neuer Realms verfügbar).

![WebUI-ChooseRealm01](static/images/content/04-msl/de/iam_keycloak/web_ui/04_choose_realm01.png)

![Zugangsdaten](/images/content/04-msl/de/iam_keycloak/get_credentials/3-credentials-view.png)