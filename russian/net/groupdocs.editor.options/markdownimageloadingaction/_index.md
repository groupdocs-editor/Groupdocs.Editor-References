---
title: "MarkdownImageLoadingAction"
second_title: "GroupDocs.Editor для .NET справочник API"
description: "Определяет режим загрузки изображений при открытии файла в формате Markdown для редактирования"
type: docs
weight: 990
url: /ru/net/groupdocs.editor.options/markdownimageloadingaction/
---
## MarkdownImageLoadingAction enumeration

Определяет режим загрузки изображений при открытии файла в формате Markdown для редактирования

```csharp
public enum MarkdownImageLoadingAction
```

### Значения

| Имя | Значение | Описание |
| --- | --- | --- |
| Default | `0` | GroupDocs.Editor загрузит этот ресурс как обычно |
| Skip | `1` | GroupDocs.Editor пропустит загрузку этого изображения |
| UserProvided | `2` | GroupDocs.Editor будет использовать массив байтов, предоставленный пользователем в [`SetData`](../markdownimageloadargs/setdata) в качестве данных изображения |

### См. также

* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.editor.dll -->
