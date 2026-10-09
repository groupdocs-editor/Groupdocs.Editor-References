---
title: "ResourceTypeDetector"
second_title: "Node.js 用 GroupDocs.Editor (Java 経由) API リファレンス"
description: "リソースタイプの形式を検出するためのユーティリティ静的メソッド"
type: docs
weight: 10
url: /ja/nodejs-java/com.groupdocs.editor.htmlcss.resources/resourcetypedetector/
---
**Inheritance:**
java.lang.Object
```
public class ResourceTypeDetector
```

リソースタイプ（フォーマット）を検出するユーティリティの静的メソッド。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [ResourceTypeDetector()](#ResourceTypeDetector--) |  |
## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [detectTypeFromFilename(String filename)](#detectTypeFromFilename-java.lang.String-) | 指定されたファイル名からタイプを検出し、インスタンスを返します |
該当する IResourceType
|
|  | [tryDetectResource(InputStream inputResourceStream, String name, IResourceType assumptiveFormat)](#tryDetectResource-java.io.InputStream-java.lang.String-com.groupdocs.editor.htmlcss.resources.IResourceType-) | 入力ストリームを解析し、サポート可能なHTMLのいずれかを作成しようとします |
それからリソースを作成し、指定された想定タイプを考慮します、もしそれが
nullでない場合
|
### ResourceTypeDetector() {#ResourceTypeDetector--}
```
public ResourceTypeDetector()
```


### detectTypeFromFilename(String filename) {#detectTypeFromFilename-java.lang.String-}
```
public static IResourceType detectTypeFromFilename(String filename)
```


指定されたファイル名からタイプを検出し、インスタンスを返します
該当する IResourceType


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | ファイル名 | java.lang.String | 入力ファイル名。このメソッドはここから結果となる IResourceType 実装を抽出しようとします |
|

**Returns:**
[IResourceType](../../com.groupdocs.editor.htmlcss.resources/iresourcetype) - IResourceType implementation on success or NULL on failure

### tryDetectResource(InputStream inputResourceStream, String name, IResourceType assumptiveFormat) {#tryDetectResource-java.io.InputStream-java.lang.String-com.groupdocs.editor.htmlcss.resources.IResourceType-}
```
public static IHtmlResource tryDetectResource(InputStream inputResourceStream, String name, IResourceType assumptiveFormat)
```


入力ストリームを解析し、サポート可能なHTMLのいずれかを作成しようとします
それからリソースを作成し、指定された想定タイプを考慮します、もしそれが
nullでない場合


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | inputResourceStream | java.io.InputStream | 入力ストリーム。HTMLリソースが含まれていると想定されます。無効な場合は例外がスローされます。 |
|
|  | 名前 | java.lang.String | リソース名。成功時に作成および返却されるリソースに使用されます。NULL、空、または空白文字にできません |
|
|  | assumptiveFormat | [IResourceType](../../com.groupdocs.editor.htmlcss.resources/iresourcetype) | 入力HTMLリソースの想定フォーマット。最高のパフォーマンスを得るために有用です。完全に不明な場合はNULL値を使用してください。誤っている可能性があり、その場合はパフォーマンスが低下します。 |
|

**Returns:**
[IHtmlResource](../../com.groupdocs.editor.htmlcss.resources/ihtmlresource) - Instance, which implements 'IHtmlResource' interface and represents one of supportable HTML resources on success, or NULL on failure

