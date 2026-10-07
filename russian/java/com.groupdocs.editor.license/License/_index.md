---
title: "Лицензия"
second_title: "GroupDocs.Editor for Java API Справка"
description: "Предоставляет методы лицензирования компонента."
type: docs
weight: 10
url: /ru/java/com.groupdocs.editor.license/license/
---
**Inheritance:**
java.lang.Object
```
public class License
```

Предоставляет методы для лицензирования компонента. Узнайте больше о лицензировании [здесь](../https://purchase.groupdocs.com/faqs/licensing).

<br />

*** ** * ** ***

**Learn more**

* More about licensing: [GroupDocs Licensing FAQ](../https://purchase.groupdocs.com/faqs/licensing)
* More about GroupDocs.Editor licensing:[Evaluation Limitations and Licensing](../https://docs.groupdocs.com/editor/java/licensing-and-subscription/)

<br />


## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [License()](#License--) |  |
## Методы

| Метод | Описание |
| --- | --- |
|  | [setLicense(InputStream licenseStream)](#setLicense-java.io.InputStream-) | Лицензирует компонент. |
|
|  | [setLicense(String licensePath)](#setLicense-java.lang.String-) | Лицензирует компонент. |
|
### License() {#License--}
```
public License()
```


### setLicense(InputStream licenseStream) {#setLicense-java.io.InputStream-}
```
public final void setLicense(InputStream licenseStream)
```


Лицензирует компонент.


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
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | licenseStream | java.io.InputStream | Поток лицензии. |
|

### setLicense(String licensePath) {#setLicense-java.lang.String-}
```
public final void setLicense(String licensePath)
```


Лицензирует компонент.


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
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | licensePath | java.lang.String | Путь к лицензии. |
|

