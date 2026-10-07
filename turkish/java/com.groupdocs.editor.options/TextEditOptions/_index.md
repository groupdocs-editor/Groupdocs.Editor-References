---
title: "TextEditOptions"
second_title: "GroupDocs.Editor Java için API Referansı"
description: "Düz metin TXT belgelerini yüklemek için özel seçenekler belirtmeye izin verir"
type: docs
weight: 39
url: /tr/java/com.groupdocs.editor.options/texteditoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public class TextEditOptions implements IEditOptions
```

Düz metin (TXT) belgelerini yüklemek için özel seçenekler belirtmeye olanak tanır.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [TextEditOptions()](#TextEditOptions--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getEncoding()](#getEncoding--) | Metin belgesinin karakter kodlaması, uygulanacak |
açma
|
|  | [setEncoding(Charset value)](#setEncoding-java.nio.charset.Charset-) | Metin belgesinin karakter kodlaması, uygulanacak |
açma
|
|  | [getRecognizeLists()](#getRecognizeLists--) | Numaralı liste öğelerinin belge |
düz metin formatından içe aktarıldığında.
|
|  | [setRecognizeLists(boolean value)](#setRecognizeLists-boolean-) | Numaralı liste öğelerinin belge |
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
|  | [getEnablePagination()](#getEnablePagination--) | Sonuç HTML belgesinde sayfalama özelliğini etkinleştirmeye veya devre dışı bırakmaya izin verir. |
|
|  | [setEnablePagination(boolean value)](#setEnablePagination-boolean-) | Sonuç HTML belgesinde sayfalama özelliğini etkinleştirmeye veya devre dışı bırakmaya izin verir. |
|
|  | [getDirection()](#getDirection--) | Girdi düz metninde metin akış yönünü belirtmeye izin verir |
belge.
|
|  | [setDirection(int value)](#setDirection-int-) | Girdi düz metninde metin akış yönünü belirtmeye izin verir |
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


Metin belgesinin karakter kodlaması, uygulanacak
açma


**Returns:**
java.nio.charset.Charset
### setEncoding(Charset value) {#setEncoding-java.nio.charset.Charset-}
```
public final void setEncoding(Charset value)
```


Metin belgesinin karakter kodlaması, uygulanacak
açma


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.nio.charset.Charset |  |

### getRecognizeLists() {#getRecognizeLists--}
```
public final boolean getRecognizeLists()
```


Numaralı liste öğelerinin belge
düz metin formatından içe aktarıldığında. Varsayılan değer true'tır.


*** ** * ** ***

Eğer bu seçenek false olarak ayarlanırsa, liste tanıma algoritması, liste numaraları nokta, sağ köşeli parantez veya madde işareti (örneğin "\\u2022", "\*", "-" veya "o") ile bittiğinde liste paragraflarını algılar. Eğer bu seçenek true olarak ayarlanırsa, boşluk karakterleri de liste numarası sınırlayıcıları olarak kullanılır: Arap tarzı numaralandırma (1., 1.1.2.) için liste tanıma algoritması hem boşlukları hem de nokta (".") sembollerini kullanır.

<br />



**Returns:**
boolean
### setRecognizeLists(boolean value) {#setRecognizeLists-boolean-}
```
public final void setRecognizeLists(boolean value)
```


Numaralı liste öğelerinin belge
düz metin formatından içe aktarıldığında. Varsayılan değer true'tır.


*** ** * ** ***

Eğer bu seçenek false olarak ayarlanırsa, liste tanıma algoritması, liste numaraları nokta, sağ köşeli parantez veya madde işareti (örneğin "\\u2022", "\*", "-" veya "o") ile bittiğinde liste paragraflarını algılar. Eğer bu seçenek true olarak ayarlanırsa, boşluk karakterleri de liste numarası sınırlayıcıları olarak kullanılır: Arap tarzı numaralandırma (1., 1.1.2.) için liste tanıma algoritması hem boşlukları hem de nokta (".") sembollerini kullanır.

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
tüm son boşlukları keser.


**Returns:**
int
### setTrailingSpaces(int value) {#setTrailingSpaces-int-}
```
public final void setTrailingSpaces(int value)
```


Son boşluk işleme için tercih edilen seçeneği alır veya ayarlar. Varsayılan olarak
tüm son boşlukları keser.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getEnablePagination() {#getEnablePagination--}
```
public final boolean getEnablePagination()
```


Sonuçta oluşan HTML belgesinde sayfalama özelliğini etkinleştirmeye veya devre dışı bırakmaya izin verir. By
varsayılan olarak devre dışı bırakılmıştır (false).


**Returns:**
boolean
### setEnablePagination(boolean value) {#setEnablePagination-boolean-}
```
public final void setEnablePagination(boolean value)
```


Sonuçta oluşan HTML belgesinde sayfalama özelliğini etkinleştirmeye veya devre dışı bırakmaya izin verir. By
varsayılan olarak devre dışı bırakılmıştır (false).


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### getDirection() {#getDirection--}
```
public final int getDirection()
```


Girdi düz metninde metin akış yönünü belirtmeye izin verir
belge. Varsayılan olarak Soldan Sağa yönlüdür.


**Returns:**
int
### setDirection(int value) {#setDirection-int-}
```
public final void setDirection(int value)
```


Girdi düz metninde metin akış yönünü belirtmeye izin verir
belge. Varsayılan olarak Soldan Sağa yönlüdür.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

