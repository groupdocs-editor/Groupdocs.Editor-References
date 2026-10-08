---
title: "Editor"
second_title: "GroupDocs.Editor для .NET справочник API"
description: "Инициализирует новый экземпляр класса Editorgroupdocs.editor/editor и создает новый пустой документ на основе указанного формата."
type: docs
weight: 10
url: /ru/net/groupdocs.editor/editor/editor/
---
## Editor(DocumentFormatBase) {#constructor}

Инициализирует новый экземпляр класса [`Editor`](../../editor) и создает новый пустой документ на основе указанного формата.

```csharp
public Editor(DocumentFormatBase format)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| формат | DocumentFormatBase | Представляет файловый формат документа, который будет создан. |

### Замечания

**Learn more**

* More about file types supported by GroupDocs.Editor: [Document formats supported by GroupDocs.Editor](https://docs.groupdocs.com/display/editornet/Supported+Document+Formats)
* More about GroupDocs.Editor for .NET features: [Developer Guide](https://docs.groupdocs.com/display/editornet/Developer+Guide)

### Примеры

```csharp
IDocumentFormat format = new WordProcessingFormats.Docx();
using (Editor editor = new Editor(format))
{
    // Используйте экземпляр редактора для редактирования и сохранения документов
}
```

### См. также

* class [DocumentFormatBase](../../../groupdocs.editor.formats.abstraction/documentformatbase)
* class [Editor](../../editor)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

---

## Editor(Stream) {#constructor_1}

Инициализирует новый экземпляр Editor с указанным входным документом (в виде потока).

```csharp
public Editor(Stream document)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| документ | Stream | Поток, содержащий содержимое документа. Не должен быть null. |

### Замечания

**Learn more**

* More about file types supported by GroupDocs.Editor: [Document formats supported by GroupDocs.Editor](https://docs.groupdocs.com/display/editornet/Supported+Document+Formats)
* More about GroupDocs.Editor for .NET features: [Developer Guide](https://docs.groupdocs.com/display/editornet/Developer+Guide)

### Примеры

```csharp
using (FileStream fs = new FileStream("input.docx", FileMode.Open, FileAccess.Read))
{
    using (Editor editor = new Editor(fs))
    {
        // Используйте экземпляр редактора для редактирования и сохранения документов
    }
}
```

### См. также

* class [Editor](../../editor)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

---

## Editor(Stream, ILoadOptions) {#constructor_2}

Инициализирует новый экземпляр Editor с указанным входным документом (в виде потока) и его параметрами загрузки.

```csharp
public Editor(Stream document, ILoadOptions loadOptions)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| документ | Stream | Поток, содержащий содержимое документа. Не должен быть null. |
| loadOptions | ILoadOptions | Параметры загрузки документа. Может быть null. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | Выбрасывается, когда поток документа равен null. |
| ArgumentException | Выбрасывается, когда поток документа недействителен. |

### Замечания

**Learn more**

* More about file types supported by GroupDocs.Editor: [Document formats supported by GroupDocs.Editor](https://docs.groupdocs.com/display/editornet/Supported+Document+Formats)
* More about GroupDocs.Editor for .NET features: [Developer Guide](https://docs.groupdocs.com/display/editornet/Developer+Guide)

### Примеры

```csharp
using (FileStream fs = new FileStream("input.docx", FileMode.Open, FileAccess.Read))
{
    ILoadOptions loadOptions = new WordProcessingLoadOptions();
    using (Editor editor = new Editor(fs, loadOptions))
    {
        // Используйте экземпляр редактора для редактирования и сохранения документов
    }
}
```

### См. также

* interface [ILoadOptions](../../../groupdocs.editor.options/iloadoptions)
* class [Editor](../../editor)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

---

## Editor(string, ILoadOptions) {#constructor_4}

Инициализирует новый экземпляр Editor с указанным входным документом (в виде полного пути к файлу) и его параметрами загрузки.

```csharp
public Editor(string filePath, ILoadOptions loadOptions)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| filePath | String | Полный путь к файлу. Не должен быть null, пустым или содержать только пробелы. Должен быть корректным, и файл должен существовать. |
| loadOptions | ILoadOptions | Параметры загрузки документа. Может быть null. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentException | Выбрасывается, когда путь к файлу недействителен. |
| FileNotFoundException | Выбрасывается, когда файл не существует. |

### Замечания

**Learn more**

* More about file types supported by GroupDocs.Editor: [Document formats supported by GroupDocs.Editor](https://docs.groupdocs.com/display/editornet/Supported+Document+Formats)
* More about GroupDocs.Editor for .NET features: [Developer Guide](https://docs.groupdocs.com/display/editornet/Developer+Guide)

### Примеры

```csharp
string filePath = "input.docx";
ILoadOptions loadOptions = new WordProcessingLoadOptions();
using (Editor editor = new Editor(filePath, loadOptions))
{
    // Используйте экземпляр редактора для редактирования и сохранения документов
}
```

### См. также

* interface [ILoadOptions](../../../groupdocs.editor.options/iloadoptions)
* class [Editor](../../editor)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

---

## Editor(string) {#constructor_3}

Инициализирует новый экземпляр Editor с указанным входным документом (в виде полного пути к файлу) и настройками Editor.

```csharp
public Editor(string filePath)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| filePath | String | Полный путь к файлу. Не должен быть NULL. Должен быть корректным, и файл должен существовать. |

### См. также

* class [Editor](../../editor)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.editor.dll -->
