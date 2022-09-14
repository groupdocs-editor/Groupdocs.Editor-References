---
title: ICssDeclaration
second_title: GroupDocs.Editor for Java API Reference
description: Common interface for all CSS declarations including short-hand and long-hand
type: docs
weight: 17
url: /java/com.groupdocs.editor.htmlcss.css/icssdeclaration/
---
**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.serialization.ISerializable](../../com.groupdocs.editor.htmlcss.serialization/iserializable)
```
public interface ICssDeclaration extends ISerializable
```

Common interface for all CSS declarations, including short-hand and long-hand
## Methods

| Method | Description |
| --- | --- |
| [getProperty()](#getProperty--) | In implementing type should return a property name as a string |
| [getValue()](#getValue--) | In implementing type should return a value in a default string form, without affecting serialization options |
| [isDefault()](#isDefault--) | In implementing type should define, whether a current value is a default value of a declaration, or not |
| [isGlobal()](#isGlobal--) | In implementing type should define, whether a current value is a global value of a declaration (inherit [initial, unset]), or not |
| [getInherited()](#getInherited--) | All CSS declarations are divided on inherited or non-inherited, what is represented by this property |
| [getAnimationType()](#getAnimationType--) | All CSS properties have at least one animation type, which determines, how they can be animated |
### getProperty() {#getProperty--}
```
public abstract String getProperty()
```


In implementing type should return a property name as a string

**Returns:**
java.lang.String
### getValue() {#getValue--}
```
public abstract String getValue()
```


In implementing type should return a value in a default string form, without affecting serialization options

**Returns:**
java.lang.String
### isDefault() {#isDefault--}
```
public abstract boolean isDefault()
```


In implementing type should define, whether a current value is a default value of a declaration, or not

**Returns:**
boolean
### isGlobal() {#isGlobal--}
```
public abstract boolean isGlobal()
```


In implementing type should define, whether a current value is a global value of a declaration (inherit [initial, unset]), or not

**Returns:**
boolean
### getInherited() {#getInherited--}
```
public abstract boolean getInherited()
```


All CSS declarations are divided on inherited or non-inherited, what is represented by this property

--------------------

https://developer.mozilla.org/en-US/docs/Web/CSS/inheritance

**Returns:**
boolean
### getAnimationType() {#getAnimationType--}
```
public abstract int getAnimationType()
```


All CSS properties have at least one animation type, which determines, how they can be animated

**Returns:**
int
