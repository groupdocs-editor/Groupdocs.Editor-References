---
title: "IAuxDisposable"
second_title: "GroupDocs.Editor Node.js için Java API Referansı"
description: "Standart IDisposable arayüzünü genişleterek bir nesnenin mevcut durumunu elde etmeyi ve imha olayı için abone olmayı sağlar"
type: docs
weight: 11
url: /tr/nodejs-java/com.groupdocs.editor.htmlcss.resources/iauxdisposable/
---
**All Implemented Interfaces:**
[com.groupdocs.editor.interfaces.IDisposable](../../com.groupdocs.editor.interfaces/idisposable)
```
public interface IAuxDisposable extends IDisposable
```

Standart IDisposable arayüzünü genişletir, mevcut bir
nesnenin durumunu ve imha olayı için abone olmayı sağlar

## Alanlar

| Alan | Açıklama |
| --- | --- |
|  | [Disposed](#Disposed) | Nesne imha edildiğinde gerçekleşir |
|
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [isDisposed()](#isDisposed--) | Bir kaynağın kapalı olup olmadığını belirler (true) veya (false |
|
### Disposed {#Disposed}
```
public static final Event<EventHandler> Disposed
```


Nesne imha edildiğinde gerçekleşir


### isDisposed() {#isDisposed--}
```
public abstract boolean isDisposed()
```


Bir kaynağın kapalı olup olmadığını belirler (true) veya (false


**Returns:**
boolean
