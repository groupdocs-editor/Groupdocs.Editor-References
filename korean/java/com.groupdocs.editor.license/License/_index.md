---
title: "라이선스"
second_title: "GroupDocs.Editor for Java API 참조"
description: "구성 요소에 라이선스를 적용하는 메서드를 제공합니다."
type: docs
weight: 10
url: /ko/java/com.groupdocs.editor.license/license/
---
**Inheritance:**
java.lang.Object
```
public class License
```

구성 요소에 라이선스를 적용하기 위한 메서드를 제공합니다. 라이선스에 대해 자세히 알아보려면 [here](../https://purchase.groupdocs.com/faqs/licensing)를 클릭하세요.

<br />

*** ** * ** ***

**Learn more**

* More about licensing: [GroupDocs Licensing FAQ](../https://purchase.groupdocs.com/faqs/licensing)
* More about GroupDocs.Editor licensing:[Evaluation Limitations and Licensing](../https://docs.groupdocs.com/editor/java/licensing-and-subscription/)

<br />


## 생성자

| 생성자 | 설명 |
| --- | --- |
| [License()](#License--) |  |
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [setLicense(InputStream licenseStream)](#setLicense-java.io.InputStream-) | 구성 요소에 라이선스를 적용합니다. |
|
|  | [setLicense(String licensePath)](#setLicense-java.lang.String-) | 구성 요소에 라이선스를 적용합니다. |
|
### License() {#License--}
```
public License()
```


### setLicense(InputStream licenseStream) {#setLicense-java.io.InputStream-}
```
public final void setLicense(InputStream licenseStream)
```


구성 요소에 라이선스를 적용합니다.


*** ** * ** ***

> ```
>  The following example demonstrates how to set a license
>  passing Stream of the license file.
>   using (InputStream licenseStream = new FileInputStream("LicenseFile.lic"))
>  {
>      com.groupdocs.editor.License lic = new com.groupdocs.editor.License();
>      lic.setLicense(licenseStream);
>  }
>  
>  
> ```

<br />



**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | licenseStream | java.io.InputStream | 라이선스 스트림. |
|

### setLicense(String licensePath) {#setLicense-java.lang.String-}
```
public final void setLicense(String licensePath)
```


구성 요소에 라이선스를 적용합니다.


*** ** * ** ***

> ```
>  The following example demonstrates how to set a license
>  passing a path to the license file.
>   String licensePath = "GroupDocs.Editor.lic";
>  com.groupdocs.editor.License lic = new com.groupdocs.editor.License();
>  lic.setLicense(licensePath);
>  
>  
> ```

<br />



**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | licensePath | java.lang.String | 라이선스 경로. |
|

