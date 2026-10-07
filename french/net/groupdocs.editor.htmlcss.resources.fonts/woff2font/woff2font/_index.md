---
title: "Woff2Font"
second_title: "Référence API GroupDocs.Editor pour .NET"
description: "Crée une nouvelle classe Woff2Font à partir du contenu représenté sous forme de chaîne encodée en base64 et avec le nom spécifié"
type: docs
weight: 10
url: /fr/net/groupdocs.editor.htmlcss.resources.fonts/woff2font/woff2font/
---
## Woff2Font(string, string) {#constructor_1}

Crée une nouvelle classe Woff2Font à partir du contenu, représenté sous forme de chaîne encodée en base64, et avec le nom spécifié

```csharp
public Woff2Font(string name, string contentInBase64)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| nom | String | Nom de la police WOFF2. Ne peut pas être nul, vide ou composé d'espaces. |
| contentInBase64 | String | Contenu sous forme de chaîne encodée en base64. Ne peut pas être nul, vide ou composé d'espaces. Si ce n'est pas un contenu WOFF2, une exception sera levée. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException |  |
| [InvalidImageFormatException](../../../groupdocs.editor.htmlcss.exceptions/invalidimageformatexception) |  |

### Voir aussi

* class [Woff2Font](../../woff2font)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Fonts](../../../groupdocs.editor.htmlcss.resources.fonts)
* assembly [GroupDocs.Editor](../../../)

---

## Woff2Font(string, Stream) {#constructor}

Crée une nouvelle classe Woff2Font à partir du contenu, représenté sous forme de flux d'octets, et avec le nom spécifié

```csharp
public Woff2Font(string name, Stream binaryContent)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| nom | String | Nom de la police WOFF2. Ne peut pas être nul, vide ou composé d'espaces. |
| binaryContent | Stream | Contenu sous forme de flux d'octets. La lecture commence à partir de la position d'origine. Ne peut pas être nul. Doit être lisible et recherchable. Si cette instance est libérée, ce flux sera également libéré. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException |  |
| [InvalidImageFormatException](../../../groupdocs.editor.htmlcss.exceptions/invalidimageformatexception) |  |

### Voir aussi

* class [Woff2Font](../../woff2font)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Fonts](../../../groupdocs.editor.htmlcss.resources.fonts)
* assembly [GroupDocs.Editor](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.editor.dll -->
