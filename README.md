# 📊 Excel Practice — Progress Log

A documented collection of completed Excel exercises from BelajarExcel.id XL-Test, covering real-world administrative scenarios from basic arithmetic and payroll to complex date engineering, SLA monitoring, and football analytics.

## Progress

| Level | Exercises | Status |
|---|---|---|
| 🟢 Easy | 12 / 12 | ✅ Complete |
| 🟡 Medium | 15 / 15 | ✅ Complete |
| 🟠 Hard | 12 / 12 | ✅ Complete |
| 🔴 Extreme | 0 / 8 | ⏳ Planned |
| 🏆 Championship | 0 / 5 | ⏳ Planned |

---

## 🟢 Easy Level (⭐)

| Code | Title | Scenario | Skills Covered |
|---|---|---|---|
| SBEE001 | Operator Matematika | Basic arithmetic across 8 columns — add two order quantities, subtract cancellations, multiply by price, divide for cancellation rate, apply 5% tax, raise to power, apply 25% discount, and compute profit using correct operator precedence | `+`, `-`, `*`, `/`, `^`, `%`, operator precedence |
| SBEE002 | Fungsi Matematika | Aggregate function drills — SUM and subtraction-from-base for addition/subtraction series; PRODUCT and divide-from-base for multiplication/division series; all applied to 20-value rows | `SUM`, `PRODUCT`, sequential subtraction, sequential division |
| SBEE003 | VLOOKUP & HLOOKUP Penjualan Sederhana | Building store sales data — look up customer name with VLOOKUP and product name + unit price with HLOOKUP; apply tiered quantity discounts (10% above 200 units, 20% above 500); compute net sales; aggregate total and average QTY and net revenue | `VLOOKUP`, `HLOOKUP`, `IF`, `SUM`, `AVERAGE` |
| SBEE004 | Admin Data Mahasiswa | Student admin system — extract graduation year from NPM code with MID; look up faculty from a 5-entry table with VLOOKUP; derive campus branch, scholarship discount rate, and graduation fee from the last digit of NPM using nested IF; compute final fee after discount | `MID`, `VALUE`, `VLOOKUP`, `LEFT`, `RIGHT`, nested `IF` |
| SBEE005 | Admin Tiket Kereta Api | Train ticket system — decode a 4-character ticket code to extract seat class (first 3 chars, HLOOKUP) and passenger type (4th char, VLOOKUP); look up the correct fare from a 2D price matrix; apply 10% early-bird discount for departures before 1 Sep 2023; compute net fare | `HLOOKUP`, `VLOOKUP`, `MID`, `LEFT`, `MATCH`, `IF`, `DATE` |
| SBEE006 | Admin Gaji Sederhana | Simple payroll — decode an employee code to determine job title (MID, nested IF), marital status (RIGHT, IF), and division + base salary (LEFT, VLOOKUP from a 4-division table); compute child allowance (Rp25,000/child, married only); aggregate total, max, min, average salary and headcount | `MID`, `RIGHT`, `LEFT`, `IF`, `VLOOKUP`, `SUM`, `MAX`, `MIN`, `AVERAGE`, `COUNT` |
| SBEE007 | Admin Toko Penjualan | Electronics shop admin — decode a product code to extract item name (LEFT, VLOOKUP) and brand (RIGHT, VLOOKUP); compute cost price by multiplying a 2-digit rate from the code by a currency exchange rate (VLOOKUP from 5-currency table); apply 25% margin; assign tiered discount (0%–25%) and conditional bonus prize; compute net sales; aggregate weekly totals | `LEFT`, `RIGHT`, `MID`, `VLOOKUP`, `IF`, `AND`, `SUM`, `MAX`, `MIN`, `AVERAGE` |
| SBEE008 | Gaji Sederhana | Employee allowance calculator — assign base salary by grade (A/B/C) with nested IF; compute child allowance capped at 2 children (Rp300,000/child); set family allowance by marital status; assign position allowance based on years of service (≥6 years = Rp1,000,000); compute transport allowance at 7.5% of base salary | `IF`, `MIN` for cap, percentage calculation |
| SBEE009 | Kredit Perumahan | Housing loan system — look up land area, selling price, and PPn tax rate from a 5-product table; compute total price, down payment, monthly principal, monthly interest (from HLOOKUP rate table), monthly installment, total credit cost, and loan maturity date | `VLOOKUP`, `HLOOKUP`, `EDATE`, date arithmetic, percentage calculations |
| SBEE010 | Fungsi Text / String | Document & name string operations — classify letter type from first character; extract year, month, and date from a padded code string; reconstruct a valid date; insert "FL" suffix into a code with REPLACE; clean messy names with TRIM + PROPER; count character length; extract two-letter initials; build an Indonesian-locale date stamp (e.g. 19AGU2024) | `IFS`, `MID`, `RIGHT`, `TRIM`, `REPLACE`, `PROPER`, `LEN`, `LEFT`, `FIND`, `TEXT` with Indonesian locale, `DATE`, `UPPER` |
| SBEE011 | Gaji dan Potongan | Government payroll with deductions — look up base salary, allowance, and daily meal rate by education level (VLOOKUP/HLOOKUP from a 4-tier table); compute monthly meal allowance (×25 working days); look up tax rate by education (HLOOKUP); apply disciplinary deductions (Berat/Sedang/Ringan/Nihil) and work-time deductions (T1–T5 tiers) from total salary; compute take-home pay; aggregate totals and average tax | `VLOOKUP`, `HLOOKUP`, `IF`, `SUM`, `AVERAGE` |
| SBEE012 | Standarisasi Huruf | Text case standardization — convert raw names to ALL CAPS, all lowercase, Proper Case, Sentence case; detect case type (Huruf Besar / Huruf Kecil / Huruf Campur) using EXACT; capitalize first and last character only; standardize school names by uppercasing the level prefix (SD/SMP/SMA) while proper-casing the school name | `UPPER`, `LOWER`, `PROPER`, `EXACT`, `REPLACE`, `LEFT`, `RIGHT`, `LEN`, `TRIM`, `IF` |

