# SC-200 Anki Flashcards

<p align="center">
  <img src="banner.png" alt="SC-200 Anki Flashcards Banner" height="420">
</p>




Flashcards to help prepare for the **Microsoft SC-200: Security Operations Analyst** exam.  
All cards are provided in **TSV format** (easy to import into Anki).  

---
---

## 📝 Sample Cards

| Front | Back |
|-------|------|
| In Microsoft Sentinel, which KQL operator is used to filter rows based on a condition? | `where` |
| Which Microsoft 365 Defender product is designed to protect endpoint devices? | Microsoft Defender for Endpoint |
| What is the default log retention period in Microsoft Sentinel? | 90 days (configurable) |
| In Defender for Cloud, which feature provides secure score recommendations? | Secure Score |
| During incident response, what step comes immediately after detection? | Containment |

---

## 📥 Download Decks

You can download the TSV files directly from GitHub and import them into Anki.

### Sections
- [Sentinel](https://raw.githubusercontent.com/juansasoc/Microsoft-SC-200-Anki-Flashcards/main/sections/sentinel.tsv)
- [M365 Defender](https://raw.githubusercontent.com/juansasoc/Microsoft-SC-200-Anki-Flashcards/main/sections/m365_defender.tsv)
- [Defender for Cloud](https://raw.githubusercontent.com/juansasoc/Microsoft-SC-200-Anki-Flashcards/main/sections/defender_cloud.tsv)
- [KQL](https://raw.githubusercontent.com/juansasoc/Microsoft-SC-200-Anki-Flashcards/main/sections/kql.tsv)
- [SOC & Incident Response](https://raw.githubusercontent.com/juansasoc/Microsoft-SC-200-Anki-Flashcards/main/sections/soc_ir.tsv)

### Exam Packs
- [Exam 1](https://raw.githubusercontent.com/juansasoc/Microsoft-SC-200-Anki-Flashcards/main/exams/exam1.tsv)
- [Exam 2](https://raw.githubusercontent.com/juansasoc/Microsoft-SC-200-Anki-Flashcards/main/exams/exam2.tsv)
- [Exam 3](https://raw.githubusercontent.com/juansasoc/Microsoft-SC-200-Anki-Flashcards/main/exams/exam3.tsv)
- [Combined Pack](https://raw.githubusercontent.com/juansasoc/Microsoft-SC-200-Anki-Flashcards/main/exams/combined_pack.tsv)

---
# 📘 Microsoft SC-200 Anki Flashcards

Flashcards for the **Microsoft SC-200: Security Operations Analyst** exam, designed in **scenario style** to mimic real exam case studies.  

---

## 📂 Flashcard Sets (Direct Download Links)

| Set | File | Topics |
|-----|------|--------|
| **Set 1** | [Download TSV](SC-200_Scenario_Cards_Set1.tsv) | Sentinel incidents, automation, KQL basics (extend, join, outliers), watchlists, Secure Score, threat intel |
| **Set 2** | [Download TSV](SC-200_Scenario_Cards_Set2.tsv) | Incident response (isolation, blocking, live response), UEBA/Fusion ML, advanced automation, threat hunting (Kerberos, RDP, persistence, exfiltration) |



---

## 🛠 Import Instructions

1. Download one of the `.tsv` sets above.  
2. Open Anki → **File → Import** → select the `.tsv`.  
3. Map fields as: **Front**, **Back**, **Tags**.  
4. Import into your SC-200 deck.

---


---

## 📂 Details of Each Set

### Set 1 – Core Sentinel & KQL Scenarios
- **File:** [`SC-200_Scenario_Cards_Set1.tsv`](tsv/SC-200_Scenario_Cards_Set1.tsv)
- **Topics Covered:**
  - Sentinel incidents, automation rules, data connectors
  - KQL query patterns (extend, joins, outliers)
  - Watchlists, Secure Score, Defender integrations
  - Threat Intel and basic hunting techniques

### Set 2 – Incident Response, UEBA, & Advanced Hunting
- **File:** [`SC-200_Scenario_Cards_Set2.tsv`](tsv/SC-200_Scenario_Cards_Set2.tsv)
- **Topics Covered:**
  - Incident response workflows (isolation, blocking, live response)
  - UEBA, Fusion ML correlation rules
  - Advanced automation with playbooks and external integrations
  - Threat hunting for Kerberos, RDP, persistence, and exfiltration
  - Defender for Endpoint, Defender for Cloud Apps, and Cloud integrations

---

## ✅ Study Recommendations

- Use these cards as **memory anchors**.  
- Pair with:
  - Microsoft Learn SC-200 modules (review twice).    
  - Hands-on Sentinel & Defender labs for applied skills.  

These decks ensure both **fact recall** and **scenario-based reasoning**, closely matching the SC-200 exam format.
## 📖 How to Import into Anki
1. Download the `.tsv` file you want.  
2. In Anki: **File → Import**.  
3. Select the file.  
4. Choose **Tab-separated**, with **Field 1 = Front** and **Field 2 = Back**.  
5. Import → start studying 🚀  

---

## 🔗 Helpful Links
- [Official SC-200 Exam Page](https://learn.microsoft.com/en-us/certifications/exams/sc-200/)  
- [Microsoft Learn SC-200 Study Guide](https://learn.microsoft.com/en-us/training/courses/sc-200t00)  
- [Anki (Download)](https://apps.ankiweb.net/)  
- [Anki Manual](https://docs.ankiweb.net/)  

---

## 🛠 About
This repo contains study flashcards organized into **sections** and **exam-style packs** to match the SC-200 exam structure.  
Contributions and corrections are welcome!  

---

<!--  
## 🚀 Next Steps (Future)
Once `.apkg` exports are ready, we’ll also publish them as GitHub Releases.

1. Export decks from Anki as `.apkg`.  
2. Go to **Releases → Draft a new release**.  
3. Tag a version (e.g., `v1.0.0`) and upload the `.apkg` file(s).  
4. Users can then download and import in one click.  

[![Download Latest Deck](https://img.shields.io/github/v/release/juansasoc/Microsoft-SC-200-Anki-Flashcards?display_name=tag&sort=semver)](https://github.com/juansasoc/Microsoft-SC-200-Anki-Flashcards/releases/latest)
-->

