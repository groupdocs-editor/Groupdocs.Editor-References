---
title: PresentationFormats
second_title: GroupDocs.Editor for Node.js via Java API Reference
description: Encapsulates all Presentation formats.
type: docs
weight: 13
url: /nodejs-java/com.groupdocs.editor.formats/presentationformats/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.formats.IDocumentFormat](../../com.groupdocs.editor.formats/idocumentformat)
```
public class PresentationFormats implements IDocumentFormat
```

Encapsulates all Presentation formats. Includes the following formats: [Odp](../../com.groupdocs.editor.formats/presentationformats\#Odp), [Otp](../../com.groupdocs.editor.formats/presentationformats\#Otp), [Pot](../../com.groupdocs.editor.formats/presentationformats\#Pot), [Potm](../../com.groupdocs.editor.formats/presentationformats\#Potm), [Potx](../../com.groupdocs.editor.formats/presentationformats\#Potx), [Pps](../../com.groupdocs.editor.formats/presentationformats\#Pps), [Ppsm](../../com.groupdocs.editor.formats/presentationformats\#Ppsm), [Ppsx](../../com.groupdocs.editor.formats/presentationformats\#Ppsx), [Ppt](../../com.groupdocs.editor.formats/presentationformats\#Ppt), [Ppt95](../../com.groupdocs.editor.formats/presentationformats\#Ppt95), [Pptm](../../com.groupdocs.editor.formats/presentationformats\#Pptm), [Pptx](../../com.groupdocs.editor.formats/presentationformats\#Pptx). Learn more about Presentation formats [here][].


[here]: https://wiki.fileformat.com/presentation
## Constructors

| Constructor | Description |
| --- | --- |
| [PresentationFormats()](#PresentationFormats--) |  |
## Fields

| Field | Description |
| --- | --- |
| [Ppt95](#Ppt95) | Microsoft PowerPoint 95 Presentation (PPT) |
| [Ppt](#Ppt) | PowerPoint Presentation (.ppt) represents PowerPoint file that consists of a collection of slides for displaying as SlideShow. |
| [Pptx](#Pptx) | PowerPoint Open XML Presentation (.pptx) is a presentation file created with popular Microsoft PowerPoint application. |
| [Pptm](#Pptm) | Microsoft Office Open XML PresentationML Macro-Enabled Document (PPTM) files that are created with Microsoft PowerPoint 2007 or higher versions. |
| [Pps](#Pps) | Microsoft PowerPoint 97-2003 SlideShow (PPS) files are created using Microsoft PowerPoint for Slide Show purpose. |
| [Ppsx](#Ppsx) | Microsoft Office Open XML PresentationML Macro-Free SlideShow (PPSX) file are created using Microsoft PowerPoint 2007 and above for Slide Show purpose. |
| [Ppsm](#Ppsm) | Microsoft Office Open XML PresentationML Macro-Enabled SlideShow (PPSM) files are created with Microsoft PowerPoint 2007 or higher. |
| [Pot](#Pot) | Microsoft PowerPoint 97-2003 Presentation Template (POT) file represents Microsoft PowerPoint template files created by PowerPoint 97-2003 versions. |
| [Potx](#Potx) | Microsoft Office Open XML PresentationML Macro-Free Template (POTX) file represents Microsoft PowerPoint template presentations that are created with Microsoft PowerPoint 2007 and above. |
| [Potm](#Potm) | Microsoft Office Open XML PresentationML Macro-Enabled Template (POTM) are files with support for Macros. |
| [Odp](#Odp) | OpenDocument Presentation (ODP) file represents presentation file format used by OpenOffice.org in the OASISOpen standard. |
| [Otp](#Otp) | OpenDocument Presentation template (OTP) file represents presentation template files created by applications in OASIS OpenDocument standard format. |
| [All](#All) | Returns an internal class, that provides enumerable possibilities over all existing Presentation formats |
## Methods

| Method | Description |
| --- | --- |
| [getName()](#getName--) | Returns a formal full name of this Presentation format |
| [getExtension()](#getExtension--) | Returns an extension (without leading dot character) of this Presentation format in lower case |
| [getMime()](#getMime--) | Returns a MIME code for this format |
| [op_Equality(PresentationFormats first, PresentationFormats second)](#op-Equality-com.groupdocs.editor.formats.PresentationFormats-com.groupdocs.editor.formats.PresentationFormats-) | Checks two given PresentationFormats instances on equality |
| [op_Inequality(PresentationFormats first, PresentationFormats second)](#op-Inequality-com.groupdocs.editor.formats.PresentationFormats-com.groupdocs.editor.formats.PresentationFormats-) | Checks two given PresentationFormats instances on inequality |
| [equals(PresentationFormats other)](#equals-com.groupdocs.editor.formats.PresentationFormats-) | Determines whether this instance is equal to the other specified PresentationFormats instance |
| [equals(IDocumentFormat other)](#equals-com.groupdocs.editor.formats.IDocumentFormat-) | Determines whether this instance is equal to the other specified IDocumentFormat instance |
| [equals(Object obj)](#equals-java.lang.Object-) | Determines whether this instance is equal to the other specified object, that is presumably of boxed PresentationFormats |
| [hashCode()](#hashCode--) | Returns a hash-code, that is immutable for this instance |
| [iterator()](#iterator--) | Returns an enumerator for all supportable PresentationFormats formats |
| [fromExtension(String extension)](#fromExtension-java.lang.String-) | Returns instance of [PresentationFormats](../../com.groupdocs.editor.formats/presentationformats) structure, associated to specified filename extension, or throws an exception, if extension cannot be properly parsed |
| [toString()](#toString--) | Returns the name of this particular format, same as 'Name' property |
### PresentationFormats() {#PresentationFormats--}
```
public PresentationFormats()
```


### Ppt95 {#Ppt95}
```
public static final PresentationFormats Ppt95
```


Microsoft PowerPoint 95 Presentation (PPT)

### Ppt {#Ppt}
```
public static final PresentationFormats Ppt
```


PowerPoint Presentation (.ppt) represents PowerPoint file that consists of a collection of slides for displaying as SlideShow. It specifies the Binary File Format used by Microsoft PowerPoint 97-2003. Learn more about this file format  [here][] .


[here]: https://wiki.fileformat.com/presentation/ppt

### Pptx {#Pptx}
```
public static final PresentationFormats Pptx
```


PowerPoint Open XML Presentation (.pptx) is a presentation file created with popular Microsoft PowerPoint application. Unlike the previous version of presentation file format PPT which was binary, the PPTX format is based on the Microsoft PowerPoint open XML presentation file format. Learn more about this file format  [here][] .


[here]: https://wiki.fileformat.com/presentation/pptx

### Pptm {#Pptm}
```
public static final PresentationFormats Pptm
```


Microsoft Office Open XML PresentationML Macro-Enabled Document (PPTM) files that are created with Microsoft PowerPoint 2007 or higher versions. They are similar to PPTX files with the difference that the lateral can't execute macros though they can contain macros. Learn more about this file format  [here][] .


[here]: https://wiki.fileformat.com/presentation/pptm

### Pps {#Pps}
```
public static final PresentationFormats Pps
```


Microsoft PowerPoint 97-2003 SlideShow (PPS) files are created using Microsoft PowerPoint for Slide Show purpose. PPS file reading and creation is supported by Microsoft PowerPoint 97-2003. Learn more about this file format  [here][] .


[here]: https://wiki.fileformat.com/presentation/pps

### Ppsx {#Ppsx}
```
public static final PresentationFormats Ppsx
```


Microsoft Office Open XML PresentationML Macro-Free SlideShow (PPSX) file are created using Microsoft PowerPoint 2007 and above for Slide Show purpose. Learn more about this file format  [here][] .


[here]: https://wiki.fileformat.com/presentation/ppsx

### Ppsm {#Ppsm}
```
public static final PresentationFormats Ppsm
```


Microsoft Office Open XML PresentationML Macro-Enabled SlideShow (PPSM) files are created with Microsoft PowerPoint 2007 or higher. Learn more about this file format  [here][] .


[here]: https://wiki.fileformat.com/presentation/ppsm

### Pot {#Pot}
```
public static final PresentationFormats Pot
```


Microsoft PowerPoint 97-2003 Presentation Template (POT) file represents Microsoft PowerPoint template files created by PowerPoint 97-2003 versions. Learn more about this file format  [here][] .


[here]: https://wiki.fileformat.com/presentation/pot

### Potx {#Potx}
```
public static final PresentationFormats Potx
```


Microsoft Office Open XML PresentationML Macro-Free Template (POTX) file represents Microsoft PowerPoint template presentations that are created with Microsoft PowerPoint 2007 and above. Learn more about this file format  [here][] .


[here]: https://wiki.fileformat.com/presentation/potx

### Potm {#Potm}
```
public static final PresentationFormats Potm
```


Microsoft Office Open XML PresentationML Macro-Enabled Template (POTM) are files with support for Macros. POTM files are created with PowerPoint 2007 or above and contains default settings that can be used to create further presentation files. Learn more about this file format  [here][] .


[here]: https://wiki.fileformat.com/presentation/potm

### Odp {#Odp}
```
public static final PresentationFormats Odp
```


OpenDocument Presentation (ODP) file represents presentation file format used by OpenOffice.org in the OASISOpen standard. Learn more about this file format  [here][] .


[here]: https://wiki.fileformat.com/presentation/odp

### Otp {#Otp}
```
public static final PresentationFormats Otp
```


OpenDocument Presentation template (OTP) file represents presentation template files created by applications in OASIS OpenDocument standard format. Learn more about this file format  [here][] .


[here]: https://wiki.fileformat.com/presentation/otp

### All {#All}
```
public static final Iterator<PresentationFormats> All
```


Returns an internal class, that provides enumerable possibilities over all existing Presentation formats

### getName() {#getName--}
```
public final String getName()
```


Returns a formal full name of this Presentation format

**Returns:**
java.lang.String
### getExtension() {#getExtension--}
```
public final String getExtension()
```


Returns an extension (without leading dot character) of this Presentation format in lower case

**Returns:**
java.lang.String
### getMime() {#getMime--}
```
public final String getMime()
```


Returns a MIME code for this format

**Returns:**
java.lang.String
### op_Equality(PresentationFormats first, PresentationFormats second) {#op-Equality-com.groupdocs.editor.formats.PresentationFormats-com.groupdocs.editor.formats.PresentationFormats-}
```
public static boolean op_Equality(PresentationFormats first, PresentationFormats second)
```


Checks two given PresentationFormats instances on equality

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| first | [PresentationFormats](../../com.groupdocs.editor.formats/presentationformats) | First PresentationFormats instance to check |
| second | [PresentationFormats](../../com.groupdocs.editor.formats/presentationformats) | Second PresentationFormats instance to check |

**Returns:**
boolean - True if are equal, false if are unequal
### op_Inequality(PresentationFormats first, PresentationFormats second) {#op-Inequality-com.groupdocs.editor.formats.PresentationFormats-com.groupdocs.editor.formats.PresentationFormats-}
```
public static boolean op_Inequality(PresentationFormats first, PresentationFormats second)
```


Checks two given PresentationFormats instances on inequality

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| first | [PresentationFormats](../../com.groupdocs.editor.formats/presentationformats) | First PresentationFormats instance to check |
| second | [PresentationFormats](../../com.groupdocs.editor.formats/presentationformats) | Second PresentationFormats instance to check |

**Returns:**
boolean - True if are not equal, false if are equal
### equals(PresentationFormats other) {#equals-com.groupdocs.editor.formats.PresentationFormats-}
```
public final boolean equals(PresentationFormats other)
```


Determines whether this instance is equal to the other specified PresentationFormats instance

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| other | [PresentationFormats](../../com.groupdocs.editor.formats/presentationformats) | Other PresentationFormats instance, that should be checked on equality with this |

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
| other | [IDocumentFormat](../../com.groupdocs.editor.formats/idocumentformat) | Other IDocumentFormat instance. If it is not a PresentationFormats, method will return 'false' |

**Returns:**
boolean - True if are equal, false if are unequal
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Determines whether this instance is equal to the other specified object, that is presumably of boxed PresentationFormats

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | Other boxed PresentationFormats instance |

**Returns:**
boolean - True if are equal, false if are unequal
### hashCode() {#hashCode--}
```
public int hashCode()
```


Returns a hash-code, that is immutable for this instance

**Returns:**
int - Signed 4-byte integer
### iterator() {#iterator--}
```
public final Iterator<PresentationFormats> iterator()
```


Returns an enumerator for all supportable PresentationFormats formats

**Returns:**
java.util.Iterator<com.groupdocs.editor.formats.PresentationFormats> - Instance of internal class, that implements IEnumerator
### fromExtension(String extension) {#fromExtension-java.lang.String-}
```
public static PresentationFormats fromExtension(String extension)
```


Returns instance of [PresentationFormats](../../com.groupdocs.editor.formats/presentationformats) structure, associated to specified filename extension, or throws an exception, if extension cannot be properly parsed

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| extension | java.lang.String | Filename extension solely or filename with proper extension of any supportable Presentation format, with or without leading dot character, case-independent. Cannot be NULL or empty, should be valid. |

**Returns:**
[PresentationFormats](../../com.groupdocs.editor.formats/presentationformats) - Instance of [PresentationFormats](../../com.groupdocs.editor.formats/presentationformats) structure on success or thrown exception on failure
### toString() {#toString--}
```
public String toString()
```


Returns the name of this particular format, same as 'Name' property

**Returns:**
java.lang.String - A String that represents this instance