---

## 🟡 Medium Level (⭐⭐)

| Code | Title | Scenario | Skills Covered |
|---|---|---|---|
| SBEM001 | Excel Test Kerja 1 | Payroll system — extract employee data from composite ID codes; calculate age, tenure, work grade, normal & overtime pay, allowances, and cash denomination breakdown | `LEFT`, `MID`, `IF`, `VLOOKUP`, `DATE` arithmetic |
| SBEM002 | Admin Toko Roti | Bakery voucher admin — parse voucher codes to identify buyer category, bread type, flavor, and purchase date; apply tiered discounts and produce sales summaries | `LEFT`, `MID`, `DATEDIF`, `VLOOKUP`, `SUMIF`, `COUNTIF` |
| SBEM003 | Admin Perpustakaan | Library rental system — look up book type and fee from code; calculate loan duration, late fines per day, and quantity discounts for borrowing 5+ books | `VLOOKUP`, `IF`, date arithmetic |
| SBEM004 | Latihan Soal Item Barang | Conditional aggregation — calculate total spending excluding food, food-only totals, and payment-method-filtered sums without helper columns | `SUMIF`, `SUMPRODUCT`, `SUMIFS` |
| SBEM005 | Jumlah Siswa dan Rata-rata | Student statistics — write a single drag-to-fill formula to count students, average scores, find max/min, count above-80 scores, and filter by vowel-initial names across class groups | `COUNTIFS`, `AVERAGEIFS`, `SUMIFS`, `FIND`, `ISNUMBER` |
| SBEM006 | Latihan Soal Tanggal Lahir | Date & generation data — derive day-of-week in Indonesian, zodiac sign, age, formatted birthplace + date string, generational label, next birthday, and countdown in days | `CHOOSE`, `WEEKDAY`, `VLOOKUP`, `DATEDIF`, `TEXT`, `EDATE` |
| SBEM007 | Admin Tiket Pesawat | Airline ticket system — decode ticket codes to determine aircraft type, calculate landing time, construct route label, assign seat class, price per passenger type, compute totals, and apply tiered PSC agent fees | `MID`, `INDEX`/`MATCH`, nested `IF`, `HLOOKUP` |
| SBEM008 | Management Proyek | Project management tracker — calculate employee age, years/months/days of service, round work duration to nearest hour, and flag project status as Selesai / Sedang Berjalan / Akan Datang | `DATEDIF`, `MOD`, `IF`, time arithmetic |
| SBEM009 | Mencari Huruf dan Email | Text & email parsing — find position of "A" in multiple case modes; extract username, domain, and TLD from email addresses; classify job titles containing "Manager" | `SEARCH`, `FIND`, `IFERROR`, `LEFT`, `RIGHT`, `LEN`, `ISNUMBER` |
| SBEM010 | Revenue dan Profit Penjualan | Sales analytics — compute Net Revenue, total profit, count products below target, average achievement rate, total unit shortfall, highest single-product profit, product lookup, and discount scenario analysis | `SUMPRODUCT`, `COUNTIF`, `AVERAGEIF`, `INDEX`/`MATCH` |
| SBEM011 | Packing Dus Pesanan | Box-packing logistics — calculate boxes (42 pcs each) and loose pieces; extract order date and time; find the next Saturday payment date; compute pcs inside boxes, shortage to next full box, and total unprocessed pcs | `INT`, `MOD`, `WEEKDAY`, `IF` |
| SBEM012 | Mastering DATEDIF | DATEDIF deep dive — display age in full years, total months, total days, and compound "X Tahun Y Bulan Z Hari" string suppressing zero units; calculate 60th birthday and pension fund date | `DATEDIF` (Y/M/D/YM/MD modes), `IF`, `TEXT`, `DATE` |
| SBEM013 | Kiriman Se-Indonesia | Nationwide shipping admin — round shipment weight to expedition units, calculate delivery duration across WIB/WITA/WIT time zones, extract payment method from resi code, and compute shipping fees and promos | `HLOOKUP`/`XLOOKUP`, `ROUND`, `CEILING`, time zone offsets |
| SBEM014 | Admin Tiket Bioskop LXIX | Cinema ticket system — parse ticket codes for studio, platform, seat type, quantity in Roman numerals; assign price by showtime; compute total payment and promo; identify sales channel | `MID`, `LEFT`, `RIGHT`, `VLOOKUP`, Roman numeral conversion |
| SBEM015 | IF AND OR NOT | Logical functions challenge — complete 7 conditional columns (grade remarks, extra assignment, pass/fail, distinction, remedial, attendance rating, scholarship eligibility) using an exact allotted function budget: 7× IF, 5× AND, 1× OR, 1× NOT | `IF`, `AND`, `OR`, `NOT` |

