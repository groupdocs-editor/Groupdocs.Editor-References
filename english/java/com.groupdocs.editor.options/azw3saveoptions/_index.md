---
title: Azw3SaveOptions
second_title: GroupDocs.Editor for Java API Reference
description: Allows to specify custom options for generating and saving the AZW3 e-books also known as Kindle Format 8 KF8
type: docs
weight: 10
url: /java/com.groupdocs.editor.options/azw3saveoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ISaveOptions](../../com.groupdocs.editor.options/isaveoptions)
```
public final class Azw3SaveOptions implements ISaveOptions
```

Allows to specify custom options for generating and saving the AZW3 e-books, also known as Kindle Format 8 (KF8)
## Constructors

| Constructor | Description |
| --- | --- |
| [Azw3SaveOptions()](#Azw3SaveOptions--) |  |
## Methods

| Method | Description |
| --- | --- |
| [getSplitHeadingLevel()](#getSplitHeadingLevel--) | Specifies whether to split the content of AZW3 e-book onto packages and if yes, the maximum level of headings at which to split the content of the AZW3. |
| [setSplitHeadingLevel(int value)](#setSplitHeadingLevel-int-) | Specifies whether to split the content of AZW3 e-book onto packages and if yes, the maximum level of headings at which to split the content of the AZW3. |
### Azw3SaveOptions() {#Azw3SaveOptions--}
```
public Azw3SaveOptions()
```


### getSplitHeadingLevel() {#getSplitHeadingLevel--}
```
public final int getSplitHeadingLevel()
```


Specifies whether to split the content of AZW3 e-book onto packages and if yes, the maximum level of headings at which to split the content of the AZW3. Default value is  2 . Setting it to  0  will disable splitting, so all content of the e-book will be incorporarted into a single package inside the AZW3.

--------------------

In some cases it is preferable to split the content of e-book into several smaller packages, located inside the output AZW3 file. This property controls whether such separation should be performed and if yes, then how.

When this property is set to a value from 1 to 9, the document will be split at paragraphs formatted using  **Heading 1** ,  **Heading 2**  ,  **Heading 3**  etc. styles up to the specified heading level.

By default (value of  2 ), only  **Heading 1**  and  **Heading 2**  paragraphs cause the document to be split. Setting this property to zero will cause the document not to be split at heading paragraphs at all.

**Returns:**
int
### setSplitHeadingLevel(int value) {#setSplitHeadingLevel-int-}
```
public final void setSplitHeadingLevel(int value)
```


Specifies whether to split the content of AZW3 e-book onto packages and if yes, the maximum level of headings at which to split the content of the AZW3. Default value is  2 . Setting it to  0  will disable splitting, so all content of the e-book will be incorporarted into a single package inside the AZW3.

--------------------

In some cases it is preferable to split the content of e-book into several smaller packages, located inside the output AZW3 file. This property controls whether such separation should be performed and if yes, then how.

When this property is set to a value from 1 to 9, the document will be split at paragraphs formatted using  **Heading 1** ,  **Heading 2**  ,  **Heading 3**  etc. styles up to the specified heading level.

By default (value of  2 ), only  **Heading 1**  and  **Heading 2**  paragraphs cause the document to be split. Setting this property to zero will cause the document not to be split at heading paragraphs at all.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

