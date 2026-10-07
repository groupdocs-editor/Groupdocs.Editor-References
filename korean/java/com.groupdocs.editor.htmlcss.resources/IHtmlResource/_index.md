---
title: "IHtmlResource"
second_title: "GroupDocs.Editor for Java API 참조"
description: "알 수 없는 HTML 리소스(래스터 또는 벡터 이미지, 스타일시트, 폰트, 텍스트 리소스, CSS, XML 등)의 한 인스턴스를 나타냅니다"
type: docs
weight: 12
url: /ko/java/com.groupdocs.editor.htmlcss.resources/ihtmlresource/
---
**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.resources.IAuxDisposable](../../com.groupdocs.editor.htmlcss.resources/iauxdisposable)
```
public interface IHtmlResource extends IAuxDisposable
```

알 수 없는 HTML 리소스(래스터 또는 벡터 이미지)의 한 인스턴스를 나타냅니다
스타일시트, 폰트, 텍스트 리소스(CSS, XML) 등)

## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getName()](#getName--) | HTML 리소스의 이름 |
|
|  | [getFilenameWithExtension()](#getFilenameWithExtension--) | 지정된 리소스에 적절한 파일을 포함한 올바른 파일 이름 |
확장자
|
|  | [getType()](#getType--) | HTML 리소스의 유형 |
|
|  | [getByteContent()](#getByteContent--) | 바이트 스트림 형태의 HTML 리소스 내용 |
|
|  | [getTextContent()](#getTextContent--) | Base64 인코딩된 텍스트 문자열 형태의 HTML 리소스 내용 |
바이너리 리소스의 경우 또는 텍스트 리소스의 경우 간단한 텍스트
|
|  | [save(String fullPathToFile)](#save-java.lang.String-) | 현재 리소스를 지정된 파일에 저장합니다 |
|
### getName() {#getName--}
```
public abstract String getName()
```


HTML 리소스의 이름


**Returns:**
java.lang.String -
### getFilenameWithExtension() {#getFilenameWithExtension--}
```
public abstract String getFilenameWithExtension()
```


지정된 리소스에 적절한 파일을 포함한 올바른 파일 이름
확장자


**Returns:**
java.lang.String -
### getType() {#getType--}
```
public abstract IResourceType getType()
```


HTML 리소스의 유형


**Returns:**
[IResourceType](../../com.groupdocs.editor.htmlcss.resources/iresourcetype) - 
### getByteContent() {#getByteContent--}
```
public abstract InputStream getByteContent()
```


바이트 스트림 형태의 HTML 리소스 내용


**Returns:**
java.io.InputStream
### getTextContent() {#getTextContent--}
```
public abstract String getTextContent()
```


Base64 인코딩된 텍스트 문자열 형태의 HTML 리소스 내용
바이너리 리소스의 경우 또는 텍스트 리소스의 경우 간단한 텍스트


**Returns:**
java.lang.String
### save(String fullPathToFile) {#save-java.lang.String-}
```
public abstract void save(String fullPathToFile)
```


현재 리소스를 지정된 파일에 저장합니다


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | fullPathToFile | java.lang.String | 현재 리소스의 내용으로 생성되거나 덮어쓰기 될 파일의 전체 경로 |
|

