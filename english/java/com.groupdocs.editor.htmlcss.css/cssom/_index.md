---
title: CssOm
second_title: GroupDocs.Editor for Java API Reference
description: CSS document which is represented in a form of hierarchical Object Model with ability to manipulate its structure.
type: docs
weight: 11
url: /java/com.groupdocs.editor.htmlcss.css/cssom/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.serialization.ISerializable](../../com.groupdocs.editor.htmlcss.serialization/iserializable), com.aspose.ms.System.Collections.Generic.IGenericCollection
```
public final class CssOm implements ISerializable, System.Collections.Generic.IGenericCollection<ICssRule>
```

CSS document, which is represented in a form of hierarchical Object Model with ability to manipulate its structure. Supports flexible and customizable serialization.

--------------------

Core statements: A. Each CSS document consists of a list of items, called CSS rules. B. All rules consist of one to three parts: textual identifier, optional prelude and optional declaration block. C. All rules are divided on two principal groups: at-rules and rulesets. D. Identifier for the rulesets is called a 'selector' and has its own internal structure and logics. E. Every ruleset has an identifier, has no prelude and has a declaration block, which may be empty (\{\}). F. Declaration block for every ruleset is a set of declarations, zero or more. G. Identifier for the at-rules is fixed and constant (unique identifier for each type of the at-rule) and is preceded by '@' character without inter space. H. All at-rules are divided onto two groups: non-nested (@charset, @import, and @namespace) and nested (all others). I. All non-nested at-rules can be present only on the top-level of the stylesheet. J. All non-nested at-rules have a prelude of its own format, which follows the identifier, and nothing more. K. All nested at-rules are divided onto two sub-groups: conditional group at-rules (@media, @supports, and @document) and all others. L. Conditional group at-rules may include all other nested at-rules (including other conditional group at-rules) and rulesets, which makes the hierarchical tree. M. All other nested at-rules, which are not from the 'Conditional group', have their own internal structure. N. Rulesets can be located on the top-level of the stylesheet, or be nested inside the conditional group at-rules. \* Rules \*\* Rulesets \*\* At-rules \*\*\* Non-nested at-rules \*\*\* Nested at rules \*\*\*\* Conditional group at-rules \*\*\*\* [all others nested at-rules] ---- Sources: https://developer.mozilla.org/en-US/docs/Learn/CSS/Introduction\_to\_CSS https://developer.mozilla.org/en-US/docs/Web/CSS/Syntax https://developer.mozilla.org/en-US/docs/Web/CSS/At-rule
## Constructors

