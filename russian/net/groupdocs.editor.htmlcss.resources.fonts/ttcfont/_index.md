---
title: "TtcFont"
second_title: "GroupDocs.Editor для .NET справочник API"
description: "Представляет один шрифт в формате TTC (TrueType Collection)"
type: docs
weight: 380
url: /ru/net/groupdocs.editor.htmlcss.resources.fonts/ttcfont/
---
## TtcFont class

Представляет один шрифт в формате TTC (TrueType Collection)

```csharp
public sealed class TtcFont : FontResourceBase
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [TtcFont](ttcfont#constructor)(string, Stream) | Создаёт новый класс TtcFont из содержимого, представленного в виде потока байтов, и с указанным именем |
| [TtcFont](ttcfont#constructor_1)(string, string) | Создаёт новый класс TtcFont из содержимого, представленного в виде строки, закодированной в base64, и с указанным именем |

## Свойства

| Имя | Описание |
| --- | --- |
| [ByteContent](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/bytecontent) { get; } | Возвращает содержимое этого шрифта в виде потока байтов |
| [FilenameWithExtension](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/filenamewithextension) { get; } | Возвращает корректное имя файла этого ресурса шрифта, которое состоит из имени и расширения. Теоретически может отличаться от имени. |
| [FontsNumber](../../groupdocs.editor.htmlcss.resources.fonts/ttcfont/fontsnumber) { get; } | Количество шрифтов в этом TTC |
| [HasDsigTable](../../groupdocs.editor.htmlcss.resources.fonts/ttcfont/hasdsigtable) { get; } | Указывает, существует ли таблица DSIG в этом TTC. Таблица DSIG может присутствовать только если у TTC версия заголовка 2.0. |
| [HeaderVersion](../../groupdocs.editor.htmlcss.resources.fonts/ttcfont/headerversion) { get; } | Версия заголовка TTC, может быть "1" или "2" |
| [IsDisposed](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/isdisposed) { get; } | Определяет, освобожден ли этот шрифт или нет |
| [Name](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/name) { get; } | Возвращает имя этого ресурса шрифта. Обычно не содержит расширения файла и теоретически может отличаться от имени файла. |
| [TextContent](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/textcontent) { get; } | Возвращает содержимое этого шрифта в виде строки, закодированной base64. Это значение кэшируется после первого вызова. |
| override [Type](../../groupdocs.editor.htmlcss.resources.fonts/ttcfont/type) { get; } | Возвращает FontType.Ttc |

## Методы

| Имя | Описание |
| --- | --- |
| [Dispose](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/dispose)() | Освобождает этот ресурс шрифта, освобождая его содержимое и делая большинство методов и свойств неработоспособными |
| [Equals](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/equals)(FontResourceBase) | Проверяет данный экземпляр с указанным шрифтовым ресурсом на равенство ссылок |
| [Equals](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/equals)(IHtmlResource) | Проверяет данный экземпляр с указанным HTML‑ресурсом на равенство ссылок |
| [Save](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/save)(string) | Сохраняет этот шрифт в указанный файл |
| static [IsValid](../../groupdocs.editor.htmlcss.resources.fonts/ttcfont/isvalid#isvalid)(Stream) | Проверяет, является ли указанный поток действительным шрифтом TTC |
| static [IsValid](../../groupdocs.editor.htmlcss.resources.fonts/ttcfont/isvalid#isvalid_1)(string) | Проверяет, является ли указанная строка, закодированная base64, действительным шрифтом TTF |

## Поля

| Имя | Описание |
| --- | --- |
| const [RequiredHeaderSize](../../groupdocs.editor.htmlcss.resources.fonts/ttcfont/requiredheadersize) | Размер заголовка TTC (в байтах), необходимый для его проверки |

## События

| Имя | Описание |
| --- | --- |
| event [Disposed](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/disposed) | Событие, которое происходит, когда этот шрифт освобождается |

### Замечания

Смотрите подробнее: https://docs.fileformat.com/font/ttc/

### См. также

* class [FontResourceBase](../fontresourcebase)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Fonts](../../groupdocs.editor.htmlcss.resources.fonts)
* assembly [GroupDocs.Editor](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.editor.dll -->
