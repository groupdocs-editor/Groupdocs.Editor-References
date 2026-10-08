---
title: "EbookDocumentInfo"
second_title: "GroupDocs.Editor для .NET справочник API"
description: "Представляет метаданные одного eBook‑документа"
type: docs
weight: 710
url: /ru/net/groupdocs.editor.metadata/ebookdocumentinfo/
---
## EbookDocumentInfo structure

Представляет метаданные одного e‑Book документа

```csharp
public struct EbookDocumentInfo : IDocumentInfo, IEquatable<EbookDocumentInfo>
```

## Свойства

| Имя | Описание |
| --- | --- |
| [Format](../../groupdocs.editor.metadata/ebookdocumentinfo/format) { get; } | Возвращает формат этого e-Book |
| [IsEncrypted](../../groupdocs.editor.metadata/ebookdocumentinfo/isencrypted) { get; } | Поскольку e-Book‑документы не могут быть зашифрованы паролем, это свойство всегда возвращает 'false' |
| [PageCount](../../groupdocs.editor.metadata/ebookdocumentinfo/pagecount) { get; } | Возвращает количество страниц в случае MOBI или AZW3 или количество глав в случае ePub. |
| [Size](../../groupdocs.editor.metadata/ebookdocumentinfo/size) { get; } | Возвращает размер в байтах этого eBook-документа |

## Методы

| Имя | Описание |
| --- | --- |
| [Equals](../../groupdocs.editor.metadata/ebookdocumentinfo/equals#equals)(EbookDocumentInfo) | Определяет, равен ли данный экземпляр другому указанному экземпляру EbookDocumentInfo |

### См. также

* interface [IDocumentInfo](../idocumentinfo)
* namespace [GroupDocs.Editor.Metadata](../../groupdocs.editor.metadata)
* assembly [GroupDocs.Editor](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.editor.dll -->
