---
title: "SaveOneResource"
second_title: "GroupDocs.Editor для .NET справочник API"
description: "Метод экземпляра, вызываемый во время вызова метода Savegroupdocs.editor/editabledocument/save и который должен быть реализован конечным пользователем для получения и сохранения предоставленного HTML‑ресурса, а затем возврата ссылки на этот ресурс вызывающему."
type: docs
weight: 10
url: /ru/net/groupdocs.editor.options/ihtmlsavingcallback/saveoneresource/
---
## IHtmlSavingCallback.SaveOneResource method

Метод экземпляра, вызываемый во время вызова метода [`Save`](../../../groupdocs.editor/editabledocument/save) и который должен быть реализован конечным пользователем для получения и сохранения предоставленного HTML‑ресурса, а затем возврата ссылки на этот ресурс вызывающему.

```csharp
public string SaveOneResource(IHtmlResource resource)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| ресурс | IHtmlResource | HTML‑ресурс любого типа (изображения и шрифты, возможно таблицы стилей, если они не внедрены в HTML‑разметку), который передаётся GroupDocs.Editor в пользовательскую реализацию этого интерфейса, полученный пользователем, и пользователь может выполнять любые необходимые операции, такие как сохранение, отправка, конвертация и т.д. GroupDocs.Editor никогда не передаст `null` HTML‑ресурс в этот метод. |

### Возвращаемое значение

Ссылка (reference) на ресурс, полученная в параметре *resource*, которую пользователь должен предоставить GroupDocs.Editor, чтобы GroupDocs.Editor вставил эту ссылку в HTML‑разметку.

### Замечания

GroupDocs.Editor ожидает, что пользовательская реализация этого метода не будет бросать исключения во время выполнения. Однако, если исключения возникнут, GroupDocs.Editor запишет значение свойства [`FilenameWithExtension`](../../../groupdocs.editor.htmlcss.resources/ihtmlresource/filenamewithextension) в HTML‑разметку.

### См. также

* interface [IHtmlResource](../../../groupdocs.editor.htmlcss.resources/ihtmlresource)
* interface [IHtmlSavingCallback](../../ihtmlsavingcallback)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.editor.dll -->
