---
title: "Editor"
second_title: "GroupDocs.Editor for Java API 참조"
description: "변환 메서드를 캡슐화하는 메인 클래스입니다."
type: docs
weight: 11
url: /ko/java/com.groupdocs.editor/editor/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.resources.IAuxDisposable](../../com.groupdocs.editor.htmlcss.resources/iauxdisposable)
```
public final class Editor implements IAuxDisposable
```

변환 메서드를 캡슐화하는 메인 클래스.
Editor 클래스는 지원되는 모든 형식의 문서를 로드, 편집 및 저장하는 메서드를 제공합니다. 이 클래스는 disposable이므로 'using' 지시문을 사용하거나 'Dispose()' 메서드 호출을 통해 리소스를 수동으로 해제하십시오. 문서 로드는 생성자를 통해 수행됩니다. 문서 편집은 'Edit' 메서드를 통해, 편집 후 결과 문서에 저장은 'Save' 메서드를 통해 이루어집니다.
**Editor class should be considered as an entry point and the root object of the GroupDocs.Editor. All operations are performed using this class. Typical usage of the Editor class for performing a full document editing pipeline is the next:**

* Load a document into the Editor instance through its constructor.
* Optionally, detect a document type using a method.
* Open a document for editing by calling an method and obtaining an instance of class from it..
* Editing a document content on client-side using any WYSIWYG HTML-editor.
* Creating a new instance of from edited document content.
* Saving an edited document to some output format by calling a method.
* Disposing an instance of Editor class via 'using' operator or manually.

## 생성자

