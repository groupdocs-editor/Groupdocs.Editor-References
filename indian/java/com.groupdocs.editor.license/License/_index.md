---
title: "लाइसेंस"
second_title: "GroupDocs.Editor for Java API संदर्भ"
description: "घटक को लाइसेंस करने के लिए विधियाँ प्रदान करता है।"
type: docs
weight: 10
url: /hi/java/com.groupdocs.editor.license/license/
---
**Inheritance:**
java.lang.Object
```
public class License
```

घटक को लाइसेंस करने के लिए मेथड्स प्रदान करता है। लाइसेंसिंग के बारे में अधिक जानने के लिए [here](../https://purchase.groupdocs.com/faqs/licensing) पर जाएँ।

<br />

*** ** * ** ***

**Learn more**

* More about licensing: [GroupDocs Licensing FAQ](../https://purchase.groupdocs.com/faqs/licensing)
* More about GroupDocs.Editor licensing:[Evaluation Limitations and Licensing](../https://docs.groupdocs.com/editor/java/licensing-and-subscription/)

<br />


## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [License()](#License--) |  |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
|  | [setLicense(InputStream licenseStream)](#setLicense-java.io.InputStream-) | घटक को लाइसेंस करता है। |
|
|  | [setLicense(String licensePath)](#setLicense-java.lang.String-) | घटक को लाइसेंस करता है। |
|
### License() {#License--}
```
public License()
```


### setLicense(InputStream licenseStream) {#setLicense-java.io.InputStream-}
```
public final void setLicense(InputStream licenseStream)
```


घटक को लाइसेंस करता है।


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
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | licenseStream | java.io.InputStream | लाइसेंस स्ट्रीम। |
|

### setLicense(String licensePath) {#setLicense-java.lang.String-}
```
public final void setLicense(String licensePath)
```


घटक को लाइसेंस करता है।


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
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | licensePath | java.lang.String | लाइसेंस पथ। |
|

