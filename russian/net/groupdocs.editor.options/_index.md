---
title: GroupDocs.Editor.Options
second_title: Справочник по API GroupDocs.Editor для .NET
description: Пространство имен GroupDocs.Editor.Options предоставляет интерфейсы для параметров загрузки и сохранения.
type: docs
weight: 130
url: /ru/net/groupdocs.editor.options/
---
Пространство имен GroupDocs.Editor.Options предоставляет интерфейсы для параметров загрузки и сохранения.

## Классы

| Учебный класс | Описание |
| --- | --- |
| [Azw3SaveOptions](./azw3saveoptions) | Позволяет указать пользовательские параметры для создания и сохранения электронных книг AZW3, также известного как Kindle Format 8 (KF8) |
| [DelimitedTextEditOptions](./delimitedtexteditoptions) | Параметры для загрузки текстовых электронных таблиц (CSV, Tab и т. д.), в которых используется разделитель (разделитель) |
| [DelimitedTextSaveOptions](./delimitedtextsaveoptions) | Содержит параметры для создания и сохранения текстовых электронных таблиц (CSV, Tab и т. д.), в которых используется разделитель (разделитель) |
| [EbookEditOptions](./ebookeditoptions) | Позволяет задавать и настраивать пользовательские параметры редактирования документов электронных книг во всех поддерживаемых форматах: ePub, MOBI и AZW3. |
| [EmailEditOptions](./emaileditoptions) | Позволяет указать пользовательские параметры редактирования документов в различных форматах электронной почты (email) |
| [EmailSaveOptions](./emailsaveoptions) | Позволяет указать пользовательские параметры формирования и сохранения документов электронной почты (email) |
| [EpubSaveOptions](./epubsaveoptions) | Позволяет указать пользовательские параметры для создания и сохранения документов IDPF EPUB (открытый стандарт для электронных книг, созданный Международным форумом цифровых публикаций) |
| [FixedLayoutEditOptionsBase](./fixedlayouteditoptionsbase) | Базовый абстрактный класс для параметров всех документов форматов с фиксированным макетом, таких как PDF и XPS |
| [MhtmlSaveOptions](./mhtmlsaveoptions) | Позволяет указать пользовательские параметры для создания и сохранения MHTML (инкапсуляция MIME совокупных документов HTML) document |
| [PdfEditOptions](./pdfeditoptions) | Позволяет указать пользовательские параметры редактирования PDF-документов |
| [PdfLoadOptions](./pdfloadoptions) | Содержит опции для загрузки PDF-документов в редактор class |
| [PdfSaveOptions](./pdfsaveoptions) | Позволяет указать пользовательские параметры для создания и сохранения документов PDF (Portable Document Format) |
| [PresentationEditOptions](./presentationeditoptions) | Позволяет указать пользовательские параметры для редактирования документов всех поддерживаемых форматов презентаций (совместимых с PowerPoint) |
| [PresentationLoadOptions](./presentationloadoptions) | Позволяет указать пользовательские параметры для загрузки документов всех поддерживаемых форматов презентаций, таких как PPT(X), PPTM, PPS(X) и т. д. |
| [PresentationSaveOptions](./presentationsaveoptions) | Позволяет указать пользовательские параметры для создания и сохранения презентационных (совместимых с PowerPoint) документов |
| [SpreadsheetEditOptions](./spreadsheeteditoptions) | Позволяет указать пользовательские параметры для редактирования документов всех поддерживаемых форматов электронных таблиц (совместимых с Excel) |
| [SpreadsheetLoadOptions](./spreadsheetloadoptions) | Содержит параметры для загрузки двоичных электронных таблиц (ячейки, совместимые с Excel) документов, таких как XLS(X), ODS и т. д., в редактор class |
| [SpreadsheetSaveOptions](./spreadsheetsaveoptions) | Позволяет указать пользовательские параметры для создания и сохранения электронных таблиц (совместимых с Excel) документов |
| [TextEditOptions](./texteditoptions) | Позволяет указать пользовательские параметры для загрузки документов в виде простого текста (TXT) |
| [TextSaveOptions](./textsaveoptions) | Позволяет указать пользовательские параметры для создания и сохранения текстовых документов (TXT) |
| [WordProcessingEditOptions](./wordprocessingeditoptions) | Позволяет указать пользовательские параметры для редактирования документов всех поддерживаемых форматов WordProcessing (Words-совместимых), таких как DOC(X), RTF, ODT и т. д. |
| [WordProcessingLoadOptions](./wordprocessingloadoptions) | Содержит параметры для загрузки документов WordProcessing (Word-совместимых), таких как DOC(X), RTF, ODT и т. д., в редактор class |
| [WordProcessingProtection](./wordprocessingprotection) | Инкапсулирует параметры защиты документа WordProcessing, созданного из HTML |
| [WordProcessingSaveOptions](./wordprocessingsaveoptions) | Позволяет указать пользовательские параметры для создания и сохранения документов, совместимых с WordProcessing, после их редактирования |
| [WorksheetProtection](./worksheetprotection) | Инкапсулирует параметры защиты рабочего листа, которые позволяют защитить рабочий лист в выходном документе электронной таблицы от модификации указанного типа с указанным паролем. |
| [XmlEditOptions](./xmleditoptions) | Позволяет указать пользовательские параметры для загрузки документов XML (расширяемый язык разметки) и преобразования их в формат HTML |
| [XmlHighlightOptions](./xmlhighlightoptions) | Содержит параметры, позволяющие настроить подсветку XML при преобразовании XML в HTML |
| [XpsEditOptions](./xpseditoptions) | Позволяет указать пользовательские параметры редактирования (спецификации бумаги XML) документов |
| [XpsSaveOptions](./xpssaveoptions) | Позволяет указать пользовательские параметры для создания и сохранения документов XPS (XML Paper Specifications) |
## Структуры

