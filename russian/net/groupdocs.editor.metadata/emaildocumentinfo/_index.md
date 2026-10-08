---
title: "EmailDocumentInfo"
second_title: "GroupDocs.Editor для .NET справочник API"
description: "Представляет метаданные одного email‑документа любого поддерживаемого формата электронной почты"
type: docs
weight: 720
url: /ru/net/groupdocs.editor.metadata/emaildocumentinfo/
---
## EmailDocumentInfo structure

Представляет метаданные одного email‑документа любого поддерживаемого формата электронной почты

```csharp
public struct EmailDocumentInfo : IDocumentInfo, IEquatable<EmailDocumentInfo>
```

## Свойства

| Имя | Описание |
| --- | --- |
| [Format](../../groupdocs.editor.metadata/emaildocumentinfo/format) { get; } | Возвращает формат этого email‑документа |
| [IsEncrypted](../../groupdocs.editor.metadata/emaildocumentinfo/isencrypted) { get; } | Поскольку email‑документы не могут быть зашифрованы паролем, это свойство всегда возвращает 'false' |
| [PageCount](../../groupdocs.editor.metadata/emaildocumentinfo/pagecount) { get; } | Всегда возвращает 1, потому что у email‑документов нет постраничного представления |
| [Size](../../groupdocs.editor.metadata/emaildocumentinfo/size) { get; } | Возвращает размер в байтах этого email‑документа |

## Методы

| Имя | Описание |
| --- | --- |
| [Equals](../../groupdocs.editor.metadata/emaildocumentinfo/equals#equals)(EmailDocumentInfo) | Определяет, равен ли этот экземпляр другому указанному экземпляру EmailDocumentInfo |

### См. также

* interface [IDocumentInfo](../idocumentinfo)
* namespace [GroupDocs.Editor.Metadata](../../groupdocs.editor.metadata)
* assembly [GroupDocs.Editor](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.editor.dll -->
