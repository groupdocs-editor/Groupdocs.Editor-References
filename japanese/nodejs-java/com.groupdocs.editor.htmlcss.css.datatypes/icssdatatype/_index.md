---
title: "ICssDataType"
second_title: "Node.js 用 GroupDocs.Editor (Java 経由) API リファレンス"
description: "CSS プロパティで使用されるすべての CSS データ型の共通インターフェイス"
type: docs
weight: 15
url: /ja/nodejs-java/com.groupdocs.editor.htmlcss.css.datatypes/icssdatatype/
---
**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable
```
public interface ICssDataType extends System.IEquatable<ICssDataType>
```

CSS プロパティで使用されるすべての CSS データ型の共通インターフェイスです。

## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [serializeDefault()](#serializeDefault--) | 現在の値のデフォルト文字列表現を返す必要があります |
データ型
|
|  | [isDefault()](#isDefault--) | データ型の現在の値がデフォルトかどうかを定義すべきです |
この特定のデータ型の値であるかどうか
|
### serializeDefault() {#serializeDefault--}
```
public abstract String serializeDefault()
```


現在の値のデフォルト文字列表現を返す必要があります
データ型


**Returns:**
java.lang.String -
### isDefault() {#isDefault--}
```
public abstract boolean isDefault()
```


データ型の現在の値がデフォルトかどうかを定義すべきです
この特定のデータ型の値であるかどうか


**Returns:**
boolean -
