---
title: "LocaleBi"
second_title: "GroupDocs.Editor för .NET API-referens"
description: "Tillåter att ange överskrivning av lokalspråk för WordProcessing-dokumentet för RTL‑text (höger‑till‑vänster) som kommer att tillämpas under skapandet. När den inte anges kommer standardvärdet MS Word eller ett annat program att upptäcka eller välja dokumentets RTL‑lokal enligt sina egna inställningar eller andra faktorer."
type: docs
weight: 50
url: /sv/net/groupdocs.editor.options/wordprocessingsaveoptions/localebi/
---
## WordProcessingSaveOptions.LocaleBi property

Tillåter att ange en överskrivning av lokal (språk) för WordProcessing-dokumentet för RTL (höger-till-vänster) text, som kommer att tillämpas under dess skapande. När den inte anges (standardvärde) kommer MS Word (eller annat program) att upptäcka (eller välja) dokumentets RTL-lokal enligt sina egna inställningar eller andra faktorer.

```csharp
public CultureInfo LocaleBi { get; set; }
```

### Anmärkningar

Detta alternativ tvingar fram den angivna lokalen på all RTL‑text i dokumentet. Använd det inte om dokumentet innehåller olika textdelar som är skrivna på olika språk.

### Se även

* class [WordProcessingSaveOptions](../../wordprocessingsaveoptions)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

<!-- REDIGERA INTE: genererad av xmldocmd för GroupDocs.editor.dll -->
