---
title: FixedLayoutFormats
second_title: Справочник по API GroupDocs.Editor для .NET
description: Инкапсулирует все форматы с фиксированным макетом также известные как фиксированные страницы включая PDF и XPS не включая растровые изображения
type: docs
weight: 80
url: /ru/net/groupdocs.editor.formats/fixedlayoutformats/
---
## FixedLayoutFormats structure

Инкапсулирует все форматы с фиксированным макетом (также известные как «фиксированные страницы»), включая PDF и XPS (не включая растровые изображения)

```csharp
public struct FixedLayoutFormats : IDocumentFormat, IEquatable<FixedLayoutFormats>
```

## Характеристики

| Имя | Описание |
| --- | --- |
| [Extension](../../groupdocs.editor.formats/fixedlayoutformats/extension) { get; } | Возвращает расширение (без начального символа точки) этого формата фиксированного макета в нижнем регистре |
| [Mime](../../groupdocs.editor.formats/fixedlayoutformats/mime) { get; } | Возвращает код MIME для этого формата |
| [Name](../../groupdocs.editor.formats/fixedlayoutformats/name) { get; } | Возвращает формальное полное имя этого фиксированного макета format |

## Методы

| Имя | Описание |
| --- | --- |
| static [FromExtension](../../groupdocs.editor.formats/fixedlayoutformats/fromextension)(string) | Возвращает экземпляр[`FixedLayoutFormats`](../fixedlayoutformats)структура, связанная с указанным расширением имени файла, или выдает исключение, если расширение не может быть правильно проанализировано |
| [Equals](../../groupdocs.editor.formats/fixedlayoutformats/equals#equals)(FixedLayoutFormats) | Определяет, равен ли этот экземпляр другому указанному FixedLayoutFormats instance |
| [Equals](../../groupdocs.editor.formats/fixedlayoutformats/equals#equals_1)(IDocumentFormat) | Определяет, равен ли этот экземпляр другому указанному IDocumentFormat instance |
| override [Equals](../../groupdocs.editor.formats/fixedlayoutformats/equals#equals_2)(object) | Определяет, равен ли этот экземпляр другому указанному объекту, предположительно упакованному FixedLayoutFormats |
| override [GetHashCode](../../groupdocs.editor.formats/fixedlayoutformats/gethashcode)() | Возвращает хеш-код, неизменяемый для данного экземпляра |
| override [ToString](../../groupdocs.editor.formats/fixedlayoutformats/tostring)() | Возвращает имя этого конкретного формата, аналогично свойству «Имя» |
| [operator ==](../../groupdocs.editor.formats/fixedlayoutformats/op_equality) | Проверяет два заданных экземпляра FixedLayoutFormats на равенство |
| [explicit operator](../../groupdocs.editor.formats/fixedlayoutformats/op_explicit#op_explicit) | Возвращает значение байта из базового поля указанного FixedLayoutFormats instance (2 operators) |
| [operator !=](../../groupdocs.editor.formats/fixedlayoutformats/op_inequality) | Проверяет два заданных экземпляра FixedLayoutFormats на неравенство |

## Поля

| Имя | Описание |
| --- | --- |
| static readonly [Pdf](../../groupdocs.editor.formats/fixedlayoutformats/pdf) | Portable Document Format (PDF) — это тип документа, созданный Adobe еще в 1990-х годах. Цель этого формата файла состояла в том, чтобы ввести стандарт для представления документов и других справочных материалов в формате, который не зависит от прикладного программного обеспечения, аппаратного обеспечения, а также операционной системы. Узнайте больше об этом формате файла[здесь](https://docs.fileformat.com/pdf/) . |
| static readonly [Xps](../../groupdocs.editor.formats/fixedlayoutformats/xps) | Файл XPS представляет собой файлы макета страницы, основанные на спецификациях XML Paper, созданных Microsoft. Он был разработан в качестве замены формата файла EMF и похож на формат файла PDF, но использует XML в макете, внешнем виде и информации о печати документа. Узнайте больше об этом формате файла[здесь](https://docs.fileformat.com/page-description-language/xps/) . |
| static readonly [All](../../groupdocs.editor.formats/fixedlayoutformats/all) | Возвращает внутренний класс, который предоставляет перечисляемые возможности по всем существующим форматам с фиксированным макетом |

## Другие члены

| Имя | Описание |
| --- | --- |
| class [AllEnumerable](fixedlayoutformats.allenumerable) | Реализует универсальный интерфейс IEnumerable, который включает возможность foreach для FixedLayoutFormats type |

### Примечания

Различные приложения для просмотра или публикации документов позволяют пользователям открывать (Adobe Acrobat, XPS Viewer) и иногда редактировать (Adobe InDesign) документы определенных форматов. Эти приложения обычно создают документы в так называемом формате «фиксированной страницы». Такой формат документа точно описывает, где на каждой странице размещается содержимое документа. Внутри формат PDF или XPS содержит описание каждой страницы, а также инструкции по рисованию, определяющие расположение содержимого на странице. Это похоже на форматы изображений, описывающие, где содержимое отображается в растровой или векторной форме.

### Смотрите также

* interface [IDocumentFormat](../idocumentformat)
* пространство имен [GroupDocs.Editor.Formats](../../groupdocs.editor.formats)
* сборка [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
