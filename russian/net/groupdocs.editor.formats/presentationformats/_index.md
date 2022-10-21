---
title: PresentationFormats
second_title: Справочник по API GroupDocs.Editor для .NET
description: Инкапсулирует все форматы презентаций. Включает следующие форматы Odp./presentationformats/odp  Otp./presentationformats/otp  Pot./presentationformats/pot  Potm./presentationformats/potm  Potx./presentationformats/potx  Pps./presentationformats/pps  Ppsm./presentationformats/ppsm  Ppsx./presentationformats/ppsx  Ppt./presentationformats/ppt  Ppt95./presentationformats/ppt95  Pptm./presentationformats/pptm  Pptx./presentationformats/pptx. Подробнее о форматах презентацийздесьhttps//wiki.fileformat.com/presentation .
type: docs
weight: 110
url: /ru/net/groupdocs.editor.formats/presentationformats/
---
## PresentationFormats structure

Инкапсулирует все форматы презентаций. Включает следующие форматы: [`Odp`](./odp) , [`Otp`](./otp) , [`Pot`](./pot) , [`Potm`](./potm) , [`Potx`](./potx) , [`Pps`](./pps) , [`Ppsm`](./ppsm) , [`Ppsx`](./ppsx) , [`Ppt`](./ppt) , [`Ppt95`](./ppt95) , [`Pptm`](./pptm) , [`Pptx`](./pptx). Подробнее о форматах презентаций[здесь](https://wiki.fileformat.com/presentation) .

```csharp
public struct PresentationFormats : IDocumentFormat, IEquatable<PresentationFormats>
```

## Характеристики

| Имя | Описание |
| --- | --- |
| [Extension](../../groupdocs.editor.formats/presentationformats/extension) { get; } | Возвращает расширение (без начального символа точки) этого формата представления в нижнем регистре |
| [Mime](../../groupdocs.editor.formats/presentationformats/mime) { get; } | Возвращает код MIME для этого формата |
| [Name](../../groupdocs.editor.formats/presentationformats/name) { get; } | Возвращает формальное полное имя этого формата презентации |

## Методы

| Имя | Описание |
| --- | --- |
| static [FromExtension](../../groupdocs.editor.formats/presentationformats/fromextension)(string) | Возвращает экземпляр[`PresentationFormats`](../presentationformats)структура, связанная с указанным расширением имени файла, или выдает исключение, если расширение не может быть правильно проанализировано |
| [Equals](../../groupdocs.editor.formats/presentationformats/equals#equals)(IDocumentFormat) | Определяет, равен ли этот экземпляр другому указанному IDocumentFormat instance |
| override [Equals](../../groupdocs.editor.formats/presentationformats/equals#equals_2)(object) | Определяет, равен ли этот экземпляр другому указанному объекту, предположительно упакованному PresentationFormats |
| [Equals](../../groupdocs.editor.formats/presentationformats/equals#equals_1)(PresentationFormats) | Определяет, равен ли этот экземпляр другому указанному PresentationFormats instance |
| override [GetHashCode](../../groupdocs.editor.formats/presentationformats/gethashcode)() | Возвращает хеш-код, неизменяемый для данного экземпляра |
| [operator ==](../../groupdocs.editor.formats/presentationformats/op_equality) | Проверяет два заданных экземпляра PresentationFormats на равенство |
| [operator !=](../../groupdocs.editor.formats/presentationformats/op_inequality) | Проверяет два заданных экземпляра PresentationFormats на неравенство |

## Поля

| Имя | Описание |
| --- | --- |
| static readonly [Odp](../../groupdocs.editor.formats/presentationformats/odp) | Файл презентации OpenDocument (ODP) представляет собой формат файла презентации, используемый OpenOffice.org в стандарте OASISOpen. Узнайте больше об этом формате файла[здесь](https://wiki.fileformat.com/presentation/odp) . |
| static readonly [Otp](../../groupdocs.editor.formats/presentationformats/otp) | Файл шаблона презентации OpenDocument (OTP) представляет собой файлы шаблонов презентаций, созданные приложениями в стандартном формате OASIS OpenDocument. Узнайте больше об этом формате файла[здесь](https://wiki.fileformat.com/presentation/otp) . |
| static readonly [Pot](../../groupdocs.editor.formats/presentationformats/pot) | Файл шаблона презентации Microsoft PowerPoint 97-2003 (POT) представляет собой файлы шаблонов Microsoft PowerPoint, созданные версиями PowerPoint 97-2003. Узнайте больше об этом формате файла[здесь](https://wiki.fileformat.com/presentation/pot) . |
| static readonly [Potm](../../groupdocs.editor.formats/presentationformats/potm) | Microsoft Office Open XML PresentationML Macro-Enabled Template (POTM) — это файлы с поддержкой макросов. Файлы POTM создаются с помощью PowerPoint 2007 или более поздней версии и содержат параметры по умолчанию, которые можно использовать для создания дополнительных файлов презентаций. Подробнее об этом формате файлов[здесь](https://wiki.fileformat.com/presentation/potm) . |
| static readonly [Potx](../../groupdocs.editor.formats/presentationformats/potx) | Файл Microsoft Office Open XML PresentationML Macro-Free Template (POTX) представляет шаблоны презентаций Microsoft PowerPoint, созданные с помощью Microsoft PowerPoint 2007 и более поздних версий. Подробнее об этом формате файла[здесь](https://wiki.fileformat.com/presentation/potx) . |
| static readonly [Pps](../../groupdocs.editor.formats/presentationformats/pps) | Файлы слайд-шоу Microsoft PowerPoint 97-2003 (PPS) создаются с помощью Microsoft PowerPoint для целей слайд-шоу. Чтение и создание файла PPS поддерживается Microsoft PowerPoint 97-2003. Узнайте больше об этом формате файла[здесь](https://wiki.fileformat.com/presentation/pps) . |
| static readonly [Ppsm](../../groupdocs.editor.formats/presentationformats/ppsm) | Файлы слайд-шоу Microsoft Office Open XML PresentationML с поддержкой макросов (PPSM) создаются с помощью Microsoft PowerPoint 2007 или более поздней версии. Подробнее об этом формате файлов[здесь](https://wiki.fileformat.com/presentation/ppsm) . |
| static readonly [Ppsx](../../groupdocs.editor.formats/presentationformats/ppsx) | Файл слайд-шоу Microsoft Office Open XML PresentationML (PPSX) без макросов создается с использованием Microsoft PowerPoint 2007 и более поздних версий для целей слайд-шоу. Подробнее об этом формате файла[здесь](https://wiki.fileformat.com/presentation/ppsx) . |
| static readonly [Ppt](../../groupdocs.editor.formats/presentationformats/ppt) | Презентация PowerPoint (.ppt) представляет собой файл PowerPoint, состоящий из набора слайдов для отображения в виде слайд-шоу. Он указывает формат двоичного файла, используемый Microsoft PowerPoint 97-2003. Узнайте больше об этом формате файла[здесь](https://wiki.fileformat.com/presentation/ppt) . |
| static readonly [Ppt95](../../groupdocs.editor.formats/presentationformats/ppt95) | Презентация Microsoft PowerPoint 95 (PPT) |
| static readonly [Pptm](../../groupdocs.editor.formats/presentationformats/pptm) | Файлы Microsoft Office Open XML PresentationML Macro-Enabled Document (PPTM), созданные с помощью Microsoft PowerPoint 2007 или более поздних версий. Они аналогичны файлам PPTX с той разницей, что боковые не могут выполнять макросы, хотя они могут содержать макросы. Узнайте больше об этом формате файла.[здесь](https://wiki.fileformat.com/presentation/pptm) . |
| static readonly [Pptx](../../groupdocs.editor.formats/presentationformats/pptx) | Презентация PowerPoint Open XML (.pptx) — это файл презентации, созданный с помощью популярного приложения Microsoft PowerPoint. В отличие от предыдущей версии формата файла презентации PPT, которая была двоичной, формат PPTX основан на формате файла презентации Microsoft PowerPoint open XML. Узнайте больше об этом формате файла[здесь](https://wiki.fileformat.com/presentation/pptx) . |
| static readonly [All](../../groupdocs.editor.formats/presentationformats/all) | Возвращает внутренний класс, который предоставляет перечисляемые возможности для всех существующих форматов представления |

## Другие члены

| Имя | Описание |
| --- | --- |
| class [AllEnumerable](presentationformats.allenumerable) | Реализует универсальный интерфейс IEnumerable, который включает возможность foreach для PresentationFormats type |

### Смотрите также

* interface [IDocumentFormat](../idocumentformat)
* пространство имен [GroupDocs.Editor.Formats](../../groupdocs.editor.formats)
* сборка [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
