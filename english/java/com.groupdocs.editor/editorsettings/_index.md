---
title: EditorSettings
second_title: GroupDocs.Editor for Java API Reference
description:  Defines settings for customizing  behaviour.
type: docs
weight: 12
url: /java/com.groupdocs.editor/editorsettings/
---
**Inheritance:**
java.lang.Object
```
public final class EditorSettings
```

Defines settings for customizing [Editor](../../com.groupdocs.editor/editor) behaviour.
## Constructors

| Constructor | Description |
| --- | --- |
| [EditorSettings()](#EditorSettings--) |  |
## Methods

| Method | Description |
| --- | --- |
| [getCache()](#getCache--) | Allows to specify custom user-defined caching system, that will be used by GroupDocs.Editor to store intermediate internal data |
| [setCache(ICache value)](#setCache-com.groupdocs.editor.caching.ICache-) | Allows to specify custom user-defined caching system, that will be used by GroupDocs.Editor to store intermediate internal data |
| [getLogger()](#getLogger--) | Allows to specify custom user-defined logging system, that will obtain messages from GroupDocs.Editor |
| [setLogger(ILogger value)](#setLogger-com.groupdocs.editor.logging.ILogger-) | Allows to specify custom user-defined logging system, that will obtain messages from GroupDocs.Editor |
### EditorSettings() {#EditorSettings--}
```
public EditorSettings()
```


### getCache() {#getCache--}
```
public final ICache getCache()
```


Allows to specify custom user-defined caching system, that will be used by GroupDocs.Editor to store intermediate internal data

**Returns:**
[ICache](../../com.groupdocs.editor.caching/icache) - 
### setCache(ICache value) {#setCache-com.groupdocs.editor.caching.ICache-}
```
public final void setCache(ICache value)
```


Allows to specify custom user-defined caching system, that will be used by GroupDocs.Editor to store intermediate internal data

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ICache](../../com.groupdocs.editor.caching/icache) |  |

### getLogger() {#getLogger--}
```
public final ILogger getLogger()
```


Allows to specify custom user-defined logging system, that will obtain messages from GroupDocs.Editor

**Returns:**
[ILogger](../../com.groupdocs.editor.logging/ilogger) - 
### setLogger(ILogger value) {#setLogger-com.groupdocs.editor.logging.ILogger-}
```
public final void setLogger(ILogger value)
```


Allows to specify custom user-defined logging system, that will obtain messages from GroupDocs.Editor

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ILogger](../../com.groupdocs.editor.logging/ilogger) |  |

