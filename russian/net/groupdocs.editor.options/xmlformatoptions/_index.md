---
title: "XmlFormatOptions"
second_title: "GroupDocs.Editor для .NET справочник API"
description: "Содержит параметры, позволяющие настроить форматирование XML‑документа при его представлении в виде HTML"
type: docs
weight: 1280
url: /ru/net/groupdocs.editor.options/xmlformatoptions/
---
## XmlFormatOptions class

Содержит параметры, позволяющие настроить форматирование XML‑документа при его представлении в виде HTML

```csharp
public sealed class XmlFormatOptions : IEditOptions
```

## Свойства

| Имя | Описание |
| --- | --- |
| [EachAttributeFromNewline](../../groupdocs.editor.options/xmlformatoptions/eachattributefromnewline) { get; set; } | Если включено, каждая пара атрибут‑значение в каждом XML‑элементе будет размещена на новой строке. По умолчанию значение false (отключено) — все пары атрибут‑значение размещаются в одной строке. |
| [IsDefault](../../groupdocs.editor.options/xmlformatoptions/isdefault) { get; } | Указывает, имеет ли данный экземпляр параметров форматирования XML значение по умолчанию |
| [LeafTextNodesOnNewline](../../groupdocs.editor.options/xmlformatoptions/leaftextnodesonnewline) { get; set; } | Если включено, листовые текстовые узлы (текстовое содержимое внутри XML‑элементов, не имеющих дочерних узлов) будут выводиться на новой строке с большим отступом слева. По умолчанию значение false (отключено) — листовые текстовые узлы размещаются в той же строке, что и их родители, без дополнительного отступа. |
| [LeftIndent](../../groupdocs.editor.options/xmlformatoptions/leftindent) { get; set; } | Позволяет задать смещение левого отступа для каждой новой строки. Не может быть безразмерным ненулевым значением. По умолчанию — 10 pt. |

### См. также

* interface [IEditOptions](../ieditoptions)
* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.editor.dll -->
