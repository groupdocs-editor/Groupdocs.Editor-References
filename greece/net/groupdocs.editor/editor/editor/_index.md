---
title: Editor
second_title: GroupDocs.Editor για Αναφορά API .NET
description: Αρχικοποιεί νέα παρουσία του Editor με καθορισμένο έγγραφο εισόδου ως ροή
type: docs
weight: 10
url: /el/net/groupdocs.editor/editor/editor/
---
## Editor(Func&lt;Stream&gt;) {#constructor}

Αρχικοποιεί νέα παρουσία του Editor με καθορισμένο έγγραφο εισόδου (ως ροή)

```csharp
public Editor(Func<Stream> document)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| document | Func`1 | Εκπρόσωπος, που θα πρέπει να επιστρέψει μια ροή με περιεχόμενο εγγράφου. Δεν πρέπει να είναι NULL. |

### Παρατηρήσεις

**Μάθε περισσότερα**

* Περισσότερα σχετικά με τους τύπους αρχείων που υποστηρίζονται από το GroupDocs.Editor: [Μορφές εγγράφων που υποστηρίζονται από το GroupDocs.Editor](https://docs.groupdocs.com/display/editornet/Supported+Document+Formats)
* Περισσότερα για το GroupDocs.Editor για λειτουργίες .NET: [Οδηγός προγραμματιστή](https://docs.groupdocs.com/display/editornet/Developer+Guide)

### Δείτε επίσης

* class [Editor](../../editor)
* χώρος ονομάτων [GroupDocs.Editor](../../editor)
* συνέλευση [GroupDocs.Editor](../../../)

---

## Editor(Func&lt;Stream&gt;, Func&lt;ILoadOptions&gt;) {#constructor_1}

Αρχικοποιεί νέα παρουσία του Editor με καθορισμένο έγγραφο εισόδου (ως ροή) με τις επιλογές φόρτωσης

```csharp
public Editor(Func<Stream> document, Func<ILoadOptions> loadOptions)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| document | Func`1 | Εκπρόσωπος, που θα πρέπει να επιστρέψει μια ροή με περιεχόμενο εγγράφου. Δεν πρέπει να είναι NULL. |
| loadOptions | Func`1 | Εκπρόσωπος, που θα πρέπει να επιστρέψει επιλογές φόρτωσης εγγράφου. Μπορεί να είναι NULL και μπορεί να επιστρέψει null - σε αυτήν την περίπτωση ο τύπος εγγράφου θα εντοπιστεί αυτόματα και θα εφαρμοστούν οι προεπιλεγμένες επιλογές φόρτωσης για αυτόν τον τύπο. |

### Παρατηρήσεις

**Μάθε περισσότερα**

* Περισσότερα σχετικά με τους τύπους αρχείων που υποστηρίζονται από το GroupDocs.Editor: [Μορφές εγγράφων που υποστηρίζονται από το GroupDocs.Editor](https://docs.groupdocs.com/display/editornet/Supported+Document+Formats)
* Περισσότερα για το GroupDocs.Editor για λειτουργίες .NET: [Οδηγός προγραμματιστή](https://docs.groupdocs.com/display/editornet/Developer+Guide)
* Περισσότερα σχετικά με τον τρόπο ανοίγματος και επεξεργασίας εγγράφων και εγγράφων που προστατεύονται με κωδικό πρόσβασης από διαφορετικούς χώρους αποθήκευσης: [Φορτώστε και επεξεργαστείτε έγγραφα χρησιμοποιώντας το GroupDocs.Editor](https://docs.groupdocs.com/display/editornet/Load+document)

### Δείτε επίσης

* interface [ILoadOptions](../../../groupdocs.editor.options/iloadoptions)
* class [Editor](../../editor)
* χώρος ονομάτων [GroupDocs.Editor](../../editor)
* συνέλευση [GroupDocs.Editor](../../../)

---

## Editor(string) {#constructor_2}

Αρχικοποιεί νέα παρουσία του Editor με καθορισμένο έγγραφο εισόδου (ως πλήρη διαδρομή αρχείου)

```csharp
public Editor(string filePath)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| filePath | String | Πλήρης διαδρομή προς το αρχείο. Δεν πρέπει να είναι NULL. Θα πρέπει να είναι έγκυρο και το αρχείο πρέπει να υπάρχει. |

### Παρατηρήσεις

**Μάθε περισσότερα**

* Περισσότερα σχετικά με τους τύπους αρχείων που υποστηρίζονται από το GroupDocs.Editor: [Μορφές εγγράφων που υποστηρίζονται από το GroupDocs.Editor](https://docs.groupdocs.com/display/editornet/Supported+Document+Formats)
* Περισσότερα για το GroupDocs.Editor για λειτουργίες .NET: [Οδηγός προγραμματιστή](https://docs.groupdocs.com/display/editornet/Developer+Guide)

### Δείτε επίσης

* class [Editor](../../editor)
* χώρος ονομάτων [GroupDocs.Editor](../../editor)
* συνέλευση [GroupDocs.Editor](../../../)

---

## Editor(string, Func&lt;ILoadOptions&gt;) {#constructor_3}

Αρχικοποιεί νέα παρουσία του Editor με καθορισμένο έγγραφο εισόδου (ως πλήρη διαδρομή αρχείου) με τις επιλογές φόρτωσης

```csharp
public Editor(string filePath, Func<ILoadOptions> loadOptions)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| filePath | String | Πλήρης διαδρομή προς το αρχείο. Δεν πρέπει να είναι NULL. Θα πρέπει να είναι έγκυρο και το αρχείο πρέπει να υπάρχει. |
| loadOptions | Func`1 | Εκπρόσωπος, που θα πρέπει να επιστρέψει επιλογές φόρτωσης εγγράφου. Μπορεί να είναι NULL και μπορεί να επιστρέψει null - σε αυτήν την περίπτωση ο τύπος εγγράφου θα εντοπιστεί αυτόματα και θα εφαρμοστούν οι προεπιλεγμένες επιλογές φόρτωσης για αυτόν τον τύπο. |

### Παρατηρήσεις

**Μάθε περισσότερα**

* Περισσότερα σχετικά με τους τύπους αρχείων που υποστηρίζονται από το GroupDocs.Editor: [Μορφές εγγράφων που υποστηρίζονται από το GroupDocs.Editor](https://docs.groupdocs.com/display/editornet/Supported+Document+Formats)
* Περισσότερα για το GroupDocs.Editor για λειτουργίες .NET: [Οδηγός προγραμματιστή](https://docs.groupdocs.com/display/editornet/Developer+Guide)
* Περισσότερα σχετικά με τον τρόπο ανοίγματος και επεξεργασίας εγγράφων και εγγράφων που προστατεύονται με κωδικό πρόσβασης από διαφορετικούς χώρους αποθήκευσης: [Φορτώστε και επεξεργαστείτε έγγραφα χρησιμοποιώντας το GroupDocs.Editor](https://docs.groupdocs.com/display/editornet/Load+document)

### Δείτε επίσης

* interface [ILoadOptions](../../../groupdocs.editor.options/iloadoptions)
* class [Editor](../../editor)
* χώρος ονομάτων [GroupDocs.Editor](../../editor)
* συνέλευση [GroupDocs.Editor](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
