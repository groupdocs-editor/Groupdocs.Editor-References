---
title: "MarkdownSaveOptions"
second_title: "GroupDocs.Editor Node.js için Java API Referansı"
description: "Markdown belgelerini oluşturmak ve kaydetmek için özel seçenekleri belirtmeye izin verir."
type: docs
weight: 24
url: /tr/nodejs-java/com.groupdocs.editor.options/markdownsaveoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ISaveOptions](../../com.groupdocs.editor.options/isaveoptions)
```
public final class MarkdownSaveOptions implements ISaveOptions
```

Markdown belgelerini oluşturmak ve kaydetmek için özel seçenekleri belirtmeye izin verir.

<br />

*** ** * ** ***

MarkdownSaveOptions sınıfı, düzenlenmiş belge içeriğini içeren bir EditableDocument sınıfı örneği olduğunda ve bu içeriğin Markdown formatında yeni bir belgeye kaydedilmesi gerektiğinde kullanıcı tarafından uygulanmalıdır.

<br />


## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [MarkdownSaveOptions()](#MarkdownSaveOptions--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getOptimizeMemoryUsage()](#getOptimizeMemoryUsage--) | HTML'den belge oluşturulurken bellek kullanımını azaltma maliyeti olarak performansı düşüren bellek optimizasyon mekanizmalarını etkinleştirir. |
|
|  | [setOptimizeMemoryUsage(boolean value)](#setOptimizeMemoryUsage-boolean-) | HTML'den belge oluşturulurken bellek kullanımını azaltma maliyeti olarak performansı düşüren bellek optimizasyon mekanizmalarını etkinleştirir. |
|
|  | [getTableContentAlignment()](#getTableContentAlignment--) | Allow, içeriklerin Markdown formatına dışa aktarılırken tablolar içinde nasıl hizalanacağını belirtir. |
|
|  | [setTableContentAlignment(int value)](#setTableContentAlignment-int-) | Allow, içeriklerin Markdown formatına dışa aktarılırken tablolar içinde nasıl hizalanacağını belirtir. |
|
|  | [getImagesFolder()](#getImagesFolder--) | Bir belgeyi dışa aktarırken görüntülerin kaydedildiği fiziksel klasörü belirtir. |
Markdown formatına.
|
|  | [setImagesFolder(String value)](#setImagesFolder-java.lang.String-) | Bir belgeyi dışa aktarırken görüntülerin kaydedildiği fiziksel klasörü belirtir. |
Markdown formatına.
|
|  | [getExportImagesAsBase64()](#getExportImagesAsBase64--) | Görüntülerin çıktı dosyasına Base64 formatında kaydedilip kaydedilmeyeceğini belirtir. |
|
|  | [setExportImagesAsBase64(boolean value)](#setExportImagesAsBase64-boolean-) | Görüntülerin çıktı dosyasına Base64 formatında kaydedilip kaydedilmeyeceğini belirtir. |
|
### MarkdownSaveOptions() {#MarkdownSaveOptions--}
```
public MarkdownSaveOptions()
```


### getOptimizeMemoryUsage() {#getOptimizeMemoryUsage--}
```
public final boolean getOptimizeMemoryUsage()
```


HTML'den belge oluşturulurken bellek kullanımını azaltma maliyeti olarak performansı düşüren bellek optimizasyon mekanizmalarını etkinleştirir.
Bu seçeneği ayarlamak
true
büyük belgeler oluşturulurken bellek tüketimini önemli ölçüde azaltabilir, ancak daha yavaş kaydetme süresi maliyetiyle.
Varsayılan
false
(daha iyi performans için bellek optimizasyonu devre dışı bırakılmıştır).


**Returns:**
boolean
### setOptimizeMemoryUsage(boolean value) {#setOptimizeMemoryUsage-boolean-}
```
public final void setOptimizeMemoryUsage(boolean value)
```


HTML'den belge oluşturulurken bellek kullanımını azaltma maliyeti olarak performansı düşüren bellek optimizasyon mekanizmalarını etkinleştirir.
Bu seçeneği ayarlamak
true
büyük belgeler oluşturulurken bellek tüketimini önemli ölçüde azaltabilir, ancak daha yavaş kaydetme süresi maliyetiyle.
Varsayılan
false
(daha iyi performans için bellek optimizasyonu devre dışı bırakılmıştır).


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### getTableContentAlignment() {#getTableContentAlignment--}
```
public final int getTableContentAlignment()
```


Allow, içeriklerin Markdown formatına dışa aktarılırken tablolar içinde nasıl hizalanacağını belirtir.
Varsayılan değer [MarkdownTableContentAlignment.Auto](../../com.groupdocs.editor.options/markdowntablecontentalignment#Auto) olarak belirlenmiştir.
Değer: Tablo içeriği hizalaması


**Returns:**
int
### setTableContentAlignment(int value) {#setTableContentAlignment-int-}
```
public final void setTableContentAlignment(int value)
```


Allow, içeriklerin Markdown formatına dışa aktarılırken tablolar içinde nasıl hizalanacağını belirtir.
Varsayılan değer [MarkdownTableContentAlignment.Auto](../../com.groupdocs.editor.options/markdowntablecontentalignment#Auto) olarak belirlenmiştir.
Değer: Tablo içeriği hizalaması


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getImagesFolder() {#getImagesFolder--}
```
public final String getImagesFolder()
```


Bir belgeyi dışa aktarırken görüntülerin kaydedildiği fiziksel klasörü belirtir.
Markdown formatı. Varsayılan null.

<br />

*** ** * ** ***

Kullanıcı tarafından ne ImagesFolder (#getImagesFolder.getImagesFolder/#setImagesFolder(String).setImagesFolder(String)) ne de ExportImagesAsBase64 (#getExportImagesAsBase64.getExportImagesAsBase64/#setExportImagesAsBase64(boolean).setExportImagesAsBase64(boolean)) belirtilmezse, GroupDocs.Editor, ImagesFolder (#getImagesFolder.getImagesFolder/#setImagesFolder(String).setImagesFolder(String)) değerini kendiliğinden belirlemeye çalışır ve başarılı olduğunda uygular.

<br />



**Returns:**
java.lang.String
### setImagesFolder(String value) {#setImagesFolder-java.lang.String-}
```
public final void setImagesFolder(String value)
```


Bir belgeyi dışa aktarırken görüntülerin kaydedildiği fiziksel klasörü belirtir.
Markdown formatı. Varsayılan null.

<br />

*** ** * ** ***

Kullanıcı tarafından ne ImagesFolder (#getImagesFolder.getImagesFolder/#setImagesFolder(String).setImagesFolder(String)) ne de ExportImagesAsBase64 (#getExportImagesAsBase64.getExportImagesAsBase64/#setExportImagesAsBase64(boolean).setExportImagesAsBase64(boolean)) belirtilmezse, GroupDocs.Editor, ImagesFolder (#getImagesFolder.getImagesFolder/#setImagesFolder(String).setImagesFolder(String)) değerini kendiliğinden belirlemeye çalışır ve başarılı olduğunda uygular.

<br />



**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### getExportImagesAsBase64() {#getExportImagesAsBase64--}
```
public final boolean getExportImagesAsBase64()
```


Görüntülerin çıktı dosyasına Base64 formatında kaydedilip kaydedilmeyeceğini belirtir. Varsayılan
false
.

<br />

*** ** * ** ***

Bu özellik true olarak ayarlandığında, görüntü verileri doğrudan ![](../) görüntü öğelerine aktarılır ve ayrı dosyalar oluşturulmaz. Bu özellik true olarak ayarlandığında, MarkdownSaveOptions.ImagesFolder (#getImagesFolder.getImagesFolder/#setImagesFolder(String).setImagesFolder(String)) özelliğinden daha yüksek önceliğe sahiptir.

<br />



**Returns:**
boolean
### setExportImagesAsBase64(boolean value) {#setExportImagesAsBase64-boolean-}
```
public final void setExportImagesAsBase64(boolean value)
```


Görüntülerin çıktı dosyasına Base64 formatında kaydedilip kaydedilmeyeceğini belirtir. Varsayılan
false
.

<br />

*** ** * ** ***

Bu özellik true olarak ayarlandığında, görüntü verileri doğrudan ![](../) görüntü öğelerine aktarılır ve ayrı dosyalar oluşturulmaz. Bu özellik true olarak ayarlandığında, MarkdownSaveOptions.ImagesFolder (#getImagesFolder.getImagesFolder/#setImagesFolder(String).setImagesFolder(String)) özelliğinden daha yüksek önceliğe sahiptir.

<br />



**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