---

## 🟠 Hard Level (⭐⭐⭐)

| Code | Title | Scenario | Skills Covered |
|---|---|---|---|
| SBEH001 | Hari Libur Kerja | Payroll with custom work calendars — calculate working days for 17 employees across 7 different day-off schedules; compute actual attendance after absences; calculate full-year 2024 salary with per-day rate minus absence penalties | `NETWORKDAYS.INTL`, `COUNTIFS`, date arithmetic, custom weekend codes |
| SBEH002 | Multi Harga Grosir | Tiered wholesale pricing — look up product name, apply the correct price tier (3 tiers per product based on quantity thresholds), and apply the matching discount rate; no helper columns allowed | Nested `VLOOKUP`, `MATCH` with array `{3\4\5}`, `SUMPRODUCT` |
| SBEH003 | Latihan Soal NIK | Indonesian NIK parsing — extract gender, birthdate (female +40 day correction), age as of a fixed date, detect duplicate NIKs, assign payment by gender, sum total payments per NIK | `MID`, `DATE`, `MOD`, `DATEDIF`, `SUMPRODUCT`, `COUNTIF` |
| SBEH004 | Database Vertical | Vertical database lookup — extract Name, Family Name, and DOB from a vertically-structured SID database (5 rows per record); parse Join Date from the last 5 digits of SID; calculate tenure in complete weeks to a fixed reference date | `VLOOKUP` on vertical layout, `INDEX`/`MATCH`, `INT`, `LEFT`/`RIGHT`/`MID`, `DATEDIF` |
| SBEH005 | Transaksi Andi | Fuzzy name search in free-text transaction descriptions — count and sum transactions containing "andi" (excluding "yandi", "andini", etc.) using space-padded FIND; filter by exact transaction code; combine name and code filters in one formula | `SUMPRODUCT`, `ISNUMBER`, `FIND` with space padding, `COUNTIF`/`SUMIF` with tilde escape `~*PKA*~` |
| SBEH006 | Mastering VLOOKUP | VLOOKUP mastery across 9 sub-exercises — basic exact and approximate lookup, multi-criteria lookup with concatenated keys, HLOOKUP, cross-sheet reference, and bonus tier assignment from a range table | `VLOOKUP` (TRUE/FALSE), `HLOOKUP`, `INDEX`/`MATCH`, multi-key concatenation, `IFERROR` |
| SBEH007 | Mastering Fungsi Logika | Logic functions across 12 columns — decode product codes to derive warehouse, origin city, product type, and color; assign shipping cost, bonus, and extra fees by condition; categorize sales trend; determine promo status vs today; grade by sales score | `IF`, `AND`, `OR`, `CHOOSE`, `SWITCH`, `IFS`, `MID`, `LEFT` |
| SBEH008 | Management Tanggal Proyek | Advanced project date management — calculate end date on Sun–Thu calendar (Fri/Sat off); count salary paydays (1st of each month); count Fridays; find first/last payday and Friday; compute 3-month review and 6-month end-of-month review dates; count even-date working days for boss visits | `WORKDAY.INTL`, `NETWORKDAYS.INTL`, `EDATE`, `EOMONTH`, `SUMPRODUCT`, `DAY`, `MOD`, `WEEKDAY` |
| SBEH009 | Data Pesanan Komplek | Unstructured order text parsing — extract buyer name from a free-text sentence to look up their residential block from a 100+ resident directory; cross-reference product and store name to find the price from a 10×5 matrix; assign delivery order by block sequence | `FIND`, `ISNUMBER`, `SUMPRODUCT`, `INDEX`/`MATCH`, `SEARCH`, nested `VLOOKUP` |
| SBEH010 | Game Seri A Liga Italia | Serie A football analytics — rank teams by points; compute SoT% and G/SoT (excluding penalties); tally last-5-match points from a W/D/L string; compute average attendance and stadium occupancy %; calculate total ticket revenue; sum yellow cards and max goals per player; count Italian-nationality players per team | `RANK`, `ROUND`, `SUMPRODUCT`, `LEN`, `SUBSTITUTE`, `MAXIFS`, `COUNTIF`, cross-sheet `SUMIF` |
| SBEH011 | MIN MAX Level Hard | Conditional MIN/MAX — find each employee's most recent work date (MAXIFS) and retrieve their latest hour total; compute gross salary with tiered overtime (Rp25,000/hr first 160 hrs, Rp35,000/hr beyond); add child allowance (max 3 kids); calculate insurance (5% gross, min Rp250,000); apply conditional bonus, infaq deduction, and tiered PPh tax | `MAXIFS`, `MINIFS`, `IF`, nested `MIN`/`MAX`, tiered calculation logic |
| SBEH012 | SLA Monitoring VISA | VISA SLA tracker — map VFS branch code to city and SLA days; calculate estimated completion using branch-specific schedules (Jakarta: Mon/Tue/Thu; Surabaya & Bandung: Mon–Fri; Bali: Tue/Thu/Sat) plus national holidays; compute remaining working days; assign status (Expired / Urgent / Proses); rank by urgency with no ties; validate apply date against branch schedule | `WORKDAY.INTL` with custom weekend masks, `NETWORKDAYS.INTL`, `IF`, `IFS`, `RANK`, `WEEKDAY`, holiday array |

