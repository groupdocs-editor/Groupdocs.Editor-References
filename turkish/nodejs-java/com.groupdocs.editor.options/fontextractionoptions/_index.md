---
title: "FontExtractionOptions"
second_title: "GroupDocs.Editor Node.js için Java API Referansı"
description: "Font çıkarma seçenekleri, hangi fontların ve nereden çıkarılacağını kontrol eder"
type: docs
weight: 18
url: /tr/nodejs-java/com.groupdocs.editor.options/fontextractionoptions/
---
**Inheritance:**
java.lang.Object
```
public final class FontExtractionOptions
```

Font çıkarma seçenekleri, hangi fontların çıkarılacağını ve nereden
nereden

## Alanlar

| Alan | Açıklama |
| --- | --- |
|  | [NotExtract](#NotExtract) | Ne belge içinden ne de |
sistem.
|
|  | [ExtractAllEmbedded](#ExtractAllEmbedded) | Giriş Word belgesine gömülmüş olan tüm font kaynaklarını çıkarır |
belge, ne oldukları ne olursa olsun: özel veya sistem.
|
|  | [ExtractEmbeddedWithoutSystem](#ExtractEmbeddedWithoutSystem) | Yalnızca özel (özel olmayan) gömülü yazı tipi kaynaklarını çıkarır ( |
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


Ne belge içinden ne de
sistem. Varsayılan değer.


### ExtractAllEmbedded {#ExtractAllEmbedded}
```
public static final int ExtractAllEmbedded
```


Giriş Word belgesine gömülmüş olan tüm font kaynaklarını çıkarır
belge, ne oldukları ne olursa olsun: özel veya sistem.


*** ** * ** ***

Converter, giriş WordProcessing belgesine gömülü tüm %100 yazı tipi kaynaklarını bulur ve çıkarır, ancak bunların sistem mi yoksa özel mi olduğunu belirlemez; Windows Registry'ye veya sistem klasörlerine hiç dokunmaz.

<br />



### ExtractEmbeddedWithoutSystem {#ExtractEmbeddedWithoutSystem}
```
public static final int ExtractEmbeddedWithoutSystem
```


Yalnızca özel (özel olmayan) gömülü yazı tipi kaynaklarını çıkarır (
sistem)


*** ** * ** ***

Converter, tüm gömülü yazı tipi kaynaklarını bulur ve çıkarır, ardından bu yazı tiplerinden hangilerinin sistem, hangilerinin ise değil olduğunu belirlemeye çalışır. Bunu başarmak için converter, Windows Registry ve sistem klasörlerini kullanarak tüm sistem yazı tiplerinin bir listesini almaya çalışır ve ardından bu listeyi gömülü yazı tipleri kümesiyle karşılaştırır. Sonuç olarak, sistemde bulunmayan gömülü yazı tiplerinin yalnızca bir alt kümesi döndürülür.

<br />



### ExtractAll {#ExtractAll}
```
public static final int ExtractAll
```


Giriş WordProcessing içinde kullanılan tüm yazı tiplerini çıkarmaya çalışır
belge, sistem yazı tipleri dahil.


*** ** * ** ***

Converter, bir giriş WordProcessing belgesini analiz ediyor ve kullanılan tüm yazı tiplerini buluyor. Bu yazı tiplerinin tümü giriş belgesine gömülü ise, converter bunları çıkarır ve döndürür. Aksi takdirde, gömülü yazı tipleri koleksiyonu belgede kullanılan tüm yazı tiplerini kapsamazsa veya boşsa, converter bu yazı tipi kaynaklarını Windows Registry ve sistem klasörlerini kullanarak sistemden çıkarmaya çalışır.

<br />



### getFontExtractionOptions() {#getFontExtractionOptions--}
```
public static int[] getFontExtractionOptions()
```




**Returns:**
int[]
