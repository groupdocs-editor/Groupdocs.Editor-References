---
title: "IsValid"
second_title: "GroupDocs.Editor for .NET API Referansı"
description: "Belirtilen akışın geçerli bir EMF görüntüsü olup olmadığını denetler"
type: docs
weight: 90
url: /tr/net/groupdocs.editor.htmlcss.resources.images.vector/emfimage/isvalid/
---
## IsValid(Stream) {#isvalid}

Belirtilen akışın geçerli bir EMF görüntüsü olup olmadığını denetler

```csharp
public static bool IsValid(Stream binaryContent)
```

| Parameter | Type | Açıklama |
| --- | --- | --- |
| binaryContent | Stream | Giriş bayt akışı. NULL olamaz, okuma ve konumlandırma (seeking) desteklemelidir. |

### Dönüş Değeri

Belirtilen akış geçerli bir EMF görüntüsü içeriyorsa True, aksi takdirde false.

### Ayrıca Bakınız

* class [EmfImage](../../emfimage)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Images.Vector](../../../groupdocs.editor.htmlcss.resources.images.vector)
* assembly [GroupDocs.Editor](../../../)

---

## IsValid(string) {#isvalid_1}

Belirtilen base64 kodlu dizgenin geçerli bir EMF görüntüsü olup olmadığını denetler

```csharp
public static bool IsValid(string contentInBase64)
```

| Parameter | Type | Açıklama |
| --- | --- | --- |
| contentInBase64 | String | EMF görüntüsünün içeriğinin base64 kodlamasıyla saklandığı girdi dizesi. NULL olamaz ve boş olamaz. |

### Dönüş Değeri

Belirtilen dize geçerli bir EMF görüntüsü içeriyorsa True, aksi takdirde false.

### Ayrıca Bakınız

* class [EmfImage](../../emfimage)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Images.Vector](../../../groupdocs.editor.htmlcss.resources.images.vector)
* assembly [GroupDocs.Editor](../../../)

<!-- DÜZENLEMEYİN: GroupDocs.editor.dll için xmldocmd tarafından oluşturuldu -->
