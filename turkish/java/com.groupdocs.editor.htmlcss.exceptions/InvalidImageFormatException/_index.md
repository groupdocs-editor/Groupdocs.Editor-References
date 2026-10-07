---
title: "InvalidImageFormatException"
second_title: "GroupDocs.Editor Java için API Referansı"
description: "Açma, yükleme, kaydetme veya işleme sırasında, muhtemelen bir görüntü (raster veya vektör) olduğu varsayılan ancak aslında beklenmeyen bir türde görüntü ya da hiç görüntü olmayan bir içerik üzerinde ortaya çıkan istisna."
type: docs
weight: 11
url: /tr/java/com.groupdocs.editor.htmlcss.exceptions/invalidimageformatexception/
---
**Inheritance:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException
```
public class InvalidImageFormatException extends RuntimeException
```

Açma, yükleme, kaydetme veya işleme sırasında ortaya çıkan istisna.
başka bir şekilde, muhtemelen bir görüntü (raster veya vektör) olan bazı içerik,
ancak aslında beklenmeyen bir türde görüntü ya da hiç görüntü değildir.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
|  | [InvalidImageFormatException(String message)](#InvalidImageFormatException-java.lang.String-) | Belirtilen hata mesajı ile yeni bir InvalidImageFormatException örneği oluşturur |
|
|  | [InvalidImageFormatException(String message, RuntimeException innerException)](#InvalidImageFormatException-java.lang.String-java.lang.RuntimeException-) | Belirtilen hata mesajı ve bu istisnanın nedeni olan iç istisna referansı ile yeni bir InvalidImageFormatException örneği oluşturur |
|
### InvalidImageFormatException(String message) {#InvalidImageFormatException-java.lang.String-}
```
public InvalidImageFormatException(String message)
```


Belirtilen hata mesajı ile yeni bir InvalidImageFormatException örneği oluşturur


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | message | java.lang.String | Hata açıklamasını içeren metin mesajı, null veya boş olabilir |
|

### InvalidImageFormatException(String message, RuntimeException innerException) {#InvalidImageFormatException-java.lang.String-java.lang.RuntimeException-}
```
public InvalidImageFormatException(String message, RuntimeException innerException)
```


Belirtilen hata mesajı ve bu istisnanın nedeni olan iç istisna referansı ile yeni bir InvalidImageFormatException örneği oluşturur


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | message | java.lang.String | Hata açıklamasını içeren metin mesajı, null veya boş olabilir |
|
|  | innerException | java.lang.RuntimeException | Mevcut istisnanın nedeni olan istisna, ya da iç istisna belirtilmemişse null referans. |
|

