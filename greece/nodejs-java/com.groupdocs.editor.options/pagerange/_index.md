---
title: "PageRange"
second_title: "GroupDocs.Editor για Node.js μέσω Java API Reference"
description: "Περιλαμβάνει ένα εύρος σελίδων που μπορεί να έχει ανοιχτά ή κλειστά όρια."
type: docs
weight: 27
url: /el/nodejs-java/com.groupdocs.editor.options/pagerange/
---
**Inheritance:**
java.lang.Object
```
public class PageRange
```

Περιλαμβάνει ένα εύρος σελίδων, το οποίο μπορεί να έχει ανοιχτά ή κλειστά όρια. Από προεπιλογή είναι "πλήρως ανοιχτό" - περιλαμβάνει όλες τις υπάρχουσες σελίδες. Η αρίθμηση των σελίδων ξεκινά από 1, όχι από 0.

<br />

*** ** * ** ***

Αμετάβλητη δομή που περιλαμβάνει ένα εύρος σελίδων, το οποίο δεν σχετίζεται με κάποιο συγκεκριμένο έγγραφο και μπορεί να αντιπροσωπεύει ένα εύρος σελίδων για οποιοδήποτε έγγραφο.

<br />


## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [PageRange()](#PageRange--) |  |
## Πεδία

