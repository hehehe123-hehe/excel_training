# 📊 Excel Practice — Progress Log

A documented collection of completed Excel exercises from BelajarExcel.id XL-Test, covering real-world administrative scenarios from basic arithmetic and salary calculations to advanced date engineering, NIK parsing, and SLA monitoring.

## Progress

| Level | Exercises | Status |
|---|---|---|
| 🟢 Easy | 12 / 12 | ✅ Complete |
| 🟡 Medium | 15 / 15 | ✅ Complete |
| 🟠 Hard | 12 / 12 | ✅ Complete |
| 🔴 Extreme | 8 / 8 | ✅ Complete |
| 🏆 Championship | 0 / 5 | ⏳ Planned |

---

## 🟢 Easy Level — Exercise Summaries

| Code | Title | Scenario | Skills Covered |
|---|---|---|---|
| SBEE001 | Operator Matematika | Basic arithmetic on order data — calculate total orders (add), cancelled orders (subtract), total price (multiply), cancellation rate (divide), 5% tax, orders squared, price after 25% discount, and net profit using operator precedence | `+`, `-`, `*`, `/`, `%`, `^`, operator precedence |
| SBEE002 | Fungsi Matematika | Aggregate functions on 20-number arrays — sum, subtract-from-base, and multiply/divide all values across 8 rows using Excel functions instead of manual operators | `SUM`, `PRODUCT`, subtraction from base value |
| SBEE003 | VLOOKUP & HLOOKUP Penjualan Sederhana | Building materials sales — look up customer name by code (VLOOKUP), product name and unit price by product code (HLOOKUP), compute total sales, assign tiered discount (10% above 200 qty, 20% above 500), calculate net sales, total and average QTY and revenue | `VLOOKUP`, `HLOOKUP`, `IF`, `SUM`, `AVERAGE` |
| SBEE004 | Admin Sekolah (Data Mahasiswa) | University graduation fee calculator — extract enrollment year from NPM using MID, look up major from 2-letter prefix using VLOOKUP, assign campus branch / discount / tuition fee by NPM last digit and GPA using nested IF, compute final fee after discount | `MID`, `VALUE`, `LEFT`, `RIGHT`, `VLOOKUP`, nested `IF` |
| SBEE005 | Admin Tiket Kereta Api | Train ticket system — decode 4-character ticket code: first 3 letters → seat class (HLOOKUP from class table), 4th letter → passenger type (VLOOKUP from ticket table), price from cross-lookup of class × type, 10% early-bird discount for departures before Sept 1 2023, net price | `HLOOKUP`, `VLOOKUP`, `MATCH`, `LEFT`, `MID`, `IF`, `DATE` |
| SBEE006 | Gaji Sederhana (Admin Gaji) | Simple payroll — decode employee code to derive job title (MID, nested IF), marital status (RIGHT, IF), division and base salary (VLOOKUP from lookup table), child allowance (Rp25,000/child for married staff), total salary; aggregate totals, max, min, average, count | `MID`, `RIGHT`, `LEFT`, `IF`, `VLOOKUP`, `SUM`, `MAX`, `MIN`, `AVERAGE`, `COUNT` |
| SBEE007 | Admin Toko Penjualan | Electronics sales report — parse composite product code to derive product name and brand (VLOOKUP/HLOOKUP), calculate cost price from embedded digits × currency rate (VLOOKUP), total sales price (+25% markup × qty), 6-tier discount, bonus reward (PowerBank/TWS/Voucher) by combined sales+discount criteria, net total; aggregate summary | `LEFT`, `MID`, `RIGHT`, `VLOOKUP`, `HLOOKUP`, nested `IF`, `AND`, `SUM`, `MAX`, `MIN`, `AVERAGE` |
| SBEE008 | Gaji Sederhana (DEF1) | Government-style allowance payroll — calculate base salary by employment grade (A/B/C) using IF; child allowance Rp300,000/child capped at 2 children (MIN); family allowance by marital status (IF); job allowance by tenure ≥6 years (IF); transport allowance as 7.5% of base salary | `IF`, `MIN`, `*` percentage |
| SBEE009 | Kredit Perumahan | Housing credit calculator — look up land area, selling price, and PPN rate by house type code (VLOOKUP); calculate total price with PPN; derive down payment, principal per month, interest per month (HLOOKUP), monthly installment, total credit cost, and loan maturity date | `VLOOKUP`, `HLOOKUP`, `SUM`, `EDATE`, date arithmetic |
| SBEE010 | Fungsi Text / String | Letter code & text parsing — classify letter type (B/R/S) from first character; extract year, month, day from padded letter code string using MID/RIGHT; construct a valid DATE; insert "FL" into code string using REPLACE; clean and proper-case messy names (TRIM, PROPER); count characters (LEN); extract two-letter initials; build Indonesian date stamp (TEXT with locale) | `IFS`, `LEFT`, `MID`, `RIGHT`, `TRIM`, `DATE`, `REPLACE`, `PROPER`, `LEN`, `FIND`, `TEXT` with Indonesian locale |
| SBEE011 | Gaji dan Potongan | Multi-table payroll with deductions — look up base salary, allowance, and daily meal allowance (×25 working days) by education level; compute total gross; look up income tax rate by education (HLOOKUP); calculate post-tax salary; apply discipline penalty (% of gross from sanctions table) and late-deduction (% of gross from time table); compute net salary; aggregate totals and average tax | `VLOOKUP`, `HLOOKUP`, `IF`, `SUM`, `AVERAGE` |
| SBEE012 | Standarisasi Huruf | Text case standardisation — convert names to ALL CAPS, all lowercase, Proper Case (every word), Sentence Case (first word only); detect whether original text is all-lowercase / all-uppercase / mixed using EXACT comparison; capitalise both first and last character; normalise mixed-case school codes so the 2–3 letter school-type prefix (SD/SMP/SMA) is uppercase and the school name is Proper Case | `UPPER`, `LOWER`, `PROPER`, `REPLACE`, `EXACT`, `LEFT`, `RIGHT`, `LEN`, `TRIM` |

