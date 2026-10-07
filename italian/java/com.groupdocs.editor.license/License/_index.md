---
title: "Licenza"
second_title: "GroupDocs.Editor per Java Riferimento API"
description: "Fornisce metodi per licenziare il componente."
type: docs
weight: 10
url: /it/java/com.groupdocs.editor.license/license/
---
**Inheritance:**
java.lang.Object
```
public class License
```

Fornisce metodi per licenziare il componente. Scopri di più sulla licenza [qui](../https://purchase.groupdocs.com/faqs/licensing).

<br />

*** ** * ** ***

**Learn more**

* More about licensing: [GroupDocs Licensing FAQ](../https://purchase.groupdocs.com/faqs/licensing)
* More about GroupDocs.Editor licensing:[Evaluation Limitations and Licensing](../https://docs.groupdocs.com/editor/java/licensing-and-subscription/)

<br />


## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [License()](#License--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [setLicense(InputStream licenseStream)](#setLicense-java.io.InputStream-) | Concede licenza al componente. |
|
|  | [setLicense(String licensePath)](#setLicense-java.lang.String-) | Concede licenza al componente. |
|
### License() {#License--}
```
public License()
```


### setLicense(InputStream licenseStream) {#setLicense-java.io.InputStream-}
```
public final void setLicense(InputStream licenseStream)
```


Concede licenza al componente.


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
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | licenseStream | java.io.InputStream | Il flusso di licenza. |
|

### setLicense(String licensePath) {#setLicense-java.lang.String-}
```
public final void setLicense(String licensePath)
```


Concede licenza al componente.


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
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | licensePath | java.lang.String | Il percorso della licenza. |
|

