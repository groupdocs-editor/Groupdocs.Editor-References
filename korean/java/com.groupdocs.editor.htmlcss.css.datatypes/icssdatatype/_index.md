---
title: "ICssDataType"
second_title: "GroupDocs.Editor for Java API 참조"
description: "CSS 속성에서 사용되는 모든 CSS 데이터 유형에 대한 공통 인터페이스"
type: docs
weight: 15
url: /ko/java/com.groupdocs.editor.htmlcss.css.datatypes/icssdatatype/
---
**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable
```
public interface ICssDataType extends System.IEquatable<ICssDataType>
```

CSS 속성에서 사용되는 모든 CSS 데이터 유형을 위한 공통 인터페이스

## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [serializeDefault()](#serializeDefault--) | 현재 값의 기본 문자열 표현을 반환해야 합니다 |
데이터 유형
|
|  | [isDefault()](#isDefault--) | 데이터 유형의 현재 값이 기본값인지 여부를 정의해야 합니다 |
특정 데이터 유형에 대한 값인지 여부
|
### serializeDefault() {#serializeDefault--}
```
public abstract String serializeDefault()
```


현재 값의 기본 문자열 표현을 반환해야 합니다
데이터 유형


**Returns:**
java.lang.String -
### isDefault() {#isDefault--}
```
public abstract boolean isDefault()
```


데이터 유형의 현재 값이 기본값인지 여부를 정의해야 합니다
특정 데이터 유형에 대한 값인지 여부


**Returns:**
boolean -
