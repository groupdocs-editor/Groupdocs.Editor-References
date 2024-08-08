---
title: EmailFormats
second_title: GroupDocs.Editor for .NET API Reference
description: Encapsulates all emails formats. Includes the following file types Tnef./emailformats/tnef Eml./emailformats/eml Emlx./emailformats/emlx Msg./emailformats/msg Html./emailformats/html Mhtml./emailformats/mhtml.
type: docs
weight: 90
url: /net/groupdocs.editor.formats/emailformats/
---
## EmailFormats class

Encapsulates all emails formats. Includes the following file types: [`Tnef`](./tnef), [`Eml`](./eml), [`Emlx`](./emlx), [`Msg`](./msg), [`Html`](./html), [`Mhtml`](./mhtml).

```csharp
public class EmailFormats : DocumentFormatBase
```

## Properties

| Name | Description |
| --- | --- |
| [Extension](../../groupdocs.editor.formats.abstraction/documentformatbase/extension) { get; } | Gets the file extension of the document format. |
| [FormatFamily](../../groupdocs.editor.formats.abstraction/documentformatbase/formatfamily) { get; } | Gets the format family to which the document format belongs. |
| [Id](../../groupdocs.editor.formats.abstraction/formatfamilybase/id) { get; } | Gets the unique identifier for the format family. |
| [Mime](../../groupdocs.editor.formats.abstraction/documentformatbase/mime) { get; } | Gets the MIME type of the document format. |
| [Name](../../groupdocs.editor.formats.abstraction/formatfamilybase/name) { get; } | Gets the name of the format family. |
| static [All](../../groupdocs.editor.formats/emailformats/all) { get; } | Gets an enumerable collection of all [`EmailFormats`](../emailformats). |

## Methods

| Name | Description |
| --- | --- |
| static [FromExtension](../../groupdocs.editor.formats/emailformats/fromextension)(string) | Retrieves an instance of the specified type [`EmailFormats`](../emailformats) that has the specified file extension. |
| [Equals](../../groupdocs.editor.formats.abstraction/formatfamilybase/equals)(FormatFamilyBase) | Determines whether this instance is equal to the specified [`FormatFamilyBase`](../../groupdocs.editor.formats.abstraction/formatfamilybase) instance. |
| [Equals](../../groupdocs.editor.formats.abstraction/documentformatbase/equals)(IDocumentFormat) | Determines whether this instance is equal to the specified [`IDocumentFormat`](../../groupdocs.editor.formats.abstraction/idocumentformat) instance. |
| override [Equals](../../groupdocs.editor.formats.abstraction/documentformatbase/equals)(object) | Determines whether this instance is equal to the specified [`DocumentFormatBase`](../../groupdocs.editor.formats.abstraction/documentformatbase) instance. |
| override [GetHashCode](../../groupdocs.editor.formats.abstraction/documentformatbase/gethashcode)() | Returns a hash code for the current object. |
| override [ToString](../../groupdocs.editor.formats.abstraction/formatfamilybase/tostring)() | Returns a string that represents the current object. |
| [explicit operator](../../groupdocs.editor.formats/emailformats/op_explicit) | Converts a string representing a file extension to a [`EmailFormats`](../emailformats) object. |

## Fields

| Name | Description |
| --- | --- |
| static readonly [Eml](../../groupdocs.editor.formats/emailformats/eml) | EML file format represents email messages saved using Outlook and other relevant applications. Learn more about this file format [here](https://docs.fileformat.com/email/eml/). |
| static readonly [Emlx](../../groupdocs.editor.formats/emailformats/emlx) | The EMLX file format is implemented and developed by Apple. The Apple Mail application uses the EMLX file format for exporting the emails. Learn more about this file format [here](https://docs.fileformat.com/email/emlx/). |
| static readonly [Html](../../groupdocs.editor.formats/emailformats/html) | HTML formatted emails. |
| static readonly [Ics](../../groupdocs.editor.formats/emailformats/ics) | The Internet Calendaring and Scheduling Core Object Specification (iCalendar) is an internet standard (RFC 2445) for exchanging and deploying calendaring events and scheduling. Learn more about this file format [here](https://docs.fileformat.com/email/ics/). |
| static readonly [Mbox](../../groupdocs.editor.formats/emailformats/mbox) | MBox file format is a generic term that represents a container for collection of electronic mail messages. Learn more about this file format [here](https://docs.fileformat.com/email/mbox/). |
| static readonly [Mhtml](../../groupdocs.editor.formats/emailformats/mhtml) | MHTML, an initialism of "MIME encapsulation of aggregate HTML documents". |
| static readonly [Msg](../../groupdocs.editor.formats/emailformats/msg) | MSG is a file format used by Microsoft Outlook and Exchange to store email messages, contact, appointment, or other tasks. Learn more about this file format [here](https://docs.fileformat.com/email/msg/). |
| static readonly [Oft](../../groupdocs.editor.formats/emailformats/oft) | Files with .oft extension are template files that are created using Microsoft Outlook. Learn more about this file format [here](https://docs.fileformat.com/email/oft/). |
| static readonly [Ost](../../groupdocs.editor.formats/emailformats/ost) | Offline Storage Table (OST) file represents user’s mailbox data in offline mode on local machine upon registration with Exchange Server using Microsoft Outlook. Learn more about this file format [here](https://docs.fileformat.com/email/ost/). |
| static readonly [Pst](../../groupdocs.editor.formats/emailformats/pst) | Files with .pst extension represent Outlook Personal Storage Files (also called Personal Storage Table) that store variety of user information. Learn more about this file format [here](https://docs.fileformat.com/email/pst/). |
| static readonly [Tnef](../../groupdocs.editor.formats/emailformats/tnef) | Transport Neutral Encapsulation Format (TNEF) is a Microsoft proprietary format for encapsulating email attachments based on Messaging Application Programming Interface (MAPI). Learn more about this file format [here](https://docs.fileformat.com/email/tnef/). |
| static readonly [Vcf](../../groupdocs.editor.formats/emailformats/vcf) | VCF (Virtual Card Format) or vCard is a digital file format for storing contact information. Learn more about this file format [here](https://docs.fileformat.com/email/vcf/). |

### Remarks

Learn more about emails format [here](https://docs.fileformat.com/email/).

### See Also

* class [DocumentFormatBase](../../groupdocs.editor.formats.abstraction/documentformatbase)
* namespace [GroupDocs.Editor.Formats](../../groupdocs.editor.formats)
* assembly [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.editor.dll -->
