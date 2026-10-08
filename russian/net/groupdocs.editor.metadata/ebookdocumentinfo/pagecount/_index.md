---
title: "PageCount"
second_title: "GroupDocs.Editor для .NET справочник API"
description: "Возвращает количество страниц в случае MOBI или AZW3 или количество глав в случае ePub."
type: docs
weight: 30
url: /ru/net/groupdocs.editor.metadata/ebookdocumentinfo/pagecount/
---
## EbookDocumentInfo.PageCount property

Возвращает количество страниц в случае MOBI или AZW3 или количество глав в случае ePub.

```csharp
public int PageCount { get; }
```

### Замечания

Документы e-Book обычно не имеют фиксированных страниц и, следовательно, количества страниц. В случае ePub возможно вычислить количество глав. Однако форматы MOBI и AZW3 также не имеют глав, поэтому это число рассчитывается исходя из стандартного размера страницы, установленного на A4 в портретной ориентации.

### См. также

* struct [EbookDocumentInfo](../../ebookdocumentinfo)
* namespace [GroupDocs.Editor.Metadata](../../../groupdocs.editor.metadata)
* assembly [GroupDocs.Editor](../../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.editor.dll -->
