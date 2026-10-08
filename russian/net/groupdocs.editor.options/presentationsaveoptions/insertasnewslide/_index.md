---
title: "InsertAsNewSlide"
second_title: "GroupDocs.Editor для .NET справочник API"
description: "Булевый флаг, указывающий, должна ли отредактированная часть заменять существующий слайд в оригинальной презентации на позиции, указанной свойством SlideNumbergroupdocs.editor.options/presentationsaveoptions/slidenumber, или её следует вставить между существующим слайдом и предыдущим без замены его содержимого. По умолчанию false — существующий слайд будет заменён. Это свойство игнорируется, если значение свойства SlideNumbergroupdocs.editor.options/presentationsaveoptions/slidenumber установлено в 0."
type: docs
weight: 20
url: /ru/net/groupdocs.editor.options/presentationsaveoptions/insertasnewslide/
---
## PresentationSaveOptions.InsertAsNewSlide property

Булевый флаг, указывающий, должна ли отредактированная часть заменять существующий слайд в оригинальной презентации на позиции, указанной свойством [`SlideNumber`](../slidenumber), или её следует вставить между существующим слайдом и предыдущим без замены его содержимого. По умолчанию `false` — существующий слайд будет заменён. Это свойство игнорируется, если значение свойства [`SlideNumber`](../slidenumber) установлено в '0'.

```csharp
public bool InsertAsNewSlide { get; set; }
```

### Замечания

По умолчанию слайд заменяется. Это означает, что если в презентации 5 слайдов, и [`SlideNumber`](../slidenumber)=4, то 4‑й слайд будет заменён новым отредактированным слайдом, при этом общее количество слайдов в презентации (5) останется без изменений. Однако если значение этого свойства установить в true, новый отредактированный слайд будет вставлен как 4‑й, а все последующие слайды сместятся к концу: \"old\" 4‑й слайд станет 5‑м, а 5‑й — 6‑м, и общее количество слайдов в презентации увеличится на один и станет равным 6.

### См. также

* class [PresentationSaveOptions](../../presentationsaveoptions)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.editor.dll -->
