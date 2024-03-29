---
title: XpsSaveOptions
second_title: GroupDocs.Editor voor .NET API-referentie
description: Maakt het mogelijk om aangepaste opties te specificeren voor het genereren en opslaan van XPSdocumenten XML Paper Specifications
type: docs
weight: 1310
url: /nl/net/groupdocs.editor.options/xpssaveoptions/
---
## XpsSaveOptions class

Maakt het mogelijk om aangepaste opties te specificeren voor het genereren en opslaan van XPS-documenten (XML Paper Specifications)

```csharp
public sealed class XpsSaveOptions : ISaveOptions
```

## Constructeurs

| Naam | Beschrijving |
| --- | --- |
| [XpsSaveOptions](xpssaveoptions)() | De standaard constructeur. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [OptimizeMemoryUsage](../../groupdocs.editor.options/xpssaveoptions/optimizememoryusage) { get; set; } | Schakelt mechanismen voor geheugenoptimalisatie in tijdens het genereren van documenten vanuit HTML, wat de prestaties verslechtert als kosten van afnemend geheugengebruik. Als u deze optie instelt op true, kan het geheugenverbruik aanzienlijk worden verminderd terwijl grote documenten worden gegenereerd, wat ten koste gaat van een langzamere opslagtijd. Standaard is false (geheugenoptimalisatie is uitgeschakeld omwille van betere prestaties). |

### Opmerkingen

Een XPS-bestand vertegenwoordigt paginalay-outbestanden die zijn gebaseerd op XML-papierspecificaties gemaakt door Microsoft. Het is ontwikkeld als vervanging van het EMF-bestandsformaat en is vergelijkbaar met het PDF-bestandsformaat, maar gebruikt XML in lay-out, uiterlijk en afdrukinformatie van een document.

### Zie ook

* interface [ISaveOptions](../isaveoptions)
* naamruimte [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* montage [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
