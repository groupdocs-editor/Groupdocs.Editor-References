---
title: "TtfFont"
second_title: "GroupDocs.Editor Node.js için Java API Referansı"
description: "TTF TrueType Font formatında bir yazı tipini temsil eder"
type: docs
weight: 15
url: /tr/nodejs-java/com.groupdocs.editor.htmlcss.resources.fonts/ttffont/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.fonts.FontResourceBase](../../com.groupdocs.editor.htmlcss.resources.fonts/fontresourcebase)
```
public final class TtfFont extends FontResourceBase
```

TTF (TrueType Font) formatındaki bir yazı tipini temsil eder.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
|  | [TtfFont(String name, String contentInBase64)](#TtfFont-java.lang.String-java.lang.String-) | İçerikten, base64 kodlu olarak temsil edilen yeni TtfFont sınıfı oluşturur |
dize ve belirtilen ad
|
|  | [TtfFont(String name, InputStream binaryContent)](#TtfFont-java.lang.String-java.io.InputStream-) | İçerikten, bayt akışı olarak temsil edilen yeni TtfFont sınıfı oluşturur ve |
belirtilen adla
|
## Alanlar

| Alan | Açıklama |
| --- | --- |
|  | [RequiredHeaderSize](#RequiredHeaderSize) | Doğrulama için gerekli olan TTF başlık boyutu (bayt cinsinden) |
|
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [isValid(InputStream binaryContent)](#isValid-java.io.InputStream-) | Belirtilen akışın geçerli bir TTF yazı tipi olup olmadığını kontrol eder |
|
|  | [isValid(String contentInBase64)](#isValid-java.lang.String-) | Belirtilen base64 kodlu dizenin geçerli bir TTF yazı tipi olup olmadığını kontrol eder |
|
|  | [getType()](#getType--) | FontType.Ttf değerini döndürür |
|
### TtfFont(String name, String contentInBase64) {#TtfFont-java.lang.String-java.lang.String-}
```
public TtfFont(String name, String contentInBase64)
```


İçerikten, base64 kodlu olarak temsil edilen yeni TtfFont sınıfı oluşturur
dize ve belirtilen ad


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | ad | java.lang.String | TTF yazı tipinin adı. Null, boş veya sadece boşluk olamaz. |
|
|  | contentInBase64 | java.lang.String | İçerik base64 kodlu dize olarak. Null, boş veya sadece boşluk olamaz. TTF içeriği değilse, istisna fırlatılacaktır. |
|

### TtfFont(String name, InputStream binaryContent) {#TtfFont-java.lang.String-java.io.InputStream-}
```
public TtfFont(String name, InputStream binaryContent)
```


İçerikten, bayt akışı olarak temsil edilen yeni TtfFont sınıfı oluşturur ve
belirtilen adla


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | ad | java.lang.String | TTF yazı tipinin adı. Null, boş veya sadece boşluk olamaz. |
|
|  | binaryContent | java.io.InputStream | İçerik bayt akışı olarak. Okuma orijinal konumdan başlar. Null olamaz. Okunabilir ve aranabilir olmalıdır. Bu örnek serbest bırakılırsa, bu akış da serbest bırakılacaktır. |
|

### RequiredHeaderSize {#RequiredHeaderSize}
```
public static final int RequiredHeaderSize
```


Doğrulama için gerekli olan TTF başlık boyutu (bayt cinsinden)


### isValid(InputStream binaryContent) {#isValid-java.io.InputStream-}
```
public static boolean isValid(InputStream binaryContent)
```


Belirtilen akışın geçerli bir TTF yazı tipi olup olmadığını kontrol eder


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | binaryContent | java.io.InputStream | Tahmini olarak bir TTF kaynağı içeren bayt akışı |
|

**Returns:**
boolean - Belirtilen akış geçerli bir TTF yazı tipini içeriyorsa True, aksi takdirde false

### isValid(String contentInBase64) {#isValid-java.lang.String-}
```
public static boolean isValid(String contentInBase64)
```


Belirtilen base64 kodlu dizenin geçerli bir TTF yazı tipi olup olmadığını kontrol eder


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | Tahmini TTF yazı tipinin içeriği base64 kodlu dize biçiminde |
|

**Returns:**
boolean - Belirtilen dize geçerli bir TTF yazı tipini içeriyorsa True, aksi takdirde false

### getType() {#getType--}
```
public FontType getType()
```


FontType.Ttf değerini döndürür


**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype)
