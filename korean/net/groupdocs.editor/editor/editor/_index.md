---
title: Editor
second_title: .NET API 참조용 GroupDocs.Editor
description: 지정된 입력 문서스트림으로로 새 Editor 인스턴스를 초기화합니다.
type: docs
weight: 10
url: /ko/net/groupdocs.editor/editor/editor/
---
## Editor(Func&lt;Stream&gt;) {#constructor}

지정된 입력 문서(스트림으로)로 새 Editor 인스턴스를 초기화합니다.

```csharp
public Editor(Func<Stream> document)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| document | Func`1 | 문서 콘텐츠가 있는 스트림을 반환해야 하는 대리자. NULL이 아니어야 합니다. |

### 비고

**더 알아보기**

* GroupDocs.Editor: 에서 지원하는 파일 유형에 대한 추가 정보[GroupDocs.Editor에서 지원하는 문서 형식](https://docs.groupdocs.com/display/editornet/Supported+Document+Formats)
* .NET용 GroupDocs.Editor 기능에 대한 추가 정보: [개발자 가이드](https://docs.groupdocs.com/display/editornet/Developer+Guide)

### 또한보십시오

* class [Editor](../../editor)
* 네임스페이스 [GroupDocs.Editor](../../editor)
* 집회 [GroupDocs.Editor](../../../)

---

## Editor(Func&lt;Stream&gt;, Func&lt;ILoadOptions&gt;) {#constructor_1}

로드 options 를 사용하여 지정된 입력 문서(스트림)로 새 Editor 인스턴스를 초기화합니다.

```csharp
public Editor(Func<Stream> document, Func<ILoadOptions> loadOptions)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| document | Func`1 | 문서 콘텐츠가 있는 스트림을 반환해야 하는 대리자. NULL이 아니어야 합니다. |
| loadOptions | Func`1 | 문서 로드 옵션을 반환해야 하는 위임. NULL일 수 있으며 null - 를 반환할 수 있습니다. 이 경우 문서 유형이 자동으로 감지되고 해당 유형에 대한 기본 로드 옵션이 적용됩니다. |

### 비고

**더 알아보기**

* GroupDocs.Editor: 에서 지원하는 파일 유형에 대한 추가 정보[GroupDocs.Editor에서 지원하는 문서 형식](https://docs.groupdocs.com/display/editornet/Supported+Document+Formats)
* .NET용 GroupDocs.Editor 기능에 대한 추가 정보: [개발자 가이드](https://docs.groupdocs.com/display/editornet/Developer+Guide)
* 암호로 보호된 문서 및 다른 저장소의 문서를 열고 편집하는 방법에 대한 추가 정보: [GroupDocs.Editor를 사용하여 문서 로드 및 편집](https://docs.groupdocs.com/display/editornet/Load+document)

### 또한보십시오

* interface [ILoadOptions](../../../groupdocs.editor.options/iloadoptions)
* class [Editor](../../editor)
* 네임스페이스 [GroupDocs.Editor](../../editor)
* 집회 [GroupDocs.Editor](../../../)

---

## Editor(string) {#constructor_2}

지정된 입력 문서로 새 Editor 인스턴스를 초기화합니다(전체 파일 경로로)

```csharp
public Editor(string filePath)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| filePath | String | 파일의 전체 경로입니다. NULL이 아니어야 합니다. 유효해야 하며 파일이 존재해야 합니다. |

### 비고

**더 알아보기**

* GroupDocs.Editor: 에서 지원하는 파일 유형에 대한 추가 정보[GroupDocs.Editor에서 지원하는 문서 형식](https://docs.groupdocs.com/display/editornet/Supported+Document+Formats)
* .NET용 GroupDocs.Editor 기능에 대한 추가 정보: [개발자 가이드](https://docs.groupdocs.com/display/editornet/Developer+Guide)

### 또한보십시오

* class [Editor](../../editor)
* 네임스페이스 [GroupDocs.Editor](../../editor)
* 집회 [GroupDocs.Editor](../../../)

---

## Editor(string, Func&lt;ILoadOptions&gt;) {#constructor_3}

로드 options 를 사용하여 지정된 입력 문서(전체 파일 경로)로 새 Editor 인스턴스를 초기화합니다.

```csharp
public Editor(string filePath, Func<ILoadOptions> loadOptions)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| filePath | String | 파일의 전체 경로입니다. NULL이 아니어야 합니다. 유효해야 하며 파일이 존재해야 합니다. |
| loadOptions | Func`1 | 문서 로드 옵션을 반환해야 하는 위임. NULL일 수 있으며 null - 를 반환할 수 있습니다. 이 경우 문서 유형이 자동으로 감지되고 해당 유형에 대한 기본 로드 옵션이 적용됩니다. |

### 비고

**더 알아보기**

* GroupDocs.Editor: 에서 지원하는 파일 유형에 대한 추가 정보[GroupDocs.Editor에서 지원하는 문서 형식](https://docs.groupdocs.com/display/editornet/Supported+Document+Formats)
* .NET용 GroupDocs.Editor 기능에 대한 추가 정보: [개발자 가이드](https://docs.groupdocs.com/display/editornet/Developer+Guide)
* 암호로 보호된 문서 및 다른 저장소의 문서를 열고 편집하는 방법에 대한 추가 정보: [GroupDocs.Editor를 사용하여 문서 로드 및 편집](https://docs.groupdocs.com/display/editornet/Load+document)

### 또한보십시오

* interface [ILoadOptions](../../../groupdocs.editor.options/iloadoptions)
* class [Editor](../../editor)
* 네임스페이스 [GroupDocs.Editor](../../editor)
* 집회 [GroupDocs.Editor](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->