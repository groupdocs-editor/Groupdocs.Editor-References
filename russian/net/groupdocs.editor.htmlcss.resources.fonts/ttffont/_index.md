---
title: "TtfFont"
second_title: "GroupDocs.Editor для .NET справочник API"
description: "Представляет один шрифт в формате TTF TrueType Font"
type: docs
weight: 390
url: /ru/net/groupdocs.editor.htmlcss.resources.fonts/ttffont/
---
## TtfFont class

Представляет один шрифт в формате TTF (TrueType Font)

```csharp
public sealed class TtfFont : FontResourceBase
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [TtfFont](ttffont#constructor)(string, Stream) | Создаёт новый класс TtfFont из содержимого, представленного в виде байтового потока, и с указанным именем |
| [TtfFont](ttffont#constructor_1)(string, string) | Создаёт новый класс TtfFont из содержимого, представленного в виде строки, закодированной base64, и с указанным именем |

## Свойства

| Имя | Описание |
| --- | --- |
| [ByteContent](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/bytecontent) { get; } | Возвращает содержимое этого шрифта в виде потока байтов |
| [FilenameWithExtension](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/filenamewithextension) { get; } | Возвращает корректное имя файла этого ресурса шрифта, которое состоит из имени и расширения. Теоретически может отличаться от имени. |
| [IsDisposed](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/isdisposed) { get; } | Определяет, освобожден ли этот шрифт или нет |
| [Name](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/name) { get; } | Возвращает имя этого ресурса шрифта. Обычно не содержит расширения файла и теоретически может отличаться от имени файла. |
| [TextContent](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/textcontent) { get; } | Возвращает содержимое этого шрифта в виде строки, закодированной base64. Это значение кэшируется после первого вызова. |
| override [Type](../../groupdocs.editor.htmlcss.resources.fonts/ttffont/type) { get; } | Возвращает FontType.Ttf |

## Методы

| Имя | Описание |
| --- | --- |
| [Dispose](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/dispose)() | Освобождает этот ресурс шрифта, освобождая его содержимое и делая большинство методов и свойств неработоспособными |
| [Equals](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/equals)(FontResourceBase) | Проверяет данный экземпляр с указанным шрифтовым ресурсом на равенство ссылок |
| [Equals](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/equals)(IHtmlResource) | Проверяет данный экземпляр с указанным HTML‑ресурсом на равенство ссылок |
| [Save](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/save)(string) | Сохраняет этот шрифт в указанный файл |
| static [IsValid](../../groupdocs.editor.htmlcss.resources.fonts/ttffont/isvalid#isvalid)(Stream) | Проверяет, является ли указанный поток действительным шрифтом TTF |
| static [IsValid](../../groupdocs.editor.htmlcss.resources.fonts/ttffont/isvalid#isvalid_1)(string) | Проверяет, является ли указанная строка, закодированная base64, действительным шрифтом TTF |

## Поля

| Имя | Описание |
| --- | --- |
| const [RequiredHeaderSize](../../groupdocs.editor.htmlcss.resources.fonts/ttffont/requiredheadersize) | Размер заголовка TTF (в байтах), необходимый для его проверки |

## События

| Имя | Описание |
| --- | --- |
| event [Disposed](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/disposed) | Событие, которое происходит, когда этот шрифт освобождается |

### См. также

* class [FontResourceBase](../fontresourcebase)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Fonts](../../groupdocs.editor.htmlcss.resources.fonts)
* assembly [GroupDocs.Editor](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.editor.dll -->
