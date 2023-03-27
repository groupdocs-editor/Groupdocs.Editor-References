---
title: SpreadsheetLoadOptions
second_title: .NET API 참조용 GroupDocs.Editor
description: XLSX ODS 등과 같은 이진 스프레드시트셀 Excel 호환 문서를 편집기에 로드하기 위한 옵션 포함 class
type: docs
weight: 1110
url: /ko/net/groupdocs.editor.options/spreadsheetloadoptions/
---
## SpreadsheetLoadOptions class

XLS(X), ODS 등과 같은 이진 스프레드시트(셀, Excel 호환) 문서를 편집기에 로드하기 위한 옵션 포함 class

```csharp
public sealed class SpreadsheetLoadOptions : ILoadOptions
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [SpreadsheetLoadOptions](spreadsheetloadoptions)() | 기본 매개변수 없는 생성자 - 모든 매개변수에 기본값이 있음 |

## 속성

| 이름 | 설명 |
| --- | --- |
| [OptimizeMemoryUsage](../../groupdocs.editor.options/spreadsheetloadoptions/optimizememoryusage) { get; set; } | 입력 문서를 처리하는 동안 메모리 최적화 메커니즘을 활성화하여 일부 특수한 경우( ) 성능이 저하될 수 있지만 반면에 메모리 사용량은 감소합니다. 대용량 문서를 처리하고 OutOfMemoryException에 직면할 때 유용합니다. 기본값은 false입니다(성능 향상을 위해 메모리 최적화가 비활성화됨). |
| [Password](../../groupdocs.editor.options/spreadsheetloadoptions/password) { get; set; } | 인코딩된 경우 스프레드시트 문서를 여는 데 사용할 암호를 지정, 수정 및 얻을 수 있습니다. 암호를 사용하지 않으려면 NULL 또는 빈 문자열로 설정합니다(기본값). |

### 또한보십시오

* interface [ILoadOptions](../iloadoptions)
* 네임스페이스 [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* 집회 [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->