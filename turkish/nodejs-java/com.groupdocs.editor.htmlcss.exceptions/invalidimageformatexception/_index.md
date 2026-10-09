---
title: "InvalidImageFormatException"
second_title: "GroupDocs.Editor Node.js için Java API Referansı"
description: "Açma, yükleme, kaydetme veya işleme sırasında, muhtemelen bir raster veya vektör görüntüsü olan ancak aslında beklenmeyen bir türde görüntü ya da hiç görüntü olmayan bir içeriğe erişilmeye çalışıldığında fırlatılan istisna."
type: docs
weight: 11
url: /tr/nodejs-java/com.groupdocs.editor.htmlcss.exceptions/invalidimageformatexception/
---
**Inheritance:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException
```
public class InvalidImageFormatException extends RuntimeException
```

Açma, yükleme, kaydetme veya işleme sırasında fırlatılan istisna
başka bir şekilde muhtemelen bir görüntü (raster veya vektör) olan bir içerik,
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
|  | mesaj | java.lang.String | Hata açıklamasını içeren metinsel mesaj, null veya boş olabilir |
|

### InvalidImageFormatException(String message, RuntimeException innerException) {#InvalidImageFormatException-java.lang.String-java.lang.RuntimeException-}
```
public InvalidImageFormatException(String message, RuntimeException innerException)
```


Belirtilen hata mesajı ve bu istisnanın nedeni olan iç istisna referansı ile yeni bir InvalidImageFormatException örneği oluşturur


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | mesaj | java.lang.String | Hata açıklamasını içeren metinsel mesaj, null veya boş olabilir |
|
|  | innerException | java.lang.RuntimeException | Mevcut istisnanın nedeni olan istisna, ya da iç istisna belirtilmemişse null referans |
|

