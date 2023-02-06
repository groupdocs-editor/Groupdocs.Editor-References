---
title: EmailFormats
second_title: GroupDocs.Editor for Java API Reference
description: Encapsulates all emails formats.
type: docs
weight: 10
url: /java/com.groupdocs.editor.formats/emailformats/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.formats.IDocumentFormat](../../com.groupdocs.editor.formats/idocumentformat)
```
public class EmailFormats implements IDocumentFormat
```

Encapsulates all emails formats. Includes the following file types: [Tnef](../../com.groupdocs.editor.formats/emailformats\#Tnef), [Eml](../../com.groupdocs.editor.formats/emailformats\#Eml), [Emlx](../../com.groupdocs.editor.formats/emailformats\#Emlx), [Msg](../../com.groupdocs.editor.formats/emailformats\#Msg), [Html](../../com.groupdocs.editor.formats/emailformats\#Html), [Mhtml](../../com.groupdocs.editor.formats/emailformats\#Mhtml).

--------------------

Learn more about emails format [here][].


[here]: https://docs.fileformat.com/email/
## Constructors

| Constructor | Description |
| --- | --- |
| [EmailFormats()](#EmailFormats--) |  |
## Fields

| Field | Description |
| --- | --- |
| [Tnef](#Tnef) | Transport Neutral Encapsulation Format (TNEF) is a Microsoft proprietary, for encapsulating email attachments based on Messaging Application Programming Interface (MAPI). |
| [Eml](#Eml) | EML file format represents email messages saved using Outlook and other relevant applications. |
| [Emlx](#Emlx) | The EMLX file format is implemented and developed by Apple. |
| [Msg](#Msg) | MSG is a file format used by Microsoft Outlook and Exchange to store email messages, contact, appointment, or other tasks. |
| [Html](#Html) | HTML formatted emails. |
| [Mhtml](#Mhtml) | MHTML, an initialism of "MIME encapsulation of aggregate HTML documents" |
| [Ics](#Ics) | The Internet Calendaring and Scheduling Core Object Specification (iCalendar) is an internet standard (RFC 2445) for exchanging and deploying the calendaring events and scheduling. |
| [Vcf](#Vcf) | VCF (Virtual Card Format) or vCard is a digital file format for storing contact information. |
| [Pst](#Pst) | Files with .pst extension represent Outlook Personal Storage Files (also called Personal Storage Table) that store variety of user information. |
| [Mbox](#Mbox) | MBox file format is a generic term that represents a container for collection of electronic mail messages. |
| [Oft](#Oft) | Files with .oft extension are template files that are created using Microsoft Outlook. |
| [Ost](#Ost) | Offline Storage Table (OST) file represents user\\u2019s mailbox data in offline mode on local machine upon registration with Exchange Server using Microsoft Outlook. |
| [All](#All) | Returns an internal class, that provides enumerable possibilities over all existing email formats |
## Methods

| Method | Description |
| --- | --- |
| [getName()](#getName--) | In implementing type should return full formal format name |
| [getExtension()](#getExtension--) | In implementing type should return format file extension (without leading dot character). |
| [getMime()](#getMime--) | In implementing type should return a MIME-code for the given format |
| [op_Equality(EmailFormats first, EmailFormats second)](#op-Equality-com.groupdocs.editor.formats.EmailFormats-com.groupdocs.editor.formats.EmailFormats-) | Checks two given Email instances on equality |
| [op_Inequality(EmailFormats first, EmailFormats second)](#op-Inequality-com.groupdocs.editor.formats.EmailFormats-com.groupdocs.editor.formats.EmailFormats-) | Checks two given Email instances on inequality |
| [equals(EmailFormats other)](#equals-com.groupdocs.editor.formats.EmailFormats-) | Determines whether this instance is equal to the other specified Email instance |
| [equals(IDocumentFormat other)](#equals-com.groupdocs.editor.formats.IDocumentFormat-) | Determines whether this instance is equal to the other specified IDocumentFormat instance |
| [equals(Object obj)](#equals-java.lang.Object-) | Determines whether this instance is equal to the other specified object, that is presumably of boxed Email |
| [hashCode()](#hashCode--) | Returns a hash-code, that is immutable for this instance |
| [fromExtension(String extension)](#fromExtension-java.lang.String-) | Returns instance of [EmailFormats](../../com.groupdocs.editor.formats/emailformats) structure, associated to specified filename extension, or throws an exception, if extension cannot be properly parsed |
| [toString()](#toString--) | Returns a format name of this format |
### EmailFormats() {#EmailFormats--}
```
public EmailFormats()
```


### Tnef {#Tnef}
```
public static final EmailFormats Tnef
```


Transport Neutral Encapsulation Format (TNEF) is a Microsoft proprietary, for encapsulating email attachments based on Messaging Application Programming Interface (MAPI). Learn more about this file format  [here][] .


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


MHTML, an initialism of "MIME encapsulation of aggregate HTML documents"

### Ics {#Ics}
```
public static final EmailFormats Ics
```


The Internet Calendaring and Scheduling Core Object Specification (iCalendar) is an internet standard (RFC 2445) for exchanging and deploying the calendaring events and scheduling. Learn more about this file format  [here][] .


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

### All {#All}
```
public static final EmailFormats.AllEnumerable All
```


Returns an internal class, that provides enumerable possibilities over all existing email formats

### getName() {#getName--}
```
public final String getName()
```


In implementing type should return full formal format name

**Returns:**
java.lang.String
### getExtension() {#getExtension--}
```
public final String getExtension()
```


In implementing type should return format file extension (without leading dot character).

**Returns:**
java.lang.String
### getMime() {#getMime--}
```
public final String getMime()
```


In implementing type should return a MIME-code for the given format

**Returns:**
java.lang.String
### op_Equality(EmailFormats first, EmailFormats second) {#op-Equality-com.groupdocs.editor.formats.EmailFormats-com.groupdocs.editor.formats.EmailFormats-}
```
public static boolean op_Equality(EmailFormats first, EmailFormats second)
```


Checks two given Email instances on equality

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| first | [EmailFormats](../../com.groupdocs.editor.formats/emailformats) | First Email instance to check |
| second | [EmailFormats](../../com.groupdocs.editor.formats/emailformats) | Second Email instance to check |

**Returns:**
boolean - True if are equal, false if are unequal
### op_Inequality(EmailFormats first, EmailFormats second) {#op-Inequality-com.groupdocs.editor.formats.EmailFormats-com.groupdocs.editor.formats.EmailFormats-}
```
public static boolean op_Inequality(EmailFormats first, EmailFormats second)
```


Checks two given Email instances on inequality

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| first | [EmailFormats](../../com.groupdocs.editor.formats/emailformats) | First Email instance to check |
| second | [EmailFormats](../../com.groupdocs.editor.formats/emailformats) | Second Email instance to check |

**Returns:**
boolean - True if are not equal, false if are equal
### equals(EmailFormats other) {#equals-com.groupdocs.editor.formats.EmailFormats-}
```
public final boolean equals(EmailFormats other)
```


Determines whether this instance is equal to the other specified Email instance

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| other | [EmailFormats](../../com.groupdocs.editor.formats/emailformats) | Other Email instance, that should be checked on equality with this |

**Returns:**
boolean - True if are equal, false if are unequal
### equals(IDocumentFormat other) {#equals-com.groupdocs.editor.formats.IDocumentFormat-}
```
public final boolean equals(IDocumentFormat other)
```


Determines whether this instance is equal to the other specified IDocumentFormat instance

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| other | [IDocumentFormat](../../com.groupdocs.editor.formats/idocumentformat) | Other IDocumentFormat instance. If it is not a Email, method will return 'false' |

**Returns:**
boolean - True if are equal, false if are unequal
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Determines whether this instance is equal to the other specified object, that is presumably of boxed Email

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | Other boxed Email instance |

**Returns:**
boolean - True if are equal, false if are unequal
### hashCode() {#hashCode--}
```
public int hashCode()
```


Returns a hash-code, that is immutable for this instance

**Returns:**
int - Signed 4-byte integer
### fromExtension(String extension) {#fromExtension-java.lang.String-}
```
public static EmailFormats fromExtension(String extension)
```


Returns instance of [EmailFormats](../../com.groupdocs.editor.formats/emailformats) structure, associated to specified filename extension, or throws an exception, if extension cannot be properly parsed

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| extension | java.lang.String | Filename extension of any supportable Email format, with or without leading dot character, case-independent. Cannot be NULL or empty, should be valid. |

**Returns:**
[EmailFormats](../../com.groupdocs.editor.formats/emailformats) - Instance of [EmailFormats](../../com.groupdocs.editor.formats/emailformats) structure on success or thrown exception on failure
### toString() {#toString--}
```
public String toString()
```


Returns a format name of this format

**Returns:**
java.lang.String - A String that represents this instance.
