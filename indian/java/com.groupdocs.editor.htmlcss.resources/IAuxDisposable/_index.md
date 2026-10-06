---
title: "IAuxDisposable"
second_title: "GroupDocs.Editor for Java API संदर्भ"
description: "मानक IDisposable इंटरफ़ेस को विस्तारित करता है, जिससे किसी वस्तु की वर्तमान स्थिति प्राप्त की जा सकती है और निपटान इवेंट की सदस्यता ली जा सकती है"
type: docs
weight: 11
url: /hi/java/com.groupdocs.editor.htmlcss.resources/iauxdisposable/
---
**All Implemented Interfaces:**
[com.groupdocs.editor.interfaces.IDisposable](../../com.groupdocs.editor.interfaces/idisposable)
```
public interface IAuxDisposable extends IDisposable
```

मानक IDisposable इंटरफ़ेस को विस्तारित करता है, वर्तमान प्राप्त करने की अनुमति देता है
ऑब्जेक्ट की स्थिति और डिस्पोज़िंग इवेंट की सदस्यता लें

## Fields

| Field | विवरण |
| --- | --- |
|  | [Disposed](#Disposed) | जब ऑब्जेक्ट डिस्पोज़ हो जाता है तब होता है |
|
## मेथड्स

| मेथड | विवरण |
| --- | --- |
|  | [isDisposed()](#isDisposed--) | निर्धारित करता है कि संसाधन बंद है (true) या नहीं (false |
|
### Disposed {#Disposed}
```
public static final Event<EventHandler> Disposed
```


जब ऑब्जेक्ट डिस्पोज़ हो जाता है तब होता है


### isDisposed() {#isDisposed--}
```
public abstract boolean isDisposed()
```


निर्धारित करता है कि संसाधन बंद है (true) या नहीं (false


**Returns:**
boolean
