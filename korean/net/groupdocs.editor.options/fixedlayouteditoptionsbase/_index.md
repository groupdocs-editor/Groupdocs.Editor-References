---
title: FixedLayoutEditOptionsBase
second_title: .NET API 참조용 GroupDocs.Editor
description: PDF 및 XPS 와 같은 고정 레이아웃 형식의 모든 문서에 대한 옵션의 기본 추상 클래스
type: docs
weight: 880
url: /ko/net/groupdocs.editor.options/fixedlayouteditoptionsbase/
---
## FixedLayoutEditOptionsBase class

PDF 및 XPS 와 같은 고정 레이아웃 형식의 모든 문서에 대한 옵션의 기본 추상 클래스

```csharp
public abstract class FixedLayoutEditOptionsBase : IEditOptions
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [EnablePagination](../../groupdocs.editor.options/fixedlayouteditoptionsbase/enablepagination) { get; set; } | 결과 HTML 문서에서 페이지 매김을 활성화(true) 또는 비활성화(false)할 수 있습니다. 기본적으로 비활성화되어 있습니다(false). |
| [Pages](../../groupdocs.editor.options/fixedlayouteditoptionsbase/pages) { get; set; } | 처리할 페이지 범위를 설정할 수 있습니다. 기본적으로 고정 레이아웃 문서의 모든 페이지가 처리됩니다. |
| [SkipImages](../../groupdocs.editor.options/fixedlayouteditoptionsbase/skipimages) { get; set; } | 입력 고정 레이아웃 문서를 결과 HTML로 변환하는 동안 이미지를 건너뛰어야 하는지 여부를 나타내는 플래그를 가져오거나 설정합니다. 기본값은 false입니다. 이미지가 보존됩니다. |

### 또한보십시오

* interface [IEditOptions](../ieditoptions)
* 네임스페이스 [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* 집회 [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->