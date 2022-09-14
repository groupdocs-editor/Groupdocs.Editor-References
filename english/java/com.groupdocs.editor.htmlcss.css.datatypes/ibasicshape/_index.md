---
title: IBasicShape
second_title: GroupDocs.Editor for Java API Reference
description:  basic-shape CSS data type represents a shape used in the clip-path
 shape-outside and offset-path properties
type: docs
weight: 28
url: /java/com.groupdocs.editor.htmlcss.css.datatypes/ibasicshape/
---
**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.css.datatypes.ICssDataType](../../com.groupdocs.editor.htmlcss.css.datatypes/icssdatatype)
```
public interface IBasicShape extends ICssDataType
```

basic-shape CSS data type represents a shape used in the clip-path, shape-outside, and offset-path properties

--------------------

https://developer.mozilla.org/en-US/docs/Web/CSS/basic-shape
## Methods

| Method | Description |
| --- | --- |
| [equals(IBasicShape other)](#equals-com.groupdocs.editor.htmlcss.css.datatypes.IBasicShape-) | In implementing type should check equality between this and other specified basic shapes |
| [serializeDefault()](#serializeDefault--) |  |
| [isDefault()](#isDefault--) |  |
### equals(IBasicShape other) {#equals-com.groupdocs.editor.htmlcss.css.datatypes.IBasicShape-}
```
public abstract boolean equals(IBasicShape other)
```


In implementing type should check equality between this and other specified basic shapes

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| other | [IBasicShape](../../com.groupdocs.editor.htmlcss.css.datatypes/ibasicshape) |  |

**Returns:**
boolean - 
### serializeDefault() {#serializeDefault--}
```
public abstract String serializeDefault()
```


Should return a default string representation of the current value of the data type

**Returns:**
java.lang.String
### isDefault() {#isDefault--}
```
public abstract boolean isDefault()
```


Should define whether the current value of the data type is the default value for this specific data type or not

**Returns:**
boolean
