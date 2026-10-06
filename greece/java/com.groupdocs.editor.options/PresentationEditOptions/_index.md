---
title: "PresentationEditOptions"
second_title: "Αναφορά API του GroupDocs.Editor για Java"
description: "Επιτρέπει τον καθορισμό προσαρμοσμένων επιλογών για την επεξεργασία εγγράφων όλων των υποστηριζόμενων μορφών Παρουσίασης συμβατών με PowerPoint"
type: docs
weight: 32
url: /el/java/com.groupdocs.editor.options/presentationeditoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public class PresentationEditOptions implements IEditOptions
```

Επιτρέπει τον καθορισμό προσαρμοσμένων επιλογών για την επεξεργασία εγγράφων όλων των υποστηριζόμενων
Μορφές Παρουσίασης (συμβατές με PowerPoint)

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [PresentationEditOptions()](#PresentationEditOptions--) |  |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getSlideNumber()](#getSlideNumber--) | Επιτρέπει τον καθορισμό των αριθμών των διαφανειών που πρέπει να ανοιχτούν για επεξεργασία |
|
|  | [setSlideNumber(int value)](#setSlideNumber-int-) | Επιτρέπει τον καθορισμό των αριθμών των διαφανειών που πρέπει να ανοιχτούν για επεξεργασία |
|
|  | [getShowHiddenSlides()](#getShowHiddenSlides--) | Καθορίζει αν οι κρυφές διαφάνειες πρέπει να συμπεριληφθούν ή όχι. |
|
|  | [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Καθορίζει αν οι κρυφές διαφάνειες πρέπει να συμπεριληφθούν ή όχι. |
|
### PresentationEditOptions() {#PresentationEditOptions--}
```
public PresentationEditOptions()
```


### getSlideNumber() {#getSlideNumber--}
```
public final int getSlideNumber()
```


Επιτρέπει τον καθορισμό των αριθμών των διαφανειών που πρέπει να ανοιχτούν για επεξεργασία


*** ** * ** ***

Ο αριθμός διαφάνειας είναι ένας δείκτης μηδενικής βάσης μιας διαφάνειας, που επιτρέπει τον καθορισμό και την επιλογή μιας συγκεκριμένης διαφάνειας από μια παρουσίαση για επεξεργασία. Εάν είναι μικρότερος από 0, θα επιλεγεί η πρώτη διαφάνεια (ίδιο με SlideNumber = 0). Εάν είναι μεγαλύτερος από τον αριθμό όλων των διαφανειών στην παρουσίαση, θα επιλεγεί η τελευταία διαφάνεια. Εάν η εισερχόμενη παρουσίαση περιέχει μόνο μία διαφάνεια, αυτή η επιλογή θα αγνοηθεί και αυτή η μοναδική διαφάνεια θα επεξεργαστεί. Εάν προσπαθήσετε να ανοίξετε για επεξεργασία μια κρυφή διαφάνεια, ενώ η επιλογή ShowHiddenSlides (#getShowHiddenSlides.getShowHiddenSlides/#setShowHiddenSlides(boolean).setShowHiddenSlides(boolean)) είναι ορισμένη σε 'false', θα προκληθεί εξαίρεση.

<br />



**Returns:**
int
### setSlideNumber(int value) {#setSlideNumber-int-}
```
public final void setSlideNumber(int value)
```


Επιτρέπει τον καθορισμό των αριθμών των διαφανειών που πρέπει να ανοιχτούν για επεξεργασία


*** ** * ** ***

Ο αριθμός διαφάνειας είναι ένας δείκτης μηδενικής βάσης μιας διαφάνειας, που επιτρέπει τον καθορισμό και την επιλογή μιας συγκεκριμένης διαφάνειας από μια παρουσίαση για επεξεργασία. Εάν είναι μικρότερος από 0, θα επιλεγεί η πρώτη διαφάνεια (ίδιο με SlideNumber = 0). Εάν είναι μεγαλύτερος από τον αριθμό όλων των διαφανειών στην παρουσίαση, θα επιλεγεί η τελευταία διαφάνεια. Εάν η εισερχόμενη παρουσίαση περιέχει μόνο μία διαφάνεια, αυτή η επιλογή θα αγνοηθεί και αυτή η μοναδική διαφάνεια θα επεξεργαστεί. Εάν προσπαθήσετε να ανοίξετε για επεξεργασία μια κρυφή διαφάνεια, ενώ η επιλογή ShowHiddenSlides (#getShowHiddenSlides.getShowHiddenSlides/#setShowHiddenSlides(boolean).setShowHiddenSlides(boolean)) είναι ορισμένη σε 'false', θα προκληθεί εξαίρεση.

<br />



**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public final boolean getShowHiddenSlides()
```


Καθορίζει αν οι κρυφές διαφάνειες πρέπει να συμπεριληφθούν ή όχι. Η προεπιλογή είναι
false - οι κρυφές διαφάνειες δεν εμφανίζονται και θα προκληθεί εξαίρεση ενώ
προσπαθείτε να τις επεξεργαστείτε.


**Returns:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public final void setShowHiddenSlides(boolean value)
```


Καθορίζει αν οι κρυφές διαφάνειες πρέπει να συμπεριληφθούν ή όχι. Η προεπιλογή είναι
false - οι κρυφές διαφάνειες δεν εμφανίζονται και θα προκληθεί εξαίρεση ενώ
προσπαθείτε να τις επεξεργαστείτε.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

