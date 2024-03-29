---
title: TextType
second_title: .NET API 참조용 GroupDocs.Editor
description: 지원 가능한 하나의 텍스트 리소스 type 를 나타냅니다.
type: docs
weight: 650
url: /ko/net/groupdocs.editor.htmlcss.resources.textual/texttype/
---
## TextType structure

지원 가능한 하나의 텍스트 리소스 type 를 나타냅니다.

```csharp
public struct TextType : IEquatable<TextType>, IResourceType
```

## 속성

| 이름 | 설명 |
| --- | --- |
| static [Css](../../groupdocs.editor.htmlcss.resources.textual/texttype/css) { get; } | 텍스트 리소스의 CSS 유형 |
| static [Undefined](../../groupdocs.editor.htmlcss.resources.textual/texttype/undefined) { get; } | 정의되지 않았거나 알 수 없거나 지원되지 않는 텍스트 리소스 를 표시하는 특수 값 |
| static [Xml](../../groupdocs.editor.htmlcss.resources.textual/texttype/xml) { get; } | 텍스트 리소스의 XML 유형 |
| [FileExtension](../../groupdocs.editor.htmlcss.resources.textual/texttype/fileextension) { get; } | 특정 텍스트 리소스 의 파일 확장자(선행 점 문자 없음) |
| [FormalName](../../groupdocs.editor.htmlcss.resources.textual/texttype/formalname) { get; } | 이 텍스트 리소스 type 의 공식 이름을 반환합니다. |
| [MimeCode](../../groupdocs.editor.htmlcss.resources.textual/texttype/mimecode) { get; } | 특정 텍스트 자원 type 의 MIME 코드 |

## 행동 양식

| 이름 | 설명 |
| --- | --- |
| static [ParseFromFilenameWithExtension](../../groupdocs.editor.htmlcss.resources.textual/texttype/parsefromfilenamewithextension)(string) | 확장자가 지정된 파일 이름 또는 순수 확장자 에서 추출한 파일 이름 확장자에 해당하는 TextType 값을 반환합니다. |
| override [Equals](../../groupdocs.editor.htmlcss.resources.textual/texttype/equals#equals_1)(object) | 이 인스턴스가 다른 "TextType" instance 인 지정된 캐스팅되지 않은 개체와 같은지 여부를 결정합니다. |
| [Equals](../../groupdocs.editor.htmlcss.resources.textual/texttype/equals#equals)(TextType) | 이 인스턴스가 지정된 "TextType" instance 와 같은지 여부를 결정합니다. |
| override [GetHashCode](../../groupdocs.editor.htmlcss.resources.textual/texttype/gethashcode)() | 이 특정 값 type 에 대한 상수인 해시 코드를 반환합니다. |
| [operator ==](../../groupdocs.editor.htmlcss.resources.textual/texttype/op_equality) | 두 개의 특정 "TextType" 인스턴스가 같은지 여부를 정의합니다 |
| [operator !=](../../groupdocs.editor.htmlcss.resources.textual/texttype/op_inequality) | 두 개의 특정 "TextType" 인스턴스가 같지 않은지 여부를 정의합니다 |

### 또한보십시오

* interface [IResourceType](../../groupdocs.editor.htmlcss.resources/iresourcetype)
* 네임스페이스 [GroupDocs.Editor.HtmlCss.Resources.Textual](../../groupdocs.editor.htmlcss.resources.textual)
* 집회 [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
