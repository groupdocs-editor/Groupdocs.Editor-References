---
title: "IAuxDisposable"
second_title: "Référence d'API GroupDocs.Editor pour Node.js via Java"
description: "Étend l'interface standard IDisposable et permet d'obtenir l'état actuel d'un objet et de s'abonner à l'événement de libération"
type: docs
weight: 11
url: /fr/nodejs-java/com.groupdocs.editor.htmlcss.resources/iauxdisposable/
---
**All Implemented Interfaces:**
[com.groupdocs.editor.interfaces.IDisposable](../../com.groupdocs.editor.interfaces/idisposable)
```
public interface IAuxDisposable extends IDisposable
```

Étend l'interface standard IDisposable, permet d'obtenir un
état d'un objet et de s'abonner à l'événement de libération

## Champs

| Champ | Description |
| --- | --- |
|  | [Disposed](#Disposed) | Se produit lorsque l'objet est libéré |
|
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [isDisposed()](#isDisposed--) | Détermine si une ressource est fermée (true) ou non (false |
|
### Disposed {#Disposed}
```
public static final Event<EventHandler> Disposed
```


Se produit lorsque l'objet est libéré


### isDisposed() {#isDisposed--}
```
public abstract boolean isDisposed()
```


Détermine si une ressource est fermée (true) ou non (false


**Returns:**
booléen