| 생성자 | 설명 |
| --- | --- |
|  | [Editor(DocumentFormatBase format)](#Editor-com.groupdocs.editor.formats.abstraction.DocumentFormatBase-) | 새로운 [Editor](../../com.groupdocs.editor/editor) 클래스 인스턴스를 초기화하고 지정된 형식을 기반으로 새로운 빈 문서를 생성합니다. |
|
|  | [Editor(InputStream document)](#Editor-java.io.InputStream-) | 지정된 입력 문서(스트림 형태)로 새로운 Editor 인스턴스를 초기화합니다. |
|
|  | [Editor(InputStream document, ILoadOptions loadOptions)](#Editor-java.io.InputStream-com.groupdocs.editor.options.ILoadOptions-) | 지정된 입력 문서(형식이 |
스트림)과 로드 옵션 및 Editor 설정을 사용합니다.
|
|  | [Editor(String filePath)](#Editor-java.lang.String-) | 지정된 입력 문서(전체 파일 경로)로 새로운 Editor 인스턴스를 초기화합니다. |
|
|  | [Editor(String filePath, ILoadOptions loadOptions)](#Editor-java.lang.String-com.groupdocs.editor.options.ILoadOptions-) | 지정된 입력 문서(전체 파일 경로)와 로드 옵션을 사용하여 새로운 Editor 인스턴스를 초기화합니다. |
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [edit(IEditOptions editOptions)](#edit-com.groupdocs.editor.options.IEditOptions-) | 지정된 형식별 옵션을 사용하여 이전에 로드된 문서를 편집하기 위해 '' 클래스를 생성하고 반환하며, 이 클래스는 HTML 마크업 및 관련 리소스를 생성하는 메서드를 포함합니다. |
|
|  | [edit()](#edit--) | 기본 옵션을 사용하여 이전에 로드된 문서를 편집하기 위해 열고 |
'EditableDocument' 클래스를 생성하고 반환하여,
이 클래스는 차례로 HTML 마크업 및 관련
리소스를 포함합니다.
|
|  | [save(EditableDocument inputDocument, OutputStream outputDocument, ISaveOptions saveOptions)](#save-com.groupdocs.editor.EditableDocument-java.io.OutputStream-com.groupdocs.editor.options.ISaveOptions-) | 지정된 편집된 문서를 인스턴스로 표현된 |
'EditableDocument'를 지정된 형식의 결과 문서로 변환하고
그 내용을 지정된 스트림에 저장합니다.
|
|  | [save(EditableDocument inputDocument, String filePath, ISaveOptions saveOptions)](#save-com.groupdocs.editor.EditableDocument-java.lang.String-com.groupdocs.editor.options.ISaveOptions-) | 지정된 편집된 문서를 '' 인스턴스로 표현하여 지정된 형식의 결과 문서로 변환하고, 지정된 파일 경로에 파일로 저장합니다. |
|
|  | [save(EditableDocument inputDocument, String filePath)](#save-com.groupdocs.editor.EditableDocument-java.lang.String-) | 지정된 편집된 문서([EditableDocument](../../com.groupdocs.editor/editabledocument)로 표현됨)를 파일 이름 확장자에 따라 결정되는 형식의 출력 문서로 변환하고, 지정된 파일 경로에 저장합니다. |
|
|  | [save(OutputStream outputDocument, WordProcessingSaveOptions saveOptions)](#save-java.io.OutputStream-com.groupdocs.editor.options.WordProcessingSaveOptions-) | 수정 후 원본 문서를 변환합니다 (예를 들어, |
FormFieldManager
(#getFormFieldManager.getFormFieldManager)),
지정된 형식의 결과 문서로 변환하고, 제공된 스트림에 내용을 저장합니다.
|
|  | [save(OutputStream outputDocument)](#save-java.io.OutputStream-) | 현재 문서 내용을 지정된 출력 스트림에 저장합니다. |
|
|  | [getDocumentInfo(String password)](#getDocumentInfo-java.lang.String-) | 이 'Editor' 인스턴스에 로드된 문서에 대한 메타데이터를 반환합니다. |
|
|  | [dispose()](#dispose--) | Editor 인스턴스를 해제하여 모든 내부 리소스를 해제합니다. |
리소스가 소모되어 더 이상 사용할 수 없습니다.
|
|  | [isDisposed()](#isDisposed--) | 이 Editor 인스턴스가 이미 해제되어 더 이상 사용할 수 없는지 여부를 나타냅니다 |
더 이상 사용되지 않는지 (true) 혹은 활성 상태인지 (false) 를 나타냅니다
|
### Editor(DocumentFormatBase format) {#Editor-com.groupdocs.editor.formats.abstraction.DocumentFormatBase-}
```
public Editor(DocumentFormatBase format)
```


새로운 [Editor](../../com.groupdocs.editor/editor) 클래스 인스턴스를 초기화하고 지정된 형식을 기반으로 새로운 빈 문서를 생성합니다.

<br />

*** ** * ** ***

> ```
>   IDocumentFormat format = WordProcessingFormats.Docx;
>  Editor editor = new Editor(format);
>  {
>      // Use the editor instance to edit and save documents
>  }
>  
>  
> ```

<br />



**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | format | [DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase) | 생성될 문서의 파일 형식을 나타냅니다. **Learn more** |

* More about file types supported by GroupDocs.Editor: [Document formats supported by GroupDocs.Editor](../https://docs.groupdocs.com/display/editornet/Supported+Document+Formats)
* More about GroupDocs.Editor for Java features: [Developer Guide](../https://docs.groupdocs.com/editor/java/developer-guide/)
|

### Editor(InputStream document) {#Editor-java.io.InputStream-}
```
public Editor(InputStream document)
```


지정된 입력 문서(스트림 형태)로 새로운 Editor 인스턴스를 초기화합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 문서 | java.io.InputStream | 문서 내용을 포함하는 스트림을 반환해야 하는 대리자입니다. NULL이어서는 안 됩니다. **Learn more** |

* More about file types supported by GroupDocs.Editor: [Document formats supported by GroupDocs.Editor](../https://docs.groupdocs.com/display/editornet/Supported+Document+Formats)
* More about GroupDocs.Editor for Java features: [Developer Guide](../https://docs.groupdocs.com/editor/java/developer-guide/)
|

### Editor(InputStream document, ILoadOptions loadOptions) {#Editor-java.io.InputStream-com.groupdocs.editor.options.ILoadOptions-}
```
public Editor(InputStream document, ILoadOptions loadOptions)
```


지정된 입력 문서(형식이
스트림)과 로드 옵션 및 Editor 설정을 사용합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 문서 | java.io.InputStream | 문서 내용을 포함하는 스트림을 반환해야 하는 대리자입니다. NULL이어서는 안 됩니다. |
|
|  | loadOptions | [ILoadOptions](../../com.groupdocs.editor.options/iloadoptions) | 문서 로드 옵션을 반환해야 하는 대리자입니다. NULL일 수 있으며 null을 반환할 수도 있습니다—이 경우 문서 유형이 자동으로 감지되고 해당 유형에 대한 기본 로드 옵션이 적용됩니다. |
|

### Editor(String filePath) {#Editor-java.lang.String-}
```
public Editor(String filePath)
```


지정된 입력 문서(전체 파일 경로)로 새로운 Editor 인스턴스를 초기화합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | filePath | java.lang.String | 파일의 전체 경로입니다. NULL이어서는 안 됩니다. 유효해야 하며 파일이 존재해야 합니다. **Learn more** |

* More about file types supported by GroupDocs.Editor: [Document formats supported by GroupDocs.Editor](../https://docs.groupdocs.com/editor/java/supported-document-formats/)
* More about GroupDocs.Editor for Java features: [Developer Guide](../https://docs.groupdocs.com/editor/java/developer-guide/)
|

### Editor(String filePath, ILoadOptions loadOptions) {#Editor-java.lang.String-com.groupdocs.editor.options.ILoadOptions-}
```
public Editor(String filePath, ILoadOptions loadOptions)
```


지정된 입력 문서(전체 파일 경로)와 로드 옵션을 사용하여 새로운 Editor 인스턴스를 초기화합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | filePath | java.lang.String | 파일의 전체 경로입니다. NULL이어서는 안 됩니다. 유효해야 하며 파일이 존재해야 합니다. |
|
|  | loadOptions | [ILoadOptions](../../com.groupdocs.editor.options/iloadoptions) | 문서 로드 옵션을 반환해야 하는 대리자입니다. NULL일 수 있으며 null을 반환할 수도 있습니다—이 경우 문서 유형이 자동으로 감지되고 해당 유형에 대한 기본 로드 옵션이 적용됩니다. **Learn more** |

* More about file types supported by GroupDocs.Editor: [Document formats supported by GroupDocs.Editor](../https://docs.groupdocs.com/editor/java/supported-document-formats/)
* More about GroupDocs.Editor for Java features: [Developer Guide](../https://docs.groupdocs.com/editor/java/developer-guide/)
* More about how to open and edit password-protected documents and document from different storages: [Load and edit documents using GroupDocs.Editor](../https://docs.groupdocs.com/editor/java/load-document/)
|

### edit(IEditOptions editOptions) {#edit-com.groupdocs.editor.options.IEditOptions-}
```
public final EditableDocument edit(IEditOptions editOptions)
```


지정된 형식별 옵션을 사용하여 이전에 로드된 문서를 편집하기 위해 '' 클래스를 생성하고 반환하며, 이 클래스는 HTML 마크업 및 관련 리소스를 생성하는 메서드를 포함합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | editOptions | [IEditOptions](../../com.groupdocs.editor.options/ieditoptions) | 변환 프로세스를 조정할 수 있는 형식별 문서 옵션입니다. NULL이어서는 안 됩니다. 이전에 적용된 로드 옵션과 충돌해서도 안 됩니다. |


*** ** * ** ***

입력 원본 문서를 생성자를 통해 'Editor' 인스턴스로 로드하면, 이 메서드는 문서를 중간 형식으로 변환하여 'EditableDocument' 클래스의 인스턴스로 캡슐화함으로써 편집을 열 수 있게 합니다. 이 메서드가 반환하는 'EditableDocument'는 HTML 마크업 및 해당 리소스(이미지, 글꼴, 스타일시트 등)를 생성하는 데 필요한 모든 메서드와 속성을 포함하고 있으며, 이후 어떤 WYSIWYG HTML 편집기로도 전달할 수 있도록 모든 필요한 구성으로 제공됩니다. 이 오버로드는 패밀리 형식에 특화된 편집 옵션을 가져옵니다.

*** ** * ** ***


**Learn more**

* More about editing documents using GroupDocs.Editor: [How to edit document using GroupDocs.Editor](../https://docs.groupdocs.com/display/editornet/Edit+document)
|

**Returns:**
[EditableDocument](../../com.groupdocs.editor/editabledocument)
### edit() {#edit--}
```
public final EditableDocument edit()
```


기본 옵션을 사용하여 이전에 로드된 문서를 편집하기 위해 열고
'EditableDocument' 클래스를 생성하고 반환하여,
이 클래스는 차례로 HTML 마크업 및 관련
리소스를 포함합니다.


**Returns:**
[EditableDocument](../../com.groupdocs.editor/editabledocument) - Instance of the 'EditableDocument' class, which encapsulates overall input document with all its resources in intermediate format. This method, if successfully finished, never returns NULL.


*** ** * ** ***

입력 원본 문서를 생성자를 통해 'Editor' 인스턴스로 로드하면, 이 메서드는 문서를 중간 형식으로 변환하여 'EditableDocument' 클래스의 인스턴스로 캡슐화함으로써 편집을 열 수 있게 합니다. 이 메서드가 반환하는 'EditableDocument'는 HTML 마크업 및 해당 리소스(이미지, 글꼴, 스타일시트 등)를 생성하는 데 필요한 모든 메서드와 속성을 포함하고 있으며, 이후 어떤 WYSIWYG HTML 편집기로도 전달할 수 있도록 모든 필요한 구성으로 제공됩니다. 이 오버로드는 입력 문서가 속한 형식에 대한 기본 편집 옵션을 적용합니다.

<br />

**Learn more**

* More about editing documents using GroupDocs.Editor: [How to edit document using GroupDocs.Editor](../https://docs.groupdocs.com/editor/java/edit-document/)

### save(EditableDocument inputDocument, OutputStream outputDocument, ISaveOptions saveOptions) {#save-com.groupdocs.editor.EditableDocument-java.io.OutputStream-com.groupdocs.editor.options.ISaveOptions-}
```
public final void save(EditableDocument inputDocument, OutputStream outputDocument, ISaveOptions saveOptions)
```


지정된 편집된 문서를 인스턴스로 표현된
'EditableDocument'를 지정된 형식의 결과 문서로 변환하고
그 내용을 지정된 스트림에 저장합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | inputDocument | [EditableDocument](../../com.groupdocs.editor/editabledocument) | WYSIWYG HTML 편집기에서 편집된 입력 문서의 버전으로, 'EditableDocument' 클래스의 인스턴스로 저장되며 특정 형식의 출력 문서로 변환되어야 합니다. |
|
|  | outputDocument | java.io.OutputStream | 결과 문서의 내용이 기록될 출력 스트림입니다. NULL이 아니어야 하고, 해제되지 않아야 하며, 쓰기를 지원해야 합니다. |
|
|  | saveOptions | [ISaveOptions](../../com.groupdocs.editor.options/isaveoptions) | 결과 문서의 형식을 정의하고 일반 및 형식별 저장 옵션을 포함하는 문서 저장 옵션입니다. **Learn more** |

* More about saving document after edit using GroupDocs.Editor: [How to save edited document using GroupDocs.Editor](../https://docs.groupdocs.com/display/editornet/Save+document)
|

### save(EditableDocument inputDocument, String filePath, ISaveOptions saveOptions) {#save-com.groupdocs.editor.EditableDocument-java.lang.String-com.groupdocs.editor.options.ISaveOptions-}
```
public final void save(EditableDocument inputDocument, String filePath, ISaveOptions saveOptions)
```


지정된 편집된 문서를 '' 인스턴스로 표현하여 지정된 형식의 결과 문서로 변환하고, 지정된 파일 경로에 파일로 저장합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | inputDocument | [EditableDocument](../../com.groupdocs.editor/editabledocument) | WYSIWYG HTML 편집기에서 편집된 입력 문서의 버전으로, '' 클래스의 인스턴스로 저장되며 특정 형식의 출력 문서로 변환되어야 합니다. null이 아니어야 하고 해제되지 않아야 합니다. |
|
|  | filePath | java.lang.String | 출력 문서가 저장될 파일의 경로입니다. 동일한 이름의 파일이 존재하면 완전히 덮어쓰게 됩니다. 경로 문자열은 null이 아니어야 하고, 비어 있지 않아야 하며 공백만 포함해서도 안 됩니다. |
|
|  | saveOptions | [ISaveOptions](../../com.groupdocs.editor.options/isaveoptions) | 결과 문서의 형식을 정의하고 일반 및 형식별 저장 옵션을 포함하는 문서 저장 옵션입니다. null이어서는 안 됩니다. **Learn more** |

* More about saving document after edit using GroupDocs.Editor: [How to save edited document using GroupDocs.Editor](../https://docs.groupdocs.com/display/editornet/Save+document)
|

### save(EditableDocument inputDocument, String filePath) {#save-com.groupdocs.editor.EditableDocument-java.lang.String-}
```
public final void save(EditableDocument inputDocument, String filePath)
```


지정된 편집된 문서([EditableDocument](../../com.groupdocs.editor/editabledocument)로 표현됨)를 파일 이름 확장자에 따라 결정되는 형식의 출력 문서로 변환하고, 지정된 파일 경로에 저장합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | inputDocument | [EditableDocument](../../com.groupdocs.editor/editabledocument) | WYSIWYG HTML 편집기에서 편집된 입력 문서의 버전으로, [EditableDocument](../../com.groupdocs.editor/editabledocument) 인스턴스로 저장됩니다. null이 아니어야 하고 해제되지 않아야 합니다. |
|
|  | filePath | java.lang.String | 출력 문서가 저장될 파일의 경로입니다. 동일한 이름의 파일이 존재하면 완전히 덮어쓰게 됩니다. 경로 문자열은 null이 아니어야 하고, 비어 있지 않아야 하며, 공백만 포함해서도 안 됩니다. 기본 저장 옵션 및 출력 형식이 파일 이름에서 결정되므로 유효한 확장자를 가져야 합니다. |
|

### save(OutputStream outputDocument, WordProcessingSaveOptions saveOptions) {#save-java.io.OutputStream-com.groupdocs.editor.options.WordProcessingSaveOptions-}
```
public final OutputStream save(OutputStream outputDocument, WordProcessingSaveOptions saveOptions)
```


수정 후 원본 문서를 변환합니다 (예를 들어,
FormFieldManager
(#getFormFieldManager.getFormFieldManager)),
지정된 형식의 결과 문서로 변환하고, 제공된 스트림에 내용을 저장합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | outputDocument | java.io.OutputStream | 출력 문서가 저장될 스트림입니다. 이 스트림은 쓰기 가능하고 문서 내용의 시작 위치에 있어야 합니다. null이어서는 안 됩니다. |
|
|  | saveOptions | [WordProcessingSaveOptions](../../com.groupdocs.editor.options/wordprocessingsaveoptions) | 결과 문서의 형식을 정의하고 일반 및 형식별 저장 옵션을 포함하는 문서 저장 옵션입니다. null이어서는 안 됩니다. |

<br />

*** ** * ** ***

outputDocument 또는 saveOptions가 null이면 NullPointerException이 발생합니다. 저장할 문서가 없으면 NullPointerException이 발생합니다.

<br />

<br />

*** ** * ** ***

 **Learn more:** 

* 

<br />

|

**Returns:**
java.io.OutputStream - 저장된 문서 내용을 포함하는 스트림.

### save(OutputStream outputDocument) {#save-java.io.OutputStream-}
```
public final OutputStream save(OutputStream outputDocument)
```


현재 문서 내용을 지정된 출력 스트림에 저장합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | outputDocument | java.io.OutputStream | 문서 내용이 저장될 스트림입니다. 이 값은 null일 수 없습니다. |

<br />

*** ** * ** ***

이 메서드는 내부 문서 표현에서 제공된 출력 스트림으로 내용을 복사합니다. 저장 작업 후 스트림의 원래 위치가 유지됩니다.

<br />

|

**Returns:**
java.io.OutputStream - 저장된 문서 내용을 가진 스트림.

### getDocumentInfo(String password) {#getDocumentInfo-java.lang.String-}
```
public final IDocumentInfo getDocumentInfo(String password)
```


이 'Editor' 인스턴스에 로드된 문서에 대한 메타데이터를 반환합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 비밀번호 | java.lang.String | 사용자는 문서가 비밀번호로 암호화된 경우 해당 문서에 비밀번호를 지정할 수 있습니다. NULL이거나 빈 문자열일 경우 비밀번호가 없는 것과 동일합니다. 비밀번호 보호 기능이 없는 문서 형식의 경우 이 인자는 무시됩니다. 문서가 암호화되어 있고 이 매개변수에 비밀번호가 지정되지 않았지만 인스턴스를 생성할 때 로드 옵션에서 이미 지정된 경우 해당 비밀번호가 사용됩니다. **Learn more** |

* Learn more about obtaining document specific properties in code: [How to get document info using GroupDocs.Editor](../https://docs.groupdocs.com/editor/java/extracting-document-metainfo/)
|

**Returns:**
[IDocumentInfo](../../com.groupdocs.editor.metadata/idocumentinfo)
### dispose() {#dispose--}
```
public final void dispose()
```


Editor 인스턴스를 해제하여 모든 내부 리소스를 해제합니다.
리소스가 소모되어 더 이상 사용할 수 없습니다.


### isDisposed() {#isDisposed--}
```
public final boolean isDisposed()
```


이 Editor 인스턴스가 이미 해제되어 더 이상 사용할 수 없는지 여부를 나타냅니다
더 이상 사용되지 않는지 (true) 혹은 활성 상태인지 (false) 를 나타냅니다


**Returns:**
boolean
