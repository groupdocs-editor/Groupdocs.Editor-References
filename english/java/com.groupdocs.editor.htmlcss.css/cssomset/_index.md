---
title: CssOmSet
second_title: GroupDocs.Editor for Java API Reference
description: Represents an ordered set of CSSOM resources for the HTML document.
type: docs
weight: 12
url: /java/com.groupdocs.editor.htmlcss.css/cssomset/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.Collections.ObjectModel.Collection, com.aspose.ms.System.Collections.ObjectModel.KeyedCollection
```
public final class CssOmSet extends System.Collections.ObjectModel.KeyedCollection<String,CssOm>
```

Represents an ordered set of CSSOM resources for the HTML document. CSSOM instances can be obtained via their textual names or 0-based index.
## Constructors

| Constructor | Description |
| --- | --- |
| [CssOmSet()](#CssOmSet--) |  |
| [CssOmSet(CssOm first)](#CssOmSet-com.groupdocs.editor.htmlcss.css.CssOm-) |  |
## Methods

| Method | Description |
| --- | --- |
| [toResources(ISerializationOptions serializationOptions)](#toResources-com.groupdocs.editor.htmlcss.serialization.ISerializationOptions-) |  |
### CssOmSet() {#CssOmSet--}
```
public CssOmSet()
```


### CssOmSet(CssOm first) {#CssOmSet-com.groupdocs.editor.htmlcss.css.CssOm-}
```
public CssOmSet(CssOm first)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| first | [CssOm](../../com.groupdocs.editor.htmlcss.css/cssom) |  |

### toResources(ISerializationOptions serializationOptions) {#toResources-com.groupdocs.editor.htmlcss.serialization.ISerializationOptions-}
```
public final System.Collections.Generic.List<CssText> toResources(ISerializationOptions serializationOptions)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| serializationOptions | [ISerializationOptions](../../com.groupdocs.editor.htmlcss.serialization/iserializationoptions) |  |

**Returns:**
com.aspose.ms.System.Collections.Generic.List<com.groupdocs.editor.htmlcss.resources.textual.CssText>
