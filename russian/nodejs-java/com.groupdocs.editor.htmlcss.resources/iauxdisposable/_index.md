---
title: "IAuxDisposable"
second_title: "GroupDocs.Editor для Node.js через Java API Reference"
description: "Расширяет стандартный интерфейс IDisposable, позволяя получить текущее состояние объекта и подписаться на событие освобождения."
type: docs
weight: 11
url: /ru/nodejs-java/com.groupdocs.editor.htmlcss.resources/iauxdisposable/
---
**All Implemented Interfaces:**
[com.groupdocs.editor.interfaces.IDisposable](../../com.groupdocs.editor.interfaces/idisposable)
```
public interface IAuxDisposable extends IDisposable
```

Расширяет стандартный интерфейс IDisposable, позволяет получить текущее
состояние объекта и подписаться на событие освобождения.

## Поля

| Поле | Описание |
| --- | --- |
|  | [Disposed](#Disposed) | Происходит, когда объект освобождается. |
|
## Методы

| Метод | Описание |
| --- | --- |
|  | [isDisposed()](#isDisposed--) | Определяет, закрыт ли ресурс (true) или нет (false |
|
### Disposed {#Disposed}
```
public static final Event<EventHandler> Disposed
```


Происходит, когда объект освобождается.


### isDisposed() {#isDisposed--}
```
public abstract boolean isDisposed()
```


Определяет, закрыт ли ресурс (true) или нет (false


**Returns:**
boolean
