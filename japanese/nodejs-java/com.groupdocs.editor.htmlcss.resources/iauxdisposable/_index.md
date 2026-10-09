---
title: "IAuxDisposable"
second_title: "Node.js 用 GroupDocs.Editor (Java 経由) API リファレンス"
description: "標準の IDisposable インターフェイスを拡張し、オブジェクトの現在の状態を取得し、破棄イベントを購読できるようにします"
type: docs
weight: 11
url: /ja/nodejs-java/com.groupdocs.editor.htmlcss.resources/iauxdisposable/
---
**All Implemented Interfaces:**
[com.groupdocs.editor.interfaces.IDisposable](../../com.groupdocs.editor.interfaces/idisposable)
```
public interface IAuxDisposable extends IDisposable
```

標準の IDisposable インターフェイスを拡張し、現在の取得を可能にします
オブジェクトの状態を取得し、破棄イベントを購読します

## フィールド

| フィールド | 説明 |
| --- | --- |
|  | [Disposed](#Disposed) | オブジェクトが破棄されたときに発生します |
|
## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [isDisposed()](#isDisposed--) | リソースが閉じているかどうかを判断します（true）または（false） |
|
### Disposed {#Disposed}
```
public static final Event<EventHandler> Disposed
```


オブジェクトが破棄されたときに発生します


### isDisposed() {#isDisposed--}
```
public abstract boolean isDisposed()
```


リソースが閉じているかどうかを判断します（true）または（false）


**Returns:**
ブール
