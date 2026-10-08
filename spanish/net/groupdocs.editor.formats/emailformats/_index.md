---
title: "EmailFormats"
second_title: "GroupDocs.Editor para .NET Referencia de API"
description: "Encapsula todos los formatos de correo electrónico. Incluye los siguientes tipos de archivo Tnef./emailformats/tnef Eml./emailformats/eml Emlx./emailformats/emlx Msg./emailformats/msg Html./emailformats/html Mhtml./emailformats/mhtml."
type: docs
weight: 90
url: /es/net/groupdocs.editor.formats/emailformats/
---
## EmailFormats class

Encapsula todos los formatos de correo electrónico. Incluye los siguientes tipos de archivo: [`Tnef`](./tnef), [`Eml`](./eml), [`Emlx`](./emlx), [`Msg`](./msg), [`Html`](./html), [`Mhtml`](./mhtml).

```csharp
public class EmailFormats : DocumentFormatBase
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Extension](../../groupdocs.editor.formats.abstraction/documentformatbase/extension) { get; } | Obtiene la extensión de archivo del formato de documento. |
| [FormatFamily](../../groupdocs.editor.formats.abstraction/documentformatbase/formatfamily) { get; } | Obtiene la familia de formato a la que pertenece el formato de documento. |
| [Id](../../groupdocs.editor.formats.abstraction/formatfamilybase/id) { get; } | Obtiene el identificador único de la familia de formato. |
| [Mime](../../groupdocs.editor.formats.abstraction/documentformatbase/mime) { get; } | Obtiene el tipo MIME del formato de documento. |
| [Name](../../groupdocs.editor.formats.abstraction/formatfamilybase/name) { get; } | Obtiene el nombre de la familia de formato. |
| static [All](../../groupdocs.editor.formats/emailformats/all) { get; } | Obtiene una colección enumerable de todos los [`EmailFormats`](../emailformats). |

## Métodos

| Nombre | Descripción |
| --- | --- |
| static [FromExtension](../../groupdocs.editor.formats/emailformats/fromextension)(string) | Recupera una instancia del tipo especificado [`EmailFormats`](../emailformats) que tiene la extensión de archivo especificada. |
| [Equals](../../groupdocs.editor.formats.abstraction/formatfamilybase/equals)(FormatFamilyBase) | Determina si esta instancia es igual a la instancia especificada de [`FormatFamilyBase`](../../groupdocs.editor.formats.abstraction/formatfamilybase). |
| [Equals](../../groupdocs.editor.formats.abstraction/documentformatbase/equals)(IDocumentFormat) | Determina si esta instancia es igual a la instancia especificada de [`IDocumentFormat`](../../groupdocs.editor.formats.abstraction/idocumentformat). |
| override [Equals](../../groupdocs.editor.formats.abstraction/documentformatbase/equals)(object) | Determina si esta instancia es igual a la instancia especificada de [`DocumentFormatBase`](../../groupdocs.editor.formats.abstraction/documentformatbase). |
| override [GetHashCode](../../groupdocs.editor.formats.abstraction/documentformatbase/gethashcode)() | Devuelve un código hash para el objeto actual. |
| override [ToString](../../groupdocs.editor.formats.abstraction/formatfamilybase/tostring)() | Devuelve una cadena que representa el objeto actual. |
| [explicit operator](../../groupdocs.editor.formats/emailformats/op_explicit) | Convierte una cadena que representa una extensión de archivo a un objeto [`EmailFormats`](../emailformats). |

## Campos

| Nombre | Descripción |
| --- | --- |
| static readonly [Eml](../../groupdocs.editor.formats/emailformats/eml) | El formato de archivo EML representa mensajes de correo electrónico guardados usando Outlook y otras aplicaciones relevantes. Obtenga más información sobre este formato de archivo [aquí](https://docs.fileformat.com/email/eml/). |
| static readonly [Emlx](../../groupdocs.editor.formats/emailformats/emlx) | El formato de archivo EMLX es implementado y desarrollado por Apple. La aplicación Apple Mail utiliza el formato de archivo EMLX para exportar los correos electrónicos. Obtenga más información sobre este formato de archivo [aquí](https://docs.fileformat.com/email/emlx/). |
| static readonly [Html](../../groupdocs.editor.formats/emailformats/html) | Correos electrónicos formateados en HTML. |
| static readonly [Ics](../../groupdocs.editor.formats/emailformats/ics) | La especificación Internet Calendaring and Scheduling Core Object Specification (iCalendar) es un estándar de internet (RFC 2445) para intercambiar y desplegar eventos de calendario y programación. Obtenga más información sobre este formato de archivo [aquí](https://docs.fileformat.com/email/ics/). |
| static readonly [Mbox](../../groupdocs.editor.formats/emailformats/mbox) | El formato de archivo MBox es un término genérico que representa un contenedor para una colección de mensajes de correo electrónico. Obtenga más información sobre este formato de archivo [aquí](https://docs.fileformat.com/email/mbox/). |
| static readonly [Mhtml](../../groupdocs.editor.formats/emailformats/mhtml) | MHTML, una sigla de "MIME encapsulation of aggregate HTML documents". |
| static readonly [Msg](../../groupdocs.editor.formats/emailformats/msg) | MSG es un formato de archivo utilizado por Microsoft Outlook y Exchange para almacenar mensajes de correo electrónico, contactos, citas u otras tareas. Obtenga más información sobre este formato de archivo [aquí](https://docs.fileformat.com/email/msg/). |
| static readonly [Oft](../../groupdocs.editor.formats/emailformats/oft) | Los archivos con extensión .oft son archivos de plantilla creados usando Microsoft Outlook. Obtenga más información sobre este formato de archivo [aquí](https://docs.fileformat.com/email/oft/). |
| static readonly [Ost](../../groupdocs.editor.formats/emailformats/ost) | El archivo Offline Storage Table (OST) representa los datos del buzón del usuario en modo offline en la máquina local tras el registro con Exchange Server usando Microsoft Outlook. Obtén más información sobre este formato de archivo [aquí](https://docs.fileformat.com/email/ost/). |
| static readonly [Pst](../../groupdocs.editor.formats/emailformats/pst) | Los archivos con extensión .pst representan Outlook Personal Storage Files (también llamados Personal Storage Table) que almacenan una variedad de información del usuario. Obtén más información sobre este formato de archivo [aquí](https://docs.fileformat.com/email/pst/). |
| static readonly [Tnef](../../groupdocs.editor.formats/emailformats/tnef) | Transport Neutral Encapsulation Format (TNEF) es un formato propietario de Microsoft para encapsular archivos adjuntos de correo electrónico basado en Messaging Application Programming Interface (MAPI). Obtén más información sobre este formato de archivo [aquí](https://docs.fileformat.com/email/tnef/). |
| static readonly [Vcf](../../groupdocs.editor.formats/emailformats/vcf) | VCF (Virtual Card Format) o vCard es un formato de archivo digital para almacenar información de contactos. Obtén más información sobre este formato de archivo [aquí](https://docs.fileformat.com/email/vcf/). |

### Observaciones

Obtén más información sobre el formato de correos electrónicos [aquí](https://docs.fileformat.com/email/).

### Ver también

* class [DocumentFormatBase](../../groupdocs.editor.formats.abstraction/documentformatbase)
* namespace [GroupDocs.Editor.Formats](../../groupdocs.editor.formats)
* assembly [GroupDocs.Editor](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.editor.dll -->
