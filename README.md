# Η συμβολή της Τεχνητής Νοημοσύνης (Generative AI) στην Κυβερνοασφάλεια
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

---
---

# The Contribution of Artificial Intelligence (Generative AI) to Cybersecurity
**Group**: Trovia Dimitra (3200203), Fatsea Anthippi (3190209)

---

## Introduction
Cybersecurity is a critical issue in the digital age, as threats in cyberspace grow increasingly complex. Generative AI, a subset of AI, offers new capabilities to enhance defensive mechanisms through:
-Process automation
-Attack simulation
-Vulnerability detection

However, its use raises ethical concerns and risks, as it can be exploited by malicious actors.

## Key Points

### 1. Generative AI as a Defense Tool
- **Process Automation**: 
  - Optimizes time-consuming tasks (e.g., log file analysis, threat hunting).
- **Example**: 
  - IBM Security Guardium for cloud data protection.
- **Attack Simulation**:
  - Generates realistic scenarios (e.g., phishing emails) to train systems.
  - Techniques like CrowdCanary for phishing website detection.
- **Vulnerability Detection**:
  - Application of SAST (Static Application Security Testing) and SMT-based models.

### 2. Challenges & Risks
- **Malicious Use**:
  - Creation of polymorphic malware (e.g., ransomware) and automated hacking.
  - Enhanced phishing attacks via NLG (Natural Language Generation).
- **Ethical Issues**:
  - **Deepfakes**: Identity forgery for social engineering (e.g., a $25M scam using deepfake video calls).
  - **Data Leaks**: Risks from training LLMs (Large Language Models) on poisoned datasets.
  - **Jailbreaking**: Bypassing AI model restrictions (e.g., DAN, SWITCH methods).

### 3. Practical Applications
- **Experiments with ChatGPT 3.5 & Gemini**:
  - **Jailbreaking**: Revealing social engineering details via roleplay techniques.
  - **Phishing Email Generation**: ChatGPT produced examples, while Gemini refused malicious code.
  - **Findings**: Models recognize ethical boundaries but remain vulnerable to targeted prompts without "trigger words."

### 4. Solutions & Future Prospects
-Ethical Design:
  -Transparency, legal data collection, and privacy protection.
- **Regular Retraining**:
  -To address emerging threats and maintain accuracy.
- **Defensive Applications**:
  -Anomaly detection, threat prioritization, and automated data analysis.
- **Defense vs. Offense**:
  -70% of CISOs believe Generative AI is more useful for attacks, but its defensive use is rising.

---

## Conclusions
Generative AI is a double-edged sword in cybersecurity:
- ✅ Benefits: Enhanced threat detection, automation.
- ❌ Risks: Evolution of malicious techniques (e.g., deepfakes, automated hacking).

Its future impact depends on:
1. Ethical alignment in model development.
2. Data protection and continuous updates against emerging threats.
3. Cross-disciplinary collaboration to address security gaps.
   
---

## References
Includes 18 sources, such as:
- [Research studies (arXiv)](https://arxiv.org/)
- [Industry reports (IBM, Palo Alto Networks)](https://www.ibm.com/)
- [Case studies (CNN, Check Point)](https://edition.cnn.com/)

*For the full paper, refer to the original work: [P3200203_P3190209.pdf].*
