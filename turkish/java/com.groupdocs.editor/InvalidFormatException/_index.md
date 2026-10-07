---
title: "InvalidFormatException"
second_title: "GroupDocs.Editor Java için API Referansı"
description: "Kullanıcı, özgün belge formatıyla uyumsuz format‑özel seçeneklerle bir belge açmaya çalıştığında fırlatılan istisna."
type: docs
weight: 15
url: /tr/java/com.groupdocs.editor/invalidformatexception/
---
**Inheritance:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException
```
public final class InvalidFormatException extends RuntimeException
```

Kullanıcı bir belgeyi şu seçeneklerle açmaya çalıştığında fırlatılan istisna
orijinal belge formatıyla uyumsuz format‑özel seçenekler.


*** ** * ** ***

Örneğin, bir Spreadsheet belgesini WordProcessing belge seçenekleriyle açmaya çalışırsanız bu istisna fırlatılacaktır.

<br />


## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [InvalidFormatException()](#InvalidFormatException--) |  |
| [InvalidFormatException(String message)](#InvalidFormatException-java.lang.String-) |  |
| [InvalidFormatException(String message, RuntimeException inner)](#InvalidFormatException-java.lang.String-java.lang.RuntimeException-) |  |
### InvalidFormatException() {#InvalidFormatException--}
```
public InvalidFormatException()
```


### InvalidFormatException(String message) {#InvalidFormatException-java.lang.String-}
```
public InvalidFormatException(String message)
```


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| message | java.lang.String |  |

### InvalidFormatException(String message, RuntimeException inner) {#InvalidFormatException-java.lang.String-java.lang.RuntimeException-}
```
public InvalidFormatException(String message, RuntimeException inner)
```


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| message | java.lang.String |  |
| iç | java.lang.RuntimeException |  |

