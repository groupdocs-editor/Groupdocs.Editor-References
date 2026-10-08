---
title: "SplitHeadingLevel"
second_title: "GroupDocs.Editor для .NET справочник API"
description: "Указывает максимальный уровень заголовков, при котором следует разбивать eBook‑файл. Значение по умолчанию — 2. Установка значения 0 отключит разбивку, и всё содержимое eBook будет включено в один пакет внутри результирующего файла."
type: docs
weight: 40
url: /ru/net/groupdocs.editor.options/ebooksaveoptions/splitheadinglevel/
---
## EbookSaveOptions.SplitHeadingLevel property

Указывает максимальный уровень заголовков, при котором файл e-Book будет разбит. Значение по умолчанию — `2`. Установка значения `0` отключит разбивку, и всё содержимое e-Book будет включено в один пакет внутри результирующего файла.

```csharp
public int SplitHeadingLevel { get; set; }
```

### Замечания

Когда это свойство установлено в значение от 1 до 9, документ будет разбит на абзацы, отформатированные стилями **Heading 1**, **Heading 2**, **Heading 3** и т.д., до указанного уровня заголовка.

По умолчанию только абзацы **Heading 1** и **Heading 2** вызывают разбивку документа. Установка этого свойства в ноль (или отрицательное значение) полностью отключит разбивку по заголовкам.

### См. также

* class [EbookSaveOptions](../../ebooksaveoptions)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.editor.dll -->
