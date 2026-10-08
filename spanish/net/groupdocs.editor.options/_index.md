---
title: "GroupDocs.Editor.Options"
second_title: "GroupDocs.Editor para .NET Referencia de API"
description: "El espacio de nombres GroupDocs.Editor.Options proporciona interfaces para opciones de carga y guardado."
type: docs
weight: 160
url: /es/net/groupdocs.editor.options/
---
El espacio de nombres GroupDocs.Editor.Options proporciona interfaces para opciones de carga y guardado.

## Clases

| Clase | Descripción |
| --- | --- |
| [DelimitedTextEditOptions](./delimitedtexteditoptions) | Opciones para cargar documentos de hoja de cálculo basados en texto (CSV, basados en tabulaciones, etc.), que utilizan un separador (delimitador) |
| [DelimitedTextSaveOptions](./delimitedtextsaveoptions) | Contiene opciones para generar y guardar documentos de hoja de cálculo basados en texto (CSV, basados en tabulaciones, etc.), que utilizan un separador (delimitador) |
| [EbookEditOptions](./ebookeditoptions) | Permite especificar y ajustar opciones personalizadas para editar documentos de libros electrónicos en todos los formatos compatibles: ePub, MOBI y AZW3. |
| [EbookSaveOptions](./ebooksaveoptions) | Permite especificar opciones personalizadas para generar y guardar el documento en todos los formatos de libro electrónico compatibles: ePub, MOBI y AZW3. |
| [EmailEditOptions](./emaileditoptions) | Permite especificar opciones personalizadas para editar documentos en los diferentes formatos de correo electrónico (email) |
| [EmailSaveOptions](./emailsaveoptions) | Permite especificar opciones personalizadas para generar y guardar documentos de correo electrónico (email) |
| [FixedLayoutEditOptionsBase](./fixedlayouteditoptionsbase) | Clase abstracta base para las opciones de todos los documentos de formatos de diseño fijo como PDF y XPS |
| [HtmlSaveOptions](./htmlsaveoptions) | Permite especificar opciones personalizadas para guardar la instancia de [`EditableDocument`](../groupdocs.editor/editabledocument) en formato HTML |
| [MarkdownEditOptions](./markdowneditoptions) | Permite especificar opciones personalizadas para editar documentos en formato Markdown (MD) |
| [MarkdownImageLoadArgs](./markdownimageloadargs) | Proporciona datos para el evento ProcessImage. |
| [MarkdownSaveOptions](./markdownsaveoptions) | Permite especificar opciones personalizadas para generar y guardar documentos Markdown |
| [MhtmlSaveOptions](./mhtmlsaveoptions) | Permite especificar opciones personalizadas para generar y guardar los documentos MHTML (encapsulación MIME de documentos HTML agregados) |
| [PdfEditOptions](./pdfeditoptions) | Permite especificar opciones personalizadas para editar documentos PDF |
| [PdfLoadOptions](./pdfloadoptions) | Contiene opciones para cargar documentos PDF en la clase Editor |
| [PdfSaveOptions](./pdfsaveoptions) | Permite especificar opciones personalizadas para generar y guardar documentos PDF (Formato de Documento Portátil) |
| [PresentationEditOptions](./presentationeditoptions) | Permite especificar opciones personalizadas para editar documentos de todos los formatos de Presentación (compatibles con PowerPoint) soportados |
| [PresentationLoadOptions](./presentationloadoptions) | Permite especificar opciones personalizadas para cargar documentos de todos los formatos de Presentación soportados, como PPT(X), PPTM, PPS(X), etc. |
| [PresentationSaveOptions](./presentationsaveoptions) | Permite especificar opciones personalizadas para generar y guardar documentos de Presentación (compatibles con PowerPoint) |
| [SpreadsheetEditOptions](./spreadsheeteditoptions) | Permite especificar opciones personalizadas para editar documentos de todos los formatos de Hoja de cálculo (compatibles con Excel) soportados |
| [SpreadsheetLoadOptions](./spreadsheetloadoptions) | Contiene opciones para cargar documentos binarios de Hoja de cálculo (Cells, compatibles con Excel) como XLS(X), ODS, etc., en la clase Editor |
| [SpreadsheetSaveOptions](./spreadsheetsaveoptions) | Permite especificar opciones personalizadas para generar y guardar documentos de Hoja de cálculo (compatibles con Excel) |
| [TextEditOptions](./texteditoptions) | Permite especificar opciones personalizadas para cargar documentos de texto plano (TXT) |
| [TextSaveOptions](./textsaveoptions) | Permite especificar opciones personalizadas para generar y guardar documentos de texto plano (TXT) |
| [WebFont](./webfont) | Representa una configuración de fuente para la web |
| [WordProcessingEditOptions](./wordprocessingeditoptions) | Permite especificar opciones personalizadas para editar documentos de todos los formatos compatibles de procesamiento de texto (compatibles con Words) como DOC(X), RTF, ODT, etc. |
| [WordProcessingLoadOptions](./wordprocessingloadoptions) | Contiene opciones para cargar documentos de procesamiento de texto (compatibles con Word) como DOC(X), RTF, ODT, etc. en la clase Editor |
| [WordProcessingProtection](./wordprocessingprotection) | Encapsula opciones de protección de documento para el documento de procesamiento de texto, que se genera a partir de HTML |
| [WordProcessingSaveOptions](./wordprocessingsaveoptions) | Permite especificar opciones personalizadas para generar y guardar documentos compatibles con procesamiento de texto después de haber sido editados |
| [WorksheetProtection](./worksheetprotection) | Encapsula opciones de protección de hoja de cálculo, que permiten proteger una hoja de cálculo en el documento de hoja de cálculo de salida contra modificaciones de tipo especificado con una contraseña especificada. |
| [XmlEditOptions](./xmleditoptions) | Permite especificar opciones personalizadas para editar documentos XML (eXtensible Markup Language) y convertirlos a HTML |
| [XmlFormatOptions](./xmlformatoptions) | Contiene opciones que permiten ajustar el formato del documento XML cuando se representa como HTML |
| [XmlHighlightOptions](./xmlhighlightoptions) | Contiene opciones que permiten personalizar el resaltado XML durante la conversión de XML a HTML |
| [XpsSaveOptions](./xpssaveoptions) | Permite especificar opciones personalizadas para generar y guardar documentos XPS (XML Paper Specifications) |
## Structures

