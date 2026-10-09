---
title: "TextDirection"
second_title: "Node.js 用 GroupDocs.Editor (Java 経由) API リファレンス"
description: "プレーンテキスト文書におけるテキスト方向の扱い方を表す 3 つの可能なバリエーションを示します"
type: docs
weight: 38
url: /ja/nodejs-java/com.groupdocs.editor.options/textdirection/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class TextDirection extends System.Enum
```

プレーンテキストにおけるテキスト方向の扱い方を表す 3 つの可能なバリエーションです
ドキュメント

## フィールド

| フィールド | 説明 |
| --- | --- |
|  | [LeftToRight](#LeftToRight) | 左から右への方向、通常のテキスト、デフォルト値です。 |
|
|  | [RightToLeft](#RightToLeft) | 右から左への方向 |
|
|  | [Auto](#Auto) | 方向を自動検出します。 |
|
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getTextDirection()](#getTextDirection--) |  |
### LeftToRight {#LeftToRight}
```
public static final int LeftToRight
```


左から右への方向、通常のテキスト、デフォルト値です。


### RightToLeft {#RightToLeft}
```
public static final int RightToLeft
```


右から左への方向


### Auto {#Auto}
```
public static final int Auto
```


方向を自動検出します。このオプションが選択され、テキストに
RTL スクリプトに属する文字が含まれている場合、文書の方向は
自動的に RTL に設定されます。


### getTextDirection() {#getTextDirection--}
```
public static int[] getTextDirection()
```




**Returns:**
int[]
