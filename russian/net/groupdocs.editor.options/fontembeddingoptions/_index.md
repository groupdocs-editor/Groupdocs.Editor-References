---
title: "FontEmbeddingOptions"
second_title: "GroupDocs.Editor для .NET справочник API"
description: "Параметры встраивания шрифтов определяют, какие ресурсы шрифтов должны быть встроены в выходной документ WordProcessing или PDF"
type: docs
weight: 880
url: /ru/net/groupdocs.editor.options/fontembeddingoptions/
---
## FontEmbeddingOptions enumeration

Параметры встраивания шрифтов определяют, какие ресурсы шрифтов должны быть встроены в выходной документ WordProcessing или PDF

```csharp
public enum FontEmbeddingOptions
```

### Значения

| Имя | Значение | Описание |
| --- | --- | --- |
| NotEmbed | `0` | Не встраивать ни один ресурс шрифта ни из EditableDocument, ни из системы. Значение по умолчанию. |
| EmbedAll | `1` | Анализирует содержимое документа из входного EditableDocument, находит все используемые шрифты и встраивает их в выходной документ WordProcessing или PDF. Сначала GroupDocs.Editor берёт шрифты из ресурсов шрифтов внутри EditableDocument. Если их недостаточно или они отсутствуют, то GroupDocs.Editor берёт шрифты из ОС. |
| EmbedWithoutSystem | `2` | То же, что EmbedAll, но исключает те шрифты, которые ОС считает системными. |

### Замечания

Параметры встраивания шрифтов применяются при сохранении документа (из промежуточного EditableDocument в выходной формат WordProcessing или PDF); этот перечислимый тип включён как свойство в WordProcessingSaveOptions и PdfSaveOptions, откуда его следует использовать.

### См. также

* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.editor.dll -->
