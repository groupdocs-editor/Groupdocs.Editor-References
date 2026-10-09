---
title: "InvalidFontFormatException"
second_title: "GroupDocs.Editor Node.js için Java API Referansı"
description: "Açma, yükleme, kaydetme veya işleme sırasında, desteklenen bilinen bir formatta olduğu varsayılan ancak aslında desteklenmeyen veya beklenmeyen bir formatta ya da hiç bir font olmayan bir içeriğe erişilmeye çalışıldığında fırlatılan istisna."
type: docs
weight: 10
url: /tr/nodejs-java/com.groupdocs.editor.htmlcss.exceptions/invalidfontformatexception/
---
**Inheritance:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException
```
public class InvalidFontFormatException extends RuntimeException
```

Desteklenen (bilinen) formatta bir yazı tipi olduğu varsayılan, ancak aslında desteklenmeyen veya beklenmeyen formatta bir yazı tipi ya da hiç yazı tipi olmayan bir içeriği açmaya, yüklemeye, kaydetmeye veya başka bir şekilde işlemeye çalışırken ortaya çıkan istisna.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
|  | [InvalidFontFormatException(String message)](#InvalidFontFormatException-java.lang.String-) | Belirtilen hata mesajı ile yeni bir örnek oluşturur |
|
|  | [InvalidFontFormatException(String message, RuntimeException innerException)](#InvalidFontFormatException-java.lang.String-java.lang.RuntimeException-) | Belirtilen hata mesajı ve bu istisnanın nedeni olan iç istisna referansı ile @see \"InvalidFontFormatException\" yeni bir örnek oluşturur |
|
### InvalidFontFormatException(String message) {#InvalidFontFormatException-java.lang.String-}
```
public InvalidFontFormatException(String message)
```


Belirtilen hata mesajı ile yeni bir örnek oluşturur


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | mesaj | java.lang.String | Hata açıklamasını içeren metinsel mesaj, null veya boş olabilir |
|

### InvalidFontFormatException(String message, RuntimeException innerException) {#InvalidFontFormatException-java.lang.String-java.lang.RuntimeException-}
```
public InvalidFontFormatException(String message, RuntimeException innerException)
```


Belirtilen hata mesajı ve bu istisnanın nedeni olan iç istisna referansı ile @see \"InvalidFontFormatException\" yeni bir örnek oluşturur


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | mesaj | java.lang.String | Hata açıklamasını içeren metinsel mesaj, null veya boş olabilir |
|
|  | innerException | java.lang.RuntimeException | Mevcut istisnanın nedeni olan istisna, ya da iç istisna belirtilmemişse null referans |
|

