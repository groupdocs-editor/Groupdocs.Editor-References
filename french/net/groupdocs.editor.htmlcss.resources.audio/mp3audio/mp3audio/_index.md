---
title: "Mp3Audio"
second_title: "Référence API GroupDocs.Editor pour .NET"
description: "Crée une nouvelle classe Mp3Audio à partir du contenu MP3 représenté sous forme de flux d'octets et avec le nom spécifié"
type: docs
weight: 10
url: /fr/net/groupdocs.editor.htmlcss.resources.audio/mp3audio/mp3audio/
---
## Mp3Audio constructor

Crée une nouvelle classe Mp3Audio à partir du contenu MP3, représenté sous forme de flux d'octets, et avec le nom spécifié

```csharp
public Mp3Audio(string name, Stream binaryContent)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| nom | String | Nom du contenu MP3. Ne peut pas être null, vide ou composé d'espaces. |
| binaryContent | Stream | Contenu sous forme de flux d'octets. La lecture commence à partir de la position d'origine. Ne peut pas être nul. Doit être lisible et recherchable. Si cette instance est libérée, ce flux sera également libéré. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException |  |

### Voir aussi

* class [Mp3Audio](../../mp3audio)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Audio](../../../groupdocs.editor.htmlcss.resources.audio)
* assembly [GroupDocs.Editor](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.editor.dll -->
