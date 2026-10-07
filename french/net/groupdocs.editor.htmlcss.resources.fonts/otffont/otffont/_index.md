---
title: "OtfFont"
second_title: "Référence API GroupDocs.Editor pour .NET"
description: "Crée une nouvelle classe OtfFont à partir du contenu représenté sous forme de chaîne encodée en base64 et avec le nom spécifié"
type: docs
weight: 10
url: /fr/net/groupdocs.editor.htmlcss.resources.fonts/otffont/otffont/
---
## OtfFont(string, string) {#constructor_1}

Crée une nouvelle classe OtfFont à partir du contenu, représenté sous forme de chaîne codée en base64, et avec le nom spécifié

```csharp
public OtfFont(string name, string contentInBase64)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| nom | String | Nom de la police OTF. Ne peut pas être nul, vide ou contenir uniquement des espaces. |
| contentInBase64 | String | Contenu sous forme de chaîne encodée en base64. Ne peut pas être nul, vide ou contenir uniquement des espaces. Si ce n'est pas un contenu OTF, une exception sera levée. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException |  |
| [InvalidImageFormatException](../../../groupdocs.editor.htmlcss.exceptions/invalidimageformatexception) |  |

### Voir aussi

* class [OtfFont](../../otffont)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Fonts](../../../groupdocs.editor.htmlcss.resources.fonts)
* assembly [GroupDocs.Editor](../../../)

---

## OtfFont(string, Stream) {#constructor}

Crée une nouvelle classe OtfFont à partir du contenu, représenté sous forme de flux d'octets, et avec le nom spécifié

```csharp
public OtfFont(string name, Stream binaryContent)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| nom | String | Nom de la police OTF. Ne peut pas être nul, vide ou contenir uniquement des espaces. |
| binaryContent | Stream | Contenu sous forme de flux d'octets. La lecture commence à partir de la position d'origine. Ne peut pas être nul. Doit être lisible et recherchable. Si cette instance est libérée, ce flux sera également libéré. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException |  |
| [InvalidImageFormatException](../../../groupdocs.editor.htmlcss.exceptions/invalidimageformatexception) |  |

### Voir aussi

* class [OtfFont](../../otffont)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Fonts](../../../groupdocs.editor.htmlcss.resources.fonts)
* assembly [GroupDocs.Editor](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.editor.dll -->
