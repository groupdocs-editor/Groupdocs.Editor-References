---
title: WordProcessingEditOptions
second_title: GroupDocs.Editor for Java API Reference
description: Allows to specify custom options for editing documents of all supportable WordProcessing Words-compliant formats like DOCX RTF ODT etc.
type: docs
weight: 40
url: /java/com.groupdocs.editor.options/wordprocessingeditoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public class WordProcessingEditOptions implements IEditOptions
```

Allows to specify custom options for editing documents of all supportable WordProcessing (Words-compliant) formats like DOC(X), RTF, ODT etc.
## Constructors

| Constructor | Description |
| --- | --- |
| [WordProcessingEditOptions()](#WordProcessingEditOptions--) | Creates and returns a new instance of the WordProcessingEditOptions class, where all options are set to their default values |
| [WordProcessingEditOptions(boolean enablePagination)](#WordProcessingEditOptions-boolean-) | Creates and returns a new instance of the WordProcessingEditOptions class with specified pagination and default all other options |
## Methods

| Method | Description |
| --- | --- |
| [getEnablePagination()](#getEnablePagination--) | Allows to enable or disable pagination in the resultant HTML document. |
| [setEnablePagination(boolean value)](#setEnablePagination-boolean-) | Allows to enable or disable pagination in the resultant HTML document. |
| [getEnableLanguageInformation()](#getEnableLanguageInformation--) | Specifies whether language information is exported to the HTML markup in a form of 'lang' HTML attributes. |
| [setEnableLanguageInformation(boolean value)](#setEnableLanguageInformation-boolean-) | Specifies whether language information is exported to the HTML markup in a form of 'lang' HTML attributes. |
| [getExtractOnlyUsedFont()](#getExtractOnlyUsedFont--) | Gets or sets a value indicating whether extract only font resources that are used in the textual content of the document. |
| [setExtractOnlyUsedFont(boolean value)](#setExtractOnlyUsedFont-boolean-) | Gets or sets a value indicating whether extract only font resources that are used in the textual content of the document. |
| [getFontExtraction()](#getFontExtraction--) | Responsible for extracting font resources, which are used in the input WordProcessing document. |
| [setFontExtraction(byte value)](#setFontExtraction-byte-) | Responsible for extracting font resources, which are used in the input WordProcessing document. |
| [getInputControlsClassName()](#getInputControlsClassName--) | Allows to specify a class name, which will be placed to the 'class' attributes in every HTML element, that represents some field in the input WordProcessing document. |
| [setInputControlsClassName(String value)](#setInputControlsClassName-java.lang.String-) | Allows to specify a class name, which will be placed to the 'class' attributes in every HTML element, that represents some field in the input WordProcessing document. |
### WordProcessingEditOptions() {#WordProcessingEditOptions--}
```
public WordProcessingEditOptions()
```


Creates and returns a new instance of the WordProcessingEditOptions class, where all options are set to their default values

### WordProcessingEditOptions(boolean enablePagination) {#WordProcessingEditOptions-boolean-}
```
public WordProcessingEditOptions(boolean enablePagination)
```


Creates and returns a new instance of the WordProcessingEditOptions class with specified pagination and default all other options

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| enablePagination | boolean | Pagination flag, that enables HTML output, adjusted for paged mode |

### getEnablePagination() {#getEnablePagination--}
```
public final boolean getEnablePagination()
```


Allows to enable or disable pagination in the resultant HTML document. By default is disabled (false).

**Returns:**
boolean
### setEnablePagination(boolean value) {#setEnablePagination-boolean-}
```
public final void setEnablePagination(boolean value)
```


Allows to enable or disable pagination in the resultant HTML document. By default is disabled (false).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getEnableLanguageInformation() {#getEnableLanguageInformation--}
```
public final boolean getEnableLanguageInformation()
```


Specifies whether language information is exported to the HTML markup in a form of 'lang' HTML attributes. This option may be useful for roundtrip conversion of the multi-language documents. By default it is disabled (false).

**Returns:**
boolean
### setEnableLanguageInformation(boolean value) {#setEnableLanguageInformation-boolean-}
```
public final void setEnableLanguageInformation(boolean value)
```


Specifies whether language information is exported to the HTML markup in a form of 'lang' HTML attributes. This option may be useful for roundtrip conversion of the multi-language documents. By default it is disabled (false).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getExtractOnlyUsedFont() {#getExtractOnlyUsedFont--}
```
public final boolean getExtractOnlyUsedFont()
```


Gets or sets a value indicating whether extract only font resources that are used in the textual content of the document.

Value:  true  if it is required to extract only those font resources, which are used in text content of the document; otherwise,  false . Default value is  false .

--------------------

Not all fonts, used in the WordProcessing document, are 100% used directly (applied to some text). There may be a situation, when font is referenced in the document and even may be embedded, but is not applied to any piece of text. For example, some font may be attached to some style, but this style is not applied to any part of text. This option controls how to process such cases.

**Returns:**
boolean
### setExtractOnlyUsedFont(boolean value) {#setExtractOnlyUsedFont-boolean-}
```
public final void setExtractOnlyUsedFont(boolean value)
```


Gets or sets a value indicating whether extract only font resources that are used in the textual content of the document.

Value:  true  if it is required to extract only those font resources, which are used in text content of the document; otherwise,  false . Default value is  false .

--------------------

Not all fonts, used in the WordProcessing document, are 100% used directly (applied to some text). There may be a situation, when font is referenced in the document and even may be embedded, but is not applied to any piece of text. For example, some font may be attached to some style, but this style is not applied to any part of text. This option controls how to process such cases.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getFontExtraction() {#getFontExtraction--}
```
public final byte getFontExtraction()
```


Responsible for extracting font resources, which are used in the input WordProcessing document. By default doesn't extract any fonts (NotExtract).

**Returns:**
byte
### setFontExtraction(byte value) {#setFontExtraction-byte-}
```
public final void setFontExtraction(byte value)
```


Responsible for extracting font resources, which are used in the input WordProcessing document. By default doesn't extract any fonts (NotExtract).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getInputControlsClassName() {#getInputControlsClassName--}
```
public final String getInputControlsClassName()
```


Allows to specify a class name, which will be placed to the 'class' attributes in every HTML element, that represents some field in the input WordProcessing document. By default is NULL - 'class' attributes are not applied.

--------------------

Almost all formats from WordProcessing format family contain fields \\u2014 specific document entities, that allow to obtain input data from users. There are a wide variety of fields: text-boxes, checkboxes, combo-boxes, drop down lists, buttons, date/time pickers, etc. All of them are translated into the most appropriate HTML structures and elements, with preserving the entered user data, if they are present in the input document. In specific use-cases it is required only to gather entered data on a client-side instead of editing the entire document content. For such case it is required to identify input controls in some way for fetching them with their data on client-side. This property allows to specify a class name, that will be applied for every input control in HTML markup, so client code will be able to traverse over HTML document structure and gather data.

**Returns:**
java.lang.String
### setInputControlsClassName(String value) {#setInputControlsClassName-java.lang.String-}
```
public final void setInputControlsClassName(String value)
```


Allows to specify a class name, which will be placed to the 'class' attributes in every HTML element, that represents some field in the input WordProcessing document. By default is NULL - 'class' attributes are not applied.

--------------------

Almost all formats from WordProcessing format family contain fields \\u2014 specific document entities, that allow to obtain input data from users. There are a wide variety of fields: text-boxes, checkboxes, combo-boxes, drop down lists, buttons, date/time pickers, etc. All of them are translated into the most appropriate HTML structures and elements, with preserving the entered user data, if they are present in the input document. In specific use-cases it is required only to gather entered data on a client-side instead of editing the entire document content. For such case it is required to identify input controls in some way for fetching them with their data on client-side. This property allows to specify a class name, that will be applied for every input control in HTML markup, so client code will be able to traverse over HTML document structure and gather data.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

