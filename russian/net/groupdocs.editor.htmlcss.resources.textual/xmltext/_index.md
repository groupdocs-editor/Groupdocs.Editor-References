---
title: "XmlText"
second_title: "GroupDocs.Editor для .NET справочник API"
description: "Представляет один текстовый ресурс, который является XML."
type: docs
weight: 650
url: /ru/net/groupdocs.editor.htmlcss.resources.textual/xmltext/
---
## XmlText class

Представляет один текстовый ресурс, который является XML.

```csharp
public sealed class XmlText : TextResourceBase
```

## Свойства

| Имя | Описание |
| --- | --- |
| [ByteContent](../../groupdocs.editor.htmlcss.resources.textual/textresourcebase/bytecontent) { get; } | Возвращает содержимое этого текстового ресурса в виде байтового потока с оригинальной кодировкой |
| [Encoding](../../groupdocs.editor.htmlcss.resources.textual/textresourcebase/encoding) { get; } | Возвращает кодировку этого текстового ресурса. Обычно возвращает UTF-8. |
| [FilenameWithExtension](../../groupdocs.editor.htmlcss.resources.textual/textresourcebase/filenamewithextension) { get; } | Возвращает корректное имя файла этого текстового ресурса, которое состоит из имени и расширения |
| [IsDisposed](../../groupdocs.editor.htmlcss.resources.textual/textresourcebase/isdisposed) { get; } | Определяет, освобождён ли этот текстовый ресурс, или нет |
| [Name](../../groupdocs.editor.htmlcss.resources.textual/textresourcebase/name) { get; } | Возвращает имя этого текстового ресурса без расширения файла |
| [ParsedDocument](../../groupdocs.editor.htmlcss.resources.textual/xmltext/parseddocument) { get; } | Возвращает объект "XmlDocument" из этого XML‑ресурса |
| [TextContent](../../groupdocs.editor.htmlcss.resources.textual/textresourcebase/textcontent) { get; } | Возвращает содержимое этого текстового ресурса в виде стандартной строки |
| override [Type](../../groupdocs.editor.htmlcss.resources.textual/xmltext/type) { get; } | Возвращает TextType.Xml |

## Методы

| Имя | Описание |
| --- | --- |
| [Dispose](../../groupdocs.editor.htmlcss.resources.textual/textresourcebase/dispose)() | Освобождает этот текстовый ресурс, освобождая его содержимое и делая большинство методов и свойств неработоспособными. Допускает многократные вызовы. |
| [Equals](../../groupdocs.editor.htmlcss.resources.textual/textresourcebase/equals)(IHtmlResource) | Проверяет этот экземпляр с указанным на равенство. |
| [Save](../../groupdocs.editor.htmlcss.resources.textual/textresourcebase/save)(string) | Сохраняет этот текстовый ресурс в указанный файл |

## События

| Имя | Описание |
| --- | --- |
| event [Disposed](../../groupdocs.editor.htmlcss.resources.textual/textresourcebase/disposed) | Событие, которое происходит, когда этот текстовый ресурс освобождается |

### См. также

* class [TextResourceBase](../textresourcebase)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Textual](../../groupdocs.editor.htmlcss.resources.textual)
* assembly [GroupDocs.Editor](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.editor.dll -->
