---
title: TextEditOptions
second_title: .NET API 참조용 GroupDocs.Editor
description: 일반 텍스트TXT 문서를 로드하기 위한 사용자 지정 옵션을 지정할 수 있습니다
type: docs
weight: 1140
url: /ko/net/groupdocs.editor.options/texteditoptions/
---
## TextEditOptions class

일반 텍스트(TXT) 문서를 로드하기 위한 사용자 지정 옵션을 지정할 수 있습니다

```csharp
public class TextEditOptions : IEditOptions
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [TextEditOptions](texteditoptions)() | 기본 생성자입니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [Direction](../../groupdocs.editor.options/texteditoptions/direction) { get; set; } | 입력된 일반 텍스트 문서에서 텍스트 흐름의 방향을 지정할 수 있습니다. 기본적으로 왼쪽에서 오른쪽입니다. |
| [EnablePagination](../../groupdocs.editor.options/texteditoptions/enablepagination) { get; set; } | 결과 HTML 문서에서 페이지 매김을 활성화하거나 비활성화할 수 있습니다. 기본적으로 비활성화되어 있습니다(false). |
| [Encoding](../../groupdocs.editor.options/texteditoptions/encoding) { get; set; } | 오프닝에 적용될 텍스트 문서의 문자 인코딩 |
| [LeadingSpaces](../../groupdocs.editor.options/texteditoptions/leadingspaces) { get; set; } | 선행 공백 처리의 기본 옵션을 가져오거나 설정합니다. 기본적으로 선행 공백을 왼쪽 들여쓰기로 변환합니다. |
| [RecognizeLists](../../groupdocs.editor.options/texteditoptions/recognizelists) { get; set; } | 일반 텍스트 형식에서 문서를 가져올 때 번호 매기기 목록 항목을 인식하는 방법을 지정할 수 있습니다. 기본값은 true입니다. |
| [TrailingSpaces](../../groupdocs.editor.options/texteditoptions/trailingspaces) { get; set; } | 후행 공백 처리의 기본 옵션을 가져오거나 설정합니다. 기본적으로 모든 후행 공백을 자릅니다. |

### 또한보십시오

* interface [IEditOptions](../ieditoptions)
* 네임스페이스 [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* 집회 [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->