---
title: "op_Explicit"
second_title: "Référence API GroupDocs.Editor pour .NET"
description: "Convertit le Byte 8 bits octet spécifié en le TextDecorationLineTypegroupdocs.editor.htmlcss.css.properties/textdecorationlinetype correspondant, lève une exception si le cast est invalide"
type: docs
weight: 180
url: /fr/net/groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/op_explicit/
---
## explicit operator {#op_explicit_1}

Convertit le Byte (octet 8 bits) spécifié en le [`TextDecorationLineType`](../../textdecorationlinetype) correspondant, lève une exception si le cast est invalide

```csharp
public static explicit operator TextDecorationLineType(byte octet)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| octet | Octet | Un octet de 8 bits (champ de bits), où les 5 bits de tête sont à zéro, tandis que les 3 derniers indiquent les indicateurs |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentOutOfRangeException | L'*octet* spécifié a une valeur invalide |

### Voir aussi

* struct [TextDecorationLineType](../../textdecorationlinetype)
* namespace [GroupDocs.Editor.HtmlCss.Css.Properties](../../../groupdocs.editor.htmlcss.css.properties)
* assembly [GroupDocs.Editor](../../../)

---

## explicit operator {#op_explicit}

Convertit l'instance [`TextDecorationLineType`](../../textdecorationlinetype) spécifiée en l'octet équivalent (champ de bits 8 bits)

```csharp
public static explicit operator byte(TextDecorationLineType input)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| input | TextDecorationLineType | Instance [`TextDecorationLineType`](../../textdecorationlinetype) à convertir |

### Voir aussi

* struct [TextDecorationLineType](../../textdecorationlinetype)
* namespace [GroupDocs.Editor.HtmlCss.Css.Properties](../../../groupdocs.editor.htmlcss.css.properties)
* assembly [GroupDocs.Editor](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.editor.dll -->
