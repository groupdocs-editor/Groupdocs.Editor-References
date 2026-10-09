---
title: "AudioType"
second_title: "Node.js 用 GroupDocs.Editor (Java 経由) API リファレンス"
description: "サポート可能なオーディオタイプ形式を表します"
type: docs
weight: 10
url: /ja/nodejs-java/com.groupdocs.editor.htmlcss.resources.audio/audiotype/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.resources.IResourceType](../../com.groupdocs.editor.htmlcss.resources/iresourcetype)
```
public class AudioType implements IResourceType
```

サポート可能なオーディオタイプ（フォーマット）を表します。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [AudioType()](#AudioType--) |  |
## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [getFormalName()](#getFormalName--) | このオーディオ形式の正式名称 |
|
|  | [getFileExtension()](#getFileExtension--) | このオーディオ形式のファイル名拡張子（ドット文字なし） |
|
|  | [getMimeCode()](#getMimeCode--) | このオーディオ形式の MIME コード |
|
|  | [equals(AudioType other)](#equals-com.groupdocs.editor.htmlcss.resources.audio.AudioType-) | このインスタンスが指定された "AudioType" インスタンスと等しいかどうかを判断します |
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | このインスタンスが指定されたキャストされていないオブジェクト（おそらく別の "AudioType" インスタンス）と等しいかどうかを判断します |
|
|  | [op_Equality(AudioType first, AudioType second)](#op-Equality-com.groupdocs.editor.htmlcss.resources.audio.AudioType-com.groupdocs.editor.htmlcss.resources.audio.AudioType-) | 2 つの "AudioType" 値が等しいかどうかをチェックします |
|
|  | [op_Inequality(AudioType first, AudioType second)](#op-Inequality-com.groupdocs.editor.htmlcss.resources.audio.AudioType-com.groupdocs.editor.htmlcss.resources.audio.AudioType-) | 2 つの "AudioType" 値が等しくないかどうかをチェックします |
|
|  | [hashCode()](#hashCode--) | この特定の値型に対して一定の数値であるハッシュコードを返します |
|
|  | [getUndefined()](#getUndefined--) | 未定義、未知、またはサポートされていないオーディオ形式を示す特別な値 |
|
|  | [getMp3()](#getMp3--) | MPEG-1 Audio Layer III オーディオ形式を表します |
|
|  | [parseFromFilenameWithExtension(String filename)](#parseFromFilenameWithExtension-java.lang.String-) | 指定されたファイル名から抽出されたファイル名拡張子に相当する AudioType 値を返します |
|
### AudioType() {#AudioType--}
```
public AudioType()
```


### getFormalName() {#getFormalName--}
```
public final String getFormalName()
```


このオーディオ形式の正式名称


**Returns:**
java.lang.String
### getFileExtension() {#getFileExtension--}
```
public final String getFileExtension()
```


このオーディオ形式のファイル名拡張子（ドット文字なし）


**Returns:**
java.lang.String
### getMimeCode() {#getMimeCode--}
```
public final String getMimeCode()
```


このオーディオ形式の MIME コード


**Returns:**
java.lang.String
### equals(AudioType other) {#equals-com.groupdocs.editor.htmlcss.resources.audio.AudioType-}
```
public final boolean equals(AudioType other)
```


このインスタンスが指定された "AudioType" インスタンスと等しいかどうかを判断します


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | other | [AudioType](../../com.groupdocs.editor.htmlcss.resources.audio/audiotype) | このインスタンスと比較する他の AudioType インスタンス |
|

**Returns:**
boolean - 等しい場合は true、等しくない場合は false

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


このインスタンスが指定されたキャストされていないオブジェクト（おそらく別の "AudioType" インスタンス）と等しいかどうかを判断します


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | obj | java.lang.Object | System.Object にボックス化された AudioType 構造体と思われる他のインスタンス |
|

**Returns:**
boolean - 等しい場合は true、等しくない場合は false

### op_Equality(AudioType first, AudioType second) {#op-Equality-com.groupdocs.editor.htmlcss.resources.audio.AudioType-com.groupdocs.editor.htmlcss.resources.audio.AudioType-}
```
public static boolean op_Equality(AudioType first, AudioType second)
```


2 つの "AudioType" 値が等しいかどうかをチェックします


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | first | [AudioType](../../com.groupdocs.editor.htmlcss.resources.audio/audiotype) | 比較する最初の AudioType |
|
|  | second | [AudioType](../../com.groupdocs.editor.htmlcss.resources.audio/audiotype) | 比較する2番目の AudioType |
|

**Returns:**
boolean - 等しい場合は true、等しくない場合は false

### op_Inequality(AudioType first, AudioType second) {#op-Inequality-com.groupdocs.editor.htmlcss.resources.audio.AudioType-com.groupdocs.editor.htmlcss.resources.audio.AudioType-}
```
public static boolean op_Inequality(AudioType first, AudioType second)
```


2 つの "AudioType" 値が等しくないかどうかをチェックします


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | first | [AudioType](../../com.groupdocs.editor.htmlcss.resources.audio/audiotype) | 比較する最初の AudioType |
|
|  | second | [AudioType](../../com.groupdocs.editor.htmlcss.resources.audio/audiotype) | 比較する2番目の AudioType |
|

**Returns:**
boolean - 等しい場合は true、等しくない場合は false

### hashCode() {#hashCode--}
```
public int hashCode()
```


この特定の値型に対して一定の数値であるハッシュコードを返します


**Returns:**
int - 4 バイト符号付き整数、未定義値の場合は 0

### getUndefined() {#getUndefined--}
```
public static AudioType getUndefined()
```


未定義、未知、またはサポートされていないオーディオ形式を示す特別な値


**Returns:**
[AudioType](../../com.groupdocs.editor.htmlcss.resources.audio/audiotype)
### getMp3() {#getMp3--}
```
public static AudioType getMp3()
```


MPEG-1 Audio Layer III オーディオ形式を表します


**Returns:**
[AudioType](../../com.groupdocs.editor.htmlcss.resources.audio/audiotype)
### parseFromFilenameWithExtension(String filename) {#parseFromFilenameWithExtension-java.lang.String-}
```
public static AudioType parseFromFilenameWithExtension(String filename)
```


指定されたファイル名から抽出されたファイル名拡張子に相当する AudioType 値を返します


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | ファイル名 | java.lang.String | 任意のファイル名で、相対パスまたはフルパスにすることができます |
|

**Returns:**
[AudioType](../../com.groupdocs.editor.htmlcss.resources.audio/audiotype) - AudioType value. Returns AudioType.Undefined, if extension cannot be recognized.

