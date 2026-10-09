---
title: "Editor"
second_title: "GroupDocs.Editor для Node.js через Java API Reference"
description: "Основной класс, который инкапсулирует методы конвертации."
type: docs
weight: 11
url: /ru/nodejs-java/com.groupdocs.editor/editor/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.resources.IAuxDisposable](../../com.groupdocs.editor.htmlcss.resources/iauxdisposable)
```
public final class Editor implements IAuxDisposable
```

Основной класс, инкапсулирующий методы конвертации.
Класс Editor предоставляет методы для загрузки, редактирования и сохранения документов всех поддерживаемых форматов. Он является disposable, поэтому используйте директиву 'using' или освобождайте его ресурсы вручную вызовом метода 'Dispose()'. Загрузка документов выполняется через конструкторы. Редактирование документов — через метод 'Edit', а сохранение полученного документа после редактирования — через метод 'Save'.
**Editor class should be considered as an entry point and the root object of the GroupDocs.Editor. All operations are performed using this class. Typical usage of the Editor class for performing a full document editing pipeline is the next:**

* Load a document into the Editor instance through its constructor.
* Optionally, detect a document type using a method.
* Open a document for editing by calling an method and obtaining an instance of class from it..
* Editing a document content on client-side using any WYSIWYG HTML-editor.
* Creating a new instance of from edited document content.
* Saving an edited document to some output format by calling a method.
* Disposing an instance of Editor class via 'using' operator or manually.

## Конструкторы

