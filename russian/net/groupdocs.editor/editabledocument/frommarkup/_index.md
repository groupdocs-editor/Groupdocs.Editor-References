---
title: "FromMarkup"
second_title: "GroupDocs.Editor для .NET справочник API"
description: "Статическая фабрика, создающая экземпляр EditableDocumentgroupdocs.editor/editabledocument из указанной разметки HTML"
type: docs
weight: 20
url: /ru/net/groupdocs.editor/editabledocument/frommarkup/
---
## FromMarkup(string) {#frommarkup}

Статическая фабрика, создающая экземпляр [`EditableDocument`](../../editabledocument) из указанной разметки HTML

```csharp
public static EditableDocument FromMarkup(string newHtmlContent)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| newHtmlContent | String | Строка, содержащая необработанную разметку HTML, которую следует разобрать. Не может быть NULL, пустой или недействительной. |

### Возвращаемое значение

Новый ненулевой экземпляр EditableDocument

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentException | Строка с исходной разметкой HTML не может быть null или пустой |

### Замечания

Этот статический метод полезен для создания экземпляра [`EditableDocument`](../../editabledocument) из однострочной разметки HTML, где все ресурсы внедрены в него с помощью base64‑кодирования.

### См. также

* class [EditableDocument](../../editabledocument)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

---

## FromMarkup(string, IEnumerable&lt;IHtmlResource&gt;) {#frommarkup_1}

Статическая фабрика, создающая экземпляр EditableDocument из указанной разметки HTML и набора соответствующих связанных ресурсов

```csharp
public static EditableDocument FromMarkup(string newHtmlContent, 
    IEnumerable<IHtmlResource> resources)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| newHtmlContent | String | Строка, содержащая необработанную разметку HTML, которую следует разобрать. Не может быть NULL, пустой или недействительной. |
| resources | IEnumerable`1 | Коллекция всех ресурсов (изображений, таблиц стилей, шрифтов), которые используются в HTML‑документе, указанном в параметре *newHtmlContent*. Может отсутствовать (NULL или пустая коллекция). |

### Возвращаемое значение

Новый ненулевой экземпляр EditableDocument

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentException | Строка с исходной разметкой HTML не может быть null или пустой |

### См. также

* interface [IHtmlResource](../../../groupdocs.editor.htmlcss.resources/ihtmlresource)
* class [EditableDocument](../../editabledocument)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.editor.dll -->
