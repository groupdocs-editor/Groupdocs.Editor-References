---
title: Inset
second_title: GroupDocs.Editor for Java API Reference
description: Defines an inset rectangle.
type: docs
weight: 20
url: /java/com.groupdocs.editor.htmlcss.css.datatypes/inset/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.css.datatypes.IBasicShape](../../com.groupdocs.editor.htmlcss.css.datatypes/ibasicshape)
```
public class Inset implements IBasicShape
```

Defines an inset rectangle. 1st of 5 basic-shape functions.
## Constructors

| Constructor | Description |
| --- | --- |
| [Inset()](#Inset--) | Returns a new default instance of "inset", where all components have default values |
## Methods

| Method | Description |
| --- | --- |
| [isDefault()](#isDefault--) |  |
| [getBySide(byte side)](#getBySide-byte-) | Returns offset of specified side |
| [getRoundedCorners()](#getRoundedCorners--) | Allows to get or set a border-radius value for rounded corners of a rectangle |
| [setRoundedCorners(BorderRadius value)](#setRoundedCorners-com.groupdocs.editor.htmlcss.css.specificdeclarations.borderradius.BorderRadius-) | Allows to get or set a border-radius value for rounded corners of a rectangle |
| [serializeDefault()](#serializeDefault--) |  |
| [equals(Inset other)](#equals-com.groupdocs.editor.htmlcss.css.datatypes.Inset-) | Defines whether this Inset is equal to the specified |
| [equals(ICssDataType other)](#equals-com.groupdocs.editor.htmlcss.css.datatypes.ICssDataType-) |  |
| [equals(IBasicShape other)](#equals-com.groupdocs.editor.htmlcss.css.datatypes.IBasicShape-) |  |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [op_Equality(Inset first, Inset second)](#op-Equality-com.groupdocs.editor.htmlcss.css.datatypes.Inset-com.groupdocs.editor.htmlcss.css.datatypes.Inset-) | Checks two "Inset" instances on equality |
| [op_Inequality(Inset first, Inset second)](#op-Inequality-com.groupdocs.editor.htmlcss.css.datatypes.Inset-com.groupdocs.editor.htmlcss.css.datatypes.Inset-) | Checks two "Inset" instances on inequality |
| [create(Length top, Length right, Length bottom, Length left, BorderRadius borderRadius)](#create-com.groupdocs.editor.htmlcss.css.datatypes.Length-com.groupdocs.editor.htmlcss.css.datatypes.Length-com.groupdocs.editor.htmlcss.css.datatypes.Length-com.groupdocs.editor.htmlcss.css.datatypes.Length-com.groupdocs.editor.htmlcss.css.specificdeclarations.borderradius.BorderRadius-) |  |
### Inset() {#Inset--}
```
public Inset()
```


Returns a new default instance of "inset", where all components have default values

### isDefault() {#isDefault--}
```
public final boolean isDefault()
```


Should define whether the current value of the data type is the default value for this specific data type or not

**Returns:**
boolean
### getBySide(byte side) {#getBySide-byte-}
```
public final Length getBySide(byte side)
```


Returns offset of specified side

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| side | byte |  |

**Returns:**
[Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) - 
### getRoundedCorners() {#getRoundedCorners--}
```
public final BorderRadius getRoundedCorners()
```


Allows to get or set a border-radius value for rounded corners of a rectangle

**Returns:**
[BorderRadius](../../com.groupdocs.editor.htmlcss.css.specificdeclarations.borderradius/borderradius)
### setRoundedCorners(BorderRadius value) {#setRoundedCorners-com.groupdocs.editor.htmlcss.css.specificdeclarations.borderradius.BorderRadius-}
```
public final void setRoundedCorners(BorderRadius value)
```


Allows to get or set a border-radius value for rounded corners of a rectangle

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [BorderRadius](../../com.groupdocs.editor.htmlcss.css.specificdeclarations.borderradius/borderradius) |  |

### serializeDefault() {#serializeDefault--}
```
public final String serializeDefault()
```


Should return a default string representation of the current value of the data type

**Returns:**
java.lang.String
### equals(Inset other) {#equals-com.groupdocs.editor.htmlcss.css.datatypes.Inset-}
```
public final boolean equals(Inset other)
```


Defines whether this Inset is equal to the specified

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| other | [Inset](../../com.groupdocs.editor.htmlcss.css.datatypes/inset) |  |

**Returns:**
boolean - 
### equals(ICssDataType other) {#equals-com.groupdocs.editor.htmlcss.css.datatypes.ICssDataType-}
```
public final boolean equals(ICssDataType other)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| other | [ICssDataType](../../com.groupdocs.editor.htmlcss.css.datatypes/icssdatatype) |  |

**Returns:**
boolean
### equals(IBasicShape other) {#equals-com.groupdocs.editor.htmlcss.css.datatypes.IBasicShape-}
```
public final boolean equals(IBasicShape other)
```


In implementing type should check equality between this and other specified basic shapes

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| other | [IBasicShape](../../com.groupdocs.editor.htmlcss.css.datatypes/ibasicshape) |  |

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
### op_Equality(Inset first, Inset second) {#op-Equality-com.groupdocs.editor.htmlcss.css.datatypes.Inset-com.groupdocs.editor.htmlcss.css.datatypes.Inset-}
```
public static boolean op_Equality(Inset first, Inset second)
```


Checks two "Inset" instances on equality

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| first | [Inset](../../com.groupdocs.editor.htmlcss.css.datatypes/inset) |  |
| second | [Inset](../../com.groupdocs.editor.htmlcss.css.datatypes/inset) |  |

**Returns:**
boolean - 
### op_Inequality(Inset first, Inset second) {#op-Inequality-com.groupdocs.editor.htmlcss.css.datatypes.Inset-com.groupdocs.editor.htmlcss.css.datatypes.Inset-}
```
public static boolean op_Inequality(Inset first, Inset second)
```


Checks two "Inset" instances on inequality

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| first | [Inset](../../com.groupdocs.editor.htmlcss.css.datatypes/inset) |  |
| second | [Inset](../../com.groupdocs.editor.htmlcss.css.datatypes/inset) |  |

**Returns:**
boolean - 
### create(Length top, Length right, Length bottom, Length left, BorderRadius borderRadius) {#create-com.groupdocs.editor.htmlcss.css.datatypes.Length-com.groupdocs.editor.htmlcss.css.datatypes.Length-com.groupdocs.editor.htmlcss.css.datatypes.Length-com.groupdocs.editor.htmlcss.css.datatypes.Length-com.groupdocs.editor.htmlcss.css.specificdeclarations.borderradius.BorderRadius-}
```
public static Inset create(Length top, Length right, Length bottom, Length left, BorderRadius borderRadius)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| top | [Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) |  |
| right | [Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) |  |
| bottom | [Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) |  |
| left | [Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) |  |
| borderRadius | [BorderRadius](../../com.groupdocs.editor.htmlcss.css.specificdeclarations.borderradius/borderradius) |  |

**Returns:**
[Inset](../../com.groupdocs.editor.htmlcss.css.datatypes/inset)
