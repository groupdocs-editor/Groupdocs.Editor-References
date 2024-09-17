---
title: EmailFormats
second_title: GroupDocs.Editor for Java API Reference
description: Encapsulates all emails formats.
type: docs
weight: 11
url: /java/com.groupdocs.editor.formats/emailformats/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.formats.abstraction.FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase), [com.groupdocs.editor.formats.abstraction.DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase)
```
public class EmailFormats extends DocumentFormatBase
```

Encapsulates all emails formats. Includes the following file types: [Tnef](../../com.groupdocs.editor.formats/emailformats\#Tnef), [Eml](../../com.groupdocs.editor.formats/emailformats\#Eml), [Emlx](../../com.groupdocs.editor.formats/emailformats\#Emlx), [Msg](../../com.groupdocs.editor.formats/emailformats\#Msg), [Html](../../com.groupdocs.editor.formats/emailformats\#Html), [Mhtml](../../com.groupdocs.editor.formats/emailformats\#Mhtml).

--------------------

Learn more about emails format [here][].


[here]: https://docs.fileformat.com/email/
## Fields

| Field | Description |
| --- | --- |
| [Tnef](#Tnef) | Transport Neutral Encapsulation Format (TNEF) is a Microsoft proprietary format for encapsulating email attachments based on Messaging Application Programming Interface (MAPI). |
| [Eml](#Eml) | EML file format represents email messages saved using Outlook and other relevant applications. |
| [Emlx](#Emlx) | The EMLX file format is implemented and developed by Apple. |
| [Msg](#Msg) | MSG is a file format used by Microsoft Outlook and Exchange to store email messages, contact, appointment, or other tasks. |
| [Html](#Html) | HTML formatted emails. |
| [Mhtml](#Mhtml) | MHTML, an initialism of "MIME encapsulation of aggregate HTML documents". |
| [Ics](#Ics) | The Internet Calendaring and Scheduling Core Object Specification (iCalendar) is an internet standard (RFC 2445) for exchanging and deploying calendaring events and scheduling. |
| [Vcf](#Vcf) | VCF (Virtual Card Format) or vCard is a digital file format for storing contact information. |
| [Pst](#Pst) | Files with .pst extension represent Outlook Personal Storage Files (also called Personal Storage Table) that store variety of user information. |
| [Mbox](#Mbox) | MBox file format is a generic term that represents a container for collection of electronic mail messages. |
| [Oft](#Oft) | Files with .oft extension are template files that are created using Microsoft Outlook. |
| [Ost](#Ost) | Offline Storage Table (OST) file represents user\\u2019s mailbox data in offline mode on local machine upon registration with Exchange Server using Microsoft Outlook. |
## Methods

| Method | Description |
| --- | --- |
| [getAll()](#getAll--) | Gets an enumerable collection of all [EmailFormats](../../com.groupdocs.editor.formats/emailformats). |
| [fromExtension(String extension)](#fromExtension-java.lang.String-) | Retrieves an instance of the specified type [EmailFormats](../../com.groupdocs.editor.formats/emailformats) that has the specified file extension. |
| [fromString(String extension)](#fromString-java.lang.String-) | Converts a string representing a file extension to a [EmailFormats](../../com.groupdocs.editor.formats/emailformats) object. |
### Tnef {#Tnef}
```
public static final EmailFormats Tnef
```


Transport Neutral Encapsulation Format (TNEF) is a Microsoft proprietary format for encapsulating email attachments based on Messaging Application Programming Interface (MAPI). Learn more about this file format  [here][] .


[here]: https://docs.fileformat.com/email/tnef/

### Eml {#Eml}
```
public static final EmailFormats Eml
```


EML file format represents email messages saved using Outlook and other relevant applications. Learn more about this file format  [here][] .


[here]: https://docs.fileformat.com/email/eml/

### Emlx {#Emlx}
```
public static final EmailFormats Emlx
```


The EMLX file format is implemented and developed by Apple. The Apple Mail application uses the EMLX file format for exporting the emails. Learn more about this file format  [here][] .


[here]: https://docs.fileformat.com/email/emlx/

### Msg {#Msg}
```
public static final EmailFormats Msg
```


MSG is a file format used by Microsoft Outlook and Exchange to store email messages, contact, appointment, or other tasks. Learn more about this file format  [here][] .


[here]: https://docs.fileformat.com/email/msg/

### Html {#Html}
```
public static final EmailFormats Html
```


HTML formatted emails.

### Mhtml {#Mhtml}
```
public static final EmailFormats Mhtml
```


MHTML, an initialism of "MIME encapsulation of aggregate HTML documents".

### Ics {#Ics}
```
public static final EmailFormats Ics
```


The Internet Calendaring and Scheduling Core Object Specification (iCalendar) is an internet standard (RFC 2445) for exchanging and deploying calendaring events and scheduling. Learn more about this file format  [here][] .


[here]: https://docs.fileformat.com/email/ics/

### Vcf {#Vcf}
```
public static final EmailFormats Vcf
```


VCF (Virtual Card Format) or vCard is a digital file format for storing contact information. Learn more about this file format  [here][] .


[here]: https://docs.fileformat.com/email/vcf/

### Pst {#Pst}
```
public static final EmailFormats Pst
```


Files with .pst extension represent Outlook Personal Storage Files (also called Personal Storage Table) that store variety of user information. Learn more about this file format  [here][] .


[here]: https://docs.fileformat.com/email/pst/

### Mbox {#Mbox}
```
public static final EmailFormats Mbox
```


MBox file format is a generic term that represents a container for collection of electronic mail messages. Learn more about this file format  [here][] .


[here]: https://docs.fileformat.com/email/mbox/

### Oft {#Oft}
```
public static final EmailFormats Oft
```


Files with .oft extension are template files that are created using Microsoft Outlook. Learn more about this file format  [here][] .


[here]: https://docs.fileformat.com/email/oft/

### Ost {#Ost}
```
public static final EmailFormats Ost
```


Offline Storage Table (OST) file represents user\\u2019s mailbox data in offline mode on local machine upon registration with Exchange Server using Microsoft Outlook. Learn more about this file format  [here][] .


[here]: https://docs.fileformat.com/email/ost/

### getAll() {#getAll--}
```
public static List<EmailFormats> getAll()
```


Gets an enumerable collection of all [EmailFormats](../../com.groupdocs.editor.formats/emailformats).

Value: An  IEnumerable\{EmailFormats\}  containing all instances of [EmailFormats](../../com.groupdocs.editor.formats/emailformats).

**Returns:**
java.util.List<com.groupdocs.editor.formats.EmailFormats>
### fromExtension(String extension) {#fromExtension-java.lang.String-}
```
public static EmailFormats fromExtension(String extension)
```


Retrieves an instance of the specified type [EmailFormats](../../com.groupdocs.editor.formats/emailformats) that has the specified file extension.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| extension | java.lang.String | The file extension of the document format. |

**Returns:**
[EmailFormats](../../com.groupdocs.editor.formats/emailformats) - An instance of the specified type [EmailFormats](../../com.groupdocs.editor.formats/emailformats) with the specified file extension.
### fromString(String extension) {#fromString-java.lang.String-}
```
public static EmailFormats fromString(String extension)
```


Converts a string representing a file extension to a [EmailFormats](../../com.groupdocs.editor.formats/emailformats) object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| extension | java.lang.String | The file extension to convert. If the extension contains multiple periods, the part after the last period is used. |

**Returns:**
[EmailFormats](../../com.groupdocs.editor.formats/emailformats) - A [EmailFormats](../../com.groupdocs.editor.formats/emailformats) object corresponding to the specified file extension.
