---
title: "TtcFont"
second_title: "GroupDocs.Editor Node.js için Java API Referansı"
description: "TTC TrueType Collection formatında bir fontu temsil eder"
type: docs
weight: 14
url: /tr/nodejs-java/com.groupdocs.editor.htmlcss.resources.fonts/ttcfont/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.fonts.FontResourceBase](../../com.groupdocs.editor.htmlcss.resources.fonts/fontresourcebase)
```
public final class TtcFont extends FontResourceBase
```

TTC (TrueType Collection) formatındaki bir yazı tipini temsil eder.


Daha fazla bilgi: https://docs.fileformat.com/font/ttc/

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
|  | [TtcFont(String name, String contentInBase64)](#TtcFont-java.lang.String-java.lang.String-) | İçeriği base64 kodlu olarak temsil eden yeni TtcFont sınıfını oluşturur |
dize ve belirtilen ad
|
|  | [TtcFont(String name, InputStream binaryContent)](#TtcFont-java.lang.String-java.io.InputStream-) | İçeriği bayt akışı olarak temsil eden yeni TtcFont sınıfını oluşturur ve |
belirtilen adla
|
## Alanlar

| Alan | Açıklama |
| --- | --- |
|  | [RequiredHeaderSize](#RequiredHeaderSize) | Doğrulama için gerekli olan TTC başlık boyutu (bayt cinsinden) |
|
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [isValid(InputStream binaryContent)](#isValid-java.io.InputStream-) | Belirtilen akışın geçerli bir TTC fontu olup olmadığını kontrol eder |
|
|  | [isValid(String contentInBase64)](#isValid-java.lang.String-) | Belirtilen base64 kodlu dizgenin geçerli bir TTC fontu olup olmadığını kontrol eder |
|
|  | [getType()](#getType--) | FontType.Ttc değerini döndürür |
|
|  | [getHeaderVersion()](#getHeaderVersion--) | TTC Başlık Sürümü, "1" veya "2" olabilir |
|
|  | [getFontsNumber()](#getFontsNumber--) | Bu TTC içindeki font sayısı |
|
|  | [getHasDsigTable()](#getHasDsigTable--) | Bu TTC'nin bir DSIG tablosu içerip içermediğini gösterir. |
|
### TtcFont(String name, String contentInBase64) {#TtcFont-java.lang.String-java.lang.String-}
```
public TtcFont(String name, String contentInBase64)
```


İçeriği base64 kodlu olarak temsil eden yeni TtcFont sınıfını oluşturur
dize ve belirtilen ad


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | ad | java.lang.String | TTC fontunun adı. Null, boş veya sadece boşluk olamaz. |
|
|  | contentInBase64 | java.lang.String | İçerik base64 kodlu dize olarak. Null, boş veya sadece boşluk olamaz. Eğer bir TTC içeriği değilse, istisna fırlatılacaktır. |
|

### TtcFont(String name, InputStream binaryContent) {#TtcFont-java.lang.String-java.io.InputStream-}
```
public TtcFont(String name, InputStream binaryContent)
```


İçeriği bayt akışı olarak temsil eden yeni TtcFont sınıfını oluşturur ve
belirtilen adla


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | ad | java.lang.String | TTC fontunun adı. Null, boş veya sadece boşluk olamaz. |
|
|  | binaryContent | java.io.InputStream | İçerik bayt akışı olarak. Okuma orijinal konumdan başlar. Null olamaz. Okunabilir ve aranabilir olmalıdır. Bu örnek serbest bırakılırsa, bu akış da serbest bırakılacaktır. |
|

### RequiredHeaderSize {#RequiredHeaderSize}
```
public static final int RequiredHeaderSize
```


Doğrulama için gerekli olan TTC başlık boyutu (bayt cinsinden)


### isValid(InputStream binaryContent) {#isValid-java.io.InputStream-}
```
public static boolean isValid(InputStream binaryContent)
```


Belirtilen akışın geçerli bir TTC fontu olup olmadığını kontrol eder


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | binaryContent | java.io.InputStream | Muhtemelen bir TTC kaynağı içeren bayt akışı |
|

**Returns:**
boolean - Belirtilen akış geçerli bir TTC yazı tipini içeriyorsa True, aksi takdirde false

### isValid(String contentInBase64) {#isValid-java.lang.String-}
```
public static boolean isValid(String contentInBase64)
```


Belirtilen base64 kodlu dizgenin geçerli bir TTC fontu olup olmadığını kontrol eder


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | Tahmini TTC yazı tipinin içeriği base64 kodlu dize biçiminde |
|

**Returns:**
boolean - Belirtilen dize geçerli bir TTC yazı tipini içeriyorsa True, aksi takdirde false

### getType() {#getType--}
```
public FontType getType()
```


FontType.Ttc değerini döndürür


**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype)
### getHeaderVersion() {#getHeaderVersion--}
```
public byte getHeaderVersion()
```


TTC Başlık Sürümü, "1" veya "2" olabilir


**Returns:**
bayt
### getFontsNumber() {#getFontsNumber--}
```
public long getFontsNumber()
```


Bu TTC içindeki font sayısı


**Returns:**
long
### getHasDsigTable() {#getHasDsigTable--}
```
public boolean getHasDsigTable()
```


Bu TTC'nin bir DSIG tablosu olup olmadığını gösterir. DSIG tablosu mevcut olabilir
yalnızca TTC'nin Header sürümü 2.0'a sahip olması durumunda.


**Returns:**
boolean
