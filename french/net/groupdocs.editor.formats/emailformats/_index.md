---
title: EmailFormats
second_title: Référence de l'API GroupDocs.Editor pour .NET
description: Encapsule tous les formats demails. Inclut les types de fichiers suivants  Tnef./emailformats/tnef  Eml./emailformats/eml  Emlx./emailformats/emlx  Msg./emailformats/msg  Html./emailformats/html  Mhtml./emailformats/mhtml .
type: docs
weight: 60
url: /fr/net/groupdocs.editor.formats/emailformats/
---
## EmailFormats structure

Encapsule tous les formats d'e-mails. Inclut les types de fichiers suivants : [`Tnef`](./tnef) , [`Eml`](./eml) , [`Emlx`](./emlx) , [`Msg`](./msg) , [`Html`](./html) , [`Mhtml`](./mhtml) .

```csharp
public struct EmailFormats : IDocumentFormat, IEquatable<EmailFormats>
```

## Propriétés

| Nom | La description |
| --- | --- |
| [Extension](../../groupdocs.editor.formats/emailformats/extension) { get; } | Lors de l'implémentation, le type doit renvoyer l'extension de fichier de format (sans point de début). |
| [Mime](../../groupdocs.editor.formats/emailformats/mime) { get; } | Lors de l'implémentation, le type doit renvoyer un code MIME pour le format donné |
| [Name](../../groupdocs.editor.formats/emailformats/name) { get; } | Lors de l'implémentation, le type doit renvoyer le nom de format formel complet |

## Méthodes

| Nom | La description |
| --- | --- |
| static [FromExtension](../../groupdocs.editor.formats/emailformats/fromextension)(string) | Renvoie une instance de[`EmailFormats`](../emailformats) structure, associée à l'extension de nom de fichier spécifiée, ou lève une exception, si l'extension ne peut pas être correctement analysée |
| [Equals](../../groupdocs.editor.formats/emailformats/equals#equals)(EmailFormats) | Détermine si cette instance est égale à l'autre instance de messagerie spécifiée |
| [Equals](../../groupdocs.editor.formats/emailformats/equals#equals_1)(IDocumentFormat) | Détermine si cette instance est égale à l'autre instance IDocumentFormat spécifiée |
| override [Equals](../../groupdocs.editor.formats/emailformats/equals#equals_2)(object) | Détermine si cette instance est égale à l'autre objet spécifié, c'est-à-dire probablement l'Email encadré |
| override [GetHashCode](../../groupdocs.editor.formats/emailformats/gethashcode)() | Renvoie un code de hachage, qui est immuable pour cette instance |
| override [ToString](../../groupdocs.editor.formats/emailformats/tostring)() | Renvoie un nom de format de ce format |
| [operator ==](../../groupdocs.editor.formats/emailformats/op_equality) | Vérifie deux instances de messagerie données sur l'égalité |
| [operator !=](../../groupdocs.editor.formats/emailformats/op_inequality) | Vérifie deux instances de messagerie données sur l'inégalité |

## Des champs

| Nom | La description |
| --- | --- |
| static readonly [Eml](../../groupdocs.editor.formats/emailformats/eml) | Le format de fichier EML représente les messages électroniques enregistrés à l'aide d'Outlook et d'autres applications pertinentes. En savoir plus sur ce format de fichier[ici](https://docs.fileformat.com/email/eml/) . |
| static readonly [Emlx](../../groupdocs.editor.formats/emailformats/emlx) | Le format de fichier EMLX est implémenté et développé par Apple. L'application Apple Mail utilise le format de fichier EMLX pour exporter les e-mails. En savoir plus sur ce format de fichier[ici](https://docs.fileformat.com/email/emlx/) . |
| static readonly [Html](../../groupdocs.editor.formats/emailformats/html) | E-mails au format HTML. |
| static readonly [Ics](../../groupdocs.editor.formats/emailformats/ics) | L'Internet Calendaring and Scheduling Core Object Specification (iCalendar) est une norme Internet (RFC 2445) pour l'échange et le déploiement des événements de calendrier et de planification. En savoir plus sur ce format de fichier[ici](https://docs.fileformat.com/email/ics/) . |
| static readonly [Mbox](../../groupdocs.editor.formats/emailformats/mbox) | Le format de fichier MBox est un terme générique qui représente un conteneur pour la collecte de messages électroniques. En savoir plus sur ce format de fichier[ici](https://docs.fileformat.com/email/mbox/) . |
| static readonly [Mhtml](../../groupdocs.editor.formats/emailformats/mhtml) | MHTML, un initialisme de "encapsulation MIME de documents HTML agrégés" |
| static readonly [Msg](../../groupdocs.editor.formats/emailformats/msg) | MSG est un format de fichier utilisé par Microsoft Outlook et Exchange pour stocker des messages électroniques, des contacts, des rendez-vous ou d'autres tâches. En savoir plus sur ce format de fichier[ici](https://docs.fileformat.com/email/msg/) . |
| static readonly [Oft](../../groupdocs.editor.formats/emailformats/oft) | Les fichiers avec l'extension .oft sont des fichiers modèles créés à l'aide de Microsoft Outlook. En savoir plus sur ce format de fichier[ici](https://docs.fileformat.com/email/oft/) . |
| static readonly [Ost](../../groupdocs.editor.formats/emailformats/ost) | Le fichier de table de stockage hors ligne (OST) représente les données de la boîte aux lettres de l'utilisateur en mode hors ligne sur l'ordinateur local lors de l'enregistrement auprès d'Exchange Server à l'aide de Microsoft Outlook. En savoir plus sur ce format de fichier[ici](https://docs.fileformat.com/email/ost/) . |
| static readonly [Pst](../../groupdocs.editor.formats/emailformats/pst) | Les fichiers avec l'extension .pst représentent les fichiers de stockage personnels Outlook (également appelés table de stockage personnel) qui stockent diverses informations utilisateur. En savoir plus sur ce format de fichier[ici](https://docs.fileformat.com/email/pst/) . |
| static readonly [Tnef](../../groupdocs.editor.formats/emailformats/tnef) | Transport Neutral Encapsulation Format (TNEF) est une propriété exclusive de Microsoft, permettant d'encapsuler les pièces jointes d'e-mails sur la base de l'interface de programmation d'application de messagerie (MAPI). En savoir plus sur ce format de fichier[ici](https://docs.fileformat.com/email/tnef/) . |
| static readonly [Vcf](../../groupdocs.editor.formats/emailformats/vcf) | VCF (Virtual Card Format) ou vCard est un format de fichier numérique pour stocker les informations de contact. En savoir plus sur ce format de fichier[ici](https://docs.fileformat.com/email/vcf/) . |
| static readonly [All](../../groupdocs.editor.formats/emailformats/all) | Renvoie une classe interne, qui offre des possibilités énumérables sur tous les formats de courrier électronique existants |

## Autres membres

| Nom | La description |
| --- | --- |
| class [AllEnumerable](emailformats.allenumerable) | Implémente l'interface générique IEnumerable, qui permet une possibilité "foreach" pour le type d'email |

### Remarques

En savoir plus sur le format des e-mails[ici](https://docs.fileformat.com/email/) .

### Voir également

* interface [IDocumentFormat](../idocumentformat)
* espace de noms [GroupDocs.Editor.Formats](../../groupdocs.editor.formats)
* Assemblée [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
