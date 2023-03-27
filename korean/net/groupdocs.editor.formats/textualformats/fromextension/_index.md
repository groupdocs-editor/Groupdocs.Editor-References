---
title: FromExtension
second_title: .NET API 참조용 GroupDocs.Editor
description: 인스턴스 반환TextualFormatsgroupdocs.editor.formats/textualformats 지정된 파일 이름 확장자와 연결된 구조이거나 확장자를 제대로 구문 분석할 수 없는 경우 예외가 발생합니다
type: docs
weight: 80
url: /ko/net/groupdocs.editor.formats/textualformats/fromextension/
---
## TextualFormats.FromExtension method

인스턴스 반환[`TextualFormats`](../../textualformats) 지정된 파일 이름 확장자와 연결된 구조이거나 확장자를 제대로 구문 분석할 수 없는 경우 예외가 발생합니다

```csharp
public static TextualFormats FromExtension(string extension)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| extension | String | 지원 가능한 텍스트 형식의 파일 이름 확장자, 선행 점 문자 포함 여부, 대소문자 독립적. NULL이거나 비어 있을 수 없으며 유효해야 합니다. |

### 반환 값

성공 시 TextualFormats 구조의 인스턴스 또는 실패 시 예외 발생

### 또한보십시오

* struct [TextualFormats](../../textualformats)
* 네임스페이스 [GroupDocs.Editor.Formats](../../textualformats)
* 집회 [GroupDocs.Editor](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->