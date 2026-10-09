---
title: "PresentationEditOptions"
second_title: "GroupDocs.Editor για Node.js μέσω Java API Reference"
description: "Επιτρέπει τον καθορισμό προσαρμοσμένων επιλογών για την επεξεργασία εγγράφων όλων των υποστηριζόμενων μορφών Presentation συμβατών με PowerPoint."
type: docs
weight: 32
url: /el/nodejs-java/com.groupdocs.editor.options/presentationeditoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public class PresentationEditOptions implements IEditOptions
```

Επιτρέπει τον καθορισμό προσαρμοσμένων επιλογών για την επεξεργασία εγγράφων όλων των υποστηριζόμενων
Μορφές Presentation (συμβατές με PowerPoint)

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [PresentationEditOptions()](#PresentationEditOptions--) |  |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getSlideNumber()](#getSlideNumber--) | Επιτρέπει τον καθορισμό των αριθμών διαφανειών που πρέπει να ανοίξουν για επεξεργασία |
|
|  | [setSlideNumber(int value)](#setSlideNumber-int-) | Επιτρέπει τον καθορισμό των αριθμών διαφανειών που πρέπει να ανοίξουν για επεξεργασία |
|
|  | [getShowHiddenSlides()](#getShowHiddenSlides--) | Καθορίζει εάν οι κρυφές διαφάνειες πρέπει να συμπεριληφθούν ή όχι. |
|
|  | [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Καθορίζει εάν οι κρυφές διαφάνειες πρέπει να συμπεριληφθούν ή όχι. |
|
### PresentationEditOptions() {#PresentationEditOptions--}
```
public PresentationEditOptions()
```


### getSlideNumber() {#getSlideNumber--}
```
public final int getSlideNumber()
```


Επιτρέπει τον καθορισμό των αριθμών διαφανειών που πρέπει να ανοίξουν για επεξεργασία


*** ** * ** ***

Ο αριθμός διαφάνειας είναι ένας δείκτης μηδενικής βάσης μιας διαφάνειας, που επιτρέπει τον καθορισμό και την επιλογή μιας συγκεκριμένης διαφάνειας από μια παρουσία για επεξεργασία. Εάν είναι μικρότερος από 0, θα επιλεγεί η πρώτη διαφάνεια (ίδιο με SlideNumber = 0). Εάν είναι μεγαλύτερος από τον αριθμό όλων των διαφανειών στην παρουσία, θα επιλεγεί η τελευταία διαφάνεια. Εάν η είσοδος παρουσία περιέχει μόνο μία διαφάνεια, αυτή η επιλογή θα αγνοηθεί και αυτή η μοναδική διαφάνεια θα υποστεί επεξεργασία. Εάν προσπαθείτε να ανοίξετε για επεξεργασία μια κρυφή διαφάνεια, ενώ η επιλογή ShowHiddenSlides (#getShowHiddenSlides.getShowHiddenSlides/#setShowHiddenSlides(boolean).setShowHiddenSlides(boolean)) είναι ορισμένη σε 'false', θα ριχθεί η εξαίρεση.

<br />



**Returns:**
int
### setSlideNumber(int value) {#setSlideNumber-int-}
```
public final void setSlideNumber(int value)
```


Επιτρέπει τον καθορισμό των αριθμών διαφανειών που πρέπει να ανοίξουν για επεξεργασία


*** ** * ** ***

Ο αριθμός διαφάνειας είναι ένας δείκτης μηδενικής βάσης μιας διαφάνειας, που επιτρέπει τον καθορισμό και την επιλογή μιας συγκεκριμένης διαφάνειας από μια παρουσία για επεξεργασία. Εάν είναι μικρότερος από 0, θα επιλεγεί η πρώτη διαφάνεια (ίδιο με SlideNumber = 0). Εάν είναι μεγαλύτερος από τον αριθμό όλων των διαφανειών στην παρουσία, θα επιλεγεί η τελευταία διαφάνεια. Εάν η είσοδος παρουσία περιέχει μόνο μία διαφάνεια, αυτή η επιλογή θα αγνοηθεί και αυτή η μοναδική διαφάνεια θα υποστεί επεξεργασία. Εάν προσπαθείτε να ανοίξετε για επεξεργασία μια κρυφή διαφάνεια, ενώ η επιλογή ShowHiddenSlides (#getShowHiddenSlides.getShowHiddenSlides/#setShowHiddenSlides(boolean).setShowHiddenSlides(boolean)) είναι ορισμένη σε 'false', θα ριχθεί η εξαίρεση.

<br />



**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public final boolean getShowHiddenSlides()
```


Καθορίζει εάν οι κρυφές διαφάνειες πρέπει να συμπεριληφθούν ή όχι. Προεπιλογή είναι
ψευδές - οι κρυφές διαφάνειες δεν εμφανίζονται και η εξαίρεση θα ριχθεί ενώ
προσπαθείτε να τις επεξεργαστείτε.


**Returns:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public final void setShowHiddenSlides(boolean value)
```


Καθορίζει εάν οι κρυφές διαφάνειες πρέπει να συμπεριληφθούν ή όχι. Προεπιλογή είναι
ψευδές - οι κρυφές διαφάνειες δεν εμφανίζονται και η εξαίρεση θα ριχθεί ενώ
προσπαθείτε να τις επεξεργαστείτε.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

