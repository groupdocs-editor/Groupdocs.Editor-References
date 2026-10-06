---
title: "Lizenz"
second_title: "GroupDocs.Editor für Java API-Referenz"
description: "Stellt Methoden zum Lizenzieren der Komponente bereit."
type: docs
weight: 10
url: /de/java/com.groupdocs.editor.license/license/
---
**Inheritance:**
java.lang.Object
```
public class License
```

Stellt Methoden zum Lizenzieren der Komponente bereit. Weitere Informationen zur Lizenzierung finden Sie [hier](../https://purchase.groupdocs.com/faqs/licensing).

<br />

*** ** * ** ***

**Learn more**

* More about licensing: [GroupDocs Licensing FAQ](../https://purchase.groupdocs.com/faqs/licensing)
* More about GroupDocs.Editor licensing:[Evaluation Limitations and Licensing](../https://docs.groupdocs.com/editor/java/licensing-and-subscription/)

<br />


## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [License()](#License--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [setLicense(InputStream licenseStream)](#setLicense-java.io.InputStream-) | Lizenziert die Komponente. |
|
|  | [setLicense(String licensePath)](#setLicense-java.lang.String-) | Lizenziert die Komponente. |
|
### License() {#License--}
```
public License()
```


### setLicense(InputStream licenseStream) {#setLicense-java.io.InputStream-}
```
public final void setLicense(InputStream licenseStream)
```


Lizenziert die Komponente.


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
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | licenseStream | java.io.InputStream | Der Lizenz-Stream. |
|

### setLicense(String licensePath) {#setLicense-java.lang.String-}
```
public final void setLicense(String licensePath)
```


Lizenziert die Komponente.


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
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | licensePath | java.lang.String | Der Lizenzpfad. |
|

