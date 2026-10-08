---
title: "WordProcessingDocumentInfo"
second_title: "GroupDocs.Editor для .NET справочник API"
description: "Представляет метаданные одного документа обработки текста"
type: docs
weight: 790
url: /ru/net/groupdocs.editor.metadata/wordprocessingdocumentinfo/
---
## WordProcessingDocumentInfo structure

Представляет метаданные одного документа обработки текста

```csharp
public struct WordProcessingDocumentInfo : IDocumentInfo, IEquatable<WordProcessingDocumentInfo>
```

## Свойства

| Имя | Описание |
| --- | --- |
| [Format](../../groupdocs.editor.metadata/wordprocessingdocumentinfo/format) { get; } | Возвращает формат этого документа WordProcessing |
| [IsEncrypted](../../groupdocs.editor.metadata/wordprocessingdocumentinfo/isencrypted) { get; } | Определяет, зашифрован ли этот конкретный документ WordProcessing и требует ли пароль для открытия |
| [PageCount](../../groupdocs.editor.metadata/wordprocessingdocumentinfo/pagecount) { get; } | Возвращает количество страниц |
| [Size](../../groupdocs.editor.metadata/wordprocessingdocumentinfo/size) { get; } | Возвращает размер в байтах этого документа WordProcessing |

## Методы

| Имя | Описание |
| --- | --- |
| [Equals](../../groupdocs.editor.metadata/wordprocessingdocumentinfo/equals#equals)(WordProcessingDocumentInfo) | Определяет, равен ли этот экземпляр другому указанному экземпляру WordProcessingDocumentInfo |
| [GeneratePreview](../../groupdocs.editor.metadata/wordprocessingdocumentinfo/generatepreview)(int) | Создаёт и возвращает предварительный просмотр выбранной страницы в виде SVG‑изображения |

### См. также

* interface [IDocumentInfo](../idocumentinfo)
* namespace [GroupDocs.Editor.Metadata](../../groupdocs.editor.metadata)
* assembly [GroupDocs.Editor](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.editor.dll -->
