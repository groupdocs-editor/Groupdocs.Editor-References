---
title: "InvalidFormatException"
second_title: "GroupDocs.Editor Node.js için Java API Referansı"
description: "Kullanıcı, özgün belge formatıyla uyumsuz format‑spesifik seçeneklerle bir belge açmaya çalıştığında atılan istisna."
type: docs
weight: 15
url: /tr/nodejs-java/com.groupdocs.editor/invalidformatexception/
---
**Inheritance:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException
```
public final class InvalidFormatException extends RuntimeException
```

Kullanıcı bazı bir belgeyi şu seçeneklerle açmaya çalıştığında atılan istisna
orijinal belge formatıyla uyumsuz format‑spesifik seçenekler.


*** ** * ** ***

Örneğin, bu istisna, bir Spreadsheet belgesini WordProcessing belge seçenekleriyle açmaya çalışılırsa atılır.

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
| mesaj | java.lang.String |  |

### InvalidFormatException(String message, RuntimeException inner) {#InvalidFormatException-java.lang.String-java.lang.RuntimeException-}
```
public InvalidFormatException(String message, RuntimeException inner)
```


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| mesaj | java.lang.String |  |
| iç | java.lang.RuntimeException |  |

