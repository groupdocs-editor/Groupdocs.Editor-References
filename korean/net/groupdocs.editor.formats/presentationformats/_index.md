---
title: PresentationFormats
second_title: .NET API 참조용 GroupDocs.Editor
description: 모든 프레젠테이션 형식을 캡슐화합니다. 다음 형식을 포함합니다. Odp./presentationformats/odp  Otp./presentationformats/otp  Pot./presentationformats/pot  Potm./presentationformats/potm  Potx./presentationformats/potx  Pps./presentationformats/pps  Ppsm./presentationformats/ppsm  Ppsx./presentationformats/ppsx  Ppt./presentationformats/ppt  Ppt95./presentationformats/ppt95  Pptm./presentationformats/pptm  Pptx./presentationformats/pptx. 프레젠테이션 형식에 대해 자세히 알아보기여기https//wiki.fileformat.com/presentation .
type: docs
weight: 110
url: /ko/net/groupdocs.editor.formats/presentationformats/
---
## PresentationFormats structure

모든 프레젠테이션 형식을 캡슐화합니다. 다음 형식을 포함합니다. [`Odp`](./odp) , [`Otp`](./otp) , [`Pot`](./pot) , [`Potm`](./potm) , [`Potx`](./potx) , [`Pps`](./pps) , [`Ppsm`](./ppsm) , [`Ppsx`](./ppsx) , [`Ppt`](./ppt) , [`Ppt95`](./ppt95) , [`Pptm`](./pptm) , [`Pptx`](./pptx). 프레젠테이션 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/presentation) .