| Конструктор | Описание |
| --- | --- |
|  | [Editor(DocumentFormatBase format)](#Editor-com.groupdocs.editor.formats.abstraction.DocumentFormatBase-) | Инициализирует новый экземпляр класса [Editor](../../com.groupdocs.editor/editor) и создает новый пустой документ на основе указанного формата. |
|
|  | [Editor(InputStream document)](#Editor-java.io.InputStream-) | Инициализирует новый экземпляр Editor с указанным входным документом (в виде потока) |
|
|  | [Editor(InputStream document, ILoadOptions loadOptions)](#Editor-java.io.InputStream-com.groupdocs.editor.options.ILoadOptions-) | Инициализирует новый экземпляр Editor с указанным входным документом (в виде |
поток) с его параметрами загрузки и настройками Editor
|
|  | [Editor(String filePath)](#Editor-java.lang.String-) | Инициализирует новый экземпляр Editor с указанным входным документом (полный путь к файлу) |
|
|  | [Editor(String filePath, ILoadOptions loadOptions)](#Editor-java.lang.String-com.groupdocs.editor.options.ILoadOptions-) | Инициализирует новый экземпляр Editor с указанным входным документом (полный путь к файлу) с его параметрами загрузки |
|
## Методы

| Метод | Описание |
| --- | --- |
|  | [edit(IEditOptions editOptions)](#edit-com.groupdocs.editor.options.IEditOptions-) | Открывает ранее загруженный документ для редактирования, используя указанные параметры, специфичные для формата, путем создания и возврата экземпляра класса '' , который, в свою очередь, содержит методы для создания HTML‑разметки и связанных ресурсов. |
|
|  | [edit()](#edit--) | Открывает ранее загруженный документ для редактирования, используя параметры по умолчанию, путем |
создавая и возвращая экземпляр класса 'EditableDocument', который,
в свою очередь, содержит методы для создания HTML‑разметки и связанных
ресурсов.
|
|  | [save(EditableDocument inputDocument, OutputStream outputDocument, ISaveOptions saveOptions)](#save-com.groupdocs.editor.EditableDocument-java.io.OutputStream-com.groupdocs.editor.options.ISaveOptions-) | Преобразует указанный отредактированный документ, представленный как экземпляр |
'EditableDocument', в результирующий документ указанного формата и
сохраняет его содержимое в указанный поток
|
|  | [save(EditableDocument inputDocument, String filePath, ISaveOptions saveOptions)](#save-com.groupdocs.editor.EditableDocument-java.lang.String-com.groupdocs.editor.options.ISaveOptions-) | Преобразует указанный отредактированный документ, представленный как экземпляр '', в результирующий документ указанного формата и сохраняет его содержимое в файл по указанному пути |
|
|  | [save(EditableDocument inputDocument, String filePath)](#save-com.groupdocs.editor.EditableDocument-java.lang.String-) | Преобразует указанный отредактированный документ (представленный [EditableDocument](../../com.groupdocs.editor/editabledocument)) в выходной документ, формат которого определяется по расширению имени файла, и сохраняет его по указанному пути к файлу. |
|
|  | [save(OutputStream outputDocument, WordProcessingSaveOptions saveOptions)](#save-java.io.OutputStream-com.groupdocs.editor.options.WordProcessingSaveOptions-) | Преобразует оригинальный документ после изменения (например, |
FormFieldManager
(#getFormFieldManager.getFormFieldManager)),
в результирующий документ указанного формата и сохраняет его содержимое в предоставленный поток.
|
|  | [save(OutputStream outputDocument)](#save-java.io.OutputStream-) | Сохраните текущее содержимое документа в указанный выходной поток. |
|
|  | [getDocumentInfo(String password)](#getDocumentInfo-java.lang.String-) | Возвращает метаданные о документе, который был загружен в этот экземпляр 'Editor' |
|
|  | [dispose()](#dispose--) | Освобождает этот экземпляр Editor, чтобы он освободил все внутренние |
ресурсы и становится недоступным для дальнейшего использования
|
|  | [isDisposed()](#isDisposed--) | Указывает, был ли этот экземпляр Editor уже освобождён и не может быть |
использоваться дальше (true) или нет и активен (false)
|
### Editor(DocumentFormatBase format) {#Editor-com.groupdocs.editor.formats.abstraction.DocumentFormatBase-}
```
public Editor(DocumentFormatBase format)
```


Инициализирует новый экземпляр класса [Editor](../../com.groupdocs.editor/editor) и создает новый пустой документ на основе указанного формата.

<br />

*** ** * ** ***

> ```
>   IDocumentFormat format = WordProcessingFormats.Docx;
>  Editor editor = new Editor(format);
>  {
>      // Use the editor instance to edit and save documents
>  }
>  
>  
> ```

<br />



**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | format | [DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase) | представляет файловый формат документа, который будет создан. **Узнать больше** |

* More about file types supported by GroupDocs.Editor: [Document formats supported by GroupDocs.Editor](../https://docs.groupdocs.com/display/editornet/Supported+Document+Formats)
* More about GroupDocs.Editor for Java features: [Developer Guide](../https://docs.groupdocs.com/editor/java/developer-guide/)
|

### Editor(InputStream document) {#Editor-java.io.InputStream-}
```
public Editor(InputStream document)
```


Инициализирует новый экземпляр Editor с указанным входным документом (в виде потока)


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | документа | java.io.InputStream | Делегат, который должен возвращать поток с содержимым документа. Не должен быть NULL. **Узнать больше** |

* More about file types supported by GroupDocs.Editor: [Document formats supported by GroupDocs.Editor](../https://docs.groupdocs.com/display/editornet/Supported+Document+Formats)
* More about GroupDocs.Editor for Java features: [Developer Guide](../https://docs.groupdocs.com/editor/java/developer-guide/)
|

### Editor(InputStream document, ILoadOptions loadOptions) {#Editor-java.io.InputStream-com.groupdocs.editor.options.ILoadOptions-}
```
public Editor(InputStream document, ILoadOptions loadOptions)
```


Инициализирует новый экземпляр Editor с указанным входным документом (в виде
поток) с его параметрами загрузки и настройками Editor


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | документа | java.io.InputStream | Делегат, который должен возвращать поток с содержимым документа. Не должен быть NULL. |
|
|  | loadOptions | [ILoadOptions](../../com.groupdocs.editor.options/iloadoptions) | Делегат, который должен возвращать параметры загрузки документа. Может быть NULL и может возвращать null — в этом случае тип документа будет определён автоматически, и будут применены параметры загрузки по умолчанию для этого типа. |
|

### Editor(String filePath) {#Editor-java.lang.String-}
```
public Editor(String filePath)
```


Инициализирует новый экземпляр Editor с указанным входным документом (полный путь к файлу)


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | filePath | java.lang.String | Полный путь к файлу. Не должен быть NULL. Должен быть действительным, и файл должен существовать. **Learn more** |

* More about file types supported by GroupDocs.Editor: [Document formats supported by GroupDocs.Editor](../https://docs.groupdocs.com/editor/java/supported-document-formats/)
* More about GroupDocs.Editor for Java features: [Developer Guide](../https://docs.groupdocs.com/editor/java/developer-guide/)
|

### Editor(String filePath, ILoadOptions loadOptions) {#Editor-java.lang.String-com.groupdocs.editor.options.ILoadOptions-}
```
public Editor(String filePath, ILoadOptions loadOptions)
```


Инициализирует новый экземпляр Editor с указанным входным документом (полный путь к файлу) с его параметрами загрузки


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | filePath | java.lang.String | Полный путь к файлу. Не должен быть NULL. Должен быть действительным, и файл должен существовать. |
|
|  | loadOptions | [ILoadOptions](../../com.groupdocs.editor.options/iloadoptions) | Делегат, который должен возвращать параметры загрузки документа. Может быть NULL и может возвращать null — в этом случае тип документа будет определён автоматически, и будут применены параметры загрузки по умолчанию для этого типа. **Learn more** |

* More about file types supported by GroupDocs.Editor: [Document formats supported by GroupDocs.Editor](../https://docs.groupdocs.com/editor/java/supported-document-formats/)
* More about GroupDocs.Editor for Java features: [Developer Guide](../https://docs.groupdocs.com/editor/java/developer-guide/)
* More about how to open and edit password-protected documents and document from different storages: [Load and edit documents using GroupDocs.Editor](../https://docs.groupdocs.com/editor/java/load-document/)
|

### edit(IEditOptions editOptions) {#edit-com.groupdocs.editor.options.IEditOptions-}
```
public final EditableDocument edit(IEditOptions editOptions)
```


Открывает ранее загруженный документ для редактирования, используя указанные параметры, специфичные для формата, путем создания и возврата экземпляра класса '' , который, в свою очередь, содержит методы для создания HTML‑разметки и связанных ресурсов.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | editOptions | [IEditOptions](../../com.groupdocs.editor.options/ieditoptions) | Опции документа, специфичные для формата, которые позволяют настроить процесс конвертации. Не должны быть NULL. Не должны конфликтовать с ранее применёнными параметрами загрузки. |


*** ** * ** ***

Когда исходный документ загружается в экземпляр 'Editor' через конструктор, этот метод позволяет открыть документ для редактирования, преобразовав его во промежуточный формат, который инкапсулирован в экземпляре класса 'EditableDocument'. 'EditableDocument', возвращённый этим методом, содержит все необходимые методы и свойства для создания HTML‑разметки и соответствующих ресурсов (например, изображений, шрифтов и таблиц стилей) во всех необходимых конфигурациях для последующей передачи их в любой WYSIWYG HTML‑editor. Эта перегрузка получает параметры редактирования, специфичные для семейств форматов.

*** ** * ** ***


**Learn more**

* More about editing documents using GroupDocs.Editor: [How to edit document using GroupDocs.Editor](../https://docs.groupdocs.com/display/editornet/Edit+document)
|

**Returns:**
[EditableDocument](../../com.groupdocs.editor/editabledocument)
### edit() {#edit--}
```
public final EditableDocument edit()
```


Открывает ранее загруженный документ для редактирования, используя параметры по умолчанию, путем
создавая и возвращая экземпляр класса 'EditableDocument', который,
в свою очередь, содержит методы для создания HTML‑разметки и связанных
ресурсов.


**Returns:**
[EditableDocument](../../com.groupdocs.editor/editabledocument) - Instance of the 'EditableDocument' class, which encapsulates overall input document with all its resources in intermediate format. This method, if successfully finished, never returns NULL.


*** ** * ** ***

Когда исходный документ загружается в экземпляр 'Editor' через конструктор, этот метод позволяет открыть документ для редактирования, преобразовав его во промежуточный формат, который инкапсулирован в экземпляре класса 'EditableDocument'. 'EditableDocument', возвращённый этим методом, содержит все необходимые методы и свойства для создания HTML‑разметки и соответствующих ресурсов (например, изображений, шрифтов и таблиц стилей) во всех необходимых конфигурациях для последующей передачи их в любой WYSIWYG HTML‑editor. Эта перегрузка применяет параметры редактирования, которые являются значениями по умолчанию для формата, к которому относится входной документ.

<br />

**Learn more**

* More about editing documents using GroupDocs.Editor: [How to edit document using GroupDocs.Editor](../https://docs.groupdocs.com/editor/java/edit-document/)

### save(EditableDocument inputDocument, OutputStream outputDocument, ISaveOptions saveOptions) {#save-com.groupdocs.editor.EditableDocument-java.io.OutputStream-com.groupdocs.editor.options.ISaveOptions-}
```
public final void save(EditableDocument inputDocument, OutputStream outputDocument, ISaveOptions saveOptions)
```


Преобразует указанный отредактированный документ, представленный как экземпляр
'EditableDocument', в результирующий документ указанного формата и
сохраняет его содержимое в указанный поток


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | inputDocument | [EditableDocument](../../com.groupdocs.editor/editabledocument) | Версия входного документа, отредактированного в WYSIWYG HTML‑editor и хранящегося как экземпляр класса 'EditableDocument', который должен быть преобразован в выходной документ определённого формата |
|
|  | outputDocument | java.io.OutputStream | Поток вывода, в котором будет записано содержимое результирующего документа. Не должен быть NULL, освобождён, должен поддерживать запись. |
|
|  | saveOptions | [ISaveOptions](../../com.groupdocs.editor.options/isaveoptions) | Параметры сохранения документа, которые определяют формат результирующего документа, а также общие и специфичные для формата параметры сохранения. **Learn more** |

* More about saving document after edit using GroupDocs.Editor: [How to save edited document using GroupDocs.Editor](../https://docs.groupdocs.com/display/editornet/Save+document)
|

### save(EditableDocument inputDocument, String filePath, ISaveOptions saveOptions) {#save-com.groupdocs.editor.EditableDocument-java.lang.String-com.groupdocs.editor.options.ISaveOptions-}
```
public final void save(EditableDocument inputDocument, String filePath, ISaveOptions saveOptions)
```


Преобразует указанный отредактированный документ, представленный как экземпляр '', в результирующий документ указанного формата и сохраняет его содержимое в файл по указанному пути


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | inputDocument | [EditableDocument](../../com.groupdocs.editor/editabledocument) | Версия входного документа, отредактированного в WYSIWYG HTML‑editor и хранящегося как экземпляр класса '' , который должен быть преобразован в выходной документ определённого формата. Не должна быть null или освобождена. |
|
|  | filePath | java.lang.String | Путь к файлу, в котором будет сохранён выходной документ. Если файл с тем же именем существует, он будет полностью перезаписан. Строка пути не должна быть null, пустой или содержать только пробелы. |
|
|  | saveOptions | [ISaveOptions](../../com.groupdocs.editor.options/isaveoptions) | Параметры сохранения документа, которые определяют формат результирующего документа, а также общие и специфичные для формата параметры сохранения. Не должны быть null. **Learn more** |

* More about saving document after edit using GroupDocs.Editor: [How to save edited document using GroupDocs.Editor](../https://docs.groupdocs.com/display/editornet/Save+document)
|

### save(EditableDocument inputDocument, String filePath) {#save-com.groupdocs.editor.EditableDocument-java.lang.String-}
```
public final void save(EditableDocument inputDocument, String filePath)
```


Преобразует указанный отредактированный документ (представленный [EditableDocument](../../com.groupdocs.editor/editabledocument)) в выходной документ, формат которого определяется по расширению имени файла, и сохраняет его по указанному пути к файлу.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | inputDocument | [EditableDocument](../../com.groupdocs.editor/editabledocument) | Версия входного документа, отредактированного в WYSIWYG HTML‑editor и хранящегося как экземпляр [EditableDocument](../../com.groupdocs.editor/editabledocument). Не должна быть  null  или освобождена. |
|
|  | filePath | java.lang.String | Путь к файлу, в котором будет сохранён выходной документ. Если файл с тем же именем существует, он будет полностью перезаписан. Строка пути не должна быть  null , пустой или содержать только пробелы. Поскольку параметры сохранения по умолчанию и формат вывода определяются по этому имени файла, он должен иметь действительное расширение. |
|

### save(OutputStream outputDocument, WordProcessingSaveOptions saveOptions) {#save-java.io.OutputStream-com.groupdocs.editor.options.WordProcessingSaveOptions-}
```
public final OutputStream save(OutputStream outputDocument, WordProcessingSaveOptions saveOptions)
```


Преобразует оригинальный документ после изменения (например,
FormFieldManager
(#getFormFieldManager.getFormFieldManager)),
в результирующий документ указанного формата и сохраняет его содержимое в предоставленный поток.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | outputDocument | java.io.OutputStream | Поток, в который будет сохраняться выходной документ. Этот поток должен поддерживать запись и быть позиционированным в начале содержимого документа. Не должен быть null. |
|
|  | saveOptions | [WordProcessingSaveOptions](../../com.groupdocs.editor.options/wordprocessingsaveoptions) | Параметры сохранения документа, определяющие формат результирующего документа, а также общие и специфичные для формата параметры сохранения. Не должны быть null. |

<br />

*** ** * ** ***

Если outputDocument или saveOptions равны null, будет выброшено исключение NullPointerException. Если документ для сохранения отсутствует, будет выброшено исключение NullPointerException.

<br />

<br />

*** ** * ** ***

 **Learn more:** 

* 

<br />

|

**Returns:**
java.io.OutputStream - Поток, содержащий сохранённое содержимое документа.

### save(OutputStream outputDocument) {#save-java.io.OutputStream-}
```
public final OutputStream save(OutputStream outputDocument)
```


Сохраните текущее содержимое документа в указанный выходной поток.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | outputDocument | java.io.OutputStream | Поток, в который будет сохранено содержимое документа. Он не может быть null. |

<br />

*** ** * ** ***

Этот метод копирует содержимое из внутреннего представления документа в предоставленный выходной поток. Исходная позиция потока сохраняется после операции сохранения.

<br />

|

**Returns:**
java.io.OutputStream - Поток с сохранённым содержимым документа.

### getDocumentInfo(String password) {#getDocumentInfo-java.lang.String-}
```
public final IDocumentInfo getDocumentInfo(String password)
```


Возвращает метаданные о документе, который был загружен в этот экземпляр 'Editor'


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | пароль | java.lang.String | Пользователь может указать пароль для документа, если этот документ зашифрован паролем. Может быть NULL или пустой строкой, что эквивалентно отсутствию пароля. Для форматов документов, которые не поддерживают защиту паролем, этот аргумент будет игнорироваться. Если документ зашифрован, и пароль не указан в этом параметре, но был указан ранее в параметрах загрузки при создании этого экземпляра, он будет использован. **Learn more** |

* Learn more about obtaining document specific properties in code: [How to get document info using GroupDocs.Editor](../https://docs.groupdocs.com/editor/java/extracting-document-metainfo/)
|

**Returns:**
[IDocumentInfo](../../com.groupdocs.editor.metadata/idocumentinfo)
### dispose() {#dispose--}
```
public final void dispose()
```


Освобождает этот экземпляр Editor, чтобы он освободил все внутренние
ресурсы и становится недоступным для дальнейшего использования


### isDisposed() {#isDisposed--}
```
public final boolean isDisposed()
```


Указывает, был ли этот экземпляр Editor уже освобождён и не может быть
использоваться дальше (true) или нет и активен (false)


**Returns:**
boolean
