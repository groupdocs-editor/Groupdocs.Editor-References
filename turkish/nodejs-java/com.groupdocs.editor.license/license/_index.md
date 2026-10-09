---
title: "Lisans"
second_title: "GroupDocs.Editor Node.js için Java API Referansı"
description: "Bileşeni lisanslamak için yöntemler sağlar."
type: docs
weight: 10
url: /tr/nodejs-java/com.groupdocs.editor.license/license/
---
**Inheritance:**
java.lang.Object
```
public class License
```

Bileşeni lisanslamak için yöntemler sağlar. Lisanslama hakkında daha fazla bilgiyi [burada](../https://purchase.groupdocs.com/faqs/licensing) öğrenin.

<br />

*** ** * ** ***

**Learn more**

* More about licensing: [GroupDocs Licensing FAQ](../https://purchase.groupdocs.com/faqs/licensing)
* More about GroupDocs.Editor licensing:[Evaluation Limitations and Licensing](../https://docs.groupdocs.com/editor/java/licensing-and-subscription/)

<br />


## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [License()](#License--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [setLicense(InputStream licenseStream)](#setLicense-java.io.InputStream-) | Bileşeni lisanslar. |
|
|  | [setLicense(String licensePath)](#setLicense-java.lang.String-) | Bileşeni lisanslar. |
|
### License() {#License--}
```
public License()
```


### setLicense(InputStream licenseStream) {#setLicense-java.io.InputStream-}
```
public final void setLicense(InputStream licenseStream)
```


Bileşeni lisanslar.


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
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | licenseStream | java.io.InputStream | Lisans akışı. |
|

### setLicense(String licensePath) {#setLicense-java.lang.String-}
```
public final void setLicense(String licensePath)
```


Bileşeni lisanslar.


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
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | licensePath | java.lang.String | Lisans yolu. |
|

