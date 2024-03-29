---
title: XmlFormatOptions
second_title: GroupDocs.Editor för .NET API-referens
description: Innehåller alternativ som gör det möjligt att justera formateringen av XMLdokument när det representeras som HTML
type: docs
weight: 1280
url: /sv/net/groupdocs.editor.options/xmlformatoptions/
---
## XmlFormatOptions class

Innehåller alternativ som gör det möjligt att justera formateringen av XML-dokument, när det representeras som HTML

```csharp
public sealed class XmlFormatOptions : IEditOptions
```

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [EachAttributeFromNewline](../../groupdocs.editor.options/xmlformatoptions/eachattributefromnewline) { get; set; } | När det är aktiverat kommer varje par av attribut-värde i varje XML-element att placeras på en ny rad. Som standard är false (inaktiverad) — alla attribut-värde-par placeras på en enda rad. |
| [IsDefault](../../groupdocs.editor.options/xmlformatoptions/isdefault) { get; } | Anger om denna instans av XML-formateringsalternativ har ett standardvärde |
| [LeafTextNodesOnNewline](../../groupdocs.editor.options/xmlformatoptions/leaftextnodesonnewline) { get; set; } | När det är aktiverat kommer bladtextnoder (textinnehåll i XML-element, som inte har några underordnade) att renderas på en ny rad med större vänster indrag. Som standard är false (inaktiverad) — bladtextnoder placeras på samma rad som deras föräldrar, utan ny strecksats. |
| [LeftIndent](../../groupdocs.editor.options/xmlformatoptions/leftindent) { get; set; } | Tillåter att ange en offset för den vänstra indragen på varje ny rad. Kan inte vara ett enhetslöst värde som inte är noll. Som standard är 10pt |

### Se även

* interface [IEditOptions](../ieditoptions)
* namnutrymme [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* hopsättning [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
