---
title: "IAuxDisposable"
second_title: "Riferimento API di GroupDocs.Editor per Node.js via Java"
description: "Estende l'interfaccia standard IDisposable consentendo di ottenere lo stato corrente di un oggetto e di iscriversi all'evento di rilascio."
type: docs
weight: 11
url: /it/nodejs-java/com.groupdocs.editor.htmlcss.resources/iauxdisposable/
---
**All Implemented Interfaces:**
[com.groupdocs.editor.interfaces.IDisposable](../../com.groupdocs.editor.interfaces/idisposable)
```
public interface IAuxDisposable extends IDisposable
```

Estende l'interfaccia standard IDisposable, consente di ottenere un corrente
stato di un oggetto e iscriversi all'evento di rilascio.

## Campi

| Campo | Descrizione |
| --- | --- |
|  | [Disposed](#Disposed) | Si verifica quando l'oggetto viene rilasciato. |
|
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [isDisposed()](#isDisposed--) | Determina se una risorsa è chiusa (true) o no (false |
|
### Disposed {#Disposed}
```
public static final Event<EventHandler> Disposed
```


Si verifica quando l'oggetto viene rilasciato.


### isDisposed() {#isDisposed--}
```
public abstract boolean isDisposed()
```


Determina se una risorsa è chiusa (true) o no (false


**Returns:**
boolean
