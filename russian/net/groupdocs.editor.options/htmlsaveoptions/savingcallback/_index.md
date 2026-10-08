---
title: "SavingCallback"
second_title: "GroupDocs.Editor для .NET справочник API"
description: "Интерфейс, который должен быть реализован конечным пользователем для сохранения всех внешних HTML‑ресурсов. Это свойство не должно быть null, иначе GroupDocs.Editor выбросит исключение при сохранении EditableDocumentgroupdocs.editor/editabledocument в формат HTML."
type: docs
weight: 50
url: /ru/net/groupdocs.editor.options/htmlsaveoptions/savingcallback/
---
## HtmlSaveOptions.SavingCallback property

Интерфейс, который должен быть реализован конечным пользователем для сохранения всех внешних HTML‑ресурсов. Это свойство **must** не должно быть `null`, иначе GroupDocs.Editor выбросит исключение при сохранении [`EditableDocument`](../../../groupdocs.editor/editabledocument) в формат HTML.

```csharp
public IHtmlSavingCallback SavingCallback { get; set; }
```

### Замечания

Если значение свойства [`EmbedStylesheetsIntoMarkup`](../embedstylesheetsintomarkup) установлено в `true`, все таблицы стилей будут внедрены в HTML‑разметку и поэтому они не будут переданы этому обратному вызову сохранения

### См. также

* interface [IHtmlSavingCallback](../../ihtmlsavingcallback)
* class [HtmlSaveOptions](../../htmlsaveoptions)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.editor.dll -->
