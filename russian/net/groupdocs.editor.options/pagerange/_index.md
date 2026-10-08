---
title: "PageRange"
second_title: "GroupDocs.Editor для .NET справочник API"
description: "Инкапсулирует один диапазон страниц, который может иметь открытые или закрытые границы. По умолчанию полностью открытый, он включает все существующие страницы. Нумерация страниц начинается с 1, а не с 0."
type: docs
weight: 1030
url: /ru/net/groupdocs.editor.options/pagerange/
---
## PageRange structure

Инкапсулирует один диапазон страниц, который может иметь открытые или закрытые границы. По умолчанию «полностью открытый» — включает все существующие страницы. Нумерация страниц начинается с 1, а не с 0.

```csharp
public struct PageRange : IEquatable<PageRange>
```

## Свойства

| Имя | Описание |
| --- | --- |
| [Count](../../groupdocs.editor.options/pagerange/count) { get; } | Количество страниц в диапазоне. Если 0 — диапазон страниц распространяется до конца документа независимо от количества страниц. |
| [EndNumber](../../groupdocs.editor.options/pagerange/endnumber) { get; } | Эксклюзивный номер конечной страницы, до которой продолжается диапазон и на которой он останавливается исключительно. Если 0 — диапазон распространяется до конца документа. |
| [IsDefault](../../groupdocs.editor.options/pagerange/isdefault) { get; } | Указывает, представляет ли данный экземпляр диапазон страниц по умолчанию «полностью открытый», т.е. все страницы документа (true) или нет (false). |
| [StartNumber](../../groupdocs.editor.options/pagerange/startnumber) { get; } | Включающий номер начальной страницы, с которой начинается диапазон. Если 1 — диапазон начинается с первой страницы документа. |

## Методы

| Имя | Описание |
| --- | --- |
| static [FromBeginningWithCount](../../groupdocs.editor.options/pagerange/frombeginningwithcount)(ushort) | Создаёт диапазон страниц, начинающийся с первой страницы и содержащий указанное количество страниц. |
| static [FromStartPageTillEnd](../../groupdocs.editor.options/pagerange/fromstartpagetillend)(ushort) | Создаёт диапазон страниц, начинающийся с указанного номера страницы и продолжающийся до конца документа. |
| static [FromStartPageTillEndPage](../../groupdocs.editor.options/pagerange/fromstartpagetillendpage)(ushort, ushort) | Создаёт диапазон страниц, начинающийся с указанного номера страницы (включительно) и продолжающийся до указанного номера страницы (исключительно). |
| static [FromStartPageWithCount](../../groupdocs.editor.options/pagerange/fromstartpagewithcount)(ushort, ushort) | Создаёт диапазон страниц, начинающийся с указанного номера страницы и содержащий указанное количество страниц, либо неограниченное количество страниц (до конца). |
| [Equals](../../groupdocs.editor.options/pagerange/equals#equals)(PageRange) | Определяет, равен ли данный экземпляр PageRange указанному. |

## Поля

| Имя | Описание |
| --- | --- |
| static readonly [AllPages](../../groupdocs.editor.options/pagerange/allpages) | Представляет все существующие страницы документа. Значение по умолчанию. |

### Замечания

Неизменяемая структура, которая инкапсулирует диапазон страниц, не связанный с конкретным документом, и может представлять диапазон страниц для любого документа.

### См. также

* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.editor.dll -->
