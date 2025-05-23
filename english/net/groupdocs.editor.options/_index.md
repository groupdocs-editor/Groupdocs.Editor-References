---
title: GroupDocs.Editor.Options
second_title: GroupDocs.Editor for .NET API Reference
description: The GroupDocs.Editor.Options namespace provides interfaces for load and save options.
type: docs
weight: 160
url: /net/groupdocs.editor.options/
---
The GroupDocs.Editor.Options namespace provides interfaces for load and save options.

## Classes

| Class | Description |
| --- | --- |
| [DelimitedTextEditOptions](./delimitedtexteditoptions) | Options for loading text-based Spreadsheet documents (CSV, Tab-based etc.), that use a separator (delimiter) |
| [DelimitedTextSaveOptions](./delimitedtextsaveoptions) | Contains options for generating and saving text-based Spreadsheet documents (CSV, Tab-based etc.), that use a separator (delimiter) |
| [EbookEditOptions](./ebookeditoptions) | Allows to specify and adjust custom options for editing E-book documents in all supported formats: ePub, MOBI, and AZW3. |
| [EbookSaveOptions](./ebooksaveoptions) | Allows to specify custom options for generating and saving the document in all supportable e-Book formats: ePub, MOBI, and AZW3. |
| [EmailEditOptions](./emaileditoptions) | Allows to specify custom options for editing documents in the different electronic mail (email) formats |
| [EmailSaveOptions](./emailsaveoptions) | Allows to specify custom options for generating and saving electronic mail (email) documents |
| [FixedLayoutEditOptionsBase](./fixedlayouteditoptionsbase) | Base abstract class for the options for all documents of fixed-layout formats like PDF and XPS |
| [HtmlSaveOptions](./htmlsaveoptions) | Allows to specify custom options for saving the [`EditableDocument`](../groupdocs.editor/editabledocument) instance to the HTML format |
| [MarkdownEditOptions](./markdowneditoptions) | Allows to specify custom options for editing documents in Markdown (MD) format |
| [MarkdownImageLoadArgs](./markdownimageloadargs) | Provides data for the ProcessImage event. |
| [MarkdownSaveOptions](./markdownsaveoptions) | Allows to specify custom options for generating and saving Markdown documents |
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
| [WebFont](./webfont) | Represents a font settings for the web |
| [WordProcessingEditOptions](./wordprocessingeditoptions) | Allows to specify custom options for editing documents of all supportable WordProcessing (Words-compliant) formats like DOC(X), RTF, ODT etc. |
| [WordProcessingLoadOptions](./wordprocessingloadoptions) | Contains options for loading WordProcessing (Word-compatible) documents like DOC(X), RTF, ODT etc. into Editor class |
| [WordProcessingProtection](./wordprocessingprotection) | Encapsulates document protection options for the WordProcessing document, which is generated from HTML |
| [WordProcessingSaveOptions](./wordprocessingsaveoptions) | Allows to specify custom options for generating and saving WordProcessing-compliant documents after they were edited |
| [WorksheetProtection](./worksheetprotection) | Encapsulates worksheet protection options, which allow to protect a worksheet in the output Spreadsheet document from modification of specified type with a specified password. |
| [XmlEditOptions](./xmleditoptions) | Allows to specify custom options for editing XML (eXtensible Markup Language) documents and converting them to the HTML |
| [XmlFormatOptions](./xmlformatoptions) | Contains options, that allow to adjust the formatting of XML document, when it is represented as HTML |
| [XmlHighlightOptions](./xmlhighlightoptions) | Contains options, that allow to customize the XML highlighting during XML-to-HTML conversion |
| [XpsSaveOptions](./xpssaveoptions) | Allows to specify custom options for generating and saving XPS (XML Paper Specifications) documents |
## Structures

| Structure | Description |
| --- | --- |
| [PageRange](./pagerange) | Encapsulates one page range, which can have open or closed bounds. By default is "fully open" - it includes all existing pages. Page numbering starts from 1, not from 0. |
## Interfaces

| Interface | Description |
| --- | --- |
| [IEditOptions](./ieditoptions) | Common interface for all options, which are responsible for document-to-HTML conversions. Declares no members. |
| [IHtmlSavingCallback](./ihtmlsavingcallback) | Interface, that is used while saving the  to the HTML format and which must be implemented by the end-user in order to save the provided resource and returns a link to it |
| [ILoadOptions](./iloadoptions) | Common interface for all option classes, responsible for loading documents of different type formats |
| [IMarkdownImageLoadCallback](./imarkdownimageloadcallback) | Implement this interface if you want to control how GroupDocs.Editor load images when loading the file in Markdown format |
| [ISaveOptions](./isaveoptions) | Interface for all saving options for all documents types. Declares no members. |
## Enumeration

| Enumeration | Description |
| --- | --- |
| [FontEmbeddingOptions](./fontembeddingoptions) | Font embedding options controls which font resources should be embedded into the output WordProcessing or PDF document |
| [FontExtractionOptions](./fontextractionoptions) | Font extraction options control which fonts should be extracted and from where |
| [MailMessageOutput](./mailmessageoutput) | Controls which parts of the mail message should be delivered to the output processing |
| [MarkdownImageLoadingAction](./markdownimageloadingaction) | Defines the mode of image loading while opening for editing the file in Markdown format |
| [MarkdownTableContentAlignment](./markdowntablecontentalignment) | Allows to specify the alignment of the content of the table to be used when exporting into Markdown format |
| [PdfCompliance](./pdfcompliance) | Specifies the PDF standards compliance level |
| [TextDirection](./textdirection) | Represents 3 possible variants how to treat text direction in the plain text documents |
| [TextLeadingSpacesOptions](./textleadingspacesoptions) | Contains available options for leading space handling during opening plain text document (TXT) |
| [TextTrailingSpacesOptions](./texttrailingspacesoptions) | Contains available options for trailing space handling during opening plain text document (TXT) |
| [WordProcessingProtectionType](./wordprocessingprotectiontype) | Represents all available protection types of the WordProcessing document |
| [WorksheetProtectionType](./worksheetprotectiontype) | Represents Spreadsheet worksheet (tab) protection types |

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.editor.dll -->
