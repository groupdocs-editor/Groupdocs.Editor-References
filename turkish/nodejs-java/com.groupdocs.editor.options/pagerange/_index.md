---
title: "PageRange"
second_title: "GroupDocs.Editor Node.js için Java API Referansı"
description: "Açık veya kapalı sınırları olabilen bir sayfa aralığını kapsar."
type: docs
weight: 27
url: /tr/nodejs-java/com.groupdocs.editor.options/pagerange/
---
**Inheritance:**
java.lang.Object
```
public class PageRange
```

Açık veya kapalı sınırları olabilen bir sayfa aralığını kapsar. Varsayılan olarak "tamamen açık"tır - mevcut tüm sayfaları içerir. Sayfa numaralandırması 0'dan değil, 1'den başlar.

<br />

*** ** * ** ***

Herhangi bir belirli belgeyle ilişkili olmayan ve herhangi bir belge için sayfa aralığını temsil edebilen, değiştirilemez bir yapı (struct) olup bir sayfa aralığını kapsar.

<br />


## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [PageRange()](#PageRange--) |  |
## Alanlar

| Alan | Açıklama |
| --- | --- |
|  | [AllPages](#AllPages) | Bir belgenin mevcut tüm sayfalarını temsil eder. |
|
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getStartNumber()](#getStartNumber--) | Kapsayıcı başlangıç sayfa numarası, bu sayfa aralığının başladığı yer. |
|
|  | [getEndNumber()](#getEndNumber--) | Kapsam dışı bitiş sayfa numarası, bu sayfa aralığının devam ettiği ve sadece bu numarada sona erdiği yer. |
|
|  | [getCount()](#getCount--) | Aralık içindeki sayfa sayıları. |
|
|  | [isDefault()](#isDefault--) | Bu örnek, varsayılan "tamamen açık" sayfa aralığını temsil edip etmediğini gösterir, yani. |
|
|  | [equals(PageRange other)](#equals-com.groupdocs.editor.options.PageRange-) | Bu PageRange örneğinin belirtilenle eşit olup olmadığını algılar. |
|
|  | [fromBeginningWithCount(int pageCount)](#fromBeginningWithCount-int-) | İlk sayfadan başlayan ve belirtilen sayıda sayfaya sahip bir sayfa aralığı oluşturur. |
|
|  | [fromStartPageTillEnd(int startPageNumber)](#fromStartPageTillEnd-int-) | Belirtilen sayfa numarasından başlayan ve belgenin sonuna kadar devam eden bir sayfa aralığı oluşturur. |
|
|  | [fromStartPageWithCount(int startPageNumber, int pageCount)](#fromStartPageWithCount-int-int-) | Belirtilen sayfa numarasından başlayan ve belirtilen sayıda sayfaya sahip bir sayfa aralığı oluşturur veya sınırsız sayfa sayısı (sona kadar) oluşturur. |
|
|  | [fromStartPageTillEndPage(int startPageNumber, int endPageNumber)](#fromStartPageTillEndPage-int-int-) | Belirtilen sayfa numarasından (kapsayıcı) başlayan ve belirtilen sayfa numarasına (kapsam dışı) kadar devam eden bir sayfa aralığı oluşturur. |
|
### PageRange() {#PageRange--}
```
public PageRange()
```


### AllPages {#AllPages}
```
public static final PageRange AllPages
```


Bir belgenin mevcut tüm sayfalarını temsil eder. Varsayılan değer.


### getStartNumber() {#getStartNumber--}
```
public final int getStartNumber()
```


Kapsayıcı başlangıç sayfa numarası, bu sayfa aralığının başladığı yer. Eğer 1 ise - sayfa aralığı belgenin ilk sayfasından başlar.


**Returns:**
int
### getEndNumber() {#getEndNumber--}
```
public final int getEndNumber()
```


Kapsam dışı bitiş sayfa numarası, bu sayfa aralığının devam ettiği ve sadece bu numarada sona erdiği yer. Eğer 0 ise - sayfa aralığı belgenin sonuna kadar yayılır.


**Returns:**
int
### getCount() {#getCount--}
```
public final int getCount()
```


Aralık içindeki sayfa sayıları. Eğer 0 ise - sayfa aralığı belgenin sonuna kadar yayılır, kaç sayfa olursa olsun.


**Returns:**
int
### isDefault() {#isDefault--}
```
public final boolean isDefault()
```


Bu örneğin varsayılan "tamamen açık" sayfa aralığını temsil edip etmediğini gösterir, yani bir belgenin tüm sayfalarından oluşur.


**Returns:**
boolean
### equals(PageRange other) {#equals-com.groupdocs.editor.options.PageRange-}
```
public final boolean equals(PageRange other)
```


Bu PageRange örneğinin belirtilenle eşit olup olmadığını algılar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | other | [PageRange](../../com.groupdocs.editor.options/pagerange) | Eşitliği kontrol edilecek diğer PageRange örneği. |
|

**Returns:**
boolean - true eşittir; false eşit değildir.

### fromBeginningWithCount(int pageCount) {#fromBeginningWithCount-int-}
```
public static PageRange fromBeginningWithCount(int pageCount)
```


İlk sayfadan başlayan ve belirtilen sayıda sayfaya sahip bir sayfa aralığı oluşturur.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | pageCount | int | Sayfa sayısı, sıfırdan büyük olmalıdır. |
|

**Returns:**
[PageRange](../../com.groupdocs.editor.options/pagerange) - New PageRange instance

### fromStartPageTillEnd(int startPageNumber) {#fromStartPageTillEnd-int-}
```
public static PageRange fromStartPageTillEnd(int startPageNumber)
```


Belirtilen sayfa numarasından başlayan ve belgenin sonuna kadar devam eden bir sayfa aralığı oluşturur.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | startPageNumber | int | Sayfa numarası, sayfa aralığının başladığı yer, kapsayıcı. Sayfa numaraları 1 tabanlıdır, bu yüzden sıfırdan büyük olmalıdır. |
|

**Returns:**
[PageRange](../../com.groupdocs.editor.options/pagerange) - New PageRange instance

### fromStartPageWithCount(int startPageNumber, int pageCount) {#fromStartPageWithCount-int-int-}
```
public static PageRange fromStartPageWithCount(int startPageNumber, int pageCount)
```


Belirtilen sayfa numarasından başlayan ve belirtilen sayıda sayfaya sahip bir sayfa aralığı oluşturur veya sınırsız sayfa sayısı (sona kadar) oluşturur.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | startPageNumber | int | Sayfa numarası, sayfa aralığının başladığı yer, kapsayıcı. Sayfa numaraları 1 tabanlıdır, bu yüzden sıfırdan büyük olmalıdır. |
|
|  | pageCount | int | Sayfa sayısı, sıfırdan büyük olmalıdır. Eğer sıfır ise - bu, belgenin sonuna kadar tüm sayfalar anlamına gelir. |
|

**Returns:**
[PageRange](../../com.groupdocs.editor.options/pagerange) - New PageRange instance

### fromStartPageTillEndPage(int startPageNumber, int endPageNumber) {#fromStartPageTillEndPage-int-int-}
```
public static PageRange fromStartPageTillEndPage(int startPageNumber, int endPageNumber)
```


Belirtilen sayfa numarasından (kapsayıcı) başlayan ve belirtilen sayfa numarasına (kapsam dışı) kadar devam eden bir sayfa aralığı oluşturur.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | startPageNumber | int | Sayfa numarası, sayfa aralığının başladığı yer, kapsayıcı. Sayfa numaraları 1 tabanlıdır, bu yüzden sıfırdan büyük olmalıdır. |
|
|  | endPageNumber | int | Sayfa numarası, sayfa aralığının sona erdiği yer, kapsam dışı. Sayfa numaraları 1 tabanlıdır, bu yüzden sıfırdan büyük olmalı ve ayrıca startPageNumber'dan büyük olmalıdır. |
|

**Returns:**
[PageRange](../../com.groupdocs.editor.options/pagerange) - 
