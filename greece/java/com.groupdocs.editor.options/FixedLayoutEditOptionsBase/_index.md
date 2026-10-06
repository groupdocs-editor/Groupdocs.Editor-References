---
title: "FixedLayoutEditOptionsBase"
second_title: "Αναφορά API του GroupDocs.Editor για Java"
description: "Βασική αφηρημένη κλάση για τις επιλογές όλων των εγγράφων σταθερού μορφοτύπου όπως PDF και XPS"
type: docs
weight: 16
url: /el/java/com.groupdocs.editor.options/fixedlayouteditoptionsbase/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public abstract class FixedLayoutEditOptionsBase implements IEditOptions
```

Βασική αφηρημένη κλάση για τις επιλογές όλων των εγγράφων σταθερού μορφοτύπου όπως PDF και XPS

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [FixedLayoutEditOptionsBase()](#FixedLayoutEditOptionsBase--) |  |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getSkipImages()](#getSkipImages--) | Λαμβάνει ή ορίζει τη σημαία που υποδεικνύει εάν οι εικόνες πρέπει να παραλειφθούν κατά τη μετατροπή του εισερχόμενου εγγράφου σταθερής διάταξης στο τελικό HTML. |
|
|  | [setSkipImages(boolean value)](#setSkipImages-boolean-) | Λαμβάνει ή ορίζει τη σημαία που υποδεικνύει εάν οι εικόνες πρέπει να παραλειφθούν κατά τη μετατροπή του εισερχόμενου εγγράφου σταθερής διάταξης στο τελικό HTML. |
|
|  | [getPages()](#getPages--) | Επιτρέπει τον ορισμό ενός εύρους σελίδων για επεξεργασία. |
|
|  | [setPages(PageRange value)](#setPages-com.groupdocs.editor.options.PageRange-) | Επιτρέπει τον ορισμό ενός εύρους σελίδων για επεξεργασία. |
|
|  | [getEnablePagination()](#getEnablePagination--) | Επιτρέπει την ενεργοποίηση (true) ή την απενεργοποίηση (false) του σελιδοποίησης στο τελικό έγγραφο HTML. |
|
|  | [setEnablePagination(boolean value)](#setEnablePagination-boolean-) | Επιτρέπει την ενεργοποίηση (true) ή την απενεργοποίηση (false) του σελιδοποίησης στο τελικό έγγραφο HTML. |
|
### FixedLayoutEditOptionsBase() {#FixedLayoutEditOptionsBase--}
```
public FixedLayoutEditOptionsBase()
```


### getSkipImages() {#getSkipImages--}
```
public final boolean getSkipImages()
```


Λαμβάνει ή ορίζει τη σημαία που υποδεικνύει εάν οι εικόνες πρέπει να παραλειφθούν κατά τη μετατροπή του εισερχόμενου εγγράφου σταθερής διάταξης στο τελικό HTML. Η προεπιλογή είναι false — οι εικόνες διατηρούνται.


**Returns:**
boolean
### setSkipImages(boolean value) {#setSkipImages-boolean-}
```
public final void setSkipImages(boolean value)
```


Λαμβάνει ή ορίζει τη σημαία που υποδεικνύει εάν οι εικόνες πρέπει να παραλειφθούν κατά τη μετατροπή του εισερχόμενου εγγράφου σταθερής διάταξης στο τελικό HTML. Η προεπιλογή είναι false — οι εικόνες διατηρούνται.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### getPages() {#getPages--}
```
public final PageRange getPages()
```


Επιτρέπει τον ορισμό ενός εύρους σελίδων για επεξεργασία. Από προεπιλογή όλες οι σελίδες ενός εγγράφου σταθερής διάταξης επεξεργάζονται.


**Returns:**
[PageRange](../../com.groupdocs.editor.options/pagerange)
### setPages(PageRange value) {#setPages-com.groupdocs.editor.options.PageRange-}
```
public final void setPages(PageRange value)
```


Επιτρέπει τον ορισμό ενός εύρους σελίδων για επεξεργασία. Από προεπιλογή όλες οι σελίδες ενός εγγράφου σταθερής διάταξης επεξεργάζονται.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [PageRange](../../com.groupdocs.editor.options/pagerange) |  |

### getEnablePagination() {#getEnablePagination--}
```
public final boolean getEnablePagination()
```


Επιτρέπει την ενεργοποίηση (true) ή την απενεργοποίηση (false) του σελιδοποίησης στο τελικό έγγραφο HTML. Από προεπιλογή είναι απενεργοποιημένο (false).

<br />

*** ** * ** ***

Τα έγγραφα μορφής σταθερής διάταξης (ιδιαίτερα PDF και XPS) είναι στην ουσία αυστηρά σελιδοποιημένα, το περιεχόμενό τους έχει σταθερή διάταξη και χωρίζεται σε σελίδες. Ωστόσο, το τελικό επεξεργάσιμο HTML μπορεί να εμφανιστεί είτε χωρίς σελίδες είτε σε σελιδοποιημένη προβολή.

<br />



**Returns:**
boolean
### setEnablePagination(boolean value) {#setEnablePagination-boolean-}
```
public final void setEnablePagination(boolean value)
```


Επιτρέπει την ενεργοποίηση (true) ή την απενεργοποίηση (false) του σελιδοποίησης στο τελικό έγγραφο HTML. Από προεπιλογή είναι απενεργοποιημένο (false).

<br />

*** ** * ** ***

Τα έγγραφα μορφής σταθερής διάταξης (ιδιαίτερα PDF και XPS) είναι στην ουσία αυστηρά σελιδοποιημένα, το περιεχόμενό τους έχει σταθερή διάταξη και χωρίζεται σε σελίδες. Ωστόσο, το τελικό επεξεργάσιμο HTML μπορεί να εμφανιστεί είτε χωρίς σελίδες είτε σε σελιδοποιημένη προβολή.

<br />



**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

