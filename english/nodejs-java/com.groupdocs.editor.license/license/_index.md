---
title: License
second_title: GroupDocs.Editor for Node.js via Java API Reference
description: Provides methods to license the component.
type: docs
weight: 10
url: /nodejs-java/com.groupdocs.editor.license/license/
---
**Inheritance:**
java.lang.Object
```
public class License
```

Provides methods to license the component. Learn more about licensing [here][].

--------------------

**Learn more**

 *  More about licensing: [GroupDocs Licensing FAQ][here]
 *  More about GroupDocs.Editor licensing:[Evaluation Limitations and Licensing][]


[here]: https://purchase.groupdocs.com/faqs/licensing
[Evaluation Limitations and Licensing]: https://docs.groupdocs.com/editor/java/licensing-and-subscription/
## Constructors

| Constructor | Description |
| --- | --- |
| [License()](#License--) |  |
## Methods

| Method | Description |
| --- | --- |
| [setLicense(InputStream licenseStream)](#setLicense-java.io.InputStream-) | Licenses the component. |
| [setLicense(String licensePath)](#setLicense-java.lang.String-) | Licenses the component. |
### License() {#License--}
```
public License()
```


### setLicense(InputStream licenseStream) {#setLicense-java.io.InputStream-}
```
public final void setLicense(InputStream licenseStream)
```


Licenses the component.

--------------------

> ```
> The following example demonstrates how to set a license
>  passing Stream of the license file.
>  
>  using (InputStream licenseStream = new FileInputStream("LicenseFile.lic"))
>  {
>      com.groupdocs.editor.License lic = new com.groupdocs.editor.License();
>      lic.setLicense(licenseStream);
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| licenseStream | java.io.InputStream | The license stream. |

### setLicense(String licensePath) {#setLicense-java.lang.String-}
```
public final void setLicense(String licensePath)
```


Licenses the component.

--------------------

> ```
> The following example demonstrates how to set a license
>  passing a path to the license file.
>  
>  String licensePath = "GroupDocs.Editor.lic";
>  com.groupdocs.editor.License lic = new com.groupdocs.editor.License();
>  lic.setLicense(licensePath);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| licensePath | java.lang.String | The license path. |

