---
title: GroupDocs.Editor.Options
second_title: Referencia de API de GroupDocs.Editor para .NET
description: El espacio de nombres GroupDocs.Editor.Options proporciona interfaces para cargar y guardar opciones.
type: docs
weight: 150
url: /es/net/groupdocs.editor.options/
---
El espacio de nombres GroupDocs.Editor.Options proporciona interfaces para cargar y guardar opciones.

## Clases

| Clase | Descripción |
| --- | --- |
| [Azw3SaveOptions](./azw3saveoptions) | Permite especificar opciones personalizadas para generar y guardar los libros electrónicos AZW3, también conocido como Kindle Format 8 (KF8) |
| [DelimitedTextEditOptions](./delimitedtexteditoptions) | Opciones para cargar documentos de hoja de cálculo basados en texto (CSV, tabulados, etc.), que utilizan un separador (delimitador) |
| [DelimitedTextSaveOptions](./delimitedtextsaveoptions) | Contiene opciones para generar y guardar documentos de hoja de cálculo basados en texto (CSV, tabulados, etc.), que utilizan un separador (delimitador) |
| [EbookEditOptions](./ebookeditoptions) | Permite especificar y ajustar opciones personalizadas para editar documentos de libros electrónicos en todos los formatos admitidos: ePub, MOBI y AZW3. |
| [EmailEditOptions](./emaileditoptions) | Permite especificar opciones personalizadas para la edición de documentos en los diferentes formatos de correo electrónico (email) |
| [EmailSaveOptions](./emailsaveoptions) | Permite especificar opciones personalizadas para generar y guardar documentos de correo electrónico (email) |
| [EpubSaveOptions](./epubsaveoptions) | Permite especificar opciones personalizadas para generar y guardar los documentos IDPF EPUB (estándar abierto para libros electrónicos creado por el International Digital Publishing Forum) |
| [FixedLayoutEditOptionsBase](./fixedlayouteditoptionsbase) | Clase abstracta base para las opciones de todos los documentos de formatos de diseño fijo como PDF y XPS |
| [MarkdownEditOptions](./markdowneditoptions) | Permite especificar opciones personalizadas para editar documentos en formato Markdown (MD) |
| [MarkdownImageLoadArgs](./markdownimageloadargs) | Proporciona datos para elProcessImage evento. |
| [MarkdownSaveOptions](./markdownsaveoptions) | Permite especificar opciones personalizadas para generar y guardar documentos Markdown |
| [MhtmlSaveOptions](./mhtmlsaveoptions) | Permite especificar opciones personalizadas para generar y guardar los documentos MHTML (encapsulación MIME de documentos HTML agregados) |
| [PdfEditOptions](./pdfeditoptions) | Permite especificar opciones personalizadas para editar documentos PDF |
| [PdfLoadOptions](./pdfloadoptions) | Contiene opciones para cargar documentos PDF en Editor class |
| [PdfSaveOptions](./pdfsaveoptions) | Permite especificar opciones personalizadas para generar y guardar documentos PDF (Portable Document Format) |
| [PresentationEditOptions](./presentationeditoptions) | Permite especificar opciones personalizadas para editar documentos de todos los formatos de presentación compatibles (compatibles con PowerPoint) |
| [PresentationLoadOptions](./presentationloadoptions) | Permite especificar opciones personalizadas para cargar documentos de todos los formatos de presentación compatibles como PPT(X), PPTM, PPS(X), etc. |
| [PresentationSaveOptions](./presentationsaveoptions) | Permite especificar opciones personalizadas para generar y guardar documentos de presentación (compatibles con PowerPoint) |
| [SpreadsheetEditOptions](./spreadsheeteditoptions) | Permite especificar opciones personalizadas para editar documentos de todos los formatos de hoja de cálculo compatibles (compatibles con Excel) |
| [SpreadsheetLoadOptions](./spreadsheetloadoptions) | Contiene opciones para cargar documentos binarios de hojas de cálculo (Celdas, compatibles con Excel) como XLS(X), ODS, etc. en Editor class |
| [SpreadsheetSaveOptions](./spreadsheetsaveoptions) | Permite especificar opciones personalizadas para generar y guardar documentos de hoja de cálculo (compatibles con Excel) |
| [TextEditOptions](./texteditoptions) | Permite especificar opciones personalizadas para cargar documentos de texto sin formato (TXT) |
| [TextSaveOptions](./textsaveoptions) | Permite especificar opciones personalizadas para generar y guardar documentos de texto sin formato (TXT) |
| [WebFont](./webfont) | Representa una configuración de fuente para la web |
| [WordProcessingEditOptions](./wordprocessingeditoptions) | Permite especificar opciones personalizadas para editar documentos de todos los formatos compatibles con WordProcessing (compatibles con Words) como DOC(X), RTF, ODT, etc. |
| [WordProcessingLoadOptions](./wordprocessingloadoptions) | Contiene opciones para cargar documentos de procesamiento de textos (compatibles con Word) como DOC(X), RTF, ODT, etc. en Editor class |
| [WordProcessingProtection](./wordprocessingprotection) | Encapsula las opciones de protección de documentos para el documento de WordProcessing, que se genera a partir de HTML |
| [WordProcessingSaveOptions](./wordprocessingsaveoptions) | Permite especificar opciones personalizadas para generar y guardar documentos compatibles con WordProcessing después de editarlos |
| [WorksheetProtection](./worksheetprotection) | Encapsula las opciones de protección de la hoja de cálculo, que permiten proteger una hoja de cálculo en el documento de hoja de cálculo de salida de la modificación del tipo especificado con una contraseña especificada. |
| [XmlEditOptions](./xmleditoptions) | Permite especificar opciones personalizadas para editar documentos XML (lenguaje de marcado extensible) y convertirlos a HTML |
| [XmlFormatOptions](./xmlformatoptions) | Contiene opciones que permiten ajustar el formato del documento XML, cuando se representa como HTML |
| [XmlHighlightOptions](./xmlhighlightoptions) | Contiene opciones que permiten personalizar el resaltado de XML durante la conversión de XML a HTML |
| [XpsEditOptions](./xpseditoptions) | Permite especificar opciones personalizadas para editar documentos (Especificaciones de papel XML) |
| [XpsSaveOptions](./xpssaveoptions) | Permite especificar opciones personalizadas para generar y guardar documentos XPS (Especificaciones de papel XML) |
## Estructuras

