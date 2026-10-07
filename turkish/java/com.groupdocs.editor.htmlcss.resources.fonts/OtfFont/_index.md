---
title: "OtfFont"
second_title: "GroupDocs.Editor Java için API Referansı"
description: "OTF Open Type Format formatında bir yazı tipini temsil eder"
type: docs
weight: 13
url: /tr/java/com.groupdocs.editor.htmlcss.resources.fonts/otffont/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.fonts.FontResourceBase](../../com.groupdocs.editor.htmlcss.resources.fonts/fontresourcebase)
```
public final class OtfFont extends FontResourceBase
```

OTF (Open Type Format) formatındaki bir yazı tipini temsil eder.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
|  | [OtfFont(String name, String contentInBase64)](#OtfFont-java.lang.String-java.lang.String-) | İçeriği base64 kodlu olarak temsil eden yeni OtfFont sınıfı oluşturur |
dize ve belirtilen adla
|
|  | [OtfFont(String name, InputStream binaryContent)](#OtfFont-java.lang.String-java.io.InputStream-) | İçeriği bayt akışı olarak temsil eden yeni OtfFont sınıfı oluşturur ve |
belirtilen adla
|
## Alanlar

| Alan | Açıklama |
| --- | --- |
|  | [RequiredHeaderSize](#RequiredHeaderSize) | Doğrulama için gerekli olan OTF başlık boyutu (bayt cinsinden) |
|
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [isValid(InputStream binaryContent)](#isValid-java.io.InputStream-) | Belirtilen akışın geçerli bir OTF yazı tipi olup olmadığını denetler |
|
|  | [isValid(String contentInBase64)](#isValid-java.lang.String-) | Belirtilen base64 kodlu dizgenin geçerli bir OTF yazı tipi olup olmadığını denetler |
|
|  | [getType()](#getType--) | Döndürür |
FontType.Otf
([FontType.getOtf](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype#getOtf))
|
### OtfFont(String name, String contentInBase64) {#OtfFont-java.lang.String-java.lang.String-}
```
public OtfFont(String name, String contentInBase64)
```


İçeriği base64 kodlu olarak temsil eden yeni OtfFont sınıfı oluşturur
dize ve belirtilen adla


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | ad | java.lang.String | OTF yazı tipinin adı. Boş, null veya yalnız boşluk olamaz. |
|
|  | contentInBase64 | java.lang.String | İçerik base64 kodlu dize olarak. Boş, null veya yalnız boşluk olamaz. OTF içeriği değilse, istisna fırlatılacaktır. |
|

### OtfFont(String name, InputStream binaryContent) {#OtfFont-java.lang.String-java.io.InputStream-}
```
public OtfFont(String name, InputStream binaryContent)
```


İçeriği bayt akışı olarak temsil eden yeni OtfFont sınıfı oluşturur ve
belirtilen adla


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | ad | java.lang.String | OTF yazı tipinin adı. Boş, null veya yalnız boşluk olamaz. |
|
|  | binaryContent | java.io.InputStream | İçerik bayt akışı olarak. Okuma, orijinal konumdan başlar. Null olamaz. Okunabilir ve aranabilir olmalıdır. Bu örnek serbest bırakılırsa, bu akış da serbest bırakılacaktır. |
|

### RequiredHeaderSize {#RequiredHeaderSize}
```
public static final int RequiredHeaderSize
```


Doğrulama için gerekli olan OTF başlık boyutu (bayt cinsinden)


### isValid(InputStream binaryContent) {#isValid-java.io.InputStream-}
```
public static boolean isValid(InputStream binaryContent)
```


Belirtilen akışın geçerli bir OTF yazı tipi olup olmadığını denetler


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | binaryContent | java.io.InputStream | OTF kaynağı içerdiği varsayılan bayt akışı |
|

**Returns:**
boolean - Belirtilen akış geçerli bir OTF yazı tipi içeriyorsa true, aksi takdirde false

### isValid(String contentInBase64) {#isValid-java.lang.String-}
```
public static boolean isValid(String contentInBase64)
```


Belirtilen base64 kodlu dizgenin geçerli bir OTF yazı tipi olup olmadığını denetler


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | OTF olduğu varsayılan yazı tipinin içeriği, base64 kodlu dize biçiminde |
|

**Returns:**
boolean - Belirtilen dize geçerli bir OTF yazı tipi içeriyorsa true, aksi takdirde false

### getType() {#getType--}
```
public FontType getType()
```


Döndürür
FontType.Otf
([FontType.getOtf](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype#getOtf))


**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) - 
