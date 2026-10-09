---
title: "ResourceTypeDetector"
second_title: "Referencia de API de GroupDocs.Editor para Node.js vía Java"
description: "Métodos estáticos de utilidad para detectar tipos y formatos de recursos"
type: docs
weight: 10
url: /es/nodejs-java/com.groupdocs.editor.htmlcss.resources/resourcetypedetector/
---
**Inheritance:**
java.lang.Object
```
public class ResourceTypeDetector
```

Métodos estáticos de utilidad para detectar tipos de recursos (formatos).

## Constructores

| Constructor | Descripción |
| --- | --- |
| [ResourceTypeDetector()](#ResourceTypeDetector--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
|  | [detectTypeFromFilename(String filename)](#detectTypeFromFilename-java.lang.String-) | Detecta un tipo a partir del nombre de archivo especificado y devuelve una instancia de |
respectivo IResourceType
|
|  | [tryDetectResource(InputStream inputResourceStream, String name, IResourceType assumptiveFormat)](#tryDetectResource-java.io.InputStream-java.lang.String-com.groupdocs.editor.htmlcss.resources.IResourceType-) | Intenta analizar un flujo de entrada y crea uno de los HTML compatibles |
recursos a partir de él, teniendo en cuenta un tipo supuesto especificado, si es
no es nulo
|
### ResourceTypeDetector() {#ResourceTypeDetector--}
```
public ResourceTypeDetector()
```


### detectTypeFromFilename(String filename) {#detectTypeFromFilename-java.lang.String-}
```
public static IResourceType detectTypeFromFilename(String filename)
```


Detecta un tipo a partir del nombre de archivo especificado y devuelve una instancia de
respectivo IResourceType


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | nombre de archivo | java.lang.String | Nombre de archivo de entrada, del cual este método intentará extraer la implementación resultante de IResourceType |
|

**Returns:**
[IResourceType](../../com.groupdocs.editor.htmlcss.resources/iresourcetype) - IResourceType implementation on success or NULL on failure

### tryDetectResource(InputStream inputResourceStream, String name, IResourceType assumptiveFormat) {#tryDetectResource-java.io.InputStream-java.lang.String-com.groupdocs.editor.htmlcss.resources.IResourceType-}
```
public static IHtmlResource tryDetectResource(InputStream inputResourceStream, String name, IResourceType assumptiveFormat)
```


Intenta analizar un flujo de entrada y crea uno de los HTML compatibles
recursos a partir de él, teniendo en cuenta un tipo supuesto especificado, si es
no es nulo


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | inputResourceStream | java.io.InputStream | Flujo de entrada, que presumiblemente contiene un recurso HTML. Si es inválido, se lanzará una excepción. |
|
|  | name | java.lang.String | Nombre del recurso, que se utilizará para el recurso creado y devuelto en caso de éxito. No puede ser NULL, vacío o contener solo espacios en blanco |
|
|  | assumptiveFormat | [IResourceType](../../com.groupdocs.editor.htmlcss.resources/iresourcetype) | Formato asumido del recurso HTML de entrada, que es útil para lograr el mejor rendimiento. Si es completamente desconocido, use el valor NULL. Puede ser incorrecto, lo que solo empeorará el rendimiento. |
|

**Returns:**
[IHtmlResource](../../com.groupdocs.editor.htmlcss.resources/ihtmlresource) - Instance, which implements 'IHtmlResource' interface and represents one of supportable HTML resources on success, or NULL on failure

