---
title: UnknownCssDeclaration
second_title: GroupDocs.Editor for Java API Reference
description: Represents one unknown CSS declaration with its property key and value.
type: docs
weight: 16
url: /java/com.groupdocs.editor.htmlcss.css/unknowncssdeclaration/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable, [com.groupdocs.editor.htmlcss.css.ICssDeclaration](../../com.groupdocs.editor.htmlcss.css/icssdeclaration)
```
public class UnknownCssDeclaration implements System.IEquatable<UnknownCssDeclaration>, ICssDeclaration
```

Represents one unknown CSS declaration with its property (key) and value. Property is immutable, while value is mutable.
## Constructors

| Constructor | Description |
| --- | --- |
| [UnknownCssDeclaration(String property, String value)](#UnknownCssDeclaration-java.lang.String-java.lang.String-) |  |
## Methods

| Method | Description |
| --- | --- |
| [getProperty()](#getProperty--) |  |
| [getValue()](#getValue--) |  |
| [setValue(String value)](#setValue-java.lang.String-) |  |
| [isDefault()](#isDefault--) |  |
| [isGlobal()](#isGlobal--) |  |
| [getInherited()](#getInherited--) |  |
| [setInherited(boolean value)](#setInherited-boolean-) |  |
| [getImportant()](#getImportant--) |  |
| [setImportant(boolean value)](#setImportant-boolean-) |  |
| [getAnimationType()](#getAnimationType--) |  |
| [setAnimationType(int value)](#setAnimationType-int-) |  |
| [equals(UnknownCssDeclaration other)](#equals-com.groupdocs.editor.htmlcss.css.UnknownCssDeclaration-) |  |
| [equals(ICssDeclaration other)](#equals-com.groupdocs.editor.htmlcss.css.ICssDeclaration-) |  |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [hashCode()](#hashCode--) |  |
| [serialize(ISerializationOptions serializationOptions)](#serialize-com.groupdocs.editor.htmlcss.serialization.ISerializationOptions-) |  |
| [serialize(ISerializationOptions serializationOptions, System.IO.TextWriter output)](#serialize-com.groupdocs.editor.htmlcss.serialization.ISerializationOptions-com.aspose.ms.System.IO.TextWriter-) |  |
### UnknownCssDeclaration(String property, String value) {#UnknownCssDeclaration-java.lang.String-java.lang.String-}
```
public UnknownCssDeclaration(String property, String value)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| property | java.lang.String |  |
| value | java.lang.String |  |

### getProperty() {#getProperty--}
```
public final String getProperty()
```


In implementing type should return a property name as a string

**Returns:**
java.lang.String
### getValue() {#getValue--}
```
public final String getValue()
```


In implementing type should return a value in a default string form, without affecting serialization options

**Returns:**
java.lang.String
### setValue(String value) {#setValue-java.lang.String-}
```
public final void setValue(String value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### isDefault() {#isDefault--}
```
public final boolean isDefault()
```


In implementing type should define, whether a current value is a default value of a declaration, or not

**Returns:**
boolean
### isGlobal() {#isGlobal--}
```
public final boolean isGlobal()
```


In implementing type should define, whether a current value is a global value of a declaration (inherit [initial, unset]), or not

**Returns:**
boolean
### getInherited() {#getInherited--}
```
public final boolean getInherited()
```


All CSS declarations are divided on inherited or non-inherited, what is represented by this property

--------------------

https://developer.mozilla.org/en-US/docs/Web/CSS/inheritance

**Returns:**
boolean
### setInherited(boolean value) {#setInherited-boolean-}
```
public final void setInherited(boolean value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getImportant() {#getImportant--}
```
public final boolean getImportant()
```




**Returns:**
boolean
### setImportant(boolean value) {#setImportant-boolean-}
```
public final void setImportant(boolean value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getAnimationType() {#getAnimationType--}
```
public final int getAnimationType()
```


All CSS properties have at least one animation type, which determines, how they can be animated

**Returns:**
int
### setAnimationType(int value) {#setAnimationType-int-}
```
public final void setAnimationType(int value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### equals(UnknownCssDeclaration other) {#equals-com.groupdocs.editor.htmlcss.css.UnknownCssDeclaration-}
```
public final boolean equals(UnknownCssDeclaration other)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| other | [UnknownCssDeclaration](../../com.groupdocs.editor.htmlcss.css/unknowncssdeclaration) |  |

**Returns:**
boolean
### equals(ICssDeclaration other) {#equals-com.groupdocs.editor.htmlcss.css.ICssDeclaration-}
```
public final boolean equals(ICssDeclaration other)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| other | [ICssDeclaration](../../com.groupdocs.editor.htmlcss.css/icssdeclaration) |  |

**Returns:**
boolean
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Returns:**
boolean
### hashCode() {#hashCode--}
```
public int hashCode()
```




**Returns:**
int
### serialize(ISerializationOptions serializationOptions) {#serialize-com.groupdocs.editor.htmlcss.serialization.ISerializationOptions-}
```
public final String serialize(ISerializationOptions serializationOptions)
```


In implementing type returns a serialized representation of an object as a string

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| serializationOptions | [ISerializationOptions](../../com.groupdocs.editor.htmlcss.serialization/iserializationoptions) |  |

**Returns:**
java.lang.String
### serialize(ISerializationOptions serializationOptions, System.IO.TextWriter output) {#serialize-com.groupdocs.editor.htmlcss.serialization.ISerializationOptions-com.aspose.ms.System.IO.TextWriter-}
```
public final void serialize(ISerializationOptions serializationOptions, System.IO.TextWriter output)
```


In implementing type writes a serialized representation of an object to the specified output TextWriter implementation

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| serializationOptions | [ISerializationOptions](../../com.groupdocs.editor.htmlcss.serialization/iserializationoptions) |  |
| output | com.aspose.ms.System.IO.TextWriter |  |

