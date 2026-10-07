---
title: "TtfFont"
second_title: "GroupDocs.Editor Java için API Referansı"
description: "TTF TrueType Font formatında bir fontu temsil eder"
type: docs
weight: 15
url: /tr/java/com.groupdocs.editor.htmlcss.resources.fonts/ttffont/
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
|  | [TtfFont(String name, String contentInBase64)](#TtfFont-java.lang.String-java.lang.String-) | İçeriği base64 kodlu olarak temsil eden yeni TtfFont sınıfını oluşturur |
dize ve belirtilen adla
|
|  | [TtfFont(String name, InputStream binaryContent)](#TtfFont-java.lang.String-java.io.InputStream-) | İçeriği bayt akışı olarak temsil eden yeni TtfFont sınıfını oluşturur ve |
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
|  | [isValid(InputStream binaryContent)](#isValid-java.io.InputStream-) | Belirtilen akışın geçerli bir TTF fontu olup olmadığını kontrol eder |
|
|  | [isValid(String contentInBase64)](#isValid-java.lang.String-) | Belirtilen base64 kodlu dizgenin geçerli bir TTF fontu olup olmadığını kontrol eder |
|
|  | [getType()](#getType--) | FontType.Ttf döndürür |
|
### TtfFont(String name, String contentInBase64) {#TtfFont-java.lang.String-java.lang.String-}
```
public TtfFont(String name, String contentInBase64)
```


İçeriği base64 kodlu olarak temsil eden yeni TtfFont sınıfını oluşturur
dize ve belirtilen adla


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | ad | java.lang.String | TTF fontunun adı. Boş, null veya sadece boşluk olamaz. |
|
|  | contentInBase64 | java.lang.String | İçerik base64 kodlu dize olarak. Boş, null veya sadece boşluk olamaz. TTF içeriği değilse, bir istisna fırlatılacaktır. |
|

### TtfFont(String name, InputStream binaryContent) {#TtfFont-java.lang.String-java.io.InputStream-}
```
public TtfFont(String name, InputStream binaryContent)
```


İçeriği bayt akışı olarak temsil eden yeni TtfFont sınıfını oluşturur ve
belirtilen adla


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | ad | java.lang.String | TTF fontunun adı. Boş, null veya sadece boşluk olamaz. |
|
|  | binaryContent | java.io.InputStream | İçerik bayt akışı olarak. Okuma, orijinal konumdan başlar. Null olamaz. Okunabilir ve aranabilir olmalıdır. Bu örnek serbest bırakılırsa, bu akış da serbest bırakılacaktır. |
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


Belirtilen akışın geçerli bir TTF fontu olup olmadığını kontrol eder


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | binaryContent | java.io.InputStream | TTF kaynağı içeriyor gibi görünen bayt akışı |
|

**Returns:**
boolean - Belirtilen akış geçerli bir TTF yazı tipi içeriyorsa True, aksi takdirde false

### isValid(String contentInBase64) {#isValid-java.lang.String-}
```
public static boolean isValid(String contentInBase64)
```


Belirtilen base64 kodlu dizgenin geçerli bir TTF fontu olup olmadığını kontrol eder


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | Tahmini TTF yazı tipinin içeriği base64 kodlu dize biçiminde |
|

**Returns:**
boolean - Belirtilen dize geçerli bir TTF yazı tipi içeriyorsa True, aksi takdirde false

### getType() {#getType--}
```
public FontType getType()
```


FontType.Ttf döndürür


**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype)
