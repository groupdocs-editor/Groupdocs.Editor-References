---
title: "MarkdownImageLoadArgs"
second_title: "GroupDocs.Editor for Java API 참조"
description: "MGroupDocs.Editor.Options.IMarkdownImageLoadCallback.ProcessImageMarkdownImageLoadArgs 이벤트에 대한 데이터를 제공합니다."
type: docs
weight: 22
url: /ko/java/com.groupdocs.editor.options/markdownimageloadargs/
---
**Inheritance:**
java.lang.Object
```
public class MarkdownImageLoadArgs
```

다음에 대한 데이터를 제공합니다.

M:GroupDocs.Editor.Options.IMarkdownImageLoadCallback.ProcessImage(MarkdownImageLoadArgs)

이벤트.

## 생성자

| 생성자 | 설명 |
| --- | --- |
| [MarkdownImageLoadArgs()](#MarkdownImageLoadArgs--) |  |
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getImageFileName()](#getImageFileName--) | Markdown 문서에 있는 그대로의 파일 이름을 가져오거나 설정합니다. |
처리합니다.
|
|  | [setImageFileName(String value)](#setImageFileName-java.lang.String-) | Markdown 문서에 있는 그대로의 파일 이름을 가져오거나 설정합니다. |
처리합니다.
|
|  | [isAbsoluteUri()](#isAbsoluteUri--) | 이 이미지가 절대 URI 링크인지 여부를 나타내는 값을 가져옵니다. |
|
|  | [setAbsoluteUri(boolean value)](#setAbsoluteUri-boolean-) | 이 이미지가 절대 URI 링크인지 여부를 나타내는 값을 가져옵니다. |
|
|  | [setData(byte[] data)](#setData-byte---) | 사용자가 제공한 리소스 데이터를 설정합니다(사용되는 경우). |

M:GroupDocs.Editor.Options.IMarkdownImageLoadCallback.ProcessImage(MarkdownImageLoadArgs)

|
### MarkdownImageLoadArgs() {#MarkdownImageLoadArgs--}
```
public MarkdownImageLoadArgs()
```


### getImageFileName() {#getImageFileName--}
```
public final String getImageFileName()
```


Markdown 문서에 있는 그대로의 파일 이름을 가져오거나 설정합니다.
처리합니다.


**Returns:**
java.lang.String
### setImageFileName(String value) {#setImageFileName-java.lang.String-}
```
public final void setImageFileName(String value)
```


Markdown 문서에 있는 그대로의 파일 이름을 가져오거나 설정합니다.
처리합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### isAbsoluteUri() {#isAbsoluteUri--}
```
public final boolean isAbsoluteUri()
```


이 이미지가 절대 URI 링크인지 여부를 나타내는 값을 가져옵니다.
값: 이 이미지가 절대 URI 링크인 경우 true, 그렇지 않으면 false.


**Returns:**
boolean
### setAbsoluteUri(boolean value) {#setAbsoluteUri-boolean-}
```
public final void setAbsoluteUri(boolean value)
```


이 이미지가 절대 URI 링크인지 여부를 나타내는 값을 가져옵니다.
값: 이 이미지가 절대 URI 링크인 경우 true, 그렇지 않으면 false.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### setData(byte[] data) {#setData-byte---}
```
public final void setData(byte[] data)
```


사용자가 제공한 리소스 데이터를 설정합니다(사용되는 경우).

M:GroupDocs.Editor.Options.IMarkdownImageLoadCallback.ProcessImage(MarkdownImageLoadArgs)



**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 데이터 | byte[] |  |

