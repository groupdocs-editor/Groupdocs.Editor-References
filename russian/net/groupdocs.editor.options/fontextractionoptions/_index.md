---
title: "FontExtractionOptions"
second_title: "GroupDocs.Editor для .NET справочник API"
description: "Параметры извлечения шрифтов определяют, какие шрифты следует извлечь и откуда"
type: docs
weight: 890
url: /ru/net/groupdocs.editor.options/fontextractionoptions/
---
## FontExtractionOptions enumeration

Параметры извлечения шрифтов определяют, какие шрифты следует извлечь и откуда

```csharp
public enum FontExtractionOptions
```

### Значения

| Имя | Значение | Описание |
| --- | --- | --- |
| NotExtract | `0` | Не извлекает ни один ресурс шрифта ни из документа, ни из системы. Значение по умолчанию. |
| ExtractAllEmbedded | `1` | Извлекает все ресурсы шрифтов, встроенные во входной документ Word, независимо от их типа: пользовательские или системные. |
| ExtractEmbeddedWithoutSystem | `2` | Извлекает только те встроенные ресурсы шрифтов, которые являются пользовательскими (не системными). |
| ExtractAll | `3` | Пытается извлечь все шрифты, используемые во входном документе WordProcessing, включая системные шрифты. |

### См. также

* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.editor.dll -->
