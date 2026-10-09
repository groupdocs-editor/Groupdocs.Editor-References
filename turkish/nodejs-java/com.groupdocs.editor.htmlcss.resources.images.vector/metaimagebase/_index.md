---
title: "MetaImageBase"
second_title: "GroupDocs.Editor Node.js için Java API Referansı"
description: "WMF ve EMF görüntü formatları için temel soyut sınıf."
type: docs
weight: 11
url: /tr/nodejs-java/com.groupdocs.editor.htmlcss.resources.images.vector/metaimagebase/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.images.vector.VectorImageResourceBase](../../com.groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase)
```
public abstract class MetaImageBase extends VectorImageResourceBase
```

WMF ve EMF görüntü formatları için temel soyut sınıf.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
|  | [MetaImageBase(String name, String contentInBase64, boolean isWmf)](#MetaImageBase-java.lang.String-java.lang.String-boolean-) | Ortak yapıcı, bir WMF veya EMF örneği oluşturmayı hazırlayan |
base64 kodlu dize
|
|  | [MetaImageBase(String name, InputStream binaryContent, boolean isWmf)](#MetaImageBase-java.lang.String-java.io.InputStream-boolean-) | Ortak yapıcı, bir WMF veya EMF örneği oluşturmayı hazırlayan |
bayt akışı
|
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [isValidWmf(InputStream binaryContent)](#isValidWmf-java.io.InputStream-) | Belirtilen bayt akışının geçerli bir WMF görüntüsü içerip içermediğini belirler |
|
|  | [isValidWmf(String contentInBase64)](#isValidWmf-java.lang.String-) | Belirtilen dizenin geçerli bir WMF görüntüsü içerip içermediğini belirler, ki bu |
base64 ile kodlanmış
|
|  | [isValidEmf(InputStream binaryContent)](#isValidEmf-java.io.InputStream-) | Belirtilen bayt akışının geçerli bir EMF görüntüsü içerip içermediğini belirler |
|
|  | [isValidEmf(String contentInBase64)](#isValidEmf-java.lang.String-) | Belirtilen dizenin geçerli bir EMF görüntüsü içerip içermediğini belirler, ki bu |
base64 ile kodlanmış
|
|  | [saveToSvg(OutputStream outputSvgContent)](#saveToSvg-java.io.OutputStream-) | Uygulayan tür, mevcut vektör meta-görseli şuraya kaydetmelidir |
vektör SVG formatını belirtilen bayt akışına
|
### MetaImageBase(String name, String contentInBase64, boolean isWmf) {#MetaImageBase-java.lang.String-java.lang.String-boolean-}
```
public MetaImageBase(String name, String contentInBase64, boolean isWmf)
```


Ortak yapıcı, bir WMF veya EMF örneği oluşturmayı hazırlayan
base64 kodlu dize


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | ad | java.lang.String | Zorunlu ad |
|
|  | contentInBase64 | java.lang.String | İçerik base64 dizesi olarak. NULL olmamalı ve boş olmamalıdır. |
|
|  | isWmf | boolean | WMF için true, EMF için false |
|

### MetaImageBase(String name, InputStream binaryContent, boolean isWmf) {#MetaImageBase-java.lang.String-java.io.InputStream-boolean-}
```
public MetaImageBase(String name, InputStream binaryContent, boolean isWmf)
```


Ortak yapıcı, bir WMF veya EMF örneği oluşturmayı hazırlayan
bayt akışı


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | ad | java.lang.String | Zorunlu ad |
|
|  | binaryContent | java.io.InputStream | İçerik bayt akışı olarak. Geçerli olmalıdır. |
|
|  | isWmf | boolean | WMF için true, EMF için false |
|

### isValidWmf(InputStream binaryContent) {#isValidWmf-java.io.InputStream-}
```
public static boolean isValidWmf(InputStream binaryContent)
```


Belirtilen bayt akışının geçerli bir WMF görüntüsü içerip içermediğini belirler


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | binaryContent | java.io.InputStream | Giriş bayt akışı. Geçerli olmalıdır. |
|

**Returns:**
boolean - Geçerliyse 'true', geçersizse 'false' döndürür

### isValidWmf(String contentInBase64) {#isValidWmf-java.lang.String-}
```
public static boolean isValidWmf(String contentInBase64)
```


Belirtilen dizenin geçerli bir WMF görüntüsü içerip içermediğini belirler, ki bu
base64 ile kodlanmış


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | Base64 kodlu WMF görüntüsü içerdiği varsayılan dize |
|

**Returns:**
boolean - Geçerliyse 'true', geçersizse 'false' döndürür

### isValidEmf(InputStream binaryContent) {#isValidEmf-java.io.InputStream-}
```
public static boolean isValidEmf(InputStream binaryContent)
```


Belirtilen bayt akışının geçerli bir EMF görüntüsü içerip içermediğini belirler


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | binaryContent | java.io.InputStream | Giriş bayt akışı. Geçerli olmalıdır. |
|

**Returns:**
boolean - Geçerliyse 'true', geçersizse 'false' döndürür

### isValidEmf(String contentInBase64) {#isValidEmf-java.lang.String-}
```
public static boolean isValidEmf(String contentInBase64)
```


Belirtilen dizenin geçerli bir EMF görüntüsü içerip içermediğini belirler, ki bu
base64 ile kodlanmış


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | Base64 kodlu EMF görüntüsü içerdiği varsayılan dize |
|

**Returns:**
boolean - Geçerliyse 'true', geçersizse 'false' döndürür

### saveToSvg(OutputStream outputSvgContent) {#saveToSvg-java.io.OutputStream-}
```
public abstract void saveToSvg(OutputStream outputSvgContent)
```


Uygulayan tür, mevcut vektör meta-görseli şuraya kaydetmelidir
vektör SVG formatını belirtilen bayt akışına


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | outputSvgContent | java.io.OutputStream | Bayt akışı, bu vektör meta-görselinin SVG sürümünün depolanacağı yer. NULL olmamalı ve yazma desteklemelidir. |
|

