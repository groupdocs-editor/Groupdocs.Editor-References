---
title: "GroupDocs.Editor.Options"
second_title: "GroupDocs.Editor för .NET API-referens"
description: "GroupDocs.Editor.Options-namnrymden tillhandahåller gränssnitt för inläsnings- och sparalternativ"
type: docs
weight: 160
url: /sv/net/groupdocs.editor.options/
---
GroupDocs.Editor.Options-namnrymden tillhandahåller gränssnitt för inläsnings- och sparalternativ

## Klasser

| Klass | Beskrivning |
| --- | --- |
| [DelimitedTextEditOptions](./delimitedtexteditoptions) | Alternativ för att läsa in textbaserade kalkylbladsdokument (CSV, tabbaserade etc.) som använder en separator (avgränsare) |
| [DelimitedTextSaveOptions](./delimitedtextsaveoptions) | Innehåller alternativ för att generera och spara textbaserade kalkylbladsdokument (CSV, tabbaserade etc.) som använder en separator (avgränsare) |
| [EbookEditOptions](./ebookeditoptions) | Tillåter att ange och justera anpassade alternativ för redigering av e‑bokdokument i alla stödda format: ePub, MOBI och AZW3. |
| [EbookSaveOptions](./ebooksaveoptions) | Tillåter att ange anpassade alternativ för att generera och spara dokumentet i alla stödbara e‑bokformat: ePub, MOBI och AZW3. |
| [EmailEditOptions](./emaileditoptions) | Tillåter att ange anpassade alternativ för att redigera dokument i de olika e‑postformaten (email) |
| [EmailSaveOptions](./emailsaveoptions) | Tillåter att ange anpassade alternativ för att generera och spara e‑postdokument (email) |
| [FixedLayoutEditOptionsBase](./fixedlayouteditoptionsbase) | Abstrakt basklass för alternativen för alla dokument i fasta layoutformat som PDF och XPS |
| [HtmlSaveOptions](./htmlsaveoptions) | Tillåter att ange anpassade alternativ för att spara [`EditableDocument`](../groupdocs.editor/editabledocument)-instansen till HTML-formatet |
| [MarkdownEditOptions](./markdowneditoptions) | Tillåter att ange anpassade alternativ för att redigera dokument i Markdown (MD)-format |
| [MarkdownImageLoadArgs](./markdownimageloadargs) | Tillhandahåller data för ProcessImage‑händelsen. |
| [MarkdownSaveOptions](./markdownsaveoptions) | Tillåter att ange anpassade alternativ för att generera och spara Markdown-dokument |
| [MhtmlSaveOptions](./mhtmlsaveoptions) | Tillåter att ange anpassade alternativ för att generera och spara MHTML (MIME encapsulation of aggregate HTML documents)-dokument |
| [PdfEditOptions](./pdfeditoptions) | Tillåter att ange anpassade alternativ för att redigera PDF-dokument |
| [PdfLoadOptions](./pdfloadoptions) | Innehåller alternativ för att läsa in PDF-dokument i Editor‑klassen |
| [PdfSaveOptions](./pdfsaveoptions) | Tillåter att ange anpassade alternativ för att generera och spara PDF (Portable Document Format)-dokument |
| [PresentationEditOptions](./presentationeditoptions) | Tillåter att ange anpassade alternativ för redigering av dokument i alla stödjade Presentation (PowerPoint-compatible)-format |
| [PresentationLoadOptions](./presentationloadoptions) | Tillåter att ange anpassade alternativ för inläsning av dokument i alla stödjade Presentation-format, såsom PPT(X), PPTM, PPS(X) etc. |
| [PresentationSaveOptions](./presentationsaveoptions) | Tillåter att ange anpassade alternativ för generering och sparande av Presentation (PowerPoint-compatible)-dokument |
| [SpreadsheetEditOptions](./spreadsheeteditoptions) | Tillåter att ange anpassade alternativ för redigering av dokument i alla stödjade Spreadsheet (Excel-compatible)-format |
| [SpreadsheetLoadOptions](./spreadsheetloadoptions) | Innehåller alternativ för inläsning av binära Spreadsheet (Cells, Excel-compatible)-dokument, såsom XLS(X), ODS etc., i Editor-klassen |
| [SpreadsheetSaveOptions](./spreadsheetsaveoptions) | Tillåter att ange anpassade alternativ för generering och sparande av Spreadsheet (Excel-compliant)-dokument |
| [TextEditOptions](./texteditoptions) | Tillåter att ange anpassade alternativ för inläsning av ren text (TXT)-dokument |
| [TextSaveOptions](./textsaveoptions) | Tillåter att ange anpassade alternativ för generering och sparande av ren text (TXT)-dokument |
| [WebFont](./webfont) | Representerar en teckensnittskonfiguration för webben |
| [WordProcessingEditOptions](./wordprocessingeditoptions) | Tillåter att ange anpassade alternativ för redigering av dokument i alla stödjade WordProcessing (Words-compliant)-format, såsom DOC(X), RTF, ODT etc. |
| [WordProcessingLoadOptions](./wordprocessingloadoptions) | Innehåller alternativ för inläsning av WordProcessing (Word-compatible)-dokument, såsom DOC(X), RTF, ODT etc., i Editor-klassen |
| [WordProcessingProtection](./wordprocessingprotection) | Inkapslar dokumentskyddsalternativ för WordProcessing-dokumentet som genereras från HTML |
| [WordProcessingSaveOptions](./wordprocessingsaveoptions) | Tillåter att ange anpassade alternativ för generering och sparande av WordProcessing-kompatibla dokument efter att de har redigerats |
| [WorksheetProtection](./worksheetprotection) | Inkapslar skyddsalternativ för kalkylblad, som möjliggör att skydda ett kalkylblad i det genererade Spreadsheet-dokumentet från ändringar av en specificerad typ med ett angivet lösenord |
| [XmlEditOptions](./xmleditoptions) | Tillåter att ange anpassade alternativ för redigering av XML (eXtensible Markup Language)-dokument och konvertering av dem till HTML |
| [XmlFormatOptions](./xmlformatoptions) | Innehåller alternativ som möjliggör att justera formateringen av XML-dokumentet när det visas som HTML |
| [XmlHighlightOptions](./xmlhighlightoptions) | Innehåller alternativ som möjliggör att anpassa XML-markering under XML-till-HTML-konvertering |
| [XpsSaveOptions](./xpssaveoptions) | Tillåter att ange anpassade alternativ för generering och sparande av XPS (XML Paper Specifications)-dokument |
## Structures

