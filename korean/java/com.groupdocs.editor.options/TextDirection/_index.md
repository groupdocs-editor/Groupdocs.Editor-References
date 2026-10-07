---
title: "TextDirection"
second_title: "GroupDocs.Editor for Java API 참조"
description: "일반 텍스트 문서에서 텍스트 방향을 처리하는 3가지 가능한 변형을 나타냅니다."
type: docs
weight: 38
url: /ko/java/com.groupdocs.editor.options/textdirection/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class TextDirection extends System.Enum
```

일반 텍스트에서 텍스트 방향을 처리하는 3가지 가능한 변형을 나타냅니다.
문서

## 필드

| 필드 | 설명 |
| --- | --- |
|  | [LeftToRight](#LeftToRight) | 왼쪽에서 오른쪽 방향, 일반 텍스트, 기본값. |
|
|  | [RightToLeft](#RightToLeft) | 오른쪽에서 왼쪽 방향 |
|
|  | [Auto](#Auto) | 방향 자동 감지. |
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getTextDirection()](#getTextDirection--) |  |
### LeftToRight {#LeftToRight}
```
public static final int LeftToRight
```


왼쪽에서 오른쪽 방향, 일반 텍스트, 기본값.


### RightToLeft {#RightToLeft}
```
public static final int RightToLeft
```


오른쪽에서 왼쪽 방향


### Auto {#Auto}
```
public static final int Auto
```


방향 자동 감지. 이 옵션을 선택하고 텍스트에
RTL 스크립트에 속하는 문자가 포함된 경우, 문서 방향이
자동으로 RTL로 설정됩니다.


### getTextDirection() {#getTextDirection--}
```
public static int[] getTextDirection()
```




**Returns:**
int[]
