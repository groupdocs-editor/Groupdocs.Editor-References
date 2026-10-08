---
title: "PageCount"
second_title: "GroupDocs.Editor для .NET справочник API"
description: "При реализации тип должен возвращать количество страниц или другие аналогичные formatdependent сущности, такие как tabs, slides и т.д. Для тех типов семейства, которые не имеют аналогичного, как обычные текстовые документы или XML, следует возвращать 1."
type: docs
weight: 30
url: /ru/net/groupdocs.editor.metadata/idocumentinfo/pagecount/
---
## IDocumentInfo.PageCount property

В реализующем типе следует возвращать количество (число) страниц или других аналогичных зависящих от формата сущностей (вкладок, слайдов и т.п.). Для семейств типов, которые не имеют аналогов (например, обычные текстовые документы или XML), следует возвращать 1.

```csharp
public int PageCount { get; }
```

### См. также

* interface [IDocumentInfo](../../idocumentinfo)
* namespace [GroupDocs.Editor.Metadata](../../../groupdocs.editor.metadata)
* assembly [GroupDocs.Editor](../../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.editor.dll -->
