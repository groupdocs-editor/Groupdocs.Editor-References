---
title: "WoffFont"
second_title: "GroupDocs.Editor Node.js için Java API Referansı"
description: "WOFF Web Open Font Format formatında bir fontu temsil eder"
type: docs
weight: 17
url: /tr/nodejs-java/com.groupdocs.editor.htmlcss.resources.fonts/wofffont/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.fonts.FontResourceBase](../../com.groupdocs.editor.htmlcss.resources.fonts/fontresourcebase)
```
public final class WoffFont extends FontResourceBase
```

WOFF (Web Open Font Format) formatındaki bir yazı tipini temsil eder.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
|  | [WoffFont(String name, String contentInBase64)](#WoffFont-java.lang.String-java.lang.String-) | İçeriği base64 kodlu olarak temsil eden yeni WoffFont sınıfını oluşturur |
dize ve belirtilen ad
|
|  | [WoffFont(String name, InputStream binaryContent)](#WoffFont-java.lang.String-java.io.InputStream-) | İçeriği bayt akışı olarak temsil eden yeni WoffFont sınıfını oluşturur ve |
belirtilen adla
|
## Alanlar

| Alan | Açıklama |
| --- | --- |
|  | [RequiredHeaderSize](#RequiredHeaderSize) | WOFF başlık boyutu (bayt cinsinden), doğrulama için gereklidir |
|
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [isValid(InputStream binaryContent)](#isValid-java.io.InputStream-) | Belirtilen akışın geçerli bir WOFF fontu olup olmadığını denetler |
|
|  | [isValid(String contentInBase64)](#isValid-java.lang.String-) | Belirtilen base64 kodlu dizgenin geçerli bir WOFF fontu olup olmadığını denetler |
|
|  | [getType()](#getType--) | FontType.Woff değerini döndürür |
|
### WoffFont(String name, String contentInBase64) {#WoffFont-java.lang.String-java.lang.String-}
```
public WoffFont(String name, String contentInBase64)
```


İçeriği base64 kodlu olarak temsil eden yeni WoffFont sınıfını oluşturur
dize ve belirtilen ad


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | ad | java.lang.String | WOFF fontunun adı. Null, boş veya sadece boşluk olamaz. |
|
|  | contentInBase64 | java.lang.String | İçerik base64 kodlu dize olarak. Null, boş veya sadece boşluk olamaz. WOFF içeriği değilse, istisna fırlatılacaktır. |
|

### WoffFont(String name, InputStream binaryContent) {#WoffFont-java.lang.String-java.io.InputStream-}
```
public WoffFont(String name, InputStream binaryContent)
```


İçeriği bayt akışı olarak temsil eden yeni WoffFont sınıfını oluşturur ve
belirtilen adla


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | ad | java.lang.String | WOFF fontunun adı. Null, boş veya sadece boşluk olamaz. |
|
|  | binaryContent | java.io.InputStream | İçerik bayt akışı olarak. Okuma orijinal konumdan başlar. Null olamaz. Okunabilir ve aranabilir olmalıdır. Bu örnek iptal edilirse, bu akış da iptal edilecektir. |
|

### RequiredHeaderSize {#RequiredHeaderSize}
```
public static final int RequiredHeaderSize
```


WOFF başlık boyutu (bayt cinsinden), doğrulama için gereklidir


### isValid(InputStream binaryContent) {#isValid-java.io.InputStream-}
```
public static boolean isValid(InputStream binaryContent)
```


Belirtilen akışın geçerli bir WOFF fontu olup olmadığını denetler


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | binaryContent | java.io.InputStream | Muhtemelen bir WOFF kaynağı içeren bayt akışı |
|

**Returns:**
boolean - Belirtilen akış geçerli bir WOFF fontu içeriyorsa True, aksi takdirde false

### isValid(String contentInBase64) {#isValid-java.lang.String-}
```
public static boolean isValid(String contentInBase64)
```


Belirtilen base64 kodlu dizgenin geçerli bir WOFF fontu olup olmadığını denetler


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | Muhtemelen WOFF fontunun içeriği base64 kodlu dize biçiminde |
|

**Returns:**
boolean - Belirtilen dize geçerli bir WOFF fontu içeriyorsa True, aksi takdirde false

### getType() {#getType--}
```
public FontType getType()
```


FontType.Woff değerini döndürür


**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype)
