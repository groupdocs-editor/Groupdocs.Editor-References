---
title: "Woff2Font"
second_title: "GroupDocs.Editor Java için API Referansı"
description: "WOFF2 Web Open Font Format formatında bir fontu temsil eder"
type: docs
weight: 16
url: /tr/java/com.groupdocs.editor.htmlcss.resources.fonts/woff2font/
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
|  | [Woff2Font(String name, String contentInBase64)](#Woff2Font-java.lang.String-java.lang.String-) | İçeriği base64 kodlu olarak temsil eden yeni Woff2Font sınıfını oluşturur |
dize ve belirtilen adla
|
|  | [Woff2Font(String name, InputStream binaryContent)](#Woff2Font-java.lang.String-java.io.InputStream-) | İçeriği bayt akışı olarak temsil eden yeni Woff2Font sınıfını oluşturur ve |
belirtilen adla
|
## Alanlar

| Alan | Açıklama |
| --- | --- |
|  | [RequiredHeaderSize](#RequiredHeaderSize) | Doğrulama için gerekli olan WOFF2 başlık boyutu (bayt cinsinden) |
|
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [isValid(InputStream binaryContent)](#isValid-java.io.InputStream-) | Belirtilen akışın geçerli bir WOFF2 fontu olup olmadığını kontrol eder |
|
|  | [isValid(String contentInBase64)](#isValid-java.lang.String-) | Belirtilen base64 kodlu dizgenin geçerli bir WOFF2 fontu olup olmadığını kontrol eder |
|
|  | [getType()](#getType--) | FontType.Woff2 döndürür |
|
### Woff2Font(String name, String contentInBase64) {#Woff2Font-java.lang.String-java.lang.String-}
```
public Woff2Font(String name, String contentInBase64)
```


İçeriği base64 kodlu olarak temsil eden yeni Woff2Font sınıfını oluşturur
dize ve belirtilen adla


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | ad | java.lang.String | WOFF2 fontunun adı. Boş, null veya sadece boşluk olamaz. |
|
|  | contentInBase64 | java.lang.String | İçerik base64 kodlu dize olarak. Boş, null veya sadece boşluk olamaz. WOFF2 içeriği değilse, bir istisna fırlatılacaktır. |
|

### Woff2Font(String name, InputStream binaryContent) {#Woff2Font-java.lang.String-java.io.InputStream-}
```
public Woff2Font(String name, InputStream binaryContent)
```


İçeriği bayt akışı olarak temsil eden yeni Woff2Font sınıfını oluşturur ve
belirtilen adla


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | ad | java.lang.String | WOFF2 fontunun adı. Boş, null veya sadece boşluk olamaz. |
|
|  | binaryContent | java.io.InputStream | İçerik bayt akışı olarak. Okuma orijinal konumdan başlar. Null olamaz. Okunabilir ve aranabilir olmalıdır. Bu örnek iptal edilirse, bu akış da iptal edilecektir. |
|

### RequiredHeaderSize {#RequiredHeaderSize}
```
public static final int RequiredHeaderSize
```


Doğrulama için gerekli olan WOFF2 başlık boyutu (bayt cinsinden)


### isValid(InputStream binaryContent) {#isValid-java.io.InputStream-}
```
public static boolean isValid(InputStream binaryContent)
```


Belirtilen akışın geçerli bir WOFF2 fontu olup olmadığını kontrol eder


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | binaryContent | java.io.InputStream | Muhtemelen bir WOFF2 kaynağı içeren bayt akışı |
|

**Returns:**
boolean - Belirtilen akış geçerli bir WOFF2 fontu içeriyorsa true, aksi takdirde false

### isValid(String contentInBase64) {#isValid-java.lang.String-}
```
public static boolean isValid(String contentInBase64)
```


Belirtilen base64 kodlu dizgenin geçerli bir WOFF2 fontu olup olmadığını kontrol eder


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | Muhtemelen WOFF2 fontunun içeriği, base64 kodlu dize biçiminde |
|

**Returns:**
boolean - Belirtilen dize geçerli bir WOFF2 fontu içeriyorsa true, aksi takdirde false

### getType() {#getType--}
```
public FontType getType()
```


FontType.Woff2 döndürür


**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype)
