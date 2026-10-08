---
title: "PresentationFormats"
second_title: "GroupDocs.Editor .NET용 API 레퍼런스"
description: "모든 프레젠테이션 형식을 캡슐화합니다. 다음 형식이 포함됩니다."
type: docs
weight: 120
url: /ko/net/groupdocs.editor.formats/presentationformats/
---
## PresentationFormats class

모든 프레젠테이션 형식을 캡슐화합니다. 다음 형식을 포함합니다:

* [`Odp`](./odp)
* [`Otp`](./otp)
* [`Pot`](./pot)
* [`Potm`](./potm)
* [`Potx`](./potx)
* [`Pps`](./pps)
* [`Ppsm`](./ppsm)
* [`Ppsx`](./ppsx)
* [`Ppt`](./ppt)
* [`Ppt95`](./ppt95)
* [`Pptm`](./pptm)
* [`Pptx`](./pptx)

프레젠테이션 형식에 대해 자세히 알아보려면 [여기](https://wiki.fileformat.com/presentation)를 클릭하세요.

```csharp
public class PresentationFormats : DocumentFormatBase
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [Extension](../../groupdocs.editor.formats.abstraction/documentformatbase/extension) { get; } | 문서 형식의 파일 확장자를 가져옵니다. |
| [FormatFamily](../../groupdocs.editor.formats.abstraction/documentformatbase/formatfamily) { get; } | 문서 형식이 속한 형식 패밀리를 가져옵니다. |
| [Id](../../groupdocs.editor.formats.abstraction/formatfamilybase/id) { get; } | 형식 패밀리의 고유 식별자를 가져옵니다. |
| [Mime](../../groupdocs.editor.formats.abstraction/documentformatbase/mime) { get; } | 문서 형식의 MIME 유형을 가져옵니다. |
| [Name](../../groupdocs.editor.formats.abstraction/formatfamilybase/name) { get; } | 형식 패밀리의 이름을 가져옵니다. |
| static [All](../../groupdocs.editor.formats/presentationformats/all) { get; } | 모든 [`PresentationFormats`](../presentationformats)의 열거 가능한 컬렉션을 가져옵니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| static [FromExtension](../../groupdocs.editor.formats/presentationformats/fromextension)(string) | 지정된 파일 확장자를 가진 지정 유형 [`PresentationFormats`](../presentationformats)의 인스턴스를 검색합니다. |
| [Equals](../../groupdocs.editor.formats.abstraction/formatfamilybase/equals)(FormatFamilyBase) | 이 인스턴스가 지정된 [`FormatFamilyBase`](../../groupdocs.editor.formats.abstraction/formatfamilybase) 인스턴스와 같은지 확인합니다. |
| [Equals](../../groupdocs.editor.formats.abstraction/documentformatbase/equals)(IDocumentFormat) | 이 인스턴스가 지정된 [`IDocumentFormat`](../../groupdocs.editor.formats.abstraction/idocumentformat) 인스턴스와 같은지 확인합니다. |
| override [Equals](../../groupdocs.editor.formats.abstraction/documentformatbase/equals)(object) | 이 인스턴스가 지정된 [`DocumentFormatBase`](../../groupdocs.editor.formats.abstraction/documentformatbase) 인스턴스와 같은지 확인합니다. |
| override [GetHashCode](../../groupdocs.editor.formats.abstraction/documentformatbase/gethashcode)() | 현재 객체에 대한 해시 코드를 반환합니다. |
| override [ToString](../../groupdocs.editor.formats.abstraction/formatfamilybase/tostring)() | 현재 객체를 나타내는 문자열을 반환합니다. |
| [explicit operator](../../groupdocs.editor.formats/presentationformats/op_explicit) | 파일 확장자를 나타내는 문자열을 [`PresentationFormats`](../presentationformats) 객체로 변환합니다. |

## 필드

| 이름 | 설명 |
| --- | --- |
| static readonly [Odp](../../groupdocs.editor.formats/presentationformats/odp) | OpenDocument 프레젠테이션 (ODP). 이 파일 형식에 대해 자세히 알아보려면 [여기](https://wiki.fileformat.com/presentation/odp)를 클릭하세요. |
| static readonly [Otp](../../groupdocs.editor.formats/presentationformats/otp) | OpenDocument 프레젠테이션 템플릿 (OTP). 이 파일 형식에 대해 자세히 알아보려면 [여기](https://wiki.fileformat.com/presentation/otp)를 클릭하세요. |
| static readonly [Pot](../../groupdocs.editor.formats/presentationformats/pot) | Microsoft PowerPoint 97-2003 프레젠테이션 템플릿 (POT). 이 파일 형식에 대해 자세히 알아보려면 [여기](https://wiki.fileformat.com/presentation/pot)를 클릭하세요. |
| static readonly [Potm](../../groupdocs.editor.formats/presentationformats/potm) | Microsoft Office Open XML PresentationML 매크로 사용 템플릿 (POTM). 이 파일 형식에 대해 자세히 알아보려면 [여기](https://wiki.fileformat.com/presentation/potm)를 클릭하세요. |
| static readonly [Potx](../../groupdocs.editor.formats/presentationformats/potx) | Microsoft Office Open XML PresentationML 매크로 없는 템플릿 (POTX). 이 파일 형식에 대해 자세히 알아보려면 [여기](https://wiki.fileformat.com/presentation/potx)를 클릭하세요. |
| static readonly [Pps](../../groupdocs.editor.formats/presentationformats/pps) | Microsoft PowerPoint 97-2003 슬라이드쇼 (PPS). 이 파일 형식에 대해 자세히 알아보려면 [여기](https://wiki.fileformat.com/presentation/pps)를 클릭하세요. |
| static readonly [Ppsm](../../groupdocs.editor.formats/presentationformats/ppsm) | Microsoft Office Open XML PresentationML 매크로 사용 슬라이드쇼 (PPSM). 이 파일 형식에 대해 자세히 알아보려면 [여기](https://wiki.fileformat.com/presentation/ppsm)를 클릭하세요. |
| static readonly [Ppsx](../../groupdocs.editor.formats/presentationformats/ppsx) | Microsoft Office Open XML PresentationML 매크로 없는 슬라이드쇼 (PPSX). 이 파일 형식에 대해 자세히 알아보려면 [여기](https://wiki.fileformat.com/presentation/ppsx)를 클릭하세요. |
| static readonly [Ppt](../../groupdocs.editor.formats/presentationformats/ppt) | Microsoft PowerPoint 97-2003 프레젠테이션 (PPT). 이 파일 형식에 대해 자세히 알아보려면 [여기](https://wiki.fileformat.com/presentation/ppt)를 클릭하세요. |
| static readonly [Ppt95](../../groupdocs.editor.formats/presentationformats/ppt95) | Microsoft PowerPoint 95 프레젠테이션 (PPT). |
| static readonly [Pptm](../../groupdocs.editor.formats/presentationformats/pptm) | Microsoft Office Open XML PresentationML 매크로 사용 문서 (PPTM). 이 파일 형식에 대해 자세히 알아보려면 [여기](https://wiki.fileformat.com/presentation/pptm)를 클릭하세요. |
| static readonly [Pptx](../../groupdocs.editor.formats/presentationformats/pptx) | Microsoft Office Open XML PresentationML 매크로 없는 문서 (PPTX). 이 파일 형식에 대해 자세히 알아보려면 [여기](https://wiki.fileformat.com/presentation/pptx)를 클릭하세요. |

### 참고

* class [DocumentFormatBase](../../groupdocs.editor.formats.abstraction/documentformatbase)
* namespace [GroupDocs.Editor.Formats](../../groupdocs.editor.formats)
* assembly [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.editor.dll -->
