---
title: IconImage
second_title: .NET API 참조용 GroupDocs.Editor
description: 메타데이터 및 추가 메서드가 있는 ICON 형식의 하나의 이미지를 나타냅니다
type: docs
weight: 520
url: /ko/net/groupdocs.editor.htmlcss.resources.images.raster/iconimage/
---
## IconImage class

메타데이터 및 추가 메서드가 있는 ICON 형식의 하나의 이미지를 나타냅니다

```csharp
public sealed class IconImage : RasterImageResourceBase
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [IconImage](iconimage#constructor)(string, Stream) | 바이트 스트림으로 표시되고 지정된 name 를 사용하여 콘텐츠에서 새 IconImage 인스턴스를 만듭니다. |
| [IconImage](iconimage#constructor_1)(string, string) | 콘텐츠에서 base64로 인코딩된 문자열로 표시되고 지정된 name 를 사용하여 새 IconImage 인스턴스를 만듭니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [AspectRatio](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/aspectratio) { get; } | 이 이미지의 종횡비를 너비-높이 관계로 반환합니다 |
| [ByteContent](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/bytecontent) { get; } | 이 래스터 이미지의 내용을 바이트 stream 로 반환합니다. |
| [FilenameWithExtension](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/filenamewithextension) { get; } | 이름과 확장자로 구성된 이 래스터 이미지의 올바른 파일 이름을 반환합니다. 이론적으로 이름과 다를 수 있습니다. |
| [IsDisposed](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/isdisposed) { get; } | 이 래스터 이미지를 폐기할지 여부를 결정합니다 |
| [Length](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/length) { get; } | 이 래스터 이미지 파일의 길이를 bytes 로 반환합니다. |
| [LinearDimensions](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/lineardimensions) { get; } | 이 래스터 이미지의 선형 치수를 반환합니다(너비 및 높이) |
| [Name](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/name) { get; } | 이 래스터 이미지의 이름을 반환합니다. 일반적으로 파일 이름 확장자를 포함하지 않으며 이론적으로 파일 이름과 다를 수 있습니다. |
| [NumberOfImages](../../groupdocs.editor.htmlcss.resources.images.raster/iconimage/numberofimages) { get; } | 이 ICON file 에 있는 이미지 수를 반환합니다. |
| [TextContent](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/textcontent) { get; } | 이 래스터 이미지의 내용을 base64로 인코딩된 string 로 반환합니다. |
| override [Type](../../groupdocs.editor.htmlcss.resources.images.raster/iconimage/type) { get; } | ImageType.Icon 를 반환합니다. |

## 행동 양식

| 이름 | 설명 |
| --- | --- |
| [Dispose](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/dispose)() | 이 래스터 이미지를 폐기하고 내용을 폐기하고 대부분의 메서드와 속성을 비작동 |
| [Equals](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/equals)(IHtmlResource) | 참조 동등성에 지정된 이 인스턴스를 확인합니다. |
| [GenerateBitmap](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/generatebitmap)() | 이 래스터 이미지에서 'System.Drawing.Bitmap'의 새 인스턴스를 생성하고 반환합니다. |
| [ReduceToNewHeight](../../groupdocs.editor.htmlcss.resources.images.raster/iconimage/reducetonewheight#reducetonewheight)(ushort) | 새로 축소된 아이콘 이미지를 생성하고 반환하지만 새로 축소된 높이와 비례적으로 축소된 너비를 지정합니다. (2 methods) |
| [Save](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/save)(string) | 이 래스터 이미지를 지정된 file 에 저장합니다. |
| static [IsValid](../../groupdocs.editor.htmlcss.resources.images.raster/iconimage/isvalid#isvalid)(Stream) | 지정된 스트림이 유효한 아이콘인지 확인합니다. image |
| static [IsValid](../../groupdocs.editor.htmlcss.resources.images.raster/iconimage/isvalid#isvalid_1)(string) | 지정된 base64 인코딩 문자열이 유효한 아이콘인지 확인합니다. image |

## 이벤트

| 이름 | 설명 |
| --- | --- |
| event [Disposed](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/disposed) | 이 래스터 이미지가 폐기될 때 발생하는 이벤트 |

### 또한보십시오

* class [RasterImageResourceBase](../rasterimageresourcebase)
* 네임스페이스 [GroupDocs.Editor.HtmlCss.Resources.Images.Raster](../../groupdocs.editor.htmlcss.resources.images.raster)
* 집회 [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->