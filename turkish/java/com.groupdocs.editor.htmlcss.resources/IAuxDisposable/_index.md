---
title: "IAuxDisposable"
second_title: "GroupDocs.Editor Java için API Referansı"
description: "Standart IDisposable arayüzünü genişleterek bir nesnenin mevcut durumunu elde etmeyi ve imha olayı için abone olmayı sağlar"
type: docs
weight: 11
url: /tr/java/com.groupdocs.editor.htmlcss.resources/iauxdisposable/
---
**All Implemented Interfaces:**
[com.groupdocs.editor.interfaces.IDisposable](../../com.groupdocs.editor.interfaces/idisposable)
```
public interface IAuxDisposable extends IDisposable
```

Standart IDisposable arabirimini genişletir, mevcut birini elde etmeyi sağlar
bir nesnenin durumu ve imha olayına abone olma

## Alanlar

| Alan | Açıklama |
| --- | --- |
|  | [Disposed](#Disposed) | Nesne imha edildiğinde gerçekleşir |
|
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [isDisposed()](#isDisposed--) | Bir kaynağın kapalı (true) veya açık (false) olup olmadığını belirler |
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


Bir kaynağın kapalı (true) veya açık (false) olup olmadığını belirler


**Returns:**
boolean
