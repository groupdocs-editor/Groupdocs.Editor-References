---
title: "WorksheetProtection"
second_title: "GroupDocs.Editor för .NET API-referens"
description: "Inkapslar alternativ för skydd av kalkylblad som möjliggör att skydda ett kalkylblad i den genererade Spreadsheet‑dokumentet mot ändringar av angiven typ med ett angivet lösenord."
type: docs
weight: 1250
url: /sv/net/groupdocs.editor.options/worksheetprotection/
---
## WorksheetProtection class

Inkapslar skyddsalternativ för kalkylblad, som möjliggör att skydda ett kalkylblad i det genererade Spreadsheet-dokumentet från ändringar av en specificerad typ med ett angivet lösenord

```csharp
public sealed class WorksheetProtection
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [WorksheetProtection](worksheetprotection#constructor)() | Skapar en ny instans med standardparametrar. Om den inte ändras och skickas till SpreadsheetSaveOptions kommer inget kalkylblads-skydd att tillämpas. |
| [WorksheetProtection](worksheetprotection#constructor_1)(WorksheetProtectionType, string) | Skapar en ny instans med angiven typ av kalkylblads-skydd och lösenord. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Password](../../groupdocs.editor.options/worksheetprotection/password) { get; set; } | Lösenord som används för att skydda ett kalkylblad. Om NULL eller tom sträng kommer skyddet inte att tillämpas. |
| [ProtectionType](../../groupdocs.editor.options/worksheetprotection/protectiontype) { get; set; } | Tillåter att ange en typ av kalkylblads-skydd. Som standard är 'None' – skyddet tillämpas inte. |

### Anmärkningar

De flesta kalkylbladsformat som XLSX tillåter att skydda ett kalkylblad från redigering med lösenord. Denna klass möjliggör att aktivera sådant skydd och specificera dess alternativ.

### Se även

* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- REDIGERA INTE: genererad av xmldocmd för GroupDocs.editor.dll -->
