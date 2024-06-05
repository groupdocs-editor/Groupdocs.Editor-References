---
title: MhtmlSaveOptions
second_title: GroupDocs.Editor for Node.js via Java API Reference
description: Allows to specify custom options for generating and saving the MHTML MIME encapsulation of aggregate HTML documents documents
type: docs
weight: 26
url: /nodejs-java/com.groupdocs.editor.options/mhtmlsaveoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ISaveOptions](../../com.groupdocs.editor.options/isaveoptions)
```
public final class MhtmlSaveOptions implements ISaveOptions
```

Allows to specify custom options for generating and saving the MHTML (MIME encapsulation of aggregate HTML documents) documents
## Constructors

| Constructor | Description |
| --- | --- |
| [MhtmlSaveOptions()](#MhtmlSaveOptions--) |  |
## Methods

| Method | Description |
| --- | --- |
| [getExportCidUrls()](#getExportCidUrls--) | Specifies whether to use CID (Content-ID) URLs to reference resources (images, fonts, CSS) included in MHTML documents. |
| [setExportCidUrls(boolean value)](#setExportCidUrls-boolean-) | Specifies whether to use CID (Content-ID) URLs to reference resources (images, fonts, CSS) included in MHTML documents. |
| [getExportDocumentProperties()](#getExportDocumentProperties--) | Specifies whether to export built-in and custom document properties to MHTML. |
| [setExportDocumentProperties(boolean value)](#setExportDocumentProperties-boolean-) | Specifies whether to export built-in and custom document properties to MHTML. |
| [getExportLanguageInformation()](#getExportLanguageInformation--) | Specifies whether language information is exported to MHTML. |
| [setExportLanguageInformation(boolean value)](#setExportLanguageInformation-boolean-) | Specifies whether language information is exported to MHTML. |
### MhtmlSaveOptions() {#MhtmlSaveOptions--}
```
public MhtmlSaveOptions()
```


### getExportCidUrls() {#getExportCidUrls--}
```
public final boolean getExportCidUrls()
```


Specifies whether to use CID (Content-ID) URLs to reference resources (images, fonts, CSS) included in MHTML documents. Default value is  false .

--------------------

By default, resources in MHTML documents are referenced by file name (for example, "image.png"), which are matched against "Content-Location" headers of MIME parts. This option enables an alternative method, where references to resource files are written as CID (Content-ID) URLs (for example, "cid:image.png") and are matched against "Content-ID" headers.

In theory, there should be no difference between the two referencing methods and either of them should work fine in any browser or mail agent. In practice, however, some agents fail to fetch resources by file name. If your browser or mail agent refuses to load resources included in an MTHML document (doesn't show images or doesn't load CSS styles), try exporting the document with CID URLs.

**Returns:**
boolean
### setExportCidUrls(boolean value) {#setExportCidUrls-boolean-}
```
public final void setExportCidUrls(boolean value)
```


Specifies whether to use CID (Content-ID) URLs to reference resources (images, fonts, CSS) included in MHTML documents. Default value is  false .

--------------------

By default, resources in MHTML documents are referenced by file name (for example, "image.png"), which are matched against "Content-Location" headers of MIME parts. This option enables an alternative method, where references to resource files are written as CID (Content-ID) URLs (for example, "cid:image.png") and are matched against "Content-ID" headers.

In theory, there should be no difference between the two referencing methods and either of them should work fine in any browser or mail agent. In practice, however, some agents fail to fetch resources by file name. If your browser or mail agent refuses to load resources included in an MTHML document (doesn't show images or doesn't load CSS styles), try exporting the document with CID URLs.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getExportDocumentProperties() {#getExportDocumentProperties--}
```
public final boolean getExportDocumentProperties()
```


Specifies whether to export built-in and custom document properties to MHTML. Default value is  false .

**Returns:**
boolean
### setExportDocumentProperties(boolean value) {#setExportDocumentProperties-boolean-}
```
public final void setExportDocumentProperties(boolean value)
```


Specifies whether to export built-in and custom document properties to MHTML. Default value is  false .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getExportLanguageInformation() {#getExportLanguageInformation--}
```
public final boolean getExportLanguageInformation()
```


Specifies whether language information is exported to MHTML. Default value is  false .

--------------------

When this property is set to  true , the GroupDocs.Editor emits the  lang  HTML-attribute on the document elements that specify language. This can be needed to preserve language related semantics.

**Returns:**
boolean
### setExportLanguageInformation(boolean value) {#setExportLanguageInformation-boolean-}
```
public final void setExportLanguageInformation(boolean value)
```


Specifies whether language information is exported to MHTML. Default value is  false .

--------------------

When this property is set to  true , the GroupDocs.Editor emits the  lang  HTML-attribute on the document elements that specify language. This can be needed to preserve language related semantics.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

