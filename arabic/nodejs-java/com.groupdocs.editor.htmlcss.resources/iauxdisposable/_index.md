---
title: "IAuxDisposable"
second_title: "مرجع API لـ GroupDocs.Editor لـ Node.js عبر Java"
description: "يوسع واجهة IDisposable القياسية ويسمح بالحصول على الحالة الحالية لكائن والاشتراك في حدث التخلص"
type: docs
weight: 11
url: /ar/nodejs-java/com.groupdocs.editor.htmlcss.resources/iauxdisposable/
---
**All Implemented Interfaces:**
[com.groupdocs.editor.interfaces.IDisposable](../../com.groupdocs.editor.interfaces/idisposable)
```
public interface IAuxDisposable extends IDisposable
```

يوسع واجهة IDisposable القياسية، ويسمح بالحصول على الحالية
حالة كائن والاشتراك في حدث التخلص

## الحقول

| حقل | الوصف |
| --- | --- |
|  | [Disposed](#Disposed) | يحدث عندما يتم التخلص من الكائن |
|
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [isDisposed()](#isDisposed--) | يحدد ما إذا كان المورد مغلقًا (true) أم لا (false |
|
### Disposed {#Disposed}
```
public static final Event<EventHandler> Disposed
```


يحدث عندما يتم التخلص من الكائن


### isDisposed() {#isDisposed--}
```
public abstract boolean isDisposed()
```


يحدد ما إذا كان المورد مغلقًا (true) أم لا (false


**Returns:**
boolean
