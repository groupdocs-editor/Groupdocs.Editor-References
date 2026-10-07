---
title: "XpsSaveOptions"
second_title: "GroupDocs.Editor Java için API Referansı"
description: "XPS XML Paper Specifications belgelerinin oluşturulması ve kaydedilmesi için özel seçenekler belirtmeye izin verir"
type: docs
weight: 54
url: /tr/java/com.groupdocs.editor.options/xpssaveoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ISaveOptions](../../com.groupdocs.editor.options/isaveoptions)
```
public final class XpsSaveOptions implements ISaveOptions
```

XPS (XML Paper Specifications) belgelerini oluşturmak ve kaydetmek için özel seçenekler belirtmeye olanak tanır.

<br />

*** ** * ** ***

XPS dosyası, Microsoft tarafından oluşturulan XML Paper Specifications tabanlı sayfa düzeni dosyalarını temsil eder. EMF dosya formatının yerine geliştirilmiştir ve PDF dosya formatına benzer, ancak bir belgenin düzen, görünüm ve baskı bilgileri için XML kullanır.

<br />


## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [XpsSaveOptions()](#XpsSaveOptions--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getFontEmbedding()](#getFontEmbedding--) | Orijinal belgede kullanılan font kaynaklarını sonuç XPS belgesine gömmekten sorumludur. |
|
|  | [getOptimizeMemoryUsage()](#getOptimizeMemoryUsage--) | HTML'den belge oluşturulurken bellek kullanımını azaltma maliyeti olarak performansı düşüren bellek optimizasyon mekanizmalarını etkinleştirir. |
|
|  | [setOptimizeMemoryUsage(boolean value)](#setOptimizeMemoryUsage-boolean-) | HTML'den belge oluşturulurken bellek kullanımını azaltma maliyeti olarak performansı düşüren bellek optimizasyon mekanizmalarını etkinleştirir. |
|
### XpsSaveOptions() {#XpsSaveOptions--}
```
public XpsSaveOptions()
```


### getFontEmbedding() {#getFontEmbedding--}
```
public final byte getFontEmbedding()
```


Orijinal belgede kullanılan font kaynaklarını sonuç XPS belgesine gömmekten sorumludur.
Varsayılan olarak herhangi bir font gömmez (NotEmbed).


**Returns:**
bayt
### getOptimizeMemoryUsage() {#getOptimizeMemoryUsage--}
```
public final boolean getOptimizeMemoryUsage()
```


HTML'den belge oluşturulurken bellek kullanımını azaltma maliyeti olarak performansı düşüren bellek optimizasyon mekanizmalarını etkinleştirir.
Bu seçeneği true olarak ayarlamak, büyük belgeler oluşturulurken daha yavaş kaydetme süresi pahasına bellek tüketimini önemli ölçüde azaltabilir.
Varsayılan değer false'tur (daha iyi performans için bellek optimizasyonu devre dışı bırakılmıştır).


**Returns:**
boolean
### setOptimizeMemoryUsage(boolean value) {#setOptimizeMemoryUsage-boolean-}
```
public final void setOptimizeMemoryUsage(boolean value)
```


HTML'den belge oluşturulurken bellek kullanımını azaltma maliyeti olarak performansı düşüren bellek optimizasyon mekanizmalarını etkinleştirir.
Bu seçeneği true olarak ayarlamak, büyük belgeler oluşturulurken daha yavaş kaydetme süresi pahasına bellek tüketimini önemli ölçüde azaltabilir.
Varsayılan değer false'tur (daha iyi performans için bellek optimizasyonu devre dışı bırakılmıştır).


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

