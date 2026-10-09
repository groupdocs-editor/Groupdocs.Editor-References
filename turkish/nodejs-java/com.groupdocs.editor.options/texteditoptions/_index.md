---
title: "TextEditOptions"
second_title: "GroupDocs.Editor Node.js için Java API Referansı"
description: "Düz metin TXT belgelerini yüklemek için özel seçenekler belirtmeye izin verir"
type: docs
weight: 39
url: /tr/nodejs-java/com.groupdocs.editor.options/texteditoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public class TextEditOptions implements IEditOptions
```

Düz metin (TXT) belgelerini yüklemek için özel seçenekler belirtmeyi sağlar.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [TextEditOptions()](#TextEditOptions--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getEncoding()](#getEncoding--) | Metin belgesinin karakter kodlaması, bunun için uygulanacak |
açma
|
|  | [setEncoding(Charset value)](#setEncoding-java.nio.charset.Charset-) | Metin belgesinin karakter kodlaması, bunun için uygulanacak |
açma
|
|  | [getRecognizeLists()](#getRecognizeLists--) | Belge olduğunda numaralı liste öğelerinin nasıl tanındığını belirtmeye izin verir |
düz metin formatından içe aktarıldığında.
|
|  | [setRecognizeLists(boolean value)](#setRecognizeLists-boolean-) | Belge olduğunda numaralı liste öğelerinin nasıl tanındığını belirtmeye izin verir |
düz metin formatından içe aktarıldığında.
|
|  | [getLeadingSpaces()](#getLeadingSpaces--) | Ön boşluk işleme için tercih edilen seçeneği alır veya ayarlar. |
|
|  | [setLeadingSpaces(int value)](#setLeadingSpaces-int-) | Ön boşluk işleme için tercih edilen seçeneği alır veya ayarlar. |
|
|  | [getTrailingSpaces()](#getTrailingSpaces--) | Son boşluk işleme için tercih edilen seçeneği alır veya ayarlar. |
|
|  | [setTrailingSpaces(int value)](#setTrailingSpaces-int-) | Son boşluk işleme için tercih edilen seçeneği alır veya ayarlar. |
|
|  | [getEnablePagination()](#getEnablePagination--) | Ortaya çıkan HTML belgesinde sayfalama özelliğini etkinleştirmeye veya devre dışı bırakmaya izin verir. |
|
|  | [setEnablePagination(boolean value)](#setEnablePagination-boolean-) | Ortaya çıkan HTML belgesinde sayfalama özelliğini etkinleştirmeye veya devre dışı bırakmaya izin verir. |
|
|  | [getDirection()](#getDirection--) | Giriş düz metninde metin akış yönünü belirtmeye izin verir |
belge.
|
|  | [setDirection(int value)](#setDirection-int-) | Giriş düz metninde metin akış yönünü belirtmeye izin verir |
belge.
|
### TextEditOptions() {#TextEditOptions--}
```
public TextEditOptions()
```


### getEncoding() {#getEncoding--}
```
public final Charset getEncoding()
```


Metin belgesinin karakter kodlaması, bunun için uygulanacak
açma


**Returns:**
java.nio.charset.Charset
### setEncoding(Charset value) {#setEncoding-java.nio.charset.Charset-}
```
public final void setEncoding(Charset value)
```


Metin belgesinin karakter kodlaması, bunun için uygulanacak
açma


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.nio.charset.Charset |  |

### getRecognizeLists() {#getRecognizeLists--}
```
public final boolean getRecognizeLists()
```


Belge olduğunda numaralı liste öğelerinin nasıl tanındığını belirtmeye izin verir
düz metin formatından içe aktarıldı. Varsayılan değer doğrudur.


*** ** * ** ***

Bu seçenek false olarak ayarlanırsa, liste tanıma algoritması, liste numaraları nokta, sağ köşeli parantez veya madde işareti (örneğin "\\u2022", "\*", "-" veya "o") ile bittiğinde liste paragraflarını algılar. Bu seçenek true olarak ayarlanırsa, boşluk karakterleri de liste numarası sınırlayıcıları olarak kullanılır: Arapça stil numaralandırma (1., 1.1.2.) için liste tanıma algoritması hem boşlukları hem de nokta (".") sembollerini kullanır.

<br />



**Returns:**
boolean
### setRecognizeLists(boolean value) {#setRecognizeLists-boolean-}
```
public final void setRecognizeLists(boolean value)
```


Belge olduğunda numaralı liste öğelerinin nasıl tanındığını belirtmeye izin verir
düz metin formatından içe aktarıldı. Varsayılan değer doğrudur.


*** ** * ** ***

Bu seçenek false olarak ayarlanırsa, liste tanıma algoritması, liste numaraları nokta, sağ köşeli parantez veya madde işareti (örneğin "\\u2022", "\*", "-" veya "o") ile bittiğinde liste paragraflarını algılar. Bu seçenek true olarak ayarlanırsa, boşluk karakterleri de liste numarası sınırlayıcıları olarak kullanılır: Arapça stil numaralandırma (1., 1.1.2.) için liste tanıma algoritması hem boşlukları hem de nokta (".") sembollerini kullanır.

<br />



**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### getLeadingSpaces() {#getLeadingSpaces--}
```
public final int getLeadingSpaces()
```


Ön boşluk işleme için tercih edilen seçeneği alır veya ayarlar. Varsayılan olarak
ön boşlukları sol girintiye dönüştürür.


**Returns:**
int
### setLeadingSpaces(int value) {#setLeadingSpaces-int-}
```
public final void setLeadingSpaces(int value)
```


Ön boşluk işleme için tercih edilen seçeneği alır veya ayarlar. Varsayılan olarak
ön boşlukları sol girintiye dönüştürür.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getTrailingSpaces() {#getTrailingSpaces--}
```
public final int getTrailingSpaces()
```


Son boşluk işleme için tercih edilen seçeneği alır veya ayarlar. Varsayılan olarak
tüm sondaki boşlukları kırpar.


**Returns:**
int
### setTrailingSpaces(int value) {#setTrailingSpaces-int-}
```
public final void setTrailingSpaces(int value)
```


Son boşluk işleme için tercih edilen seçeneği alır veya ayarlar. Varsayılan olarak
tüm sondaki boşlukları kırpar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getEnablePagination() {#getEnablePagination--}
```
public final boolean getEnablePagination()
```


Sonuç HTML belgesinde sayfalama özelliğini etkinleştirmeye veya devre dışı bırakmaya izin verir. By
varsayılan olarak devre dışıdır (false).


**Returns:**
boolean
### setEnablePagination(boolean value) {#setEnablePagination-boolean-}
```
public final void setEnablePagination(boolean value)
```


Sonuç HTML belgesinde sayfalama özelliğini etkinleştirmeye veya devre dışı bırakmaya izin verir. By
varsayılan olarak devre dışıdır (false).


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### getDirection() {#getDirection--}
```
public final int getDirection()
```


Giriş düz metninde metin akış yönünü belirtmeye izin verir
belge. Varsayılan olarak Soldan Sağa'dır.


**Returns:**
int
### setDirection(int value) {#setDirection-int-}
```
public final void setDirection(int value)
```


Giriş düz metninde metin akış yönünü belirtmeye izin verir
belge. Varsayılan olarak Soldan Sağa'dır.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

