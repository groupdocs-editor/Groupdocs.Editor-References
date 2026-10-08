---
title: "FromMarkupAndResourceFolder"
second_title: "GroupDocs.Editor для .NET справочник API"
description: "Статическая фабрика, создающая экземпляр EditableDocument из указанной разметки HTML и ресурсов, расположенных в папке, путь к которой задан полностью"
type: docs
weight: 30
url: /ru/net/groupdocs.editor/editabledocument/frommarkupandresourcefolder/
---
## EditableDocument.FromMarkupAndResourceFolder method

Статическая фабрика, создающая экземпляр EditableDocument из указанной разметки HTML и из ресурсов, расположенных в папке, указанной полным путём

```csharp
public static EditableDocument FromMarkupAndResourceFolder(string newHtmlContent, 
    string resourceFolderPath)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| newHtmlContent | String | Строка, содержащая необработанную разметку HTML, которую следует разобрать. Не может быть NULL, пустой или недействительной. |
| resourceFolderPath | String | Обязательный путь к папке с ресурсами. Все таблицы стилей, находящиеся в этой папке, будут использованы. Не может быть NULL или пустой строки, и эта папка должна существовать. |

### Возвращаемое значение

Новый ненулевой экземпляр EditableDocument

### Замечания

Эта статическая фабрика полезна, когда содержимое HTML‑документа представлено в виде строки, но все ресурсы находятся в какой‑то папке, и часто ссылки на эти ресурсы в разметке HTML недействительны или отсутствуют. При вызове этого метода он сканирует указанную папку и автоматически применяет все найденные таблицы стилей к документу. Этот метод очень полезен при получении содержимого из разных HTML‑редакторов, которые обычно отрезают метаданные документа и т.п.

### См. также

* class [EditableDocument](../../editabledocument)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.editor.dll -->
