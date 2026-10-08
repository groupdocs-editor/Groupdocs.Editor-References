---
title: "Save"
second_title: "GroupDocs.Editor для .NET справочник API"
description: "Преобразует указанный отредактированный документ, представленный в виде экземпляра EditableDocumentgroupdocs.editor/editabledocument, в результирующий документ указанного формата и сохраняет его содержимое в указанный поток."
type: docs
weight: 80
url: /ru/net/groupdocs.editor/editor/save/
---
## Save(EditableDocument, Stream, ISaveOptions) {#save_2}

Преобразует указанный отредактированный документ, представленный в виде экземпляра '[`EditableDocument`](../../editabledocument)', в результирующий документ указанного формата и сохраняет его содержимое в указанный поток.

```csharp
public void Save(EditableDocument inputDocument, Stream outputDocument, ISaveOptions saveOptions)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputDocument | EditableDocument | Версия входного документа, отредактированного в WYSIWYG HTML‑редакторе и хранящегося в виде экземпляра класса '[`EditableDocument`](../../editabledocument)', которая должна быть преобразована в выходной документ некоторого конкретного формата. Не должна быть null или освобождённой. |
| outputDocument | Stream | Выходной поток, в котором будет записано содержимое результирующего документа. Не должен быть null, освобождённым, должен поддерживать запись. |
| saveOptions | ISaveOptions | Параметры сохранения документа, которые определяют формат результирующего документа, а также общие и специфичные для формата параметры сохранения. Не должны быть null. |

### Замечания

**Learn more**

* More about saving document after edit using GroupDocs.Editor: [How to save edited document using GroupDocs.Editor](https://docs.groupdocs.com/display/editornet/Save+document)

### См. также

* class [EditableDocument](../../editabledocument)
* interface [ISaveOptions](../../../groupdocs.editor.options/isaveoptions)
* class [Editor](../../editor)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

---

## Save(EditableDocument, string, ISaveOptions) {#save_4}

Преобразует указанный отредактированный документ, представленный в виде экземпляра '[`EditableDocument`](../../editabledocument)', в результирующий документ указанного формата и сохраняет его содержимое в файл по указанному пути.

```csharp
public void Save(EditableDocument inputDocument, string filePath, ISaveOptions saveOptions)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputDocument | EditableDocument | Версия входного документа, отредактированного в WYSIWYG HTML‑редакторе и хранящегося в виде экземпляра класса '[`EditableDocument`](../../editabledocument)', которая должна быть преобразована в выходной документ некоторого конкретного формата. Не должна быть null или освобождённой. |
| filePath | String | Путь к файлу, в котором будет сохранён выходной документ. Если файл с тем же именем существует, он будет полностью перезаписан. Строка пути не должна быть null, пустой или содержать только пробелы. |
| saveOptions | ISaveOptions | Параметры сохранения документа, которые определяют формат результирующего документа, а также общие и специфичные для формата параметры сохранения. Не должны быть null. |

### Замечания

**Learn more**

* More about saving document after edit using GroupDocs.Editor: [How to save edited document using GroupDocs.Editor](https://docs.groupdocs.com/display/editornet/Save+document)

### См. также

* class [EditableDocument](../../editabledocument)
* interface [ISaveOptions](../../../groupdocs.editor.options/isaveoptions)
* class [Editor](../../editor)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

---

## Save(EditableDocument, string) {#save_3}

Преобразует указанный отредактированный документ, представленный как экземпляр '[`EditableDocument`](../../editabledocument)', в результирующий документ формата, определяемого по расширению имени файла, и сохраняет его содержимое в файл по указанному пути.

```csharp
public void Save(EditableDocument inputDocument, string filePath)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputDocument | EditableDocument | Версия входного документа, отредактированного в WYSIWYG HTML‑редакторе и хранящегося в виде экземпляра класса '[`EditableDocument`](../../editabledocument)', которая должна быть преобразована в выходной документ некоторого конкретного формата. Не должна быть null или освобождённой. |
| filePath | String | Путь к файлу, в котором будет сохранён выходной документ. Если файл с тем же именем существует, он будет полностью перезаписан. Строка пути не должна быть null, пустой или содержать только пробелы. Поскольку параметры сохранения по умолчанию и формат вывода определяются из этого имени файла, у него должно быть корректное расширение. |

### См. также

* class [EditableDocument](../../editabledocument)
* class [Editor](../../editor)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

---

## Save(Stream, WordProcessingSaveOptions) {#save_1}

Преобразует оригинальный документ после изменения (например, [`FormFieldManager`](../formfieldmanager)) в результирующий документ указанного формата и сохраняет его содержимое в предоставленный поток.

```csharp
public Stream Save(Stream outputDocument, WordProcessingSaveOptions saveOptions)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputDocument | Stream | Поток, в который будет сохранён выходной документ. Этот поток должен поддерживать запись и быть позиционированным в начале содержимого документа. Не должен быть null. |
| saveOptions | WordProcessingSaveOptions | Параметры сохранения документа, определяющие формат результирующего документа, а также общие и специфичные для формата параметры сохранения. Не должны быть null. |

### Возвращаемое значение

Поток, содержащий сохранённое содержимое документа.

### Замечания

Если *outputDocument* или *saveOptions* равны null, будет выброшено исключение ArgumentNullException. Если документ для сохранения отсутствует, будет выброшено исключение ArgumentNullException.

Выбрасывается, когда *outputDocument* или *saveOptions* равны null, или когда документ для сохранения отсутствует.**Узнать больше:**

* More about saving documents after modification using GroupDocs.Editor: [How to save documents using GroupDocs.Editor](https://docs.groupdocs.com/display/editornet/Save+document)

### См. также

* class [WordProcessingSaveOptions](../../../groupdocs.editor.options/wordprocessingsaveoptions)
* class [Editor](../../editor)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

---

## Save(Stream) {#save}

Сохраняет текущее содержимое документа в указанный выходной поток.

```csharp
public Stream Save(Stream outputDocument)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputDocument | Stream | Поток, в который будет сохранено содержимое документа. Не может быть null. |

### Возвращаемое значение

Поток с сохранённым содержимым документа.

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | Выбрасывается, когда *outputDocument* равен null или если содержимое документа отсутствует. |

### Замечания

Этот метод копирует содержимое из внутреннего представления документа в предоставленный выходной поток. Исходная позиция потока сохраняется после операции сохранения.

### См. также

* class [Editor](../../editor)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.editor.dll -->
