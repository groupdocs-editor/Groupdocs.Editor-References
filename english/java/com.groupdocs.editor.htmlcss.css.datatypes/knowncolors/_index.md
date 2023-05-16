---
title: ArgbColor.KnownColors
second_title: GroupDocs.Editor for Java API Reference
description: Contains all known colors that have fixed unique name and value in CSS standart
type: docs
weight: 10
url: /java/com.groupdocs.editor.htmlcss.css.datatypes/argbcolor.knowncolors/
---
**Inheritance:**
java.lang.Object
```
public static class ArgbColor.KnownColors
```

Contains all "known colors", that have fixed unique name and value in CSS standart

--------------------

See also: https://developer.mozilla.org/en-US/docs/Web/CSS/named-color
## Constructors

| Constructor | Description |
| --- | --- |
| [KnownColors()](#KnownColors--) |  |
## Fields

| Field | Description |
| --- | --- |
| [Empty](#Empty) | Returns an empty color, which has no channels info and is fully transparent. |
| [Transparent](#Transparent) | Fully transparent empty color. |
## Methods

| Method | Description |
| --- | --- |
| [tryFind(String keyword, ArgbColor[] output)](#tryFind-java.lang.String-com.groupdocs.editor.htmlcss.css.datatypes.ArgbColor---) | Tries to find a color by its string name |
### KnownColors() {#KnownColors--}
```
public KnownColors()
```


### Empty {#Empty}
```
public static final ArgbColor Empty
```


Returns an empty color, which has no channels info and is fully transparent. Same as '\#Transparent.Transparent'. Default value.

### Transparent {#Transparent}
```
public static final ArgbColor Transparent
```


Fully transparent empty color. The same as default '\#Empty.Empty' color value.

### tryFind(String keyword, ArgbColor[] output) {#tryFind-java.lang.String-com.groupdocs.editor.htmlcss.css.datatypes.ArgbColor---}
```
public static boolean tryFind(String keyword, ArgbColor[] output)
```


Tries to find a color by its string name

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| keyword | java.lang.String | A color name |
| output | [ArgbColor\[\]](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) | The resultant color value on success or \#Transparent.Transparent value on failure |

**Returns:**
boolean - True if color was successfully found by its name, or false otherwise
