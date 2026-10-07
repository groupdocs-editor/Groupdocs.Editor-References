---
title: "InvalidFontFormatException"
second_title: "GroupDocs.Editor Java için API Referansı"
description: "Açma, yükleme, kaydetme veya işleme sırasında, desteklenen bilinen bir biçimde olduğu varsayılan ancak aslında desteklenmeyen veya beklenmeyen bir biçimde ya da hiç bir font olmayan bir içerik üzerinde ortaya çıkan istisna."
type: docs
weight: 10
url: /tr/java/com.groupdocs.editor.htmlcss.exceptions/invalidfontformatexception/
---
**Inheritance:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException
```
public class InvalidFontFormatException extends RuntimeException
```

Desteklenen (bilinen) bir formatta olduğu varsayılan, ancak aslında desteklenmeyen veya beklenmeyen bir formatta ya da hiç bir yazı tipi olmayan bir içeriği açmaya, yüklemeye, kaydetmeye veya başka bir şekilde işlemeye çalışırken ortaya çıkan istisna.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
|  | [InvalidFontFormatException(String message)](#InvalidFontFormatException-java.lang.String-) | Belirtilen hata mesajı ile yeni bir örnek oluşturur |
|
|  | [InvalidFontFormatException(String message, RuntimeException innerException)](#InvalidFontFormatException-java.lang.String-java.lang.RuntimeException-) | @see \"InvalidFontFormatException\" ile belirtilen hata mesajı ve bu istisnanın nedeni olan iç istisna referansı kullanılarak yeni bir örnek oluşturulur |
|
### InvalidFontFormatException(String message) {#InvalidFontFormatException-java.lang.String-}
```
public InvalidFontFormatException(String message)
```


Belirtilen hata mesajı ile yeni bir örnek oluşturur


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | message | java.lang.String | Hata açıklamasını içeren metin mesajı, null veya boş olabilir |
|

### InvalidFontFormatException(String message, RuntimeException innerException) {#InvalidFontFormatException-java.lang.String-java.lang.RuntimeException-}
```
public InvalidFontFormatException(String message, RuntimeException innerException)
```


@see \"InvalidFontFormatException\" ile belirtilen hata mesajı ve bu istisnanın nedeni olan iç istisna referansı kullanılarak yeni bir örnek oluşturulur


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | message | java.lang.String | Hata açıklamasını içeren metin mesajı, null veya boş olabilir |
|
|  | innerException | java.lang.RuntimeException | Mevcut istisnanın nedeni olan istisna, ya da iç istisna belirtilmemişse null referans. |
|

