---
title: GroupDocs.Editor.Options
second_title: GroupDocs.Editor for .NET API Reference
description: The GroupDocs.Editor.Options namespace provides interfaces for load and save options.
type: docs
weight: 130
url: /net/groupdocs.editor.options/
---
The GroupDocs.Editor.Options namespace provides interfaces for load and save options.

## Classes

| Class | Description |
| --- | --- |
| [Azw3SaveOptions](./azw3saveoptions) | Allows to specify custom options for generating and saving the AZW3 e-books, also known as Kindle Format 8 (KF8) |
| [DelimitedTextEditOptions](./delimitedtexteditoptions) | Options for loading text-based Spreadsheet documents (CSV, Tab-based etc.), that use a separator (delimiter) |
| [DelimitedTextSaveOptions](./delimitedtextsaveoptions) | Contains options for generating and saving text-based Spreadsheet documents (CSV, Tab-based etc.), that use a separator (delimiter) |
| [EbookEditOptions](./ebookeditoptions) | Allows to specify and adjust custom options for editing E-book documents in all supported formats: ePub, MOBI, and AZW3. |
| [EmailEditOptions](./emaileditoptions) | Allows to specify custom options for editing documents in the different electronic mail (email) formats |
| [EmailSaveOptions](./emailsaveoptions) | Allows to specify custom options for generating and saving electronic mail (email) documents |
| [EpubSaveOptions](./epubsaveoptions) | Allows to specify custom options for generating and saving the IDPF EPUB documents (open standard for e-books created by the International Digital Publishing Forum) |
| [FixedLayoutEditOptionsBase](./fixedlayouteditoptionsbase) | Base abstract class for the options for all documents of fixed-layout formats like PDF and XPS |
| [MhtmlSaveOptions](./mhtmlsaveoptions) | Allows to specify custom options for generating and saving the MHTML (MIME encapsulation of aggregate HTML documents) documents |
| [PdfEditOptions](./pdfeditoptions) | Allows to specify custom options for editing PDF documents |
| [PdfLoadOptions](./pdfloadoptions) | Contains options for loading PDF documents into Editor class |
| [PdfSaveOptions](./pdfsaveoptions) | Allows to specify custom options for generating and saving PDF (Portable Document Format) documents |
| [PresentationEditOptions](./presentationeditoptions) | Allows to specify custom options for editing documents of all supportable Presentation (PowerPoint-compatible) formats |
| [PresentationLoadOptions](./presentationloadoptions) | Allows to specify custom options for loading documents of all supportable Presentation formats like PPT(X), PPTM, PPS(X) etc. |
| [PresentationSaveOptions](./presentationsaveoptions) | Allows to specify custom options for generating and saving Presentation (PowerPoint-compatible) documents |
| [SpreadsheetEditOptions](./spreadsheeteditoptions) | Allows to specify custom options for editing documents of all supportable Spreadsheet (Excel-compatible) formats |
| [SpreadsheetLoadOptions](./spreadsheetloadoptions) | Contains options for loading binary Spreadsheet (Cells, Excel-compatible) documents like XLS(X), ODS etc. into Editor class |
| [SpreadsheetSaveOptions](./spreadsheetsaveoptions) | Allows to specify custom options for generating and saving Spreadsheet (Excel-compliant) documents |
| [TextEditOptions](./texteditoptions) | Allows to specify custom options for loading plain text (TXT) documents |
| [TextSaveOptions](./textsaveoptions) | Allows to specify custom options for generating and saving plain text (TXT) documents |
| [WordProcessingEditOptions](./wordprocessingeditoptions) | Allows to specify custom options for editing documents of all supportable WordProcessing (Words-compliant) formats like DOC(X), RTF, ODT etc. |
| [WordProcessingLoadOptions](./wordprocessingloadoptions) | Contains options for loading WordProcessing (Word-compatible) documents like DOC(X), RTF, ODT etc. into Editor class |
| [WordProcessingProtection](./wordprocessingprotection) | Encapsulates document protection options for the WordProcessing document, which is generated from HTML |
| [WordProcessingSaveOptions](./wordprocessingsaveoptions) | Allows to specify custom options for generating and saving WordProcessing-compliant documents after they were edited |
| [WorksheetProtection](./worksheetprotection) | Encapsulates worksheet protection options, which allow to protect a worksheet in the output Spreadsheet document from modification of specified type with a specified password. |
| [XmlEditOptions](./xmleditoptions) | Allows to specify custom options for loading XML (eXtensible Markup Language) documents and converting them to the HTML |
| [XmlHighlightOptions](./xmlhighlightoptions) | Contains options, that allow to customize the XML highlighting during XML-to-HTML conversion |
| [XpsEditOptions](./xpseditoptions) | Allows to specify custom options for editing (XML Paper Specifications) documents |
| [XpsSaveOptions](./xpssaveoptions) | Allows to specify custom options for generating and saving XPS (XML Paper Specifications) documents |
## Interfaces

| Interface | Description |
| --- | --- |
| [IEditOptions](./ieditoptions) | Common interface for all options, which are responsible for document-to-HTML conversions. Declares no members. |
| [ILoadOptions](./iloadoptions) | Common interface for all option classes, responsible for loading documents of different type formats |
| [ISaveOptions](./isaveoptions) | Interface for all saving options for all documents types. Declares no members. |
## Enumeration

| Enumeration | Description |
| --- | --- |
| [FontEmbeddingOptions](./fontembeddingoptions) | Font embedding options controls which font resources should be embedded into the output WordProcessing or PDF document |
| [FontExtractionOptions](./fontextractionoptions) | Font extraction options control which fonts should be extracted and from where |
| [MailMessageOutput](./mailmessageoutput) | Controls which parts of the mail message should be delivered to the output processing |
| [PdfCompliance](./pdfcompliance) | Specifies the PDF standards compliance level |
| [TextDirection](./textdirection) | Represents 3 possible variants how to treat text direction in the plain text documents |
| [TextLeadingSpacesOptions](./textleadingspacesoptions) | Contains available options for leading space handling during opening plain text document (TXT) |
| [TextTrailingSpacesOptions](./texttrailingspacesoptions) | Contains available options for trailing space handling during opening plain text document (TXT) |
| [WordProcessingProtectionType](./wordprocessingprotectiontype) | Represents all available protection types of the WordProcessing document |
| [WorksheetProtectionType](./worksheetprotectiontype) | Represents Spreadsheet worksheet (tab) protection types |

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.editor.dll -->
