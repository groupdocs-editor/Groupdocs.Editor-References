---
title: "RecognizeLists"
second_title: "GroupDocs.Editor для .NET справочник API"
description: "Позволяет указать, как распознавать элементы нумерованного списка при импорте документа из простого текстового формата. Значение по умолчанию — true."
type: docs
weight: 60
url: /ru/net/groupdocs.editor.options/texteditoptions/recognizelists/
---
## TextEditOptions.RecognizeLists property

Позволяет указать, как распознавать элементы нумерованного списка при импорте документа из простого текстового формата. Значение по умолчанию — true.

```csharp
public bool RecognizeLists { get; set; }
```

### Замечания

Если эта опция установлена в false, алгоритм распознавания списков обнаруживает абзацы списков, когда номера списков заканчиваются точкой, правой скобкой или символами маркеров (например, "•", "*", "-" или "o"). Если эта опция установлена в true, пробелы также используются в качестве разделителей номеров списков: алгоритм распознавания списков для арабской нумерации (1., 1.1.2.) использует как пробелы, так и символ точки (".").

### См. также

* class [TextEditOptions](../../texteditoptions)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.editor.dll -->
