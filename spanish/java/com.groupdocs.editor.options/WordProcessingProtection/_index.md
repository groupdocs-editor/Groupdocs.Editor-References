---
title: "WordProcessingProtection"
second_title: "GroupDocs.Editor for Java API Reference"
description: "Encapsula opciones de protección de documento para el documento WordProcessing que se genera a partir de HTML"
type: docs
weight: 46
url: /es/java/com.groupdocs.editor.options/wordprocessingprotection/
---
**Inheritance:**
java.lang.Object
```
public final class WordProcessingProtection
```

Encapsula opciones de protección de documento para el documento WordProcessing,
que se genera a partir de HTML

## Constructores

| Constructor | Descripción |
| --- | --- |
|  | [WordProcessingProtection()](#WordProcessingProtection--) | Constructor sin parámetros - todos los parámetros tienen valores predeterminados |
|
|  | [WordProcessingProtection(int protectionType, String password)](#WordProcessingProtection-int-java.lang.String-) | Permite establecer todos los parámetros durante la instanciación de la clase |
|
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getProtectionType()](#getProtectionType--) | Permite establecer un tipo de protección del documento. |
|
|  | [setProtectionType(int value)](#setProtectionType-int-) | Permite establecer un tipo de protección del documento. |
|
|  | [getPassword()](#getPassword--) | La contraseña para proteger el documento. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | La contraseña para proteger el documento. |
|
| [convertToAsposeWords(int protectionType)](#convertToAsposeWords-int-) |  |
### WordProcessingProtection() {#WordProcessingProtection--}
```
public WordProcessingProtection()
```


Constructor sin parámetros - todos los parámetros tienen valores predeterminados


### WordProcessingProtection(int protectionType, String password) {#WordProcessingProtection-int-java.lang.String-}
```
public WordProcessingProtection(int protectionType, String password)
```


Permite establecer todos los parámetros durante la instanciación de la clase


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | protectionType | int | Establecer el tipo de protección del documento |
|
|  | contraseña | java.lang.String | Establecer la contraseña de protección |
|

### getProtectionType() {#getProtectionType--}
```
public final int getProtectionType()
```


Permite establecer un tipo de protección del documento. Por defecto está configurado a no
proteger el documento en absoluto.


**Returns:**
int
### setProtectionType(int value) {#setProtectionType-int-}
```
public final void setProtectionType(int value)
```


Permite establecer un tipo de protección del documento. Por defecto está configurado a no
proteger el documento en absoluto.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
```


La contraseña con la que proteger el documento. Si es nula o una cadena vacía - la
protección no se aplicará al documento.


**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


La contraseña con la que proteger el documento. Si es nula o una cadena vacía - la
protección no se aplicará al documento.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### convertToAsposeWords(int protectionType) {#convertToAsposeWords-int-}
```
public static int convertToAsposeWords(int protectionType)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| protectionType | int |  |

**Returns:**
int
