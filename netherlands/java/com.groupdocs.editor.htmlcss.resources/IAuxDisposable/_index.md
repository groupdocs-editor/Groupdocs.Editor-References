---
title: "IAuxDisposable"
second_title: "GroupDocs.Editor for Java API-referentie"
description: "Breidt de standaard IDisposable-interface uit, waardoor de huidige status van een object kan worden verkregen en kan worden geabonneerd op het verwijderings‑event"
type: docs
weight: 11
url: /nl/java/com.groupdocs.editor.htmlcss.resources/iauxdisposable/
---
**All Implemented Interfaces:**
[com.groupdocs.editor.interfaces.IDisposable](../../com.groupdocs.editor.interfaces/idisposable)
```
public interface IAuxDisposable extends IDisposable
```

Breidt de standaard IDisposable-interface uit, maakt het mogelijk om een huidige te verkrijgen
status van een object en zich abonneren op het verwijderings‑event

## Velden

| Veld | Beschrijving |
| --- | --- |
|  | [Disposed](#Disposed) | Vindt plaats wanneer het object wordt verwijderd |
|
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [isDisposed()](#isDisposed--) | Bepaalt of een resource gesloten is (true) of niet (false |
|
### Disposed {#Disposed}
```
public static final Event<EventHandler> Disposed
```


Vindt plaats wanneer het object wordt verwijderd


### isDisposed() {#isDisposed--}
```
public abstract boolean isDisposed()
```


Bepaalt of een resource gesloten is (true) of niet (false


**Returns:**
boolean