| Constructor | Description |
| --- | --- |
| [CssOm(String name)](#CssOm-java.lang.String-) | Creates a new instance with specified name and empty content |
## Methods

| Method | Description |
| --- | --- |
| [getName()](#getName--) | Returns a textual name of this CSSOM instance, which is specified during its creation and cannot be changed. |
| [getRulesets()](#getRulesets--) | Returns all top-level rulesets, which are located in this CssOm instance, but without at-rules |
| [getAtRules()](#getAtRules--) | Returns all top-level at-rules, which are located in this CssOm instance, but without rulesets |
| [getCharset()](#getCharset--) | Allows to obtain or specify a charset for this CSSOM, which will be transformed into the @charset at-rule during serialization. |
| [setCharset(System.Text.Encoding value)](#setCharset-com.aspose.ms.System.Text.Encoding-) | Allows to obtain or specify a charset for this CSSOM, which will be transformed into the @charset at-rule during serialization. |
| [get_Item(String selector, boolean throwIfNotFound)](#get-Item-java.lang.String-boolean-) | Returns one top-level ruleset by specified textual representation of selector or throws an exception or returns NULL, if it is not found |
| [get_Item(ISelector selector, boolean throwIfNotFound)](#get-Item-com.groupdocs.editor.htmlcss.css.selectors.ISelector-boolean-) | Returns one top-level ruleset by specified selector or throws an exception or returns NULL, if it is not found |
| [getByAtRuleTypes(int type, boolean throwIfNotFound)](#getByAtRuleTypes-int-boolean-) | Returns one first occured (from beginning) at-rule of specified type or throws an exception or returns NULL, if it is not found |
| [size()](#size--) | Returns an overall count of all top-level rules inside this CssOm, including all at-rules and rulesets |
| [isReadOnly()](#isReadOnly--) |  |
| [tryAdd(ICssRule rule)](#tryAdd-com.groupdocs.editor.htmlcss.css.ICssRule-) | Adds a specified rule to this CssOm, if it is a ruleset and is not already present here, or does nothing, if this CssOm already contains ruleset with the same selector or at-rule with same type and prelude |
| [add(ICssRule rule)](#add-com.groupdocs.editor.htmlcss.css.ICssRule-) | Adds a specified rule to this CssOm or throws an exception, if this at-rule or ruleset is already present here |
| [upsertIdentical(Ruleset ruleset)](#upsertIdentical-com.groupdocs.editor.htmlcss.css.Ruleset-) | Adds specified ruleset to this CssOm, if it is not already present here, or checks, whether it is fully identical to those, which is already present. |
| [remove(ICssRule rule)](#remove-com.groupdocs.editor.htmlcss.css.ICssRule-) | Removes specified rule from this CssOm instance and returns the result of the operation |
| [clear()](#clear--) | Removes all content (rulesets and at-rules) from this CssOm instance |
| [copyTo(ICssRule[] array, int arrayIndex)](#copyTo-com.groupdocs.editor.htmlcss.css.ICssRule---int-) | Copies all items from this CssOm instance into specified array, starting from specified offset in this array |
| [contains(ICssRule rule)](#contains-com.groupdocs.editor.htmlcss.css.ICssRule-) | Determines whether tis CssOm instance contains 1) ruleset, which has the same selector, or 2) the same at-rule |
| [containsRuleset(String selector)](#containsRuleset-java.lang.String-) | Determines whether this CssOm contains a top-level ruleset with specified selector |
| [containsAtRule(int type)](#containsAtRule-int-) | Determines whether this CssOm contains a top-level at-rule of specified type |
| [serialize(ISerializationOptions serializationOptions)](#serialize-com.groupdocs.editor.htmlcss.serialization.ISerializationOptions-) |  |
| [serialize(ISerializationOptions serializationOptions, System.IO.TextWriter output)](#serialize-com.groupdocs.editor.htmlcss.serialization.ISerializationOptions-com.aspose.ms.System.IO.TextWriter-) |  |
| [toResource(ISerializationOptions serializationOptions)](#toResource-com.groupdocs.editor.htmlcss.serialization.ISerializationOptions-) | Serializes this instance of the CSSOM to the text using specified options and returns it as a CSS resource |
| [iterator()](#iterator--) |  |
| [removeItem(ICssRule item)](#removeItem-com.groupdocs.editor.htmlcss.css.ICssRule-) |  |
| [addItem(ICssRule item)](#addItem-com.groupdocs.editor.htmlcss.css.ICssRule-) |  |
| [containsItem(ICssRule item)](#containsItem-com.groupdocs.editor.htmlcss.css.ICssRule-) |  |
| [copyToTArray(ICssRule[] item, int i)](#copyToTArray-com.groupdocs.editor.htmlcss.css.ICssRule---int-) |  |
### CssOm(String name) {#CssOm-java.lang.String-}
```
public CssOm(String name)
```


Creates a new instance with specified name and empty content

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Stylesheet name, which cannot be NULL, empty or whitespaces |

### getName() {#getName--}
```
public final String getName()
```


Returns a textual name of this CSSOM instance, which is specified during its creation and cannot be changed. This is usually filename of the CSS file.

**Returns:**
java.lang.String
### getRulesets() {#getRulesets--}
```
public final RulesetList getRulesets()
```


Returns all top-level rulesets, which are located in this CssOm instance, but without at-rules

**Returns:**
[RulesetList](../../com.groupdocs.editor.htmlcss.css/rulesetlist)
### getAtRules() {#getAtRules--}
```
public final System.Collections.Generic.List<IAtRule> getAtRules()
```


Returns all top-level at-rules, which are located in this CssOm instance, but without rulesets

**Returns:**
com.aspose.ms.System.Collections.Generic.List<com.groupdocs.editor.htmlcss.css.atrules.IAtRule>
### getCharset() {#getCharset--}
```
public final System.Text.Encoding getCharset()
```


Allows to obtain or specify a charset for this CSSOM, which will be transformed into the @charset at-rule during serialization. NULL represents an absence of @charset.

**Returns:**
com.aspose.ms.System.Text.Encoding
### setCharset(System.Text.Encoding value) {#setCharset-com.aspose.ms.System.Text.Encoding-}
```
public final void setCharset(System.Text.Encoding value)
```


Allows to obtain or specify a charset for this CSSOM, which will be transformed into the @charset at-rule during serialization. NULL represents an absence of @charset.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | com.aspose.ms.System.Text.Encoding |  |

### get_Item(String selector, boolean throwIfNotFound) {#get-Item-java.lang.String-boolean-}
```
public final Ruleset get_Item(String selector, boolean throwIfNotFound)
```


Returns one top-level ruleset by specified textual representation of selector or throws an exception or returns NULL, if it is not found

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| selector | java.lang.String |  |
| throwIfNotFound | boolean | Determines how to act when top-level ruleset with specified selector was not found: throw an KeyNotFoundException if 'true' or return NULL if 'false' |

**Returns:**
[Ruleset](../../com.groupdocs.editor.htmlcss.css/ruleset) - One Ruleset instance if found or NULL, if not found
### get_Item(ISelector selector, boolean throwIfNotFound) {#get-Item-com.groupdocs.editor.htmlcss.css.selectors.ISelector-boolean-}
```
public final Ruleset get_Item(ISelector selector, boolean throwIfNotFound)
```


Returns one top-level ruleset by specified selector or throws an exception or returns NULL, if it is not found

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| selector | [ISelector](../../com.groupdocs.editor.htmlcss.css.selectors/iselector) | Any selector, which cannot be NULL |
| throwIfNotFound | boolean | Determines how to act when top-level ruleset with specified selector was not found: throw an KeyNotFoundException if 'true' or return NULL if 'false' |

**Returns:**
[Ruleset](../../com.groupdocs.editor.htmlcss.css/ruleset) - One Ruleset instance if found or NULL, if not found
### getByAtRuleTypes(int type, boolean throwIfNotFound) {#getByAtRuleTypes-int-boolean-}
```
public final IAtRule getByAtRuleTypes(int type, boolean throwIfNotFound)
```


Returns one first occured (from beginning) at-rule of specified type or throws an exception or returns NULL, if it is not found

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| type | int | Type of the desired at-rule |
| throwIfNotFound | boolean | Determines how to act when top-level at-rule of specified type was not found: throw an KeyNotFoundException if 'true' or return NULL if 'false' |

**Returns:**
[IAtRule](../../com.groupdocs.editor.htmlcss.css.atrules/iatrule) - One IAtRule instance if found or NULL, if not found
### size() {#size--}
```
public final int size()
```


Returns an overall count of all top-level rules inside this CssOm, including all at-rules and rulesets

**Returns:**
int
### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```




**Returns:**
boolean
### tryAdd(ICssRule rule) {#tryAdd-com.groupdocs.editor.htmlcss.css.ICssRule-}
```
public final boolean tryAdd(ICssRule rule)
```


Adds a specified rule to this CssOm, if it is a ruleset and is not already present here, or does nothing, if this CssOm already contains ruleset with the same selector or at-rule with same type and prelude

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rule | [ICssRule](../../com.groupdocs.editor.htmlcss.css/icssrule) | Any ruleset or at-rule. If NULL - it will be not added and 'false' will be returned. |

**Returns:**
boolean - True if specified ruleset or at-rule was added; false, if it was not added because specified rule is ruleset, and there is another (or the same) ruleset with identical selector there; or specified rule is NULL
### add(ICssRule rule) {#add-com.groupdocs.editor.htmlcss.css.ICssRule-}
```
public final void add(ICssRule rule)
```


Adds a specified rule to this CssOm or throws an exception, if this at-rule or ruleset is already present here

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rule | [ICssRule](../../com.groupdocs.editor.htmlcss.css/icssrule) | Any ruleset or at-rule. If NULL - it will be not added. |

### upsertIdentical(Ruleset ruleset) {#upsertIdentical-com.groupdocs.editor.htmlcss.css.Ruleset-}
```
public final boolean upsertIdentical(Ruleset ruleset)
```


Adds specified ruleset to this CssOm, if it is not already present here, or checks, whether it is fully identical to those, which is already present. If yes, does nothing; otherwise throws an exception.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| ruleset | [Ruleset](../../com.groupdocs.editor.htmlcss.css/ruleset) | Ruleset, which should be checked and added. Cannot be NULL. |

**Returns:**
boolean - True if specified ruleset was not present and thus was added; false is exactly the same ruleset (with identical selector and declaration block) was already present
### remove(ICssRule rule) {#remove-com.groupdocs.editor.htmlcss.css.ICssRule-}
```
public final boolean remove(ICssRule rule)
```


Removes specified rule from this CssOm instance and returns the result of the operation

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rule | [ICssRule](../../com.groupdocs.editor.htmlcss.css/icssrule) | Rule (ruleset or at-rule), which should be removed. If it is a ruleset, then it will be removed by its selector, without taking into account its content. |

**Returns:**
boolean - Returns 'true' if rule was found and successfully removed or 'false' if rule was not found and thus not removed.
### clear() {#clear--}
```
public final void clear()
```


Removes all content (rulesets and at-rules) from this CssOm instance

### copyTo(ICssRule[] array, int arrayIndex) {#copyTo-com.groupdocs.editor.htmlcss.css.ICssRule---int-}
```
public final void copyTo(ICssRule[] array, int arrayIndex)
```


Copies all items from this CssOm instance into specified array, starting from specified offset in this array

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| array | com.groupdocs.editor.htmlcss.css.ICssRule[] |  |
| arrayIndex | int |  |

### contains(ICssRule rule) {#contains-com.groupdocs.editor.htmlcss.css.ICssRule-}
```
public final boolean contains(ICssRule rule)
```


Determines whether tis CssOm instance contains 1) ruleset, which has the same selector, or 2) the same at-rule

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rule | [ICssRule](../../com.groupdocs.editor.htmlcss.css/icssrule) |  |

**Returns:**
boolean - Returns 'true' if such item is found or 'false' - if not found
### containsRuleset(String selector) {#containsRuleset-java.lang.String-}
```
public final boolean containsRuleset(String selector)
```


Determines whether this CssOm contains a top-level ruleset with specified selector

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| selector | java.lang.String | Textual representation of the selector |

**Returns:**
boolean - 
### containsAtRule(int type) {#containsAtRule-int-}
```
public final boolean containsAtRule(int type)
```


Determines whether this CssOm contains a top-level at-rule of specified type

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| type | int | Target type of the at-rule |

**Returns:**
boolean - 
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

### toResource(ISerializationOptions serializationOptions) {#toResource-com.groupdocs.editor.htmlcss.serialization.ISerializationOptions-}
```
public final CssText toResource(ISerializationOptions serializationOptions)
```


Serializes this instance of the CSSOM to the text using specified options and returns it as a CSS resource

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| serializationOptions | [ISerializationOptions](../../com.groupdocs.editor.htmlcss.serialization/iserializationoptions) |  |

**Returns:**
[CssText](../../com.groupdocs.editor.htmlcss.resources.textual/csstext) - 
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ICssRule> iterator()
```




**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.groupdocs.editor.htmlcss.css.ICssRule>
### removeItem(ICssRule item) {#removeItem-com.groupdocs.editor.htmlcss.css.ICssRule-}
```
public boolean removeItem(ICssRule item)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [ICssRule](../../com.groupdocs.editor.htmlcss.css/icssrule) |  |

**Returns:**
boolean
### addItem(ICssRule item) {#addItem-com.groupdocs.editor.htmlcss.css.ICssRule-}
```
public void addItem(ICssRule item)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [ICssRule](../../com.groupdocs.editor.htmlcss.css/icssrule) |  |

### containsItem(ICssRule item) {#containsItem-com.groupdocs.editor.htmlcss.css.ICssRule-}
```
public boolean containsItem(ICssRule item)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [ICssRule](../../com.groupdocs.editor.htmlcss.css/icssrule) |  |

**Returns:**
boolean
### copyToTArray(ICssRule[] item, int i) {#copyToTArray-com.groupdocs.editor.htmlcss.css.ICssRule---int-}
```
public void copyToTArray(ICssRule[] item, int i)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | com.groupdocs.editor.htmlcss.css.ICssRule[] |  |
| i | int |  |

