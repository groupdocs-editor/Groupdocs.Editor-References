---
title: "PresentationLoadOptions"
second_title: "GroupDocs.Editor Java için API Referansı"
description: "Desteklenen tüm Sunum formatları (PPTX, PPTM, PPSX vb.) için belgeleri yüklerken özelleştirilmiş seçenekler belirtmeye olanak tanır."
type: docs
weight: 33
url: /tr/java/com.groupdocs.editor.options/presentationloadoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ILoadOptions](../../com.groupdocs.editor.options/iloadoptions)
```
public class PresentationLoadOptions implements ILoadOptions
```

Desteklenen tüm belgeleri yüklerken özelleştirilmiş seçenekler belirtmeye olanak tanır
PPT(X), PPTM, PPS(X) vb. gibi Sunum formatları.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [PresentationLoadOptions()](#PresentationLoadOptions--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getPassword()](#getPassword--) | Şifreyi belirtmeye, değiştirmeye ve elde etmeye olanak tanır, bu şifre |
Sunum belgesi açılırken, eğer şifrelenmişse.
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Şifreyi belirtmeye, değiştirmeye ve elde etmeye olanak tanır, bu şifre |
Sunum belgesi açılırken, eğer şifrelenmişse.
|
### PresentationLoadOptions() {#PresentationLoadOptions--}
```
public PresentationLoadOptions()
```


### getPassword() {#getPassword--}
```
public final String getPassword()
```


Şifreyi belirtmeye, değiştirmeye ve elde etmeye olanak tanır, bu şifre
Sunum belgesi açılırken, eğer şifrelenmişse. NULL veya boş olarak ayarlayın
şifreyi kaldırmak için dize.


*** ** * ** ***

Varsayılan olarak bu özelliğin NULL değeri vardır — şifre ayarlanmamıştır. Giriş Sunum belgesi şifre korumalıysa, şifre zorunludur ve şifre belirtilmemiş veya geçersizse bir istisna fırlatılır. Giriş Sunum belgesi ŞİFRELEMEYE sahip değilse, ancak şifre ayarlanmışsa, göz ardı edilir.

<br />



**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Şifreyi belirtmeye, değiştirmeye ve elde etmeye olanak tanır, bu şifre
Sunum belgesi açılırken, eğer şifrelenmişse. NULL veya boş olarak ayarlayın
şifreyi kaldırmak için dize.


*** ** * ** ***

Varsayılan olarak bu özelliğin NULL değeri vardır — şifre ayarlanmamıştır. Giriş Sunum belgesi şifre korumalıysa, şifre zorunludur ve şifre belirtilmemiş veya geçersizse bir istisna fırlatılır. Giriş Sunum belgesi ŞİFRELEMEYE sahip değilse, ancak şifre ayarlanmışsa, göz ardı edilir.

<br />



**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

