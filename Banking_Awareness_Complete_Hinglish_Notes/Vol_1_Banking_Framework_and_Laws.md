# 📘 Volume 1: Banking Framework, Laws & Regulations
> **Syllabus Coverage (from 193-Page Master PDF):**
> - **Module 01:** Basel Norms (Basel I, II & III) — *[Pages 1–6]*
> - **Module 02:** Negotiable Instruments Act, 1881 — *[Pages 7–15]*
> - **Module 03:** SARFAESI Act, 2002 — *[Pages 16–20]*
> - **Module 04:** Priority Sector Lending (PSL) & MSME Norms — *[Pages 21–27]*
> - **Module 05:** Banking Regulation Act, 1949 — *[Pages 46–49]*

---

## 🏛️ Module 01: Basel Norms (Basel I, II & III)

### 1. Bank Kaise Kaam Karta Hai? (Balance Sheet & Risk Basics)
Bank ek **Financial Intermediary** (bicholiya) hota hai jo do parties ke beech kaam karta hai:
1. **Savers / Depositors:** Jinke paas surplus paisa hai, bank unse deposit leta hai aur unhe interest deta hai (e.g., 4% - 7%).
2. **Borrowers:** Jinko paise ki zaroorat hai (business, home, education, vehicle), bank unhe loan deta hai aur unse higher interest charge karta hai (e.g., 9% - 12%).

$$\text{Net Interest Margin (NIM)} = \text{Interest Earned on Loans} - \text{Interest Paid on Deposits}$$

#### ⚖️ Bank Ki Balance Sheet (Ek Nazar Me):
* **Liabilities (Bank ki Denadari):** Deposits (Savings, Current, Fixed, Recurring Deposits), Borrowings from RBI/other banks. Yeh paisa bank ka apna nahi hai, depositors ko lautana hai.
* **Assets (Bank ki Sampatti):** Loans and Advances jo bank ne logo ko diye hain, Investments in Government Securities (G-Secs), Cash in hand & balances with RBI. Yahan se bank ko income aati hai.
* **Equity / Bank Capital:** Promoters/Owners ka lagaya hua paisa + Retained Earnings (purana bachaya hua munafa).

```
+-----------------------------------------------------------+
|                   BANK BALANCE SHEET                      |
+-----------------------------+-----------------------------+
|        LIABILITIES          |           ASSETS            |
| (Deposits, Borrowings)      | (Loans Given, Investments)  |
|                             |                             |
| + BANK CAPITAL (EQUITY)     | (Bank ki kamai ka source)   |
| (Bank ka apna safety net)   |                             |
+-----------------------------+-----------------------------+
```

#### 💡 Bank Ko "Capital" (Poonji) Ki Zaroorat Kyon Hoti Hai?
Agar bank ke loans doobne lagein (NPAs ban jayein), toh depositors ka paisa surakshit rakhne ke liye bank ke paas apna khud ka ek **Financial Cushion / Shock Absorber** hona chahiye. Issi shock absorber ko **Capital** kehte hain.

