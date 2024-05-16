---
title: EmailFormats
second_title: GroupDocs.Editor for .NET API Reference
description: Encapsulates all emails formats. Includes the following file types Tnef./emailformats/tnef Eml./emailformats/eml Emlx./emailformats/emlx Msg./emailformats/msg Html./emailformats/html Mhtml./emailformats/mhtml.
type: docs
weight: 70
url: /net/groupdocs.editor.formats/emailformats/
---
## EmailFormats structure

Encapsulates all emails formats. Includes the following file types: [`Tnef`](./tnef), [`Eml`](./eml), [`Emlx`](./emlx), [`Msg`](./msg), [`Html`](./html), [`Mhtml`](./mhtml).

```csharp
public struct EmailFormats : IDocumentFormat, IEquatable<EmailFormats>
```

## Properties

| Name | Description |
| --- | --- |
| [Extension](../../groupdocs.editor.formats/emailformats/extension) { get; } | In implementing type should return format file extension (without leading dot character). |
| [Mime](../../groupdocs.editor.formats/emailformats/mime) { get; } | In implementing type should return a MIME-code for the given format |
| [Name](../../groupdocs.editor.formats/emailformats/name) { get; } | In implementing type should return full formal format name |

## Methods

| Name | Description |
| --- | --- |
| static [FromExtension](../../groupdocs.editor.formats/emailformats/fromextension)(string) | Returns instance of [`EmailFormats`](../emailformats) structure, associated to specified filename extension, or throws an exception, if extension cannot be properly parsed |
| [Equals](../../groupdocs.editor.formats/emailformats/equals#equals)(EmailFormats) | Determines whether this instance is equal to the other specified Email instance |
| [Equals](../../groupdocs.editor.formats/emailformats/equals#equals_1)(IDocumentFormat) | Determines whether this instance is equal to the other specified IDocumentFormat instance |
| override [Equals](../../groupdocs.editor.formats/emailformats/equals#equals_2)(object) | Determines whether this instance is equal to the other specified object, that is presumably of boxed Email |
| override [GetHashCode](../../groupdocs.editor.formats/emailformats/gethashcode)() | Returns a hash-code, that is immutable for this instance |
| override [ToString](../../groupdocs.editor.formats/emailformats/tostring)() | Returns a format name of this format |
| [operator ==](../../groupdocs.editor.formats/emailformats/op_equality) | Checks two given Email instances on equality |
| [operator !=](../../groupdocs.editor.formats/emailformats/op_inequality) | Checks two given Email instances on inequality |

## Fields

| Name | Description |
| --- | --- |
| static readonly [Eml](../../groupdocs.editor.formats/emailformats/eml) | EML file format represents email messages saved using Outlook and other relevant applications. Learn more about this file format [here](https://docs.fileformat.com/email/eml/). |
| static readonly [Emlx](../../groupdocs.editor.formats/emailformats/emlx) | The EMLX file format is implemented and developed by Apple. The Apple Mail application uses the EMLX file format for exporting the emails. Learn more about this file format [here](https://docs.fileformat.com/email/emlx/). |
| static readonly [Html](../../groupdocs.editor.formats/emailformats/html) | HTML formatted emails. |
| static readonly [Ics](../../groupdocs.editor.formats/emailformats/ics) | The Internet Calendaring and Scheduling Core Object Specification (iCalendar) is an internet standard (RFC 2445) for exchanging and deploying the calendaring events and scheduling. Learn more about this file format [here](https://docs.fileformat.com/email/ics/). |
| static readonly [Mbox](../../groupdocs.editor.formats/emailformats/mbox) | MBox file format is a generic term that represents a container for collection of electronic mail messages. Learn more about this file format [here](https://docs.fileformat.com/email/mbox/). |
| static readonly [Mhtml](../../groupdocs.editor.formats/emailformats/mhtml) | MHTML, an initialism of "MIME encapsulation of aggregate HTML documents" |
| static readonly [Msg](../../groupdocs.editor.formats/emailformats/msg) | MSG is a file format used by Microsoft Outlook and Exchange to store email messages, contact, appointment, or other tasks. Learn more about this file format [here](https://docs.fileformat.com/email/msg/). |
| static readonly [Oft](../../groupdocs.editor.formats/emailformats/oft) | Files with .oft extension are template files that are created using Microsoft Outlook. Learn more about this file format [here](https://docs.fileformat.com/email/oft/). |
| static readonly [Ost](../../groupdocs.editor.formats/emailformats/ost) | Offline Storage Table (OST) file represents user’s mailbox data in offline mode on local machine upon registration with Exchange Server using Microsoft Outlook. Learn more about this file format [here](https://docs.fileformat.com/email/ost/). |
| static readonly [Pst](../../groupdocs.editor.formats/emailformats/pst) | Files with .pst extension represent Outlook Personal Storage Files (also called Personal Storage Table) that store variety of user information. Learn more about this file format [here](https://docs.fileformat.com/email/pst/). |
| static readonly [Tnef](../../groupdocs.editor.formats/emailformats/tnef) | Transport Neutral Encapsulation Format (TNEF) is a Microsoft proprietary, for encapsulating email attachments based on Messaging Application Programming Interface (MAPI). Learn more about this file format [here](https://docs.fileformat.com/email/tnef/). |
| static readonly [Vcf](../../groupdocs.editor.formats/emailformats/vcf) | VCF (Virtual Card Format) or vCard is a digital file format for storing contact information. Learn more about this file format [here](https://docs.fileformat.com/email/vcf/). |
| static readonly [All](../../groupdocs.editor.formats/emailformats/all) | Returns an internal class, that provides enumerable possibilities over all existing email formats |

## Other Members

| Name | Description |
| --- | --- |
| class [AllEnumerable](emailformats.allenumerable) | Implements IEnumerable generic interface, that enables a 'foreach' possibility for the Email type |

### Remarks

Learn more about emails format [here](https://docs.fileformat.com/email/).

### See Also

* interface [IDocumentFormat](../idocumentformat)
* namespace [GroupDocs.Editor.Formats](../../groupdocs.editor.formats)
* assembly [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.editor.dll -->