---

## 🟡 Medium Level — Exercise Summaries

| Code | Title | Scenario | Skills Covered |
|---|---|---|---|
| SBEM001 | Excel Test Kerja 1 | Payroll system — extract employee data from composite ID codes; calculate age, tenure, work grade, normal & overtime pay, allowances, and cash denomination breakdown | `LEFT`, `MID`, `IF`, `VLOOKUP`, `DATE` arithmetic |
| SBEM002 | Admin Toko Roti | Bakery voucher admin — parse voucher codes to identify buyer category, bread type, flavor, and purchase date; apply tiered discounts and produce sales summaries | `LEFT`, `MID`, `DATEDIF`, `VLOOKUP`, `SUMIF`, `COUNTIF` |
| SBEM003 | Admin Perpustakaan | Library rental system — look up book type and fee, calculate loan duration, late fines per day, and quantity discounts for 5+ books | `VLOOKUP`, `IF`, date arithmetic |
| SBEM004 | Latihan Soal Item Barang | Conditional aggregation — calculate totals by category and payment method without helper columns | `SUMIF`, `SUMPRODUCT`, `SUMIFS` |
| SBEM005 | Jumlah Siswa dan Rata-rata | Student statistics — universal drag-to-fill formulas counting students, averaging scores, finding max/min, counting above-80 scores, and filtering by vowel-initial names | `COUNTIFS`, `AVERAGEIFS`, `SUMIFS`, `FIND`, `ISNUMBER` |
| SBEM006 | Latihan Soal Tanggal Lahir | Date & generation data — derive day-of-week in Indonesian, zodiac sign, age, formatted birthplace+date string, generational label, next birthday date, and countdown in days | `CHOOSE`, `WEEKDAY`, `VLOOKUP`, `DATEDIF`, `TEXT`, `EDATE` |
| SBEM007 | Admin Tiket Pesawat | Airline ticket system — decode ticket codes for aircraft type, landing time, seat class, price per passenger type, totals, and tiered PSC agent fees | `MID`, `INDEX`/`MATCH`, nested `IF`, `HLOOKUP` |
| SBEM008 | Management Proyek | Project management tracker — calculate employee age, service duration, round work hours, and flag project status (Selesai / Berjalan / Akan Datang) | `DATEDIF`, `MOD`, `IF`, time arithmetic |
| SBEM009 | Mencari Huruf dan Email | Text & email parsing — find character positions (case-sensitive and insensitive); extract username, domain, and TLD from email addresses; classify job titles | `SEARCH`, `FIND`, `IFERROR`, `LEFT`, `RIGHT`, `LEN`, `ISNUMBER` |
| SBEM010 | Revenue dan Profit Penjualan | Sales analytics — net revenue, total profit, below-target count, average achievement rate, unit shortfall, highest profit, product lookup, and discount scenario analysis | `SUMPRODUCT`, `COUNTIF`, `AVERAGEIF`, `INDEX`/`MATCH` |
| SBEM011 | Packing Dus Pesanan | Box-packing logistics — boxes and loose pieces; extract order date/time; find next Saturday payment date; compute pcs shortage to next full box | `INT`, `MOD`, `WEEKDAY`, `IF` |
| SBEM012 | Mastering DATEDIF | DATEDIF deep dive — age in years/months/days; compound "X Tahun Y Bulan Z Hari" string suppressing zeros; 60th birthday and pension fund date | `DATEDIF` (Y/M/D/YM/MD), `IF`, `TEXT`, `DATE` |
| SBEM013 | Kiriman Se-Indonesia | Nationwide shipping admin — round weight to expedition units, calculate delivery duration across WIB/WITA/WIT time zones, extract payment method, compute shipping fees and promos | `HLOOKUP`/`XLOOKUP`, `ROUND`, `CEILING`, time zone offsets |
| SBEM014 | Admin Tiket Bioskop LXIX | Cinema ticket system — parse ticket codes for studio, platform, seat type, Roman numeral quantity, price by showtime, promo percentage, and sales channel | `MID`, `LEFT`, `RIGHT`, `VLOOKUP`, Roman numeral conversion |
| SBEM015 | IF AND OR NOT | Logic functions challenge — 7 conditional columns using exactly the allotted function budget (7× IF, 5× AND, 1× OR, 1× NOT); starred questions require AND/OR or the answer is voided | `IF`, `AND`, `OR`, `NOT` |