| Estructura | Descripción |
| --- | --- |
| [PageRange](./pagerange) | Encapsula un rango de páginas, que puede tener límites abiertos o cerrados. Por defecto es "totalmente abierto" - incluye todas las páginas existentes. La numeración de páginas comienza en 1, no en 0. |
## Interfaces

| Interfaz | Descripción |
| --- | --- |
| [IEditOptions](./ieditoptions) | Interfaz común para todas las opciones, que son responsables de las conversiones de documento a HTML. No declara miembros. |
| [IHtmlSavingCallback](./ihtmlsavingcallback) | Interfaz que se utiliza al guardar al formato HTML y que debe ser implementada por el usuario final para guardar el recurso proporcionado y devolver un enlace al mismo |
| [ILoadOptions](./iloadoptions) | Interfaz común para todas las clases de opciones, responsable de cargar documentos de diferentes formatos de tipo |
| [IMarkdownImageLoadCallback](./imarkdownimageloadcallback) | Implemente esta interfaz si desea controlar cómo GroupDocs.Editor carga imágenes al cargar el archivo en formato Markdown |
| [ISaveOptions](./isaveoptions) | Interfaz para todas las opciones de guardado de todos los tipos de documentos. No declara miembros. |
## Enumeración

| Enumeración | Descripción |
| --- | --- |
| [FontEmbeddingOptions](./fontembeddingoptions) | Las opciones de incrustación de fuentes controlan qué recursos de fuentes deben incrustarse en el documento de salida de procesamiento de texto o PDF |
| [FontExtractionOptions](./fontextractionoptions) | Las opciones de extracción de fuentes controlan qué fuentes deben extraerse y de dónde |
| [MailMessageOutput](./mailmessageoutput) | Controla qué partes del mensaje de correo deben entregarse al procesamiento de salida |
| [MarkdownImageLoadingAction](./markdownimageloadingaction) | Define el modo de carga de imágenes al abrir para editar el archivo en formato Markdown |
| [MarkdownTableContentAlignment](./markdowntablecontentalignment) | Permite especificar la alineación del contenido de la tabla que se usará al exportar al formato Markdown |
| [PdfCompliance](./pdfcompliance) | Especifica el nivel de cumplimiento de los estándares PDF |
| [TextDirection](./textdirection) | Representa 3 variantes posibles de cómo tratar la dirección del texto en los documentos de texto plano |
| [TextLeadingSpacesOptions](./textleadingspacesoptions) | Contiene opciones disponibles para el manejo de espacios iniciales al abrir un documento de texto plano (TXT) |
| [TextTrailingSpacesOptions](./texttrailingspacesoptions) | Contiene opciones disponibles para el manejo de espacios finales al abrir un documento de texto plano (TXT) |
| [WordProcessingProtectionType](./wordprocessingprotectiontype) | Representa todos los tipos de protección disponibles del documento WordProcessing |
| [WorksheetProtectionType](./worksheetprotectiontype) | Representa los tipos de protección de la hoja de cálculo (pestaña) |

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.editor.dll -->
