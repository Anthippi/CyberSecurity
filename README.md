# Η συμβολή της Τεχνητής Νοημοσύνης (Generative AI) στην Κυβερνοασφάλεια [![Static Badge](https://img.shields.io/badge/English-orange)](README.en.md)



**Ομάδα**: Τροβία Δήμητρα (3200203), Φατσέα Ανθίππη (3190209)  

---

## Εισαγωγή  
Η κυβερνοασφάλεια αποτελεί κρίσιμο ζήτημα στην ψηφιακή εποχή, καθώς οι απειλές στον κυβερνοχώρο γίνονται ολοένα πιο πολύπλοκες. Η Generative AI, ως υποκατηγορία της ΤΝ, προσφέρει νέες δυνατότητες για την ενίσχυση αμυντικών μηχανισμών μέσω:  
- Αυτοματοποίησης διαδικασιών  
- Προσομοίωσης επιθέσεων  
- Ανίχνευσης ευπαθειών  

Ωστόσο, η χρήση της εγείρει **ηθικά ζητήματα** και κινδύνους, καθώς μπορεί να εκμεταλλευτεί από κακόβουλους φορείς.  

---

## Κύρια Σημεία  

### 1. Generative AI ως Εργαλείο Άμυνας  
- **Αυτοματοποίηση Διαδικασιών**:  
  - Βελτιστοποιεί χρονοβόρες εργασίες (π.χ. ανάλυση αρχείων καταγραφής, αναζήτηση απειλών).  
  - Παράδειγμα: Χρήση του *IBM Security Guardium* για προστασία δεδομένων σε cloud περιβάλλοντα.  
- **Προσομοίωση Επιθέσεων**:  
  - Δημιουργία ρεαλιστικών σεναρίων (π.χ. phishing emails) για εκπαίδευση συστημάτων.  
  - Τεχνικές όπως η *CrowdCanary* για ανίχνευση phishing ιστοτόπων.  
- **Εντοπισμός Ευπαθειών**:  
  - Εφαρμογή μεθόδων SAST (Static Application Security Testing) και SMT-based μοντέλων.  

### 2. Προκλήσεις & Κίνδυνοι  
- **Κακόβουλη Χρήση**:  
  - Δημιουργία πολυμορφικού malware (π.χ. ransomware) και αυτοματοποιημένου hacking.  
  - Βελτιωμένες επιθέσεις phishing μέσω NLG (Natural Language Generation).  
- **Ηθικά Ζητήματα**:  
  - **Deepfakes**: Πλαστογράφηση ταυτότητας για κοινωνική μηχανική (π.χ. απάτη \$25 εκατ. με deepfake βίντεοκλήση).  
  - **Διαρροές Δεδομένων**: Κίνδυνοι από εκπαίδευση LLMs (Large Language Models) σε δηλητηριασμένα δεδομένα.  
  - **Jailbreaking**: Παράκαμψη περιορισμών μοντέλων AI (π.χ. μεθόδους DAN, SWITCH).  

### 3. Πρακτική Εφαρμογή  
- **Πειράματα με ChatGPT 3.5 & Gemini**:  
  - **Jailbreaking**: Αποκάλυψη λεπτομερειών για social engineering μέσω τεχνικών roleplay.  
  - **Δημιουργία Phishing Emails**: Το ChatGPT παρήγαγε παραδείγματα, ενώ το Gemini αρνήθηκε κακόβουλο κώδικα.  
  - **Συμπεράσματα**: Τα μοντέλα αναγνωρίζουν ηθικά όρια, αλλά παραμένουν ευάλωτα σε στοχευμένες ερωτήσεις χωρίς "λέξεις-κλειδιά".  

### 4. Λύσεις & Μελλοντικές Προοπτικές  
- **Ηθικός Σχεδιασμός**:  
  - Διαφάνεια, συλλογή νόμιμων δεδομένων, προστασία απορρήτου.  
- **Τακτική Επανεκπαίδευση**:  
  - Για αντιμετώπιση νέων απειλών και διατήρηση ακρίβειας.  
- **Εφαρμογές Άμυνας**:  
  - Ανίχνευση ανωμαλιών, ιεράρχηση απειλών, αυτοματοποιημένη ανάλυση δεδομένων.  
- **Σύγκρουση Άμυνας-Επίθεσης**:  
  - 70% των CISOs πιστεύουν ότι η Generative AI είναι πιο χρήσιμη για **επίθεση**, αλλά η χρήση της ως εργαλείου άμυνας αυξάνεται.  

---

## Συμπεράσματα  
Η Generative AI αποτελεί **δίκοπο μαχαίρι** στην κυβερνοασφάλεια.  
- ✅ **Οφέλη**: Ενίσχυση ανίχνευσης απειλών, αυτοματοποίηση.  
- ❌ **Κίνδυνοι**: Εξέλιξη κακόβουλων τεχνικών (π.χ. deepfakes, αυτοματοποιημένο hacking).  

Η μελλοντική της επίδραση εξαρτάται από:  
1. Την ηθική ευθυγράμμιση στη δημιουργία μοντέλων.  
2. Την προστασία δεδομένων και τη συνεχή ενημέρωση κατά emerging threats.  
3. Την πολυεπιστημονική συνεργασία για κάλυψη κενών ασφαλείας.  

---

## Βιβλιογραφία  
Περιλαμβάνει 18 πηγές, όπως:  
- [Ερευνητικές μελέτες (arXiv)](https://arxiv.org/)  
- [Βιομηχανικές αναφορές (IBM, Palo Alto Networks)](https://www.ibm.com/)  
- [Πρακτικές περιπτώσεις (CNN, Check Point)](https://edition.cnn.com/)  

*Για πλήρη ανάγνωση, ανατρέξτε στην αρχική εργασία: [P3200203_P3190209.pdf].*  
