---
title: "IHtmlResource"
second_title: "GroupDocs.Editor для .NET справочник API"
description: "Представляет один экземпляр неизвестного HTML‑ресурса растрового или векторного изображения, таблицы стилей, шрифта, текстового ресурса, CSS, XML, аудио и т.д."
type: docs
weight: 430
url: /ru/net/groupdocs.editor.htmlcss.resources/ihtmlresource/
---
## IHtmlResource interface

Представляет один экземпляр неизвестного HTML‑ресурса (растровое или векторное изображение, таблица стилей, шрифт, текстовый ресурс (CSS, XML), аудио и т.д.)

```csharp
public interface IHtmlResource : IAuxDisposable, IEquatable<IHtmlResource>
```

## Свойства

| Имя | Описание |
| --- | --- |
| [ByteContent](../../groupdocs.editor.htmlcss.resources/ihtmlresource/bytecontent) { get; } | Содержимое HTML‑ресурса в виде потока байтов |
| [FilenameWithExtension](../../groupdocs.editor.htmlcss.resources/ihtmlresource/filenamewithextension) { get; } | Корректное имя файла указанного ресурса с соответствующим расширением |
| [Name](../../groupdocs.editor.htmlcss.resources/ihtmlresource/name) { get; } | Имя HTML‑ресурса |
| [TextContent](../../groupdocs.editor.htmlcss.resources/ihtmlresource/textcontent) { get; } | Содержимое HTML‑ресурса в виде строки текста, закодированной в base64, для бинарных ресурсов, или простого текста для текстовых ресурсов |
| [Type](../../groupdocs.editor.htmlcss.resources/ihtmlresource/type) { get; } | Тип HTML‑ресурса |

## Методы

| Имя | Описание |
| --- | --- |
| [Save](../../groupdocs.editor.htmlcss.resources/ihtmlresource/save)(string) | Сохраняет текущий ресурс в указанный файл |

### См. также

* interface [IAuxDisposable](../iauxdisposable)
* namespace [GroupDocs.Editor.HtmlCss.Resources](../../groupdocs.editor.htmlcss.resources)
* assembly [GroupDocs.Editor](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.editor.dll -->
