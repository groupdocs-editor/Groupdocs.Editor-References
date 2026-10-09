---
title: "ライセンス"
second_title: "Node.js 用 GroupDocs.Editor (Java 経由) API リファレンス"
description: "コンポーネントのライセンス付与のためのメソッドを提供します。"
type: docs
weight: 10
url: /ja/nodejs-java/com.groupdocs.editor.license/license/
---
**Inheritance:**
java.lang.Object
```
public class License
```

コンポーネントのライセンス付与のためのメソッドを提供します。ライセンスに関する詳細は[こちら](../https://purchase.groupdocs.com/faqs/licensing)をご覧ください。

<br />

*** ** * ** ***

**Learn more**

* More about licensing: [GroupDocs Licensing FAQ](../https://purchase.groupdocs.com/faqs/licensing)
* More about GroupDocs.Editor licensing:[Evaluation Limitations and Licensing](../https://docs.groupdocs.com/editor/java/licensing-and-subscription/)

<br />


## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [License()](#License--) |  |
## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [setLicense(InputStream licenseStream)](#setLicense-java.io.InputStream-) | コンポーネントにライセンスを付与します。 |
|
|  | [setLicense(String licensePath)](#setLicense-java.lang.String-) | コンポーネントにライセンスを付与します。 |
|
### License() {#License--}
```
public License()
```


### setLicense(InputStream licenseStream) {#setLicense-java.io.InputStream-}
```
public final void setLicense(InputStream licenseStream)
```


コンポーネントにライセンスを付与します。


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
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | licenseStream | java.io.InputStream | ライセンスストリームです。 |
|

### setLicense(String licensePath) {#setLicense-java.lang.String-}
```
public final void setLicense(String licensePath)
```


コンポーネントにライセンスを付与します。


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
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | licensePath | java.lang.String | ライセンスパスです。 |
|

