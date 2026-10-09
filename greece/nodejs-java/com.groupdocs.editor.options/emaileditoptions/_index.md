---
title: "EmailEditOptions"
second_title: "GroupDocs.Editor για Node.js μέσω Java API Reference"
description: "Επιτρέπει τον καθορισμό προσαρμοσμένων επιλογών για την επεξεργασία εγγράφων σε διαφορετικές μορφές ηλεκτρονικού ταχυδρομείου"
type: docs
weight: 14
url: /el/nodejs-java/com.groupdocs.editor.options/emaileditoptions/
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
|  | [EmailEditOptions()](#EmailEditOptions--) | Αρχικοποιεί ένα νέο παράδειγμα της κλάσης [EmailEditOptions](../../com.groupdocs.editor.options/emaileditoptions), όπου όλες οι επιλογές έχουν οριστεί στις προεπιλεγμένες τιμές |
|
|  | [EmailEditOptions(int mailMessageOutput)](#EmailEditOptions-int-) | Αρχικοποιεί ένα νέο παράδειγμα της κλάσης [EmailEditOptions](../../com.groupdocs.editor.options/emaileditoptions) με |
MailMessageOutput
(#getMailMessageOutput.getMailMessageOutput/#setMailMessageOutput.setMailMessageOutput) παράμετρος
|
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getMailMessageOutput()](#getMailMessageOutput--) | Επιτρέπει τον έλεγχο του ποια τμήματα του μηνύματος ηλεκτρονικού ταχυδρομείου πρέπει να παραδοθούν στο έξοδο [EditableDocument](../../com.groupdocs.editor/editabledocument) και στη συνέχεια στο παραγόμενο HTML |
|
|  | [setMailMessageOutput(int value)](#setMailMessageOutput-int-) | Επιτρέπει τον έλεγχο του ποια τμήματα του μηνύματος ηλεκτρονικού ταχυδρομείου πρέπει να παραδοθούν στο έξοδο [EditableDocument](../../com.groupdocs.editor/editabledocument) και στη συνέχεια στο παραγόμενο HTML |
|
### EmailEditOptions() {#EmailEditOptions--}
```
public EmailEditOptions()
```


Αρχικοποιεί ένα νέο παράδειγμα της κλάσης [EmailEditOptions](../../com.groupdocs.editor.options/emaileditoptions), όπου όλες οι επιλογές έχουν οριστεί στις προεπιλεγμένες τιμές


### EmailEditOptions(int mailMessageOutput) {#EmailEditOptions-int-}
```
public EmailEditOptions(int mailMessageOutput)
```


Αρχικοποιεί ένα νέο παράδειγμα της κλάσης [EmailEditOptions](../../com.groupdocs.editor.options/emaileditoptions) με
MailMessageOutput
(#getMailMessageOutput.getMailMessageOutput/#setMailMessageOutput.setMailMessageOutput) παράμετρος


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | mailMessageOutput | int | Η έξοδος του μηνύματος ηλεκτρονικού ταχυδρομείου, η οποία μπορεί επίσης να καθοριστεί μέσω της ιδιότητας |
|

### getMailMessageOutput() {#getMailMessageOutput--}
```
public final int getMailMessageOutput()
```


Επιτρέπει τον έλεγχο του ποια τμήματα του μηνύματος ηλεκτρονικού ταχυδρομείου πρέπει να παραδοθούν στο έξοδο [EditableDocument](../../com.groupdocs.editor/editabledocument) και στη συνέχεια στο παραγόμενο HTML
Τιμή: Σημασμένος enum που ελέγχει τα μέρη του μηνύματος ηλεκτρονικού ταχυδρομείου, που πρέπει να υποβληθούν σε επεξεργασία. Η προεπιλεγμένη τιμή είναι  MailMessageOutput.All


**Returns:**
int
### setMailMessageOutput(int value) {#setMailMessageOutput-int-}
```
public final void setMailMessageOutput(int value)
```


Επιτρέπει τον έλεγχο του ποια τμήματα του μηνύματος ηλεκτρονικού ταχυδρομείου πρέπει να παραδοθούν στο έξοδο [EditableDocument](../../com.groupdocs.editor/editabledocument) και στη συνέχεια στο παραγόμενο HTML
Τιμή: Σημασμένος enum που ελέγχει τα μέρη του μηνύματος ηλεκτρονικού ταχυδρομείου, που πρέπει να υποβληθούν σε επεξεργασία. Η προεπιλεγμένη τιμή είναι  MailMessageOutput.All


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

