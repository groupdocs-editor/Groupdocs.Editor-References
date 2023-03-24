---
title: EmailFormats
second_title: Referencia de API de GroupDocs.Editor para .NET
description: Encapsula todos los formatos de correo electrónico. Incluye los siguientes tipos de archivo Tnef./emailformats/tnef  Eml./emailformats/eml  Emlx./emailformats/emlx  Msg./emailformats/msg  Html./emailformats/html  Mhtml./emailformats/mhtml .
type: docs
weight: 60
url: /es/net/groupdocs.editor.formats/emailformats/
---
## EmailFormats structure

Encapsula todos los formatos de correo electrónico. Incluye los siguientes tipos de archivo: [`Tnef`](./tnef) , [`Eml`](./eml) , [`Emlx`](./emlx) , [`Msg`](./msg) , [`Html`](./html) , [`Mhtml`](./mhtml) .

```csharp
public struct EmailFormats : IDocumentFormat, IEquatable<EmailFormats>
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Extension](../../groupdocs.editor.formats/emailformats/extension) { get; } | Al implementar el tipo, debe devolver la extensión del archivo de formato (sin el carácter de punto inicial). |
| [Mime](../../groupdocs.editor.formats/emailformats/mime) { get; } | Al implementar el tipo, debe devolver un código MIME para el formato dado |
| [Name](../../groupdocs.editor.formats/emailformats/name) { get; } | Al implementar el tipo, debe devolver el formato formal completo name |

## Métodos

| Nombre | Descripción |
| --- | --- |
| static [FromExtension](../../groupdocs.editor.formats/emailformats/fromextension)(string) | Devuelve instancia de[`EmailFormats`](../emailformats) estructura, asociada a la extensión de nombre de archivo especificada, o genera una excepción, si la extensión no se puede analizar correctamente |
| [Equals](../../groupdocs.editor.formats/emailformats/equals#equals)(EmailFormats) | Determina si esta instancia es igual a la otra instancia de correo electrónico especificada |
| [Equals](../../groupdocs.editor.formats/emailformats/equals#equals_1)(IDocumentFormat) | Determina si esta instancia es igual a la otra instancia de IDocumentFormat especificada |
| override [Equals](../../groupdocs.editor.formats/emailformats/equals#equals_2)(object) | Determina si esta instancia es igual al otro objeto especificado, que presumiblemente es del correo electrónico en caja |
| override [GetHashCode](../../groupdocs.editor.formats/emailformats/gethashcode)() | Devuelve un código hash, que es inmutable para esta instancia |
| override [ToString](../../groupdocs.editor.formats/emailformats/tostring)() | Devuelve un nombre de formato de este formato |
| [operator ==](../../groupdocs.editor.formats/emailformats/op_equality) | Comprueba dos instancias de correo electrónico dadas en igualdad |
| [operator !=](../../groupdocs.editor.formats/emailformats/op_inequality) | Comprueba dos instancias de correo electrónico dadas en desigualdad |

## Campos

| Nombre | Descripción |
| --- | --- |
| static readonly [Eml](../../groupdocs.editor.formats/emailformats/eml) | El formato de archivo EML representa los mensajes de correo electrónico guardados con Outlook y otras aplicaciones relevantes. Más información sobre este formato de archivo[aquí](https://docs.fileformat.com/email/eml/) . |
| static readonly [Emlx](../../groupdocs.editor.formats/emailformats/emlx) | Apple implementa y desarrolla el formato de archivo EMLX. La aplicación Apple Mail utiliza el formato de archivo EMLX para exportar los correos electrónicos. Más información sobre este formato de archivo[aquí](https://docs.fileformat.com/email/emlx/) . |
| static readonly [Html](../../groupdocs.editor.formats/emailformats/html) | correos electrónicos con formato HTML. |
| static readonly [Ics](../../groupdocs.editor.formats/emailformats/ics) | Internet Calendaring and Scheduling Core Object Specification (iCalendar) es un estándar de Internet (RFC 2445) para intercambiar e implementar eventos de calendario y programación. Más información sobre este formato de archivo[aquí](https://docs.fileformat.com/email/ics/) . |
| static readonly [Mbox](../../groupdocs.editor.formats/emailformats/mbox) | El formato de archivo MBox es un término genérico que representa un contenedor para la recopilación de mensajes de correo electrónico. Más información sobre este formato de archivo[aquí](https://docs.fileformat.com/email/mbox/) . |
| static readonly [Mhtml](../../groupdocs.editor.formats/emailformats/mhtml) | MHTML, una sigla de "Encapsulación MIME de documentos HTML agregados" |
| static readonly [Msg](../../groupdocs.editor.formats/emailformats/msg) | MSG es un formato de archivo utilizado por Microsoft Outlook y Exchange para almacenar mensajes de correo electrónico, contactos, citas u otras tareas. Más información sobre este formato de archivo[aquí](https://docs.fileformat.com/email/msg/) . |
| static readonly [Oft](../../groupdocs.editor.formats/emailformats/oft) | Los archivos con la extensión .oft son archivos de plantilla que se crean con Microsoft Outlook. Más información sobre este formato de archivo[aquí](https://docs.fileformat.com/email/oft/) . |
| static readonly [Ost](../../groupdocs.editor.formats/emailformats/ost) | El archivo de tabla de almacenamiento fuera de línea (OST) representa los datos del buzón de correo del usuario en modo fuera de línea en la máquina local al registrarse con Exchange Server usando Microsoft Outlook. Más información sobre este formato de archivo[aquí](https://docs.fileformat.com/email/ost/) . |
| static readonly [Pst](../../groupdocs.editor.formats/emailformats/pst) | Los archivos con extensión .pst representan archivos de almacenamiento personal de Outlook (también llamados tablas de almacenamiento personal) que almacenan una variedad de información del usuario. Más información sobre este formato de archivo[aquí](https://docs.fileformat.com/email/pst/) . |
| static readonly [Tnef](../../groupdocs.editor.formats/emailformats/tnef) | El formato de encapsulación neutral para el transporte (TNEF) es propiedad de Microsoft, para encapsular archivos adjuntos de correo electrónico basados en la interfaz de programación de aplicaciones de mensajería (MAPI). Obtenga más información sobre este formato de archivo[aquí](https://docs.fileformat.com/email/tnef/) . |
| static readonly [Vcf](../../groupdocs.editor.formats/emailformats/vcf) | VCF (formato de tarjeta virtual) o vCard es un formato de archivo digital para almacenar información de contacto. Más información sobre este formato de archivo[aquí](https://docs.fileformat.com/email/vcf/) . |
| static readonly [All](../../groupdocs.editor.formats/emailformats/all) | Devuelve una clase interna que proporciona posibilidades enumerables sobre todos los formatos de correo electrónico existentes |

## Otros miembros

| Nombre | Descripción |
| --- | --- |
| class [AllEnumerable](emailformats.allenumerable) | Implementa la interfaz genérica IEnumerable, que permite la posibilidad de 'foreach' para el tipo de correo electrónico |

### Observaciones

Obtenga más información sobre el formato de los correos electrónicos[aquí](https://docs.fileformat.com/email/) .

### Ver también

* interface [IDocumentFormat](../idocumentformat)
* espacio de nombres [GroupDocs.Editor.Formats](../../groupdocs.editor.formats)
* asamblea [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
