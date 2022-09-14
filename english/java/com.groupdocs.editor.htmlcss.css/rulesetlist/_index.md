---
title: RulesetList
second_title: GroupDocs.Editor for Java API Reference
description:  Ordered indexed list of rulesets which are accessible by selector or by
 positive or negative index.
type: docs
weight: 15
url: /java/com.groupdocs.editor.htmlcss.css/rulesetlist/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public final class RulesetList implements System.Collections.Generic.IGenericEnumerable<Ruleset>
```

Ordered indexed list of rulesets, which are accessible by selector or by positive or negative index.
## Constructors

| Constructor | Description |
| --- | --- |
| [RulesetList()](#RulesetList--) |  |
| [RulesetList(int capacity)](#RulesetList-int-) |  |
## Methods

| Method | Description |
| --- | --- |
| [getCount()](#getCount--) | Returns count of rulesets in this ruleset list |
| [append(Ruleset ruleset)](#append-com.groupdocs.editor.htmlcss.css.Ruleset-) |  |
| [prepend(Ruleset ruleset)](#prepend-com.groupdocs.editor.htmlcss.css.Ruleset-) |  |
| [insertAt(int index, Ruleset ruleset)](#insertAt-int-com.groupdocs.editor.htmlcss.css.Ruleset-) | Inserts a new ruleset at specified position with specified 1-based index or appends at the end, if specified index is greater then max existing items. |
| [upsert(Ruleset newRuleset, boolean overwriteExistingDeclarations)](#upsert-com.groupdocs.editor.htmlcss.css.Ruleset-boolean-) | Upserts the input presentation into this RulesetList by appending it if not exists or merging its declarations list into existing in accordance to \`\`\` overwriteExistingDeclarations \`\`\` parameter value |
| [contains(ISelector selector)](#contains-com.groupdocs.editor.htmlcss.css.selectors.ISelector-) | Determines whether ruleset with specified selector exists in this ruleset list |
| [indexOf(ISelector selector)](#indexOf-com.groupdocs.editor.htmlcss.css.selectors.ISelector-) | Returns 1-based index of ruleset with specified selector, if it exists, or returns 0, if it doesn't exist in this ruleset list |
| [get_Item(int index)](#get-Item-int-) | Getter allows to obtain a ruleset, and setter allows to replace (update) a ruleset by specified 1-based positive or negative index. |
| [set_Item(int index, Ruleset value)](#set-Item-int-com.groupdocs.editor.htmlcss.css.Ruleset-) | Getter allows to obtain a ruleset, and setter allows to replace (update) a ruleset by specified 1-based positive or negative index. |
| [get_Item(String selector, boolean throwIfNotFound)](#get-Item-java.lang.String-boolean-) | Returns a ruleset by specified selector. |
| [get_Item(ISelector selector, boolean throwIfNotFound)](#get-Item-com.groupdocs.editor.htmlcss.css.selectors.ISelector-boolean-) | Returns a ruleset by specified selector. |
| [deleteAt(int index)](#deleteAt-int-) | Deletes and returns one ruleset at specified 1-based positive or negative index |
| [delete(ISelector selector)](#delete-com.groupdocs.editor.htmlcss.css.selectors.ISelector-) | Deletes a ruleset with specified selector from this ruleset list and returns a status of this deletion |
| [clear()](#clear--) | Deletes all rulesets from this ruleset list and returns their count |
| [iterator()](#iterator--) | Returns a collection-specific enumerator |
### RulesetList() {#RulesetList--}
```
public RulesetList()
```


### RulesetList(int capacity) {#RulesetList-int-}
```
public RulesetList(int capacity)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| capacity | int |  |

### getCount() {#getCount--}
```
public final int getCount()
```


Returns count of rulesets in this ruleset list

**Returns:**
int
### append(Ruleset ruleset) {#append-com.groupdocs.editor.htmlcss.css.Ruleset-}
```
public final void append(Ruleset ruleset)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| ruleset | [Ruleset](../../com.groupdocs.editor.htmlcss.css/ruleset) |  |

### prepend(Ruleset ruleset) {#prepend-com.groupdocs.editor.htmlcss.css.Ruleset-}
```
public final void prepend(Ruleset ruleset)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| ruleset | [Ruleset](../../com.groupdocs.editor.htmlcss.css/ruleset) |  |

