---
title: TextDirection
second_title: GroupDocs.Editor for Java API Reference
description: Represents 3 possible variants how to treat text direction in the plain text documents
type: docs
weight: 27
url: /java/com.groupdocs.editor.options/textdirection/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class TextDirection extends System.Enum
```

Represents 3 possible variants how to treat text direction in the plain text documents
## Fields

| Field | Description |
| --- | --- |
| [LeftToRight](#LeftToRight) | Left-to-Right direction, usual text, default value. |
| [RightToLeft](#RightToLeft) | Right-to-Left direction |
| [Auto](#Auto) | Auto-detect direction. |
## Methods

| Method | Description |
| --- | --- |
| [getTextDirection()](#getTextDirection--) |  |
### LeftToRight {#LeftToRight}
```
public static final int LeftToRight
```


Left-to-Right direction, usual text, default value.

### RightToLeft {#RightToLeft}
```
public static final int RightToLeft
```


Right-to-Left direction

### Auto {#Auto}
```
public static final int Auto
```


Auto-detect direction. When this option is selected and text contains characters belonging to RTL scripts, the document direction will be set automatically to RTL.

### getTextDirection() {#getTextDirection--}
```
public static int[] getTextDirection()
```




**Returns:**
int[]
