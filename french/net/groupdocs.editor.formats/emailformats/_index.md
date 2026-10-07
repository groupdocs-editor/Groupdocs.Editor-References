---
title: "EmailFormats"
second_title: "Référence API GroupDocs.Editor pour .NET"
description: "Encapsule tous les formats d'e‑mail. Inclut les types de fichiers suivants Tnef./emailformats/tnef Eml./emailformats/eml Emlx./emailformats/emlx Msg./emailformats/msg Html./emailformats/html Mhtml./emailformats/mhtml."
type: docs
weight: 90
url: /fr/net/groupdocs.editor.formats/emailformats/
---
## EmailFormats class

Encapsule tous les formats d'e‑mail. Inclut les types de fichiers suivants : [`Tnef`](./tnef), [`Eml`](./eml), [`Emlx`](./emlx), [`Msg`](./msg), [`Html`](./html), [`Mhtml`](./mhtml).

```csharp
public class EmailFormats : DocumentFormatBase
```

## Propriétés

| Nom | Description |
| --- | --- |
| [Extension](../../groupdocs.editor.formats.abstraction/documentformatbase/extension) { get; } | Obtient l'extension de fichier du format de document. |
| [FormatFamily](../../groupdocs.editor.formats.abstraction/documentformatbase/formatfamily) { get; } | Obtient la famille de formats à laquelle le format de document appartient. |
| [Id](../../groupdocs.editor.formats.abstraction/formatfamilybase/id) { get; } | Obtient l'identifiant unique de la famille de formats. |
| [Mime](../../groupdocs.editor.formats.abstraction/documentformatbase/mime) { get; } | Obtient le type MIME du format de document. |
| [Name](../../groupdocs.editor.formats.abstraction/formatfamilybase/name) { get; } | Obtient le nom de la famille de formats. |
| static [All](../../groupdocs.editor.formats/emailformats/all) { get; } | Obtient une collection énumérable de tous les [`EmailFormats`](../emailformats). |

## Méthodes

| Nom | Description |
| --- | --- |
| static [FromExtension](../../groupdocs.editor.formats/emailformats/fromextension)(string) | Récupère une instance du type spécifié [`EmailFormats`](../emailformats) qui possède l'extension de fichier spécifiée. |
| [Equals](../../groupdocs.editor.formats.abstraction/formatfamilybase/equals)(FormatFamilyBase) | Détermine si cette instance est égale à l'instance spécifiée [`FormatFamilyBase`](../../groupdocs.editor.formats.abstraction/formatfamilybase). |
| [Equals](../../groupdocs.editor.formats.abstraction/documentformatbase/equals)(IDocumentFormat) | Détermine si cette instance est égale à l'instance spécifiée [`IDocumentFormat`](../../groupdocs.editor.formats.abstraction/idocumentformat). |
| override [Equals](../../groupdocs.editor.formats.abstraction/documentformatbase/equals)(object) | Détermine si cette instance est égale à l'instance spécifiée [`DocumentFormatBase`](../../groupdocs.editor.formats.abstraction/documentformatbase). |
| override [GetHashCode](../../groupdocs.editor.formats.abstraction/documentformatbase/gethashcode)() | Renvoie un code de hachage pour l'objet actuel. |
| override [ToString](../../groupdocs.editor.formats.abstraction/formatfamilybase/tostring)() | Renvoie une chaîne qui représente l'objet actuel. |
| [explicit operator](../../groupdocs.editor.formats/emailformats/op_explicit) | Convertit une chaîne représentant une extension de fichier en un objet [`EmailFormats`](../emailformats). |

## Champs

| Nom | Description |
| --- | --- |
| static readonly [Eml](../../groupdocs.editor.formats/emailformats/eml) | Le format de fichier EML représente les messages électroniques enregistrés à l'aide d'Outlook et d'autres applications pertinentes. En savoir plus sur ce format de fichier [ici](https://docs.fileformat.com/email/eml/). |
| static readonly [Emlx](../../groupdocs.editor.formats/emailformats/emlx) | Le format de fichier EMLX est implémenté et développé par Apple. L'application Apple Mail utilise le format de fichier EMLX pour exporter les e‑mails. En savoir plus sur ce format de fichier [ici](https://docs.fileformat.com/email/emlx/). |
| static readonly [Html](../../groupdocs.editor.formats/emailformats/html) | E‑mails formatés en HTML. |
| static readonly [Ics](../../groupdocs.editor.formats/emailformats/ics) | La spécification Internet Calendaring and Scheduling Core Object (iCalendar) est une norme Internet (RFC 2445) pour l'échange et le déploiement d'événements de calendrier et de planification. En savoir plus sur ce format de fichier [ici](https://docs.fileformat.com/email/ics/). |
| static readonly [Mbox](../../groupdocs.editor.formats/emailformats/mbox) | Le format de fichier MBox est un terme générique qui représente un conteneur pour une collection de messages électroniques. En savoir plus sur ce format de fichier [ici](https://docs.fileformat.com/email/mbox/). |
| static readonly [Mhtml](../../groupdocs.editor.formats/emailformats/mhtml) | MHTML, un acronyme de « MIME encapsulation of aggregate HTML documents ». |
| static readonly [Msg](../../groupdocs.editor.formats/emailformats/msg) | MSG est un format de fichier utilisé par Microsoft Outlook et Exchange pour stocker des messages électroniques, des contacts, des rendez‑vous ou d'autres tâches. En savoir plus sur ce format de fichier [ici](https://docs.fileformat.com/email/msg/). |
| static readonly [Oft](../../groupdocs.editor.formats/emailformats/oft) | Les fichiers avec l'extension .oft sont des fichiers modèle créés à l'aide de Microsoft Outlook. En savoir plus sur ce format de fichier [ici](https://docs.fileformat.com/email/oft/). |
| static readonly [Ost](../../groupdocs.editor.formats/emailformats/ost) | Le fichier Offline Storage Table (OST) représente les données de la boîte aux lettres de l'utilisateur en mode hors ligne sur la machine locale lors de l'enregistrement avec Exchange Server à l'aide de Microsoft Outlook. En savoir plus sur ce format de fichier [ici](https://docs.fileformat.com/email/ost/). |
| static readonly [Pst](../../groupdocs.editor.formats/emailformats/pst) | Les fichiers avec l'extension .pst représentent les Outlook Personal Storage Files (également appelés Personal Storage Table) qui stockent diverses informations utilisateur. En savoir plus sur ce format de fichier [ici](https://docs.fileformat.com/email/pst/). |
| static readonly [Tnef](../../groupdocs.editor.formats/emailformats/tnef) | Le Transport Neutral Encapsulation Format (TNEF) est un format propriétaire de Microsoft pour encapsuler les pièces jointes des e‑mails basé sur le Messaging Application Programming Interface (MAPI). En savoir plus sur ce format de fichier [ici](https://docs.fileformat.com/email/tnef/). |
| static readonly [Vcf](../../groupdocs.editor.formats/emailformats/vcf) | VCF (Virtual Card Format) ou vCard est un format de fichier numérique pour stocker les informations de contact. En savoir plus sur ce format de fichier [ici](https://docs.fileformat.com/email/vcf/). |

### Remarques

En savoir plus sur le format des e‑mails [ici](https://docs.fileformat.com/email/).

### Voir aussi

* class [DocumentFormatBase](../../groupdocs.editor.formats.abstraction/documentformatbase)
* namespace [GroupDocs.Editor.Formats](../../groupdocs.editor.formats)
* assembly [GroupDocs.Editor](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.editor.dll -->
