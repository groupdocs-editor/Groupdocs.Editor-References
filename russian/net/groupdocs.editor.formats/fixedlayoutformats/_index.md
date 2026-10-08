---
title: "FixedLayoutFormats"
second_title: "GroupDocs.Editor для .NET справочник API"
description: "Представляет форматы документов фиксированного макета и фиксированной страницы, такие как PDF, исключая растровые форматы изображений."
type: docs
weight: 100
url: /ru/net/groupdocs.editor.formats/fixedlayoutformats/
---
## FixedLayoutFormats class

Представляет форматы документов с фиксированным макетом (фиксированная страница), такие как PDF, за исключением растровых форматов изображений.

```csharp
public class FixedLayoutFormats : DocumentFormatBase
```

## Свойства

| Имя | Описание |
| --- | --- |
| [Extension](../../groupdocs.editor.formats.abstraction/documentformatbase/extension) { get; } | Возвращает расширение файла формата документа. |
| [FormatFamily](../../groupdocs.editor.formats.abstraction/documentformatbase/formatfamily) { get; } | Возвращает семейство форматов, к которому относится формат документа. |
| [Id](../../groupdocs.editor.formats.abstraction/formatfamilybase/id) { get; } | Возвращает уникальный идентификатор семейства форматов. |
| [Mime](../../groupdocs.editor.formats.abstraction/documentformatbase/mime) { get; } | Возвращает MIME‑тип формата документа. |
| [Name](../../groupdocs.editor.formats.abstraction/formatfamilybase/name) { get; } | Возвращает название семейства форматов. |
| static [All](../../groupdocs.editor.formats/fixedlayoutformats/all) { get; } | Получает все доступные экземпляры [`FixedLayoutFormats`](../fixedlayoutformats). |

## Методы

| Имя | Описание |
| --- | --- |
| static [FromExtension](../../groupdocs.editor.formats/fixedlayoutformats/fromextension)(string) | Возвращает экземпляр [`FixedLayoutFormats`](../fixedlayoutformats), соответствующий указанному расширению файла. |
| [Equals](../../groupdocs.editor.formats.abstraction/formatfamilybase/equals)(FormatFamilyBase) | Определяет, равен ли данный экземпляр указанному экземпляру [`FormatFamilyBase`](../../groupdocs.editor.formats.abstraction/formatfamilybase). |
| [Equals](../../groupdocs.editor.formats.abstraction/documentformatbase/equals)(IDocumentFormat) | Определяет, равен ли данный экземпляр указанному экземпляру [`IDocumentFormat`](../../groupdocs.editor.formats.abstraction/idocumentformat). |
| override [Equals](../../groupdocs.editor.formats.abstraction/documentformatbase/equals)(object) | Определяет, равен ли данный экземпляр указанному экземпляру [`DocumentFormatBase`](../../groupdocs.editor.formats.abstraction/documentformatbase). |
| override [GetHashCode](../../groupdocs.editor.formats.abstraction/documentformatbase/gethashcode)() | Возвращает хеш‑код текущего объекта. |
| override [ToString](../../groupdocs.editor.formats.abstraction/formatfamilybase/tostring)() | Возвращает строку, представляющую текущий объект. |
| [explicit operator](../../groupdocs.editor.formats/fixedlayoutformats/op_explicit) | Явно преобразует строку расширения файла в экземпляр [`FixedLayoutFormats`](../fixedlayoutformats). |

## Поля

| Имя | Описание |
| --- | --- |
| static readonly [Pdf](../../groupdocs.editor.formats/fixedlayoutformats/pdf) | Portable Document Format (PDF), разработанный Adobe, обеспечивает стандартизированное представление документов, независимое от программного обеспечения, аппаратного обеспечения и операционных систем. Для получения дополнительной информации см.: [PDF file format](https://docs.fileformat.com/pdf/). |

### Замечания

Форматы фиксированного макета точно определяют размещение и отображение содержимого на каждой странице. Широко используются в приложениях для просмотра, публикации или редактирования документов, таких как Adobe Acrobat и Adobe InDesign. Эти форматы внутренне задают макеты страниц и позиционирование контента с помощью векторной графики и текстовых инструкций.

### См. также

* class [DocumentFormatBase](../../groupdocs.editor.formats.abstraction/documentformatbase)
* namespace [GroupDocs.Editor.Formats](../../groupdocs.editor.formats)
* assembly [GroupDocs.Editor](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.editor.dll -->
