---
title: "LocaleFarEast"
second_title: "GroupDocs.Editor för .NET API-referens"
description: "Tillåter att överskriva lokalspråket för WordProcessing‑dokumentet för östasiatisk text som kommer att tillämpas under skapandet. När den inte anges kommer standardvärdet MS Word eller ett annat program att upptäcka eller välja dokumentets östasiatiska lokal enligt sina egna inställningar eller andra faktorer."
type: docs
weight: 60
url: /sv/net/groupdocs.editor.options/wordprocessingsaveoptions/localefareast/
---
## WordProcessingSaveOptions.LocaleFarEast property

Tillåter att överskriva lokalen (språket) för WordProcessing-dokumentet för östasiatisk text, som kommer att tillämpas under dess skapande. När den inte anges (standardvärde) kommer MS Word (eller annat program) att upptäcka (eller välja) dokumentets östasiatiska lokal enligt sina egna inställningar eller andra faktorer.

```csharp
public CultureInfo LocaleFarEast { get; set; }
```

### Anmärkningar

Detta alternativ tvingar fram den angivna lokalen på all östasiatisk text i dokumentet. Använd det inte om dokumentet innehåller olika textdelar som är skrivna på olika språk.

### Se även

* class [WordProcessingSaveOptions](../../wordprocessingsaveoptions)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

<!-- REDIGERA INTE: genererad av xmldocmd för GroupDocs.editor.dll -->
