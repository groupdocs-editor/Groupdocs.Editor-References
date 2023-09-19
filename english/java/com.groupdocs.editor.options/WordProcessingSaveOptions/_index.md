---
title: WordProcessingSaveOptions
second_title: GroupDocs.Editor for Java API Reference
description: Allows to specify custom options for generating and saving WordProcessing-compliant documents after they were edited
type: docs
weight: 43
url: /java/com.groupdocs.editor.options/wordprocessingsaveoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ISaveOptions](../../com.groupdocs.editor.options/isaveoptions)
```
public final class WordProcessingSaveOptions implements ISaveOptions
```

Allows to specify custom options for generating and saving WordProcessing-compliant documents after they were edited

--------------------

WordProcessingSaveOptions is applied in situations when there is an instance of EditableDocument class, that contains an edited document content, and it is required to save this content to the new document of WordProcessing format.
## Constructors

| Constructor | Description |
| --- | --- |
| [WordProcessingSaveOptions(WordProcessingFormats outputFormat)](#WordProcessingSaveOptions-com.groupdocs.editor.formats.WordProcessingFormats-) | Creates a new instance of WordProcessingSaveOptions with specified mandatory WordProcessing output format, while all other parameters are default |
## Methods

| Method | Description |
| --- | --- |
| [getEnablePagination()](#getEnablePagination--) | Allows to enable or disable pagination which will be used for saving the document. |
| [setEnablePagination(boolean value)](#setEnablePagination-boolean-) | Allows to enable or disable pagination which will be used for saving the document. |
| [getPassword()](#getPassword--) | Allows to specify, modify, obtain, or remove a password, which will be used to encode the generated WordProcessing document. |
| [setPassword(String value)](#setPassword-java.lang.String-) | Allows to specify, modify, obtain, or remove a password, which will be used to encode the generated WordProcessing document. |
| [getOutputFormat()](#getOutputFormat--) | Allows to specify a WordProcessing format, which will be used for saving the document |
| [setOutputFormat(WordProcessingFormats value)](#setOutputFormat-com.groupdocs.editor.formats.WordProcessingFormats-) | Allows to specify a WordProcessing format, which will be used for saving the document |
| [getLocale()](#getLocale--) | Allows to set override default locale (language) for the WordProcessing document, which will be applied during its creation. |
| [setLocale(Locale value)](#setLocale-java.util.Locale-) | Allows to set override default locale (language) for the WordProcessing document, which will be applied during its creation. |
| [getLocaleBi()](#getLocaleBi--) | Allows to set override locale (language) for the WordProcessing document for the RTL (right-to-left) text, which will be applied during its creation. |
| [setLocaleBi(Locale value)](#setLocaleBi-java.util.Locale-) | Allows to set override locale (language) for the WordProcessing document for the RTL (right-to-left) text, which will be applied during its creation. |
| [getLocaleFarEast()](#getLocaleFarEast--) | Allows to override the locale (language) for the WordProcessing document for the East-Asian text, which will be applied during its creation. |
| [setLocaleFarEast(Locale value)](#setLocaleFarEast-java.util.Locale-) | Allows to override the locale (language) for the WordProcessing document for the East-Asian text, which will be applied during its creation. |
| [getOptimizeMemoryUsage()](#getOptimizeMemoryUsage--) | Enables memory optimization mechanisms during document generation from HTML, which degrades performance in as a cost of decreasing memory usage. |
| [setOptimizeMemoryUsage(boolean value)](#setOptimizeMemoryUsage-boolean-) | Enables memory optimization mechanisms during document generation from HTML, which degrades performance in as a cost of decreasing memory usage. |
| [getProtection()](#getProtection--) | Allows to control and apply the document protection options for the WordProcessing document of any format, which supports document protection. |
| [setProtection(WordProcessingProtection value)](#setProtection-com.groupdocs.editor.options.WordProcessingProtection-) | Allows to control and apply the document protection options for the WordProcessing document of any format, which supports document protection. |
| [getFontEmbedding()](#getFontEmbedding--) | Responsible for embedding font resources into output WordProcessing document. |
| [setFontEmbedding(byte value)](#setFontEmbedding-byte-) | Responsible for embedding font resources into output WordProcessing document. |
| [deepClone()](#deepClone--) | Creates and returns a full copy of this instance of WordProcessingSaveOptions class |
### WordProcessingSaveOptions(WordProcessingFormats outputFormat) {#WordProcessingSaveOptions-com.groupdocs.editor.formats.WordProcessingFormats-}
```
public WordProcessingSaveOptions(WordProcessingFormats outputFormat)
```


Creates a new instance of WordProcessingSaveOptions with specified mandatory WordProcessing output format, while all other parameters are default

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| outputFormat | [WordProcessingFormats](../../com.groupdocs.editor.formats/wordprocessingformats) | Mandatory output format, in which the WordProcessing document should be saved |

### getEnablePagination() {#getEnablePagination--}
```
public final boolean getEnablePagination()
```


Allows to enable or disable pagination which will be used for saving the document. If the original document was opened and edited in pagination mode, this option also should be enabled. By default is disabled.

**Returns:**
boolean - 
### setEnablePagination(boolean value) {#setEnablePagination-boolean-}
```
public final void setEnablePagination(boolean value)
```


Allows to enable or disable pagination which will be used for saving the document. If the original document was opened and edited in pagination mode, this option also should be enabled. By default is disabled.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
```


Allows to specify, modify, obtain, or remove a password, which will be used to encode the generated WordProcessing document. Specify NULL or empty string for removing (cleaning) the password.

**Returns:**
java.lang.String - 
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Allows to specify, modify, obtain, or remove a password, which will be used to encode the generated WordProcessing document. Specify NULL or empty string for removing (cleaning) the password.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getOutputFormat() {#getOutputFormat--}
```
public final WordProcessingFormats getOutputFormat()
```


Allows to specify a WordProcessing format, which will be used for saving the document

**Returns:**
[WordProcessingFormats](../../com.groupdocs.editor.formats/wordprocessingformats) - 
### setOutputFormat(WordProcessingFormats value) {#setOutputFormat-com.groupdocs.editor.formats.WordProcessingFormats-}
```
public final void setOutputFormat(WordProcessingFormats value)
```


Allows to specify a WordProcessing format, which will be used for saving the document

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [WordProcessingFormats](../../com.groupdocs.editor.formats/wordprocessingformats) |  |

### getLocale() {#getLocale--}
```
public final Locale getLocale()
```


Allows to set override default locale (language) for the WordProcessing document, which will be applied during its creation. When is not specified (default value), MS Word (or other program) will detect (or choose) the document locale according to its own settings or other factors.

--------------------

This option forcibly applies the specified locale to overall text in the document. Do not use it, if document contains different parts of text, which are written on different languages.

**Returns:**
java.util.Locale - 
### setLocale(Locale value) {#setLocale-java.util.Locale-}
```
public final void setLocale(Locale value)
```


Allows to set override default locale (language) for the WordProcessing document, which will be applied during its creation. When is not specified (default value), MS Word (or other program) will detect (or choose) the document locale according to its own settings or other factors.

--------------------

This option forcibly applies the specified locale to overall text in the document. Do not use it, if document contains different parts of text, which are written on different languages.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Locale |  |

### getLocaleBi() {#getLocaleBi--}
```
public final Locale getLocaleBi()
```


Allows to set override locale (language) for the WordProcessing document for the RTL (right-to-left) text, which will be applied during its creation. When is not specified (default value), MS Word (or other program) will detect (or choose) the document RTL locale according to its own settings or other factors.

--------------------

This option forcibly applies the specified locale to overall RTL text in the document. Do not use it, if document contains different parts of text, which are written on different languages.

**Returns:**
java.util.Locale - 
### setLocaleBi(Locale value) {#setLocaleBi-java.util.Locale-}
```
public final void setLocaleBi(Locale value)
```


Allows to set override locale (language) for the WordProcessing document for the RTL (right-to-left) text, which will be applied during its creation. When is not specified (default value), MS Word (or other program) will detect (or choose) the document RTL locale according to its own settings or other factors.

--------------------

This option forcibly applies the specified locale to overall RTL text in the document. Do not use it, if document contains different parts of text, which are written on different languages.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Locale |  |

### getLocaleFarEast() {#getLocaleFarEast--}
```
public final Locale getLocaleFarEast()
```


Allows to override the locale (language) for the WordProcessing document for the East-Asian text, which will be applied during its creation. When is not specified (default value), MS Word (or other program) will detect (or choose) the document East-Asian locale according to its own settings or other factors.

--------------------

This option forcibly applies the specified locale to overall East-Asian text in the document. Do not use it, if document contains different parts of text, which are written on different languages.

**Returns:**
java.util.Locale - 
### setLocaleFarEast(Locale value) {#setLocaleFarEast-java.util.Locale-}
```
public final void setLocaleFarEast(Locale value)
```


Allows to override the locale (language) for the WordProcessing document for the East-Asian text, which will be applied during its creation. When is not specified (default value), MS Word (or other program) will detect (or choose) the document East-Asian locale according to its own settings or other factors.

--------------------

This option forcibly applies the specified locale to overall East-Asian text in the document. Do not use it, if document contains different parts of text, which are written on different languages.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Locale |  |

### getOptimizeMemoryUsage() {#getOptimizeMemoryUsage--}
```
public final boolean getOptimizeMemoryUsage()
```


Enables memory optimization mechanisms during document generation from HTML, which degrades performance in as a cost of decreasing memory usage. Setting this option to true can significantly decrease memory consumption while generating large documents at the cost of slower saving time. Default is false (memory optimization is disabled for the sake of better performance).

**Returns:**
boolean - 
### setOptimizeMemoryUsage(boolean value) {#setOptimizeMemoryUsage-boolean-}
```
public final void setOptimizeMemoryUsage(boolean value)
```


Enables memory optimization mechanisms during document generation from HTML, which degrades performance in as a cost of decreasing memory usage. Setting this option to true can significantly decrease memory consumption while generating large documents at the cost of slower saving time. Default is false (memory optimization is disabled for the sake of better performance).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getProtection() {#getProtection--}
```
public final WordProcessingProtection getProtection()
```


Allows to control and apply the document protection options for the WordProcessing document of any format, which supports document protection. By default is NULL - document protection will not be used.

**Returns:**
[WordProcessingProtection](../../com.groupdocs.editor.options/wordprocessingprotection) - 
### setProtection(WordProcessingProtection value) {#setProtection-com.groupdocs.editor.options.WordProcessingProtection-}
```
public final void setProtection(WordProcessingProtection value)
```


Allows to control and apply the document protection options for the WordProcessing document of any format, which supports document protection. By default is NULL - document protection will not be used.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [WordProcessingProtection](../../com.groupdocs.editor.options/wordprocessingprotection) |  |

### getFontEmbedding() {#getFontEmbedding--}
```
public final byte getFontEmbedding()
```


Responsible for embedding font resources into output WordProcessing document. By default doesn't embed any fonts (NotEmbed).

**Returns:**
byte - 
### setFontEmbedding(byte value) {#setFontEmbedding-byte-}
```
public final void setFontEmbedding(byte value)
```


Responsible for embedding font resources into output WordProcessing document. By default doesn't embed any fonts (NotEmbed).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### deepClone() {#deepClone--}
```
public final WordProcessingSaveOptions deepClone()
```


Creates and returns a full copy of this instance of WordProcessingSaveOptions class

**Returns:**
[WordProcessingSaveOptions](../../com.groupdocs.editor.options/wordprocessingsaveoptions) - New WordProcessingSaveOptions instance
