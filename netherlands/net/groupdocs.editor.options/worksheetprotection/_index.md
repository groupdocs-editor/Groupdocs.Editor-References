---
title: WorksheetProtection
second_title: GroupDocs.Editor voor .NET API-referentie
description: Bevat opties voor werkbladbeveiliging waarmee een werkblad in het uitgevoerde spreadsheetdocument kan worden beschermd tegen wijziging van het opgegeven type met een opgegeven wachtwoord.
type: docs
weight: 1250
url: /nl/net/groupdocs.editor.options/worksheetprotection/
---
## WorksheetProtection class

Bevat opties voor werkbladbeveiliging, waarmee een werkblad in het uitgevoerde spreadsheetdocument kan worden beschermd tegen wijziging van het opgegeven type met een opgegeven wachtwoord.

```csharp
public sealed class WorksheetProtection
```

## Constructeurs

| Naam | Beschrijving |
| --- | --- |
| [WorksheetProtection](worksheetprotection#constructor)() | Maakt een nieuwe instantie aan met standaardparameters. Indien niet gewijzigd en doorgegeven aan SpreadsheetSaveOptions, wordt geen werkbladbeveiliging toegepast |
| [WorksheetProtection](worksheetprotection#constructor_1)(WorksheetProtectionType, string) | Creëert een nieuwe instantie met gespecificeerd werkbladbeveiligingstype en wachtwoord |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [Password](../../groupdocs.editor.options/worksheetprotection/password) { get; set; } | Wachtwoord, dat wordt gebruikt om een werkblad te beveiligen. Als NULL of lege tekenreeks, wordt de bescherming niet toegepast. |
| [ProtectionType](../../groupdocs.editor.options/worksheetprotection/protectiontype) { get; set; } | Maakt het mogelijk om een type werkbladbeveiliging te specificeren. Standaard is 'Geen' - bescherming wordt niet toegepast. |

### Opmerkingen

De meeste spreadsheetformaten zoals XLSX maken het mogelijk om een werkblad te beschermen tegen bewerking met een wachtwoord. Deze klasse maakt het mogelijk om dergelijke bescherming in te schakelen en de opties ervan te specificeren.

### Zie ook

* naamruimte [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* montage [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->