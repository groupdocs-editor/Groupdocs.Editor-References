---
title: FontEmbeddingOptions
second_title: GroupDocs.Editor for Java API Reference
description: Font embedding options control which font resources should be embedded into the output WordProcessing document
type: docs
weight: 16
url: /java/com.groupdocs.editor.options/fontembeddingoptions/
---
**Inheritance:**
java.lang.Object
```
public final class FontEmbeddingOptions
```

Font embedding options control which font resources should be embedded into the output WordProcessing document

--------------------

Font embedding options are applied during document saving (from intermediate EditableDocument into output WordProcessing format), this enum is included as a property in the WordProcessingSaveOptions, from where it should be used
## Fields

| Field | Description |
| --- | --- |
| [NotEmbed](#NotEmbed) | Do not embed any font resource neither from EditableDocument nor from the system. |
| [EmbedAll](#EmbedAll) | Analize document content from input EditableDocument, find all used fonts and embed them into output WordProcessing document. |
| [EmbedWithoutSystem](#EmbedWithoutSystem) | Exact to [EmbedAll](../../com.groupdocs.editor.options/fontembeddingoptions\#EmbedAll), but exclude those fonts, which are treated by OS as system fonts |
## Methods

| Method | Description |
| --- | --- |
| [getFontEmbeddingOptions()](#getFontEmbeddingOptions--) |  |
### NotEmbed {#NotEmbed}
```
public static final byte NotEmbed
```


Do not embed any font resource neither from EditableDocument nor from the system. Default value.

### EmbedAll {#EmbedAll}
```
public static final byte EmbedAll
```


Analize document content from input EditableDocument, find all used fonts and embed them into output WordProcessing document. In the first place GroupDocs.Editor takes fonts from font resources within EditableDocument. If they are insufficient or missing, then GroupDocs.Editor takes fonts from OS.

--------------------

First of all GroupDocs.Editor analyzes a content of EditableDocument and forms a list of all used fonts. Then these fotns are searched for in the font resources of EditableDocument. If EditableDocument contains some font resources, which are not involved within document content, such resources are ignored. If there are some fonts, used in the document content, which have no corresponding font resources in EditableDocument, then GroupDocs.Editor tries to find them in the OS. This option resembles the "Embed fonts in the file" option with all sub-options turned off in Microsoft Word 2007 and higher

### EmbedWithoutSystem {#EmbedWithoutSystem}
```
public static final byte EmbedWithoutSystem
```


Exact to [EmbedAll](../../com.groupdocs.editor.options/fontembeddingoptions\#EmbedAll), but exclude those fonts, which are treated by OS as system fonts

--------------------

MS Windows has a concept of system fonts, which are the most basic and used fonts by Windows itself. When using this option, the GroupDocs.Editor acts like for [EmbedAll](../../com.groupdocs.editor.options/fontembeddingoptions\#EmbedAll) case, but finally reviews a set of obtained fonts and excludes those, which are treated by OS as system fonts. This option resembles the "Embed fonts in the file" + "Do not embed common system fonts" options in Microsoft Word 2007 and higher

### getFontEmbeddingOptions() {#getFontEmbeddingOptions--}
```
public static byte[] getFontEmbeddingOptions()
```




**Returns:**
byte[]
