---
title: "Licentie"
second_title: "GroupDocs.Editor for Java API-referentie"
description: "Biedt methoden om het component te licentiëren."
type: docs
weight: 10
url: /nl/java/com.groupdocs.editor.license/license/
---
**Inheritance:**
java.lang.Object
```
public class License
```

Biedt methoden om het component te licentiëren. Meer informatie over licenties [hier](../https://purchase.groupdocs.com/faqs/licensing).

<br />

*** ** * ** ***

**Learn more**

* More about licensing: [GroupDocs Licensing FAQ](../https://purchase.groupdocs.com/faqs/licensing)
* More about GroupDocs.Editor licensing:[Evaluation Limitations and Licensing](../https://docs.groupdocs.com/editor/java/licensing-and-subscription/)

<br />


## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [License()](#License--) |  |
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [setLicense(InputStream licenseStream)](#setLicense-java.io.InputStream-) | Licentieert de component. |
|
|  | [setLicense(String licensePath)](#setLicense-java.lang.String-) | Licentieert de component. |
|
### License() {#License--}
```
public License()
```


### setLicense(InputStream licenseStream) {#setLicense-java.io.InputStream-}
```
public final void setLicense(InputStream licenseStream)
```


Licentieert de component.


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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | licenseStream | java.io.InputStream | De licentiestroom. |
|

### setLicense(String licensePath) {#setLicense-java.lang.String-}
```
public final void setLicense(String licensePath)
```


Licentieert de component.


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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | licensePath | java.lang.String | Het licentiepad. |
|

