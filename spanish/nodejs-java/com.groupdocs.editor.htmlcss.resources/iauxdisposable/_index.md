---
title: "IAuxDisposable"
second_title: "Referencia de API de GroupDocs.Editor para Node.js vía Java"
description: "Amplía la interfaz estándar IDisposable y permite obtener el estado actual de un objeto y suscribirse al evento de eliminación"
type: docs
weight: 11
url: /es/nodejs-java/com.groupdocs.editor.htmlcss.resources/iauxdisposable/
---
**All Implemented Interfaces:**
[com.groupdocs.editor.interfaces.IDisposable](../../com.groupdocs.editor.interfaces/idisposable)
```
public interface IAuxDisposable extends IDisposable
```

Amplía la interfaz estándar IDisposable, permite obtener un
estado de un objeto y suscribirse al evento de eliminación

## Campos

| Campo | Descripción |
| --- | --- |
|  | [Disposed](#Disposed) | Ocurre cuando el objeto es eliminado |
|
## Métodos

| Método | Descripción |
| --- | --- |
|  | [isDisposed()](#isDisposed--) | Determina si un recurso está cerrado (true) o no (false |
|
### Disposed {#Disposed}
```
public static final Event<EventHandler> Disposed
```


Ocurre cuando el objeto es eliminado


### isDisposed() {#isDisposed--}
```
public abstract boolean isDisposed()
```


Determina si un recurso está cerrado (true) o no (false


**Returns:**
booleano