---

## 🟠 Hard Level — Exercise Summaries

| Code | Title | Scenario | Skills Covered |
|---|---|---|---|
| SBEH001 | Hari Libur Kerja | Payroll with custom work calendars — calculate working days for 17 employees across 7 different day-off schedules; compute actual attendance after absences; calculate full-year 2024 salary with per-day rate minus absence penalties | `NETWORKDAYS.INTL`, `COUNTIFS`, date arithmetic, custom weekend codes |
| SBEH002 | Multi Harga Grosir | Tiered wholesale pricing — look up product name, apply the correct price tier (3 tiers per product based on quantity thresholds), and apply the matching discount rate; no helper columns allowed | Nested `VLOOKUP`, `MATCH` with array `{3\4\5}`, `SUMPRODUCT` |
| SBEH003 | Latihan Soal NIK | Indonesian NIK parsing — extract gender, birthdate (female +40 day correction), age as of a fixed date, detect duplicate NIKs, assign payment by gender, sum total payments per NIK | `MID`, `DATE`, `MOD`, `DATEDIF`, `SUMPRODUCT`, `COUNTIF` |
| SBEH004 | Database Vertical | Vertical database lookup — extract Name, Family Name, and DOB from a vertically-structured SID database (5 rows per record); parse Join Date from the last 5 digits of SID; calculate tenure in complete weeks to a fixed reference date | `VLOOKUP` on vertical layout, `INDEX`/`MATCH`, `INT`, `LEFT`/`RIGHT`/`MID`, `DATEDIF` |
| SBEH005 | Transaksi Andi | Fuzzy name search in free-text transaction descriptions — count and sum transactions containing "andi" (excluding "yandi", "andini", etc.) using space-padded FIND; filter by exact transaction code; combine name and code filters in one formula | `SUMPRODUCT`, `ISNUMBER`, `FIND` with space padding, `COUNTIF`/`SUMIF` with tilde escape |
| SBEH006 | Mastering VLOOKUP | VLOOKUP mastery across 9 sub-exercises — basic exact and approximate lookup, multi-criteria lookup with concatenated keys, HLOOKUP, cross-sheet reference, and bonus tier assignment from a range table | `VLOOKUP` (TRUE/FALSE), `HLOOKUP`, `INDEX`/`MATCH`, multi-key concatenation, `IFERROR` |
| SBEH007 | Mastering Fungsi Logika | Logic functions across 12 columns — decode product codes to derive warehouse, origin city, product type, and color; assign shipping cost, bonus, and extra fees by condition; categorize sales trend; determine promo status vs today; grade by sales score | `IF`, `AND`, `OR`, `CHOOSE`, `SWITCH`, `IFS`, `MID`, `LEFT` |
| SBEH008 | Management Tanggal Proyek | Advanced project date management — calculate end date on Sun–Thu calendar (Fri/Sat off); count salary paydays (1st of each month); count Fridays; find first/last payday and Friday; compute 3-month review and 6-month end-of-month review dates; count even-date working days for boss visits | `WORKDAY.INTL`, `NETWORKDAYS.INTL`, `EDATE`, `EOMONTH`, `SUMPRODUCT`, `DAY`, `MOD`, `WEEKDAY` |
| SBEH009 | Data Pesanan Komplek | Unstructured order text parsing — extract buyer name from a free-text sentence to look up their residential block from a 100+ resident directory; cross-reference product and store name to find the price from a 10×5 matrix; assign delivery order by block sequence | `FIND`, `ISNUMBER`, `SUMPRODUCT`, `INDEX`/`MATCH`, `SEARCH`, nested `VLOOKUP` |
| SBEH010 | Game Seri A Liga Italia | Serie A football analytics — rank teams by points; compute SoT% and G/SoT (excluding penalties); tally last-5-match points from a W/D/L string; compute average attendance and stadium occupancy %; calculate total ticket revenue; sum yellow cards and max goals per player; count Italian-nationality players per team | `RANK`, `ROUND`, `SUMPRODUCT`, `LEN`, `SUBSTITUTE`, `MAXIFS`, `COUNTIF`, cross-sheet `SUMIF` |
| SBEH011 | MIN MAX Level Hard | Conditional MIN/MAX — find each employee's most recent work date (MAXIFS) and retrieve their latest hour total; compute gross salary with tiered overtime (Rp25,000/hr first 160 hrs, Rp35,000/hr beyond); add child allowance (max 3 kids); calculate insurance (5% gross, min Rp250,000); apply conditional bonus, infaq deduction, and tiered PPh tax | `MAXIFS`, `MINIFS`, `IF`, nested `MIN`/`MAX`, tiered calculation logic |
| SBEH012 | SLA Monitoring VISA | VISA SLA tracker — map VFS branch code to city and SLA days; calculate estimated completion using branch-specific opening schedules (Jakarta: Mon/Tue/Thu; Surabaya & Bandung: Mon–Fri; Bali: Tue/Thu/Sat) plus national holidays; compute remaining working days; assign status (Expired / Urgent / Proses); rank by urgency with no ties; validate apply date against branch schedule | `WORKDAY.INTL` with custom weekend masks, `NETWORKDAYS.INTL`, `IF`, `IFS`, `RANK`, `WEEKDAY`, holiday array |

