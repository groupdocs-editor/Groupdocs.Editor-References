---
title: Editor
second_title: .NET API Başvurusu için GroupDocs.Editor
description: Belirtilen girdi belgesiyle akış olarak yeni Düzenleyici örneğini başlatır
type: docs
weight: 10
url: /tr/net/groupdocs.editor/editor/editor/
---
## Editor(Func&lt;Stream&gt;) {#constructor}

Belirtilen girdi belgesiyle (akış olarak) yeni Düzenleyici örneğini başlatır

```csharp
public Editor(Func<Stream> document)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| document | Func`1 | Belge içeriğine sahip bir akış döndürmesi gereken temsilci. NULL olmamalıdır. |

### Notlar

**Daha fazla bilgi edin**

* GroupDocs.Editor tarafından desteklenen dosya türleri hakkında daha fazla bilgi: [GroupDocs.Editor tarafından desteklenen belge biçimleri](https://docs.groupdocs.com/display/editornet/Supported+Document+Formats)
* .NET özellikleri için GroupDocs.Editor hakkında daha fazla bilgi: [Geliştirici Kılavuzu](https://docs.groupdocs.com/display/editornet/Developer+Guide)

### Ayrıca bakınız

* class [Editor](../../editor)
* ad alanı [GroupDocs.Editor](../../editor)
* toplantı [GroupDocs.Editor](../../../)

---

## Editor(Func&lt;Stream&gt;, Func&lt;ILoadOptions&gt;) {#constructor_1}

Yükleme seçenekleri ile belirtilen girdi belgesiyle (akış olarak) yeni Düzenleyici örneğini başlatır.

```csharp
public Editor(Func<Stream> document, Func<ILoadOptions> loadOptions)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| document | Func`1 | Belge içeriğine sahip bir akış döndürmesi gereken temsilci. NULL olmamalıdır. |
| loadOptions | Func`1 | Delege, bir belge yükleme seçenekleri döndürmelidir. NULL olabilir ve null - değerini döndürebilir, bu durumda belge türü otomatik olarak algılanacak ve bu tür için varsayılan yükleme seçenekleri uygulanacaktır. |

### Notlar

**Daha fazla bilgi edin**

* GroupDocs.Editor tarafından desteklenen dosya türleri hakkında daha fazla bilgi: [GroupDocs.Editor tarafından desteklenen belge biçimleri](https://docs.groupdocs.com/display/editornet/Supported+Document+Formats)
* .NET özellikleri için GroupDocs.Editor hakkında daha fazla bilgi: [Geliştirici Kılavuzu](https://docs.groupdocs.com/display/editornet/Developer+Guide)
* Parola korumalı belgelerin ve farklı depolardaki belgelerin nasıl açılacağı ve düzenleneceği hakkında daha fazla bilgi: [GroupDocs.Editor kullanarak belgeleri yükleyin ve düzenleyin](https://docs.groupdocs.com/display/editornet/Load+document)

### Ayrıca bakınız

* interface [ILoadOptions](../../../groupdocs.editor.options/iloadoptions)
* class [Editor](../../editor)
* ad alanı [GroupDocs.Editor](../../editor)
* toplantı [GroupDocs.Editor](../../../)

---

## Editor(string) {#constructor_2}

Belirtilen girdi belgesiyle (tam dosya yolu olarak) yeni Düzenleyici örneğini başlatır

```csharp
public Editor(string filePath)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| filePath | String | Dosyanın tam yolu. NULL olmamalıdır. Geçerli olmalı ve dosya mevcut olmalıdır. |

### Notlar

**Daha fazla bilgi edin**

* GroupDocs.Editor tarafından desteklenen dosya türleri hakkında daha fazla bilgi: [GroupDocs.Editor tarafından desteklenen belge biçimleri](https://docs.groupdocs.com/display/editornet/Supported+Document+Formats)
* .NET özellikleri için GroupDocs.Editor hakkında daha fazla bilgi: [Geliştirici Kılavuzu](https://docs.groupdocs.com/display/editornet/Developer+Guide)

### Ayrıca bakınız

* class [Editor](../../editor)
* ad alanı [GroupDocs.Editor](../../editor)
* toplantı [GroupDocs.Editor](../../../)

---

## Editor(string, Func&lt;ILoadOptions&gt;) {#constructor_3}

Yükleme seçenekleri ile belirtilen girdi belgesiyle (tam dosya yolu olarak) yeni Düzenleyici örneğini başlatır.

```csharp
public Editor(string filePath, Func<ILoadOptions> loadOptions)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| filePath | String | Dosyanın tam yolu. NULL olmamalıdır. Geçerli olmalı ve dosya mevcut olmalıdır. |
| loadOptions | Func`1 | Delege, bir belge yükleme seçenekleri döndürmelidir. NULL olabilir ve null - değerini döndürebilir, bu durumda belge türü otomatik olarak algılanacak ve bu tür için varsayılan yükleme seçenekleri uygulanacaktır. |

### Notlar

**Daha fazla bilgi edin**

* GroupDocs.Editor tarafından desteklenen dosya türleri hakkında daha fazla bilgi: [GroupDocs.Editor tarafından desteklenen belge biçimleri](https://docs.groupdocs.com/display/editornet/Supported+Document+Formats)
* .NET özellikleri için GroupDocs.Editor hakkında daha fazla bilgi: [Geliştirici Kılavuzu](https://docs.groupdocs.com/display/editornet/Developer+Guide)
* Parola korumalı belgelerin ve farklı depolardaki belgelerin nasıl açılacağı ve düzenleneceği hakkında daha fazla bilgi: [GroupDocs.Editor kullanarak belgeleri yükleyin ve düzenleyin](https://docs.groupdocs.com/display/editornet/Load+document)

### Ayrıca bakınız

* interface [ILoadOptions](../../../groupdocs.editor.options/iloadoptions)
* class [Editor](../../editor)
* ad alanı [GroupDocs.Editor](../../editor)
* toplantı [GroupDocs.Editor](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
