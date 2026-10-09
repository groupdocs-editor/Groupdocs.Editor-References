---
title: "IAuxDisposable"
second_title: "GroupDocs.Editor für Node.js über Java API-Referenz"
description: "Erweitert das standardmäßige IDisposable‑Interface und ermöglicht das Abrufen des aktuellen Zustands eines Objekts sowie das Abonnieren des Entsorgungs‑Events"
type: docs
weight: 11
url: /de/nodejs-java/com.groupdocs.editor.htmlcss.resources/iauxdisposable/
---
**All Implemented Interfaces:**
[com.groupdocs.editor.interfaces.IDisposable](../../com.groupdocs.editor.interfaces/idisposable)
```
public interface IAuxDisposable extends IDisposable
```

Erweitert das standardmäßige IDisposable‑Interface, ermöglicht das Abrufen eines aktuellen
Zustand eines Objekts und das Abonnieren des Entsorgungs‑Events

## Felder

| Feld | Beschreibung |
| --- | --- |
|  | [Disposed](#Disposed) | Tritt auf, wenn das Objekt entsorgt wird |
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [isDisposed()](#isDisposed--) | Bestimmt, ob eine Ressource geschlossen ist (true) oder nicht (false |
|
### Disposed {#Disposed}
```
public static final Event<EventHandler> Disposed
```


Tritt auf, wenn das Objekt entsorgt wird


### isDisposed() {#isDisposed--}
```
public abstract boolean isDisposed()
```


Bestimmt, ob eine Ressource geschlossen ist (true) oder nicht (false


**Returns:**
boolesch
