---
title: "Άδεια"
second_title: "GroupDocs.Editor για Node.js μέσω Java API Reference"
description: "Παρέχει μεθόδους για την άδεια του στοιχείου."
type: docs
weight: 10
url: /el/nodejs-java/com.groupdocs.editor.license/license/
---
**Inheritance:**
java.lang.Object
```
public class License
```

Παρέχει μεθόδους για την άδεια του στοιχείου. Μάθετε περισσότερα για την άδεια [εδώ](../https://purchase.groupdocs.com/faqs/licensing).

<br />

*** ** * ** ***

**Learn more**

* More about licensing: [GroupDocs Licensing FAQ](../https://purchase.groupdocs.com/faqs/licensing)
* More about GroupDocs.Editor licensing:[Evaluation Limitations and Licensing](../https://docs.groupdocs.com/editor/java/licensing-and-subscription/)

<br />


## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [License()](#License--) |  |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [setLicense(InputStream licenseStream)](#setLicense-java.io.InputStream-) | Παρέχει άδεια στο στοιχείο. |
|
|  | [setLicense(String licensePath)](#setLicense-java.lang.String-) | Παρέχει άδεια στο στοιχείο. |
|
### License() {#License--}
```
public License()
```


### setLicense(InputStream licenseStream) {#setLicense-java.io.InputStream-}
```
public final void setLicense(InputStream licenseStream)
```


Παρέχει άδεια στο στοιχείο.


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
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | licenseStream | java.io.InputStream | Η ροή άδειας. |
|

### setLicense(String licensePath) {#setLicense-java.lang.String-}
```
public final void setLicense(String licensePath)
```


Παρέχει άδεια στο στοιχείο.


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
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | licensePath | java.lang.String | Η διαδρομή άδειας. |
|

