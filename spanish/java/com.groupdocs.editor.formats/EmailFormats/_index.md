---
title: "EmailFormats"
second_title: "GroupDocs.Editor for Java API Reference"
description: "Encapsula todos los formatos de correo electrónico."
type: docs
weight: 11
url: /es/java/com.groupdocs.editor.formats/emailformats/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.formats.abstraction.FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase), [com.groupdocs.editor.formats.abstraction.DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase)
```
public class EmailFormats extends DocumentFormatBase
```

Encapsula todos los formatos de correo electrónico. Incluye los siguientes tipos de archivo:
[Tnef](../../com.groupdocs.editor.formats/emailformats#Tnef),
[Eml](../../com.groupdocs.editor.formats/emailformats#Eml),
[Emlx](../../com.groupdocs.editor.formats/emailformats#Emlx),
[Msg](../../com.groupdocs.editor.formats/emailformats#Msg),
[Html](../../com.groupdocs.editor.formats/emailformats#Html),
[Mhtml](../../com.groupdocs.editor.formats/emailformats#Mhtml).

<br />

*** ** * ** ***

Obtenga más información sobre el formato de correos electrónicos [aquí](../https://docs.fileformat.com/email/).

<br />


## Campos

| Campo | Descripción |
| --- | --- |
|  | [Tnef](#Tnef) | Transport Neutral Encapsulation Format (TNEF) es un formato propietario de Microsoft para encapsular archivos adjuntos de correo electrónico basado en Messaging Application Programming Interface (MAPI). |
|
|  | [Eml](#Eml) | El formato de archivo EML representa mensajes de correo electrónico guardados usando Outlook y otras aplicaciones relevantes. |
|
|  | [Emlx](#Emlx) | El formato de archivo EMLX está implementado y desarrollado por Apple. |
|
|  | [Msg](#Msg) | MSG es un formato de archivo utilizado por Microsoft Outlook y Exchange para almacenar mensajes de correo electrónico, contactos, citas u otras tareas. |
|
|  | [Html](#Html) | Correos electrónicos con formato HTML. |
|
|  | [Mhtml](#Mhtml) | MHTML, una sigla de "MIME encapsulation of aggregate HTML documents". |
|
|  | [Ics](#Ics) | La especificación Internet Calendaring and Scheduling Core Object Specification (iCalendar) es un estándar de internet (RFC 2445) para intercambiar y desplegar eventos de calendario y programación. |
|
|  | [Vcf](#Vcf) | VCF (Virtual Card Format) o vCard es un formato de archivo digital para almacenar información de contactos. |
|
|  | [Pst](#Pst) | Los archivos con extensión .pst representan Outlook Personal Storage Files (también llamados Personal Storage Table) que almacenan una variedad de información del usuario. |
|
|  | [Mbox](#Mbox) | El formato de archivo MBox es un término genérico que representa un contenedor para una colección de mensajes de correo electrónico. |
|
|  | [Oft](#Oft) | Los archivos con extensión .oft son archivos de plantilla que se crean usando Microsoft Outlook. |
|
|  | [Ost](#Ost) | El archivo Offline Storage Table (OST) representa los datos del buzón del usuario\u2019s en modo offline en la máquina local tras el registro con Exchange Server usando Microsoft Outlook. |
|
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getAll()](#getAll--) | Obtiene una colección enumerable de todos los [EmailFormats](../../com.groupdocs.editor.formats/emailformats). |
|
|  | [fromExtension(String extension)](#fromExtension-java.lang.String-) | Recupera una instancia del tipo especificado [EmailFormats](../../com.groupdocs.editor.formats/emailformats) que tiene la extensión de archivo especificada. |
|
|  | [fromString(String extension)](#fromString-java.lang.String-) | Convierte una cadena que representa una extensión de archivo a un objeto [EmailFormats](../../com.groupdocs.editor.formats/emailformats). |
|
### Tnef {#Tnef}
```
public static final EmailFormats Tnef
```


Transport Neutral Encapsulation Format (TNEF) es un formato propietario de Microsoft para encapsular archivos adjuntos de correo electrónico basado en Messaging Application Programming Interface (MAPI).
Obtén más información sobre este formato de archivo
[here](../https://docs.fileformat.com/email/tnef/)
.


### Eml {#Eml}
```
public static final EmailFormats Eml
```


El formato de archivo EML representa mensajes de correo electrónico guardados usando Outlook y otras aplicaciones relevantes.
Obtén más información sobre este formato de archivo
[here](../https://docs.fileformat.com/email/eml/)
.


### Emlx {#Emlx}
```
public static final EmailFormats Emlx
```


El formato de archivo EMLX está implementado y desarrollado por Apple. La aplicación Apple Mail usa el formato de archivo EMLX para exportar los correos electrónicos.
Obtén más información sobre este formato de archivo
[here](../https://docs.fileformat.com/email/emlx/)
.


### Msg {#Msg}
```
public static final EmailFormats Msg
```


MSG es un formato de archivo utilizado por Microsoft Outlook y Exchange para almacenar mensajes de correo electrónico, contactos, citas u otras tareas.
Obtén más información sobre este formato de archivo
[here](../https://docs.fileformat.com/email/msg/)
.


### Html {#Html}
```
public static final EmailFormats Html
```


Correos electrónicos con formato HTML.


### Mhtml {#Mhtml}
```
public static final EmailFormats Mhtml
```


MHTML, una sigla de "MIME encapsulation of aggregate HTML documents".


### Ics {#Ics}
```
public static final EmailFormats Ics
```


La especificación Internet Calendaring and Scheduling Core Object Specification (iCalendar) es un estándar de internet (RFC 2445) para intercambiar y desplegar eventos de calendario y programación.
Obtén más información sobre este formato de archivo
[here](../https://docs.fileformat.com/email/ics/)
.


### Vcf {#Vcf}
```
public static final EmailFormats Vcf
```


VCF (Virtual Card Format) o vCard es un formato de archivo digital para almacenar información de contactos.
Obtén más información sobre este formato de archivo
[here](../https://docs.fileformat.com/email/vcf/)
.


### Pst {#Pst}
```
public static final EmailFormats Pst
```


Los archivos con extensión .pst representan Outlook Personal Storage Files (también llamados Personal Storage Table) que almacenan una variedad de información del usuario.
Obtén más información sobre este formato de archivo
[here](../https://docs.fileformat.com/email/pst/)
.


### Mbox {#Mbox}
```
public static final EmailFormats Mbox
```


El formato de archivo MBox es un término genérico que representa un contenedor para una colección de mensajes de correo electrónico.
Obtén más información sobre este formato de archivo
[here](../https://docs.fileformat.com/email/mbox/)
.


### Oft {#Oft}
```
public static final EmailFormats Oft
```


Los archivos con extensión .oft son archivos de plantilla que se crean usando Microsoft Outlook.
Obtén más información sobre este formato de archivo
[here](../https://docs.fileformat.com/email/oft/)
.


### Ost {#Ost}
```
public static final EmailFormats Ost
```


El archivo Offline Storage Table (OST) representa los datos del buzón del usuario\u2019s en modo offline en la máquina local tras el registro con Exchange Server usando Microsoft Outlook.
Obtén más información sobre este formato de archivo
[here](../https://docs.fileformat.com/email/ost/)
.


### getAll() {#getAll--}
```
public static List<EmailFormats> getAll()
```


Obtiene una colección enumerable de todos los [EmailFormats](../../com.groupdocs.editor.formats/emailformats).
Valor: Un IEnumerable{EmailFormats} que contiene todas las instancias de [EmailFormats](../../com.groupdocs.editor.formats/emailformats).


**Returns:**
java.util.List<com.groupdocs.editor.formats.EmailFormats>
### fromExtension(String extension) {#fromExtension-java.lang.String-}
```
public static EmailFormats fromExtension(String extension)
```


Recupera una instancia del tipo especificado [EmailFormats](../../com.groupdocs.editor.formats/emailformats) que tiene la extensión de archivo especificada.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | extensión | java.lang.String | La extensión de archivo del formato del documento. |
|

**Returns:**
[EmailFormats](../../com.groupdocs.editor.formats/emailformats) - An instance of the specified type [EmailFormats](../../com.groupdocs.editor.formats/emailformats) with the specified file extension.

### fromString(String extension) {#fromString-java.lang.String-}
```
public static EmailFormats fromString(String extension)
```


Convierte una cadena que representa una extensión de archivo a un objeto [EmailFormats](../../com.groupdocs.editor.formats/emailformats).


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | extensión | java.lang.String | La extensión de archivo a convertir. Si la extensión contiene varios puntos, se usa la parte después del último punto. |
|

**Returns:**
[EmailFormats](../../com.groupdocs.editor.formats/emailformats) - A [EmailFormats](../../com.groupdocs.editor.formats/emailformats) object corresponding to the specified file extension.

