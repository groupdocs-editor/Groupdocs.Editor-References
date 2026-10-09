---
title: "DelimitedTextSaveOptions"
second_title: "GroupDocs.Editor for .NET API Referansı"
description: "Bu parametresiz yapıcı, varsayılan ayırıcı olarak noktalı virgül ile bir DelimitedTextSaveOptions örneği oluşturur; ardından Separatorgroupdocs.editor.options/delimitedtextsaveoptions/separator özelliği üzerinden değiştirilebilir."
type: docs
weight: 10
url: /tr/net/groupdocs.editor.options/delimitedtextsaveoptions/delimitedtextsaveoptions/
---
## DelimitedTextSaveOptions() {#constructor}

Bu parametresiz yapıcı, varsayılan ayırıcı olarak noktalı virgül (;) ile bir DelimitedTextSaveOptions örneği oluşturur (daha sonra [`Separator`](../separator) özelliği üzerinden değiştirilebilir).

```csharp
public DelimitedTextSaveOptions()
```

### Ayrıca Bakınız

* class [DelimitedTextSaveOptions](../../delimitedtextsaveoptions)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

---

## DelimitedTextSaveOptions(string) {#constructor_1}

Zorunlu ayırıcı (delimiter) ile ayrılmış metin için seçenek sınıfının bir örneğini oluşturur.

```csharp
public DelimitedTextSaveOptions(string separator)
```

| Parameter | Type | Açıklama |
| --- | --- | --- |
| separator | String | NULL veya boş olamayan dize ayırıcı (sınırlayıcı). |

### İstisnalar

| istisna | koşul |
| --- | --- |
| ArgumentException | Belirtilen ayırıcı null veya boş bir dize olduğunda fırlatılır. |

### Ayrıca Bakınız

* class [DelimitedTextSaveOptions](../../delimitedtextsaveoptions)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

<!-- DÜZENLEMEYİN: GroupDocs.editor.dll için xmldocmd tarafından oluşturuldu -->