| Πεδίο | Περιγραφή |
| --- | --- |
|  | [AllPages](#AllPages) | Αντιπροσωπεύει όλες τις υπάρχουσες σελίδες ενός εγγράφου. |
|
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getStartNumber()](#getStartNumber--) | Συμπεριλαμβανομένος αριθμός αρχικής σελίδας, από τον οποίο ξεκινά αυτό το εύρος σελίδων. |
|
|  | [getEndNumber()](#getEndNumber--) | Αποκλειστικός αριθμός τελικής σελίδας, μέχρι τον οποίο συνεχίζεται αυτό το εύρος σελίδων και στο οποίο σταματά αποκλειστικά. |
|
|  | [getCount()](#getCount--) | Αριθμοί σελίδων εντός του εύρους. |
|
|  | [isDefault()](#isDefault--) | Δείχνει εάν αυτή η παρουσία αντιπροσωπεύει ένα προεπιλεγμένο "πλήρως ανοιχτό" εύρος σελίδων, δηλαδή. |
|
|  | [equals(PageRange other)](#equals-com.groupdocs.editor.options.PageRange-) | Εντοπίζει εάν αυτή η παρουσία του PageRange είναι ίση με την καθορισμένη |
|
|  | [fromBeginningWithCount(int pageCount)](#fromBeginningWithCount-int-) | Δημιουργεί ένα εύρος σελίδων, που ξεκινά από την πρώτη σελίδα και έχει καθορισμένο αριθμό σελίδων |
|
|  | [fromStartPageTillEnd(int startPageNumber)](#fromStartPageTillEnd-int-) | Δημιουργεί ένα εύρος σελίδων, που ξεκινά από τον καθορισμένο αριθμό σελίδας και συνεχίζει μέχρι το τέλος του εγγράφου |
|
|  | [fromStartPageWithCount(int startPageNumber, int pageCount)](#fromStartPageWithCount-int-int-) | Δημιουργεί ένα εύρος σελίδων, που ξεκινά από τον καθορισμένο αριθμό σελίδας και έχει καθορισμένο αριθμό σελίδων, ή απεριόριστο αριθμό σελίδων (μέχρι το τέλος) |
|
|  | [fromStartPageTillEndPage(int startPageNumber, int endPageNumber)](#fromStartPageTillEndPage-int-int-) | Δημιουργεί ένα εύρος σελίδων, που ξεκινά από τον καθορισμένο αριθμό σελίδας (συμπεριλαμβανομένου) και συνεχίζει μέχρι τον καθορισμένο αριθμό σελίδας (αποκλειστικά) |
|
### PageRange() {#PageRange--}
```
public PageRange()
```


### AllPages {#AllPages}
```
public static final PageRange AllPages
```


Αντιπροσωπεύει όλες τις υπάρχουσες σελίδες ενός εγγράφου. Προεπιλεγμένη τιμή.


### getStartNumber() {#getStartNumber--}
```
public final int getStartNumber()
```


Συμπεριλαμβανομένος αριθμός αρχικής σελίδας, από τον οποίο ξεκινά αυτό το εύρος σελίδων. Αν 1 - το εύρος σελίδων ξεκινά από την πρώτη σελίδα ενός εγγράφου


**Returns:**
int
### getEndNumber() {#getEndNumber--}
```
public final int getEndNumber()
```


Αποκλειστικός αριθμός τελικής σελίδας, μέχρι τον οποίο συνεχίζεται αυτό το εύρος σελίδων και στο οποίο σταματά αποκλειστικά. Αν 0 - το εύρος σελίδων επεκτείνεται μέχρι το τέλος του εγγράφου


**Returns:**
int
### getCount() {#getCount--}
```
public final int getCount()
```


Αριθμοί σελίδων εντός του εύρους. Αν 0 - το εύρος σελίδων επεκτείνεται μέχρι το τέλος του εγγράφου, ανεξάρτητα από τον αριθμό των σελίδων που περιέχει


**Returns:**
int
### isDefault() {#isDefault--}
```
public final boolean isDefault()
```


Δείχνει εάν αυτή η παρουσία αντιπροσωπεύει ένα προεπιλεγμένο "πλήρως ανοιχτό" εύρος σελίδων, δηλαδή περιλαμβάνει όλες τις σελίδες ενός εγγράφου


**Returns:**
boolean
### equals(PageRange other) {#equals-com.groupdocs.editor.options.PageRange-}
```
public final boolean equals(PageRange other)
```


Εντοπίζει εάν αυτή η παρουσία του PageRange είναι ίση με την καθορισμένη


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | other | [PageRange](../../com.groupdocs.editor.options/pagerange) | Άλλη παρουσία του PageRange για έλεγχο ισότητας |
|

**Returns:**
boolean - true αν είναι ίσες· false αν είναι διαφορετικές

### fromBeginningWithCount(int pageCount) {#fromBeginningWithCount-int-}
```
public static PageRange fromBeginningWithCount(int pageCount)
```


Δημιουργεί ένα εύρος σελίδων, που ξεκινά από την πρώτη σελίδα και έχει καθορισμένο αριθμό σελίδων


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | pageCount | int | Αριθμός σελίδων, πρέπει να είναι αυστηρά μεγαλύτερος από το μηδέν |
|

**Returns:**
[PageRange](../../com.groupdocs.editor.options/pagerange) - New PageRange instance

### fromStartPageTillEnd(int startPageNumber) {#fromStartPageTillEnd-int-}
```
public static PageRange fromStartPageTillEnd(int startPageNumber)
```


Δημιουργεί ένα εύρος σελίδων, που ξεκινά από τον καθορισμένο αριθμό σελίδας και συνεχίζει μέχρι το τέλος του εγγράφου


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | startPageNumber | int | Αριθμός σελίδας, από τον οποίο ξεκινά το εύρος σελίδων, συμπεριλαμβανομένου. Οι αριθμοί σελίδων είναι 1-βάση, έτσι πρέπει να είναι αυστηρά μεγαλύτεροι από το μηδέν |
|

**Returns:**
[PageRange](../../com.groupdocs.editor.options/pagerange) - New PageRange instance

### fromStartPageWithCount(int startPageNumber, int pageCount) {#fromStartPageWithCount-int-int-}
```
public static PageRange fromStartPageWithCount(int startPageNumber, int pageCount)
```


Δημιουργεί ένα εύρος σελίδων, που ξεκινά από τον καθορισμένο αριθμό σελίδας και έχει καθορισμένο αριθμό σελίδων, ή απεριόριστο αριθμό σελίδων (μέχρι το τέλος)


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | startPageNumber | int | Αριθμός σελίδας, από τον οποίο ξεκινά το εύρος σελίδων, συμπεριλαμβανομένου. Οι αριθμοί σελίδων είναι 1-βάση, έτσι πρέπει να είναι αυστηρά μεγαλύτεροι από το μηδέν |
|
|  | pageCount | int | Αριθμός σελίδων, πρέπει να είναι αυστηρά μεγαλύτερος από το μηδέν. Αν μηδέν - αυτό σημαίνει όλες τις σελίδες μέχρι το τέλος ενός εγγράφου |
|

**Returns:**
[PageRange](../../com.groupdocs.editor.options/pagerange) - New PageRange instance

### fromStartPageTillEndPage(int startPageNumber, int endPageNumber) {#fromStartPageTillEndPage-int-int-}
```
public static PageRange fromStartPageTillEndPage(int startPageNumber, int endPageNumber)
```


Δημιουργεί ένα εύρος σελίδων, που ξεκινά από τον καθορισμένο αριθμό σελίδας (συμπεριλαμβανομένου) και συνεχίζει μέχρι τον καθορισμένο αριθμό σελίδας (αποκλειστικά)


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | startPageNumber | int | Αριθμός σελίδας, από τον οποίο ξεκινά το εύρος σελίδων, συμπεριλαμβανομένου. Οι αριθμοί σελίδων είναι 1-βάση, έτσι πρέπει να είναι αυστηρά μεγαλύτεροι από το μηδέν |
|
|  | endPageNumber | int | Αριθμός σελίδας, μέχρι τον οποίο συνεχίζεται το εύρος σελίδων, αποκλειστικά. Οι αριθμοί σελίδων είναι 1-βάση, έτσι πρέπει να είναι αυστηρά μεγαλύτεροι από το startPageNumber |
|

**Returns:**
[PageRange](../../com.groupdocs.editor.options/pagerange) - 
