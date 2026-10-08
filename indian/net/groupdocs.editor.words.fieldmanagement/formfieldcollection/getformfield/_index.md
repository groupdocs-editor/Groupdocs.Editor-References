---
title: "GetFormField"
second_title: "GroupDocs.Editor के लिए .NET API रेफ़रेंस"
description: "निर्दिष्ट नाम और प्रकार वाले फ़ॉर्म फ़ील्ड को प्राप्त करता है।"
type: docs
weight: 40
url: /hi/net/groupdocs.editor.words.fieldmanagement/formfieldcollection/getformfield/
---
## FormFieldCollection.GetFormField&lt;T&gt; method

निर्दिष्ट नाम और प्रकार वाले फ़ॉर्म फ़ील्ड को प्राप्त करता है।

```csharp
public T GetFormField<T>(string name)
    where T : IFormField
```

| Parameter | विवरण |
| --- | --- |
| T | फ़ॉर्म फ़ील्ड का प्रकार। |
| name | फ़ॉर्म फ़ील्ड का नाम। |

### रिटर्न मान

निर्दिष्ट नाम और प्रकार वाला फ़ॉर्म फ़ील्ड, यदि मिला; अन्यथा, प्रकार का डिफ़ॉल्ट मान।

### संबंधित देखें

* interface [IFormField](../../iformfield)
* class [FormFieldCollection](../../formfieldcollection)
* namespace [GroupDocs.Editor.Words.FieldManagement](../../../groupdocs.editor.words.fieldmanagement)
* assembly [GroupDocs.Editor](../../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.editor.dll के लिए उत्पन्न किया गया -->
