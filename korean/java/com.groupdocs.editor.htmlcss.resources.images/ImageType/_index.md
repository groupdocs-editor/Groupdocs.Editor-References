---
title: "ImageType"
second_title: "GroupDocs.Editor for Java API 참조"
description: "래스터와 벡터 형식을 모두 지원하는 이미지 타입 포맷을 나타냅니다"
type: docs
weight: 11
url: /ko/java/com.groupdocs.editor.htmlcss.resources.images/imagetype/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.resources.IResourceType](../../com.groupdocs.editor.htmlcss.resources/iresourcetype)
```
public class ImageType implements IResourceType
```

지원 가능한 이미지 유형(포맷) 하나를 나타내며, 래스터와 벡터 포맷을 모두 지원합니다.

## 생성자

| 생성자 | 설명 |
| --- | --- |
| [ImageType()](#ImageType--) |  |
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getUndefined()](#getUndefined--) | 정의되지 않은 이미지 타입 - 일반적으로 발생하지 않아야 하는 특수 값 |
|
|  | [getJpeg()](#getJpeg--) | JPEG 이미지 타입 |
|
|  | [getPng()](#getPng--) | PNG 이미지 타입 |
|
|  | [getBmp()](#getBmp--) | BMP 이미지 타입 |
|
|  | [getGif()](#getGif--) | GIF 이미지 타입 |
|
|  | [getIcon()](#getIcon--) | ICON 이미지 타입 |
|
|  | [getSvg()](#getSvg--) | SVG 벡터 이미지 타입 |
|
|  | [getWmf()](#getWmf--) | WMF (Windows MetaFile) 벡터 이미지 타입 |
|
|  | [getEmf()](#getEmf--) | EMF (Enhanced MetaFile) 벡터 이미지 유형 |
|
|  | [getTiff()](#getTiff--) | TIFF (Tagged Image File Format) 래스터 이미지 유형 |
|
|  | [getFormalName()](#getFormalName--) | 이 이미지 형식의 정식 이름을 반환합니다. |
|
|  | [isVector()](#isVector--) | 이 특정 형식이 벡터(true)인지 래스터인지 여부를 나타냅니다. |
(false)
|
|  | [getFileExtension()](#getFileExtension--) | 특정 이미지 유형의 파일 확장자(앞에 점 문자 없이) |
소문자로.
|
|  | [toString()](#toString--) | FormalName 속성을 반환합니다. |
|
|  | [getMimeCode()](#getMimeCode--) | 특정 이미지 유형의 MIME 코드를 문자열로 반환합니다. |
|
|  | [equals(ImageType other)](#equals-com.groupdocs.editor.htmlcss.resources.images.ImageType-) | 이 인스턴스가 지정된 \"ImageType\"과 같은지 여부를 판단합니다. |
인스턴스
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | 이 인스턴스가 지정된 형 변환되지 않은 객체와 같은지 여부를 결정합니다, |
이는 아마도 다른 \"ImageType\" 인스턴스일 것입니다.
|
|  | [op_Equality(ImageType first, ImageType second)](#op-Equality-com.groupdocs.editor.htmlcss.resources.images.ImageType-com.groupdocs.editor.htmlcss.resources.images.ImageType-) | 두 특정 ImageType 인스턴스가 같은지 여부를 정의합니다. |
|
|  | [op_Inequality(ImageType first, ImageType second)](#op-Inequality-com.groupdocs.editor.htmlcss.resources.images.ImageType-com.groupdocs.editor.htmlcss.resources.images.ImageType-) | 두 특정 ImageType 인스턴스가 같지 않은지 여부를 정의합니다. |
|
|  | [hashCode()](#hashCode--) | 이 특정 객체에 대한 불변 숫자인 해시 코드를 반환합니다. |
인스턴스
|
|  | [parseFromFilenameWithExtension(String filename)](#parseFromFilenameWithExtension-java.lang.String-) | 파일 확장자와 동일한 ImageType 값을 반환합니다, 이는 |
지정된 파일 이름에서 추출됩니다.
|
|  | [parseFromMime(String mimeCode)](#parseFromMime-java.lang.String-) | 지정된 MIME 코드와 동일한 ImageType 값을 반환합니다. |
|
### ImageType() {#ImageType--}
```
public ImageType()
```


### getUndefined() {#getUndefined--}
```
public static ImageType getUndefined()
```


정의되지 않은 이미지 타입 - 일반적으로 발생하지 않아야 하는 특수 값


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getJpeg() {#getJpeg--}
```
public static ImageType getJpeg()
```


JPEG 이미지 타입


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getPng() {#getPng--}
```
public static ImageType getPng()
```


PNG 이미지 타입


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getBmp() {#getBmp--}
```
public static ImageType getBmp()
```


BMP 이미지 타입


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getGif() {#getGif--}
```
public static ImageType getGif()
```


GIF 이미지 타입


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getIcon() {#getIcon--}
```
public static ImageType getIcon()
```


ICON 이미지 타입


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getSvg() {#getSvg--}
```
public static ImageType getSvg()
```


SVG 벡터 이미지 타입


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getWmf() {#getWmf--}
```
public static ImageType getWmf()
```


WMF (Windows MetaFile) 벡터 이미지 타입


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getEmf() {#getEmf--}
```
public static ImageType getEmf()
```


EMF (Enhanced MetaFile) 벡터 이미지 유형


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getTiff() {#getTiff--}
```
public static ImageType getTiff()
```


TIFF (Tagged Image File Format) 래스터 이미지 유형


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getFormalName() {#getFormalName--}
```
public final String getFormalName()
```


이 이미지 형식의 정식 이름을 반환합니다. 절대 NULL을 반환하지 않습니다. 만약
인스턴스가 손상되지 않은 경우 예외를 발생시키지 않습니다.


**Returns:**
java.lang.String
### isVector() {#isVector--}
```
public final boolean isVector()
```


이 특정 형식이 벡터(true)인지 래스터인지 여부를 나타냅니다.
(false)


**Returns:**
boolean
### getFileExtension() {#getFileExtension--}
```
public final String getFileExtension()
```


특정 이미지 유형의 파일 확장자(앞에 점 문자 없이)
소문자로. Undefined 유형의 경우 문자열 'unsefined'을 반환합니다.


**Returns:**
java.lang.String
### toString() {#toString--}
```
public String toString()
```


FormalName 속성을 반환합니다.


**Returns:**
java.lang.String -
### getMimeCode() {#getMimeCode--}
```
public final String getMimeCode()
```


특정 이미지 유형의 MIME 코드를 문자열로 반환합니다. Undefined 유형의 경우
문자열 'unsefined'을 반환합니다.


**Returns:**
java.lang.String
### equals(ImageType other) {#equals-com.groupdocs.editor.htmlcss.resources.images.ImageType-}
```
public final boolean equals(ImageType other)
```


이 인스턴스가 지정된 \"ImageType\"과 같은지 여부를 판단합니다.
인스턴스


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | other | [ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) | 이와 동등성을 확인하기 위한 다른 ImageType 인스턴스 |
|

**Returns:**
boolean - 같으면 true, 다르면 false

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


이 인스턴스가 지정된 형 변환되지 않은 객체와 같은지 여부를 결정합니다,
이는 아마도 다른 \"ImageType\" 인스턴스일 것입니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | obj | java.lang.Object | 이와 동등성을 확인하기 위한 다른 System.Object 인스턴스(아마 ImageType 유형일 것으로 추정됨) |
|

**Returns:**
boolean - 같으면 true, 다르면 false

### op_Equality(ImageType first, ImageType second) {#op-Equality-com.groupdocs.editor.htmlcss.resources.images.ImageType-com.groupdocs.editor.htmlcss.resources.images.ImageType-}
```
public static boolean op_Equality(ImageType first, ImageType second)
```


두 특정 ImageType 인스턴스가 같은지 여부를 정의합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | first | [ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) | 첫 번째 확인할 ImageType 인스턴스 |
|
|  | second | [ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) | 두 번째 ImageType 인스턴스를 확인 |
|

**Returns:**
boolean - 같으면 true, 다르면 false

### op_Inequality(ImageType first, ImageType second) {#op-Inequality-com.groupdocs.editor.htmlcss.resources.images.ImageType-com.groupdocs.editor.htmlcss.resources.images.ImageType-}
```
public static boolean op_Inequality(ImageType first, ImageType second)
```


두 특정 ImageType 인스턴스가 같지 않은지 여부를 정의합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | first | [ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) | 첫 번째 확인할 ImageType 인스턴스 |
|
|  | second | [ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) | 두 번째 ImageType 인스턴스를 확인 |
|

**Returns:**
boolean - 다르면 True, 같으면 false

### hashCode() {#hashCode--}
```
public int hashCode()
```


이 특정 객체에 대한 불변 숫자인 해시 코드를 반환합니다.
인스턴스


**Returns:**
int - 부호가 있는 4바이트 정수

### parseFromFilenameWithExtension(String filename) {#parseFromFilenameWithExtension-java.lang.String-}
```
public static ImageType parseFromFilenameWithExtension(String filename)
```


파일 확장자와 동일한 ImageType 값을 반환합니다, 이는
지정된 파일 이름에서 추출됩니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 파일 이름 | java.lang.String | 임의의 파일 이름으로, 상대 경로나 전체 경로일 수 있습니다 |
|

**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) - ImageType value. Returns ImageType.Undefined, if extension cannot be recognized.

### parseFromMime(String mimeCode) {#parseFromMime-java.lang.String-}
```
public static ImageType parseFromMime(String mimeCode)
```


지정된 MIME 코드와 동일한 ImageType 값을 반환합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | mimeCode | java.lang.String | 임의의 MIME-코드 |
|

**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) - ImageType value. Returns ImageType.Undefined, if extension cannot be recognized.