### insertAt(int index, Ruleset ruleset) {#insertAt-int-com.groupdocs.editor.htmlcss.css.Ruleset-}
```
public final int insertAt(int index, Ruleset ruleset)
```


Inserts a new ruleset at specified position with specified 1-based index or appends at the end, if specified index is greater then max existing items. If this ruleset list contains ruleset with the same selector, an exception will be thrown.

--------------------

> ```
> If there are 5 elements with indexes [1|-5...2|-4...3|-3...4|-2...5|-1]:
>  6...7...8... or -1   => set 6th and shift nothing, because 6th is last  APPEND
>  5 or -2              => set 5th and shift old (5th)                     to new (6th)
>  4 or -3              => set 4th and shift old (4th, 5th)                to new (5th, 6th)
>  3 or -4              => set 3rd and shift old (3rd, 4th, 5th)           to new (4th, 5th, 6th)
>  2 or -5              => set 2nd and shift old (2nd, 3rd, 4th, 5th)      to new (3rd, 4th, 5th, 6th)
>  1 or -6...-7...-8... => set 1st and shift old (1st, 2nd, 3rd, 4th, 5th) to new (2nd, 3rd, 4th, 5th, 6th)  PREPEND
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | 1-based index, into which new specified ruleset should be inserted. If 1 - ruleset will be prepended at the beginning of the list. May be negative - in such case it is counted from end. If exceeds the number of existing elements, ruleset will be append (if index is positive) or prepend (if index is negative). Value 0 is the only value, which is prohibited. |
| ruleset | [Ruleset](../../com.groupdocs.editor.htmlcss.css/ruleset) | New ruleset, which should be inserted. Cannot be NULL. If selector of this ruleset list is present in some other ruleset in this list, the exception will be thrown. |

**Returns:**
int - Actual 1-based positive index, in which the ruleset was inserted.
### upsert(Ruleset newRuleset, boolean overwriteExistingDeclarations) {#upsert-com.groupdocs.editor.htmlcss.css.Ruleset-boolean-}
```
public final void upsert(Ruleset newRuleset, boolean overwriteExistingDeclarations)
```


Upserts the input presentation into this RulesetList by appending it if not exists or merging its declarations list into existing in accordance to \`\`\` overwriteExistingDeclarations \`\`\` parameter value

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| newRuleset | [Ruleset](../../com.groupdocs.editor.htmlcss.css/ruleset) | New ruleset, which should be upserted. Cannot be null. |
| overwriteExistingDeclarations | boolean | Specifies what to do if this RulesetList already contains a ruleset with the same selectors, and there are declarations with the same name in both existing and new ruleset. Overwrites their values on 'true' or throws an exception on 'false'. |

### contains(ISelector selector) {#contains-com.groupdocs.editor.htmlcss.css.selectors.ISelector-}
```
public final boolean contains(ISelector selector)
```


Determines whether ruleset with specified selector exists in this ruleset list

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| selector | [ISelector](../../com.groupdocs.editor.htmlcss.css.selectors/iselector) | Any selector. Cannot be NULL. |

**Returns:**
boolean - 
### indexOf(ISelector selector) {#indexOf-com.groupdocs.editor.htmlcss.css.selectors.ISelector-}
```
public final int indexOf(ISelector selector)
```


Returns 1-based index of ruleset with specified selector, if it exists, or returns 0, if it doesn't exist in this ruleset list

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| selector | [ISelector](../../com.groupdocs.editor.htmlcss.css.selectors/iselector) |  |

**Returns:**
int - Strictly positive index when found; 0 when doesn't found.
### get_Item(int index) {#get-Item-int-}
```
public final Ruleset get_Item(int index)
```


Getter allows to obtain a ruleset, and setter allows to replace (update) a ruleset by specified 1-based positive or negative index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | 1-based strictly positive or negative index, which cannot be 0 and cannot exceed the amount of elements in this ruleset list. Value: New ruleset, which should be injected into specified position. Its selector should not be present in any of existing rulesets, except old ruleset with the same selector will be replaced onto this new. |

**Returns:**
[Ruleset](../../com.groupdocs.editor.htmlcss.css/ruleset) - Getter returns one ruleset, which cannot be NULL.
### set_Item(int index, Ruleset value) {#set-Item-int-com.groupdocs.editor.htmlcss.css.Ruleset-}
```
public final void set_Item(int index, Ruleset value)
```


Getter allows to obtain a ruleset, and setter allows to replace (update) a ruleset by specified 1-based positive or negative index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | 1-based strictly positive or negative index, which cannot be 0 and cannot exceed the amount of elements in this ruleset list. Value: New ruleset, which should be injected into specified position. Its selector should not be present in any of existing rulesets, except old ruleset with the same selector will be replaced onto this new. |
| value | [Ruleset](../../com.groupdocs.editor.htmlcss.css/ruleset) |  |

### get_Item(String selector, boolean throwIfNotFound) {#get-Item-java.lang.String-boolean-}
```
public final Ruleset get_Item(String selector, boolean throwIfNotFound)
```


Returns a ruleset by specified selector. Additional flag indicates how to cope with situation when this ruleset list doesn't contains a ruleset with specified selector.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| selector | java.lang.String | Selector as a string. Throws exception if string contains syntactically invalid selector. |
| throwIfNotFound | boolean | Determines how to cope with situation when this ruleset list doesn't contains a ruleset with specified selector: throw exception when 'true' or return NULL when 'false'. |

**Returns:**
[Ruleset](../../com.groupdocs.editor.htmlcss.css/ruleset) - One instance of Ruleset, which may be NULL only when it was not found \`\`\` *and* \`\`\` \`\`\` throwIfNotFound \`\`\` flag is set to 'true'
### get_Item(ISelector selector, boolean throwIfNotFound) {#get-Item-com.groupdocs.editor.htmlcss.css.selectors.ISelector-boolean-}
```
public final Ruleset get_Item(ISelector selector, boolean throwIfNotFound)
```


Returns a ruleset by specified selector. Additional flag indicates how to cope with situation when this ruleset list doesn't contains a ruleset with specified selector.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| selector | [ISelector](../../com.groupdocs.editor.htmlcss.css.selectors/iselector) | Selector instance, which cannot be NULL |
| throwIfNotFound | boolean | Determines how to cope with situation when this ruleset list doesn't contains a ruleset with specified selector: throw exception when 'true' or return NULL when 'false'. |

**Returns:**
[Ruleset](../../com.groupdocs.editor.htmlcss.css/ruleset) - One instance of Ruleset, which may be NULL only when it was not found \`\`\` *and* \`\`\` \`\`\` throwIfNotFound \`\`\` flag is set to 'true'
### deleteAt(int index) {#deleteAt-int-}
```
public final Ruleset deleteAt(int index)
```


Deletes and returns one ruleset at specified 1-based positive or negative index

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | 1-based positive or negative index, which cannot be 0 and cannot exceed the amount of elements in this ruleset list |

**Returns:**
[Ruleset](../../com.groupdocs.editor.htmlcss.css/ruleset) - Non-null Ruleset instance, which was deleted from this RulesetList
### delete(ISelector selector) {#delete-com.groupdocs.editor.htmlcss.css.selectors.ISelector-}
```
public final boolean delete(ISelector selector)
```


Deletes a ruleset with specified selector from this ruleset list and returns a status of this deletion

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| selector | [ISelector](../../com.groupdocs.editor.htmlcss.css.selectors/iselector) |  |

**Returns:**
boolean - True if was successfully deleted, false if not found
### clear() {#clear--}
```
public final int clear()
```


Deletes all rulesets from this ruleset list and returns their count

**Returns:**
int - Count of rulesets, which were deleted
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<Ruleset> iterator()
```


Returns a collection-specific enumerator

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.groupdocs.editor.htmlcss.css.Ruleset> - 
