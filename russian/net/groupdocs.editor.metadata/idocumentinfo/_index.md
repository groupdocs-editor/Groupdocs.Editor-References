---
title: "IDocumentInfo"
second_title: "GroupDocs.Editor для .NET справочник API"
description: "Общий интерфейс для всех обёрток метаданных файлов"
type: docs
weight: 740
url: /ru/net/groupdocs.editor.metadata/idocumentinfo/
---
## IDocumentInfo interface

Общий интерфейс для всех обёрток метаданных файлов

```csharp
public interface IDocumentInfo
```

## Свойства

| Имя | Описание |
| --- | --- |
| [Format](../../groupdocs.editor.metadata/idocumentinfo/format) { get; } | В реализующем типе следует возвращать формат документа как единственное значение из типа, представляющего одну семью форматов и наследующего интерфейс IDocumentFormat |
| [IsEncrypted](../../groupdocs.editor.metadata/idocumentinfo/isencrypted) { get; } | Указывает, зашифрован ли конкретный файл и требует ли пароль для открытия. Для типов документов, которые нельзя зашифровать (например, все текстовые), всегда должно возвращаться 'false'. |
| [PageCount](../../groupdocs.editor.metadata/idocumentinfo/pagecount) { get; } | В реализующем типе следует возвращать количество (число) страниц или других аналогичных зависящих от формата сущностей (вкладок, слайдов и т.п.). Для семейств типов, которые не имеют аналогов (например, обычные текстовые документы или XML), следует возвращать 1. |
| [Size](../../groupdocs.editor.metadata/idocumentinfo/size) { get; } | Размер документа в байтах |

### См. также

* namespace [GroupDocs.Editor.Metadata](../../groupdocs.editor.metadata)
* assembly [GroupDocs.Editor](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.editor.dll -->
