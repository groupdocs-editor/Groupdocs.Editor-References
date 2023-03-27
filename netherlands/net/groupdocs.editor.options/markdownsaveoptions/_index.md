---
title: MarkdownSaveOptions
second_title: GroupDocs.Editor voor .NET API-referentie
description: Maakt het mogelijk om aangepaste opties te specificeren voor het genereren en opslaan van Markdowndocumenten
type: docs
weight: 990
url: /nl/net/groupdocs.editor.options/markdownsaveoptions/
---
## MarkdownSaveOptions class

Maakt het mogelijk om aangepaste opties te specificeren voor het genereren en opslaan van Markdown-documenten

```csharp
public sealed class MarkdownSaveOptions : ISaveOptions
```

## Constructeurs

| Naam | Beschrijving |
| --- | --- |
| [MarkdownSaveOptions](markdownsaveoptions)() | De standaard constructeur. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [ExportImagesAsBase64](../../groupdocs.editor.options/markdownsaveoptions/exportimagesasbase64) { get; set; } | Geeft aan of afbeeldingen in Base64-indeling worden opgeslagen in het uitvoerbestand. Standaard is`vals` . |
| [ImagesFolder](../../groupdocs.editor.options/markdownsaveoptions/imagesfolder) { get; set; } | Specificeert de fysieke map waarin afbeeldingen worden opgeslagen bij het exporteren van een document naar de Markdown-indeling. Standaard is null. |
| [OptimizeMemoryUsage](../../groupdocs.editor.options/markdownsaveoptions/optimizememoryusage) { get; set; } | Schakelt mechanismen voor geheugenoptimalisatie in tijdens het genereren van documenten vanuit HTML, waardoor de prestaties afnemen omdat het geheugengebruik afneemt. Deze optie instellen op`WAAR`kan het geheugenverbruik aanzienlijk verminderen terwijl grote documenten worden gegenereerd ten koste van een langzamere besparingstijd. Standaard is`vals` (geheugenoptimalisatie is uitgeschakeld omwille van betere prestaties). |
| [TableContentAlignment](../../groupdocs.editor.options/markdownsaveoptions/tablecontentalignment) { get; set; } | Toestaan geeft aan hoe inhoud in tabellen moet worden uitgelijnd bij het exporteren naar de Markdown-indeling. De standaardwaarde isAuto . |

### Opmerkingen

De klasse MarkdownSaveOptions moet door de gebruiker worden toegepast wanneer er een instantie van de klasse EditableDocument is, die een bewerkte documentinhoud bevat, en het is vereist om deze inhoud op te slaan in het nieuwe document met de Markdown-indeling.

### Zie ook

* interface [ISaveOptions](../isaveoptions)
* naamruimte [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* montage [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->