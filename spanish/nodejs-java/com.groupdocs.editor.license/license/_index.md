---
title: "Licencia"
second_title: "Referencia de API de GroupDocs.Editor para Node.js vía Java"
description: "Proporciona métodos para licenciar el componente."
type: docs
weight: 10
url: /es/nodejs-java/com.groupdocs.editor.license/license/
---
**Inheritance:**
java.lang.Object
```
public class License
```

Proporciona métodos para licenciar el componente. Obtenga más información sobre licencias [aquí](../https://purchase.groupdocs.com/faqs/licensing).

<br />

*** ** * ** ***

**Learn more**

* More about licensing: [GroupDocs Licensing FAQ](../https://purchase.groupdocs.com/faqs/licensing)
* More about GroupDocs.Editor licensing:[Evaluation Limitations and Licensing](../https://docs.groupdocs.com/editor/java/licensing-and-subscription/)

<br />


## Constructores

| Constructor | Descripción |
| --- | --- |
| [License()](#License--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
|  | [setLicense(InputStream licenseStream)](#setLicense-java.io.InputStream-) | Licencia el componente. |
|
|  | [setLicense(String licensePath)](#setLicense-java.lang.String-) | Licencia el componente. |
|
### License() {#License--}
```
public License()
```


### setLicense(InputStream licenseStream) {#setLicense-java.io.InputStream-}
```
public final void setLicense(InputStream licenseStream)
```


Licencia el componente.


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
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | licenseStream | java.io.InputStream | El flujo de licencia. |
|

### setLicense(String licensePath) {#setLicense-java.lang.String-}
```
public final void setLicense(String licensePath)
```


Licencia el componente.


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
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | licensePath | java.lang.String | La ruta de la licencia. |
|