---

## Skills Covered

| Category | Functions & Techniques |
|---|---|
| Arithmetic | `+`, `-`, `*`, `/`, `^`, `%`, operator precedence, percentage calculations |
| Aggregate | `SUM`, `AVERAGE`, `MAX`, `MIN`, `COUNT`, `COUNTA`, `PRODUCT` |
| Conditional Aggregate | `SUMIF`, `SUMIFS`, `COUNTIF`, `COUNTIFS`, `AVERAGEIF`, `AVERAGEIFS`, `SUMPRODUCT`, `MAXIFS`, `MINIFS` |
| Logical | `IF`, nested `IF`, `AND`, `OR`, `NOT`, `IFS`, `SWITCH`, `CHOOSE` |
| Lookup | `VLOOKUP`, `HLOOKUP`, `INDEX`/`MATCH`, `XLOOKUP`, multi-key concatenation, vertical database layout |
| Text | `LEFT`, `MID`, `RIGHT`, `LEN`, `TRIM`, `UPPER`, `LOWER`, `PROPER`, `EXACT`, `REPLACE`, `TEXT`, `FIND`, `SEARCH`, `ISNUMBER`, `IFERROR`, `&`, space-padded fuzzy match, tilde escape, Indonesian locale date format |
| Date | `DATE`, `DATEDIF`, `EDATE`, `EOMONTH`, `WEEKDAY`, `CHOOSE`, `MOD`, `DAY`, date arithmetic, time zone conversion |
| Date & Calendar (Advanced) | `NETWORKDAYS.INTL`, `WORKDAY.INTL`, custom weekend codes, national holiday arrays |
| Math | `ROUND`, `CEILING`, `INT`, `MOD`, `RANK`, tiered rate calculation, Roman numeral decoding |
| Date Parsing | NIK birthdate extraction, serial date arithmetic |

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
└── Championship
```

Each file contains the original question sheet, an automated answer-checking sheet, and completed solutions. Open any file and navigate to the XL-Test sheet to verify answers.

## Source

All exercises are from [BelajarExcel.id — XL-Test](https://belajarexcel.id/xl-test/), a platform providing structured Excel practice with automated answer validation.
