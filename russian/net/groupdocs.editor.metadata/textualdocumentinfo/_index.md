---
title: "TextualDocumentInfo"
second_title: "GroupDocs.Editor для .NET справочник API"
description: "Представляет метаданные одного текстового документа, такого как XML, HTML или обычный текст TXT"
type: docs
weight: 780
url: /ru/net/groupdocs.editor.metadata/textualdocumentinfo/
---
## TextualDocumentInfo structure

Представляет метаданные одного текстового документа, например XML, HTML или обычного текста (TXT)

```csharp
public struct TextualDocumentInfo : IDocumentInfo
```

## Свойства

| Имя | Описание |
| --- | --- |
| [Encoding](../../groupdocs.editor.metadata/textualdocumentinfo/encoding) { get; } | Возвращает обнаруженную предполагаемую кодировку текстового документа |
| [Format](../../groupdocs.editor.metadata/textualdocumentinfo/format) { get; } | Возвращает формат этого текстового документа. Может быть не на 100% точным в некоторых случаях. |
| [IsEncrypted](../../groupdocs.editor.metadata/textualdocumentinfo/isencrypted) { get; } | Всегда возвращает ``false``, так как текстовые документы нельзя зашифровать |
| [PageCount](../../groupdocs.editor.metadata/textualdocumentinfo/pagecount) { get; } | Всегда возвращает 1 |
| [Size](../../groupdocs.editor.metadata/textualdocumentinfo/size) { get; } | Возвращает размер в байтах (а не количество символов) этого текстового документа |

### См. также

* interface [IDocumentInfo](../idocumentinfo)
* namespace [GroupDocs.Editor.Metadata](../../groupdocs.editor.metadata)
* assembly [GroupDocs.Editor](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.editor.dll -->
