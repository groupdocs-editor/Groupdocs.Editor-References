---
title: ICssDataType
second_title: GroupDocs.Editor for Java API Reference
description: Common interface for all CSS data types which are used in the CSS properties
type: docs
weight: 29
url: /java/com.groupdocs.editor.htmlcss.css.datatypes/icssdatatype/
---
**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable
```
public interface ICssDataType extends System.IEquatable<ICssDataType>
```

Common interface for all CSS data types, which are used in the CSS properties
## Methods

| Method | Description |
| --- | --- |
| [serializeDefault()](#serializeDefault--) | Should return a default string representation of the current value of the data type |
| [isDefault()](#isDefault--) | Should define whether the current value of the data type is the default value for this specific data type or not |
### serializeDefault() {#serializeDefault--}
```
public abstract String serializeDefault()
```


Should return a default string representation of the current value of the data type

**Returns:**
java.lang.String - 
### isDefault() {#isDefault--}
```
public abstract boolean isDefault()
```


Should define whether the current value of the data type is the default value for this specific data type or not

**Returns:**
boolean - 
