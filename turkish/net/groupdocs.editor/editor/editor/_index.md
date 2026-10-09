---
title: "Editor"
second_title: "GroupDocs.Editor for .NET API Referansı"
description: "Editorgroupdocs.editor/editor sınıfının yeni bir örneğini başlatır ve belirtilen formata göre yeni boş bir belge oluşturur."
type: docs
weight: 10
url: /tr/net/groupdocs.editor/editor/editor/
---
## Editor(DocumentFormatBase) {#constructor}

[`Editor`](../../editor) sınıfının yeni bir örneğini başlatır ve belirtilen formata göre yeni boş bir belge oluşturur.

```csharp
public Editor(DocumentFormatBase format)
```

| Parameter | Type | Açıklama |
| --- | --- | --- |
| format | DocumentFormatBase | Oluşturulacak belgenin dosya formatını temsil eder. |

### Açıklamalar

**Learn more**

* More about file types supported by GroupDocs.Editor: [Document formats supported by GroupDocs.Editor](https://docs.groupdocs.com/display/editornet/Supported+Document+Formats)
* More about GroupDocs.Editor for .NET features: [Developer Guide](https://docs.groupdocs.com/display/editornet/Developer+Guide)

### Örnekler

```csharp
IDocumentFormat format = new WordProcessingFormats.Docx();
using (Editor editor = new Editor(format))
{
    // Düzenleyici örneğini kullanarak belgeleri düzenleyin ve kaydedin
}
```

### Ayrıca Bakınız

* class [DocumentFormatBase](../../../groupdocs.editor.formats.abstraction/documentformatbase)
* class [Editor](../../editor)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

---

## Editor(Stream) {#constructor_1}

Belirtilen giriş belgesi (akış olarak) ile yeni bir Editor örneği başlatır.

```csharp
public Editor(Stream document)
```

| Parameter | Type | Açıklama |
| --- | --- | --- |
| belge | Stream | Belge içeriğini içeren akış. Null olmamalıdır. |

### Açıklamalar

**Learn more**

* More about file types supported by GroupDocs.Editor: [Document formats supported by GroupDocs.Editor](https://docs.groupdocs.com/display/editornet/Supported+Document+Formats)
* More about GroupDocs.Editor for .NET features: [Developer Guide](https://docs.groupdocs.com/display/editornet/Developer+Guide)

### Örnekler

```csharp
using (FileStream fs = new FileStream("input.docx", FileMode.Open, FileAccess.Read))
{
    using (Editor editor = new Editor(fs))
    {
        // Düzenleyici örneğini kullanarak belgeleri düzenleyin ve kaydedin
    }
}
```

### Ayrıca Bakınız

* class [Editor](../../editor)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

---

## Editor(Stream, ILoadOptions) {#constructor_2}

Belirtilen giriş belgesi (akış olarak) ve yükleme seçenekleriyle yeni bir Editor örneği başlatır.

```csharp
public Editor(Stream document, ILoadOptions loadOptions)
```

| Parameter | Type | Açıklama |
| --- | --- | --- |
| belge | Stream | Belge içeriğini içeren akış. Null olmamalıdır. |
| loadOptions | ILoadOptions | Belge yükleme seçenekleri. Null olabilir. |

### İstisnalar

| istisna | koşul |
| --- | --- |
| ArgumentNullException | Belge akışı null olduğunda fırlatılır. |
| ArgumentException | Belge akışı geçersiz olduğunda fırlatılır. |

### Açıklamalar

**Learn more**

* More about file types supported by GroupDocs.Editor: [Document formats supported by GroupDocs.Editor](https://docs.groupdocs.com/display/editornet/Supported+Document+Formats)
* More about GroupDocs.Editor for .NET features: [Developer Guide](https://docs.groupdocs.com/display/editornet/Developer+Guide)

### Örnekler

```csharp
using (FileStream fs = new FileStream("input.docx", FileMode.Open, FileAccess.Read))
{
    ILoadOptions loadOptions = new WordProcessingLoadOptions();
    using (Editor editor = new Editor(fs, loadOptions))
    {
        // Düzenleyici örneğini kullanarak belgeleri düzenleyin ve kaydedin
    }
}
```

### Ayrıca Bakınız

* interface [ILoadOptions](../../../groupdocs.editor.options/iloadoptions)
* class [Editor](../../editor)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

---

## Editor(string, ILoadOptions) {#constructor_4}

Belirtilen giriş belgesi (tam dosya yolu olarak) ve yükleme seçenekleriyle yeni bir Editor örneği başlatır.

```csharp
public Editor(string filePath, ILoadOptions loadOptions)
```

| Parameter | Type | Açıklama |
| --- | --- | --- |
| filePath | String | Dosyanın tam yolu. Null, boş veya yalnızca boşluk içermemelidir. Geçerli olmalı ve dosya mevcut olmalıdır. |
| loadOptions | ILoadOptions | Belge yükleme seçenekleri. Null olabilir. |

### İstisnalar

| istisna | koşul |
| --- | --- |
| ArgumentException | Dosya yolu geçersiz olduğunda fırlatılır. |
| FileNotFoundException | Dosya mevcut olmadığında fırlatılır. |

### Açıklamalar

**Learn more**

* More about file types supported by GroupDocs.Editor: [Document formats supported by GroupDocs.Editor](https://docs.groupdocs.com/display/editornet/Supported+Document+Formats)
* More about GroupDocs.Editor for .NET features: [Developer Guide](https://docs.groupdocs.com/display/editornet/Developer+Guide)

### Örnekler

```csharp
string filePath = "input.docx";
ILoadOptions loadOptions = new WordProcessingLoadOptions();
using (Editor editor = new Editor(filePath, loadOptions))
{
    // Düzenleyici örneğini kullanarak belgeleri düzenleyin ve kaydedin
}
```

### Ayrıca Bakınız

* interface [ILoadOptions](../../../groupdocs.editor.options/iloadoptions)
* class [Editor](../../editor)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

---

## Editor(string) {#constructor_3}

Belirtilen giriş belgesi (tam dosya yolu olarak) ve Editor ayarlarıyla yeni bir Editor örneği başlatır.

```csharp
public Editor(string filePath)
```

| Parameter | Type | Açıklama |
| --- | --- | --- |
| filePath | String | Dosyanın tam yolu. NULL olmamalıdır. Geçerli olmalı ve dosya mevcut olmalıdır. |

### Ayrıca Bakınız

* class [Editor](../../editor)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

<!-- DÜZENLEMEYİN: GroupDocs.editor.dll için xmldocmd tarafından oluşturuldu -->
