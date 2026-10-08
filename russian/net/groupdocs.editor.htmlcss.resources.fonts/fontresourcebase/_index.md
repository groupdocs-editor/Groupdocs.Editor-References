---
title: "FontResourceBase"
second_title: "GroupDocs.Editor для .NET справочник API"
description: "Базовый класс для любого поддерживаемого типа шрифта как ресурса для HTML‑документа со всеми его свойствами."
type: docs
weight: 350
url: /ru/net/groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/
---
## FontResourceBase class

Базовый класс для любого поддерживаемого типа шрифта как ресурса для HTML‑документа со всеми его свойствами.

```csharp
public abstract class FontResourceBase : IEquatable<FontResourceBase>, IHtmlResource
```

## Свойства

| Имя | Описание |
| --- | --- |
| [ByteContent](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/bytecontent) { get; } | Возвращает содержимое этого шрифта в виде потока байтов |
| [FilenameWithExtension](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/filenamewithextension) { get; } | Возвращает корректное имя файла этого ресурса шрифта, которое состоит из имени и расширения. Теоретически может отличаться от имени. |
| [IsDisposed](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/isdisposed) { get; } | Определяет, освобожден ли этот шрифт или нет |
| [Name](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/name) { get; } | Возвращает имя этого ресурса шрифта. Обычно не содержит расширения файла и теоретически может отличаться от имени файла. |
| [TextContent](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/textcontent) { get; } | Возвращает содержимое этого шрифта в виде строки, закодированной base64. Это значение кэшируется после первого вызова. |
| abstract [Type](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/type) { get; } | В реализующем типе следует возвращать информацию о типе конкретного ресурса шрифта в виде экземпляра конкретного типа FontType, который инкапсулирует всю типо‑специфическую информацию |

## Методы

| Имя | Описание |
| --- | --- |
| [Dispose](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/dispose)() | Освобождает этот ресурс шрифта, освобождая его содержимое и делая большинство методов и свойств неработоспособными |
| [Equals](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/equals#equals)(FontResourceBase) | Проверяет данный экземпляр с указанным шрифтовым ресурсом на равенство ссылок |
| [Equals](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/equals#equals_1)(IHtmlResource) | Проверяет данный экземпляр с указанным HTML‑ресурсом на равенство ссылок |
| [Save](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/save)(string) | Сохраняет этот шрифт в указанный файл |

## События

| Имя | Описание |
| --- | --- |
| event [Disposed](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/disposed) | Событие, которое происходит, когда этот шрифт освобождается |

### См. также

* interface [IHtmlResource](../../groupdocs.editor.htmlcss.resources/ihtmlresource)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Fonts](../../groupdocs.editor.htmlcss.resources.fonts)
* assembly [GroupDocs.Editor](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.editor.dll -->
