---
title: "ExtractOnlyUsedFont"
second_title: "GroupDocs.Editor для .NET справочник API"
description: "Получает или задаёт значение, указывающее, извлекать ли только ресурсы шрифтов, используемые в текстовом содержимом документа."
type: docs
weight: 40
url: /ru/net/groupdocs.editor.options/wordprocessingeditoptions/extractonlyusedfont/
---
## WordProcessingEditOptions.ExtractOnlyUsedFont property

Получает или задаёт значение, указывающее, извлекать ли только ресурсы шрифтов, используемые в текстовом содержимом документа.

```csharp
public bool ExtractOnlyUsedFont { get; set; }
```

### Property Value

`true` если необходимо извлекать только те ресурсы шрифтов, которые используются в текстовом содержимом документа; иначе `false`. Значение по умолчанию — `false`.

### Замечания

Не все шрифты, используемые в документе WordProcessing, применяются напрямую (к какому‑то тексту) на 100 %. Может возникнуть ситуация, когда шрифт упоминается в документе и даже может быть встроен, но не применяется к какой‑либо части текста. Например, некоторый шрифт может быть привязан к какому‑то стилю, но этот стиль не применяется к любой части текста. Эта опция управляет тем, как обрабатывать такие случаи.

### См. также

* class [WordProcessingEditOptions](../../wordprocessingeditoptions)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.editor.dll -->
