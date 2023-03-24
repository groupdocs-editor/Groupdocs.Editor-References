---
title: WordProcessingSaveOptions
second_title: GroupDocs.Editor voor .NET API-referentie
description: Maakt het mogelijk om aangepaste opties te specificeren voor het genereren en opslaan van WordProcessingcompatibele documenten nadat ze zijn bewerkt
type: docs
weight: 1240
url: /nl/net/groupdocs.editor.options/wordprocessingsaveoptions/
---
## WordProcessingSaveOptions class

Maakt het mogelijk om aangepaste opties te specificeren voor het genereren en opslaan van WordProcessing-compatibele documenten nadat ze zijn bewerkt

```csharp
public sealed class WordProcessingSaveOptions : ICloneable, ISaveOptions
```

## Constructeurs

| Naam | Beschrijving |
| --- | --- |
| [WordProcessingSaveOptions](wordprocessingsaveoptions)(WordProcessingFormats) | Maakt een nieuw exemplaar van WordProcessingSaveOptions met opgegeven verplichte WordProcessing-uitvoerindeling, terwijl alle andere parameters default zijn |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [EnablePagination](../../groupdocs.editor.options/wordprocessingsaveoptions/enablepagination) { get; set; } | Hiermee kan paginering worden in- of uitgeschakeld die wordt gebruikt voor het opslaan van het tekstverwerkingsdocument. Als het originele document is geopend en bewerkt in pagineringsmodus, moet deze optie ook zijn ingeschakeld. Standaard is uitgeschakeld. |
| [FontEmbedding](../../groupdocs.editor.options/wordprocessingsaveoptions/fontembedding) { get; set; } | Verantwoordelijk voor het insluiten van lettertypebronnen in het WordProcessing-uitvoerdocument. Sluit standaard geen lettertypen in (NotEmbed). |
| [Locale](../../groupdocs.editor.options/wordprocessingsaveoptions/locale) { get; set; } | Maakt het mogelijk om de standaard locale (taal) voor het WordProcessing-document te overschrijven, die zal worden toegepast tijdens het maken. Wanneer niet is opgegeven (standaardwaarde), zal MS Word (of een ander programma) de document locale detecteren (of kiezen) volgens aan zijn eigen instellingen of andere factoren. |
| [LocaleBi](../../groupdocs.editor.options/wordprocessingsaveoptions/localebi) { get; set; } | Hiermee kunt u de locale (taal) voor het WordProcessing-document instellen voor de RTL-tekst (van rechts naar links), die wordt toegepast tijdens het maken ervan. Wanneer niet is opgegeven (standaardwaarde), MS Word (of ander programma) zal het document RTL locale detecteren (of kiezen) volgens zijn eigen instellingen of andere factoren. |
| [LocaleFarEast](../../groupdocs.editor.options/wordprocessingsaveoptions/localefareast) { get; set; } | Maakt het mogelijk om de locale (taal) voor het WordProcessing-document te overschrijven voor de Oost-Aziatische tekst, die zal worden toegepast tijdens het maken ervan. Wanneer niet is opgegeven (standaardwaarde), zal MS Word (of een ander programma) detecteren (of ) het document Oost-Aziatische locale volgens zijn eigen instellingen of andere factoren. |
| [OptimizeMemoryUsage](../../groupdocs.editor.options/wordprocessingsaveoptions/optimizememoryusage) { get; set; } | Schakelt mechanismen voor geheugenoptimalisatie in tijdens het genereren van documenten vanuit HTML, wat de prestaties verslechtert als kosten van afnemend geheugengebruik. Als u deze optie instelt op true, kan het geheugenverbruik aanzienlijk worden verminderd terwijl grote documenten worden gegenereerd, wat ten koste gaat van een langzamere opslagtijd. Standaard is false (geheugenoptimalisatie is uitgeschakeld omwille van betere prestaties). |
| [OutputFormat](../../groupdocs.editor.options/wordprocessingsaveoptions/outputformat) { get; set; } | Maakt het mogelijk om een WordProcessing-indeling op te geven, die zal worden gebruikt voor het opslaan van het document |
| [Password](../../groupdocs.editor.options/wordprocessingsaveoptions/password) { get; set; } | Hiermee kunt u een wachtwoord specificeren, wijzigen, verkrijgen of verwijderen, dat zal worden gebruikt om het gegenereerde WordProcessing-document te coderen. Specificeer NULL of een lege tekenreeks voor het verwijderen (opschonen) van het wachtwoord. |
| [Protection](../../groupdocs.editor.options/wordprocessingsaveoptions/protection) { get; set; } | Maakt het mogelijk om de opties voor documentbeveiliging te beheren en toe te passen voor het tekstverwerkingsdocument van elk formaat dat documentbeveiliging ondersteunt. Standaard is NULL - documentbeveiliging wordt niet gebruikt. |

## methoden

| Naam | Beschrijving |
| --- | --- |
| [Clone](../../groupdocs.editor.options/wordprocessingsaveoptions/clone)() | Maakt en retourneert een volledige kopie van deze instantie van WordProcessingSaveOptions class |

### Opmerkingen

WordProcessingSaveOptions wordt toegepast in situaties waarin er een instantie van de klasse EditableDocument is, die een bewerkte documentinhoud bevat en deze inhoud moet worden opgeslagen in het nieuwe document met WordProcessing-indeling.

### Zie ook

* interface [ISaveOptions](../isaveoptions)
* naamruimte [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* montage [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
