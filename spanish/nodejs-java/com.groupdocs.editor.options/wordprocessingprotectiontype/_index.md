---
title: "WordProcessingProtectionType"
second_title: "Referencia de API de GroupDocs.Editor para Node.js vía Java"
description: "Representa todos los tipos de protección disponibles del documento de procesamiento de texto."
type: docs
weight: 47
url: /es/nodejs-java/com.groupdocs.editor.options/wordprocessingprotectiontype/
---
**Inheritance:**
java.lang.Object
```
public final class WordProcessingProtectionType
```

Representa todos los tipos de protección disponibles del documento de procesamiento de texto.

## Campos

| Campo | Descripción |
| --- | --- |
|  | [NoProtection](#NoProtection) | El documento no está protegido. |
|
|  | [AllowOnlyRevisions](#AllowOnlyRevisions) | El usuario solo puede agregar marcas de revisión al documento |
|
|  | [AllowOnlyComments](#AllowOnlyComments) | El usuario solo puede modificar los comentarios en el documento |
|
|  | [AllowOnlyFormFields](#AllowOnlyFormFields) | El usuario solo puede ingresar datos en los campos de formulario del documento |
|
|  | [ReadOnly](#ReadOnly) | No se permiten cambios en el documento |
|
## Métodos

| Método | Descripción |
| --- | --- |
| [getAll()](#getAll--) |  |
### NoProtection {#NoProtection}
```
public static final int NoProtection
```


El documento no está protegido. Valor predeterminado.


### AllowOnlyRevisions {#AllowOnlyRevisions}
```
public static final int AllowOnlyRevisions
```


El usuario solo puede agregar marcas de revisión al documento


### AllowOnlyComments {#AllowOnlyComments}
```
public static final int AllowOnlyComments
```


El usuario solo puede modificar los comentarios en el documento


### AllowOnlyFormFields {#AllowOnlyFormFields}
```
public static final int AllowOnlyFormFields
```


El usuario solo puede ingresar datos en los campos de formulario del documento


### ReadOnly {#ReadOnly}
```
public static final int ReadOnly
```


No se permiten cambios en el documento


### getAll() {#getAll--}
```
public static Map<Integer,String> getAll()
```




**Returns:**
java.util.Map<java.lang.Integer,java.lang.String>
