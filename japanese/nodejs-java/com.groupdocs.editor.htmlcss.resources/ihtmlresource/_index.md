---
title: "IHtmlResource"
second_title: "Node.js 用 GroupDocs.Editor (Java 経由) API リファレンス"
description: "不明な HTML リソース（ラスタまたはベクタ画像、スタイルシート、フォント、テキスト、リソース、CSS、XML など）のインスタンスを表します"
type: docs
weight: 12
url: /ja/nodejs-java/com.groupdocs.editor.htmlcss.resources/ihtmlresource/
---
**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.resources.IAuxDisposable](../../com.groupdocs.editor.htmlcss.resources/iauxdisposable)
```
public interface IHtmlResource extends IAuxDisposable
```

不明な HTML リソース（ラスタまたはベクタ画像）のインスタンスを表します、
スタイルシート、フォント、テキストリソース（CSS、XML）など）

## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [getName()](#getName--) | HTMLリソースの名前 |
|
|  | [getFilenameWithExtension()](#getFilenameWithExtension--) | 指定されたリソースの正しいファイル名（適切なファイル） |
拡張子
|
|  | [getType()](#getType--) | HTMLリソースのタイプ |
|
|  | [getByteContent()](#getByteContent--) | HTMLリソースの内容（バイトストリーム形式） |
|
|  | [getTextContent()](#getTextContent--) | HTMLリソースの内容（Base64エンコードされたテキスト文字列形式） |
バイナリリソースの場合、またはテキストリソースの場合は単純なテキスト
|
|  | [save(String fullPathToFile)](#save-java.lang.String-) | 現在のリソースを指定されたファイルに保存します |
|
### getName() {#getName--}
```
public abstract String getName()
```


HTMLリソースの名前


**Returns:**
java.lang.String -
### getFilenameWithExtension() {#getFilenameWithExtension--}
```
public abstract String getFilenameWithExtension()
```


指定されたリソースの正しいファイル名（適切なファイル）
拡張子


**Returns:**
java.lang.String -
### getType() {#getType--}
```
public abstract IResourceType getType()
```


HTMLリソースのタイプ


**Returns:**
[IResourceType](../../com.groupdocs.editor.htmlcss.resources/iresourcetype) - 
### getByteContent() {#getByteContent--}
```
public abstract InputStream getByteContent()
```


HTMLリソースの内容（バイトストリーム形式）


**Returns:**
java.io.InputStream
### getTextContent() {#getTextContent--}
```
public abstract String getTextContent()
```


HTMLリソースの内容（Base64エンコードされたテキスト文字列形式）
バイナリリソースの場合、またはテキストリソースの場合は単純なテキスト


**Returns:**
java.lang.String
### save(String fullPathToFile) {#save-java.lang.String-}
```
public abstract void save(String fullPathToFile)
```


現在のリソースを指定されたファイルに保存します


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | fullPathToFile | java.lang.String | 現在のリソースの内容で作成または上書きされるファイルへのフルパス |
|

