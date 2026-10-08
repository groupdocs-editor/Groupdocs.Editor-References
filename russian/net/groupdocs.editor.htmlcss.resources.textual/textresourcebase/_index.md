---
title: "TextResourceBase"
second_title: "GroupDocs.Editor для .NET справочник API"
description: "Базовый класс для любого поддерживаемого текстового ресурса с содержимым текста и кодировкой"
type: docs
weight: 630
url: /ru/net/groupdocs.editor.htmlcss.resources.textual/textresourcebase/
---
## TextResourceBase class

Базовый класс для любого поддерживаемого текстового ресурса с содержимым текста и кодировкой

```csharp
public abstract class TextResourceBase : IHtmlResource
```

## Свойства

| Имя | Описание |
| --- | --- |
| [ByteContent](../../groupdocs.editor.htmlcss.resources.textual/textresourcebase/bytecontent) { get; } | Возвращает содержимое этого текстового ресурса в виде байтового потока с оригинальной кодировкой |
| [Encoding](../../groupdocs.editor.htmlcss.resources.textual/textresourcebase/encoding) { get; } | Возвращает кодировку этого текстового ресурса. Обычно возвращает UTF-8. |
| [FilenameWithExtension](../../groupdocs.editor.htmlcss.resources.textual/textresourcebase/filenamewithextension) { get; } | Возвращает корректное имя файла этого текстового ресурса, которое состоит из имени и расширения |
| [IsDisposed](../../groupdocs.editor.htmlcss.resources.textual/textresourcebase/isdisposed) { get; } | Определяет, освобождён ли этот текстовый ресурс, или нет |
| [Name](../../groupdocs.editor.htmlcss.resources.textual/textresourcebase/name) { get; } | Возвращает имя этого текстового ресурса без расширения файла |
| [TextContent](../../groupdocs.editor.htmlcss.resources.textual/textresourcebase/textcontent) { get; } | Возвращает содержимое этого текстового ресурса в виде стандартной строки |
| abstract [Type](../../groupdocs.editor.htmlcss.resources.textual/textresourcebase/type) { get; } | В реализации тип должен возвращать информацию о типе текстового ресурса |

## Методы

| Имя | Описание |
| --- | --- |
| [Dispose](../../groupdocs.editor.htmlcss.resources.textual/textresourcebase/dispose)() | Освобождает этот текстовый ресурс, освобождая его содержимое и делая большинство методов и свойств неработоспособными. Допускает многократные вызовы. |
| [Equals](../../groupdocs.editor.htmlcss.resources.textual/textresourcebase/equals#equals)(IHtmlResource) | Проверяет этот экземпляр с указанным на равенство. |
| [Save](../../groupdocs.editor.htmlcss.resources.textual/textresourcebase/save)(string) | Сохраняет этот текстовый ресурс в указанный файл |

## События

| Имя | Описание |
| --- | --- |
| event [Disposed](../../groupdocs.editor.htmlcss.resources.textual/textresourcebase/disposed) | Событие, которое происходит, когда этот текстовый ресурс освобождается |

### См. также

* interface [IHtmlResource](../../groupdocs.editor.htmlcss.resources/ihtmlresource)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Textual](../../groupdocs.editor.htmlcss.resources.textual)
* assembly [GroupDocs.Editor](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.editor.dll -->
