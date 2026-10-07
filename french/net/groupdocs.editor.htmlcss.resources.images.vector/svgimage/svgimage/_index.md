---
title: "SvgImage"
second_title: "Référence API GroupDocs.Editor pour .NET"
description: "Crée une nouvelle instance SvgImage à partir d'un contenu représenté sous forme de chaîne habituelle et avec le nom spécifié"
type: docs
weight: 10
url: /fr/net/groupdocs.editor.htmlcss.resources.images.vector/svgimage/svgimage/
---
## SvgImage(string, string) {#constructor_1}

Creates new SvgImage instance from content, represented as usual string, and with specified name

```csharp
public SvgImage(string name, string content)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| nom | String | Nom de l'image SVG. Ne peut pas être nul, vide ou composé d'espaces. |
| contenu | String | Contenu sous forme de chaîne habituelle, qui contient un contenu SVG valide conforme XML. Ne peut pas être nul, vide ou composé d'espaces. Si ce n'est pas un contenu SVG, une exception sera levée. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | Certains paramètres sont invalides |
| [InvalidImageFormatException](../../../groupdocs.editor.htmlcss.exceptions/invalidimageformatexception) | *content* argument contient un contenu SVG invalide |

### Voir aussi

* class [SvgImage](../../svgimage)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Images.Vector](../../../groupdocs.editor.htmlcss.resources.images.vector)
* assembly [GroupDocs.Editor](../../../)

---

## SvgImage(string, Stream) {#constructor}

Creates new SvgImage instance from content, represented as byte stream, and with specified name

```csharp
public SvgImage(string name, Stream binaryContent)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| nom | String | Nom de l'image SVG. Ne peut pas être nul, vide ou composé d'espaces. |
| binaryContent | Stream | Contenu sous forme de flux d'octets. La lecture commence à partir de la position d'origine. Ne peut pas être nul. Doit être lisible et recherchable. Si cette instance est libérée, ce flux sera également libéré. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException |  |
| [InvalidImageFormatException](../../../groupdocs.editor.htmlcss.exceptions/invalidimageformatexception) |  |

### Voir aussi

* class [SvgImage](../../svgimage)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Images.Vector](../../../groupdocs.editor.htmlcss.resources.images.vector)
* assembly [GroupDocs.Editor](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.editor.dll -->
