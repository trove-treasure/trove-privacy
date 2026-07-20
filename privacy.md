# Politika e Privatësisë - Trove

**Data e fundit e përditësimit:** 17 Korrik 2026

**Versioni zyrtar i hostuar (Play Store):** https://github.com/trove-treasure/trove-privacy/blob/main/privacy.md


## 1. Hyrje

Mirë se vini në Trove ("ne", "nesh", "tonë"). Privatësia juaj është
prioriteti ynë. Kjo Politikë e Privatësisë shpjegon si mblidhen,
përdoren dhe mbrohen të dhënat tuaja kur përdorni aplikacionin tonë.

## 2. Të dhënat që mbledhim

### 2.1 Të dhëna që ruhen LOKALISHT në pajisjen tuaj

Trove është aplikacion **offline-first**. Të gjitha të dhënat tuaja
personale ruhen vetëm në pajisjen tuaj (bazë e dhënash lokale SQLite) dhe
nuk transmetohen në serverët tanë:

- Receta dhe ilaçe shtëpiake
- Shënime personale
- Të dhëna shëndetësore familjare
- Shpenzime dhe buxhete
- Anëtarë të familjes
- Borxhe dhe pagesa
- Detyra kujdesi
- Cikli menstrual dhe regjistrime ditore
- Medikamente dhe rikujtues
- Imazhe që ngarkoni

### 2.2 Të dhëna anonime për analytics (Firebase Analytics & Crashlytics)

Mbledhim të dhëna **anonime** dhe **agregate** për të kuptuar si
përdoret aplikacioni:

- Versioni i aplikacionit dhe sistemi operativ
- Modeli i pajisjes (jo numri serik)
- Vendi (jo qyteti specifik)
- Sa kohë kaloni në aplikacion
- Cilat funksione përdorni më shumë (pa përmbajtje)
- Crashe dhe gabime teknike (Firebase Crashlytics)

**Nuk mbledhim:**

- Emrin tuaj
- Email-in
- Numrin e telefonit
- Përmbajtjen e shënimeve, recetave, apo të dhënave shëndetësore
- Imazhet që ngarkoni

Mund ta **çaktivizoni Analytics në çdo moment** nga *Cilësime* → çelësi
"Ndihmo me statistika anonime" në fund të faqes.

### 2.3 Backup në Google Drive (opsional)

Nëse aktivizoni manualisht lidhjen me Google Drive nga *Cilësime*:

- Përdorim Google Sign-In për t'ju autentikuar
- Backup-i (file `.tbak`, **i kriptuar lokalisht me AES-256** para se të
  ngarkohet) ruhet në një folder të quajtur **"Trove Backups"** brenda
  Google Drive-it TUAJ personal — jo në serverët tanë
- Ky folder është i dukshëm dhe i aksesueshëm nga ju direkt në Google
  Drive; mund ta shihni, shkarkoni apo fshini file-in në çdo moment,
  qoftë nga aplikacioni Trove, qoftë direkt nga Google Drive
- Ne **NUK** kemi qasje në të dhënat tuaja të Google Drive
- Mund të shkëputni lidhjen me Google (sign out) në çdo moment nga
  aplikacioni

## 3. Si i përdorim të dhënat

Të dhënat anonime të analytics përdoren për:

- Përmirësimin e aplikacionit
- Identifikimin dhe rregullimin e bug-eve
- Kuptimin e funksioneve më të dobishme
- Vendimet për zhvillim të mëtejshëm

**Nuk i shesim, nuk i ndajmë dhe nuk i transferojmë të dhënat tuaja
te palë të treta për qëllime marketingu.**

## 4. Të dhënat shëndetësore

Trove përmban funksione për menaxhimin e shëndetit familjar (rekorde
mjekësore, medikamente, cikli menstrual). Të gjitha këto të dhëna:

- **Ruhen vetëm në pajisjen tuaj**
- **Nuk transmetohen kurrë** në internet (përveç nëse aktivizoni
  manualisht backup në Google Drive tuaj, siç përshkruhet te 2.3)
- Mund të mbrohen me PIN dhe/ose biometrikë (gjurmë gishti / fytyrë)
  përmes opsioneve të sigurisë (*Cilësime → Siguria*)
- Mund të fshihen duke çinstaluar aplikacionin, ose duke pastruar
  ruajtjen (storage) e tij nga Cilësimet e sistemit Android

**Trove nuk është substitut për këshillim mjekësor profesional.**

## 5. Siguria

Marrim masa për të mbrojtur të dhënat tuaja:

- **PIN lock** dhe **autentikim biometrik** (gjurmë gishti / Face ID)
  për module të ndjeshme — kyçja/hyrja verifikohet plotësisht nga
  sistemi operativ i pajisjes tuaj (Android BiometricPrompt); Trove
  **nuk ruan dhe nuk sheh kurrë** të dhënat tuaja biometrike — ne
  marrim vetëm rezultatin "sukses/dështim" nga sistemi operativ
- Kriptim **AES-256** për backup-et lokale/Google Drive (kur aktivizohet)
- Nuk dërgohen kredenciale në serverë të jashtëm

## 6. In-App Purchases (Trove Premium)

Funksionet me pagesë (Trove Premium) **nuk janë ende aktive** në këtë
version të aplikacionit (është ende në fazë testimi/pre-lançimi). Kur
të aktivizohen, çdo transaksion do të menaxhohet plotësisht nga
**Google Play Billing**. Ne nuk do të ruajmë kurrë:

- Numrat e kartës suaj
- Detajet e pagesës
- Adresën e faturimit

Do të mbajmë vetëm një token të thjeshtë verifikimi lokal për të
konfirmuar statusin tuaj premium.

## 7. Të drejtat tuaja (GDPR)

