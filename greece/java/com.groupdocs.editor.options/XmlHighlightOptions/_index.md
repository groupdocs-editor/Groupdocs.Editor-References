---
title: "Περιέχει επιλογές που επιτρέπουν την προσαρμογή της επισήμανσης XML κατά τη μετατροπή XML-σε-HTML"
second_title: "Αναφορά API του GroupDocs.Editor για Java"
description: "Υπεύθυνο για την αναπαράσταση της γραμματοσειράς των ετικετών XML (γωνιακές αγκύλες με τα ονόματα των ετικετών)"
type: docs
weight: 53
url: /el/java/com.groupdocs.editor.options/xmlhighlightoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public class XmlHighlightOptions implements IEditOptions
```

Περιέχει επιλογές που επιτρέπουν την προσαρμογή της επισήμανσης XML κατά τη μετατροπή XML-σε-HTML.

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getXmlTagsFontSettings()](#getXmlTagsFontSettings--) | Υπεύθυνο για την αναπαράσταση της γραμματοσειράς των ονομάτων χαρακτηριστικών |
|
|  | [getAttributeNamesFontSettings()](#getAttributeNamesFontSettings--) | Υπεύθυνο για την αναπαράσταση της γραμματοσειράς των τιμών χαρακτηριστικών |
|
|  | [getAttributeValuesFontSettings()](#getAttributeValuesFontSettings--) | Υπεύθυνο για την αναπαράσταση της γραμματοσειράς του κειμένου εντός ετικέτας |
|
|  | [getInnerTextFontSettings()](#getInnerTextFontSettings--) | Υπεύθυνο για την αναπαράσταση της γραμματοσειράς των σχολίων HTML (συμπεριλαμβανομένου του ζεύγους ανοίγματος και κλεισίματος ετικετών) |
|
|  | [getHtmlCommentsFontSettings()](#getHtmlCommentsFontSettings--) | Υπεύθυνο για την αναπαράσταση της γραμματοσειράς των ενοτήτων CDATA (συμπεριλαμβανομένου του ζεύγους ανοίγματος και κλεισίματος ετικετών) |
|
|  | [getCDataFontSettings()](#getCDataFontSettings--) | Καθορίζει εάν αυτό το αντικείμενο επιλογών XML Highlight έχει προεπιλεγμένες ρυθμίσεις γραμματοσειράς |
|
|  | [isDefault()](#isDefault--) | Επαναφέρει τις τρέχουσες ρυθμίσεις γραμματοσειράς στις προεπιλεγμένες τιμές |
|
|  | [resetToDefault()](#resetToDefault--) | WordProcessingEditOptions |
|
### getXmlTagsFontSettings() {#getXmlTagsFontSettings--}
```
public final WebFont getXmlTagsFontSettings()
```


Υπεύθυνο για την αναπαράσταση της γραμματοσειράς των ονομάτων χαρακτηριστικών


**Returns:**
[WebFont](../../com.groupdocs.editor.options/webfont)
### getAttributeNamesFontSettings() {#getAttributeNamesFontSettings--}
```
public final WebFont getAttributeNamesFontSettings()
```


Υπεύθυνο για την αναπαράσταση της γραμματοσειράς των τιμών χαρακτηριστικών


**Returns:**
[WebFont](../../com.groupdocs.editor.options/webfont)
### getAttributeValuesFontSettings() {#getAttributeValuesFontSettings--}
```
public final WebFont getAttributeValuesFontSettings()
```


Υπεύθυνο για την αναπαράσταση της γραμματοσειράς του κειμένου εντός ετικέτας


**Returns:**
[WebFont](../../com.groupdocs.editor.options/webfont)
### getInnerTextFontSettings() {#getInnerTextFontSettings--}
```
public final WebFont getInnerTextFontSettings()
```


Υπεύθυνο για την αναπαράσταση της γραμματοσειράς των σχολίων HTML (συμπεριλαμβανομένου του ζεύγους ανοίγματος και κλεισίματος ετικετών)


**Returns:**
[WebFont](../../com.groupdocs.editor.options/webfont)
### getHtmlCommentsFontSettings() {#getHtmlCommentsFontSettings--}
```
public final WebFont getHtmlCommentsFontSettings()
```


Υπεύθυνο για την αναπαράσταση της γραμματοσειράς των ενοτήτων CDATA (συμπεριλαμβανομένου του ζεύγους ανοίγματος και κλεισίματος ετικετών)


**Returns:**
[WebFont](../../com.groupdocs.editor.options/webfont)
### getCDataFontSettings() {#getCDataFontSettings--}
```
public final WebFont getCDataFontSettings()
```


Καθορίζει εάν αυτό το αντικείμενο επιλογών XML Highlight έχει προεπιλεγμένες ρυθμίσεις γραμματοσειράς


**Returns:**
[WebFont](../../com.groupdocs.editor.options/webfont)
### isDefault() {#isDefault--}
```
public final boolean isDefault()
```


Επαναφέρει τις τρέχουσες ρυθμίσεις γραμματοσειράς στις προεπιλεγμένες τιμές


**Returns:**
boolean
### resetToDefault() {#resetToDefault--}
```
public final void resetToDefault()
```


WordProcessingEditOptions


