---
title: "FixedLayoutFormats"
second_title: "GroupDocs.Editor Java için API Referansı"
description: "PDF ve XPS'yi içeren, raster görüntüleri içermeyen, sabit sayfa olarak da bilinen tüm sabit düzen formatlarını kapsar"
type: docs
weight: 12
url: /tr/java/com.groupdocs.editor.formats/fixedlayoutformats/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.formats.abstraction.FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase), [com.groupdocs.editor.formats.abstraction.DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase)
```
public class FixedLayoutFormats extends DocumentFormatBase
```

PDF ve XPS'yi içeren tüm sabit düzen (\"fixed-page\" olarak da bilinir) formatlarını kapsar (bu, raster görüntüleri içermez)

<br />

*** ** * ** ***

Çeşitli belge görüntüleme veya yayınlama uygulamaları, kullanıcıların belirli formatlardaki belgeleri (Adobe Acrobat, XPS Viewer) açmasına ve bazen (Adobe InDesign) düzenlemesine izin verir. Bu uygulamalar genellikle sözde \u201cfixed-page\u201d format belgeleri üretir. Böyle bir belge formatı, bir belgenin\u2019s içeriğinin her sayfada tam olarak nerede konumlandırıldığını açıklar. İçeride, PDF veya XPS formatı her sayfanın bir açıklamasını ve sayfadaki içeriğin düzenini belirten çizim talimatlarını içerir. Bu, içeriğin raster veya vektör biçiminde gösterildiği yeri tanımlayan görüntü formatlarına benzer.

<br />


## Alanlar

| Alan | Açıklama |
| --- | --- |
|  | [Pdf](#Pdf) | Taşınabilir Belge Formatı (PDF), 1990'larda Adobe tarafından oluşturulan bir belge türüdür. |
|
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getAll()](#getAll--) | Tüm [FixedLayoutFormats](../../com.groupdocs.editor.formats/fixedlayoutformats) öğelerinin sayılabilir bir koleksiyonunu alır. |
|
|  | [fromExtension(String extension)](#fromExtension-java.lang.String-) | Belirtilen dosya uzantısına sahip belirtilen türdeki [FixedLayoutFormats](../../com.groupdocs.editor.formats/fixedlayoutformats) örneğini getirir. |
|
|  | [fromString(String extension)](#fromString-java.lang.String-) | Dosya uzantısını temsil eden bir dizeyi bir [FixedLayoutFormats](../../com.groupdocs.editor.formats/fixedlayoutformats) nesnesine dönüştürür. |
|
### Pdf {#Pdf}
```
public static final FixedLayoutFormats Pdf
```


Taşınabilir Belge Formatı (PDF), 1990'larda Adobe tarafından oluşturulan bir belge türüdür. Bu dosya formatının amacı, belgelerin ve diğer referans materyallerin, uygulama yazılımı, donanım ve işletim sisteminden bağımsız bir formatta temsil edilmesi için bir standart getirmekti.
Bu dosya formatı hakkında daha fazla bilgi edinin
[here](../https://docs.fileformat.com/pdf/)
.


### getAll() {#getAll--}
```
public static List<FixedLayoutFormats> getAll()
```


Tüm [FixedLayoutFormats](../../com.groupdocs.editor.formats/fixedlayoutformats) öğelerinin sayılabilir bir koleksiyonunu alır.
Değer: Tüm [FixedLayoutFormats](../../com.groupdocs.editor.formats/fixedlayoutformats) örneklerini içeren bir IEnumerable{FixedLayoutFormats}.


**Returns:**
java.util.List<com.groupdocs.editor.formats.FixedLayoutFormats>
### fromExtension(String extension) {#fromExtension-java.lang.String-}
```
public static FixedLayoutFormats fromExtension(String extension)
```


Belirtilen dosya uzantısına sahip belirtilen türdeki [FixedLayoutFormats](../../com.groupdocs.editor.formats/fixedlayoutformats) örneğini getirir.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | uzantı | java.lang.String | Belge formatının dosya uzantısı. |
|

**Returns:**
[FixedLayoutFormats](../../com.groupdocs.editor.formats/fixedlayoutformats) - An instance of the specified type [FixedLayoutFormats](../../com.groupdocs.editor.formats/fixedlayoutformats) with the specified file extension.

### fromString(String extension) {#fromString-java.lang.String-}
```
public static FixedLayoutFormats fromString(String extension)
```


Dosya uzantısını temsil eden bir dizeyi bir [FixedLayoutFormats](../../com.groupdocs.editor.formats/fixedlayoutformats) nesnesine dönüştürür.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | uzantı | java.lang.String | Dönüştürülecek dosya uzantısı. Uzantı birden fazla nokta içeriyorsa, son noktanın sonrasındaki kısım kullanılır. |
|

**Returns:**
[FixedLayoutFormats](../../com.groupdocs.editor.formats/fixedlayoutformats) - A [FixedLayoutFormats](../../com.groupdocs.editor.formats/fixedlayoutformats) object corresponding to the specified file extension.

