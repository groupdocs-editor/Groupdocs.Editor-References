---
title: "Mp3Audio"
second_title: "GroupDocs.Editor для .NET справочник API"
description: "Представляет один аудио‑ресурс произвольного формата"
type: docs
weight: 330
url: /ru/net/groupdocs.editor.htmlcss.resources.audio/mp3audio/
---
## Mp3Audio class

Представляет один аудио‑ресурс произвольного формата

```csharp
public sealed class Mp3Audio : IEquatable<Mp3Audio>, IHtmlResource
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [Mp3Audio](mp3audio)(string, Stream) | Создаёт новый объект класса Mp3Audio из MP3‑контента, представленного в виде потока байтов, и с указанным именем |

## Свойства

| Имя | Описание |
| --- | --- |
| [ByteContent](../../groupdocs.editor.htmlcss.resources.audio/mp3audio/bytecontent) { get; } | Возвращает содержимое этого шрифта в виде потока байтов |
| [FilenameWithExtension](../../groupdocs.editor.htmlcss.resources.audio/mp3audio/filenamewithextension) { get; } | Возвращает корректное имя файла этого MP3‑контента, состоящее из имени и расширения. Теоретически может отличаться от имени. |
| [IsDisposed](../../groupdocs.editor.htmlcss.resources.audio/mp3audio/isdisposed) { get; } | Определяет, освобожден ли этот MP3‑контент или нет |
| [Name](../../groupdocs.editor.htmlcss.resources.audio/mp3audio/name) { get; } | Возвращает имя этого MP3‑контента. Обычно не содержит расширения файла и теоретически может отличаться от имени файла. |
| [TextContent](../../groupdocs.editor.htmlcss.resources.audio/mp3audio/textcontent) { get; } | Возвращает содержимое этого MP3‑ресурса в виде строки, закодированной в base64. Это значение кэшируется после первого вызова. |
| [Type](../../groupdocs.editor.htmlcss.resources.audio/mp3audio/type) { get; } | Возвращает AudioType.Mp3 |

## Методы

| Имя | Описание |
| --- | --- |
| [Dispose](../../groupdocs.editor.htmlcss.resources.audio/mp3audio/dispose)() | Освобождает этот MP3‑ресурс, освобождая его содержимое и делая большинство методов и свойств неработоспособными |
| [Equals](../../groupdocs.editor.htmlcss.resources.audio/mp3audio/equals#equals_1)(IHtmlResource) | Проверяет данный экземпляр с указанным HTML‑ресурсом на равенство ссылок |
| [Equals](../../groupdocs.editor.htmlcss.resources.audio/mp3audio/equals#equals)(Mp3Audio) | Проверяет данный экземпляр с указанным шрифтовым ресурсом на равенство ссылок |
| [Save](../../groupdocs.editor.htmlcss.resources.audio/mp3audio/save)(string) | Сохраняет этот MP3‑ресурс в указанный файл |
| static [IsValid](../../groupdocs.editor.htmlcss.resources.audio/mp3audio/isvalid)(Stream) | Проверяет, является ли указанный поток действительным MP3‑контентом |

## События

| Имя | Описание |
| --- | --- |
| event [Disposed](../../groupdocs.editor.htmlcss.resources.audio/mp3audio/disposed) | Событие, которое происходит, когда этот MP3‑контент освобождается |

### См. также

* interface [IHtmlResource](../../groupdocs.editor.htmlcss.resources/ihtmlresource)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Audio](../../groupdocs.editor.htmlcss.resources.audio)
* assembly [GroupDocs.Editor](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.editor.dll -->
