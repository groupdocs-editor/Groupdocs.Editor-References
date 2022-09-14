---
title: Ruleset
second_title: GroupDocs.Editor for Java API Reference
description:  Represents one ruleset which contains a selector and a declaration block and
 supports serialization
type: docs
weight: 14
url: /java/com.groupdocs.editor.htmlcss.css/ruleset/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.css.atrules.NestedRuleBase](../../com.groupdocs.editor.htmlcss.css.atrules/nestedrulebase)

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.css.ICssRule](../../com.groupdocs.editor.htmlcss.css/icssrule), com.aspose.ms.System.IEquatable
```
public final class Ruleset extends NestedRuleBase implements ICssRule, System.IEquatable<Ruleset>
```

Represents one ruleset, which contains a selector and a declaration block and supports serialization
## Constructors

| Constructor | Description |
| --- | --- |
| [Ruleset(ISelector selector, CssDeclarationBlock declarationBlock)](#Ruleset-com.groupdocs.editor.htmlcss.css.selectors.ISelector-com.groupdocs.editor.htmlcss.css.CssDeclarationBlock-) |  |
## Methods

| Method | Description |
| --- | --- |
| [getSelector()](#getSelector--) | Allows to obtain or update the selector of this ruleset. |
| [setSelector(ISelector value)](#setSelector-com.groupdocs.editor.htmlcss.css.selectors.ISelector-) | Allows to obtain or update the selector of this ruleset. |
| [getDeclarationBlock()](#getDeclarationBlock--) | Allows to obtain or update the CSS declarations block of this ruleset. |
| [setDeclarationBlock(CssDeclarationBlock value)](#setDeclarationBlock-com.groupdocs.editor.htmlcss.css.CssDeclarationBlock-) | Allows to obtain or update the CSS declarations block of this ruleset. |
| [serialize(ISerializationOptions serializationOptions)](#serialize-com.groupdocs.editor.htmlcss.serialization.ISerializationOptions-) |  |
| [serialize(ISerializationOptions serializationOptions, System.IO.TextWriter output)](#serialize-com.groupdocs.editor.htmlcss.serialization.ISerializationOptions-com.aspose.ms.System.IO.TextWriter-) |  |
| [areEqual(Ruleset first, Ruleset second)](#areEqual-com.groupdocs.editor.htmlcss.css.Ruleset-com.groupdocs.editor.htmlcss.css.Ruleset-) |  |
| [equals(Ruleset other)](#equals-com.groupdocs.editor.htmlcss.css.Ruleset-) | Compares this ruleset with specified by comparing their selectors and CSS declaration blocks |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
### Ruleset(ISelector selector, CssDeclarationBlock declarationBlock) {#Ruleset-com.groupdocs.editor.htmlcss.css.selectors.ISelector-com.groupdocs.editor.htmlcss.css.CssDeclarationBlock-}
```
public Ruleset(ISelector selector, CssDeclarationBlock declarationBlock)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| selector | [ISelector](../../com.groupdocs.editor.htmlcss.css.selectors/iselector) |  |
| declarationBlock | [CssDeclarationBlock](../../com.groupdocs.editor.htmlcss.css/cssdeclarationblock) |  |

### getSelector() {#getSelector--}
```
public final ISelector getSelector()
```


Allows to obtain or update the selector of this ruleset. Null values are not allowed.

**Returns:**
[ISelector](../../com.groupdocs.editor.htmlcss.css.selectors/iselector)
### setSelector(ISelector value) {#setSelector-com.groupdocs.editor.htmlcss.css.selectors.ISelector-}
```
public final void setSelector(ISelector value)
```


Allows to obtain or update the selector of this ruleset. Null values are not allowed.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ISelector](../../com.groupdocs.editor.htmlcss.css.selectors/iselector) |  |

### getDeclarationBlock() {#getDeclarationBlock--}
```
public final CssDeclarationBlock getDeclarationBlock()
```


Allows to obtain or update the CSS declarations block of this ruleset. Null values are not allowed.

**Returns:**
[CssDeclarationBlock](../../com.groupdocs.editor.htmlcss.css/cssdeclarationblock)
### setDeclarationBlock(CssDeclarationBlock value) {#setDeclarationBlock-com.groupdocs.editor.htmlcss.css.CssDeclarationBlock-}
```
public final void setDeclarationBlock(CssDeclarationBlock value)
```


Allows to obtain or update the CSS declarations block of this ruleset. Null values are not allowed.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [CssDeclarationBlock](../../com.groupdocs.editor.htmlcss.css/cssdeclarationblock) |  |

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

### areEqual(Ruleset first, Ruleset second) {#areEqual-com.groupdocs.editor.htmlcss.css.Ruleset-com.groupdocs.editor.htmlcss.css.Ruleset-}
```
public static boolean areEqual(Ruleset first, Ruleset second)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| first | [Ruleset](../../com.groupdocs.editor.htmlcss.css/ruleset) |  |
| second | [Ruleset](../../com.groupdocs.editor.htmlcss.css/ruleset) |  |

**Returns:**
boolean
### equals(Ruleset other) {#equals-com.groupdocs.editor.htmlcss.css.Ruleset-}
```
public final boolean equals(Ruleset other)
```


Compares this ruleset with specified by comparing their selectors and CSS declaration blocks

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| other | [Ruleset](../../com.groupdocs.editor.htmlcss.css/ruleset) |  |

**Returns:**
boolean - 
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
