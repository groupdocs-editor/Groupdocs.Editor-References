---
title: "Licence"
second_title: "Référence d'API GroupDocs.Editor pour Node.js via Java"
description: "Fournit des méthodes pour licencier le composant."
type: docs
weight: 10
url: /fr/nodejs-java/com.groupdocs.editor.license/license/
---
**Inheritance:**
java.lang.Object
```
public class License
```

Fournit des méthodes pour licencier le composant. En savoir plus sur la licence [ici](../https://purchase.groupdocs.com/faqs/licensing).

<br />

*** ** * ** ***

**Learn more**

* More about licensing: [GroupDocs Licensing FAQ](../https://purchase.groupdocs.com/faqs/licensing)
* More about GroupDocs.Editor licensing:[Evaluation Limitations and Licensing](../https://docs.groupdocs.com/editor/java/licensing-and-subscription/)

<br />


## Constructeurs

| Constructeur | Description |
| --- | --- |
| [License()](#License--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [setLicense(InputStream licenseStream)](#setLicense-java.io.InputStream-) | Licence le composant. |
|
|  | [setLicense(String licensePath)](#setLicense-java.lang.String-) | Licence le composant. |
|
### License() {#License--}
```
public License()
```


### setLicense(InputStream licenseStream) {#setLicense-java.io.InputStream-}
```
public final void setLicense(InputStream licenseStream)
```


Licence le composant.


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
| Paramètre | Type | Description |
| --- | --- | --- |
|  | licenseStream | java.io.InputStream | Le flux de licence. |
|

### setLicense(String licensePath) {#setLicense-java.lang.String-}
```
public final void setLicense(String licensePath)
```


Licence le composant.


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
| Paramètre | Type | Description |
| --- | --- | --- |
|  | licensePath | java.lang.String | Le chemin de licence. |
|

