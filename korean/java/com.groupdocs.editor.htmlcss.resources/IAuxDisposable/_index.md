---
title: "IAuxDisposable"
second_title: "GroupDocs.Editor for Java API 참조"
description: "표준 IDisposable 인터페이스를 확장하여 객체의 현재 상태를 얻고 폐기 이벤트를 구독할 수 있게 합니다"
type: docs
weight: 11
url: /ko/java/com.groupdocs.editor.htmlcss.resources/iauxdisposable/
---
**All Implemented Interfaces:**
[com.groupdocs.editor.interfaces.IDisposable](../../com.groupdocs.editor.interfaces/idisposable)
```
public interface IAuxDisposable extends IDisposable
```

표준 IDisposable 인터페이스를 확장하고, 현재
객체의 상태를 확인하며 폐기 이벤트를 구독합니다

## 필드

| 필드 | 설명 |
| --- | --- |
|  | [Disposed](#Disposed) | 객체가 폐기될 때 발생합니다 |
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [isDisposed()](#isDisposed--) | 리소스가 닫혔는지 (true) 아니면 (false)인지 판단합니다 |
|
### Disposed {#Disposed}
```
public static final Event<EventHandler> Disposed
```


객체가 폐기될 때 발생합니다


### isDisposed() {#isDisposed--}
```
public abstract boolean isDisposed()
```


리소스가 닫혔는지 (true) 아니면 (false)인지 판단합니다


**Returns:**
boolean
