---
title: "Woff2Font"
second_title: "GroupDocs.Editor Node.js için Java API Referansı"
description: "WOFF2 Web Open Font Format formatında bir yazı tipini temsil eder"
type: docs
weight: 16
url: /tr/nodejs-java/com.groupdocs.editor.htmlcss.resources.fonts/woff2font/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.fonts.FontResourceBase](../../com.groupdocs.editor.htmlcss.resources.fonts/fontresourcebase)
```
public final class Woff2Font extends FontResourceBase
```

WOFF2 (Web Open Font Format) formatındaki bir yazı tipini temsil eder.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
|  | [Woff2Font(String name, String contentInBase64)](#Woff2Font-java.lang.String-java.lang.String-) | İçeriğinden, base64 kodlu olarak temsil edilen yeni Woff2Font sınıfı oluşturur |
dize ve belirtilen ad
|
|  | [Woff2Font(String name, InputStream binaryContent)](#Woff2Font-java.lang.String-java.io.InputStream-) | İçeriğinden, bayt akışı olarak temsil edilen yeni Woff2Font sınıfı oluşturur ve |
belirtilen adla
|
## Alanlar

| Alan | Açıklama |
| --- | --- |
|  | [RequiredHeaderSize](#RequiredHeaderSize) | WOFF2 başlık boyutu (bayt cinsinden), doğrulama için gereklidir |
|
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [isValid(InputStream binaryContent)](#isValid-java.io.InputStream-) | Belirtilen akışın geçerli bir WOFF2 yazı tipi olup olmadığını kontrol eder |
|
|  | [isValid(String contentInBase64)](#isValid-java.lang.String-) | Belirtilen base64 kodlu dizenin geçerli bir WOFF2 yazı tipi olup olmadığını kontrol eder |
|
|  | [getType()](#getType--) | FontType.Woff2 değerini döndürür |
|
### Woff2Font(String name, String contentInBase64) {#Woff2Font-java.lang.String-java.lang.String-}
```
public Woff2Font(String name, String contentInBase64)
```


İçeriğinden, base64 kodlu olarak temsil edilen yeni Woff2Font sınıfı oluşturur
dize ve belirtilen ad


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | ad | java.lang.String | WOFF2 yazı tipinin adı. Boş, null veya sadece boşluk olamaz. |
|
|  | contentInBase64 | java.lang.String | İçerik base64 kodlu dize biçiminde. Boş, null veya sadece boşluk olamaz. Eğer bir WOFF2 içeriği değilse, istisna fırlatılacak. |
|

### Woff2Font(String name, InputStream binaryContent) {#Woff2Font-java.lang.String-java.io.InputStream-}
```
public Woff2Font(String name, InputStream binaryContent)
```


İçeriğinden, bayt akışı olarak temsil edilen yeni Woff2Font sınıfı oluşturur ve
belirtilen adla


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | ad | java.lang.String | WOFF2 yazı tipinin adı. Boş, null veya sadece boşluk olamaz. |
|
|  | binaryContent | java.io.InputStream | İçerik bayt akışı olarak. Okuma orijinal konumdan başlar. Null olamaz. Okunabilir ve aranabilir olmalıdır. Bu örnek iptal edilirse, bu akış da iptal edilecektir. |
|

### RequiredHeaderSize {#RequiredHeaderSize}
```
public static final int RequiredHeaderSize
```


WOFF2 başlık boyutu (bayt cinsinden), doğrulama için gereklidir


### isValid(InputStream binaryContent) {#isValid-java.io.InputStream-}
```
public static boolean isValid(InputStream binaryContent)
```


Belirtilen akışın geçerli bir WOFF2 yazı tipi olup olmadığını kontrol eder


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | binaryContent | java.io.InputStream | WOFF2 kaynağı içeriyor gibi görünen bayt akışı |
|

**Returns:**
boolean - Belirtilen akış geçerli bir WOFF2 yazı tipi içeriyorsa true, aksi takdirde false

### isValid(String contentInBase64) {#isValid-java.lang.String-}
```
public static boolean isValid(String contentInBase64)
```


Belirtilen base64 kodlu dizenin geçerli bir WOFF2 yazı tipi olup olmadığını kontrol eder


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | Tahmini WOFF2 yazı tipinin içeriği base64 kodlu dize biçiminde |
|

**Returns:**
boolean - Belirtilen dize geçerli bir WOFF2 yazı tipi içeriyorsa true, aksi takdirde false

### getType() {#getType--}
```
public FontType getType()
```


FontType.Woff2 değerini döndürür


**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype)
