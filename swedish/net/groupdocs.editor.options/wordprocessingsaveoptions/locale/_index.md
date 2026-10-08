---
title: "Locale"
second_title: "GroupDocs.Editor för .NET API-referens"
description: "Tillåter att ange överskrivning av standardlokalspråk för WordProcessing‑dokumentet som kommer att tillämpas under skapandet. När den inte anges kommer standardvärdet MS Word eller ett annat program att upptäcka eller välja dokumentets lokal enligt sina egna inställningar eller andra faktorer."
type: docs
weight: 40
url: /sv/net/groupdocs.editor.options/wordprocessingsaveoptions/locale/
---
## WordProcessingSaveOptions.Locale property

Tillåter att ange en överskrivning av standardlokal (språk) för WordProcessing-dokumentet, som kommer att tillämpas under dess skapande. När den inte anges (standardvärde) kommer MS Word (eller annat program) att upptäcka (eller välja) dokumentets lokal enligt sina egna inställningar eller andra faktorer.

```csharp
public CultureInfo Locale { get; set; }
```

### Anmärkningar

Detta alternativ tvingar fram den angivna lokalen på all text i dokumentet. Använd det inte om dokumentet innehåller olika textdelar som är skrivna på olika språk.

### Se även

* class [WordProcessingSaveOptions](../../wordprocessingsaveoptions)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

<!-- REDIGERA INTE: genererad av xmldocmd för GroupDocs.editor.dll -->
