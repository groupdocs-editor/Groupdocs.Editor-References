---
title: "IAuxDisposable"
second_title: "Referensi API GroupDocs.Editor untuk Java"
description: "Memperluas antarmuka IDisposable standar, memungkinkan memperoleh status terkini dari sebuah objek dan berlangganan pada peristiwa pembuangan"
type: docs
weight: 11
url: /id/java/com.groupdocs.editor.htmlcss.resources/iauxdisposable/
---
**All Implemented Interfaces:**
[com.groupdocs.editor.interfaces.IDisposable](../../com.groupdocs.editor.interfaces/idisposable)
```
public interface IAuxDisposable extends IDisposable
```

Memperluas antarmuka IDisposable standar, memungkinkan untuk memperoleh nilai saat ini
status sebuah objek dan berlangganan ke acara disposing

## Bidang

| Bidang | Deskripsi |
| --- | --- |
|  | [Disposed](#Disposed) | Terjadi ketika objek dibuang |
|
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [isDisposed()](#isDisposed--) | Menentukan apakah sebuah sumber daya ditutup (true) atau tidak (false |
|
### Disposed {#Disposed}
```
public static final Event<EventHandler> Disposed
```


Terjadi ketika objek dibuang


### isDisposed() {#isDisposed--}
```
public abstract boolean isDisposed()
```


Menentukan apakah sebuah sumber daya ditutup (true) atau tidak (false


**Returns:**
boolean
