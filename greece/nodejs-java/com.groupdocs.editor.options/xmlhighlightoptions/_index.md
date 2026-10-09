---
title: "XmlHighlightOptions"
second_title: "GroupDocs.Editor για Node.js μέσω Java API Reference"
description: "Περιέχει επιλογές που επιτρέπουν την προσαρμογή της επισήμανσης XML κατά τη μετατροπή XML‑σε‑HTML"
type: docs
weight: 53
url: /el/nodejs-java/com.groupdocs.editor.options/xmlhighlightoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public class XmlHighlightOptions implements IEditOptions
```

Περιέχει επιλογές που επιτρέπουν την προσαρμογή της επισήμανσης XML κατά τη μετατροπή XML-to-HTML.

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getXmlTagsFontSettings()](#getXmlTagsFontSettings--) | Υπεύθυνο για την αναπαράσταση της γραμματοσειράς των ετικετών XML (γωνιακές αγκύλες με ονόματα ετικετών) |
|
|  | [getAttributeNamesFontSettings()](#getAttributeNamesFontSettings--) | Υπεύθυνο για την αναπαράσταση της γραμματοσειράς των ονομάτων ιδιοτήτων |
|
|  | [getAttributeValuesFontSettings()](#getAttributeValuesFontSettings--) | Υπεύθυνο για την αναπαράσταση της γραμματοσειράς των τιμών ιδιοτήτων |
|
|  | [getInnerTextFontSettings()](#getInnerTextFontSettings--) | Υπεύθυνο για την αναπαράσταση της γραμματοσειράς του κειμένου εντός ετικέτας |
|
|  | [getHtmlCommentsFontSettings()](#getHtmlCommentsFontSettings--) | Υπεύθυνο για την αναπαράσταση της γραμματοσειράς των σχολίων HTML (συμπεριλαμβανομένου του ζεύγους ανοικτής και κλειστής ετικέτας) |
|
|  | [getCDataFontSettings()](#getCDataFontSettings--) | Υπεύθυνο για την αναπαράσταση της γραμματοσειράς των τμημάτων CDATA (συμπεριλαμβανομένου του ζεύγους ανοικτής και κλειστής ετικέτας) |
|
|  | [isDefault()](#isDefault--) | Καθορίζει εάν αυτό το αντικείμενο επιλογών XML Highlight έχει προεπιλεγμένες ρυθμίσεις γραμματοσειράς |
|
|  | [resetToDefault()](#resetToDefault--) | Επαναφέρει τις τρέχουσες ρυθμίσεις γραμματοσειράς στις προεπιλεγμένες τιμές τους |
|
### getXmlTagsFontSettings() {#getXmlTagsFontSettings--}
```
public final WebFont getXmlTagsFontSettings()
```


Υπεύθυνο για την αναπαράσταση της γραμματοσειράς των ετικετών XML (γωνιακές αγκύλες με ονόματα ετικετών)


**Returns:**
[WebFont](../../com.groupdocs.editor.options/webfont)
### getAttributeNamesFontSettings() {#getAttributeNamesFontSettings--}
```
public final WebFont getAttributeNamesFontSettings()
```


Υπεύθυνο για την αναπαράσταση της γραμματοσειράς των ονομάτων ιδιοτήτων


**Returns:**
[WebFont](../../com.groupdocs.editor.options/webfont)
### getAttributeValuesFontSettings() {#getAttributeValuesFontSettings--}
```
public final WebFont getAttributeValuesFontSettings()
```


Υπεύθυνο για την αναπαράσταση της γραμματοσειράς των τιμών ιδιοτήτων


**Returns:**
[WebFont](../../com.groupdocs.editor.options/webfont)
### getInnerTextFontSettings() {#getInnerTextFontSettings--}
```
public final WebFont getInnerTextFontSettings()
```


Υπεύθυνο για την αναπαράσταση της γραμματοσειράς του κειμένου εντός ετικέτας


**Returns:**
[WebFont](../../com.groupdocs.editor.options/webfont)
### getHtmlCommentsFontSettings() {#getHtmlCommentsFontSettings--}
```
public final WebFont getHtmlCommentsFontSettings()
```


Υπεύθυνο για την αναπαράσταση της γραμματοσειράς των σχολίων HTML (συμπεριλαμβανομένου του ζεύγους ανοικτής και κλειστής ετικέτας)


**Returns:**
[WebFont](../../com.groupdocs.editor.options/webfont)
### getCDataFontSettings() {#getCDataFontSettings--}
```
public final WebFont getCDataFontSettings()
```


Υπεύθυνο για την αναπαράσταση της γραμματοσειράς των τμημάτων CDATA (συμπεριλαμβανομένου του ζεύγους ανοικτής και κλειστής ετικέτας)


**Returns:**
[WebFont](../../com.groupdocs.editor.options/webfont)
### isDefault() {#isDefault--}
```
public final boolean isDefault()
```


Καθορίζει εάν αυτό το αντικείμενο επιλογών XML Highlight έχει προεπιλεγμένες ρυθμίσεις γραμματοσειράς


**Returns:**
boolean
### resetToDefault() {#resetToDefault--}
```
public final void resetToDefault()
```


Επαναφέρει τις τρέχουσες ρυθμίσεις γραμματοσειράς στις προεπιλεγμένες τιμές τους


