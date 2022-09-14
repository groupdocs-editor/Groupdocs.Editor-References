---
title: EventHandler
second_title: GroupDocs.Editor for Java API Reference
description: 
type: docs
weight: 12
url: /java/com.groupdocs.editor.handler/eventhandler/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.Delegate, com.aspose.ms.System.MulticastDelegate
```
public abstract class EventHandler extends System.MulticastDelegate
```
## Constructors

| Constructor | Description |
| --- | --- |
| [EventHandler()](#EventHandler--) |  |
## Methods

| Method | Description |
| --- | --- |
| [invoke(Object signature, EventArgs args)](#invoke-java.lang.Object-com.groupdocs.editor.handler.EventArgs-) |  |
| [beginInvoke(Object signature, EventArgs args, System.AsyncCallback callback, Object state)](#beginInvoke-java.lang.Object-com.groupdocs.editor.handler.EventArgs-com.aspose.ms.System.AsyncCallback-java.lang.Object-) |  |
| [endInvoke(System.IAsyncResult result)](#endInvoke-com.aspose.ms.System.IAsyncResult-) |  |
### EventHandler() {#EventHandler--}
```
public EventHandler()
```


### invoke(Object signature, EventArgs args) {#invoke-java.lang.Object-com.groupdocs.editor.handler.EventArgs-}
```
public abstract void invoke(Object signature, EventArgs args)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| signature | java.lang.Object |  |
| args | [EventArgs](../../com.groupdocs.editor.handler/eventargs) |  |

### beginInvoke(Object signature, EventArgs args, System.AsyncCallback callback, Object state) {#beginInvoke-java.lang.Object-com.groupdocs.editor.handler.EventArgs-com.aspose.ms.System.AsyncCallback-java.lang.Object-}
```
public final System.IAsyncResult beginInvoke(Object signature, EventArgs args, System.AsyncCallback callback, Object state)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| signature | java.lang.Object |  |
| args | [EventArgs](../../com.groupdocs.editor.handler/eventargs) |  |
| callback | com.aspose.ms.System.AsyncCallback |  |
| state | java.lang.Object |  |

**Returns:**
com.aspose.ms.System.IAsyncResult
### endInvoke(System.IAsyncResult result) {#endInvoke-com.aspose.ms.System.IAsyncResult-}
```
public final void endInvoke(System.IAsyncResult result)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| result | com.aspose.ms.System.IAsyncResult |  |

