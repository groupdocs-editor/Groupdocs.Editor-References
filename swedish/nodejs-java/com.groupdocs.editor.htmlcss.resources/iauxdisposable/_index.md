---
title: "IAuxDisposable"
second_title: "GroupDocs.Editor för Node.js via Java API-referens"
description: "Utökar det standardmässiga IDisposable‑gränssnittet och möjliggör att erhålla ett aktuellt tillstånd för ett objekt samt prenumerera på avstängningshändelsen"
type: docs
weight: 11
url: /sv/nodejs-java/com.groupdocs.editor.htmlcss.resources/iauxdisposable/
---
**All Implemented Interfaces:**
[com.groupdocs.editor.interfaces.IDisposable](../../com.groupdocs.editor.interfaces/idisposable)
```
public interface IAuxDisposable extends IDisposable
```

Utökar det standardmässiga IDisposable‑gränssnittet, möjliggör att erhålla ett aktuellt
tillstånd för ett objekt och prenumerera på avstängningshändelsen

## Fält

| Fält | Beskrivning |
| --- | --- |
|  | [Disposed](#Disposed) | Uppstår när objektet har avstängts |
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [isDisposed()](#isDisposed--) | Bestämmer om en resurs är stängd (true) eller inte (false |
|
### Disposed {#Disposed}
```
public static final Event<EventHandler> Disposed
```


Uppstår när objektet har avstängts


### isDisposed() {#isDisposed--}
```
public abstract boolean isDisposed()
```


Bestämmer om en resurs är stängd (true) eller inte (false


**Returns:**
boolean
