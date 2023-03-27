---
title: TextualFormats
second_title: Справочник по API GroupDocs.Editor для .NET
description: Инкапсулирует все текстовые текстовые форматы включая разметку XML HTML и другие. Включает следующие форматы Html./textualformats/html  Txt./textualformats/txt  Xml./textualformats/xml . Md./textualformats/md  Json./textualformats/json .
type: docs
weight: 150
url: /ru/net/groupdocs.editor.formats/textualformats/
---
## TextualFormats structure

Инкапсулирует все текстовые (текстовые) форматы, включая разметку (XML, HTML) и другие. Включает следующие форматы: [`Html`](./html) , [`Txt`](./txt) , [`Xml`](./xml) . [`Md`](./md) , [`Json`](./json) .

```csharp
public struct TextualFormats : IDocumentFormat, IEquatable<TextualFormats>
```

## Характеристики

| Имя | Описание |
| --- | --- |
| [Extension](../../groupdocs.editor.formats/textualformats/extension) { get; } | Возвращает расширение (без начального символа точки) этого текстового формата в нижнем регистре |
| [Mime](../../groupdocs.editor.formats/textualformats/mime) { get; } | Возвращает код MIME для этого формата |
| [Name](../../groupdocs.editor.formats/textualformats/name) { get; } | Возвращает формальное полное имя этого текстового формата |

## Методы

| Имя | Описание |
| --- | --- |
| static [FromExtension](../../groupdocs.editor.formats/textualformats/fromextension)(string) | Возвращает экземпляр[`TextualFormats`](../textualformats) структура, связанная с указанным расширением имени файла, или выдает исключение, если расширение не может быть правильно проанализировано |
| [Equals](../../groupdocs.editor.formats/textualformats/equals#equals)(IDocumentFormat) | Определяет, равен ли этот экземпляр другому указанному IDocumentFormat instance |
| override [Equals](../../groupdocs.editor.formats/textualformats/equals#equals_2)(object) | Определяет, равен ли этот экземпляр другому указанному объекту, который предположительно представляет собой упакованный TextualFormats |
| [Equals](../../groupdocs.editor.formats/textualformats/equals#equals_1)(TextualFormats) | Определяет, равен ли этот экземпляр другому указанному TextualFormats instance |
| override [GetHashCode](../../groupdocs.editor.formats/textualformats/gethashcode)() | Возвращает хеш-код, неизменяемый для данного экземпляра |
| override [ToString](../../groupdocs.editor.formats/textualformats/tostring)() | Возвращает имя этого конкретного формата, аналогично свойству «Имя» |
| [operator ==](../../groupdocs.editor.formats/textualformats/op_equality) | Проверяет два заданных экземпляра TextualFormat на равенство |
| [operator !=](../../groupdocs.editor.formats/textualformats/op_inequality) | Проверяет два заданных экземпляра TextualFormat на неравенство |

## Поля

| Имя | Описание |
| --- | --- |
| static readonly [Chm](../../groupdocs.editor.formats/textualformats/chm) | Скомпилированная HTML-справка Microsoft — это собственный двоичный формат интерактивной справки Microsoft, состоящий из набора HTML-страниц, указателя и других средств навигации. Подробнее об этом формате файла[здесь](https://docs.fileformat.com/web/chm/) . |
| static readonly [Html](../../groupdocs.editor.formats/textualformats/html) | Документ на языке гипертекстовой разметки (HTML) — это расширение для веб-страниц, созданных для отображения в браузерах. Подробнее об этом формате файла[здесь](https://wiki.fileformat.com/web/html) . |
| static readonly [Json](../../groupdocs.editor.formats/textualformats/json) | JSON (JavaScript Object Notation) — это открытый стандартный формат файла для обмена данными, который использует удобочитаемый текст для хранения и передачи данных. Подробнее об этом формате файла[здесь](https://docs.fileformat.com/web/json/) . |
| static readonly [Md](../../groupdocs.editor.formats/textualformats/md) | Markdown — это облегченный язык разметки для создания форматированного текста с помощью текстового редактора. Узнайте больше об этом формате файла[здесь](https://docs.fileformat.com/word-processing/md/) . |
| static readonly [Mhtml](../../groupdocs.editor.formats/textualformats/mhtml) | MIME-инкапсуляция совокупных HTML-документов — это формат архива веб-страницы, используемый для объединения в одном компьютерном файле HTML-кода и сопутствующих ресурсов. Подробнее об этом формате файла[здесь](https://docs.fileformat.com/web/mhtml/) . |
| static readonly [Txt](../../groupdocs.editor.formats/textualformats/txt) | Обычный текстовый документ (TXT) представляет собой текстовый документ, содержащий обычный текст в виде строк. Подробнее об этом формате файла[здесь](https://wiki.fileformat.com/word-processing/txt) . |
| static readonly [Xml](../../groupdocs.editor.formats/textualformats/xml) | Документ на расширяемом языке разметки (XML), похожий на HTML, но отличающийся использованием тегов для определения объектов. Подробнее об этом формате файла[здесь](https://wiki.fileformat.com/web/xml) . |
| static readonly [All](../../groupdocs.editor.formats/textualformats/all) | Возвращает внутренний класс, который предоставляет перечисляемые возможности для всех существующих текстовых форматов. |

## Другие члены

| Имя | Описание |
| --- | --- |
| class [AllEnumerable](textualformats.allenumerable) | Реализует общий интерфейс IEnumerable, который включает возможность foreach для TextualFormats type |

### Смотрите также

* interface [IDocumentFormat](../idocumentformat)
* пространство имен [GroupDocs.Editor.Formats](../../groupdocs.editor.formats)
* сборка [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