| Struktur | Beskrivning |
| --- | --- |
| [PageRange](./pagerange) | Inkapslar ett sidintervall som kan ha öppna eller slutna gränser. Som standard är det "fullt öppet" – det inkluderar alla befintliga sidor. Sidnumrering börjar på 1, inte på 0. |
## Gränssnitt

| Gränssnitt | Beskrivning |
| --- | --- |
| [IEditOptions](./ieditoptions) | Gemensamt gränssnitt för alla alternativ som ansvarar för dokument‑till‑HTML‑konverteringar. Deklarerar inga medlemmar. |
| [IHtmlSavingCallback](./ihtmlsavingcallback) | Gränssnitt som används vid sparande till HTML-formatet och som måste implementeras av slutanvändaren för att spara den tillhandahållna resursen och returnera en länk till den |
| [ILoadOptions](./iloadoptions) | Gemensamt gränssnitt för alla alternativklasser som ansvarar för inläsning av dokument av olika format |
| [IMarkdownImageLoadCallback](./imarkdownimageloadcallback) | Implementera detta gränssnitt om du vill styra hur GroupDocs.Editor laddar bilder när filen läses in i Markdown-format |
| [ISaveOptions](./isaveoptions) | Gränssnitt för alla sparalternativ för alla dokumenttyper. Deklarerar inga medlemmar. |
## Uppräkning

| Uppräkning | Beskrivning |
| --- | --- |
| [FontEmbeddingOptions](./fontembeddingoptions) | Teckensnittsinbäddningsalternativ styr vilka teckensnittresurser som ska bäddas in i det genererade WordProcessing- eller PDF-dokumentet |
| [FontExtractionOptions](./fontextractionoptions) | Fontextraktionsalternativ styr vilka teckensnitt som ska extraheras och varifrån |
| [MailMessageOutput](./mailmessageoutput) | Styr vilka delar av e‑postmeddelandet som ska levereras till utdatahanteringen |
| [MarkdownImageLoadingAction](./markdownimageloadingaction) | Definierar läget för bildladdning när filen öppnas för redigering i Markdown-format |
| [MarkdownTableContentAlignment](./markdowntablecontentalignment) | Tillåter att ange justeringen av tabellens innehåll som ska användas vid export till Markdown-format |
| [PdfCompliance](./pdfcompliance) | Anger PDF-standardernas efterlevnadsnivå |
| [TextDirection](./textdirection) | Representerar 3 möjliga varianter för hur textens riktning ska hanteras i rena textdokument |
| [TextLeadingSpacesOptions](./textleadingspacesoptions) | Innehåller tillgängliga alternativ för hantering av inledande mellanslag vid öppning av rena textdokument (TXT) |
| [TextTrailingSpacesOptions](./texttrailingspacesoptions) | Innehåller tillgängliga alternativ för hantering av avslutande mellanslag vid öppning av rena textdokument (TXT) |
| [WordProcessingProtectionType](./wordprocessingprotectiontype) | Representerar alla tillgängliga skyddstyper för WordProcessing-dokumentet |
| [WorksheetProtectionType](./worksheetprotectiontype) | Representerar skyddstyper för kalkylbladets arbetsblad (flik) |

<!-- REDIGERA INTE: genererad av xmldocmd för GroupDocs.editor.dll -->
