---
title: CssDeclarationBlock
second_title: GroupDocs.Editor for Java API Reference
description:  Represents one CSS declaration block list of declarations
type: docs
weight: 10
url: /java/com.groupdocs.editor.htmlcss.css/cssdeclarationblock/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.Collections.ObjectModel.Collection, com.aspose.ms.System.Collections.ObjectModel.KeyedCollection

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.css.ICssDeclarationBlock](../../com.groupdocs.editor.htmlcss.css/icssdeclarationblock)
```
public class CssDeclarationBlock extends System.Collections.ObjectModel.KeyedCollection<String,ICssDeclaration> implements ICssDeclarationBlock
```

Represents one CSS declaration block (list of declarations)
## Constructors

| Constructor | Description |
| --- | --- |
| [CssDeclarationBlock()](#CssDeclarationBlock--) | Creates and returns new empty instance of declaration block, without declarationsinject |
| [CssDeclarationBlock(ICssDeclaration firstDeclaration)](#CssDeclarationBlock-com.groupdocs.editor.htmlcss.css.ICssDeclaration-) |  |
## Methods

| Method | Description |
| --- | --- |
| [isEmpty()](#isEmpty--) | Detects whether the current block is empty (true) or there exists at least one declaration (false) |
| [getFirst()](#getFirst--) | Returns first CSS declaration from this declaration block or throws an exception, if it is empty |
| [getLast()](#getLast--) | Returns last CSS declaration from this declaration block or throws an exception, if it is empty |
| [<TDecl>doesNotContain(Class<TDecl> clazz)](#-TDecl-doesNotContain-java.lang.Class-TDecl--) | Determines whether this declaration block doesn't contain specified CSS property |
| [upsert(ICssDeclaration newDeclaration)](#upsert-com.groupdocs.editor.htmlcss.css.ICssDeclaration-) | Adds a new CSS declaration with specified property and value, if it doesn't exist, or updates value of the declaration with specified property |
| [<TDecl>tryGet(Class<TDecl> typeOfTDecl)](#-TDecl-tryGet-java.lang.Class-TDecl--) | Tries to find and return a declaration of specified type via generic type argument or return a default value, if it not present in this declaration block |
| [<TDecl>tryGet(Class<TDecl> typeOfTDecl, String declarationName)](#-TDecl-tryGet-java.lang.Class-TDecl--java.lang.String-) | Tries to find and return a declaration of specified type (via generic type argument and name) or return a default value, if it not present in this declaration block |
| [tryGet(String declarationName)](#tryGet-java.lang.String-) | Tries to find and return a declaration of specified name, or returns a NULL, if it not present in this declaration block |
| [serialize(ISerializationOptions serializationOptions)](#serialize-com.groupdocs.editor.htmlcss.serialization.ISerializationOptions-) |  |
| [serialize(ISerializationOptions serializationOptions, System.IO.TextWriter output)](#serialize-com.groupdocs.editor.htmlcss.serialization.ISerializationOptions-com.aspose.ms.System.IO.TextWriter-) |  |
| [inject(CssDeclarationBlock otherDeclBlock, boolean upsertMatches)](#inject-com.groupdocs.editor.htmlcss.css.CssDeclarationBlock-boolean-) | Pushes all declarations from specified declaration block into this declaration block. |
| [equals(CssDeclarationBlock other)](#equals-com.groupdocs.editor.htmlcss.css.CssDeclarationBlock-) | Determines whether specified CSS declaration block is equal to this one: does it have the same amount of the same CSS declarations, while their order is not important |
### CssDeclarationBlock() {#CssDeclarationBlock--}
```
public CssDeclarationBlock()
```


Creates and returns new empty instance of declaration block, without declarationsinject

### CssDeclarationBlock(ICssDeclaration firstDeclaration) {#CssDeclarationBlock-com.groupdocs.editor.htmlcss.css.ICssDeclaration-}
```
public CssDeclarationBlock(ICssDeclaration firstDeclaration)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| firstDeclaration | [ICssDeclaration](../../com.groupdocs.editor.htmlcss.css/icssdeclaration) |  |

### isEmpty() {#isEmpty--}
```
public final boolean isEmpty()
```


Detects whether the current block is empty (true) or there exists at least one declaration (false)

**Returns:**
boolean
### getFirst() {#getFirst--}
```
public final ICssDeclaration getFirst()
```


Returns first CSS declaration from this declaration block or throws an exception, if it is empty

**Returns:**
[ICssDeclaration](../../com.groupdocs.editor.htmlcss.css/icssdeclaration)
### getLast() {#getLast--}
```
public final ICssDeclaration getLast()
```


Returns last CSS declaration from this declaration block or throws an exception, if it is empty

**Returns:**
[ICssDeclaration](../../com.groupdocs.editor.htmlcss.css/icssdeclaration)
### <TDecl>doesNotContain(Class<TDecl> clazz) {#-TDecl-doesNotContain-java.lang.Class-TDecl--}
```
public final boolean <TDecl>doesNotContain(Class<TDecl> clazz)
```


Determines whether this declaration block doesn't contain specified CSS property

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| clazz | java.lang.Class<TDecl> |  |

**Returns:**
boolean - \`\`\` TDecl \`\`\`: ICssDeclaration inheritor, which should have a constant string fileld 'Name' with ObfuscationAttribute(Feature = "renaming")
### upsert(ICssDeclaration newDeclaration) {#upsert-com.groupdocs.editor.htmlcss.css.ICssDeclaration-}
```
public final boolean upsert(ICssDeclaration newDeclaration)
```


Adds a new CSS declaration with specified property and value, if it doesn't exist, or updates value of the declaration with specified property

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| newDeclaration | [ICssDeclaration](../../com.groupdocs.editor.htmlcss.css/icssdeclaration) |  |

**Returns:**
boolean - True if existent declaration was modified; false if it was added
### <TDecl>tryGet(Class<TDecl> typeOfTDecl) {#-TDecl-tryGet-java.lang.Class-TDecl--}
```
public final TDecl <TDecl>tryGet(Class<TDecl> typeOfTDecl)
```


Tries to find and return a declaration of specified type via generic type argument or return a default value, if it not present in this declaration block

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| typeOfTDecl | java.lang.Class<TDecl> |  |

**Returns:**
TDecl - \`\`\` TDecl \`\`\`:
### <TDecl>tryGet(Class<TDecl> typeOfTDecl, String declarationName) {#-TDecl-tryGet-java.lang.Class-TDecl--java.lang.String-}
```
public final TDecl <TDecl>tryGet(Class<TDecl> typeOfTDecl, String declarationName)
```


Tries to find and return a declaration of specified type (via generic type argument and name) or return a default value, if it not present in this declaration block

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| typeOfTDecl | java.lang.Class<TDecl> |  |
| declarationName | java.lang.String | \`\`\` TDecl \`\`\`: |

**Returns:**
TDecl - 
### tryGet(String declarationName) {#tryGet-java.lang.String-}
```
public final ICssDeclaration tryGet(String declarationName)
```


Tries to find and return a declaration of specified name, or returns a NULL, if it not present in this declaration block

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| declarationName | java.lang.String |  |

**Returns:**
[ICssDeclaration](../../com.groupdocs.editor.htmlcss.css/icssdeclaration) - 
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

### inject(CssDeclarationBlock otherDeclBlock, boolean upsertMatches) {#inject-com.groupdocs.editor.htmlcss.css.CssDeclarationBlock-boolean-}
```
public final void inject(CssDeclarationBlock otherDeclBlock, boolean upsertMatches)
```


Pushes all declarations from specified declaration block into this declaration block. Boolean parameter determines how to process matches.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| otherDeclBlock | [CssDeclarationBlock](../../com.groupdocs.editor.htmlcss.css/cssdeclarationblock) |  |
| upsertMatches | boolean | If true, all matches from specified block will replace declarations from this block. If false, an exception will occur on the first match, if values are unequal. In other words, 'true' serves as 'Upsert', and 'false' - as 'Add', but ignores equal values. |

### equals(CssDeclarationBlock other) {#equals-com.groupdocs.editor.htmlcss.css.CssDeclarationBlock-}
```
public final boolean equals(CssDeclarationBlock other)
```


Determines whether specified CSS declaration block is equal to this one: does it have the same amount of the same CSS declarations, while their order is not important

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| other | [CssDeclarationBlock](../../com.groupdocs.editor.htmlcss.css/cssdeclarationblock) |  |

**Returns:**
boolean - 
