---
title: Password
second_title: GroupDocs.Editor για Αναφορά API .NET
description: Επιτρέπει τον καθορισμό την τροποποίηση και τη λήψη του κωδικού πρόσβασης ο οποίος θα χρησιμοποιηθεί για το άνοιγμα του εγγράφου παρουσίασης εάν είναι κωδικοποιημένο. Ορίστε σε NULL ή κενή συμβολοσειρά για να αφαιρέσετε τον κωδικό πρόσβασης.
type: docs
weight: 20
url: /el/net/groupdocs.editor.options/presentationloadoptions/password/
---
## PresentationLoadOptions.Password property

Επιτρέπει τον καθορισμό, την τροποποίηση και τη λήψη του κωδικού πρόσβασης, ο οποίος θα χρησιμοποιηθεί για το άνοιγμα του εγγράφου παρουσίασης, εάν είναι κωδικοποιημένο. Ορίστε σε NULL ή κενή συμβολοσειρά για να αφαιρέσετε τον κωδικό πρόσβασης.

```csharp
public string Password { get; set; }
```

### Παρατηρήσεις

Από προεπιλογή, αυτή η ιδιότητα έχει τιμή NULL — δεν έχει οριστεί κωδικός πρόσβασης. Εάν το έγγραφο Παρουσίασης εισαγωγής προστατεύεται με κωδικό πρόσβασης, ο κωδικός πρόσβασης είναι υποχρεωτικός και θα υπάρξει εξαίρεση εάν ο κωδικός πρόσβασης δεν έχει καθοριστεί ή δεν είναι έγκυρος. Εάν το έγγραφο παρουσίασης εισόδου ΔΕΝ προστατεύεται με κωδικό πρόσβασης, αλλά έχει οριστεί κωδικός πρόσβασης, θα αγνοηθεί.

### Δείτε επίσης

* class [PresentationLoadOptions](../../presentationloadoptions)
* χώρος ονομάτων [GroupDocs.Editor.Options](../../presentationloadoptions)
* συνέλευση [GroupDocs.Editor](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