```csharp
public struct PresentationFormats : IDocumentFormat, IEquatable<PresentationFormats>
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [Extension](../../groupdocs.editor.formats/presentationformats/extension) { get; } | 이 프리젠테이션 형식의 확장자(선행 점 문자 없음)를 소문자 로 반환합니다. |
| [Mime](../../groupdocs.editor.formats/presentationformats/mime) { get; } | 이 format 에 대한 MIME 코드를 반환합니다. |
| [Name](../../groupdocs.editor.formats/presentationformats/name) { get; } | 이 프레젠테이션 format 의 공식적인 전체 이름을 반환합니다. |

## 행동 양식

| 이름 | 설명 |
| --- | --- |
| static [FromExtension](../../groupdocs.editor.formats/presentationformats/fromextension)(string) | 인스턴스 반환[`PresentationFormats`](../presentationformats) 지정된 파일 이름 확장자와 연결된 구조이거나 확장자를 제대로 구문 분석할 수 없는 경우 예외가 발생합니다 |
| [Equals](../../groupdocs.editor.formats/presentationformats/equals#equals)(IDocumentFormat) | 이 인스턴스가 지정된 다른 IDocumentFormat instance 와 같은지 여부를 결정합니다. |
| override [Equals](../../groupdocs.editor.formats/presentationformats/equals#equals_2)(object) | 이 인스턴스가 다른 지정된 개체, 즉 boxed PresentationFormats 와 같은지 여부를 결정합니다. |
| [Equals](../../groupdocs.editor.formats/presentationformats/equals#equals_1)(PresentationFormats) | 이 인스턴스가 지정된 다른 PresentationFormats instance 와 같은지 여부를 결정합니다. |
| override [GetHashCode](../../groupdocs.editor.formats/presentationformats/gethashcode)() | 이 instance 에 대해 변경할 수 없는 해시 코드를 반환합니다. |
| [operator ==](../../groupdocs.editor.formats/presentationformats/op_equality) | equal 에서 두 개의 지정된 PresentationFormats 인스턴스를 확인합니다. |
| [operator !=](../../groupdocs.editor.formats/presentationformats/op_inequality) | inequality 에서 두 개의 지정된 PresentationFormats 인스턴스를 확인합니다. |

## 필드

| 이름 | 설명 |
| --- | --- |
| static readonly [Odp](../../groupdocs.editor.formats/presentationformats/odp) | ODP(OpenDocument Presentation) 파일은 OASISOpen 표준에서 OpenOffice.org에서 사용하는 프레젠테이션 파일 형식을 나타냅니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/presentation/odp) . |
| static readonly [Otp](../../groupdocs.editor.formats/presentationformats/otp) | OpenDocument 프리젠테이션 템플릿(OTP) 파일은 OASIS OpenDocument 표준 형식의 응용 프로그램에서 만든 프리젠테이션 템플릿 파일을 나타냅니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/presentation/otp) . |
| static readonly [Pot](../../groupdocs.editor.formats/presentationformats/pot) | Microsoft PowerPoint 97-2003 프레젠테이션 템플릿(POT) 파일은 PowerPoint 97-2003 버전에서 만든 Microsoft PowerPoint 템플릿 파일을 나타냅니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/presentation/pot) . |
| static readonly [Potm](../../groupdocs.editor.formats/presentationformats/potm) | Microsoft Office Open XML PresentationML POTM(Macro-Enabled Template)은 매크로를 지원하는 파일입니다. POTM 파일은 PowerPoint 2007 이상에서 생성되며 추가 프레젠테이션 파일을 생성하는 데 사용할 수 있는 기본 설정을 포함합니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/presentation/potm) . |
| static readonly [Potx](../../groupdocs.editor.formats/presentationformats/potx) | Microsoft Office Open XML PresentationML POTX(Macro-Free Template) 파일은 Microsoft PowerPoint 2007 이상에서 생성된 Microsoft PowerPoint 템플릿 프레젠테이션을 나타냅니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/presentation/potx) . |
| static readonly [Pps](../../groupdocs.editor.formats/presentationformats/pps) | Microsoft PowerPoint 97-2003 SlideShow(PPS) 파일은 슬라이드 쇼용으로 Microsoft PowerPoint를 사용하여 생성됩니다. PPS 파일 읽기 및 생성은 Microsoft PowerPoint 97-2003에서 지원됩니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/presentation/pps) . |
| static readonly [Ppsm](../../groupdocs.editor.formats/presentationformats/ppsm) | Microsoft Office Open XML PresentationML PPSM(Macro-Enabled SlideShow) 파일은 Microsoft PowerPoint 2007 이상에서 생성됩니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/presentation/ppsm) . |
| static readonly [Ppsx](../../groupdocs.editor.formats/presentationformats/ppsx) | Microsoft Office Open XML PresentationML PPSX(Macro-Free SlideShow) 파일은 슬라이드 쇼 목적으로 Microsoft PowerPoint 2007 이상을 사용하여 생성됩니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/presentation/ppsx) . |
| static readonly [Ppt](../../groupdocs.editor.formats/presentationformats/ppt) | PowerPoint 프레젠테이션(.ppt)은 슬라이드 쇼로 표시하기 위한 슬라이드 모음으로 구성된 PowerPoint 파일을 나타냅니다. Microsoft PowerPoint 97-2003에서 사용하는 이진 파일 형식을 지정합니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/presentation/ppt) . |
| static readonly [Ppt95](../../groupdocs.editor.formats/presentationformats/ppt95) | Microsoft PowerPoint 95 프레젠테이션(PPT) |
| static readonly [Pptm](../../groupdocs.editor.formats/presentationformats/pptm) | Microsoft PowerPoint 2007 이상 버전에서 생성된 Microsoft Office Open XML PresentationML PPTM(Macro-Enabled Document) 파일. 그들은 매크로를 포함할 수 있지만 측면이 매크로를 실행할 수 없다는 차이점을 제외하면 PPTX 파일과 유사합니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/presentation/pptm) . |
| static readonly [Pptx](../../groupdocs.editor.formats/presentationformats/pptx) | PowerPoint Open XML 프레젠테이션(.pptx)은 널리 사용되는 Microsoft PowerPoint 응용 프로그램으로 만든 프레젠테이션 파일입니다. 프레젠테이션 파일 형식 PPT의 이전 버전인 바이너리와 달리 PPTX 형식은 Microsoft PowerPoint 개방형 XML 프레젠테이션 파일 형식을 기반으로 합니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/presentation/pptx) . |
| static readonly [All](../../groupdocs.editor.formats/presentationformats/all) | 기존의 모든 프레젠테이션 형식에 대해 열거 가능한 가능성을 제공하는 내부 클래스를 반환합니다. |

## 다른 멤버들

| 이름 | 설명 |
| --- | --- |
| class [AllEnumerable](presentationformats.allenumerable) | PresentationFormats type 에 대한 'foreach' 가능성을 활성화하는 IEnumerable 일반 인터페이스를 구현합니다. |

### 또한보십시오

* interface [IDocumentFormat](../idocumentformat)
* 네임스페이스 [GroupDocs.Editor.Formats](../../groupdocs.editor.formats)
* 집회 [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
