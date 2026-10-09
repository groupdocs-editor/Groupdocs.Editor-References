---
title: "ResourceTypeDetector"
second_title: "GroupDocs.Editor Node.js için Java API Referansı"
description: "Kaynak türleri ve biçimlerini tespit etmek için yardımcı statik yöntemler"
type: docs
weight: 10
url: /tr/nodejs-java/com.groupdocs.editor.htmlcss.resources/resourcetypedetector/
---
**Inheritance:**
java.lang.Object
```
public class ResourceTypeDetector
```

Kaynak türlerini (formatları) tespit etmek için yardımcı statik yöntemler.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [ResourceTypeDetector()](#ResourceTypeDetector--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [detectTypeFromFilename(String filename)](#detectTypeFromFilename-java.lang.String-) | Belirtilen dosya adından bir tür tespit eder ve bir örnek döndürür |
ilgili IResourceType
|
|  | [tryDetectResource(InputStream inputResourceStream, String name, IResourceType assumptiveFormat)](#tryDetectResource-java.io.InputStream-java.lang.String-com.groupdocs.editor.htmlcss.resources.IResourceType-) | Bir giriş akışını analiz etmeye çalışır ve desteklenebilir HTML'lerden birini oluşturur |
kaynakları, belirtilen varsayımsal türü dikkate alarak, eğer
null değilse
|
### ResourceTypeDetector() {#ResourceTypeDetector--}
```
public ResourceTypeDetector()
```


### detectTypeFromFilename(String filename) {#detectTypeFromFilename-java.lang.String-}
```
public static IResourceType detectTypeFromFilename(String filename)
```


Belirtilen dosya adından bir tür tespit eder ve bir örnek döndürür
ilgili IResourceType


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | dosya adı | java.lang.String | Bu yöntemin sonuç IResourceType uygulamasını çıkarmaya çalışacağı giriş dosya adı |
|

**Returns:**
[IResourceType](../../com.groupdocs.editor.htmlcss.resources/iresourcetype) - IResourceType implementation on success or NULL on failure

### tryDetectResource(InputStream inputResourceStream, String name, IResourceType assumptiveFormat) {#tryDetectResource-java.io.InputStream-java.lang.String-com.groupdocs.editor.htmlcss.resources.IResourceType-}
```
public static IHtmlResource tryDetectResource(InputStream inputResourceStream, String name, IResourceType assumptiveFormat)
```


Bir giriş akışını analiz etmeye çalışır ve desteklenebilir HTML'lerden birini oluşturur
kaynakları, belirtilen varsayımsal türü dikkate alarak, eğer
null değilse


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | inputResourceStream | java.io.InputStream | HTML kaynağı içerdiği varsayılan giriş akışı. Geçersiz ise bir istisna fırlatılacaktır. |
|
|  | ad | java.lang.String | Başarıyla oluşturulan ve döndürülen kaynak için kullanılacak kaynak adı. NULL, boş veya sadece boşluk olamaz. |
|
|  | assumptiveFormat | [IResourceType](../../com.groupdocs.editor.htmlcss.resources/iresourcetype) | Girdi HTML kaynağının varsayılan biçimi, en iyi performansı elde etmek için faydalıdır. Tamamen bilinmiyorsa, NULL değerini kullanın. Yanlış olabilir, bu sadece performansı düşürecektir. |
|

**Returns:**
[IHtmlResource](../../com.groupdocs.editor.htmlcss.resources/ihtmlresource) - Instance, which implements 'IHtmlResource' interface and represents one of supportable HTML resources on success, or NULL on failure

