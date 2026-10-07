---
title: "FontExtractionOptions"
second_title: "GroupDocs.Editor Java için API Referansı"
description: "Yazı tipi çıkarma seçenekleri, hangi yazı tiplerinin çıkarılacağını ve nereden alınacağını kontrol eder"
type: docs
weight: 18
url: /tr/java/com.groupdocs.editor.options/fontextractionoptions/
---
**Inheritance:**
java.lang.Object
```
public final class FontExtractionOptions
```

Yazı tipi çıkarma seçenekleri, hangi yazı tiplerinin çıkarılacağını ve nereden alınacağını kontrol eder
nereden

## Alanlar

| Alan | Açıklama |
| --- | --- |
|  | [NotExtract](#NotExtract) | Belgeden ya da |
sistemden.
|
|  | [ExtractAllEmbedded](#ExtractAllEmbedded) | Giriş Word belgesine gömülü tüm yazı tipi kaynaklarını çıkarır |
belge, bunların ne olduğu fark etmeksizin: özel veya sistem.
|
|  | [ExtractEmbeddedWithoutSystem](#ExtractEmbeddedWithoutSystem) | Yalnızca özel (not |
sistem)
|
|  | [ExtractAll](#ExtractAll) | Giriş WordProcessing içinde kullanılan tüm yazı tiplerini çıkarmaya çalışır |
belge, sistem yazı tipleri dahil.
|
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getFontExtractionOptions()](#getFontExtractionOptions--) |  |
### NotExtract {#NotExtract}
```
public static final int NotExtract
```


Belgeden ya da
sistem. Varsayılan değer.


### ExtractAllEmbedded {#ExtractAllEmbedded}
```
public static final int ExtractAllEmbedded
```


Giriş Word belgesine gömülü tüm yazı tipi kaynaklarını çıkarır
belge, bunların ne olduğu fark etmeksizin: özel veya sistem.


*** ** * ** ***

Dönüştürücü, giriş WordProcessing belgesine gömülü olan tüm %100 yazı tipi kaynaklarını bulur ve çıkarır, ancak bunların sistem mi yoksa özel mi olduğunu belirlemez; Windows Registry'ye veya sistem klasörlerine hiç dokunmaz.

<br />



### ExtractEmbeddedWithoutSystem {#ExtractEmbeddedWithoutSystem}
```
public static final int ExtractEmbeddedWithoutSystem
```


Yalnızca özel (not
sistem)


*** ** * ** ***

Dönüştürücü, tüm gömülü yazı tipi kaynaklarını bulur ve çıkarır, ardından bu yazı tiplerinden hangilerinin sistem, hangilerinin ise değil olduğunu belirlemeye çalışır. Bunu başarmak için, dönüştürücü Windows Registry ve sistem klasörlerini kullanarak tüm sistem yazı tiplerinin bir listesini almaya çalışır ve ardından bu listeyi gömülü yazı tipleri kümesiyle karşılaştırır. Sonuç olarak, sistemde bulunmayan gömülü yazı tiplerinin yalnızca bir alt kümesi döndürülecektir.

<br />



### ExtractAll {#ExtractAll}
```
public static final int ExtractAll
```


Giriş WordProcessing içinde kullanılan tüm yazı tiplerini çıkarmaya çalışır
belge, sistem yazı tipleri dahil.


*** ** * ** ***

Dönüştürücü, bir giriş WordProcessing belgesini analiz eder ve orada kullanılan tüm yazı tiplerini bulur. Bu yazı tiplerinin tümü giriş belgesine gömülü ise, dönüştürücü onları çıkarır ve döndürür. Aksi takdirde, gömülü yazı tipleri koleksiyonu belgede kullanılan tüm yazı tiplerini kapsamazsa veya boşsa, dönüştürücü bu yazı tipi kaynaklarını Windows Registry ve sistem klasörlerini kullanarak sistemden çıkarmaya çalışır.

<br />



### getFontExtractionOptions() {#getFontExtractionOptions--}
```
public static int[] getFontExtractionOptions()
```




**Returns:**
int[]
