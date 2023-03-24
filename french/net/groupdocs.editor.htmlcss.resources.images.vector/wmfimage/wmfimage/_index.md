---
title: WmfImage
second_title: Référence de l'API GroupDocs.Editor pour .NET
description: Crée une nouvelle instance WmfImage à partir du contenu représentée sous forme de chaîne encodée en base64 et avec le nom spécifié
type: docs
weight: 10
url: /fr/net/groupdocs.editor.htmlcss.resources.images.vector/wmfimage/wmfimage/
---
## WmfImage(string, string) {#constructor_1}

Crée une nouvelle instance WmfImage à partir du contenu, représentée sous forme de chaîne encodée en base64 et avec le nom spécifié

```csharp
public WmfImage(string name, string contentInBase64)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| name | String | Nom de l'image WMF. Ne peut pas être nul, vide ou des espaces blancs. |
| contentInBase64 | String | Contenu sous forme de chaîne encodée en base64. Ne peut pas être nul, vide ou des espaces blancs. S'il ne s'agit pas d'un contenu WMF, une exception sera levée. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException |  |
| [InvalidImageFormatException](../../../groupdocs.editor.htmlcss.exceptions/invalidimageformatexception) |  |

### Voir également

* class [WmfImage](../../wmfimage)
* espace de noms [GroupDocs.Editor.HtmlCss.Resources.Images.Vector](../../wmfimage)
* Assemblée [GroupDocs.Editor](../../../)

---

## WmfImage(string, Stream) {#constructor}

Crée une nouvelle instance WmfImage à partir du contenu, représenté sous forme de flux d'octets et avec le nom spécifié

```csharp
public WmfImage(string name, Stream binaryContent)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| name | String | Nom de l'image WMF. Ne peut pas être nul, vide ou des espaces blancs. |
| binaryContent | Stream | Contenu sous forme de flux d'octets. La lecture commence à partir de la position d'origine. Ne peut pas être nulle. Doit être lisible et accessible. Si cette instance est supprimée, ce flux le sera également. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException |  |
| [InvalidImageFormatException](../../../groupdocs.editor.htmlcss.exceptions/invalidimageformatexception) |  |

### Voir également

* class [WmfImage](../../wmfimage)
* espace de noms [GroupDocs.Editor.HtmlCss.Resources.Images.Vector](../../wmfimage)
* Assemblée [GroupDocs.Editor](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->