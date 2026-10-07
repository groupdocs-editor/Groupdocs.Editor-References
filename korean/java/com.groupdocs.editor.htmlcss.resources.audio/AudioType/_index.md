---
title: "AudioType"
second_title: "GroupDocs.Editor for Java API 참조"
description: "지원 가능한 오디오 형식 중 하나를 나타냅니다"
type: docs
weight: 10
url: /ko/java/com.groupdocs.editor.htmlcss.resources.audio/audiotype/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.resources.IResourceType](../../com.groupdocs.editor.htmlcss.resources/iresourcetype)
```
public class AudioType implements IResourceType
```

지원 가능한 오디오 유형(포맷) 하나를 나타냅니다.

## 생성자

| 생성자 | 설명 |
| --- | --- |
| [AudioType()](#AudioType--) |  |
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getFormalName()](#getFormalName--) | 이 오디오 형식의 공식 이름 |
|
|  | [getFileExtension()](#getFileExtension--) | 이 오디오 형식의 파일 이름 확장자(점 문자 제외) |
|
|  | [getMimeCode()](#getMimeCode--) | 이 오디오 형식의 MIME 코드 |
|
|  | [equals(AudioType other)](#equals-com.groupdocs.editor.htmlcss.resources.audio.AudioType-) | 이 인스턴스가 지정된 "AudioType" 인스턴스와 같은지 여부를 결정합니다 |
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | 이 인스턴스가 지정된 형 변환되지 않은 객체와 같은지 여부를 결정합니다. 해당 객체는 다른 "AudioType" 인스턴스로 추정됩니다 |
|
|  | [op_Equality(AudioType first, AudioType second)](#op-Equality-com.groupdocs.editor.htmlcss.resources.audio.AudioType-com.groupdocs.editor.htmlcss.resources.audio.AudioType-) | 두 "AudioType" 값이 같은지 확인합니다 |
|
|  | [op_Inequality(AudioType first, AudioType second)](#op-Inequality-com.groupdocs.editor.htmlcss.resources.audio.AudioType-com.groupdocs.editor.htmlcss.resources.audio.AudioType-) | 두 "AudioType" 값이 같지 않은지 확인합니다 |
|
|  | [hashCode()](#hashCode--) | 이 특정 값 형식에 대해 상수인 해시 코드를 반환합니다 |
|
|  | [getUndefined()](#getUndefined--) | 정의되지 않았거나 알 수 없거나 지원되지 않는 오디오 형식을 표시하는 특수 값 |
|
|  | [getMp3()](#getMp3--) | MPEG-1 Audio Layer III 오디오 형식을 나타냅니다 |
|
|  | [parseFromFilenameWithExtension(String filename)](#parseFromFilenameWithExtension-java.lang.String-) | 지정된 파일 이름에서 추출한 파일 확장자와 동일한 AudioType 값을 반환합니다 |
|
### AudioType() {#AudioType--}
```
public AudioType()
```


### getFormalName() {#getFormalName--}
```
public final String getFormalName()
```


이 오디오 형식의 공식 이름


**Returns:**
java.lang.String
### getFileExtension() {#getFileExtension--}
```
public final String getFileExtension()
```


이 오디오 형식의 파일 이름 확장자(점 문자 제외)


**Returns:**
java.lang.String
### getMimeCode() {#getMimeCode--}
```
public final String getMimeCode()
```


이 오디오 형식의 MIME 코드


**Returns:**
java.lang.String
### equals(AudioType other) {#equals-com.groupdocs.editor.htmlcss.resources.audio.AudioType-}
```
public final boolean equals(AudioType other)
```


이 인스턴스가 지정된 "AudioType" 인스턴스와 같은지 여부를 결정합니다


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | other | [AudioType](../../com.groupdocs.editor.htmlcss.resources.audio/audiotype) | 이와 비교할 다른 AudioType 인스턴스 |
|

**Returns:**
boolean - 같으면 true, 다르면 false

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


이 인스턴스가 지정된 형 변환되지 않은 객체와 같은지 여부를 결정합니다. 해당 객체는 다른 "AudioType" 인스턴스로 추정됩니다


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | obj | java.lang.Object | AudioType 구조체의 다른 인스턴스로, System.Object에 박싱된 것으로 추정됩니다 |
|

**Returns:**
boolean - 같으면 true, 다르면 false

### op_Equality(AudioType first, AudioType second) {#op-Equality-com.groupdocs.editor.htmlcss.resources.audio.AudioType-com.groupdocs.editor.htmlcss.resources.audio.AudioType-}
```
public static boolean op_Equality(AudioType first, AudioType second)
```


두 "AudioType" 값이 같은지 확인합니다


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | first | [AudioType](../../com.groupdocs.editor.htmlcss.resources.audio/audiotype) | 첫 번째 확인할 AudioType |
|
|  | second | [AudioType](../../com.groupdocs.editor.htmlcss.resources.audio/audiotype) | 두 번째 확인할 AudioType |
|

**Returns:**
boolean - 같으면 true, 다르면 false

### op_Inequality(AudioType first, AudioType second) {#op-Inequality-com.groupdocs.editor.htmlcss.resources.audio.AudioType-com.groupdocs.editor.htmlcss.resources.audio.AudioType-}
```
public static boolean op_Inequality(AudioType first, AudioType second)
```


두 "AudioType" 값이 같지 않은지 확인합니다


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | first | [AudioType](../../com.groupdocs.editor.htmlcss.resources.audio/audiotype) | 첫 번째 확인할 AudioType |
|
|  | second | [AudioType](../../com.groupdocs.editor.htmlcss.resources.audio/audiotype) | 두 번째 확인할 AudioType |
|

**Returns:**
boolean - 같으면 true, 다르면 false

### hashCode() {#hashCode--}
```
public int hashCode()
```


이 특정 값 형식에 대해 상수인 해시 코드를 반환합니다


**Returns:**
int - 4바이트 부호 있는 정수, 정의되지 않은 값은 0

### getUndefined() {#getUndefined--}
```
public static AudioType getUndefined()
```


정의되지 않았거나 알 수 없거나 지원되지 않는 오디오 형식을 표시하는 특수 값


**Returns:**
[AudioType](../../com.groupdocs.editor.htmlcss.resources.audio/audiotype)
### getMp3() {#getMp3--}
```
public static AudioType getMp3()
```


MPEG-1 Audio Layer III 오디오 형식을 나타냅니다


**Returns:**
[AudioType](../../com.groupdocs.editor.htmlcss.resources.audio/audiotype)
### parseFromFilenameWithExtension(String filename) {#parseFromFilenameWithExtension-java.lang.String-}
```
public static AudioType parseFromFilenameWithExtension(String filename)
```


지정된 파일 이름에서 추출한 파일 확장자와 동일한 AudioType 값을 반환합니다


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 파일 이름 | java.lang.String | 임의의 파일 이름으로, 상대 경로나 전체 경로일 수 있습니다 |
|

**Returns:**
[AudioType](../../com.groupdocs.editor.htmlcss.resources.audio/audiotype) - AudioType value. Returns AudioType.Undefined, if extension cannot be recognized.

