---
title: FromMarkupAndResourceFolder
second_title: .NET API 참조용 GroupDocs.Editor
description: 전체 경로 로 지정된 폴더에 있는 리소스와 지정된 HTML 마크업에서 EditableDocument의 인스턴스를 생성하는 정적 팩터리
type: docs
weight: 30
url: /ko/net/groupdocs.editor/editabledocument/frommarkupandresourcefolder/
---
## EditableDocument.FromMarkupAndResourceFolder method

전체 경로 로 지정된 폴더에 있는 리소스와 지정된 HTML 마크업에서 EditableDocument의 인스턴스를 생성하는 정적 팩터리

```csharp
public static EditableDocument FromMarkupAndResourceFolder(string newHtmlContent, 
    string resourceFolderPath)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| newHtmlContent | String | 구문 분석해야 하는 원시 HTML 마크업을 포함하는 문자열입니다. NULL이거나 비어 있거나 유효하지 않을 수 없습니다. |
| resourceFolderPath | String | 리소스가 있는 폴더의 필수 경로입니다. 이 폴더에 있는 모든 스타일시트가 사용됩니다. NULL 또는 빈 문자열일 수 없으며 이 폴더가 있어야 합니다. |

### 반환 값

EditableDocument의 null이 아닌 새 인스턴스

### 비고

이 정적 팩토리는 HTML 문서의 내용이 문자열로 표시되지만 모든 리소스가 일부 폴더에 있고 HTML 마크업에서 이러한 리소스에 대한 링크가 유효하지 않거나 없는 경우에 유용합니다. 이 메소드를 호출하면 지정된 폴더를 스캔하고 발견된 모든 스타일시트를 문서에 자동으로 적용합니다. 이 방법은 일반적으로 문서 메타데이터 등을 차단하는 다른 HTML 편집기에서 콘텐츠를 가져올 때 매우 유용합니다.

### 또한보십시오

* class [EditableDocument](../../editabledocument)
* 네임스페이스 [GroupDocs.Editor](../../editabledocument)
* 집회 [GroupDocs.Editor](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->