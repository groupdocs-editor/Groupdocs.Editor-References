---
title: "Save"
second_title: "GroupDocs.Editor для .NET справочник API"
description: "Сохраняет этот HTML‑документ в файл по указанному пути, где будет храниться разметка HTML, и в сопутствующую папку с ресурсами."
type: docs
weight: 160
url: /ru/net/groupdocs.editor/editabledocument/save/
---
## Save(string) {#save_1}

Сохраняет этот HTML‑документ в файл по указанному пути, где будет храниться разметка HTML, и в сопутствующую папку с ресурсами.

```csharp
public void Save(string htmlFilePath)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| htmlFilePath | String | Полный путь к файлу, где будет храниться разметка HTML. Файл будет создан или перезаписан, если существует. Сопутствующая папка ресурсов будет создана в той же папке, где находится HTML‑файл. |

### См. также

* class [EditableDocument](../../editabledocument)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

---

## Save(string, string) {#save_2}

Сохраняет этот HTML‑документ в файл по указанному пути, где будет храниться разметка HTML, и в сопутствующую папку с ресурсами, расположенную по указанному пути.

```csharp
public void Save(string htmlFilePath, string resourcesFolderPath)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| htmlFilePath | String | Полный путь к файлу, где будет храниться разметка HTML. Не может быть NULL или пустым. Файл будет создан или перезаписан, если существует. |
| resourcesFolderPath | String | Полный путь к сопутствующей папке, где будут храниться все связанные ресурсы. Если NULL или пусто, папка будет создана автоматически в том же каталоге, где находится файл *.html. Если указано и папка не существует, она будет создана. |

### См. также

* class [EditableDocument](../../editabledocument)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

---

## Save(TextWriter, HtmlSaveOptions) {#save}

Сохраняет содержимое этого [`EditableDocument`](../../editabledocument) как HTML‑документ в указанный текстовый писатель, при этом второй параметр options позволяет настроить процесс сохранения и указать обратный вызов сохранения ресурсов.

```csharp
public void Save(TextWriter htmlMarkup, HtmlSaveOptions saveOptions)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| htmlMarkup | TextWriter | Реализация текстового писателя, в который будет записана разметка HTML. Не может быть null. |
| saveOptions | HtmlSaveOptions | Параметры сохранения HTML, которые контролируют процесс сохранения: как хранится разметка HTML (имена тегов, типы кавычек) и как и где будут сохраняться CSS и другие ресурсы, такие как изображения или шрифты. Пользователь должен указать наследника интерфейса в свойстве [`SavingCallback`](../../../groupdocs.editor.options/htmlsaveoptions/savingcallback) для управления тем, как ресурсы должны сохраняться и ссылаться из разметки HTML. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | Любой из указанных аргументов или свойство `SavingCallback` в *saveOptions* равно `null` |

### См. также

* class [HtmlSaveOptions](../../../groupdocs.editor.options/htmlsaveoptions)
* class [EditableDocument](../../editabledocument)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.editor.dll -->
