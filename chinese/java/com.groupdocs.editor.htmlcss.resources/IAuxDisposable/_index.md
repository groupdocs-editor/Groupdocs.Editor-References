---
title: "IAuxDisposable"
second_title: "GroupDocs.Editor for Java API 参考"
description: "扩展标准 IDisposable 接口，允许获取对象的当前状态并订阅释放事件"
type: docs
weight: 11
url: /zh/java/com.groupdocs.editor.htmlcss.resources/iauxdisposable/
---
**All Implemented Interfaces:**
[com.groupdocs.editor.interfaces.IDisposable](../../com.groupdocs.editor.interfaces/idisposable)
```
public interface IAuxDisposable extends IDisposable
```

扩展标准 IDisposable 接口，允许获取当前
对象的状态并订阅释放事件

## 字段

| 字段 | 描述 |
| --- | --- |
|  | [Disposed](#Disposed) | 当对象被释放时发生 |
|
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [isDisposed()](#isDisposed--) | 确定资源是否已关闭（true）或未关闭（false |
|
### Disposed {#Disposed}
```
public static final Event<EventHandler> Disposed
```


当对象被释放时发生


### isDisposed() {#isDisposed--}
```
public abstract boolean isDisposed()
```


确定资源是否已关闭（true）或未关闭（false


**Returns:**
boolean
