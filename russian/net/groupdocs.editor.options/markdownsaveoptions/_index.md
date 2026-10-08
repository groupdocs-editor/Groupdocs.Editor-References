---
title: "MarkdownSaveOptions"
second_title: "GroupDocs.Editor для .NET справочник API"
description: "Позволяет задавать пользовательские параметры для создания и сохранения документов Markdown"
type: docs
weight: 1000
url: /ru/net/groupdocs.editor.options/markdownsaveoptions/
---
## MarkdownSaveOptions class

Позволяет задавать пользовательские параметры для создания и сохранения документов Markdown

```csharp
public sealed class MarkdownSaveOptions : ISaveOptions
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [MarkdownSaveOptions](markdownsaveoptions)() | Конструктор по умолчанию. |

## Свойства

| Имя | Описание |
| --- | --- |
| [ExportImagesAsBase64](../../groupdocs.editor.options/markdownsaveoptions/exportimagesasbase64) { get; set; } | Указывает, сохраняются ли изображения в формате Base64 в выходном файле. По умолчанию — `false`. |
| [ImagesFolder](../../groupdocs.editor.options/markdownsaveoptions/imagesfolder) { get; set; } | Указывает физическую папку, в которой сохраняются изображения при экспорте документа в формат Markdown. По умолчанию — null. |
| [OptimizeMemoryUsage](../../groupdocs.editor.options/markdownsaveoptions/optimizememoryusage) { get; set; } | Включает механизмы оптимизации памяти при генерации документа из HTML, что ухудшает производительность в обмен на снижение использования памяти. Установка этой опции в `true` может значительно уменьшить потребление памяти при генерации больших документов, но за счёт более медленного времени сохранения. По умолчанию — `false` (оптимизация памяти отключена ради лучшей производительности). |
| [TableContentAlignment](../../groupdocs.editor.options/markdownsaveoptions/tablecontentalignment) { get; set; } | Allow указывает, как выравнивать содержимое в таблицах при экспорте в формат Markdown. Значение по умолчанию — Auto. |

### Замечания

Класс MarkdownSaveOptions должен использоваться пользователем, когда существует экземпляр класса EditableDocument, содержащий отредактированное содержимое документа, и необходимо сохранить это содержимое в новый документ формата Markdown.

### См. также

* interface [ISaveOptions](../isaveoptions)
* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.editor.dll -->
