---
title: "IImageResource"
second_title: "GroupDocs.Editor for Java API 참조"
description: "라스터 또는 벡터 등 모든 유형의 이미지 리소스를 나타냅니다"
type: docs
weight: 13
url: /ko/java/com.groupdocs.editor.htmlcss.resources.images/iimageresource/
---
**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.resources.IHtmlResource](../../com.groupdocs.editor.htmlcss.resources/ihtmlresource), [com.groupdocs.editor.htmlcss.resources.images.IImage](../../com.groupdocs.editor.htmlcss.resources.images/iimage)
```
public interface IImageResource extends IHtmlResource, IImage
```

모든 유형(래스터 또는 벡터)의 이미지 리소스를 나타냅니다.


*** ** * ** ***

https://developer.mozilla.org/en-US/docs/Web/CSS/image

<br />


## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getType()](#getType--) | 구현 시 타입은 특정 이미지의 유형을 반환해야 합니다 |
특정 ImageType 인스턴스로, 모든 유형별 정보를 캡슐화합니다
|
|  | [getAspectRatio()](#getAspectRatio--) | 구현 시 타입은 특정 이미지의 가로세로 비율을 반환해야 합니다 |
그 유형에 관계없이.
|
|  | [getLinearDimensions()](#getLinearDimensions--) | 구현 시 타입은 이미지의 선형 차원을 반환해야 합니다. |
|
### getType() {#getType--}
```
public abstract ImageType getType()
```


구현 시 타입은 특정 이미지의 유형을 반환해야 합니다
특정 ImageType 인스턴스로, 모든 유형별 정보를 캡슐화합니다


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getAspectRatio() {#getAspectRatio--}
```
public abstract Ratio getAspectRatio()
```


구현 시 타입은 특정 이미지의 가로세로 비율을 반환해야 합니다
그 유형에 관계없이. 벡터와 라스터 이미지 모두 고유한
너비와 높이 사이의 가로세로 비율을 가집니다.


**Returns:**
[Ratio](../../com.groupdocs.editor.htmlcss.css.datatypes/ratio) - 
### getLinearDimensions() {#getLinearDimensions--}
```
public abstract Dimensions getLinearDimensions()
```


구현 시 타입은 이미지의 선형 차원을 반환해야 합니다. 대상
라스터 이미지의 경우 픽셀 단위 고유 차원을 가집니다. 벡터 이미지의 경우,
반면 고정된 차원이 없지만 메타데이터에
다양한 측정 단위의 기본 차원들이 포함될 수 있습니다.


**Returns:**
[Dimensions](../../com.groupdocs.editor.htmlcss.resources.images/dimensions) - 
