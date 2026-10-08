---
title: "EnablePagination"
second_title: "GroupDocs.Editor для .NET справочник API"
description: "Позволяет включать или отключать разбиение на страницы в результирующем HTML‑документе. По умолчанию отключено false."
type: docs
weight: 30
url: /ru/net/groupdocs.editor.options/ebookeditoptions/enablepagination/
---
## EbookEditOptions.EnablePagination property

Позволяет включать или отключать пагинацию в результирующем HTML‑документе. По умолчанию отключена (`false`).

```csharp
public bool EnablePagination { get; set; }
```

### Замечания

По своей сути большинство форматов электронных книг внутренне являются потоковым форматом, подобным Office Open XML, где содержимое представляет собой единый блок и разбивается на главы, а не на страницы. Однако он содержит некоторую информацию, специфичную для страниц, такую как номера страниц, сноски, колонтитулы и т.д. Некоторые читалки электронных книг разбивают содержимое на страницы, в то время как другие (особенно мобильные) — нет. Эта опция позволяет управлять тем, как содержимое электронной книги должно отображаться в HTML/CSS при редактировании — в плавающем (`false`) или постраничном (`true`) виде.

### См. также

* class [EbookEditOptions](../../ebookeditoptions)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.editor.dll -->
