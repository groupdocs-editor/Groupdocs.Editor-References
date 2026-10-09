---
title: "WorksheetProtection"
second_title: "GroupDocs.Editor Node.js için Java API Referansı"
description: "Belirli bir şifre ile belirtilen türdeki değişikliklerden korumak için çıktı Spreadsheet belgesindeki bir çalışma sayfasını korumaya izin veren çalışma sayfası koruma seçeneklerini kapsüller."
type: docs
weight: 49
url: /tr/nodejs-java/com.groupdocs.editor.options/worksheetprotection/
---
**Inheritance:**
java.lang.Object
```
public final class WorksheetProtection
```

Çalışma sayfasını korumaya izin veren çalışma sayfası koruma seçeneklerini kapsüller.
çıktı Spreadsheet belgesinde belirtilen türdeki değişikliklerden bir
belirtilen şifre.


*** ** * ** ***

XLSX gibi çoğu Spreadsheet formatı, bir çalışma sayfasını şifreyle düzenlemeye karşı korumaya izin verir. Bu sınıf, bu korumayı etkinleştirmeyi ve seçeneklerini belirtmeyi sağlar.

<br />


## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
|  | [WorksheetProtection()](#WorksheetProtection--) | Varsayılan parametrelerle yeni bir örnek oluşturur. |
|
|  | [WorksheetProtection(int protectionType, String password)](#WorksheetProtection-int-java.lang.String-) | Belirtilen çalışma sayfası koruma türüyle yeni bir örnek oluşturur ve |
parola
|
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getProtectionType()](#getProtectionType--) | Bir çalışma sayfası koruma türü belirtmeye izin verir. |
|
|  | [setProtectionType(int value)](#setProtectionType-int-) | Bir çalışma sayfası koruma türü belirtmeye izin verir. |
|
|  | [getPassword()](#getPassword--) | Bir çalışma sayfasını korumak için kullanılan şifre. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Bir çalışma sayfasını korumak için kullanılan şifre. |
|
### WorksheetProtection() {#WorksheetProtection--}
```
public WorksheetProtection()
```


Varsayılan parametrelerle yeni bir örnek oluşturur. Değiştirilmez ve geçirilmezse
SpreadsheetSaveOptions'a, hiçbir çalışma sayfası koruması uygulanmayacaktır


### WorksheetProtection(int protectionType, String password) {#WorksheetProtection-int-java.lang.String-}
```
public WorksheetProtection(int protectionType, String password)
```


Belirtilen çalışma sayfası koruma türüyle yeni bir örnek oluşturur ve
parola


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | protectionType | int | Çalışma sayfası koruma türü |
|
|  | parola | java.lang.String | Koruma kilitleyen şifre |
|

### getProtectionType() {#getProtectionType--}
```
public final int getProtectionType()
```


Bir çalışma sayfası koruma türü belirtmeye izin verir. Varsayılan olarak 'None' (Hiçbiri) -
koruma uygulanmaz.


**Returns:**
int
### setProtectionType(int value) {#setProtectionType-int-}
```
public final void setProtectionType(int value)
```


Bir çalışma sayfası koruma türü belirtmeye izin verir. Varsayılan olarak 'None' (Hiçbiri) -
koruma uygulanmaz.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
```


Bir çalışma sayfasını korumak için kullanılan şifre. NULL veya boş ise
dize, koruma uygulanmayacaktır.


**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Bir çalışma sayfasını korumak için kullanılan şifre. NULL veya boş ise
dize, koruma uygulanmayacaktır.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

