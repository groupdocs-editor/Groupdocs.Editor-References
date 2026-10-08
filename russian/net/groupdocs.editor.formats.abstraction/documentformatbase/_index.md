---
title: "DocumentFormatBase"
second_title: "GroupDocs.Editor для .NET справочник API"
description: "Представляет базовый класс для форматов документов, предоставляющий общую функциональность для экземпляров форматов."
type: docs
weight: 50
url: /ru/net/groupdocs.editor.formats.abstraction/documentformatbase/
---
## DocumentFormatBase class

Представляет базовый класс для форматов документов, предоставляя общую функциональность для экземпляров форматов.

```csharp
public abstract class DocumentFormatBase : FormatFamilyBase, IDocumentFormat
```

## Свойства

| Имя | Описание |
| --- | --- |
| [Extension](../../groupdocs.editor.formats.abstraction/documentformatbase/extension) { get; } | Возвращает расширение файла формата документа. |
| [FormatFamily](../../groupdocs.editor.formats.abstraction/documentformatbase/formatfamily) { get; } | Возвращает семейство форматов, к которому относится формат документа. |
| [Id](../../groupdocs.editor.formats.abstraction/formatfamilybase/id) { get; } | Возвращает уникальный идентификатор семейства форматов. |
| [Mime](../../groupdocs.editor.formats.abstraction/documentformatbase/mime) { get; } | Возвращает MIME‑тип формата документа. |
| [Name](../../groupdocs.editor.formats.abstraction/formatfamilybase/name) { get; } | Возвращает название семейства форматов. |

## Методы

| Имя | Описание |
| --- | --- |
| [Equals](../../groupdocs.editor.formats.abstraction/formatfamilybase/equals)(FormatFamilyBase) | Определяет, равен ли этот экземпляр указанному экземпляру [`FormatFamilyBase`](../formatfamilybase). |
| [Equals](../../groupdocs.editor.formats.abstraction/documentformatbase/equals#equals_1)(IDocumentFormat) | Определяет, равен ли этот экземпляр указанному экземпляру [`IDocumentFormat`](../idocumentformat). |
| override [Equals](../../groupdocs.editor.formats.abstraction/documentformatbase/equals#equals_2)(object) | Определяет, равен ли этот экземпляр указанному экземпляру [`DocumentFormatBase`](../documentformatbase). |
| override [GetHashCode](../../groupdocs.editor.formats.abstraction/documentformatbase/gethashcode)() | Возвращает хеш‑код текущего объекта. |
| override [ToString](../../groupdocs.editor.formats.abstraction/formatfamilybase/tostring)() | Возвращает строку, представляющую текущий объект. |
| static [FromMime&lt;T&gt;](../../groupdocs.editor.formats.abstraction/documentformatbase/frommime)(string) | Получает экземпляр указанного типа *T*, имеющий указанный MIME‑тип. |
| [implicit operator](../../groupdocs.editor.formats.abstraction/documentformatbase/op_implicit) | Неявно преобразует экземпляр [`DocumentFormatBase`](../documentformatbase) в строку. |

### См. также

* class [FormatFamilyBase](../formatfamilybase)
* interface [IDocumentFormat](../idocumentformat)
* namespace [GroupDocs.Editor.Formats.Abstraction](../../groupdocs.editor.formats.abstraction)
* assembly [GroupDocs.Editor](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.editor.dll -->
