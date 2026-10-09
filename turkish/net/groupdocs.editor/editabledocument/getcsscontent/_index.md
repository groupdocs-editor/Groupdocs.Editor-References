---
title: "GetCssContent"
second_title: "GroupDocs.Editor for .NET API Referansı"
description: "Tüm dış stil sayfalarının içeriğini, her birinin bir stil sayfasını temsil ettiği bir dizi dize olarak döndürür. Bu belge için CSS bulunmuyorsa boş bir dizi döndürür."
type: docs
weight: 140
url: /tr/net/groupdocs.editor/editabledocument/getcsscontent/
---
## GetCssContent() {#getcsscontent}

Tüm harici stil sayfalarının içeriğini, her bir stil sayfasını temsil eden bir dize olarak bir liste şeklinde döndürür. Bu belge için CSS yoksa boş liste döndürür.

```csharp
public List<string> GetCssContent()
```

### Dönüş Değeri

Her bir dizenin bir CSS belgesinin içeriğini tuttuğu bir dizi dize.

### Ayrıca Bakınız

* class [EditableDocument](../../editabledocument)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

---

## GetCssContent(string, string) {#getcsscontent_1}

Tüm harici stil sayfalarının içeriğini, her bir stil sayfasını temsil eden bir dize olarak bir liste şeklinde döndürür. Belirtilen önek, her sonuç stil sayfasındaki dış kaynağa yapılan her bağlantıya uygulanır. Bu belge için CSS yoksa boş liste döndürür.

```csharp
public List<string> GetCssContent(string externalImagesPrefix, string externalFontsPrefix)
```

| Parameter | Type | Açıklama |
| --- | --- | --- |
| externalImagesPrefix | String | Bu parametre aracılığıyla, sonuç CSS dizelerinde CSS bildirimlerinde yer alacak tüm dış görüntülere eklenmek üzere bir önek belirtilebilir. NULL veya boş ise, önek eklenmez. |
| externalFontsPrefix | String | Bu parametre aracılığıyla, sonuç CSS dizelerinde @font-face kurallarındaki tüm dış fontlara eklenmek üzere bir önek belirtilebilir. NULL veya boş ise, önek eklenmez. |

### Dönüş Değeri

Her bir dizenin bir CSS belgesinin içeriğini tuttuğu bir dizi dize.

### Ayrıca Bakınız

* class [EditableDocument](../../editabledocument)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

<!-- DÜZENLEMEYİN: GroupDocs.editor.dll için xmldocmd tarafından oluşturuldu -->
