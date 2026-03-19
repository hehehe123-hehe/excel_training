# 📊 Excel Practice — Easy Level Complete

> A documented collection of 12 completed Easy-level Excel exercises from [BelajarExcel.id](https://belajarexcel.id/xl-test/), covering real-world administrative scenarios from payroll and sales administration to text manipulation and housing credit calculations.

---

## About This Repository

This repository documents my progress through a structured Excel practice platform. Every exercise file has been completed and is included here as-is — each `.xlsx` file contains its own automated answer-checking system (the platform's XL-Test engine), so the correctness of each solution can be verified directly by opening the file.

The exercises simulate real workplace data scenarios: employee payroll, sales reporting, ticket booking systems, document administration, and financial calculations. All 12 Easy-level exercises are complete. Medium through Championship levels are the next target.

---

## Progress

| Level | Exercises | Status |
|-------|-----------|--------|
| 🟢 Easy | 12 / 12 | ✅ Complete |
| 🟡 Medium | 0 / 14 | 🔄 Up next |
| 🟠 Hard | 0 / 11 | ⏳ Planned |
| 🔴 Extreme | 0 / 7 | ⏳ Planned |
| 🏆 Championship | 0 / 5 | ⏳ Planned |

---

## Exercises Completed

### SBEE001 — Mathematical Operators
**File:** `SBEE001_Operator_Matematika.xlsx`

A sales order dataset with 14 data rows. The task covers all core arithmetic operators: addition (total orders), subtraction (cancelled vs fulfilled), multiplication (total price from unit price × quantity), division (cancellation rate as a percentage), percentage calculation (5% tax), exponentiation (orders squared), percentage-based discount, and operator precedence for profit calculation.

**Functions used:** arithmetic operators `+` `-` `*` `/`, `^`, order of operations

---

### SBEE002 — Math Functions
**File:** `SBEE002_Matematika_V1.xlsx`

A series of 8 standalone math problems using Excel aggregate functions instead of manual operators. Each row presents a sequence of 20 numbers and asks for a specific operation across them — summing, subtracting, multiplying, or dividing the entire sequence. The challenge is selecting the correct function and range for each case.

**Functions used:** `SUM`, `PRODUCT`, arithmetic operators for sequential subtraction and division

---

### SBEE003 — VLOOKUP and HLOOKUP
**File:** `SBEE003_VLOOKUP_dan_HLOOKUP.xlsx`

A sales transaction log for a building materials store (Toko Bangunan Berkah) with 15 transactions across multiple customers and products. Customer names and product details are stored in separate reference tables; the task requires pulling them in using lookup functions. Additional tasks: calculate total sales (unit price × quantity), apply a conditional discount (10% if quantity > 200, 20% if quantity > 500), calculate net sales, and compute total and average values.

**Functions used:** `VLOOKUP`, `HLOOKUP`, `IF`, `SUM`, `AVERAGE`, multiplication operators

---

### SBEE004 — School Administration
**File:** `SBEE004_Admin_Sekolah.xlsx`

A university graduation fee dataset with 10 student records. Each student has a National Student ID (NPM) that encodes their year of enrollment, faculty, and campus branch. Tasks include: extracting the enrollment year from mid-string characters, looking up faculty name from a reference table using a 2-character code, determining campus branch from the 7th character of the NPM, calculating discount percentage based on GPA ranges, determining the graduation fee based on enrollment year, and computing the final total as fee minus discount.

**Functions used:** `MID`, `VLOOKUP`, `IF` (nested), `VALUE`, `LEFT`, `RIGHT`

---

### SBEE005 — Train Ticket Administration
**File:** `SBEE005_Admin_Tiket_Kereta_Api.xlsx`

A ticket booking system dataset with 7 passenger records. Each record has a 4-character ticket code encoding both the travel class (first 3 characters: EKO, BIS, EXC) and passenger type (4th character: A=Anak/Child, D=Dewasa/Adult, L=Lansia/Senior). Tasks: decode the class using `LEFT` and `HLOOKUP` against a class table, decode the passenger type using `RIGHT` and `VLOOKUP`, look up the base ticket price from a 2D rate table based on both class and type, apply a 10% discount for departures before a cutoff date, and calculate net price.

**Functions used:** `LEFT`, `RIGHT`, `MID`, `VLOOKUP`, `HLOOKUP`, `IF`, subtraction operators

---

### SBEE006 — Simple Payroll
**File:** `SBEE006_Gaji_Sederhana.xlsx`

An employee payroll report for PT. BelajarExcel.ID Property with 10 employees. Each employee has a structured 5-character code (e.g. `A-1-M`) that encodes division, position, and marital status. Tasks: extract position from the 3rd character and map it (1=Kepala/Head, 2=Staff, 3=Operator), extract marital status from the last character (S=Single, M=Married), extract division from the 1st character and look up the name and base salary from a reference table, calculate child allowance at Rp25,000 per child (married employees only), compute total salary, and calculate aggregate statistics (total, highest, lowest, average, count).

**Functions used:** `MID`, `RIGHT`, `LEFT`, `VLOOKUP`, `IF`, `SUM`, `MAX`, `MIN`, `AVERAGE`, `COUNTA`

---

### SBEE007 — Sales Administration
**File:** `SBEE007_Admin_Penjualan.xlsx`

A weekly profit report for an electronics store (Toko Ilmu BelajarExcel.id) with 10 product records. Each product has a structured code (e.g. `TV-99-EUR-M2`) encoding the product type, a 2-digit price multiplier, currency, and brand tier. Tasks: construct the product name from code segments using lookup tables, calculate base cost from the 2-digit code × currency rate × brand multiplier, calculate total sales at 125% of cost × quantity sold, apply a tiered discount (0% to 25% based on 6 revenue thresholds), determine the bonus item using nested `IF` logic (PowerBank, TWS, Voucher, or none based on revenue and discount combinations), and compute the net total. Aggregate statistics required at the end.

**Functions used:** `LEFT`, `MID`, `VLOOKUP`, `IF` (nested, multiple conditions), `VALUE`, `SUM`, `MAX`, `MIN`, `AVERAGE`, `COUNT`, arithmetic operators

---

### SBEE008 — Simple Payroll with Allowances
**File:** `SBEE008_Gaji_Sederhana.xlsx`

An employee salary calculation with 9 employees across 3 employment grades (A, B, C). Tasks: determine base salary from grade (A=Rp1,500,000 / B=Rp1,800,000 / C=Rp2,000,000), calculate child allowance at Rp300,000 per child up to a maximum of 2 children, determine family allowance (Rp500,000 if married, Rp400,000 if single), apply a position allowance of Rp1,000,000 for employees with 5 or more years of service, calculate transportation allowance as 7.5% of base salary, and sum all components into a final total salary.

**Functions used:** `IF`, `MIN`, arithmetic operators, percentage calculations

---

### SBEE009 — Housing Credit (Mortgage)
**File:** `SBEE009_Kredit_Perumahan.xlsx`

A housing credit sales dataset for PT. BelajarExcel.id with 10 property buyers. Property types are encoded with a single letter (A, C, M, S, T) linked to a reference table. Tasks: look up land area and sale price from the property code, calculate VAT (PPn) as a percentage of the sale price based on the property code, compute the total price, determine the down payment from a credit table percentage, calculate the monthly principal installment, calculate monthly interest from the credit table rate, sum both into a monthly payment, compute the total credit cost, and determine the loan end date by adding the loan duration in months to the start date.

**Functions used:** `VLOOKUP`, `IF`, arithmetic operators, `DATE`, `EDATE` or date arithmetic, percentage calculations

---

### SBEE010 — Text and String Functions
**File:** `SBEE010_Fungsi_Text_atau_String.xlsx`

A document management dataset with 14 letter records. Each record has a raw letter code with intentional leading/trailing spaces and inconsistent formatting (e.g. `   R-002/2023/04/20   `), and a raw participant name in mixed random case (e.g. `bUDi sANtoSo`). Tasks: classify the letter type from the first character of the trimmed code (B=Biasa, R=Rahasia, S=Segera), extract year, month, and day from fixed positions in the code, build a valid date from those components, generate a final standardized code by inserting `FL` before the date segment, clean and properly capitalize the participant name using `TRIM` and `PROPER`, count the character length of the cleaned name, extract initials from the first letter of each word, and build a formatted identifier combining initials and date.

**Functions used:** `TRIM`, `LEFT`, `MID`, `RIGHT`, `LEN`, `PROPER`, `UPPER`, `IF`, `DATE`, `TEXT`, `&` (concatenation), `FIND`

---

### SBEE011 — Payroll with Deductions
**File:** `SBEE011_Gaji_dan_Potongan.xlsx`

A non-permanent employee payroll for an international organization with 16 employees. Base salary components (base pay, allowance, meal allowance) are looked up from an education-level reference table (SMA, D-III, S-1, S-2). Tasks: populate all three salary components from the table, compute the total gross salary, determine income tax percentage from the education table, calculate post-tax salary, apply a disciplinary deduction as a fraction of gross salary based on a violation severity code (Berat/Heavy=50%, Sedang/Medium=25%, Ringan/Light=15%, Nihil/None=0%), apply a working-hours deduction based on a time-violation code from a separate penalties table, and calculate the final net salary. The last row requires column totals for all fields except tax, which uses the average.

**Functions used:** `VLOOKUP`, `IF` (nested), `SUM`, `AVERAGE`, arithmetic operators, percentage calculations

---

### SBEE012 — Text Case Standardization
**File:** `SBEE012_Hurup_Besar_Hurup_Kecil.xlsx`

A participant data cleaning exercise with 15 records. Each record has a raw name in inconsistent mixed case and a raw school name in random case. Tasks: convert the name to all uppercase, convert to all lowercase, convert to title case (each word capitalized), convert to sentence case (first word only capitalized), detect the original casing type (all-uppercase, all-lowercase, or mixed — determined by comparing the original against its uppercase and lowercase transforms), build a custom format with first letter capitalized and last letter uppercased, and standardize the school name so only the education level prefix (SD, SMP, SMA) is uppercase while the rest follows title case.

**Functions used:** `UPPER`, `LOWER`, `PROPER`, `LEFT`, `RIGHT`, `MID`, `LEN`, `IF`, `EXACT`, `&` (concatenation)

---

## Skills Covered

| Category | Functions |
|----------|-----------|
| Arithmetic | `+` `-` `*` `/` `^`, operator precedence, percentage |
| Aggregate | `SUM`, `AVERAGE`, `MAX`, `MIN`, `COUNT`, `COUNTA`, `PRODUCT` |
| Logical | `IF`, nested `IF`, multi-condition `IF` |
| Lookup | `VLOOKUP`, `HLOOKUP` |
| Text | `LEFT`, `MID`, `RIGHT`, `LEN`, `TRIM`, `UPPER`, `LOWER`, `PROPER`, `EXACT`, `&`, `TEXT`, `FIND` |
| Date | `DATE`, `EDATE`, date arithmetic |
| Financial | percentage-based installment and interest calculation |

---

## Repository Structure

```
excel-practice/
├── README.md
├── SBEE001_Operator_Matematika.xlsx
├── SBEE002_Matematika_V1.xlsx
├── SBEE003_VLOOKUP_dan_HLOOKUP.xlsx
├── SBEE004_Admin_Sekolah.xlsx
├── SBEE005_Admin_Tiket_Kereta_Api.xlsx
├── SBEE006_Gaji_Sederhana.xlsx
├── SBEE007_Admin_Penjualan.xlsx
├── SBEE008_Gaji_Sederhana_Allowances.xlsx
├── SBEE009_Kredit_Perumahan.xlsx
├── SBEE010_Fungsi_Text_String.xlsx
├── SBEE011_Gaji_dan_Potongan.xlsx
└── SBEE012_Hurup_Besar_Hurup_Kecil.xlsx
```

Each file contains the original question sheet, an automated answer-checking sheet, and my completed solutions. Opening any file and navigating to the `XL-Test` sheet will show which answers are marked correct.

---

## Source

All exercises are from [BelajarExcel.id — XL-Test](https://belajarexcel.id/xl-test/), a platform providing structured Excel practice with automated answer validation.
