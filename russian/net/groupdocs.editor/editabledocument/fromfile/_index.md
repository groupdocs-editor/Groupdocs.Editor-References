---
title: "FromFile"
second_title: "GroupDocs.Editor для .NET справочник API"
description: "Статическая фабрика, создающая экземпляр EditableDocument из HTML‑файла, указанный путем к самому .html файлу и папкой со связанными ресурсами"
type: docs
weight: 10
url: /ru/net/groupdocs.editor/editabledocument/fromfile/
---
## EditableDocument.FromFile method

Статическая фабрика, создающая экземпляр EditableDocument из HTML‑файла, указанный путем к самому файлу *.html и папкой со связанными ресурсами

```csharp
public static EditableDocument FromFile(string htmlFilePath, string resourceFolderPath)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| htmlFilePath | String | Строка, содержащая полный путь к HTML‑файлу. Не может быть null, должна быть корректным файловым путём, и сам файл должен существовать. |
| resourceFolderPath | String | Необязательный путь к папке с HTML‑ресурсами. Если NULL, некорректен или такая папка не существует, редактор попытается найти эту папку самостоятельно, анализируя разметку HTML. |

### Возвращаемое значение

Новый ненулевой экземпляр EditableDocument

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentException | Путь к HTML‑файлу и/или путь к папке ресурсов недействителен(ы) |
| FileNotFoundException | Указанный HTML‑файл не найден |

### См. также

* class [EditableDocument](../../editabledocument)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.editor.dll -->
