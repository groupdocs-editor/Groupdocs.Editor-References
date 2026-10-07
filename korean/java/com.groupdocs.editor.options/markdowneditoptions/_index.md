---
title: "MarkdownEditOptions"
second_title: "GroupDocs.Editor for Java API 참조"
description: "Markdown 형식의 문서를 편집하기 위한 사용자 지정 옵션을 지정할 수 있습니다."
type: docs
weight: 21
url: /ko/java/com.groupdocs.editor.options/markdowneditoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public final class MarkdownEditOptions implements IEditOptions
```

Markdown 형식의 문서를 편집하기 위한 사용자 지정 옵션을 지정할 수 있습니다.

## 생성자

| 생성자 | 설명 |
| --- | --- |
|  | [MarkdownEditOptions()](#MarkdownEditOptions--) | MarkdownEditOptions 클래스의 새 인스턴스를 생성하고 반환합니다, |
모든 옵션이 기본값으로 설정된 상태입니다
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getImageLoadCallback()](#getImageLoadCallback--) | Markdown 문서를 변환할 때 이미지가 저장되는 방식을 제어할 수 있습니다 |
HTML로.
|
|  | [setImageLoadCallback(IMarkdownImageLoadCallback value)](#setImageLoadCallback-com.groupdocs.editor.options.IMarkdownImageLoadCallback-) | Markdown 문서를 변환할 때 이미지가 저장되는 방식을 제어할 수 있습니다 |
HTML로.
|
### MarkdownEditOptions() {#MarkdownEditOptions--}
```
public MarkdownEditOptions()
```


MarkdownEditOptions 클래스의 새 인스턴스를 생성하고 반환합니다,
모든 옵션이 기본값으로 설정된 상태입니다


### getImageLoadCallback() {#getImageLoadCallback--}
```
public final IMarkdownImageLoadCallback getImageLoadCallback()
```


Markdown 문서를 변환할 때 이미지가 저장되는 방식을 제어할 수 있습니다
HTML로.
값: 이미지 저장 콜백입니다.


**Returns:**
[IMarkdownImageLoadCallback](../../com.groupdocs.editor.options/imarkdownimageloadcallback)
### setImageLoadCallback(IMarkdownImageLoadCallback value) {#setImageLoadCallback-com.groupdocs.editor.options.IMarkdownImageLoadCallback-}
```
public final void setImageLoadCallback(IMarkdownImageLoadCallback value)
```


Markdown 문서를 변환할 때 이미지가 저장되는 방식을 제어할 수 있습니다
HTML로.
값: 이미지 저장 콜백입니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [IMarkdownImageLoadCallback](../../com.groupdocs.editor.options/imarkdownimageloadcallback) |  |