#### 📈 Return on Investment (ROI) vs Return on Equity (ROE):
PDF me diya gaya classic concept:
* **ROI (Return on Investment):** $\frac{\text{Total Net Profit}}{\text{Total Assets / Investment}} \times 100$
* **ROE (Return on Equity):** $\frac{\text{Total Net Profit}}{\text{Owner's Equity Capital}} \times 100$
* Jab bank high leverage (kam apna paisa + zyada depositors ka paisa) use karta hai, toh ROE badh jata hai, lekin risk bhi kai guna badh jata hai!

---

### 2. Risk-Weighted Assets (RWA) Aur Capital Adequacy Ratio (CAR)

#### 🛡️ Risk-Weighted Assets (RWA) Kya Hai?
Bank jo bhi loan deta hai, sabme barabar risk nahi hota:
* **Government Securities (G-Secs):** Zero risk (0% Risk Weight). Sovereign guarantee hoti hai.
* **Home Loan (fully secured):** Kam risk (usually 35% - 50% Risk Weight). Ghar bank ke paas girvi hota hai.
* **Personal Loan / Credit Card:** Bohot zyada risk (unsecured loan) $\rightarrow$ **100% ya 125% - 150% Risk Weight** (PDF Example: Unsecured personal loan criteria depends on income level, repayment capacity, employment history).

$$\text{RWA} = \sum (\text{Loan Amount} \times \text{Risk Weight Percentage})$$

#### 🧮 Capital Adequacy Ratio (CAR / CRAR) Formula:
$$\text{CAR / CRAR} = \frac{\text{Total Capital (Tier 1 + Tier 2)}}{\text{Total Risk Weighted Assets (RWA)}} \times 100$$

#### 🧱 Capital Ke Types:
1. **Tier 1 Capital (Core Capital - Going Concern Capital):**
   * Bank ka sabse solid aur permanent capital jo ordinary business losses ko bina bank band hue absorb kar sakta hai.
   * Includes: Common Equity Tier 1 (CET1) jaise Paid-up Equity Capital, Disclosed Free Reserves, Statutory Reserves; plus Additional Tier 1 (AT1) bonds (perpetual non-cumulative preference shares).
2. **Tier 2 Capital (Supplementary Capital - Gone Concern Capital):**
   * Yeh capital tab kaam aata hai jab bank winding-up (diwaliya) hone ki naubat par aa jaye taaki depositors ko loss na ho.
   * Includes: Subordinated Debt (term >= 5 years), Revaluation Reserves (at discount), General Provisions & Loss Reserves, Hybrid debt capital instruments.

---

### 3. Basel Accords Ka Safar: Basel I, II & III

#### 🌍 Background & Origin:
* **BIS (Bank for International Settlements):** Headquarters: **Basel, Switzerland**. Established: **1930**. Isse central banks ka bank kaha jata hai.
* **BCBS (Basel Committee on Banking Supervision):** 1974 me G-10 desho ke central bank governors ne banaya.
* **Uddeshya:** Duniya bhar ke banking system ko stable aur safe banana taaki 2008 jaisa global financial crisis na dohraye.

```
       +--------------------------------------------------------+
       |                  BASEL ACCORDS TIMELINE                |
       +--------------------------------------------------------+
       | 1988: Basel I  -> Only Credit Risk, 8% CAR            |
       | 2004: Basel II -> 3 Pillars, Credit/Market/Op Risk    |
       | 2010: Basel III-> Strict CET1, Buffers (CCB), LCR/NSFR |
       +--------------------------------------------------------+
```

---

### 4. Detailed Comparison: Basel I vs Basel II vs Basel III

| Parameter | Basel I (1988) | Basel II (2004) | Basel III (2010) |
| :--- | :--- | :--- | :--- |
| **Year of Release** | 1988 (India adopted in 1999) | 2004 (Implemented 2008-09 in India) | 2010 (Post-Lehman crisis, rolled out 2013-2021) |
| **Pillars** | No Pillars concept | **3 Pillars framework** | 3 Pillars strengthen hue + Liquidity standards |
| **Risks Covered** | Only **Credit Risk** | **Credit, Market & Operational Risk** | Credit, Market, Operational + **Systemic & Liquidity Risk** |
| **Minimum CAR (Global)** | **8.0%** | **8.0%** | **8.0%** |
| **Minimum CAR (India - RBI)**| **9.0%** (PSBs target 12%) | **9.0%** | **9.0%** (+ 2.5% CCB = **11.5% Total**) |
| **Tier 1 Capital** | Min 4% (Global) | Min 4% (Global) / **6.0% (India)** | Min 6.0% (Global) / **7.0% (India)** |
| **CET 1 (Common Equity)** | Not separately defined | Min 2% | Min 4.5% (Global) / **5.5% (India)** |
| **Capital Buffers** | Koi buffer nahi tha | Koi buffer nahi tha | **CCB (2.5%)** + **Countercyclical Buffer (0 - 2.5%)** |
| **Liquidity Ratios** | NA | NA | **LCR (100%)** & **NSFR (100%)** |
| **Leverage Ratio** | NA | NA | Min **3.5%** (for domestic banks) / 4.0% for D-SIBs |

---

### 5. Basel II Ke 3 Pillars (Exam Favourite 🌟)

1. **Pillar 1: Minimum Capital Requirements (Poonji Ki Zaroorat)**
   * Teen major risks ke khilaf capital maintain karna mandatory hai:
     * **Credit Risk:** Borrower loan wapas na kare (Standardized, FIRB, AIRB approaches).
     * **Market Risk:** Interest rate badalne, share market girne ya currency exchange rate change hone se loss.
     * **Operational Risk:** Internal systems fail hona, human fraud, software crash, natural disaster (Basic Indicator, Standardized, Advanced Measurement approaches).
2. **Pillar 2: Supervisory Review Process (RBI Ka Danda)**
   * Banks ko apna internal risk assessment karna hota hai jise **ICAAP (Internal Capital Adequacy Assessment Process)** kehte hain.
   * RBI inspect karega ki kya bank ke paas additional buffer capital hai ya nahi. Agar bank zyada risky activities kar raha hai, toh RBI usey extra capital rakhne ka order de sakta hai.
3. **Pillar 3: Market Discipline (Transparency & Disclosures)**
   * Banks ko public aur investors ke samne apna data disclose karna padega: quarterly/annual balance sheet me RWA, NPA levels, capital components, aur risk management practices batana compulsory hai.

---

### 6. Basel III Ke Unique Tools (Deep Dive)

#### 🔹 1. Capital Conservation Buffer (CCB):
* Normal ache dino me bank ko **2.5%** ka additional Common Equity Tier 1 (CET1) capital jama karke rakhna hota hai.
* Jab crisis ya economic stress aaye, toh bank is buffer ko use karke loss absorb kar sakta hai bina collapse hue.
* Isliye India me total minimum capital: **9% (CAR) + 2.5% (CCB) = 11.5%**.

#### 🔹 2. Countercyclical Capital Buffer (CCCB):
* Yeh ek dynamic buffer hai jo **0% se 2.5%** ke beech hota hai.
* Jab economy bohot tezi se boom kar rahi ho aur market me credit growth bohot zyada ho (risk badh raha ho), tab RBI banks ko CCCB build karne bolta hai. Recession me isse release kar diya jata hai.

#### 🔹 3. Liquidity Coverage Ratio (LCR) — *[PDF Page 6]*:
* **Concept:** LCR yeh check karta hai ki agar achanak koi severe liquidity crisis aa jaye (jaise bank run), toh kya bank ke paas itna cash ya cash-jaisa asset hai ki agle **30 dino** tak saari cash demand puri kar sake?
* **Requirement:** Bank ko **High-Quality Liquid Assets (HQLA)** maintain karna padta hai jo easily cash me convert ho sakein bina value loss ke (Cash, Excess CRR/SLR, G-Secs under MSF/FALLCR).
$$\text{LCR} = \frac{\text{Total High-Quality Liquid Assets (HQLA)}}{\text{Total Net Cash Outflows over 30 Days}} \ge 100\%$$

#### 🔹 4. Net Stable Funding Ratio (NSFR):
* LCR short-term (30 days) dekhta hai, jabki **NSFR 1 saal (medium to long-term)** liquidity dekhta hai.
* Iska rule hai: Bank ke long-term illiquid assets (jaise 20 saal ke home loans) ko stable long-term liabilities (jaise 3-5 saal ki fixed deposits, equity capital) se fund kiya jaye, short-term call money se nahi!
$$\text{NSFR} = \frac{\text{Available Stable Funding (ASF)}}{\text{Required Stable Funding (RSF)}} \ge 100\%$$

#### 🔹 5. Leverage Ratio:
* Yeh ek non-risk-based backstop measure hai.
$$\text{Leverage Ratio} = \frac{\text{Tier 1 Capital}}{\text{Total Exposure (On-balance sheet + Off-balance sheet)}} \ge 3.5\%$$
*(Domestic Systemically Important Banks / D-SIBs ke liye 4.0%)*.

---

### 🎯 Exam Pointers & High-Yield Facts (Basel Norms)
* 📌 BCBS Headquarter: **Basel, Switzerland** at Bank for International Settlements (BIS).
* 📌 Basel I introduced in **1988**, Basel II in **2004**, Basel III in **2010**.
* 📌 India me Minimum CAR for Commercial Banks: **9%** (Basel norm says 8%, RBI kept it stricter at 9%).
* 📌 India me Total Capital including CCB: **11.5%** (9% CAR + 2.5% CCB).
* 📌 Small Finance Banks (SFBs) ke liye minimum CAR kitna hai? **15%**!
* 📌 LCR horizon period kitna hai? **30 calendar days**.
* 📌 NSFR time horizon kitna hai? **1 year (greater than 1 year stability)**.

---

### ⚠️ Exam Trap Alert!
> [!CAUTION]
> * **Trap 1:** Exam me puchte hain: "Is Basel norm legally binding on countries?" **NO!** Basel committee guidelines recommendatory hoti hain; har desh ka central bank (jaise RBI) apne regulations ke through unhe legally enforce karta hai.
> * **Trap 2:** Confusing Tier 1 and Tier 2: Agar bank operational hai aur loss absorb ho raha hai toh **Tier 1** kaam aata hai. Agar bank liquidate/band ho raha hai tab **Tier 2** kaam aata hai.

---

### 🧠 Quick Self-Check Quiz (Module 01)
1. **Under Basel III, what is the minimum percentage of Capital Conservation Buffer (CCB) required?**
   * *Answer:* 2.5% (maintained in the form of Common Equity Tier 1).
2. **What is the minimum CAR mandated by RBI for Scheduled Commercial Banks in India (excluding CCB)?**
   * *Answer:* 9% (Global Basel mandate is 8%).
3. **Liquidity Coverage Ratio (LCR) ensures resilience for how many days under a stressed scenario?**
   * *Answer:* 30 Days.

---
---

## 📜 Module 02: Negotiable Instruments Act, 1881

### 1. Act Ka Background & Basic Introduction
* **Enactment Date:** **9 December 1881**
* **Commencement Date (Laagu kab hua):** **1 March 1882**
* **Total Sections:** 148 sections (originally 147, Section 148 added later for appeals in cheque dishonour).
* **Section 13 (1) of NI Act:** Negotiable Instrument ka matlab hota hai — ek **Promissory Note**, **Bill of Exchange**, ya **Cheque**, jo payable ho either to **Order** or to **Bearer**.

#### 🔑 "Negotiable" Ka Matlab Kya Hai?
* **Freely Transferable:** Ek vyakti se dusre vyakti ko bina kisi registration ya stamp duty ke delivery ya endorsement ke through transfer kiya ja sakta hai.
* **Bona Fide Holder for Value (Holder in Due Course - HDC):** Agar lene wale ne good faith me aur valid consideration dekar instrument liya hai, toh uska title transferor ke defective title se bhi better ho jata hai (Section 36 & 118).

```
+------------------------------------------------------------------------+
|                 NEGOTIABLE INSTRUMENTS (SECTION 13)                    |
+--------------------+----------------------------+----------------------+
|  PROMISSORY NOTE   |      BILL OF EXCHANGE      |        CHEQUE        |
|    (Section 4)     |        (Section 5)         |     (Section 6)      |
| "I promise to pay" | "Pay to X or his order"    | Always drawn on bank,|
| 2 Parties (Maker,  | 3 Parties (Drawer, Drawee, | Always payable on    |
| Payee)             | Payee)                     | demand (3 months)    |
+--------------------+----------------------------+----------------------+
```

---

### 2. Promissory Note (Section 4)
* **Definition:** Ek written instrument (bank note ya currency note nahi!) jisme maker ek **unconditional undertaking** (shart-rahit wada) karta hai ki woh ek nishchit vyakti ko ya uske order par ek nishchit raashi (certain sum of money) chukayega.
* **Parties:** 
  1. **Maker:** Jo note banata hai aur sign karta hai (Debtor / Karzdar).
  2. **Payee:** Jisko paisa milna hai (Creditor / Sahukar).
* **Important Legal Restriction (Section 31 of RBI Act, 1934):**
  * Koi bhi private vyakti Promissory Note ko **"Payable to Bearer on Demand"** nahi bana sakta! Yeh privilege sirf aur sirf **RBI aur Central Government** ke paas hai (kyunki agar har koi aisa karega toh woh currency ban jayegi).

---

### 3. Bill of Exchange (Section 5)
* **Definition:** Ek written document jisme drawer kisi vyakti (drawee) ko **unconditional order** deta hai ki woh ek specified person (payee) ko ek specified amount pay kare.
* **Parties:**
  1. **Drawer:** Jo bill likhta hai (Seller / Creditor).
  2. **Drawee:** Jisko order diya jata hai pay karne ka (Buyer / Debtor). Jab drawee bill accept kar leta hai, toh use **Acceptor** kehte hain.
  3. **Payee:** Jisko payment milti hai (Drawer khud bhi payee ho sakta hai, ya koi third party).
  4. **Drawee in case of need:** Agar primary drawee dishonour karde, toh alternative person ka naam mention kiya ja sakta hai.

---

### 4. Cheque (Section 6) — *[Detailed Breakdown]*
* **Definition (Sec 6):** Cheque ek aisa Bill of Exchange hai jo:
  1. Hamesha ek **Specified Banker** par draw kiya jata hai.
  2. Hamesha **On Demand** payable hota hai (kisi future date par demand ke bina nahi).
  3. Isme **Electronic image of a truncated cheque** aur **Cheque in electronic form** shamil hain (amended in 2002).

#### ⏱️ Cheque Ki Validity:
* Pehle cheque ki validity 6 months hoti thi.
* **Effective 1 April 2012**, RBI directive ke mutabik cheque ki validity **3 Months** (90 days) kar di gayi hai.

#### 🏷️ Types of Cheques (Exam Points):
* **Bearer Cheque:** Cheque par "Or Bearer" likha hota hai. Jo vyakti bank counter par cheque lekar jayega, use cash mil jayega. Endorsement ki zaroorat nahi.
* **Order Cheque:** Cheque par "Or Order" likha hota hai. Yeh sirf us vyakti ko milega jiska naam likha hai ya jisko usne endorse kiya hai. Identity verification zaroori hai.
* **Stale Cheque:** Cheque ki date se 3 mahine beet chuke hon. Bank ise dishonour kar dega.
* **Ante-Dated Cheque:** Cheque par aaj ki date se pehle ki date dali ho (valid hai, agar 3 mahine ke andar present kiya jaye).
* **Post-Dated Cheque:** Cheque par aane wali future date dali ho (us date se pehle bank payment nahi kar sakta).
* **Mutilated Cheque:** Fata hua ya damage cheque (agar important part jaise signature, amount ya date damage ho, toh drawer ka confirmation zaroori hai).

---

### 5. Cheque Truncation System (CTS) & MICR Code — *[PDF Pages 11–12]*

#### 🖥️ Cheque Truncation System (CTS-2010):
* Pehle physical cheque ko ek branch se dusri branch physically bheja jata tha, jisme 3-5 din lagte the.
* **CTS:** Ek image-based cheque clearing system hai jahan physical paper cheque ko drawer bank me hi rok (truncate) liya jata hai, aur clearing house ke zariye sirf cheque ki **electronic high-resolution image + MICR data** drawee bank ko bheji jaati hai.
* Bharat me teen operational grids hain:
  1. **Northern Grid (New Delhi)**
  2. **Western Grid (Mumbai)**
  3. **Southern Grid (Chennai)**

#### 🔢 MICR Code (Magnetic Ink Character Recognition) — *9 Digits Structure*:
Cheque ke bottom white band par magnetic ink (Iron Oxide ink) se 9 digits ka code print hota hai:
* Format: `CCC BBB SSS`
  * **First 3 Digits (1 to 3):** **City Code** (PIN code ke pehle 3 digit se match karta hai).
  * **Middle 3 Digits (4 to 6):** **Bank Code** (Particular bank ka unique code).
  * **Last 3 Digits (7 to 9):** **Branch Code** (Us bank ki specific branch ka code).

> **PDF Example [Page 12]:** 
> DBS Bank Fort Branch (Mumbai) ka MICR Code = `400641002`
> * `400` = Mumbai (City)
> * `641` = DBS Bank (Bank)
> * `002` = Fort Branch (Branch)

---

### 6. Crossing of Cheques (Sections 123 to 131)

Crossing ka matlab hai cheque ke face par left-hand top corner me do parallel transverse lines khichna. Crossing ka matlab: **Counter par cash payment nahi hoga; paisa sirf bank account me hi credit hoga.**

```
+--------------------------------------------------------------------+
|                         TYPES OF CROSSING                          |
+---------------------+-----------------------+----------------------+
|  GENERAL CROSSING   |   SPECIAL CROSSING    |   NOT NEGOTIABLE     |
|    (Section 123)    |     (Section 124)     |    (Section 130)     |
|   // or // & Co. // | // State Bank of India// Title transferable,   |
|   Paisa kisi bhi    | Sirf usi specified    | but no better title  |
|   bank account me   | bank me account me    | than transferor      |
|   jama hoga         | jama hoga             |                      |
+---------------------+-----------------------+----------------------+
```

1. **General Crossing (Section 123):** Do parallel transversal lines, jisme "& Co." ya kuch na likha ho. Payment kisi bhi bank account me credit ho sakti hai.
2. **Special Crossing (Section 124):** Do lines ke beech kisi **Bank ka naam** likh diya jata hai (e.g., "State Bank of India"). Ab payment sirf aur sirf usi bank ke through ho sakti hai.
3. **Restrictive Crossing ("Account Payee Only"):** NI Act me specific section nahi hai, par court practice aur RBI guidelines se recognized hai. Cheque strictly usi person ke account me credit hoga jiska naam payee column me likha hai. Endorsement banned ho jati hai.
4. **"Not Negotiable" Crossing (Section 130):** Bohot important concept! Iska matlab yeh NAHI hai ki cheque transfer nahi ho sakta. Yeh transfer ho sakta hai, LEKIN lene wale (transferee) ko transferor se behtar title nahi milega (*Nemo dat quod non habet* - koi bhi vyakti dusre ko usse behtar haq nahi de sakta jo uske paas khud nahi hai). Agar cheque chori ka hai, toh aage kisi ko bhi valid ownership nahi milegi.

---

### 7. Endorsement Ke Types (Section 15) — *[PDF Page 9]*
Endorsement ka matlab hota hai instrument ke peeche ya alag kagaz (**Allonge**) par sign karke uske ownership rights kisi dusre ko transfer karna.
1. **Blank / General Endorsement (Sec 16):** Endorser sirf apna sign karta hai, kisi ka naam nahi likhta. Instrument **Bearer** ban jata hai.
2. **Special / Full Endorsement (Sec 16):** Sign ke sath recipient ka naam bhi likha jata hai ("Pay to Rohan or order").
3. **Restrictive Endorsement (Sec 50):** Aage transfer karne par rok laga di jaati hai ("Pay to Rohan only").
4. **Conditional / Qualified Endorsement (Sec 52):** Payment ko kisi condition se baandh diya jata hai.
5. **Sans Recourse Endorsement (Sec 52):** Endorser likh deta hai *"Sans Recourse"* (bina meri zimmedari ke). Agar instrument dishonour hota hai, toh endorser kisi liability ke liye zimmedar nahi hoga!
6. **Facultative Endorsement:** Endorser apna legal right chhod deta hai (e.g., "Notice of dishonour waived").
7. **Partial Endorsement:** Instrument ke aadhi amount ko endorse karna legally **INVALID** hai (Section 56).

---

### 8. Dishonour of Cheque: Section 138 (Penal Provisions)
Section 138 ke tehat cheque bounce hona (due to insufficient funds ya exceeding arrangements) ek **Criminal Offence** hai.
* **Saza:** Jail term up to **2 Years**, ya cheque amount ka **double (2x) fine**, ya dono!
* **Mandatory Procedure Timelines:**
  1. Cheque validity ke andar (3 months) bank me present hona chahiye.
  2. Cheque return memo milne ke **30 Dino** ke andar drawer ko legal notice bhejna zaroori hai.
  3. Notice milne ke baad drawer ko payment karne ke liye **15 Dino** ka grace time milta hai.
  4. Agar 15 din me payment nahi ki, toh agle **30 Dino** ke andar court (Magistrate court) me complaint file karni hoti hai.

---

### 🎯 Summary Table: Sections of NI Act, 1881
| Section | Subject Matter |
| :--- | :--- |
| **Section 4** | Promissory Note |
| **Section 5** | Bill of Exchange |
| **Section 6** | Cheque |
| **Section 11** | Inland Instrument (Drawn in India & payable in India, or drawn on person resident in India) |
| **Section 12** | Foreign Instrument (Any instrument that is not an Inland Instrument) |
| **Section 13** | Negotiable Instrument (Definition & characteristics) |
| **Section 15** | Endorsement |
| **Section 16** | Endorsement in Blank & Endorsement in Full |
| **Section 22** | Maturity & **3 Days of Grace** (Applicable to Bill of Exchange & Promissory Note; NOT to Cheques!) |
| **Section 25** | Public Holiday falling on maturity date (Instrument matures on the **preceding business day**; for emergency holiday, succeeding day) |
| **Section 85** | Protection to paying banker in case of bearer & order cheques |
| **Section 123** | General Crossing |
| **Section 124** | Special Crossing |
| **Section 130** | "Not Negotiable" Crossing |
| **Section 131** | Protection to collecting banker |
| **Section 138** | Dishonour of Cheque for insufficiency of funds |

---

### 🧠 Quick Self-Check Quiz (Module 02)
1. **Can a private business issue a Promissory Note payable to bearer on demand?**
   * *Answer:* No! Under Section 31 of the RBI Act, 1934, only RBI or the Central Government can issue bearer demand notes.
2. **What does the middle 3 digits of a 9-digit MICR code represent?**
   * *Answer:* Bank Code (First 3 = City, Middle 3 = Bank, Last 3 = Branch).
3. **How many days of grace are allowed for payment of a cheque?**
   * *Answer:* ZERO days! Cheques are always payable on demand. Grace period (3 days) applies only to usance Bills of Exchange and Promissory Notes (Sec 22).

---
---

## ⚖️ Module 03: SARFAESI Act, 2002

### 1. Full Form & Background
* **Full Form:** **Securitisation and Reconstruction of Financial Assets and Enforcement of Security Interest Act, 2002**.
* **Kiske Recommendation par bana?** **Narasimham Committee II (1998)** aur **Andhyarujina Committee (1999)**.
* **Kyon laya gaya?** Pehle banks ko default loans recover karne ke liye Civil Courts ya DRT (Debts Recovery Tribunal) me saalo litigation ladni padti thi. SARFAESI Act ne banks aur financial institutions ko bina court jaye girvi rakhi property (mortgaged security) ko seize aur nilam (auction) karne ki power di!

---

### 2. SARFAESI Act Kahan Apply NAHI Hota? (Section 31 Exemptions) — *[PDF Page 17]*
Yeh exam me 100% pucha jane wala section hai! SARFAESI Act followings par laagu nahi hota:
1. **Agricultural Land (Krishi Bhoomi):** Kheti ki zameen par bank SARFAESI ke tehat direct kabza nahi le sakta (kisano ki suraksha ke liye).
2. **Loan amount below ₹1 Lakh:** Agar kisi loan ka outstanding principal + interest ₹1,00,000 se kam hai.
3. **Remaining debt below 20%:** Agar borrower ne original principal aur interest ka **80% se zyada chuka diya hai** aur bacha hua baaki karz **20% se kam** hai.
4. **Security interest in Aircraft or Vessel/Ship:** Ships aur airplanes par alag maritime/aviation laws lagte hain.
5. **Contract of Pledge (Girvi):** Movable assets jo physically bank ke possession me hain (e.g., Gold Loan me gold jewellery bank ke locker me hoti hai - uspe Indian Contract Act lagta hai, SARFAESI nahi).
6. **Lien on Goods:** Normal banker's lien ya unpaid seller lien.

---

### 3. Step-by-Step Enforcement Process under SARFAESI

```
+--------------------------------------------------------------------------+
|                       SARFAESI RECOVERY TIMELINE                         |
+--------------------------------------------------------------------------+
| 1. NPA Classification: Loan default >= 90 days                           |
| 2. Demand Notice Sec 13(2): 60 Days time given to borrower               |
| 3. Borrower Objection: Borrower can object in 15 days; Bank replies in 15|
| 4. Possession Notice Sec 13(4): Bank takes physical possession           |
| 5. Public Sale Notice: 30 Days notice before auction                     |
| 6. Appeals: Borrower can appeal to DRT within 45 Days                    |
+--------------------------------------------------------------------------+
```

#### Step 1: NPA Declaration
Account ko RBI norms ke tehat **NPA (Non-Performing Asset)** declare hona zaroori hai (overdue > 90 days).

#### Step 2: Demand Notice (Section 13(2))
* Bank borrower aur guarantors ko **60 Days ka legal demand notice** bhejta hai ki pura baaki paisa 60 din ke andar jama karein.

#### Step 3: Borrower's Representation / Objection
* Borrower notice ke khilaf apna representation bhej sakta hai. Bank ko borrower ki objection ka reply **15 Dino ke andar** dena mandatory hai. Agar bank objection reject karta hai, toh reasons specify karne honge.

#### Step 4: Enforcement Measures (Section 13(4))
Agar 60 din me karz nahi chukaya gaya, toh bank followings kar sakta hai:
1. Girvi rakhi sampatti (secured asset) ka physical possession le sakta hai.
2. Property ko rent par de sakta hai ya bech sakta hai.
3. Business ka management take over kar sakta hai.
4. Borrower ke denadaron (debtors) ko bol sakta hai ki paisa borrower ko dene ke bajaye direct bank me jama karein.

#### 👥 Consortium Lending Rule — *[PDF Page 18]*:
Agar kai banks ne milkar kisi company ko loan diya hai (Consortium), toh SARFAESI action initiate karne ke liye kam se kam **60% by value** wale banks ki consent zaroori hai (pehle yeh limit 75% thi, jise amend karke 60% kiya gaya!).

---

### 4. Auction & Bidding Rules — *[PDF Pages 19–20]*
* **Public Sale Notice:** Auction karne se pehle public notice (two leading newspapers, jisme ek vernacular language me ho) me **30 Days ka notice** dena hota hai.
* Subsequent (dusri baar) auction ke liye minimum notice period **15 days** hota hai.
* **Reserve Price:** Bank registered valuer se property ki fair market value aur reserve price fix karwata hai.
* **Earnest Money Deposit (EMD):** Bidders ko sealed envelope ke sath EMD jama karni hoti hai (usually 10% of reserve price).
* **Payment Terms for Highest Bidder:**
  * Successful bidder ko auction ke turant baad bid amount ka **25%** (including EMD) usi din ya agle working day tak jama karna hota hai.
  * Baaki bacha hua **75% amount 15 Dino ke andar** pay karna hota hai (extendable up to max 90 days on written agreement).

---

### 5. Appeals Mechanism (DRT & DRAT)
* **Debts Recovery Tribunal (DRT - Section 17):**
  * Agar borrower bank ke action se aggrieved hai, toh woh possession lene ke **45 Dino ke andar** DRT me appeal kar sakta hai.
* **Debts Recovery Appellate Tribunal (DRAT - Section 18):**
  * DRT ke order ke khilaf appeal **30 Dino ke andar** DRAT me ki ja sakti hai.
  * **Pre-deposit Condition:** Borrower ko DRAT me appeal karne ke liye debt claim ka kam se kam **50% amount** deposit karna padega (DRAT discretion par ise minimum 25% tak kam kar sakta hai, but cannot waive completely!).

---

### 6. Asset Reconstruction Companies (ARCs)
* SARFAESI Act ke Section 3 ke tehat ARCs establish hoti hain aur RBI se register hoti hain.
* ARCs banks se bad loans (NPAs) khareedti hain aur badle me **Security Receipts (SRs)** issue karti hain.
* ARCs in stressed assets ko resolve, restructure ya liquidate karke recovery karti hain. Example: ARCIL, NARCL (National Asset Reconstruction Company Ltd - Bad Bank).

---

### 🧠 Quick Self-Check Quiz (Module 03)
1. **Can a bank seize agricultural land under the SARFAESI Act?**
   * *Answer:* NO! Section 31 specifically exempts agricultural land.
2. **What is the minimum percentage of lenders required to approve action under SARFAESI in consortium lending?**
   * *Answer:* 60% by value (amended from 75%).
3. **What is the demand notice period given to the borrower under Section 13(2)?**
   * *Answer:* 60 Days.
4. **How much pre-deposit is generally required to file an appeal before DRAT?**
   * *Answer:* 50% of the debt amount (can be reduced to minimum 25% by DRAT).

---
---

## 🌾 Module 04: Priority Sector Lending (PSL) & MSME Norms

### 1. PSL Kya Hai Aur Kyon Zaroori Hai?
Desh ki overall inclusive growth ke liye RBI aur Government of India kuch aise sectors identify karti hain jinhe agar easily aur saste rate par credit (loan) na mile toh garib, kisan aur chhote karobari peechhe chhut jayenge. Inhi priority sectors ko banks ke dwara loan dena mandatory banaya gaya hai.
* **Origin:** 1972 me National Credit Council ki meeting me concept shuru hua; formal framework **Dr. K.S. Krishnaswamy Committee** ki report par 1980 me implement hua.

---

### 2. Overall PSL Targets (% of ANBC or CEOBE, whichever is higher)

* **ANBC:** Adjusted Net Bank Credit
* **CEOBE:** Credit Equivalent of Off-Balance Sheet Exposure

```
+---------------------------------------------------------------------+
|                  OVERALL PSL TARGET MATRIX                          |
+---------------------------------------------------+-----------------+
| Bank Category                                     | Overall Target  |
+---------------------------------------------------+-----------------+
| Domestic Scheduled Commercial Banks (Public/Pvt)  | 40% of ANBC     |
| Foreign Banks with 20 branches and above          | 40% of ANBC     |
| Foreign Banks with less than 20 branches          | 40% of ANBC *   |
| Regional Rural Banks (RRBs)                       | 75% of ANBC     |
| Small Finance Banks (SFBs)                        | 75% of ANBC     |
| Primary Urban Co-operative Banks (UCBs)           | 75% by Mar 2026 |
+---------------------------------------------------+-----------------+
* Note: Foreign banks with < 20 branches can achieve up to 32% in exports and remaining 8% in any other priority sector.
```

---

### 3. Priority Sector Ke 8 Mandated Categories (Deep Dive)

1. **Agriculture (Krishi):** Total Agriculture target is **18% of ANBC** (jisme se **10% Small & Marginal Farmers** ke liye sub-target hai).
   * **Farm Credit (Kisaano ko direct loan):** Crop loans, allied activities (dairy, poultry, fisheries).
   * **Agriculture Infrastructure:** Poly houses, cold chains, silos, warehouses $\rightarrow$ **Aggregate limit of ₹100 Crore per borrower** from the banking system!
   * **Ancillary Activities:** Setting up Agri-clinics, Custom Hiring Centres, food processing units up to ₹100 Crore per borrower.
   * **Loans against Warehouse Receipts (NWRs/eNWRs) — [PDF Page 23]:**
     * Against Negotiable Warehouse Receipts (NWRs/eNWRs): **Up to ₹75 Lakh** (tenor up to 12 months).
     * Against other warehouse receipts: **Up to ₹50 Lakh**.
   * **Loans to FPOs / Farmer Producer Companies:** **Up to ₹5 Crore** per borrowing entity having assured marketing at pre-determined price. UCBs are NOT permitted to lend to co-operatives of farmers.
2. **Micro, Small & Medium Enterprises (MSME):**
   * Mandated sub-target: **7.5% of ANBC** for **Micro Enterprises**.
   * **Revised MSME Composite Criteria (w.e.f. 1 July 2020) — [PDF Page 23]:**
     * **Micro:** Investment in Plant & Machinery $\le$ **₹1 Crore** AND Annual Turnover $\le$ **₹5 Crore**.
     * **Small:** Investment in Plant & Machinery $\le$ **₹10 Crore** AND Annual Turnover $\le$ **₹50 Crore**.
     * **Medium:** Investment in Plant & Machinery $\le$ **₹50 Crore** AND Annual Turnover $\le$ **₹250 Crore**.
3. **Education — [PDF Page 24]:**
   * Loans to individuals for educational purposes, including vocational courses, **up to ₹20 Lakh** (irrespective of whether studying in India or abroad).
4. **Housing — [PDF Page 24]:**
   * **Metropolitan centres** (population 10 Lakh & above): Loans **up to ₹35 Lakh** where overall dwelling unit cost does not exceed **₹45 Lakh**.
   * **Other centres / Non-metro**: Loans **up to ₹25 Lakh** where overall dwelling unit cost does not exceed **₹30 Lakh**.
   * **Repairs to damaged houses:** Up to **₹10 Lakh** in metropolitan centres, and up to **₹6 Lakh** in other centres.
   * Housing loans to banks' own employees are NOT counted under PSL!
5. **Social Infrastructure — [PDF Page 24]:**
   * Schools, drinking water facilities, sanitation facilities (including construction/refurbishment of toilets), and health care facilities: **Up to ₹5 Crore per borrower**.
   * Health care facilities under Ayushman Bharat in Tier II to Tier VI centres: **Up to ₹10 Crore per borrower**.
6. **Renewable Energy — [PDF Page 24]:**
   * Solar based power generators, biomass generators, wind mills, micro-hydel plants: **Up to ₹30 Crore per borrower**.
   * For individual households: Loan limit is **up to ₹10 Lakh per borrower**.
7. **Export Credit:**
   * Domestic banks: Incremental export credit over previous year up to **2% of ANBC/CEOBE**, subject to sanctioned limit up to **₹40 Crore per borrower**.
8. **Others / Weaker Sections — [PDF Page 26]:**
   * Mandatory target for Weaker Sections: **12% of ANBC** (phased up from 10%).
   * Loans to distressed persons not exceeding ₹1 Lakh to prepay debt to non-institutional lenders.
   * Loans to individual women beneficiaries up to ₹1 Lakh.
   * Beneficiaries under DRI (Differential Rate of Interest Scheme - 4% interest, up to ₹15,000 loan).

---

### 4. Small & Marginal Farmers (SMFs) Definition — *[PDF Page 22]*
* **Marginal Farmers:** Jin kisaano ke paas **up to 1 hectare** (approx 2.5 acres) zameen hai.
* **Small Farmers:** Jin kisaano ke paas **more than 1 hectare and up to 2 hectares** (approx 2.5 to 5 acres) zameen hai.
* Sub-target for SMFs in Agriculture: **10% of ANBC** (phased up from 8%).

---

### 5. Revised PSL Guidelines 2020 (UK Sinha Committee Recommendations) — *[PDF Page 25]*
1. **District-Level Weightage System:**
   * To address regional disparities in credit flow, RBI introduced an incentive framework:
     * Districts with low credit penetration (per capita PSL credit < ₹25,000): **125% higher weightage** given to incremental loans!
     * Districts with already high credit flow (per capita PSL credit > ₹40,000): **90% lower weightage** given.
2. **Startups Financing:** Bank loans **up to ₹50 Crore** to startups engaged in Agriculture and MSME classified under PSL.
3. **Solarisation of Agriculture Pumps:** Loans to farmers for solarisation of grid-connected agriculture pumps and setting up compressed bio-gas (CBG) plants covered under PSL.

---

### 6. PSL Kahan Apply NAHI Hota? Aur Shortfall Par Kya Hota Hai? — *[PDF Page 27]*
* **PSL Excluded Institutions:** **Payments Banks** (kyunki woh loan nahi de sakte) aur **AIFIs** (NABARD, NHB, SIDBI, EXIM, NaBFID).
* **Penalty on PSL Non-Achievement:**
  * Agar koi commercial bank apna PSL target achieve karne me fail ho jata hai, toh us shortfall amount ko RBI ke instructions par low-interest yielding funds me deposit karna padta hai:
    * **RIDF (Rural Infrastructure Development Fund)** with NABARD.
    * **SEDF (Small Enterprises Development Fund)** with SIDBI.
    * **RHDF (Rural Housing Development Fund)** with NHB.
* **PSLC (Priority Sector Lending Certificates):**
  * Banks target shortfall se bachne ke liye doosre surplus banks se **PSLCs** khareed sakte hain bina actual loan assets transfer kiye (traded on RBI e-Kuber portal).

---

### 🧠 Quick Self-Check Quiz (Module 04)
1. **What is the overall PSL target for Regional Rural Banks (RRBs) and Small Finance Banks (SFBs)?**
   * *Answer:* 75% of ANBC or CEOBE.
2. **What is the maximum loan limit for education under priority sector lending?**
   * *Answer:* ₹20 Lakh.
3. **What is the maximum investment and turnover limit for a 'Micro' enterprise under the revised MSME definition?**
   * *Answer:* Investment $\le$ ₹1 Crore and Turnover $\le$ ₹5 Crore.
4. **What is the loan limit against electronic Negotiable Warehouse Receipts (eNWRs) under PSL?**
   * *Answer:* Up to ₹75 Lakh (for non-eNWRs it is ₹50 Lakh).

---
---

## 🏛️ Module 05: Banking Regulation Act, 1949

### 1. Act Ka History & Structure
* **Enactment:** Originally passed as **The Banking Companies Act, 1949**.
* **Came into force:** **16 March 1949**.
* **Renamed:** **The Banking Regulation Act, 1949** w.e.f. **1 March 1966**.
* **Extension to Co-operative Banks:** **1965 me Section 56 (Part V)** add karke cooperative banks ko bhi iske purview me laya gaya.
* **Applicability:** Pure Bharat me sabhi banking companies, cooperative banks (with certain exceptions), aur scheduled banks par laagu hota hai. (RBI Act central banking powers deta hai, jabki BR Act commercial banking operations aur licensing ko govern karta hai).

---

### 2. Banking Definition & Permitted Activities

#### 📌 Section 5(b) - Definition of "Banking":
"Banking means the accepting, for the purpose of lending or investment, of deposits of money from the public, repayable on demand or otherwise, and withdrawable by cheque, draft, order or otherwise."
> **Key Elements:**
> 1. Public se deposit lena.
> 2. Deposit ka purpose lending (loan dena) ya investment hona chahiye.
> 3. Yeh deposit demand par ya tenure khatam hone par vapas milna chahiye.
> 4. Customer ise Cheque, DD, ATM ya electronic order se nikal sakta ho.

#### 📌 Section 6 - Permitted Business for Banks:
Banks loan dene aur deposit lene ke alawa foreign exchange, issuing letters of credit, guarantees, bill discounting, safe deposit lockers, acting as agents, etc. kar sakte hain.

#### 🚫 Section 8 - Prohibition of Trading:
Koi bhi bank direct trading in goods (saman khareedna aur bechna) ya commercial business nahi kar sakta, except in realization of securities pledged to it.

#### 🏠 Section 9 - Disposal of Non-Banking Assets:
Agar kisi borrower ne loan default kiya aur bank ne uski property kabza kar li, toh bank use apne paas indefinite time tak nahi rakh sakta. Bank ko aisi non-banking property ko **7 Years ke andar dispose (sell)** karna padega (RBI can extend this period by another 5 years).

---

### 3. Capital & Governance Norms

#### 💰 Section 11 - Minimum Paid-up Capital & Reserves — *[PDF Page 47]*:
Historically Act me mandated baseline capital:
* **Domestic Bank:** Minimum ₹5 Lakh (Agar Mumbai aur Kolkata me business place ho toh ₹10 Lakh).
* **Foreign Bank:** Minimum ₹15 Lakh (Agar Mumbai aur Kolkata me business place ho toh ₹20 Lakh).
*(Note: Modern licensing norms me RBI on-tap guidelines ke tehat universal bank ke liye ₹500 Cr aur SFB ke liye ₹200 Cr paid-up voting equity capital mandate karta hai).*

#### 📊 Section 12 - Regulation of Capital:
* Subscribed Capital authorized capital ka kam se kam **50%** hona chahiye.
* Paid-up Capital subscribed capital ka kam se kam **50%** hona chahiye.

#### 🚫 Section 20 - Restrictions on Loans:
* Koi bhi banking company **apne khud ke shares ke khilaf loan nahi de sakti**!
* Directors aur unki interested firms ko bina board approval loans dene par strict restrictions hain.

---

### 4. Reserve Requirements & Licensing

#### 🛡️ Section 18 - Cash Reserve for Non-Scheduled Banks:
Non-scheduled banks ko apne Net Demand and Time Liabilities (NDTL) ka kam se kam **3% Cash Reserve** maintain karna padta hai (RBI Act Section 42 scheduled banks ke liye CRR govern karta hai).

#### 📜 Section 22 - Licensing of Banking Companies — *[PDF Page 48]*:
* Bharat me koi bhi company bina RBI ke dwara issue kiye gaye **Banking License** ke banking business start ya continue nahi kar sakti.
* RBI license dene se pehle verify karta hai ki company depositors ke interest ko protect karne ki financial capability rakhti hai.

#### 🏢 Section 23 - Branch Licensing:
Banks ko nayi branch kholne, ya existing branch shift karne ke liye RBI ki prior permission lena mandatory hai (subject to RBI branch authorization policy).

#### 🔒 Section 24 - Maintenance of Statutory Liquidity Ratio (SLR):
* Har banking company ko apne NDTL ka ek specified percentage liquid assets (Cash, Gold, Unencumbered Approved Government Securities) ke roop me maintain karna hota hai.
* Maximum statutory ceiling limit: **40% of NDTL**.

---

### 5. Supervisory, Regulatory & Emergency Powers of RBI

#### 📑 Section 29 & 30 - Accounts and Audit:
* Har financial year ke end (31 March) par balance sheet aur P&L account Schedule III ke format me banana hota hai aur duly audited karwana padta hai.

#### 🔍 Section 35 - Inspection:
* RBI ko power hai ki woh kisi bhi bank aur uske branches ki books of accounts aur transactions ka kisi bhi samay inspection aur scrutiny kar sakta hai.

#### 📢 Section 35A - Power of RBI to Give Directions:
* RBI public interest me, depositors ke interest me, ya banking policy ke proper management ke liye kisi bhi bank ya sabhi banks ko legally binding directions issue kar sakta hai.

#### 🛑 Section 36AA - Removal of Managerial Personnel — *[PDF Page 49]*:
* Agar RBI ko lagta hai ki bank ke Chairman, Director, MD, Chief Executive Officer ya kisi employee ka conduct depositors ke hit ke khilaf hai, toh RBI use office se **remove (barkhast)** kar sakti hai.

#### 👥 Section 36AB - Appointment of Additional Directors:
* RBI bank ke board me apne nominated **Additional Directors** appoint kar sakti hai for better governance.

#### ⏳ Section 45 - Moratorium & Amalgamation:
* Agar koi bank deep financial crisis me phas jaye, toh RBI Central Government ko apply karke bank par **Moratorium (temporary withdrawal restrictions)** lagwa sakti hai.
* Moratorium period ke dauran RBI us bank ko kisi strong bank ke sath **Amalgamate (Merge)** karne ka scheme bana sakti hai (Jaise Yes Bank crisis me SBI scheme ya PMC Bank rescue me Unity SFB amalgamation).

---

### 🎯 Summary Matrix: High-Frequency Sections of BR Act, 1949
| Section | Key Subject | Exam Note |
| :--- | :--- | :--- |
| **Section 5(b)** | Definition of Banking | Accepting deposits for lending/investment |
| **Section 8** | Prohibition of Trading | Banks cannot buy/sell commodities/goods directly |
| **Section 9** | Non-Banking Assets | Must be disposed of within **7 Years** |
| **Section 11** | Minimum Capital & Reserves | Statutory baseline capital limits |
| **Section 18** | Cash Reserve for Non-Scheduled Banks | Minimum 3% of NDTL |
| **Section 20** | Restriction on Loans | Cannot grant loans against its own shares |
| **Section 21** | RBI Power to Control Advances | Setting interest rates, margin rules |
| **Section 22** | Licensing of Banks | Mandatory license to commence banking business |
| **Section 24** | Statutory Liquidity Ratio (SLR) | Maintained in Liquid Assets up to 40% cap |
| **Section 29** | Balance Sheet & Accounts | Annual accounts audited as per Schedule III |
| **Section 35** | Inspection by RBI | Comprehensive inspection of books & records |
| **Section 35A** | Power to issue Directions | Binding directions in public/depositor interest |
| **Section 36AA** | Removal of Bank Management | Removal of Chairman/MD/CEO by RBI |
| **Section 45** | Moratorium & Reconstruction | Scheme of forced merger/rescue of failing banks |
| **Section 56** | Application to Co-operative Banks | Added in 1965 to regulate Urban Co-op Banks |

---

### 🧠 Quick Self-Check Quiz (Module 05)
1. **Under which section of the Banking Regulation Act, 1949 is 'Banking' defined?**
   * *Answer:* Section 5(b).
2. **What is the maximum time period allowed to a banking company to hold non-banking assets under Section 9?**
   * *Answer:* 7 Years (extendable by RBI by another 5 years).
3. **Can a commercial bank grant a loan against the security of its own shares?**
   * *Answer:* Strictly prohibited under Section 20!
4. **Which section gives RBI the power to issue binding directions to banks in public interest?**
   * *Answer:* Section 35A.
