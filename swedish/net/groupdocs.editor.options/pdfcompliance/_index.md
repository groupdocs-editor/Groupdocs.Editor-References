---
title: PdfCompliance
second_title: GroupDocs.Editor för .NET API-referens
description: Anger PDFstandardens efterlevnadsnivå
type: docs
weight: 1030
url: /sv/net/groupdocs.editor.options/pdfcompliance/
---
## PdfCompliance enumeration

Anger PDF-standardens efterlevnadsnivå

```csharp
public enum PdfCompliance : byte
```

### Värderingar

| namn | Värde | Beskrivning |
| --- | --- | --- |
| Pdf17 | `0` | PDF 1.7 (ISO 32000-1) standard |
| Pdf20 | `1` | PDF 2.0 (ISO 32000-2) standard |
| PdfA1a | `2` | PDF/A-1a standard. Den här nivån inkluderar alla krav i PDF/A-1b och kräver dessutom att dokumentstrukturen inkluderas (även känd som "taggad"), med syftet att säkerställa att dokumentinnehållet kan sökas i och återanvändas. |
| PdfA1b | `3` | PDF/A-1b (ISO 19005-1). PDF/A-1b har som mål att säkerställa tillförlitlig återgivning av dokumentets visuella utseende. |
| PdfA2a | `4` | PDF/A-2a (ISO 19005-2) standard. Den här nivån inkluderar alla krav i PDF/A-2u och kräver dessutom att dokumentstrukturen inkluderas (även känd som "taggad"), i syfte att säkerställa att dokumentinnehållet kan sökas i och återanvändas. |
| PdfA2u | `5` | PDF/A-2u (ISO 19005-2) standard. PDF/A-2u har som mål att bevara dokumentets statiska visuella utseende över tid, oberoende av de verktyg och system som används för att skapa, lagra eller rendera filerna. Dessutom kan all text som finns i dokumentet extraheras tillförlitligt som en serie Unicode-kodpunkter. |
| PdfUa1 | `6` | PDF/UA-1 (ISO 14289-1) standard. Det primära syftet med PDF/UA är att definiera hur elektroniska dokument ska representeras i PDF-format på ett sätt som gör att filen är tillgänglig. |

### Se även

* namnutrymme [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* hopsättning [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
