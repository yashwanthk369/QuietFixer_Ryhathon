# RYHATHON-QUIETFIXER-2026

**Project Overview**

> Quiet Fixer is a browser extension for Chrome and Firefox. It repairs inaccessible Indian government, bank and college websites live, inside the user’s own browser. It adds missing labels to form fields, names icon-only buttons, fixes heading order, releases pop-ups that trap the keyboard, and gives a keyboard path to the Submit button. The user’s own screen reader (NVDA or TalkBack) reads the repaired page, so the user does not need to learn a new tool. The core works offline, uses no AI, and sends no data anywhere. Because the site owner will not change anything before the deadline, the fix lives on the user’s side.

---

## 👥 TEAM DETAILS

This project was designed and developed by team **Ctrl C Ctrl V** under **Ryhathon 2026 - Francis Xavier Engineering College (FXEC)**.
Feel free to connect with us and explore our work!

**👤KALPANAA BABU T M**

[![Email](https://img.shields.io/badge/Email-kalpanakyashwanthk@gmail.com-red?style=flat&logo=gmail)](mailto:kalpanakyashwanthk@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Ankita%20Patil-blue?style=flat&logo=linkedin)](https://www.linkedin.com/in/ankita-patil-10b0732ab/)

---

**👤 YASHWANTH K**  

[![Email](https://img.shields.io/badge/Email-kalpanaamurali2006@gmail.com-red?style=flat&logo=gmail)](mailto:m.kalpanaamurali2006@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Mithilesh%20Kolhapurkar-blue?style=flat&logo=linkedin)](https://www.linkedin.com/in/mithilesh-kolhapurkar-258001214)

---

**👤SOJAN S**

[![Email](https://img.shields.io/badge/Email-kalpanakyashwanthk@gmail.com-red?style=flat&logo=gmail)](mailto:kalpanakyashwanthk@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Ankita%20Patil-blue?style=flat&logo=linkedin)](https://www.linkedin.com/in/ankita-patil-10b0732ab/)

---

**👤ANAND K**

[![Email](https://img.shields.io/badge/Email-kalpanakyashwanthk@gmail.com-red?style=flat&logo=gmail)](mailto:kalpanakyashwanthk@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Ankita%20Patil-blue?style=flat&logo=linkedin)](https://www.linkedin.com/in/ankita-patil-10b0732ab/)

---

**👤SURYA PRAKAH PN**

[![Email](https://img.shields.io/badge/Email-kalpanakyashwanthk@gmail.com-red?style=flat&logo=gmail)](mailto:kalpanakyashwanthk@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Ankita%20Patil-blue?style=flat&logo=linkedin)](https://www.linkedin.com/in/ankita-patil-10b0732ab/)

---

**👤AANANDHA KANNAN S**

[![Email](https://img.shields.io/badge/Email-kalpanakyashwanthk@gmail.com-red?style=flat&logo=gmail)](mailto:kalpanakyashwanthk@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Ankita%20Patil-blue?style=flat&logo=linkedin)](https://www.linkedin.com/in/ankita-patil-10b0732ab/)

---

## 📋 Table of Contents

1. [Problem Statement](#Problem-Statement)
   
3. [Problem Understanding & Approach](#Problem-Understanding-&-Approach)
   
5. [V1: CloudOps AI Copilot MVP](#v1-cloudops-ai-copilot-mvp)
   
7. [V2: UACI Multi-Project Platform](#v2-uaci-multi-project-platform)
   
9. [Quick Start](#quick-start)
    
11. [Deployment](#deployment)
    
13. [API Reference](#api-reference)
    
15. [Security & Compliance](#security--compliance)

---

## Problem Statement

### Problem ID & Domain : WEB-09 & Web Development

### Problem Title
**Inaccessible Government, Bank and College Websites for Screen Reader Users**

### Problem Description
Scholarships, bank forms, exam registration and certificates are now often available only online. Many Indian government, bank and college websites ignore accessibility guidelines: form fields have no labels, buttons are bare icons, headings jump around, captchas have no alternative, pop-ups trap keyboard focus, and upload boxes need a mouse. A blind student can fill half a scholarship form and then be unable to find the submit button. This project builds a browser extension that repairs such pages live inside the user’s own browser, works with the user’s own screen reader, works offline for its core features, and speaks the user’s language, so the user can finish the task before the deadline without waiting for the site owner.

### Target Users
Blind, low-vision and keyboard-only people, including rural users who do not read English. Often no other person is available to help them.

### Existing Gaps
* **Site owners do not fix in time:** Reports take months or are never answered, even though GIGW 3.0 and RBI guidelines require accessible sites.
* **Overlay tools often fail blind users:** n a study of blind and low-vision users, 16 rated overlays “not at all effective” and only 3 “very effective”. Their own screen reader modes clash with the user’s real one.
* **Privacy risk:** Tools that send page content to the cloud are unsafe for Aadhaar, OTP and bank data.
* **Language barrier:** Most fixes are English-only, and rural users need Tamil, Hindi and other languages.
* **Documents and captchas:** Upload boxes and captchas are among the hardest steps, and the user usually cannot ask anyone for help.
* **Wrong guesses are dangerous:** A guessed button name can lead to a wrong action such as paying or deleting.

  <img width="1376" height="768" alt="image_56abd2ef (1)" src="https://github.com/user-attachments/assets/9ad8e340-7a08-41ad-a504-3d42c7191088" />

                                             **Figure 1.1 Blind person struggle to fill the form**

---

## Problem Understanding & Approach

**Root Cause Analysis**
Websites are built to look good, but they often skip the hidden information that a screen reader needs, like labels and button names. Site owners rarely fix this before the user’s deadline. Ready-made fixing tools often clash with the user’s own screen reader. Cloud-based fixes are unsafe for private data like Aadhaar and bank details, and they fail without internet. Also, many users have no one nearby to help them.

**Solution Strategy**
We fix the page on the user’s own device with a browser extension. It finds the clues already on the page, like nearby text and field names, and adds the missing labels. The user’s own screen reader then reads the repaired page. The core works offline, uses no AI, and sends no data anywhere.

Every guess shows a confidence percentage, risky buttons like Submit always ask first, and every change can be undone. The app supports English, Hindi and Tamil. A Document Vault saves documents safely on the device for easy upload. AI is optional, off by default, and blocked on bank sites.

---

## 3. Proposed Solution

### Solution Overview
A browser extension for Chrome and Firefox that repairs inaccessible websites live, on the user's own device, so blind and keyboard-only users can finish online forms on their own.

**Key Features**
* **Offline Core:** All page repairs run on the user's device with simple rules. No AI is needed and no data leaves the device.
* **Automatic Page Repair:** Adds missing labels to form fields, names icon-only buttons, fixes heading order and releases pop-ups that trap the keyboard.
* **Works With the User's Screen Reader:** Messages go to NVDA or TalkBack, so there is no new tool to learn.
* **Honest Guessing:** Every guess is announced with a confidence percentage. Unknown buttons are never clicked.
* **Safe Actions:** Submit, Pay and Delete always ask for a second confirmation, and every change can be undone.
* **Review Before Submit:** The whole form is read back. Aadhaar, OTP, password and account fields are hidden for safety.
* **Secure Document Vault:** Documents are saved once, encrypted on the device, and attached to upload fields by a short name like "aadhaar".
* **Multilingual Support:** English, Hindi and Tamil, with the correct language tag set so the right voice is used.
* **Optional Browser Voice:** For people with no screen reader. Off by default.
* **Optional AI Add-on:** Off by default, and blocked on bank sites and sensitive fields.

---

