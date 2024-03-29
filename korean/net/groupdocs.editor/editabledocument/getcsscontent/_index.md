---
title: GetCssContent
second_title: .NET API 참조용 GroupDocs.Editor
description: 모든 외부 스타일시트의 내용을 문자열 목록으로 반환합니다. 여기서 하나의 문자열은 하나의 스타일시트를 나타냅니다. 이 문서에 대한 CSS가 없는 경우 빈 목록을 반환합니다.
type: docs
weight: 140
url: /ko/net/groupdocs.editor/editabledocument/getcsscontent/
---
## GetCssContent() {#getcsscontent}

모든 외부 스타일시트의 내용을 문자열 목록으로 반환합니다. 여기서 하나의 문자열은 하나의 스타일시트를 나타냅니다. 이 문서에 대한 CSS가 없는 경우 빈 목록을 반환합니다.

```csharp
public List<string> GetCssContent()
```

### 반환 값

각 문자열이 하나의 CSS 문서의 내용을 포함하는 문자열 목록

### 또한보십시오

* class [EditableDocument](../../editabledocument)
* 네임스페이스 [GroupDocs.Editor](../../editabledocument)
* 집회 [GroupDocs.Editor](../../../)

---

## GetCssContent(string, string) {#getcsscontent_1}

모든 외부 스타일시트의 내용을 문자열 목록으로 반환합니다. 여기서 하나의 문자열은 하나의 스타일시트를 나타냅니다. 지정된 접두사는 모든 결과 스타일시트의 외부 리소스에 대한 모든 링크에 적용됩니다. 이에 대한 CSS가 없는 경우 빈 목록을 반환합니다. 문서.

```csharp
public List<string> GetCssContent(string externalImagesPrefix, string externalFontsPrefix)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| externalImagesPrefix | String | 사용된 이 매개변수를 통해 결과 CSS 문자열의 CSS 선언에 표시될 모든 외부 이미지에 대한 링크 에 추가될 접두어를 지정할 수 있습니다. NULL이거나 비어 있으면 접두사가 추가되지 않습니다. |
| externalFontsPrefix | String | 이 매개변수를 통해 결과 CSS 문자열의 @font-face at-rules에 있는 모든 외부 글꼴에 link 에 추가될 접두어를 지정할 수 있습니다. NULL이거나 비어 있으면 접두사가 추가되지 않습니다. |

### 반환 값

각 문자열이 하나의 CSS 문서의 내용을 포함하는 문자열 목록

### 또한보십시오

* class [EditableDocument](../../editabledocument)
* 네임스페이스 [GroupDocs.Editor](../../editabledocument)
* 집회 [GroupDocs.Editor](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