---

## 🔴 Extreme Level — Exercise Summaries

| Code | Title | Scenario | Skills Covered |
|---|---|---|---|
| SBEX001 | VLOOKUP & HLOOKUP Extreme | Electronics sales — look up customer name (VLOOKUP), product name and unit price (VLOOKUP), compute total sales, apply tiered discount by QTY range (HLOOKUP), assign bonus item by QTY bracket (VLOOKUP), look up bonus price, calculate net sales; aggregate total and average QTY and net sales | `VLOOKUP`, `HLOOKUP`, `IF`, `SUM`, `AVERAGE` |
| SBEX002 | COUNTIF Extreme | Student dataset — count children with 3+ word names, count children from Bandung or Jakarta (single COUNTIF), count age range >3, count male (♂️) and female (♀️) students, count school transfer status (>) — all using exactly 1 COUNTIF per question; no helper columns | `COUNTIF` with wildcard `* * * |*`, array `{"Bandung";"Jakarta"}`, emoji wildcard `*♂️`, comparison operator in criteria |
| SBEX003 | LEFT MID RIGHT Extreme | Two sub-challenges — (1) extract variable-length alphanumeric code and 4-digit year from zero-padded strings with a dash separator; (2) split concatenated Name+Number strings where the name length is variable and no delimiter exists | `LEFT`, `MID`, `RIGHT`, `LEN`, `FIND`, `MIN`, `SEARCH` |
| SBEX004 | Total Terlambat | Attendance streak analysis — from a 31-day time-value attendance sheet: count on-time days (≤07:00), count late days (>07:00), find the longest consecutive-late streak, count how many times consecutive-late streaks occurred (≥2 days), compute total lateness points where isolated lates = 1 pt and each day in a streak after the first = 2 pts | `COUNTIF`, `LET`, `MAX`, `FREQUENCY`, `IF`, `COLUMN`, `SUMPRODUCT` — all as array formulas over time values |
| SBEX005 | Extract Transaksi | Unstructured bank transfer text parsing — extract Name (all-caps hyphenated words), transaction Value (standalone 5+ digit number), Date (from `tglN` token mapped to April 2025), and WS Code (alphanumeric after "WS") from 10 free-form transaction description strings with no fixed field order | `REGEXEXTRACT`, `SUBSTITUTE`, `VALUE`, `DATE`, `MID`, `FIND` |
| SBEX006 | Fungsi Text Extreme | Letter/certificate administration — clean and Proper-case raw names containing extra spaces and `CHAR(160)` non-breaking spaces; extract year (chars 7–10), month (chars 12–13), and day (last 2 chars) from padded letter codes; build a valid DATE; count letter "A" occurrences; extract two-letter initials; format Indonesian date stamp (DD-MMM-YYYY in Indonesian locale); classify scores into Cukup/Baik/Bagus; sensor names replacing middle characters with `*` — all using text functions only, no IF/VLOOKUP | `TRIM`, `SUBSTITUTE`, `CHAR`, `PROPER`, `MID`, `RIGHT`, `LEN`, `FIND`, `TEXT` with `[$-id-ID]` locale, `REPT`, `REPLACE`, `CONCAT` |
| SBEX007 | Data Karyawan & Slip Gaji (Anagram) | Anagram + Caesar Cipher employee lookup — input names are anagrams of real employee names; sort all characters alphabetically to generate a lookup key (TEXTJOIN + SORT + MID + SEQUENCE); match key against the same transformation of the employee table (BYROW + LAMBDA) to find City, DOB, Join Date; decode the job title column which is a Caesar Cipher (+1 shift) anagram, then reverse-shift all characters (MAP + LAMBDA + CODE + CHAR) to recover the original title; look up salary code, parse exponential notation (`G2E5` → number), compute total salary | `LET`, `XLOOKUP`, `BYROW`, `LAMBDA`, `MAP`, `TEXTJOIN`, `SORT`, `MID`, `SEQUENCE`, `LEN`, `SUBSTITUTE`, `CODE`, `CHAR`, `FIND`, `VALUE` |
| SBEX008 | Data Grid | Dynamic array grid analysis on a 30-column × 30-row number grid — (1) sum and (2) subtract multi-cell addresses from a semicolon-separated list using dynamic arrays; (3) rank top-15 row sums; (4) rank top-15 column sums; (5) rank top-15 rows by count of even numbers; (6) rank top-15 non-overlapping 2×2 block sums; (7) rank top-15 non-overlapping 4×4 block sums; (8) sum 10 diagonal cells D1–D10; no helper columns | `INDIRECT`, `MAP`, `LAMBDA`, `TEXTSPLIT`, `BYROW`, `BYCOL`, `MMULT`, `SEQUENCE`, `MOD`, `LARGE`, `RANK`, named range `Grid` |

