---
title: "EmailFormats"
second_title: "Référence API de GroupDocs.Editor pour Java"
description: "Encapsule tous les formats d'e‑mail."
type: docs
weight: 11
url: /fr/java/com.groupdocs.editor.formats/emailformats/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.formats.abstraction.FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase), [com.groupdocs.editor.formats.abstraction.DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase)
```
public class EmailFormats extends DocumentFormatBase
```

Encapsule tous les formats d’e‑mail. Inclut les types de fichiers suivants :
[Tnef](../../com.groupdocs.editor.formats/emailformats#Tnef),
[Eml](../../com.groupdocs.editor.formats/emailformats#Eml),
[Emlx](../../com.groupdocs.editor.formats/emailformats#Emlx),
[Msg](../../com.groupdocs.editor.formats/emailformats#Msg),
[Html](../../com.groupdocs.editor.formats/emailformats#Html),
[Mhtml](../../com.groupdocs.editor.formats/emailformats#Mhtml).

<br />

*** ** * ** ***

En savoir plus sur le format des e‑mails [ici](../https://docs.fileformat.com/email/).

<br />


## Champs

| Champ | Description |
| --- | --- |
|  | [Tnef](#Tnef) | Transport Neutral Encapsulation Format (TNEF) est un format propriétaire de Microsoft pour encapsuler les pièces jointes d’e‑mail basé sur l’interface de programmation d’applications de messagerie (MAPI). |
|
|  | [Eml](#Eml) | Le format de fichier EML représente les messages électroniques enregistrés à l'aide d'Outlook et d'autres applications pertinentes. |
|
|  | [Emlx](#Emlx) | Le format de fichier EMLX est implémenté et développé par Apple. |
|
|  | [Msg](#Msg) | MSG est un format de fichier utilisé par Microsoft Outlook et Exchange pour stocker des messages électroniques, des contacts, des rendez-vous ou d'autres tâches. |
|
|  | [Html](#Html) | E‑mails formatés en HTML. |
|
|  | [Mhtml](#Mhtml) | MHTML, un acronyme de « MIME encapsulation of aggregate HTML documents ». |
|
|  | [Ics](#Ics) | La spécification Internet Calendaring and Scheduling Core Object (iCalendar) est une norme Internet (RFC 2445) pour l'échange et le déploiement d'événements de calendrier et de planification. |
|
|  | [Vcf](#Vcf) | VCF (Virtual Card Format) ou vCard est un format de fichier numérique pour stocker des informations de contact. |
|
|  | [Pst](#Pst) | Les fichiers avec l'extension .pst représentent les fichiers de stockage personnel Outlook (également appelés Personal Storage Table) qui stockent diverses informations utilisateur. |
|
|  | [Mbox](#Mbox) | Le format de fichier MBox est un terme générique qui représente un conteneur pour une collection de messages électroniques. |
|
|  | [Oft](#Oft) | Les fichiers avec l'extension .oft sont des fichiers modèle créés à l'aide de Microsoft Outlook. |
|
|  | [Ost](#Ost) | Le fichier Offline Storage Table (OST) représente les données de la boîte aux lettres de l'utilisateur en mode hors ligne sur la machine locale après l'enregistrement auprès du serveur Exchange via Microsoft Outlook. |
|
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getAll()](#getAll--) | Obtient une collection énumérable de tous les [EmailFormats](../../com.groupdocs.editor.formats/emailformats). |
|
|  | [fromExtension(String extension)](#fromExtension-java.lang.String-) | Récupère une instance du type spécifié [EmailFormats](../../com.groupdocs.editor.formats/emailformats) qui possède l'extension de fichier spécifiée. |
|
|  | [fromString(String extension)](#fromString-java.lang.String-) | Convertit une chaîne représentant une extension de fichier en un objet [EmailFormats](../../com.groupdocs.editor.formats/emailformats). |
|
### Tnef {#Tnef}
```
public static final EmailFormats Tnef
```


Transport Neutral Encapsulation Format (TNEF) est un format propriétaire de Microsoft pour encapsuler les pièces jointes d’e‑mail basé sur l’interface de programmation d’applications de messagerie (MAPI).
En savoir plus sur ce format de fichier
[here](../https://docs.fileformat.com/email/tnef/)
.


### Eml {#Eml}
```
public static final EmailFormats Eml
```


Le format de fichier EML représente les messages électroniques enregistrés à l'aide d'Outlook et d'autres applications pertinentes.
En savoir plus sur ce format de fichier
[here](../https://docs.fileformat.com/email/eml/)
.


### Emlx {#Emlx}
```
public static final EmailFormats Emlx
```


Le format de fichier EMLX est implémenté et développé par Apple. L'application Apple Mail utilise le format de fichier EMLX pour exporter les e‑mails.
En savoir plus sur ce format de fichier
[here](../https://docs.fileformat.com/email/emlx/)
.


### Msg {#Msg}
```
public static final EmailFormats Msg
```


MSG est un format de fichier utilisé par Microsoft Outlook et Exchange pour stocker des messages électroniques, des contacts, des rendez-vous ou d'autres tâches.
En savoir plus sur ce format de fichier
[here](../https://docs.fileformat.com/email/msg/)
.


### Html {#Html}
```
public static final EmailFormats Html
```


E‑mails formatés en HTML.


### Mhtml {#Mhtml}
```
public static final EmailFormats Mhtml
```


MHTML, un acronyme de « MIME encapsulation of aggregate HTML documents ».


### Ics {#Ics}
```
public static final EmailFormats Ics
```


La spécification Internet Calendaring and Scheduling Core Object (iCalendar) est une norme Internet (RFC 2445) pour l'échange et le déploiement d'événements de calendrier et de planification.
En savoir plus sur ce format de fichier
[here](../https://docs.fileformat.com/email/ics/)
.


### Vcf {#Vcf}
```
public static final EmailFormats Vcf
```


VCF (Virtual Card Format) ou vCard est un format de fichier numérique pour stocker des informations de contact.
En savoir plus sur ce format de fichier
[here](../https://docs.fileformat.com/email/vcf/)
.


### Pst {#Pst}
```
public static final EmailFormats Pst
```


Les fichiers avec l'extension .pst représentent les fichiers de stockage personnel Outlook (également appelés Personal Storage Table) qui stockent diverses informations utilisateur.
En savoir plus sur ce format de fichier
[here](../https://docs.fileformat.com/email/pst/)
.


### Mbox {#Mbox}
```
public static final EmailFormats Mbox
```


Le format de fichier MBox est un terme générique qui représente un conteneur pour une collection de messages électroniques.
En savoir plus sur ce format de fichier
[here](../https://docs.fileformat.com/email/mbox/)
.


### Oft {#Oft}
```
public static final EmailFormats Oft
```


Les fichiers avec l'extension .oft sont des fichiers modèle créés à l'aide de Microsoft Outlook.
En savoir plus sur ce format de fichier
[here](../https://docs.fileformat.com/email/oft/)
.


### Ost {#Ost}
```
public static final EmailFormats Ost
```


Le fichier Offline Storage Table (OST) représente les données de la boîte aux lettres de l'utilisateur en mode hors ligne sur la machine locale après l'enregistrement auprès du serveur Exchange via Microsoft Outlook.
En savoir plus sur ce format de fichier
[here](../https://docs.fileformat.com/email/ost/)
.


### getAll() {#getAll--}
```
public static List<EmailFormats> getAll()
```


Obtient une collection énumérable de tous les [EmailFormats](../../com.groupdocs.editor.formats/emailformats).
Valeur : un IEnumerable{EmailFormats} contenant toutes les instances de [EmailFormats](../../com.groupdocs.editor.formats/emailformats).


**Returns:**
java.util.List<com.groupdocs.editor.formats.EmailFormats>
### fromExtension(String extension) {#fromExtension-java.lang.String-}
```
public static EmailFormats fromExtension(String extension)
```


Récupère une instance du type spécifié [EmailFormats](../../com.groupdocs.editor.formats/emailformats) qui possède l'extension de fichier spécifiée.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | extension | java.lang.String | L'extension de fichier du format du document. |
|

**Returns:**
[EmailFormats](../../com.groupdocs.editor.formats/emailformats) - An instance of the specified type [EmailFormats](../../com.groupdocs.editor.formats/emailformats) with the specified file extension.

### fromString(String extension) {#fromString-java.lang.String-}
```
public static EmailFormats fromString(String extension)
```


Convertit une chaîne représentant une extension de fichier en un objet [EmailFormats](../../com.groupdocs.editor.formats/emailformats).


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | extension | java.lang.String | L'extension de fichier à convertir. Si l'extension contient plusieurs points, la partie après le dernier point est utilisée. |
|

**Returns:**
[EmailFormats](../../com.groupdocs.editor.formats/emailformats) - A [EmailFormats](../../com.groupdocs.editor.formats/emailformats) object corresponding to the specified file extension.

