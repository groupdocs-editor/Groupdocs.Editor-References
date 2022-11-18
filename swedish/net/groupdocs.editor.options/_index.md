---
title: GroupDocs.Editor.Options
second_title: GroupDocs.Editor för .NET API-referens
description: Namnutrymmet GroupDocs.Editor.Options tillhandahåller gränssnitt för att ladda och spara alternativ.
type: docs
weight: 130
url: /sv/net/groupdocs.editor.options/
---
Namnutrymmet GroupDocs.Editor.Options tillhandahåller gränssnitt för att ladda och spara alternativ.

## Klasser

| Klass | Beskrivning |
| --- | --- |
| [Azw3SaveOptions](./azw3saveoptions) | Tillåter att ange anpassade alternativ för att generera och spara AZW3 e-böcker, även känd som Kindle Format 8 (KF8) |
| [DelimitedTextEditOptions](./delimitedtexteditoptions) | Alternativ för att ladda textbaserade kalkylarksdokument (CSV, Tab-baserade etc.), som använder en avgränsare (avgränsare) |
| [DelimitedTextSaveOptions](./delimitedtextsaveoptions) | Innehåller alternativ för att generera och spara textbaserade kalkylbladsdokument (CSV, Tab-baserade etc.), som använder en avgränsare (avgränsare) |
| [EbookEditOptions](./ebookeditoptions) | Gör det möjligt att specificera och justera anpassade alternativ för redigering av e-boksdokument i alla format som stöds: ePub, MOBI och AZW3. |
| [EmailEditOptions](./emaileditoptions) | Gör det möjligt att ange anpassade alternativ för redigering av dokument i de olika formaten för e-post (e-post) |
| [EmailSaveOptions](./emailsaveoptions) | Tillåter att ange anpassade alternativ för att generera och spara elektronisk post (e-post) documents |
| [EpubSaveOptions](./epubsaveoptions) | Tillåter att ange anpassade alternativ för att generera och spara IDPF EPUB-dokument (öppen standard för e-böcker skapade av International Digital Publishing Forum) |
| [FixedLayoutEditOptionsBase](./fixedlayouteditoptionsbase) | Bas abstrakt klass för alternativen för alla dokument med fasta layoutformat som PDF och XPS |
| [MhtmlSaveOptions](./mhtmlsaveoptions) | Tillåter att ange anpassade alternativ för att generera och spara MHTML (MIME-inkapsling av samlade HTML-dokument) documents |
| [PdfEditOptions](./pdfeditoptions) | Gör det möjligt att ange anpassade alternativ för redigering av PDF-dokument |
| [PdfLoadOptions](./pdfloadoptions) | Innehåller alternativ för att ladda PDF-dokument i Editor class |
| [PdfSaveOptions](./pdfsaveoptions) | Gör det möjligt att ange anpassade alternativ för att generera och spara PDF-dokument (Portable Document Format) |
| [PresentationEditOptions](./presentationeditoptions) | Tillåter att ange anpassade alternativ för redigering av dokument av alla stödbara presentationsformat (PowerPoint-kompatibla) |
| [PresentationLoadOptions](./presentationloadoptions) | Tillåter att ange anpassade alternativ för att ladda dokument av alla stödjande presentationsformat som PPT(X), PPTM, PPS(X) etc. |
| [PresentationSaveOptions](./presentationsaveoptions) | Gör det möjligt att ange anpassade alternativ för att generera och spara presentationsdokument (PowerPoint-kompatibla) |
| [SpreadsheetEditOptions](./spreadsheeteditoptions) | Gör det möjligt att ange anpassade alternativ för redigering av dokument av alla stödbara kalkylarksformat (Excel-kompatibla) |
| [SpreadsheetLoadOptions](./spreadsheetloadoptions) | Innehåller alternativ för att ladda binära kalkylark (celler, Excel-kompatibla) dokument som XLS(X), ODS etc. i Editor class |
| [SpreadsheetSaveOptions](./spreadsheetsaveoptions) | Gör det möjligt att ange anpassade alternativ för att generera och spara kalkylark (Excel-kompatibla) dokument |
| [TextEditOptions](./texteditoptions) | Gör det möjligt att ange anpassade alternativ för att ladda plain text (TXT) documents |
| [TextSaveOptions](./textsaveoptions) | Gör det möjligt att ange anpassade alternativ för att generera och spara plain text (TXT) documents |
| [WordProcessingEditOptions](./wordprocessingeditoptions) | Tillåter att ange anpassade alternativ för redigering av dokument av alla stödbara WordProcessing (Words-kompatibla) format som DOC(X), RTF, ODT etc. |
| [WordProcessingLoadOptions](./wordprocessingloadoptions) | Innehåller alternativ för att ladda WordProcessing (Word-kompatibla) dokument som DOC(X), RTF, ODT etc. i Editor class |
| [WordProcessingProtection](./wordprocessingprotection) | Kapslar in dokumentskyddsalternativ för WordProcessing-dokumentet, som genereras från HTML |
| [WordProcessingSaveOptions](./wordprocessingsaveoptions) | Gör det möjligt att ange anpassade alternativ för att generera och spara WordProcessing-kompatibla dokument efter att de har redigerats |
| [WorksheetProtection](./worksheetprotection) | Inkapslar skyddsalternativ för kalkylblad, som gör det möjligt att skydda ett kalkylblad i kalkylarksdokumentet från ändring av specificerad typ med ett specificerat lösenord. |
| [XmlEditOptions](./xmleditoptions) | Gör det möjligt att ange anpassade alternativ för att ladda XML-dokument (eXtensible Markup Language) och konvertera dem till HTML |
| [XmlHighlightOptions](./xmlhighlightoptions) | Innehåller alternativ som gör det möjligt att anpassa XML-markeringen under XML-till-HTML-konvertering |
| [XpsEditOptions](./xpseditoptions) | Tillåter att ange anpassade alternativ för redigering (XML Paper Specifications) documents |
| [XpsSaveOptions](./xpssaveoptions) | Gör det möjligt att ange anpassade alternativ för att generera och spara XPS-dokument (XML Paper Specifications) |
## Strukturer

