---
title: "MetaImageBase"
second_title: "Referencia de API de GroupDocs.Editor para Node.js vía Java"
description: "Clase abstracta base para los formatos de imagen WMF y EMF"
type: docs
weight: 11
url: /es/nodejs-java/com.groupdocs.editor.htmlcss.resources.images.vector/metaimagebase/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.images.vector.VectorImageResourceBase](../../com.groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase)
```
public abstract class MetaImageBase extends VectorImageResourceBase
```

Clase abstracta base para los formatos de imagen WMF y EMF

## Constructores

| Constructor | Descripción |
| --- | --- |
|  | [MetaImageBase(String name, String contentInBase64, boolean isWmf)](#MetaImageBase-java.lang.String-java.lang.String-boolean-) | Constructor común, que prepara la creación de una instancia WMF o EMF a partir de |
cadena codificada en base64
|
|  | [MetaImageBase(String name, InputStream binaryContent, boolean isWmf)](#MetaImageBase-java.lang.String-java.io.InputStream-boolean-) | Constructor común, que prepara la creación de una instancia WMF o EMF a partir de |
flujo de bytes
|
## Métodos

| Método | Descripción |
| --- | --- |
|  | [isValidWmf(InputStream binaryContent)](#isValidWmf-java.io.InputStream-) | Determina si el flujo de bytes especificado contiene una imagen WMF válida |
|
|  | [isValidWmf(String contentInBase64)](#isValidWmf-java.lang.String-) | Determina si la cadena especificada contiene una imagen WMF válida, que es |
codificada en base64
|
|  | [isValidEmf(InputStream binaryContent)](#isValidEmf-java.io.InputStream-) | Determina si el flujo de bytes especificado contiene una imagen EMF válida |
|
|  | [isValidEmf(String contentInBase64)](#isValidEmf-java.lang.String-) | Determina si la cadena especificada contiene una imagen EMF válida, que es |
codificada en base64
|
|  | [saveToSvg(OutputStream outputSvgContent)](#saveToSvg-java.io.OutputStream-) | En el tipo de implementación debe guardar la meta-imagen vectorial actual en el |
formato SVG vectorial en el flujo de bytes especificado
|
### MetaImageBase(String name, String contentInBase64, boolean isWmf) {#MetaImageBase-java.lang.String-java.lang.String-boolean-}
```
public MetaImageBase(String name, String contentInBase64, boolean isWmf)
```


Constructor común, que prepara la creación de una instancia WMF o EMF a partir de
cadena codificada en base64


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | name | java.lang.String | Nombre obligatorio |
|
|  | contentInBase64 | java.lang.String | Contenido como cadena base64. No debe ser NULL ni estar vacío. |
|
|  | isWmf | booleano | true para WMF, false para EMF |
|

### MetaImageBase(String name, InputStream binaryContent, boolean isWmf) {#MetaImageBase-java.lang.String-java.io.InputStream-boolean-}
```
public MetaImageBase(String name, InputStream binaryContent, boolean isWmf)
```


Constructor común, que prepara la creación de una instancia WMF o EMF a partir de
flujo de bytes


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | name | java.lang.String | Nombre obligatorio |
|
|  | binaryContent | java.io.InputStream | Contenido como flujo de bytes. Debe ser válido. |
|
|  | isWmf | booleano | true para WMF, false para EMF |
|

### isValidWmf(InputStream binaryContent) {#isValidWmf-java.io.InputStream-}
```
public static boolean isValidWmf(InputStream binaryContent)
```


Determina si el flujo de bytes especificado contiene una imagen WMF válida


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | binaryContent | java.io.InputStream | Flujo de bytes de entrada. Debe ser válido. |
|

**Returns:**
booleano - Devuelve 'true' si es válido y 'false' si es inválido

### isValidWmf(String contentInBase64) {#isValidWmf-java.lang.String-}
```
public static boolean isValidWmf(String contentInBase64)
```


Determina si la cadena especificada contiene una imagen WMF válida, que es
codificada en base64


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | Cadena, que se asume contiene una imagen WMF codificada en base64 |
|

**Returns:**
booleano - Devuelve 'true' si es válido y 'false' si es inválido

### isValidEmf(InputStream binaryContent) {#isValidEmf-java.io.InputStream-}
```
public static boolean isValidEmf(InputStream binaryContent)
```


Determina si el flujo de bytes especificado contiene una imagen EMF válida


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | binaryContent | java.io.InputStream | Flujo de bytes de entrada. Debe ser válido. |
|

**Returns:**
booleano - Devuelve 'true' si es válido y 'false' si es inválido

### isValidEmf(String contentInBase64) {#isValidEmf-java.lang.String-}
```
public static boolean isValidEmf(String contentInBase64)
```


Determina si la cadena especificada contiene una imagen EMF válida, que es
codificada en base64


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | Cadena, que se asume contiene una imagen EMF codificada en base64 |
|

**Returns:**
booleano - Devuelve 'true' si es válido y 'false' si es inválido

### saveToSvg(OutputStream outputSvgContent) {#saveToSvg-java.io.OutputStream-}
```
public abstract void saveToSvg(OutputStream outputSvgContent)
```


En el tipo de implementación debe guardar la meta-imagen vectorial actual en el
formato SVG vectorial en el flujo de bytes especificado


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | outputSvgContent | java.io.OutputStream | Flujo de bytes, en el que se almacenará la versión SVG de esta meta-imagen vectorial. No debe ser NULL y debe soportar escritura. |
|

