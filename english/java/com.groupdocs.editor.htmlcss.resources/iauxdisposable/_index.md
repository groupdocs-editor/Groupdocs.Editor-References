---
title: IAuxDisposable
second_title: GroupDocs.Editor for Java API Reference
description: Expands the standard System.IDisposable interface allows to obtain a current state of an object and subscribe to disposing event
type: docs
weight: 11
url: /java/com.groupdocs.editor.htmlcss.resources/iauxdisposable/
---
**All Implemented Interfaces:**
[com.groupdocs.editor.interfaces.IDisposable](../../com.groupdocs.editor.interfaces/idisposable)
```
public interface IAuxDisposable extends IDisposable
```

Expands the standard System.IDisposable interface, allows to obtain a current state of an object and subscribe to disposing event
## Fields

| Field | Description |
| --- | --- |
| [Disposed](#Disposed) | Occurs when object is disposed |
## Methods

| Method | Description |
| --- | --- |
| [isDisposed()](#isDisposed--) | Determines whether a resource is closed (true) or not (false |
### Disposed {#Disposed}
```
public static final Event<EventHandler> Disposed
```


Occurs when object is disposed

### isDisposed() {#isDisposed--}
```
public abstract boolean isDisposed()
```


Determines whether a resource is closed (true) or not (false

**Returns:**
boolean
