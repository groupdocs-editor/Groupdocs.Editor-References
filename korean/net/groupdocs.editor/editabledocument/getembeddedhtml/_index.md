---
title: GetEmbeddedHtml
second_title: .NET API 참조용 GroupDocs.Editor
description: 모든 관련 리소스와 함께 이 HTML 문서의 모든 콘텐츠를 단일 문자열 형식으로 반환합니다. 여기서 모든 리소스는 base64로 인코딩된 형식의 HTML 마크업에 포함됩니다.
type: docs
weight: 150
url: /ko/net/groupdocs.editor/editabledocument/getembeddedhtml/
---
## EditableDocument.GetEmbeddedHtml method

모든 관련 리소스와 함께 이 HTML 문서의 모든 콘텐츠를 단일 문자열 형식으로 반환합니다. 여기서 모든 리소스는 base64로 인코딩된 형식의 HTML 마크업에 포함됩니다.

```csharp
public string GetEmbeddedHtml()
```

### 반환 값

어떤 경우에도 NULL이 아니거나 비어 있지 않은 문자열

### 예외

| 예외 | 상태 |
| --- | --- |
| ObjectDisposedException | 이 EditableDocument 인스턴스는 이미 삭제되었습니다. |

### 비고

이 메서드는 이 EditableDocument를 HTML로 변환하고 모든 리소스가 HTML 마크업과 함께 문자열에 포함되는 단일 문자열인 로 직렬화합니다.

* HTML-&gt;BODY의 모든 이미지는 base64 형식으로 변환되며 IMG 'src' 속성에 있습니다.
* 모든 스타일시트는 HTML-&gt;HEAD 섹션 내의 STYLE 요소에 저장됩니다.
* 스타일시트의 모든 이미지는 base64 형식으로 변환되고 적절한 CSS 선언에 위치합니다.
* 스타일시트의 모든 글꼴은 base64 형식으로 변환되고 적절한 @font-face at-rules에 위치합니다.

### 또한보십시오

* class [EditableDocument](../../editabledocument)
* 네임스페이스 [GroupDocs.Editor](../../editabledocument)
* 집회 [GroupDocs.Editor](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->