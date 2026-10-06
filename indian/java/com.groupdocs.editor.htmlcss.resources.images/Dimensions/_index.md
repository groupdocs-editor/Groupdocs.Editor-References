---
title: "आयाम"
second_title: "GroupDocs.Editor for Java API संदर्भ"
description: "एक रास्टर आयताकार छवि की रैखिक आयामों (चौड़ाई और ऊँचाई) को मनमाने इकाई में दर्शाता है।"
type: docs
weight: 10
url: /hi/java/com.groupdocs.editor.htmlcss.resources.images/dimensions/
---
**Inheritance:**
java.lang.Object
```
public class Dimensions
```

एक रास्टर आयताकार की रैखिक आयाम (चौड़ाई और ऊँचाई) को दर्शाता है
इमेज मनमाने इकाई में। अपरिवर्तनीय संरचना।

## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
|  | [Dimensions(int width, int height)](#Dimensions-int-int-) | निर्दिष्ट चौड़ाई और ऊँचाई से एक नया इंस्टेंस बनाता है |
|
## मेथड्स

| मेथड | विवरण |
| --- | --- |
|  | [getWidth()](#getWidth--) | इमेज की चौड़ाई लौटाता है |
|
|  | [getHeight()](#getHeight--) | इमेज की ऊँचाई लौटाता है |
|
|  | [isSquare()](#isSquare--) | निर्धारित करता है कि निर्दिष्ट 'Dimensions' वर्गाकार है या नहीं, अर्थात् |
|
|  | [getArea()](#getArea--) | एक क्षेत्रफल लौटाता है (चौड़ाई x ऊँचाई) |
|
|  | [isEmpty()](#isEmpty--) | निर्धारित करता है कि यह "Dimensions" इंस्टेंस खाली और डिफ़ॉल्ट है या नहीं, अर्थात् |
|
|  | [getAspectRatio()](#getAspectRatio--) | इस आयाम का अनुपात चौड़ाई/ऊँचाई के रूप में |
|
|  | [proportionallyResizeForNewWidth(int targetWidth)](#proportionallyResizeForNewWidth-int-) | एक नया "Dimensions" इंस्टेंस बनाता और लौटाता है, जो अनुपातिक रूप से |
वर्तमान से पुनः आकारित, निर्दिष्ट चौड़ाई के आधार पर
|
|  | [proportionallyResizeForNewHeight(int targetHeight)](#proportionallyResizeForNewHeight-int-) | एक नया "Dimensions" इंस्टेंस बनाता और लौटाता है, जो अनुपातिक रूप से |
वर्तमान से पुनः आकारित, निर्दिष्ट ऊँचाई के आधार पर
|
|  | [equals(Dimensions other)](#equals-com.groupdocs.editor.htmlcss.resources.images.Dimensions-) | निर्धारित करता है कि यह इंस्टेंस निर्दिष्ट "Dimensions" के बराबर है या नहीं |
उदाहरण
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | निर्धारित करता है कि यह उदाहरण निर्दिष्ट अनकास्टेड ऑब्जेक्ट के बराबर है या नहीं, |
जो सम्भवतः एक अन्य "Dimensions" इंस्टेंस है
|
|  | [hashCode()](#hashCode--) | इस इंस्टेंस के लिए एक हैशकोड लौटाता है, जिसे इसके |
जीवनकाल
|
|  | [op_Equality(Dimensions first, Dimensions second)](#op-Equality-com.groupdocs.editor.htmlcss.resources.images.Dimensions-com.groupdocs.editor.htmlcss.resources.images.Dimensions-) | जाँचता है कि दो "Dimensions" मान बराबर हैं या नहीं, अर्थात् |
|
|  | [op_Inequality(Dimensions first, Dimensions second)](#op-Inequality-com.groupdocs.editor.htmlcss.resources.images.Dimensions-com.groupdocs.editor.htmlcss.resources.images.Dimensions-) | जाँचता है कि दो "Dimensions" मान बराबर नहीं हैं या नहीं, अर्थात् |
|
|  | [toString()](#toString--) | इस "Dimensions" की स्ट्रिंग प्रतिनिधित्व लौटाता है |
|
|  | [deepClone()](#deepClone--) | इस इंस्टेंस की पूरी कॉपी लौटाता है |
|
|  | [getEmpty()](#getEmpty--) | एक खाली Dimensions इंस्टेंस लौटाता है |
|
### Dimensions(int width, int height) {#Dimensions-int-int-}
```
public Dimensions(int width, int height)
```


निर्दिष्ट चौड़ाई और ऊँचाई से एक नया इंस्टेंस बनाता है


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | चौड़ाई | int | इमेज की चौड़ाई |
|
|  | ऊँचाई | int | इमेज की ऊँचाई |
|

### getWidth() {#getWidth--}
```
public final int getWidth()
```


इमेज की चौड़ाई लौटाता है


**Returns:**
int
### getHeight() {#getHeight--}
```
public final int getHeight()
```


इमेज की ऊँचाई लौटाता है


**Returns:**
int
### isSquare() {#isSquare--}
```
public final boolean isSquare()
```


निर्धारित करता है कि निर्दिष्ट 'Dimensions' वर्गाकार है या नहीं, अर्थात् यदि
चौड़ाई ऊँचाई के बराबर है


**Returns:**
boolean
### getArea() {#getArea--}
```
public final long getArea()
```


एक क्षेत्रफल लौटाता है (चौड़ाई x ऊँचाई)


**Returns:**
long
### isEmpty() {#isEmpty--}
```
public final boolean isEmpty()
```


निर्धारित करता है कि यह "Dimensions" इंस्टेंस खाली और डिफ़ॉल्ट है या नहीं, अर्थात्
यह सही चौड़ाई और ऊँचाई संग्रहीत नहीं करता है


**Returns:**
boolean
### getAspectRatio() {#getAspectRatio--}
```
public final Ratio getAspectRatio()
```


इस आयाम का अनुपात चौड़ाई/ऊँचाई के रूप में


**Returns:**
[Ratio](../../com.groupdocs.editor.htmlcss.css.datatypes/ratio)
### proportionallyResizeForNewWidth(int targetWidth) {#proportionallyResizeForNewWidth-int-}
```
public final Dimensions proportionallyResizeForNewWidth(int targetWidth)
```


एक नया "Dimensions" इंस्टेंस बनाता और लौटाता है, जो अनुपातिक रूप से
वर्तमान से पुनः आकारित, निर्दिष्ट चौड़ाई के आधार पर


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | targetWidth | int | नई लक्ष्य चौड़ाई, जो परिणामस्वरूप Dimension में उपस्थित होगी |
|

**Returns:**
[Dimensions](../../com.groupdocs.editor.htmlcss.resources.images/dimensions) - New "Dimensions" instance with specified target width and proportionally resized height

### proportionallyResizeForNewHeight(int targetHeight) {#proportionallyResizeForNewHeight-int-}
```
public final Dimensions proportionallyResizeForNewHeight(int targetHeight)
```


एक नया "Dimensions" इंस्टेंस बनाता और लौटाता है, जो अनुपातिक रूप से
वर्तमान से पुनः आकारित, निर्दिष्ट ऊँचाई के आधार पर


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | targetHeight | int | नई लक्ष्य ऊँचाई, जो परिणामस्वरूप Dimension में उपस्थित होगी |
|

**Returns:**
[Dimensions](../../com.groupdocs.editor.htmlcss.resources.images/dimensions) - New "Dimensions" instance with specified target height and proportionally resized width

### equals(Dimensions other) {#equals-com.groupdocs.editor.htmlcss.resources.images.Dimensions-}
```
public final boolean equals(Dimensions other)
```


निर्धारित करता है कि यह इंस्टेंस निर्दिष्ट "Dimensions" के बराबर है या नहीं
उदाहरण


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | other | [Dimensions](../../com.groupdocs.editor.htmlcss.resources.images/dimensions) | समानता जाँचने के लिए अन्य "Dimensions" उदाहरण |
|

**Returns:**
boolean - यदि समान हों तो True, यदि असमान हों तो false

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


निर्धारित करता है कि यह उदाहरण निर्दिष्ट अनकास्टेड ऑब्जेक्ट के बराबर है या नहीं,
जो सम्भवतः एक अन्य "Dimensions" इंस्टेंस है


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | obj | java.lang.Object | अन्य वस्तु, जो सम्भवतः "Dimensions" प्रकार की है, जिसे इस के साथ समानता के लिए जाँचना चाहिए |
|

**Returns:**
boolean - यदि समान हों तो True, यदि असमान हों तो false

### hashCode() {#hashCode--}
```
public int hashCode()
```


इस इंस्टेंस के लिए एक हैशकोड लौटाता है, जिसे इसके
जीवनकाल


**Returns:**
int - इस उदाहरण के लिए अपरिवर्तनीय (Immutable) हैश-कोड, जो साइन किए गए 4-बाइट पूर्णांक के रूप में है

### op_Equality(Dimensions first, Dimensions second) {#op-Equality-com.groupdocs.editor.htmlcss.resources.images.Dimensions-com.groupdocs.editor.htmlcss.resources.images.Dimensions-}
```
public static boolean op_Equality(Dimensions first, Dimensions second)
```


जाँचता है कि दो "Dimensions" मान समान हैं, अर्थात् उनके
चौड़ाई और ऊँचाई समान हैं, या दोनों खाली हैं


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | first | [Dimensions](../../com.groupdocs.editor.htmlcss.resources.images/dimensions) | जाँचने के लिए पहला उदाहरण |
|
|  | second | [Dimensions](../../com.groupdocs.editor.htmlcss.resources.images/dimensions) | जाँचने के लिए दूसरा उदाहरण |
|

**Returns:**
boolean - यदि समान हों तो True, यदि असमान हों तो false

### op_Inequality(Dimensions first, Dimensions second) {#op-Inequality-com.groupdocs.editor.htmlcss.resources.images.Dimensions-com.groupdocs.editor.htmlcss.resources.images.Dimensions-}
```
public static boolean op_Inequality(Dimensions first, Dimensions second)
```


जाँचता है कि दो "Dimensions" मान असमान हैं, अर्थात् उनके
संबंधित चौड़ाई और/या ऊँचाई अलग हैं


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | first | [Dimensions](../../com.groupdocs.editor.htmlcss.resources.images/dimensions) | जाँचने के लिए पहला उदाहरण |
|
|  | second | [Dimensions](../../com.groupdocs.editor.htmlcss.resources.images/dimensions) | जाँचने के लिए दूसरा उदाहरण |
|

**Returns:**
boolean - यदि असमान हों तो True, यदि समान हों तो false

### toString() {#toString--}
```
public String toString()
```


इस "Dimensions" की स्ट्रिंग प्रतिनिधित्व लौटाता है

*** ** * ** ***


> ```
> W640×H480
> ```

<br />



**Returns:**
java.lang.String - स्ट्रिंग उदाहरण, जिसमें W:(width)×H:(height) स्वरूप में चौड़ाई और ऊँचाई होती है

### deepClone() {#deepClone--}
```
public final Dimensions deepClone()
```


इस इंस्टेंस की पूरी कॉपी लौटाता है


**Returns:**
[Dimensions](../../com.groupdocs.editor.htmlcss.resources.images/dimensions) - New instance, that is a full and deep copy of this one

### getEmpty() {#getEmpty--}
```
public static Dimensions getEmpty()
```


एक खाली Dimensions इंस्टेंस लौटाता है


**Returns:**
[Dimensions](../../com.groupdocs.editor.htmlcss.resources.images/dimensions)