| Структура | Описание |
| --- | --- |
| [PageRange](./pagerange) | Инкапсулирует один диапазон страниц, который может иметь открытые или закрытые границы. По умолчанию «полностью открыт» — включает все существующие страницы. Нумерация страниц начинается с 1, а не с 0. |
## Интерфейсы

| Интерфейс | Описание |
| --- | --- |
| [IEditOptions](./ieditoptions) | Общий интерфейс для всех опций, отвечающих за преобразование документа в HTML. Объявляет об отсутствии членов. |
| [ILoadOptions](./iloadoptions) | Общий интерфейс для всех классов опционов, отвечающих за загрузку документов разных типов форматов |
| [ISaveOptions](./isaveoptions) | Интерфейс для всех вариантов сохранения для всех типов документов. Объявляет об отсутствии членов. |
## перечисление

| перечисление | Описание |
| --- | --- |
| [FontEmbeddingOptions](./fontembeddingoptions) | Параметры внедрения шрифтов определяют, какие ресурсы шрифтов должны быть встроены в выходной документ WordProcessing или PDF |
| [FontExtractionOptions](./fontextractionoptions) | Параметры извлечения шрифтов определяют, какие шрифты следует извлекать и откуда |
| [MailMessageOutput](./mailmessageoutput) | Управляет тем, какие части почтового сообщения должны быть доставлены в выходную обработку |
| [PdfCompliance](./pdfcompliance) | Указывает уровень соответствия стандартам PDF |
| [TextDirection](./textdirection) | Представляет 3 возможных варианта обработки направления текста в обычных текстовых документах |
| [TextLeadingSpacesOptions](./textleadingspacesoptions) | Содержит доступные параметры для обработки начального пробела при открытии текстового документа (TXT) |
| [TextTrailingSpacesOptions](./texttrailingspacesoptions) | Содержит доступные параметры обработки пробелов в конце при открытии текстового документа (TXT) |
| [WordProcessingProtectionType](./wordprocessingprotectiontype) | Представляет все доступные типы защиты документа WordProcessing |
| [WorksheetProtectionType](./worksheetprotectiontype) | Представляет типы защиты электронной таблицы (вкладки) |

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