---

## Skills Covered

| Category | Easy | Medium | Hard | Extreme |
|---|---|---|---|---|
| Arithmetic | `+`, `-`, `*`, `/`, `%`, `^` | | | |
| Aggregate | `SUM`, `AVERAGE`, `MAX`, `MIN`, `COUNT`, `PRODUCT` | `SUMIF`, `SUMIFS`, `COUNTIF`, `COUNTIFS`, `AVERAGEIF`, `AVERAGEIFS`, `SUMPRODUCT` | `MAXIFS`, `MINIFS` | `FREQUENCY`, array-formula aggregation |
| Logical | `IF`, nested `IF` | `AND`, `OR`, `NOT`, `IFS` | `SWITCH`, `CHOOSE` | |
| Lookup | `VLOOKUP`, `HLOOKUP` | `INDEX`/`MATCH`, `XLOOKUP`, multi-key concatenation | Vertical layout lookup, fuzzy match | Anagram key lookup, `BYROW`/`LAMBDA` dynamic match |
| Text | `LEFT`, `MID`, `RIGHT`, `LEN`, `TRIM`, `UPPER`, `LOWER`, `PROPER`, `EXACT`, `REPLACE`, `FIND`, `SEARCH` | `TEXT`, `ISNUMBER`, `IFERROR`, `&` | Space-padded FIND, tilde escape in SUMIF | `REGEXEXTRACT`, `SUBSTITUTE`, `REPT`, `CHAR`, `CODE`, `TEXTJOIN`, `TEXTSPLIT`, `CONCAT` |
| Date | `DATE`, `EDATE`, date arithmetic | `DATEDIF`, `WEEKDAY`, `CHOOSE`, `TEXT` locale, `EOMONTH` | `NETWORKDAYS.INTL`, `WORKDAY.INTL`, custom weekend codes, holiday arrays | Indonesian locale `TEXT` (`[$-id-ID]`), date from token parsing |
| Math | | `INT`, `MOD`, `ROUND`, `CEILING` | `RANK`, tiered rate calculation | `SEQUENCE`, `MMULT`, `LARGE`, grid block analysis |
| Dynamic Array | | | | `MAP`, `BYROW`, `BYCOL`, `LAMBDA`, `LET`, `SORT`, `INDIRECT`, named ranges |
| Cipher / Encoding | | | | Caesar Cipher decode (`CODE`/`CHAR` shift), exponential notation parsing (`G2E5` → number) |

---

## Repository Structure

```
excel-practice/
├── README.md
├── Easy
│  └── SBEE001 – SBEE012
├── Medium
│  └── SBEM001 – SBEM015
├── Hard
│  └── SBEH001 – SBEH012
├── Extreme
│  └── SBEX001 – SBEX008
└── Championship
```

Each file contains the original question sheet, an automated answer-checking sheet, and completed solutions. Open any file and navigate to the XL-Test sheet to verify answers.

## Source

All exercises are from [BelajarExcel.id — XL-Test](https://belajarexcel.id/xl-test/), a platform providing structured Excel practice with automated answer validation.
