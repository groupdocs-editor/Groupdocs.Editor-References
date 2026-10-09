---
title: "PdfSaveOptions"
second_title: "Node.js 用 GroupDocs.Editor (Java 経由) API リファレンス"
description: "PDF（Portable Document Format）ドキュメントの生成および保存のためのカスタムオプションを指定できます"
type: docs
weight: 31
url: /ja/nodejs-java/com.groupdocs.editor.options/pdfsaveoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ISaveOptions](../../com.groupdocs.editor.options/isaveoptions)
```
public final class PdfSaveOptions implements ISaveOptions
```

PDF（Portable の生成および保存のためのカスタムオプションを指定できます
Document Format）ドキュメント

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [PdfSaveOptions()](#PdfSaveOptions--) |  |
## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [getPassword()](#getPassword--) | 生成された PDF ドキュメントにユーザーパスワードとして適用されるパスワードで、開く際に必要です。 |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | 生成された PDF ドキュメントにユーザーパスワードとして適用されるパスワードで、開く際に必要です。 |
|
|  | [getCompliance()](#getCompliance--) | 出力ドキュメントの PDF 標準準拠レベルを指定します。 |
|
|  | [setCompliance(int value)](#setCompliance-int-) | 出力ドキュメントの PDF 標準準拠レベルを指定します。 |
|
|  | [getFontEmbedding()](#getFontEmbedding--) | 元のドキュメントで使用されているフォントリソースを結果の PDF ドキュメントに埋め込むことを担当します。 |
|
|  | [setFontEmbedding(int value)](#setFontEmbedding-int-) | 元のドキュメントで使用されているフォントリソースを結果の PDF ドキュメントに埋め込むことを担当します。 |
|
|  | [getOptimizeMemoryUsage()](#getOptimizeMemoryUsage--) | HTML からドキュメントを生成する際にメモリ最適化機構を有効にします。これによりメモリ使用量は減少しますが、パフォーマンスが低下します。 |
|
|  | [setOptimizeMemoryUsage(boolean value)](#setOptimizeMemoryUsage-boolean-) | HTML からドキュメントを生成する際にメモリ最適化機構を有効にします。これによりメモリ使用量は減少しますが、パフォーマンスが低下します。 |
|
### PdfSaveOptions() {#PdfSaveOptions--}
```
public PdfSaveOptions()
```


### getPassword() {#getPassword--}
```
public final String getPassword()
```


生成された PDF ドキュメントにユーザーパスワードとして適用されるパスワードで、開く際に必要です。
NULL または空の場合、ドキュメントにパスワードは適用されません。それ以外の場合、ドキュメントは RC4（鍵長 128 ビット）で暗号化されます。
デフォルトは NULL \\u2014 パスワードは適用されません。


**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


生成された PDF ドキュメントにユーザーパスワードとして適用されるパスワードで、開く際に必要です。
NULL または空の場合、ドキュメントにパスワードは適用されません。それ以外の場合、ドキュメントは RC4（鍵長 128 ビット）で暗号化されます。
デフォルトは NULL \\u2014 パスワードは適用されません。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### getCompliance() {#getCompliance--}
```
public final int getCompliance()
```


出力ドキュメントの PDF 標準準拠レベルを指定します。デフォルトは PdfCompliance.Pdf17 です。


**Returns:**
int
### setCompliance(int value) {#setCompliance-int-}
```
public final void setCompliance(int value)
```


出力ドキュメントの PDF 標準準拠レベルを指定します。デフォルトは PdfCompliance.Pdf17 です。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### getFontEmbedding() {#getFontEmbedding--}
```
public final int getFontEmbedding()
```


元のドキュメントで使用されているフォントリソースを結果の PDF ドキュメントに埋め込むことを担当します。デフォルトではフォントは埋め込まれません（NotEmbed）。


**Returns:**
int
### setFontEmbedding(int value) {#setFontEmbedding-int-}
```
public final void setFontEmbedding(int value)
```


元のドキュメントで使用されているフォントリソースを結果の PDF ドキュメントに埋め込むことを担当します。デフォルトではフォントは埋め込まれません（NotEmbed）。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### getOptimizeMemoryUsage() {#getOptimizeMemoryUsage--}
```
public final boolean getOptimizeMemoryUsage()
```


HTML からドキュメントを生成する際にメモリ最適化機構を有効にします。これによりメモリ使用量は減少しますが、パフォーマンスが低下します。
このオプションを true に設定すると、保存時間が遅くなる代償として、大きなドキュメント生成時のメモリ消費を大幅に削減できます。
デフォルトは false です (メモリ最適化は、より高いパフォーマンスを得るために無効化されています)。


**Returns:**
ブール
### setOptimizeMemoryUsage(boolean value) {#setOptimizeMemoryUsage-boolean-}
```
public final void setOptimizeMemoryUsage(boolean value)
```


HTML からドキュメントを生成する際にメモリ最適化機構を有効にします。これによりメモリ使用量は減少しますが、パフォーマンスが低下します。
このオプションを true に設定すると、保存時間が遅くなる代償として、大きなドキュメント生成時のメモリ消費を大幅に削減できます。
デフォルトは false です (メモリ最適化は、より高いパフォーマンスを得るために無効化されています)。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | ブール |  |

