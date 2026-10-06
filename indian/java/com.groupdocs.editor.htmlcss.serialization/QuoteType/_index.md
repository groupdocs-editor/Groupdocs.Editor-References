---
title: "QuoteType"
second_title: "GroupDocs.Editor for Java API संदर्भ"
description: "उद्धरण वर्णों का प्रतिनिधित्व करता है - सिंगल कोट और डबल कोट"
type: docs
weight: 10
url: /hi/java/com.groupdocs.editor.htmlcss.serialization/quotetype/
---
**Inheritance:**
java.lang.Object
```
public class QuoteType
```

उद्धरण चिह्नों को दर्शाता है - सिंगल कोट (') और डबल कोट (")

## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [QuoteType()](#QuoteType--) |  |
## Fields

| Field | विवरण |
| --- | --- |
|  | [SingleQuote](#SingleQuote) | सिंगल कोट (U+0027 APOSTROPHE अक्षर) |
|
|  | [DoubleQuote](#DoubleQuote) | डबल कोट (U+0022 QUOTATION MARK अक्षर) |
|
## मेथड्स

| मेथड | विवरण |
| --- | --- |
|  | [getCode()](#getCode--) | वर्तमान अक्षर का कोड पॉइंट (U+0027 या U+0022) |
|
|  | [getCharacter()](#getCharacter--) | उद्धरण के लिए अक्षर |
|
|  | [getHtmlEncoded()](#getHtmlEncoded--) | HTML-एन्कोडेड अक्षर |
|
|  | [toString()](#toString--) | वर्तमान मान के आधार पर "SingleQuote" या "DoubleQuote" स्ट्रिंग लौटाता है |
|
|  | [equals(QuoteType other)](#equals-com.groupdocs.editor.htmlcss.serialization.QuoteType-) | निर्दिष्ट के बराबर है या नहीं, यह कोट प्रकार की इस इंस्टेंस को दर्शाता है |
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | निर्दिष्ट अनकास्टेड के बराबर है या नहीं, यह कोट प्रकार की इस इंस्टेंस को दर्शाता है |
|
|  | [hashCode()](#hashCode--) | इस अक्षर के लिए हैश-कोड लौटाता है |
|
|  | [op_Equality(QuoteType first, QuoteType second)](#op-Equality-com.groupdocs.editor.htmlcss.serialization.QuoteType-com.groupdocs.editor.htmlcss.serialization.QuoteType-) | जाँचता है कि दो "QuoteType" मान बराबर हैं या नहीं |
|
|  | [op_Inequality(QuoteType first, QuoteType second)](#op-Inequality-com.groupdocs.editor.htmlcss.serialization.QuoteType-com.groupdocs.editor.htmlcss.serialization.QuoteType-) | जाँचता है कि दो "QuoteType" मान बराबर नहीं हैं या नहीं |
|
|  | [to_Char(QuoteType quote)](#to-Char-com.groupdocs.editor.htmlcss.serialization.QuoteType-) | निर्दिष्ट [QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype) इंस्टेंस को char में कास्ट करता है |
|
|  | [to_QuoteType(char character)](#to-QuoteType-char-) | विशिष्ट char को संबंधित [QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype) में कास्ट करता है, यदि कास्टिंग अमान्य हो तो अपवाद फेंकता है |
|
### QuoteType() {#QuoteType--}
```
public QuoteType()
```


### SingleQuote {#SingleQuote}
```
public static final QuoteType SingleQuote
```


सिंगल कोट (U+0027 APOSTROPHE अक्षर)


### DoubleQuote {#DoubleQuote}
```
public static final QuoteType DoubleQuote
```


डबल कोट (U+0022 QUOTATION MARK अक्षर)


### getCode() {#getCode--}
```
public final int getCode()
```


वर्तमान अक्षर का कोड पॉइंट (U+0027 या U+0022)


**Returns:**
int
### getCharacter() {#getCharacter--}
```
public final char getCharacter()
```


उद्धरण के लिए अक्षर


**Returns:**
char
### getHtmlEncoded() {#getHtmlEncoded--}
```
public final String getHtmlEncoded()
```


HTML-एन्कोडेड अक्षर


**Returns:**
java.lang.String
### toString() {#toString--}
```
public String toString()
```


वर्तमान मान के आधार पर "SingleQuote" या "DoubleQuote" स्ट्रिंग लौटाता है


**Returns:**
java.lang.String -
### equals(QuoteType other) {#equals-com.groupdocs.editor.htmlcss.serialization.QuoteType-}
```
public final boolean equals(QuoteType other)
```


निर्दिष्ट के बराबर है या नहीं, यह कोट प्रकार की इस इंस्टेंस को दर्शाता है


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | other | [QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype) | जाँच के लिए QuoteType का अन्य इंस्टेंस |
|

**Returns:**
boolean - यदि समान हों तो true, यदि असमान हों तो false।

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


निर्दिष्ट अनकास्टेड के बराबर है या नहीं, यह कोट प्रकार की इस इंस्टेंस को दर्शाता है


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | obj | java.lang.Object | अनकास्टेड ऑब्जेक्ट, अपेक्षित है कि यह [QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype) प्रकार का हो |
|

**Returns:**
boolean - यदि समान हों तो true, यदि असमान हों तो false।

### hashCode() {#hashCode--}
```
public int hashCode()
```


इस अक्षर के लिए हैश-कोड लौटाता है


**Returns:**
int - Hash-code एक साइन किए हुए पूर्णांक के रूप में

### op_Equality(QuoteType first, QuoteType second) {#op-Equality-com.groupdocs.editor.htmlcss.serialization.QuoteType-com.groupdocs.editor.htmlcss.serialization.QuoteType-}
```
public static boolean op_Equality(QuoteType first, QuoteType second)
```


जाँचता है कि दो "QuoteType" मान बराबर हैं या नहीं


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | first | [QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype) | जाँचने के लिए पहला मान |
|
|  | second | [QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype) | जाँचने के लिए दूसरा मान |
|

**Returns:**
boolean - यदि समान हों तो true, अन्यथा false

### op_Inequality(QuoteType first, QuoteType second) {#op-Inequality-com.groupdocs.editor.htmlcss.serialization.QuoteType-com.groupdocs.editor.htmlcss.serialization.QuoteType-}
```
public static boolean op_Inequality(QuoteType first, QuoteType second)
```


जाँचता है कि दो "QuoteType" मान बराबर नहीं हैं या नहीं


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | first | [QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype) | जाँचने के लिए पहला मान |
|
|  | second | [QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype) | जाँचने के लिए दूसरा मान |
|

**Returns:**
boolean - यदि समान हों तो false, अन्यथा true

### to_Char(QuoteType quote) {#to-Char-com.groupdocs.editor.htmlcss.serialization.QuoteType-}
```
public static char to_Char(QuoteType quote)
```


निर्दिष्ट [QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype) इंस्टेंस को char में कास्ट करता है


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | quote | [QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype) | कास्ट करने के लिए Quote type इंस्टेंस |
|

**Returns:**
char
### to_QuoteType(char character) {#to-QuoteType-char-}
```
public static QuoteType to_QuoteType(char character)
```


विशिष्ट char को संबंधित [QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype) में कास्ट करता है, यदि कास्टिंग अमान्य हो तो अपवाद फेंकता है


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | अक्षर | char | एक सिंगल कोट (U+0027 APOSTROPHE) या डबल कोट (U+0022 QUOTATION MARK) अक्षर। यदि कोई अन्य अक्षर निर्दिष्ट किया गया तो अपवाद फेंका जाएगा। |
|

**Returns:**
[QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype)