| Strukturera | Beskrivning |
| --- | --- |
| [PageRange](./pagerange) | Kapslar in ett sidintervall, som kan ha öppna eller slutna gränser. Som standard är "helt öppen" - den inkluderar alla befintliga sidor. Sidnumreringen börjar från 1, inte från 0. |
## Gränssnitt

| Gränssnitt | Beskrivning |
| --- | --- |
| [IEditOptions](./ieditoptions) | Gemensamt gränssnitt för alla alternativ, som är ansvariga för dokument-till-HTML-konverteringar. Deklarerar inga medlemmar. |
| [ILoadOptions](./iloadoptions) | Gemensamt gränssnitt för alla alternativklasser, ansvarig för att ladda dokument av olika typ formats |
| [ISaveOptions](./isaveoptions) | Gränssnitt för alla sparalternativ för alla dokumenttyper. Deklarerar inga medlemmar. |
## Uppräkning

| Uppräkning | Beskrivning |
| --- | --- |
| [FontEmbeddingOptions](./fontembeddingoptions) | Alternativ för inbäddning av teckensnitt styr vilka teckensnittsresurser som ska bäddas in i WordProcessing eller PDF-dokument |
| [FontExtractionOptions](./fontextractionoptions) | Alternativ för teckensnittsextraktion styr vilka teckensnitt som ska extraheras och varifrån |
| [MailMessageOutput](./mailmessageoutput) | Styr vilka delar av e-postmeddelandet som ska levereras till output processing |
| [PdfCompliance](./pdfcompliance) | Anger PDF-standardens efterlevnadsnivå |
| [TextDirection](./textdirection) | Representerar 3 möjliga varianter av hur man behandlar textriktning i vanliga textdokument |
| [TextLeadingSpacesOptions](./textleadingspacesoptions) | Innehåller tillgängliga alternativ för att leda utrymmeshantering vid öppning av ett vanligt textdokument (TXT) |
| [TextTrailingSpacesOptions](./texttrailingspacesoptions) | Innehåller tillgängliga alternativ för efterföljande utrymmeshantering vid öppning av ett vanligt textdokument (TXT) |
| [WordProcessingProtectionType](./wordprocessingprotectiontype) | Representerar alla tillgängliga skyddstyper för WordProcessing document |
| [WorksheetProtectionType](./worksheetprotectiontype) | Representerar skyddstyper för kalkylblad (flik) |

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
