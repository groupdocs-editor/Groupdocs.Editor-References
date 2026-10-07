---
title: "WordProcessingProtection"
second_title: "GroupDocs.Editor Java için API Referansı"
description: "HTML'den oluşturulan WordProcessing belgesi için belge koruma seçeneklerini kapsüller"
type: docs
weight: 46
url: /tr/java/com.groupdocs.editor.options/wordprocessingprotection/
---
**Inheritance:**
java.lang.Object
```
public final class WordProcessingProtection
```

WordProcessing belgesi için belge koruma seçeneklerini kapsüller,
HTML'den oluşturulan

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
|  | [WordProcessingProtection()](#WordProcessingProtection--) | Parametresiz yapıcı - tüm parametrelerin varsayılan değerleri vardır |
|
|  | [WordProcessingProtection(int protectionType, String password)](#WordProcessingProtection-int-java.lang.String-) | Sınıf örneklemesi sırasında tüm parametreleri ayarlamaya olanak tanır |
|
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getProtectionType()](#getProtectionType--) | Belgenin koruma türünü ayarlamaya olanak tanır. |
|
|  | [setProtectionType(int value)](#setProtectionType-int-) | Belgenin koruma türünü ayarlamaya olanak tanır. |
|
|  | [getPassword()](#getPassword--) | Belgeyi korumak için kullanılacak şifre. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Belgeyi korumak için kullanılacak şifre. |
|
| [convertToAsposeWords(int protectionType)](#convertToAsposeWords-int-) |  |
### WordProcessingProtection() {#WordProcessingProtection--}
```
public WordProcessingProtection()
```


Parametresiz yapıcı - tüm parametrelerin varsayılan değerleri vardır


### WordProcessingProtection(int protectionType, String password) {#WordProcessingProtection-int-java.lang.String-}
```
public WordProcessingProtection(int protectionType, String password)
```


Sınıf örneklemesi sırasında tüm parametreleri ayarlamaya olanak tanır


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | protectionType | int | Belgenin koruma türünü ayarlayın |
|
|  | parola | java.lang.String | Koruma şifresini ayarlayın |
|

### getProtectionType() {#getProtectionType--}
```
public final int getProtectionType()
```


Belgenin koruma türünü ayarlamaya izin verir. Varsayılan olarak ayarlanmamış olarak ayarlanır
belgeyi tamamen korumak.


**Returns:**
int
### setProtectionType(int value) {#setProtectionType-int-}
```
public final void setProtectionType(int value)
```


Belgenin koruma türünü ayarlamaya izin verir. Varsayılan olarak ayarlanmamış olarak ayarlanır
belgeyi tamamen korumak.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
```


Belgeyi korumak için şifre. Eğer null veya boş bir dize ise -
koruma belgeye uygulanmayacaktır.


**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Belgeyi korumak için şifre. Eğer null veya boş bir dize ise -
koruma belgeye uygulanmayacaktır.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### convertToAsposeWords(int protectionType) {#convertToAsposeWords-int-}
```
public static int convertToAsposeWords(int protectionType)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| protectionType | int |  |

**Returns:**
int