| Estructura | Descripción |
| --- | --- |
| [PageRange](./pagerange) | Encapsula un rango de páginas, que puede tener límites abiertos o cerrados. De forma predeterminada, está "totalmente abierto": incluye todas las páginas existentes. La numeración de páginas comienza desde 1, no desde 0. |
## Interfaces

| Interfaz | Descripción |
| --- | --- |
| [IEditOptions](./ieditoptions) | Interfaz común para todas las opciones, que son responsables de las conversiones de documento a HTML. No declara miembros. |
| [ILoadOptions](./iloadoptions) | Interfaz común para todas las clases de opciones, responsable de cargar documentos de diferentes tipos de formatos |
| [IMarkdownImageLoadCallback](./imarkdownimageloadcallback) | Implemente esta interfaz si desea controlar cómo GroupDocs.Editor carga imágenes al cargar el archivo en formato Markdown |
| [ISaveOptions](./isaveoptions) | Interfaz para todas las opciones de guardado para todos los tipos de documentos. No declara miembros. |
## Enumeración

| Enumeración | Descripción |
| --- | --- |
| [FontEmbeddingOptions](./fontembeddingoptions) | Las opciones de incrustación de fuentes controlan qué recursos de fuentes deben incrustarse en el documento de salida de WordProcessing o PDF |
| [FontExtractionOptions](./fontextractionoptions) | Las opciones de extracción de fuentes controlan qué fuentes deben extraerse y de dónde |
| [MailMessageOutput](./mailmessageoutput) | Controla qué partes del mensaje de correo deben entregarse al procesamiento de salida |
| [MarkdownImageLoadingAction](./markdownimageloadingaction) | Define el modo de carga de la imagen al abrir para editar el archivo en formato Markdown |
| [MarkdownTableContentAlignment](./markdowntablecontentalignment) | Permite especificar la alineación del contenido de la tabla a utilizar al exportar a formato Markdown |
| [PdfCompliance](./pdfcompliance) | Especifica el nivel de cumplimiento de estándares de PDF |
| [WebFont.TextDecorationLine](./webfont.textdecorationline) | Tipos de líneas decorativas que se utilizan en el texto de un elemento, como un subrayado, una superposición o un traspaso. Pueden combinarse entre sí, o ninguno. |
| [TextDirection](./textdirection) | Representa 3 posibles variantes de cómo tratar la dirección del texto en los documentos de texto sin formato |
| [TextLeadingSpacesOptions](./textleadingspacesoptions) | Contiene opciones disponibles para el manejo del espacio inicial durante la apertura de un documento de texto sin formato (TXT) |
| [TextTrailingSpacesOptions](./texttrailingspacesoptions) | Contiene opciones disponibles para el manejo del espacio final durante la apertura de un documento de texto sin formato (TXT) |
| [WordProcessingProtectionType](./wordprocessingprotectiontype) | Representa todos los tipos de protección disponibles del documento de WordProcessing |
| [WorksheetProtectionType](./worksheetprotectiontype) | Representa los tipos de protección de la hoja de cálculo (pestaña) de la hoja de cálculo |

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