Si përdorues kudo qofshi, ju keni të drejtë të:

- **Aksesoni** të gjitha të dhënat tuaja — janë në pajisjen tuaj dhe të
  dukshme direkt në aplikacion
- **Korrigjoni** çdo informacion në çdo kohë nga vetë aplikacioni
- **Çaktivizoni Analytics** (*Cilësime* → "Ndihmo me statistika anonime")
- **Fshini** të dhënat tuaja duke çinstaluar aplikacionin ose duke
  pastruar ruajtjen (storage) e tij nga Cilësimet e sistemit Android —
  kjo fshin përgjithmonë bazën e të dhënave lokale
  *(një buton "Fshi të gjitha të dhënat" brenda vetë aplikacionit, si
  dhe eksporti/importi i të dhënave, janë funksione të planifikuara
  por ende jo të disponueshme në këtë version)*

## 8. Fëmijët

Trove nuk është dizajnuar për përdorues nën moshën 13 vjeç. Nuk
mbledhim me dije të dhëna nga fëmijë nën këtë moshë.

## 9. Ndryshime në këtë politikë

Mund të përditësojmë këtë politikë nga koha në kohë. Ndryshimet do
të publikohen në aplikacion dhe data e fundit e përditësimit do të
ndryshohet.

## 10. Kontakti

Për pyetje rreth privatësisë, na kontaktoni në:

**Email:** trove.treasure.app@gmail.com
**Aplikacioni:** Trove
**Zhvilluesi:** Trove Team

---

# Privacy Policy - Trove (English)

**Last Updated:** July 17, 2026

**Official hosted version (Play Store):** https://github.com/trove-treasure/trove-privacy/blob/main/privacy.md

## 1. Introduction

Welcome to Trove. This Privacy Policy explains how we collect, use,
and protect your data when you use our application.

## 2. Data We Collect

### 2.1 Data Stored LOCALLY on Your Device

Trove is an **offline-first** application. All your personal data is
stored only on your device (local SQLite database) and never
transmitted to our servers:

- Recipes and home remedies
- Personal notes
- Family health records
- Expenses and budgets
- Family members
- Debts and payments
- Care tasks
- Menstrual cycle and daily logs
- Medications and reminders
- Images you upload

### 2.2 Anonymous Analytics Data (Firebase Analytics & Crashlytics)

We collect **anonymous** and **aggregate** data to understand app usage:

- App version and operating system
- Device model (not serial number)
- Country (not specific city)
- Time spent in the app
- Most used features (without content)
- Crashes and technical errors (Firebase Crashlytics)

**We do NOT collect:**

- Your name
- Email
- Phone number
- Content of notes, recipes, or health data
- Images you upload

You can **disable Analytics at any time** from *Settings* → the
"Help with anonymous statistics" switch at the bottom of the page.

### 2.3 Google Drive Backup (Optional)

If you manually connect Google Drive from *Settings*:

- We use Google Sign-In to authenticate you
- The backup (a `.tbak` file, **encrypted locally with AES-256** before
  upload) is stored in a folder named **"Trove Backups"** inside YOUR
  own personal Google Drive — not on our servers
- This folder is visible and accessible to you directly in Google
  Drive; you can view, download, or delete the file at any time,
  either from the Trove app or directly from Google Drive
- We do **NOT** have access to your Google Drive data
- You can disconnect Google (sign out) at any time from the app

## 3. How We Use Data

Anonymous analytics data is used for:

- Improving the application
- Identifying and fixing bugs
- Understanding most useful features
- Future development decisions

**We do not sell, share, or transfer your data to third parties for
marketing purposes.**

## 4. Health Data

Trove contains features for managing family health (medical records,
medications, menstrual cycle). All such data:

- **Is stored only on your device**
- **Is never transmitted** over the internet (unless you manually
  enable backup to your own Google Drive, as described in 2.3)
- Can be protected with a PIN and/or biometrics (fingerprint / face)
  through security options (*Settings → Security*)
- Can be deleted by uninstalling the app, or by clearing its storage
  from Android system Settings

**Trove is not a substitute for professional medical advice.**

## 5. Security

We take measures to protect your data:

- **PIN lock** and **biometric authentication** (fingerprint / Face ID)
  for sensitive modules — unlocking is verified entirely by your
  device's own operating system (Android BiometricPrompt); Trove
  **never stores or sees** your biometric data — we only receive a
  "success/failure" result from the OS
- **AES-256** encryption for local/Google Drive backups (when enabled)
- No credentials are sent to external servers

## 6. In-App Purchases (Trove Premium)

Paid features (Trove Premium) are **not yet active** in this version of
the app (still in testing/pre-launch). Once enabled, every transaction
will be fully managed by **Google Play Billing**. We will never store:

- Your card numbers
- Payment details
- Billing address

We will only keep a simple local verification token to confirm your
premium status.

## 7. Your Rights (GDPR)

As a user regardless of location, you have the right to:

- **Access** all your data — it lives on your device and is directly
  visible in the app
- **Correct** any information at any time from within the app
- **Disable Analytics** (*Settings* → "Help with anonymous statistics")
- **Delete** your data by uninstalling the app, or by clearing its
  storage from Android system Settings — this permanently deletes the
  local database
  *(an in-app "Delete all data" button, as well as data export/import,
  are planned features not yet available in this version)*

## 8. Children

Trove is not designed for users under the age of 13. We do not
knowingly collect data from children under this age.

## 9. Changes to This Policy

We may update this policy from time to time. Changes will be
published in the app and the last updated date will be modified.

## 10. Contact

For privacy questions, contact us at:

**Email:** trove.treasure.app@gmail.com
**Application:** Trove
**Developer:** Trove Team
