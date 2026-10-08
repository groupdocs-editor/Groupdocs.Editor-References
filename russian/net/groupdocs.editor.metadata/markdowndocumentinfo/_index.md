---
title: "MarkdownDocumentInfo"
second_title: "GroupDocs.Editor для .NET справочник API"
description: "Представляет метаданные одного Markdown‑документа"
type: docs
weight: 750
url: /ru/net/groupdocs.editor.metadata/markdowndocumentinfo/
---
## MarkdownDocumentInfo structure

Представляет метаданные одного Markdown‑документа

```csharp
public struct MarkdownDocumentInfo : IDocumentInfo, IEquatable<MarkdownDocumentInfo>
```

## Свойства

| Имя | Описание |
| --- | --- |
| [Format](../../groupdocs.editor.metadata/markdowndocumentinfo/format) { get; } | Возвращает формат этого Markdown‑документа — всегда это [`Md`](../../groupdocs.editor.formats/textualformats/md) |
| [IsEncrypted](../../groupdocs.editor.metadata/markdowndocumentinfo/isencrypted) { get; } | Поскольку Markdown‑документы нельзя зашифровать паролем, это свойство всегда возвращает ``false`` |
| [PageCount](../../groupdocs.editor.metadata/markdowndocumentinfo/pagecount) { get; } | Возвращает количество страниц. У Markdown‑документов обычно нет фиксированных страниц и, соответственно, количества страниц, поэтому это число рассчитывается исходя из стандартного размера страницы, установленного как A4 в портретной ориентации. |
| [Size](../../groupdocs.editor.metadata/markdowndocumentinfo/size) { get; } | Возвращает размер в байтах этого Markdown‑документа |

## Методы

| Имя | Описание |
| --- | --- |
| [Equals](../../groupdocs.editor.metadata/markdowndocumentinfo/equals#equals)(MarkdownDocumentInfo) | Определяет, равен ли этот экземпляр другому указанному экземпляру [`MarkdownDocumentInfo`](../markdowndocumentinfo). |

### См. также

* interface [IDocumentInfo](../idocumentinfo)
* namespace [GroupDocs.Editor.Metadata](../../groupdocs.editor.metadata)
* assembly [GroupDocs.Editor](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.editor.dll -->
