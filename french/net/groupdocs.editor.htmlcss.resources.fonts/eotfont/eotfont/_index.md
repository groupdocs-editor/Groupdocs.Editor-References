---
title: "EotFont"
second_title: "Référence API GroupDocs.Editor pour .NET"
description: "Crée une nouvelle classe EotFont à partir du contenu représenté sous forme de chaîne encodée en base64 et avec le nom spécifié"
type: docs
weight: 10
url: /fr/net/groupdocs.editor.htmlcss.resources.fonts/eotfont/eotfont/
---
## EotFont(string, string) {#constructor_1}

Crée une nouvelle classe EotFont à partir du contenu, représenté sous forme de chaîne encodée en base64, et avec le nom spécifié

```csharp
public EotFont(string eotName, string eotContentInBase64)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| eotName | String | Nom de la police EOT. Ne peut pas être nul, vide ou contenir uniquement des espaces. |
| eotContentInBase64 | String | Contenu sous forme de chaîne encodée en base64. Ne peut pas être nul, vide ou contenir uniquement des espaces. Si ce n'est pas un contenu EOT, une exception sera levée. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException |  |
| [InvalidImageFormatException](../../../groupdocs.editor.htmlcss.exceptions/invalidimageformatexception) |  |

### Voir aussi

* class [EotFont](../../eotfont)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Fonts](../../../groupdocs.editor.htmlcss.resources.fonts)
* assembly [GroupDocs.Editor](../../../)

---

## EotFont(string, Stream) {#constructor}

Crée une nouvelle classe EotFont à partir du contenu, représenté sous forme de flux d'octets, et avec le nom spécifié

```csharp
public EotFont(string eotName, Stream eotBinaryContent)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| eotName | String | Nom de la police EOT. Ne peut pas être nul, vide ou contenir uniquement des espaces. |
| eotBinaryContent | Stream | Contenu sous forme de flux d'octets. La lecture commence à partir de la position d'origine. Ne peut pas être nul. Doit être lisible et recherchable. Si cette instance est libérée, ce flux sera également libéré. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException |  |
| [InvalidImageFormatException](../../../groupdocs.editor.htmlcss.exceptions/invalidimageformatexception) |  |

### Voir aussi

* class [EotFont](../../eotfont)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Fonts](../../../groupdocs.editor.htmlcss.resources.fonts)
* assembly [GroupDocs.Editor](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.editor.dll -->
