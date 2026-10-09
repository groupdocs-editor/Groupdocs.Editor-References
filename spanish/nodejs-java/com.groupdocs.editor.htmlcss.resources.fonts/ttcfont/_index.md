---
title: "TtcFont"
second_title: "Referencia de API de GroupDocs.Editor para Node.js vía Java"
description: "Representa una fuente en el formato TTC TrueType Collection"
type: docs
weight: 14
url: /es/nodejs-java/com.groupdocs.editor.htmlcss.resources.fonts/ttcfont/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.fonts.FontResourceBase](../../com.groupdocs.editor.htmlcss.resources.fonts/fontresourcebase)
```
public final class TtcFont extends FontResourceBase
```

Representa una fuente en formato TTC (TrueType Collection).


Ver más: https://docs.fileformat.com/font/ttc/

## Constructores

| Constructor | Descripción |
| --- | --- |
|  | [TtcFont(String name, String contentInBase64)](#TtcFont-java.lang.String-java.lang.String-) | Crea una nueva clase TtcFont a partir del contenido, representado como codificado en base64 |
cadena, y con el nombre especificado
|
|  | [TtcFont(String name, InputStream binaryContent)](#TtcFont-java.lang.String-java.io.InputStream-) | Crea una nueva clase TtcFont a partir del contenido, representado como flujo de bytes, y |
con el nombre especificado
|
## Campos

| Campo | Descripción |
| --- | --- |
|  | [RequiredHeaderSize](#RequiredHeaderSize) | Tamaño del encabezado TTC (en bytes), que es necesario para su validación |
|
## Métodos

| Método | Descripción |
| --- | --- |
|  | [isValid(InputStream binaryContent)](#isValid-java.io.InputStream-) | Comprueba si el flujo especificado es una fuente TTC válida |
|
|  | [isValid(String contentInBase64)](#isValid-java.lang.String-) | Comprueba si la cadena codificada en base64 especificada es una fuente TTC válida |
|
|  | [getType()](#getType--) | Devuelve FontType.Ttc |
|
|  | [getHeaderVersion()](#getHeaderVersion--) | Versión del encabezado TTC, puede ser "1" o "2" |
|
|  | [getFontsNumber()](#getFontsNumber--) | Número de fuentes en este TTC |
|
|  | [getHasDsigTable()](#getHasDsigTable--) | Indica si este TTC tiene una tabla DSIG. |
|
### TtcFont(String name, String contentInBase64) {#TtcFont-java.lang.String-java.lang.String-}
```
public TtcFont(String name, String contentInBase64)
```


Crea una nueva clase TtcFont a partir del contenido, representado como codificado en base64
cadena, y con el nombre especificado


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | name | java.lang.String | Nombre de la fuente TTC. No puede ser nulo, vacío o contener solo espacios. |
|
|  | contentInBase64 | java.lang.String | Contenido como cadena codificada en base64. No puede ser nulo, vacío o contener solo espacios. Si no es un contenido TTC, se lanzará una excepción. |
|

### TtcFont(String name, InputStream binaryContent) {#TtcFont-java.lang.String-java.io.InputStream-}
```
public TtcFont(String name, InputStream binaryContent)
```


Crea una nueva clase TtcFont a partir del contenido, representado como flujo de bytes, y
con el nombre especificado


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | name | java.lang.String | Nombre de la fuente TTC. No puede ser nulo, vacío o contener solo espacios. |
|
|  | binaryContent | java.io.InputStream | Contenido como flujo de bytes. La lectura comienza desde la posición original. No puede ser nulo. Debe ser legible y buscable. Si esta instancia se descarta, este flujo también se descartará. |
|

### RequiredHeaderSize {#RequiredHeaderSize}
```
public static final int RequiredHeaderSize
```


Tamaño del encabezado TTC (en bytes), que es necesario para su validación


### isValid(InputStream binaryContent) {#isValid-java.io.InputStream-}
```
public static boolean isValid(InputStream binaryContent)
```


Comprueba si el flujo especificado es una fuente TTC válida


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | binaryContent | java.io.InputStream | Flujo de bytes, que presumiblemente contiene un recurso TTC |
|

**Returns:**
boolean - Verdadero si el flujo especificado contiene una fuente TTC válida, falso de lo contrario

### isValid(String contentInBase64) {#isValid-java.lang.String-}
```
public static boolean isValid(String contentInBase64)
```


Comprueba si la cadena codificada en base64 especificada es una fuente TTC válida


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | Contenido de la supuesta fuente TTC en forma de cadena codificada en base64 |
|

**Returns:**
boolean - Verdadero si la cadena especificada contiene una fuente TTC válida, falso de lo contrario

### getType() {#getType--}
```
public FontType getType()
```


Devuelve FontType.Ttc


**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype)
### getHeaderVersion() {#getHeaderVersion--}
```
public byte getHeaderVersion()
```


Versión del encabezado TTC, puede ser "1" o "2"


**Returns:**
byte
### getFontsNumber() {#getFontsNumber--}
```
public long getFontsNumber()
```


Número de fuentes en este TTC


**Returns:**
long
### getHasDsigTable() {#getHasDsigTable--}
```
public boolean getHasDsigTable()
```


Indica si este TTC tiene una tabla DSIG. La tabla DSIG puede estar presente
solo si el TTC tiene una cabecera versión 2.0.


**Returns:**
booleano
