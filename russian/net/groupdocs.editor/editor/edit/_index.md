---
title: "Edit"
second_title: "GroupDocs.Editor для .NET справочник API"
description: "Открывает ранее загруженный документ для редактирования с использованием указанных параметров, специфичных для формата, создавая и возвращая экземпляр класса EditableDocumentgroupdocs.editor/editabledocument, который, в свою очередь, содержит методы для генерации HTML‑разметки и связанных ресурсов."
type: docs
weight: 60
url: /ru/net/groupdocs.editor/editor/edit/
---
## Edit(IEditOptions) {#edit_1}

Открывает ранее загруженный документ для редактирования с использованием указанных параметров, специфичных для формата, создавая и возвращая экземпляр класса '[`EditableDocument`](../../editabledocument)', который, в свою очередь, содержит методы для генерации HTML‑разметки и связанных ресурсов.

```csharp
public EditableDocument Edit(IEditOptions editOptions)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| editOptions | IEditOptions | Параметры документа, специфичные для формата, которые позволяют настроить процесс конвертации. Может быть NULL — в этом случае GroupDocs.Editor определяет формат ранее загруженного документа и применяет параметры, по умолчанию для этого формата. Не должно конфликтовать с ранее применёнными параметрами загрузки. |

### Возвращаемое значение

Экземпляр класса '[`EditableDocument`](../../editabledocument)', который инкапсулирует весь входной документ со всеми его ресурсами в промежуточном формате. Этот метод, если успешно завершён, никогда не возвращает NULL.

### Замечания

Когда исходный документ загружается в экземпляр 'Editor' через конструктор, этот метод позволяет открыть документ для редактирования, преобразовав его в промежуточный формат, который инкапсулируется в экземпляре класса 'EditableDocument'. '[`EditableDocument`](../../editabledocument)', возвращённый этим методом, содержит все необходимые методы и свойства для создания HTML‑разметки и соответствующих ресурсов (например, изображений, шрифтов и таблиц стилей) во всех необходимых конфигурациях для последующей передачи их в любой WYSIWYG HTML‑редактор. Эта перегрузка получает параметры редактирования, специфичные для семейства форматов. **Learn more**

* More about editing documents using GroupDocs.Editor: [How to edit document using GroupDocs.Editor](https://docs.groupdocs.com/display/editornet/Edit+document)

### См. также

* class [EditableDocument](../../editabledocument)
* interface [IEditOptions](../../../groupdocs.editor.options/ieditoptions)
* class [Editor](../../editor)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

---

## Edit() {#edit}

Открывает ранее загруженный документ для редактирования с использованием параметров по умолчанию, создавая и возвращая экземпляр класса '[`EditableDocument`](../../editabledocument)', который, в свою очередь, содержит методы для создания HTML‑разметки и связанных ресурсов.

```csharp
public EditableDocument Edit()
```

### Возвращаемое значение

Экземпляр класса '[`EditableDocument`](../../editabledocument)', который инкапсулирует весь входной документ со всеми его ресурсами в промежуточном формате. Этот метод, если успешно завершён, никогда не возвращает NULL.

### Замечания

Когда исходный документ загружается в экземпляр 'Editor' через конструктор, этот метод позволяет открыть документ для редактирования, преобразовав его в промежуточный формат, который инкапсулируется в экземпляре класса '[`EditableDocument`](../../editabledocument)'. '[`EditableDocument`](../../editabledocument)', возвращённый этим методом, содержит все необходимые методы и свойства для создания HTML‑разметки и соответствующих ресурсов (например, изображений, шрифтов и таблиц стилей) во всех необходимых конфигурациях для последующей передачи их в любой WYSIWYG HTML‑редактор. Эта перегрузка применяет параметры редактирования, которые являются параметрами по умолчанию для формата, к которому принадлежит входной документ. **Learn more**

* More about editing documents using GroupDocs.Editor: [How to edit document using GroupDocs.Editor](https://docs.groupdocs.com/display/editornet/Edit+document)

### См. также

* class [EditableDocument](../../editabledocument)
* class [Editor](../../editor)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.editor.dll -->
