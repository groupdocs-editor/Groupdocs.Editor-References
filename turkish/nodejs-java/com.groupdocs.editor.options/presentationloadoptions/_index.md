---
title: "PresentationLoadOptions"
second_title: "GroupDocs.Editor Node.js için Java API Referansı"
description: "PPTX, PPTM, PPSX vb. gibi tüm desteklenen Sunum formatlarında belgeleri yüklemek için özel seçenekler belirtmeye izin verir"
type: docs
weight: 33
url: /tr/nodejs-java/com.groupdocs.editor.options/presentationloadoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ILoadOptions](../../com.groupdocs.editor.options/iloadoptions)
```
public class PresentationLoadOptions implements ILoadOptions
```

Tüm desteklenen belgeleri yüklemek için özel seçenekler belirtmeye izin verir
PPT(X), PPTM, PPS(X) vb. gibi Sunum formatları.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [PresentationLoadOptions()](#PresentationLoadOptions--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getPassword()](#getPassword--) | Şifreyi belirtmeye, değiştirmeye ve almaya izin verir; bu şifre |
Presentation belgesi kodlanmışsa, açma.
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Şifreyi belirtmeye, değiştirmeye ve almaya izin verir; bu şifre |
Presentation belgesi kodlanmışsa, açma.
|
### PresentationLoadOptions() {#PresentationLoadOptions--}
```
public PresentationLoadOptions()
```


### getPassword() {#getPassword--}
```
public final String getPassword()
```


Şifreyi belirtmeye, değiştirmeye ve almaya izin verir; bu şifre
Presentation belgesi kodlanmışsa, açma. NULL veya boş olarak ayarla
parolayı kaldırmak için dize.


*** ** * ** ***

Varsayılan olarak bu özelliğin NULL değeri vardır \u2014 parola ayarlanmamıştır. Eğer giriş Presentation belgesi parola korumalıysa, parola zorunludur ve parola belirtilmemiş veya geçersizse bir istisna fırlatılır. Eğer giriş Presentation belgesi PAROLA korumalı DEĞİLSE, ancak parola ayarlanmışsa, yok sayılır.

<br />



**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Şifreyi belirtmeye, değiştirmeye ve almaya izin verir; bu şifre
Presentation belgesi kodlanmışsa, açma. NULL veya boş olarak ayarla
parolayı kaldırmak için dize.


*** ** * ** ***

Varsayılan olarak bu özelliğin NULL değeri vardır \u2014 parola ayarlanmamıştır. Eğer giriş Presentation belgesi parola korumalıysa, parola zorunludur ve parola belirtilmemiş veya geçersizse bir istisna fırlatılır. Eğer giriş Presentation belgesi PAROLA korumalı DEĞİLSE, ancak parola ayarlanmışsa, yok sayılır.

<br />



**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

