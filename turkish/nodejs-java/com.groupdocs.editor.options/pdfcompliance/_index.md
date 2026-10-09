---
title: "PdfCompliance"
second_title: "GroupDocs.Editor Node.js için Java API Referansı"
description: "PDF standartları uyumluluk seviyesini belirtir."
type: docs
weight: 28
url: /tr/nodejs-java/com.groupdocs.editor.options/pdfcompliance/
---
**Inheritance:**
java.lang.Object
```
public final class PdfCompliance
```

PDF standartları uyumluluk seviyesini belirtir.

## Alanlar

| Alan | Açıklama |
| --- | --- |
|  | [Pdf17](#Pdf17) | PDF 1.7 (ISO 32000-1) standardı |
|
|  | [Pdf20](#Pdf20) | PDF 2.0 (ISO 32000-2) standardı |
|
|  | [PdfA1a](#PdfA1a) | PDF/A-1a standardı. |
|
|  | [PdfA1b](#PdfA1b) | PDF/A-1b (ISO 19005-1). |
|
|  | [PdfA2a](#PdfA2a) | PDF/A-2a (ISO 19005-2) standardı. |
|
|  | [PdfA2u](#PdfA2u) | PDF/A-2u (ISO 19005-2) standardı. |
|
|  | [PdfUa1](#PdfUa1) | PDF/UA-1 (ISO 14289-1) standardı. |
|
### Pdf17 {#Pdf17}
```
public static final int Pdf17
```


PDF 1.7 (ISO 32000-1) standardı


### Pdf20 {#Pdf20}
```
public static final int Pdf20
```


PDF 2.0 (ISO 32000-2) standardı


### PdfA1a {#PdfA1a}
```
public static final int PdfA1a
```


PDF/A-1a standardı. Bu seviye, PDF/A-1b'nin tüm gereksinimlerini içerir ve ayrıca belge yapısının dahil edilmesini gerektirir
(\"etiketli\" olarak da bilinir), belge içeriğinin aranabilir ve yeniden kullanılabilir olmasını sağlamak amacıyla.

<br />

*** ** * ** ***

Belge yapısını dışa aktarmanın bellek tüketimini önemli ölçüde artırdığını, özellikle büyük belgeler için, unutmayın.

<br />



### PdfA1b {#PdfA1b}
```
public static final int PdfA1b
```


PDF/A-1b (ISO 19005-1). PDF/A-1b, belgenin görsel görünümünün güvenilir bir şekilde yeniden üretilmesini sağlamayı amaçlar.


### PdfA2a {#PdfA2a}
```
public static final int PdfA2a
```


PDF/A-2a (ISO 19005-2) standardı. Bu seviye, PDF/A-2u'nun tüm gereksinimlerini içerir ve ayrıca belge yapısının dahil edilmesini (\"etiketli\" olarak da bilinir) sağlar; belge içeriğinin aranabilir ve yeniden kullanılabilir olmasını hedefler.

<br />

*** ** * ** ***

Belge yapısını dışa aktarmanın bellek tüketimini önemli ölçüde artırdığını, özellikle büyük belgeler için, unutmayın.

<br />



### PdfA2u {#PdfA2u}
```
public static final int PdfA2u
```


PDF/A-2u (ISO 19005-2) standardı. PDF/A-2u, belgelerin statik görsel görünümünün zaman içinde, oluşturma, depolama veya görüntüleme araç ve sistemlerinden bağımsız olarak korunmasını amaçlar. Ayrıca belgede bulunan tüm metin, Unicode kod noktaları dizisi olarak güvenilir bir şekilde çıkarılabilir.


### PdfUa1 {#PdfUa1}
```
public static final int PdfUa1
```


PDF/UA-1 (ISO 14289-1) standardı. PDF/UA'nın temel amacı, elektronik belgelerin PDF formatında, dosyanın erişilebilir olmasını sağlayacak şekilde temsil edilmesini tanımlamaktır.


