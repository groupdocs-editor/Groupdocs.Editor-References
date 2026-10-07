---
title: "PresentationFormats"
second_title: "GroupDocs.Editor for Java API 참조"
description: "모든 프레젠테이션 형식을 캡슐화합니다."
type: docs
weight: 14
url: /ko/java/com.groupdocs.editor.formats/presentationformats/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.formats.abstraction.FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase), [com.groupdocs.editor.formats.abstraction.DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase)
```
public class PresentationFormats extends DocumentFormatBase
```

모든 프레젠테이션 형식을 캡슐화합니다. 다음 형식이 포함됩니다:
[Odp](../../com.groupdocs.editor.formats/presentationformats#Odp),
[Otp](../../com.groupdocs.editor.formats/presentationformats#Otp),
[Pot](../../com.groupdocs.editor.formats/presentationformats#Pot),
[Potm](../../com.groupdocs.editor.formats/presentationformats#Potm),
[Potx](../../com.groupdocs.editor.formats/presentationformats#Potx),
[Pps](../../com.groupdocs.editor.formats/presentationformats#Pps),
[Ppsm](../../com.groupdocs.editor.formats/presentationformats#Ppsm),
[Ppsx](../../com.groupdocs.editor.formats/presentationformats#Ppsx),
[Ppt](../../com.groupdocs.editor.formats/presentationformats#Ppt),
[Ppt95](../../com.groupdocs.editor.formats/presentationformats#Ppt95),
[Pptm](../../com.groupdocs.editor.formats/presentationformats#Pptm),
[Pptx](../../com.groupdocs.editor.formats/presentationformats#Pptx).
프레젠테이션 형식에 대해 자세히 알아보려면 [여기](../https://wiki.fileformat.com/presentation)를 클릭하세요.

## 필드

| 필드 | 설명 |
| --- | --- |
|  | [Ppt](#Ppt) | Microsoft PowerPoint 97-2003 프레젠테이션 (PPT). |
|
|  | [Ppt95](#Ppt95) | Microsoft PowerPoint 95 프레젠테이션 (PPT). |
|
|  | [Pptx](#Pptx) | Microsoft Office Open XML PresentationML 매크로 없음 문서 (PPTX). |
|
|  | [Pptm](#Pptm) | Microsoft Office Open XML PresentationML 매크로 포함 문서 (PPTM). |
|
|  | [Pps](#Pps) | Microsoft PowerPoint 97-2003 슬라이드쇼 (PPS). |
|
|  | [Ppsx](#Ppsx) | Microsoft Office Open XML PresentationML 매크로 없음 슬라이드쇼 (PPSX). |
|
|  | [Ppsm](#Ppsm) | Microsoft Office Open XML PresentationML 매크로 포함 슬라이드쇼 (PPSM). |
|
|  | [Pot](#Pot) | Microsoft PowerPoint 97-2003 프레젠테이션 템플릿 (POT). |
|
|  | [Potx](#Potx) | Microsoft Office Open XML PresentationML 매크로 없는 템플릿 (POTX). |
|
|  | [Potm](#Potm) | Microsoft Office Open XML PresentationML 매크로 사용 가능 템플릿 (POTM). |
|
|  | [Odp](#Odp) | OpenDocument 프레젠테이션 (ODP). |
|
|  | [Otp](#Otp) | OpenDocument 프레젠테이션 템플릿 (OTP). |
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getAll()](#getAll--) | 모든 [PresentationFormats](../../com.groupdocs.editor.formats/presentationformats)의 열거 가능한 컬렉션을 가져옵니다. |
|
|  | [fromExtension(String extension)](#fromExtension-java.lang.String-) | 지정된 파일 확장자를 가진 지정된 유형 [PresentationFormats](../../com.groupdocs.editor.formats/presentationformats)의 인스턴스를 검색합니다. |
|
|  | [fromString(String extension)](#fromString-java.lang.String-) | 파일 확장자를 나타내는 문자열을 [PresentationFormats](../../com.groupdocs.editor.formats/presentationformats) 객체로 변환합니다. |
|
### Ppt {#Ppt}
```
public static final PresentationFormats Ppt
```


Microsoft PowerPoint 97-2003 프레젠테이션 (PPT).
이 파일 형식에 대해 자세히 알아보세요
[here](../https://wiki.fileformat.com/presentation/ppt)
.


### Ppt95 {#Ppt95}
```
public static final PresentationFormats Ppt95
```


Microsoft PowerPoint 95 프레젠테이션 (PPT).


### Pptx {#Pptx}
```
public static final PresentationFormats Pptx
```


Microsoft Office Open XML PresentationML 매크로 없음 문서 (PPTX).
이 파일 형식에 대해 자세히 알아보세요
[here](../https://wiki.fileformat.com/presentation/pptx)
.


### Pptm {#Pptm}
```
public static final PresentationFormats Pptm
```


Microsoft Office Open XML PresentationML 매크로 포함 문서 (PPTM).
이 파일 형식에 대해 자세히 알아보세요
[here](../https://wiki.fileformat.com/presentation/pptm)
.


### Pps {#Pps}
```
public static final PresentationFormats Pps
```


Microsoft PowerPoint 97-2003 슬라이드쇼 (PPS).
이 파일 형식에 대해 자세히 알아보세요
[here](../https://wiki.fileformat.com/presentation/pps)
.


### Ppsx {#Ppsx}
```
public static final PresentationFormats Ppsx
```


Microsoft Office Open XML PresentationML 매크로 없음 슬라이드쇼 (PPSX).
이 파일 형식에 대해 자세히 알아보세요
[here](../https://wiki.fileformat.com/presentation/ppsx)
.


### Ppsm {#Ppsm}
```
public static final PresentationFormats Ppsm
```


Microsoft Office Open XML PresentationML 매크로 포함 슬라이드쇼 (PPSM).
이 파일 형식에 대해 자세히 알아보세요
[here](../https://wiki.fileformat.com/presentation/ppsm)
.


### Pot {#Pot}
```
public static final PresentationFormats Pot
```


Microsoft PowerPoint 97-2003 프레젠테이션 템플릿 (POT).
이 파일 형식에 대해 자세히 알아보세요
[here](../https://wiki.fileformat.com/presentation/pot)
.


### Potx {#Potx}
```
public static final PresentationFormats Potx
```


Microsoft Office Open XML PresentationML 매크로 없는 템플릿 (POTX).
이 파일 형식에 대해 자세히 알아보세요
[here](../https://wiki.fileformat.com/presentation/potx)
.


### Potm {#Potm}
```
public static final PresentationFormats Potm
```


Microsoft Office Open XML PresentationML 매크로 사용 가능 템플릿 (POTM).
이 파일 형식에 대해 자세히 알아보세요
[here](../https://wiki.fileformat.com/presentation/potm)
.


### Odp {#Odp}
```
public static final PresentationFormats Odp
```


OpenDocument 프레젠테이션 (ODP).
이 파일 형식에 대해 자세히 알아보세요
[here](../https://wiki.fileformat.com/presentation/odp)
.


### Otp {#Otp}
```
public static final PresentationFormats Otp
```


OpenDocument 프레젠테이션 템플릿 (OTP).
이 파일 형식에 대해 자세히 알아보세요
[here](../https://wiki.fileformat.com/presentation/otp)
.


### getAll() {#getAll--}
```
public static List<PresentationFormats> getAll()
```


모든 [PresentationFormats](../../com.groupdocs.editor.formats/presentationformats)의 열거 가능한 컬렉션을 가져옵니다.
값: 모든 [PresentationFormats](../../com.groupdocs.editor.formats/presentationformats) 인스턴스를 포함하는 IEnumerable{PresentationFormats}.


**Returns:**
java.util.List<com.groupdocs.editor.formats.PresentationFormats>
### fromExtension(String extension) {#fromExtension-java.lang.String-}
```
public static PresentationFormats fromExtension(String extension)
```


지정된 파일 확장자를 가진 지정된 유형 [PresentationFormats](../../com.groupdocs.editor.formats/presentationformats)의 인스턴스를 검색합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 확장자 | java.lang.String | 문서 형식의 파일 확장자입니다. |
|

**Returns:**
[PresentationFormats](../../com.groupdocs.editor.formats/presentationformats) - An instance of the specified type [PresentationFormats](../../com.groupdocs.editor.formats/presentationformats) with the specified file extension.

### fromString(String extension) {#fromString-java.lang.String-}
```
public static PresentationFormats fromString(String extension)
```


파일 확장자를 나타내는 문자열을 [PresentationFormats](../../com.groupdocs.editor.formats/presentationformats) 객체로 변환합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 확장자 | java.lang.String | 변환할 파일 확장자입니다. 확장자에 마침표가 여러 개 포함된 경우, 마지막 마침표 이후의 부분이 사용됩니다. |
|

**Returns:**
[PresentationFormats](../../com.groupdocs.editor.formats/presentationformats) - A [PresentationFormats](../../com.groupdocs.editor.formats/presentationformats) object corresponding to the specified file extension.

