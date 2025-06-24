# email_phishing
A sample of an email phishing showing the techniques of how one can be able to identify phishing in emails.

# Task 2 – Phishing Email Analysis

This repository contains my analysis for Task 2 of the Elevate Labs Cybersecurity Internship. The goal of this task was to identify common indicators of phishing in a suspicious email and document the findings clearly.

---

## Task Overview

*Objective:*  
Analyze a phishing email sample and identify traits commonly used in phishing attacks such as spoofed senders, malicious links, and psychological manipulation (e.g. urgency, fear, or threats).

*Tools Used:*
- Manual inspection via text editor (Kali Linux)
- Online header analysis tools (MXToolbox, VirusTotal)
- Custom-written report (phishing_test.txt)

---

## Findings Summary

The phishing email was carefully reviewed and the following indicators were identified:

1. *Spoofed Domain Name:*
   - The sender domain paypa1.com is a clear imitation of paypal.com.
   - This is a classic example of typo-squatting (letter “l” replaced with number “1”).

2. *Unprofessional Urgency and Threats:*
   - The message demands immediate action and threatens account closure.
   - Phishers use this technique to pressure users into clicking harmful links.

3. *Insecure Link (HTTP):*
   - The link uses http:// instead of the secure https://.
   - This is another major red flag, especially from a financial entity like PayPal.

These findings have been documented in detail in the phishing_test.txt file.

---

##  Files Included

- phishing_test.txt – Simulated phishing email used for analysis and full analysis report detailing phishing indicators.

---

## Submission

This repository serves as my submission for Task 2. All files used and created during the analysis are included for review.

*GeoffreyMuriuki Mwangi*  
Cybersecurity Intern @ Elevate Labs
