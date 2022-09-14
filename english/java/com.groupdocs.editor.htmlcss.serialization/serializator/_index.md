---
title: Serializator
second_title: GroupDocs.Editor for Java API Reference
description: Utility static stateless class which contains pure methods for serializing components of HTML and CSS documents
type: docs
weight: 14
url: /java/com.groupdocs.editor.htmlcss.serialization/serializator/
---
**Inheritance:**
java.lang.Object
```
public class Serializator
```

Utility static stateless class, which contains pure methods for serializing components of HTML and CSS documents
## Constructors

| Constructor | Description |
| --- | --- |
| [Serializator()](#Serializator--) |  |
## Methods

| Method | Description |
| --- | --- |
| [serializePseudoElement(PseudoElementBase targetElement, boolean applyReadability)](#serializePseudoElement-com.groupdocs.editor.htmlcss.html.PseudoElementBase-boolean-) |  |
| [serializePseudoElement(PseudoElementBase targetElement, boolean applyReadability, System.IO.TextWriter output)](#serializePseudoElement-com.groupdocs.editor.htmlcss.html.PseudoElementBase-boolean-com.aspose.ms.System.IO.TextWriter-) |  |
| [serializeUnknownElement(ElementBase targetElement, ISerializationOptions serializationOptions)](#serializeUnknownElement-com.groupdocs.editor.htmlcss.html.ElementBase-com.groupdocs.editor.htmlcss.serialization.ISerializationOptions-) | Performs a serialization of specified element of any type (including pseudo-elements) and all its descendants to the 'StringBuilder' and returns it |
| [serializeUnknownElement(ElementBase targetElement, ISerializationOptions serializationOptions, System.IO.TextWriter output)](#serializeUnknownElement-com.groupdocs.editor.htmlcss.html.ElementBase-com.groupdocs.editor.htmlcss.serialization.ISerializationOptions-com.aspose.ms.System.IO.TextWriter-) | Performs a serialization of specified element of any type (including pseudo-elements) and all its descendants to the specified output 'TextWriter' |
| [serializeSimpleCssDeclaration(String propertyName, String declValue, ISerializationOptions serializationOptions)](#serializeSimpleCssDeclaration-java.lang.String-java.lang.String-com.groupdocs.editor.htmlcss.serialization.ISerializationOptions-) | Serializes one simple CSS declaration, which is specified by its property name and value (and using specified serialization options), to the string and returns this string. |
| [serializeSimpleCssDeclaration(String propertyName, String declValue, ISerializationOptions serializationOptions, System.IO.TextWriter output)](#serializeSimpleCssDeclaration-java.lang.String-java.lang.String-com.groupdocs.editor.htmlcss.serialization.ISerializationOptions-com.aspose.ms.System.IO.TextWriter-) | Serializes one simple CSS declaration, which is specified by its property name and value (and using specified serialization options), to the specified output TextWriter implementation |
| [dequote(String input)](#dequote-java.lang.String-) | Removes enclosing quotes from specified string, if it has opening and closing quote of the same type (single or double) and these quotes are located at the first and last index. |
| [enquote(String input, int quoteType)](#enquote-java.lang.String-int-) | Enquotes the specified string with opening and closing quote of specified type |
### Serializator() {#Serializator--}
```
public Serializator()
```


### serializePseudoElement(PseudoElementBase targetElement, boolean applyReadability) {#serializePseudoElement-com.groupdocs.editor.htmlcss.html.PseudoElementBase-boolean-}
```
public static System.Text.msStringBuilder serializePseudoElement(PseudoElementBase targetElement, boolean applyReadability)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| targetElement | [PseudoElementBase](../../com.groupdocs.editor.htmlcss.html/pseudoelementbase) |  |
| applyReadability | boolean |  |

**Returns:**
com.aspose.ms.System.Text.msStringBuilder
### serializePseudoElement(PseudoElementBase targetElement, boolean applyReadability, System.IO.TextWriter output) {#serializePseudoElement-com.groupdocs.editor.htmlcss.html.PseudoElementBase-boolean-com.aspose.ms.System.IO.TextWriter-}
```
public static void serializePseudoElement(PseudoElementBase targetElement, boolean applyReadability, System.IO.TextWriter output)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| targetElement | [PseudoElementBase](../../com.groupdocs.editor.htmlcss.html/pseudoelementbase) |  |
| applyReadability | boolean |  |
| output | com.aspose.ms.System.IO.TextWriter |  |

### serializeUnknownElement(ElementBase targetElement, ISerializationOptions serializationOptions) {#serializeUnknownElement-com.groupdocs.editor.htmlcss.html.ElementBase-com.groupdocs.editor.htmlcss.serialization.ISerializationOptions-}
```
public static System.Text.msStringBuilder serializeUnknownElement(ElementBase targetElement, ISerializationOptions serializationOptions)
```


Performs a serialization of specified element of any type (including pseudo-elements) and all its descendants to the 'StringBuilder' and returns it

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| targetElement | [ElementBase](../../com.groupdocs.editor.htmlcss.html/elementbase) |  |
| serializationOptions | [ISerializationOptions](../../com.groupdocs.editor.htmlcss.serialization/iserializationoptions) |  |

**Returns:**
com.aspose.ms.System.Text.msStringBuilder - 
### serializeUnknownElement(ElementBase targetElement, ISerializationOptions serializationOptions, System.IO.TextWriter output) {#serializeUnknownElement-com.groupdocs.editor.htmlcss.html.ElementBase-com.groupdocs.editor.htmlcss.serialization.ISerializationOptions-com.aspose.ms.System.IO.TextWriter-}
```
public static void serializeUnknownElement(ElementBase targetElement, ISerializationOptions serializationOptions, System.IO.TextWriter output)
```


Performs a serialization of specified element of any type (including pseudo-elements) and all its descendants to the specified output 'TextWriter'

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| targetElement | [ElementBase](../../com.groupdocs.editor.htmlcss.html/elementbase) |  |
| serializationOptions | [ISerializationOptions](../../com.groupdocs.editor.htmlcss.serialization/iserializationoptions) |  |
| output | com.aspose.ms.System.IO.TextWriter |  |

### serializeSimpleCssDeclaration(String propertyName, String declValue, ISerializationOptions serializationOptions) {#serializeSimpleCssDeclaration-java.lang.String-java.lang.String-com.groupdocs.editor.htmlcss.serialization.ISerializationOptions-}
```
public static String serializeSimpleCssDeclaration(String propertyName, String declValue, ISerializationOptions serializationOptions)
```


Serializes one simple CSS declaration, which is specified by its property name and value (and using specified serialization options), to the string and returns this string.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| propertyName | java.lang.String |  |
| declValue | java.lang.String |  |
| serializationOptions | [ISerializationOptions](../../com.groupdocs.editor.htmlcss.serialization/iserializationoptions) |  |

**Returns:**
java.lang.String - 
### serializeSimpleCssDeclaration(String propertyName, String declValue, ISerializationOptions serializationOptions, System.IO.TextWriter output) {#serializeSimpleCssDeclaration-java.lang.String-java.lang.String-com.groupdocs.editor.htmlcss.serialization.ISerializationOptions-com.aspose.ms.System.IO.TextWriter-}
```
public static void serializeSimpleCssDeclaration(String propertyName, String declValue, ISerializationOptions serializationOptions, System.IO.TextWriter output)
```


Serializes one simple CSS declaration, which is specified by its property name and value (and using specified serialization options), to the specified output TextWriter implementation

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| propertyName | java.lang.String |  |
| declValue | java.lang.String |  |
| serializationOptions | [ISerializationOptions](../../com.groupdocs.editor.htmlcss.serialization/iserializationoptions) |  |
| output | com.aspose.ms.System.IO.TextWriter |  |

### dequote(String input) {#dequote-java.lang.String-}
```
public static String dequote(String input)
```


Removes enclosing quotes from specified string, if it has opening and closing quote of the same type (single or double) and these quotes are located at the first and last index. If condition is invalid, returns the original string.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| input | java.lang.String |  |

**Returns:**
java.lang.String - 
### enquote(String input, int quoteType) {#enquote-java.lang.String-int-}
```
public static String enquote(String input, int quoteType)
```


Enquotes the specified string with opening and closing quote of specified type

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| input | java.lang.String |  |
| quoteType | int |  |

**Returns:**
java.lang.String - 
