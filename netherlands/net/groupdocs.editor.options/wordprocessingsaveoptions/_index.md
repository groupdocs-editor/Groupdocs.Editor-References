---
title: "WordProcessingSaveOptions"
second_title: "GroupDocs.Editor voor .NET API-referentie"
description: "Staat toe om aangepaste opties op te geven voor het genereren en opslaan van WordProcessing-conforme documenten nadat ze bewerkt zijn"
type: docs
weight: 1240
url: /nl/net/groupdocs.editor.options/wordprocessingsaveoptions/
---
## WordProcessingSaveOptions class

Staat toe aangepaste opties op te geven voor het genereren en opslaan van WordProcessing‑conforme documenten nadat ze bewerkt zijn

```csharp
public sealed class WordProcessingSaveOptions : ICloneable, ISaveOptions
```

## Constructors

| Name | Beschrijving |
| --- | --- |
| [WordProcessingSaveOptions](wordprocessingsaveoptions#constructor)() | Deze parameterloze constructor maakt een nieuwe instantie van WordProcessingSaveOptions met het DOCX-uitvoerformaat (kan daarna worden aangepast via de eigenschap [`OutputFormat`](./outputformat)) |
| [WordProcessingSaveOptions](wordprocessingsaveoptions#constructor_1)(WordProcessingFormats) | Maakt een nieuwe instantie van WordProcessingSaveOptions met het opgegeven verplichte WordProcessing-uitvoerformaat, terwijl alle andere parameters standaard zijn |

## Properties

| Name | Beschrijving |
| --- | --- |
| [EnablePagination](../../groupdocs.editor.options/wordprocessingsaveoptions/enablepagination) { get; set; } | Staat toe om paginering in of uit te schakelen die zal worden gebruikt bij het opslaan van het WordProcessing-document. Als het oorspronkelijke document geopend en bewerkt werd in pagineringsmodus, moet deze optie ook worden ingeschakeld. Standaard is uitgeschakeld. |
| [FontEmbedding](../../groupdocs.editor.options/wordprocessingsaveoptions/fontembedding) { get; set; } | Verantwoordelijk voor het insluiten van lettertypebronnen in het uitvoer‑WordProcessing‑document. Standaard worden er geen lettertypen ingesloten (NotEmbed). |
| [Locale](../../groupdocs.editor.options/wordprocessingsaveoptions/locale) { get; set; } | Staat toe om de standaardlocale (taal) voor het WordProcessing-document te overschrijven, die tijdens de creatie wordt toegepast. Wanneer niet gespecificeerd (standaardwaarde), zal MS Word (of een ander programma) de documentlocale detecteren (of kiezen) op basis van zijn eigen instellingen of andere factoren. |
| [LocaleBi](../../groupdocs.editor.options/wordprocessingsaveoptions/localebi) { get; set; } | Staat toe om de locale (taal) voor RTL‑tekst (right-to-left) in het WordProcessing-document te overschrijven, die tijdens de creatie wordt toegepast. Wanneer niet gespecificeerd (standaardwaarde), zal MS Word (of een ander programma) de RTL‑locale van het document detecteren (of kiezen) op basis van zijn eigen instellingen of andere factoren. |
| [LocaleFarEast](../../groupdocs.editor.options/wordprocessingsaveoptions/localefareast) { get; set; } | Staat toe om de locale (taal) voor Oost‑Aziatische tekst in het WordProcessing-document te overschrijven, die tijdens de creatie wordt toegepast. Wanneer niet gespecificeerd (standaardwaarde), zal MS Word (of een ander programma) de Oost‑Aziatische locale van het document detecteren (of kiezen) op basis van zijn eigen instellingen of andere factoren. |
| [OptimizeMemoryUsage](../../groupdocs.editor.options/wordprocessingsaveoptions/optimizememoryusage) { get; set; } | Schakelt geheugenoptimalisatiemechanismen in tijdens de documentgeneratie vanuit HTML, wat de prestaties vermindert als prijs voor het verlagen van het geheugenverbruik. Het instellen van deze optie op true kan het geheugenverbruik aanzienlijk verminderen bij het genereren van grote documenten, ten koste van een tragere opslagtijd. Standaard is false (geheugenoptimalisatie is uitgeschakeld ten behoeve van betere prestaties). |
| [OutputFormat](../../groupdocs.editor.options/wordprocessingsaveoptions/outputformat) { get; set; } | Staat toe om een WordProcessing-formaat op te geven, dat zal worden gebruikt voor het opslaan van het document |
| [Password](../../groupdocs.editor.options/wordprocessingsaveoptions/password) { get; set; } | Staat toe om een wachtwoord op te geven, te wijzigen, op te halen of te verwijderen, dat zal worden gebruikt om het gegenereerde WordProcessing-document te coderen. Geef NULL of een lege tekenreeks op om het wachtwoord te verwijderen (op te schonen). |
| [Protection](../../groupdocs.editor.options/wordprocessingsaveoptions/protection) { get; set; } | Staat toe om de documentbeveiligingsopties voor het WordProcessing-document van elk formaat dat documentbeveiliging ondersteunt te beheren en toe te passen. Standaard is NULL – documentbeveiliging wordt niet gebruikt. |

## Methods

| Name | Beschrijving |
| --- | --- |
| [Clone](../../groupdocs.editor.options/wordprocessingsaveoptions/clone)() | Maakt een volledige kopie van deze instantie van de WordProcessingSaveOptions‑klasse en retourneert deze |

### Opmerkingen

WordProcessingSaveOptions wordt toegepast in situaties waarin er een instantie van de EditableDocument‑klasse bestaat, die bewerkte documentinhoud bevat, en waarbij die inhoud moet worden opgeslagen in een nieuw document van WordProcessing‑formaat.

### Zie ook

* interface [ISaveOptions](../isaveoptions)
* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.editor.dll -->
