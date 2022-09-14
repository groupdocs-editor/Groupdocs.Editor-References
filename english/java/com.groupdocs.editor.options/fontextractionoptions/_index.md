---
title: FontExtractionOptions
second_title: GroupDocs.Editor for Java API Reference
description:  Font extraction options control which fonts should be extracted and from
 where
type: docs
weight: 17
url: /java/com.groupdocs.editor.options/fontextractionoptions/
---
**Inheritance:**
java.lang.Object
```
public final class FontExtractionOptions
```

Font extraction options control which fonts should be extracted and from where
## Fields

| Field | Description |
| --- | --- |
| [NotExtract](#NotExtract) | Does not extract any font resource neither from document not from the system. |
| [ExtractAllEmbedded](#ExtractAllEmbedded) | Extracts all font resources, which are embedded into the input Word document, regardless of what they are: custom or system. |
| [ExtractEmbeddedWithoutSystem](#ExtractEmbeddedWithoutSystem) | Extracts only those embedded font resources, which are custom (not system) |
| [ExtractAll](#ExtractAll) | Tries to extract all fonts, which are used in the input WordProcessing document, including system fonts. |
## Methods

| Method | Description |
| --- | --- |
| [getFontExtractionOptions()](#getFontExtractionOptions--) |  |
### NotExtract {#NotExtract}
```
public static final byte NotExtract
```


Does not extract any font resource neither from document not from the system. Default value.

### ExtractAllEmbedded {#ExtractAllEmbedded}
```
public static final byte ExtractAllEmbedded
```


Extracts all font resources, which are embedded into the input Word document, regardless of what they are: custom or system.

--------------------

Converter finds and extracts all 100% font resources, which are embedded into the input WordProcessing document, but it doesn't determine whether they are system or custom; it doesn't touch Windows Registry or system folders at all.

### ExtractEmbeddedWithoutSystem {#ExtractEmbeddedWithoutSystem}
```
public static final byte ExtractEmbeddedWithoutSystem
```


Extracts only those embedded font resources, which are custom (not system)

--------------------

Converter finds and extracts all embedded font resources, and then tries to determine which of these fonts are system, and which - not. In order to achieve this, converter tries to obtain a list of all system fonts by using Windows Registry and system folders, and then compares this list with a set of embedded fonts. As a result, only subset of those embedded fonts, which were not found in system, will be returned.

### ExtractAll {#ExtractAll}
```
public static final byte ExtractAll
```


Tries to extract all fonts, which are used in the input WordProcessing document, including system fonts.

--------------------

Converter is analyzing an input WordProcessing document and finds all fonts, which are used there. If all of these fonts are embedded into the input document, converter extracts and returns them. Otherwise, if a collection of embedded fonts doesn't cover all used fonts in the document, or is empty, converter tries to extract these font resources from system, by using Windows Registry and system folders.

### getFontExtractionOptions() {#getFontExtractionOptions--}
```
public static byte[] getFontExtractionOptions()
```




**Returns:**
byte[]
