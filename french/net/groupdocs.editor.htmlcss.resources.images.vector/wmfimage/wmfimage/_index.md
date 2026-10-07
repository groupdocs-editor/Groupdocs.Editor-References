---
title: "WmfImage"
second_title: "Référence API GroupDocs.Editor pour .NET"
description: "Crée une nouvelle instance de WmfImage à partir du contenu représenté sous forme de chaîne encodée en base64 et avec le nom spécifié."
type: docs
weight: 10
url: /fr/net/groupdocs.editor.htmlcss.resources.images.vector/wmfimage/wmfimage/
---
## WmfImage(string, string) {#constructor_1}

Crée une nouvelle instance de WmfImage à partir du contenu, représenté sous forme de chaîne encodée en base64, et avec le nom spécifié

```csharp
public WmfImage(string name, string contentInBase64)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| nom | String | Nom de l'image WMF. Ne peut pas être nul, vide ou composé d'espaces. |
| contentInBase64 | String | Contenu sous forme de chaîne encodée en base64. Ne peut pas être nul, vide ou composé d'espaces. Si ce n'est pas un contenu WMF, une exception sera levée. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException |  |
| [InvalidImageFormatException](../../../groupdocs.editor.htmlcss.exceptions/invalidimageformatexception) |  |

### Voir aussi

* class [WmfImage](../../wmfimage)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Images.Vector](../../../groupdocs.editor.htmlcss.resources.images.vector)
* assembly [GroupDocs.Editor](../../../)

---

## WmfImage(string, Stream) {#constructor}

Crée une nouvelle instance de WmfImage à partir du contenu, représenté sous forme de flux d'octets, et avec le nom spécifié

```csharp
public WmfImage(string name, Stream binaryContent)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| nom | String | Nom de l'image WMF. Ne peut pas être nul, vide ou composé d'espaces. |
| binaryContent | Stream | Contenu sous forme de flux d'octets. La lecture commence à partir de la position d'origine. Ne peut pas être nul. Doit être lisible et recherchable. Si cette instance est libérée, ce flux sera également libéré. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException |  |
| [InvalidImageFormatException](../../../groupdocs.editor.htmlcss.exceptions/invalidimageformatexception) |  |

### Voir aussi

* class [WmfImage](../../wmfimage)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Images.Vector](../../../groupdocs.editor.htmlcss.resources.images.vector)
* assembly [GroupDocs.Editor](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.editor.dll -->
