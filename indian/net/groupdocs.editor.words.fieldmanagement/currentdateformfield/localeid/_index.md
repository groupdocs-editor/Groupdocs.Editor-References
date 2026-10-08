---
title: "LocaleId"
second_title: "GroupDocs.Editor के लिए .NET API रेफ़रेंस"
description: "फ़ॉर्म फ़ील्ड का लोकैल आईडी प्राप्त करता है या सेट करता है जो फ़ॉर्म फ़ील्ड से जुड़े संस्कृति या क्षेत्रीय सेटिंग्स को दर्शाता है।"
type: docs
weight: 30
url: /hi/net/groupdocs.editor.words.fieldmanagement/currentdateformfield/localeid/
---
## CurrentDateFormField.LocaleId property

फ़ॉर्म फ़ील्ड का लोकैल आईडी प्राप्त करता है या सेट करता है, जो फ़ॉर्म फ़ील्ड से जुड़े संस्कृति या क्षेत्रीय सेटिंग्स को दर्शाता है।

```csharp
public int LocaleId { get; set; }
```

### टिप्पणियाँ

LocaleId प्रॉपर्टी एक लोकैल पहचानकर्ता (LCID) निर्दिष्ट करती है जो किसी विशिष्ट संस्कृति या क्षेत्र के अनुरूप होता है।

### उदाहरण

निम्न उदाहरण दर्शाता है कि LocaleId प्रॉपर्टी को कैसे सेट किया जाए:

```csharp
Set the LocaleId to represent the English (United States) culture
currentTimeField.LocaleId = new CultureInfo("en-US").LCID;
```

### संबंधित देखें

* class [CurrentDateFormField](../../currentdateformfield)
* namespace [GroupDocs.Editor.Words.FieldManagement](../../../groupdocs.editor.words.fieldmanagement)
* assembly [GroupDocs.Editor](../../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.editor.dll के लिए उत्पन्न किया गया -->
