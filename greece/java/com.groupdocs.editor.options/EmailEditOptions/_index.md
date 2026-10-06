---
title: "EmailEditOptions"
second_title: "Αναφορά API του GroupDocs.Editor για Java"
description: "Επιτρέπει τον καθορισμό προσαρμοσμένων επιλογών για την επεξεργασία εγγράφων σε διάφορες μορφές ηλεκτρονικού ταχυδρομείου"
type: docs
weight: 14
url: /el/java/com.groupdocs.editor.options/emaileditoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public final class EmailEditOptions implements IEditOptions
```

Επιτρέπει τον καθορισμό προσαρμοσμένων επιλογών για την επεξεργασία εγγράφων σε διαφορετικές μορφές ηλεκτρονικού ταχυδρομείου (email)

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
|  | [EmailEditOptions()](#EmailEditOptions--) | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης [EmailEditOptions](../../com.groupdocs.editor.options/emaileditoptions), όπου όλες οι επιλογές έχουν οριστεί στις προεπιλεγμένες τιμές |
|
|  | [EmailEditOptions(int mailMessageOutput)](#EmailEditOptions-int-) | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης [EmailEditOptions](../../com.groupdocs.editor.options/emaileditoptions) με |
MailMessageOutput
(#getMailMessageOutput.getMailMessageOutput/#setMailMessageOutput.setMailMessageOutput) παράμετρος
|
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getMailMessageOutput()](#getMailMessageOutput--) | Επιτρέπει τον έλεγχο του ποια τμήματα του μηνύματος ηλεκτρονικού ταχυδρομείου πρέπει να παραδοθούν στην έξοδο [EditableDocument](../../com.groupdocs.editor/editabledocument) και στη συνέχεια στο παραγόμενο HTML |
|
|  | [setMailMessageOutput(int value)](#setMailMessageOutput-int-) | Επιτρέπει τον έλεγχο του ποια τμήματα του μηνύματος ηλεκτρονικού ταχυδρομείου πρέπει να παραδοθούν στην έξοδο [EditableDocument](../../com.groupdocs.editor/editabledocument) και στη συνέχεια στο παραγόμενο HTML |
|
### EmailEditOptions() {#EmailEditOptions--}
```
public EmailEditOptions()
```


Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης [EmailEditOptions](../../com.groupdocs.editor.options/emaileditoptions), όπου όλες οι επιλογές έχουν οριστεί στις προεπιλεγμένες τιμές


### EmailEditOptions(int mailMessageOutput) {#EmailEditOptions-int-}
```
public EmailEditOptions(int mailMessageOutput)
```


Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης [EmailEditOptions](../../com.groupdocs.editor.options/emaileditoptions) με
MailMessageOutput
(#getMailMessageOutput.getMailMessageOutput/#setMailMessageOutput.setMailMessageOutput) παράμετρος


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | mailMessageOutput | int | Η έξοδος μηνύματος ηλεκτρονικού ταχυδρομείου, η οποία μπορεί επίσης να καθοριστεί μέσω της ιδιότητας |
|

### getMailMessageOutput() {#getMailMessageOutput--}
```
public final int getMailMessageOutput()
```


Επιτρέπει τον έλεγχο του ποια τμήματα του μηνύματος ηλεκτρονικού ταχυδρομείου πρέπει να παραδοθούν στην έξοδο [EditableDocument](../../com.groupdocs.editor/editabledocument) και στη συνέχεια στο παραγόμενο HTML
Τιμή: Σημαδωμένος enum που ελέγχει τα τμήματα του μηνύματος ηλεκτρονικού ταχυδρομείου, που πρέπει να υποβληθούν σε επεξεργασία. Η προεπιλεγμένη τιμή είναι MailMessageOutput.All


**Returns:**
int
### setMailMessageOutput(int value) {#setMailMessageOutput-int-}
```
public final void setMailMessageOutput(int value)
```


Επιτρέπει τον έλεγχο του ποια τμήματα του μηνύματος ηλεκτρονικού ταχυδρομείου πρέπει να παραδοθούν στην έξοδο [EditableDocument](../../com.groupdocs.editor/editabledocument) και στη συνέχεια στο παραγόμενο HTML
Τιμή: Σημαδωμένος enum που ελέγχει τα τμήματα του μηνύματος ηλεκτρονικού ταχυδρομείου, που πρέπει να υποβληθούν σε επεξεργασία. Η προεπιλεγμένη τιμή είναι MailMessageOutput.All


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

