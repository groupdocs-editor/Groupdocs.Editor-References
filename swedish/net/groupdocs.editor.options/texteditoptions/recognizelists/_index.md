---
title: RecognizeLists
second_title: GroupDocs.Editor för .NET API-referens
description: Gör det möjligt att ange hur numrerade listobjekt ska kännas igen när dokument importeras från vanligt textformat. Standardvärdet är sant.
type: docs
weight: 60
url: /sv/net/groupdocs.editor.options/texteditoptions/recognizelists/
---
## TextEditOptions.RecognizeLists property

Gör det möjligt att ange hur numrerade listobjekt ska kännas igen när dokument importeras från vanligt textformat. Standardvärdet är sant.

```csharp
public bool RecognizeLists { get; set; }
```

### Anmärkningar

Om det här alternativet är inställt på falskt, upptäcker listigenkänningsalgoritmen liststycken när listnummer slutar med antingen punkt-, högerparentes eller punktsymboler (som "•", "*", "-" eller "o"). Om det här alternativet är inställt på sant, används blanksteg också som listnummeravgränsare: listigenkänningsalgoritm för arabisk stilnumrering (1., 1.1.2.) använder både blanksteg och punkt (".") symboler.

### Se även

* class [TextEditOptions](../../texteditoptions)
* namnutrymme [GroupDocs.Editor.Options](../../texteditoptions)
* hopsättning [GroupDocs.Editor](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->