---
title: "Editor"
second_title: "مرجع API لـ GroupDocs.Editor لـ .NET"
description: "يُنشئ مثيلًا جديدًا من فئة Editorgroupdocs.editor/editor ويُنشئ مستندًا فارغًا جديدًا بناءً على الصِيغة المحددة."
type: docs
weight: 10
url: /ar/net/groupdocs.editor/editor/editor/
---
## Editor(DocumentFormatBase) {#constructor}

يُنشئ مثيلًا جديدًا من الفئة [`Editor`](../../editor) ويُنشئ مستندًا فارغًا جديدًا بناءً على الصِيغة المحددة.

```csharp
public Editor(DocumentFormatBase format)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| صيغة | DocumentFormatBase | يمثِّل صيغة الملف للمستند الذي سيتم إنشاؤه. |

### ملاحظات

**Learn more**

* More about file types supported by GroupDocs.Editor: [Document formats supported by GroupDocs.Editor](https://docs.groupdocs.com/display/editornet/Supported+Document+Formats)
* More about GroupDocs.Editor for .NET features: [Developer Guide](https://docs.groupdocs.com/display/editornet/Developer+Guide)

### أمثلة

```csharp
IDocumentFormat format = new WordProcessingFormats.Docx();
using (Editor editor = new Editor(format))
{
    // استخدم مثيل المحرر لتعديل وحفظ المستندات
}
```

### انظر أيضًا

* class [DocumentFormatBase](../../../groupdocs.editor.formats.abstraction/documentformatbase)
* class [Editor](../../editor)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

---

## Editor(Stream) {#constructor_1}

يقوم بتهيئة نسخة جديدة من فئة Editor مع مستند الإدخال المحدد (كتيار).

```csharp
public Editor(Stream document)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| مستند | Stream | دفق يحتوي على محتوى المستند. لا ينبغي أن يكون null. |

### ملاحظات

**Learn more**

* More about file types supported by GroupDocs.Editor: [Document formats supported by GroupDocs.Editor](https://docs.groupdocs.com/display/editornet/Supported+Document+Formats)
* More about GroupDocs.Editor for .NET features: [Developer Guide](https://docs.groupdocs.com/display/editornet/Developer+Guide)

### أمثلة

```csharp
using (FileStream fs = new FileStream("input.docx", FileMode.Open, FileAccess.Read))
{
    using (Editor editor = new Editor(fs))
    {
        // استخدم مثيل المحرر لتعديل وحفظ المستندات
    }
}
```

### انظر أيضًا

* class [Editor](../../editor)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

---

## Editor(Stream, ILoadOptions) {#constructor_2}

يقوم بتهيئة نسخة جديدة من فئة Editor مع مستند الإدخال المحدد (كتيار) مع خيارات التحميل الخاصة به.

```csharp
public Editor(Stream document, ILoadOptions loadOptions)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| مستند | Stream | دفق يحتوي على محتوى المستند. لا ينبغي أن يكون null. |
| loadOptions | ILoadOptions | خيارات تحميل المستند. قد تكون null. |

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | يتم إلقاؤه عندما يكون تدفق المستند null. |
| ArgumentException | يتم إلقاؤه عندما يكون تدفق المستند غير صالح. |

### ملاحظات

**Learn more**

* More about file types supported by GroupDocs.Editor: [Document formats supported by GroupDocs.Editor](https://docs.groupdocs.com/display/editornet/Supported+Document+Formats)
* More about GroupDocs.Editor for .NET features: [Developer Guide](https://docs.groupdocs.com/display/editornet/Developer+Guide)

### أمثلة

```csharp
using (FileStream fs = new FileStream("input.docx", FileMode.Open, FileAccess.Read))
{
    ILoadOptions loadOptions = new WordProcessingLoadOptions();
    using (Editor editor = new Editor(fs, loadOptions))
    {
        // استخدم مثيل المحرر لتعديل وحفظ المستندات
    }
}
```

### انظر أيضًا

* interface [ILoadOptions](../../../groupdocs.editor.options/iloadoptions)
* class [Editor](../../editor)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

---

## Editor(string, ILoadOptions) {#constructor_4}

يقوم بتهيئة نسخة جديدة من فئة Editor مع مستند الإدخال المحدد (كمسار ملف كامل) مع خيارات التحميل الخاصة به.

```csharp
public Editor(string filePath, ILoadOptions loadOptions)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| filePath | String | المسار الكامل للملف. لا يجب أن يكون null أو فارغًا أو يحتوي على مسافات فقط. يجب أن يكون صالحًا، ويجب أن يكون الملف موجودًا. |
| loadOptions | ILoadOptions | خيارات تحميل المستند. قد تكون null. |

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentException | يتم إلقاؤه عندما يكون مسار الملف غير صالح. |
| FileNotFoundException | يتم إلقاؤه عندما لا يكون الملف موجودًا. |

### ملاحظات

**Learn more**

* More about file types supported by GroupDocs.Editor: [Document formats supported by GroupDocs.Editor](https://docs.groupdocs.com/display/editornet/Supported+Document+Formats)
* More about GroupDocs.Editor for .NET features: [Developer Guide](https://docs.groupdocs.com/display/editornet/Developer+Guide)

### أمثلة

```csharp
string filePath = "input.docx";
ILoadOptions loadOptions = new WordProcessingLoadOptions();
using (Editor editor = new Editor(filePath, loadOptions))
{
    // استخدم مثيل المحرر لتعديل وحفظ المستندات
}
```

### انظر أيضًا

* interface [ILoadOptions](../../../groupdocs.editor.options/iloadoptions)
* class [Editor](../../editor)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

---

## Editor(string) {#constructor_3}

يقوم بتهيئة نسخة جديدة من فئة Editor مع مستند الإدخال المحدد (كمسار ملف كامل) وإعدادات Editor.

```csharp
public Editor(string filePath)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| filePath | String | المسار الكامل للملف. لا يجب أن يكون NULL. يجب أن يكون صالحًا، ويجب أن يكون الملف موجودًا. |

### انظر أيضًا

* class [Editor](../../editor)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.editor.dll -->
