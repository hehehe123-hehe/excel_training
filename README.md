# 📊 Excel Practice — Level Complete

A documented collection of completed Excel exercises from BelajarExcel.id, covering real-world administrative scenarios from payroll and sales administration to text manipulation and housing credit calculations.

## About This Repository

This repository documents my progress through a structured Excel practice platform. Every exercise file has been completed and is included here as-is — each `.xlsx` file contains its own automated answer-checking system (the platform's XL-Test engine), so the correctness of each solution can be verified directly by opening the file.

The exercises simulate real workplace data scenarios: employee payroll, sales reporting, ticket booking systems, document administration, and financial calculations. All 15 Medium-level exercises are complete. Hard through Championship levels are the next target.

## Progress

| Level | Exercises | Status |
|---|---|---|
| 🟢 Easy | 12 / 12 | ✅ Complete |
| 🟡 Medium | 15 / 15 | ✅ Complete |
| 🟠 Hard | 0 / 12 | ⏳ Planned |
| 🔴 Extreme | 0 / 8 | ⏳ Planned |
| 🏆 Championship | 0 / 5 | ⏳ Planned |

## Exercise Summaries — Medium Level

| Code | Title | Skills Covered |
|---|---|---|
| SBEM001 | Excel Test Kerja 1 | Payroll system — extract employee data from composite ID codes; calculate age, tenure, work grade, normal & overtime pay, allowances, and cash denomination breakdown using LEFT, MID, IF, VLOOKUP, DATE arithmetic |
| SBEM002 | Admin Toko Roti | Bakery voucher admin — parse voucher codes to identify buyer category, bread type, flavor, and purchase date; apply tiered discounts and produce sales summaries using LEFT, MID, DATEDIF, VLOOKUP, SUMIF, COUNTIF |
| SBEM003 | Admin Perpustakaan | Library rental system — look up book type and fee from code, calculate loan duration, late fines per day, and quantity discounts for borrowing 5+ books using VLOOKUP, IF, date arithmetic |
| SBEM004 | Latihan Soal Item Barang | Conditional aggregation — calculate total spending excluding food, food-only totals, and payment-method-filtered sums without helper columns using SUMIF, SUMPRODUCT, SUMIFS |
| SBEM005 | Jumlah Siswa dan Rata-rata | Student statistics — write a single universal formula (drag-to-fill) to count students, average scores, find max/min, count above-80 scores, and filter by vowel-initial names across class groups using COUNTIFS, AVERAGEIFS, SUMIFS, FIND, ISNUMBER |
| SBEM006 | Latihan Soal Tanggal Lahir | Date & generation data — derive day-of-week in Indonesian, zodiac sign from a lookup table, age in years, formatted birthplace + date string, generational label (Baby Boomer → Alpha), next birthday date, and countdown in days using CHOOSE, WEEKDAY, VLOOKUP, DATEDIF, TEXT, EDATE |
| SBEM007 | Admin Tiket Pesawat | Airline ticket system — decode ticket codes to determine aircraft type, calculate landing time from departure + route duration, construct origin-destination label, assign seat class, price per passenger type, compute totals, and apply tiered PSC agent fees using MID, INDEX/MATCH, nested IF, HLOOKUP |
| SBEM008 | Management Proyek | Project management tracker — calculate employee age, years/months/days of service, round work duration to nearest hour, and flag project status as Selesai / Sedang Berjalan / Akan Datang using DATEDIF, MOD, IF, time arithmetic |
| SBEM009 | Mencari Huruf dan Email | Text & email parsing — find the first position of "A" (case-insensitive), "a" (lowercase), and "A" (uppercase) in names; extract username, domain, and TLD from email addresses; classify job titles containing "Manager" using SEARCH, FIND, IFERROR, LEFT, RIGHT, LEN, ISNUMBER |
| SBEM010 | Revenue dan Profit Penjualan | Sales analytics — compute Net Revenue (after discount), total profit, count products below target, average target achievement rate, total unmet unit shortfall, highest single-product profit, product name lookup, and scenario analysis with a 3% discount reduction using SUMPRODUCT, COUNTIF, AVERAGEIF, INDEX/MATCH |
| SBEM011 | Packing Dus Pesanan | Box-packing logistics — calculate how many boxes (42 pcs each) and remaining loose pieces; extract order date and time; find the next Saturday payment date; compute pcs inside boxes, shortage to next full box, and total unprocessed pcs using INT, MOD, WEEKDAY, IF |
| SBEM012 | Mastering DATEDIF | DATEDIF deep dive — display age in full years, total months, total days, and a compound "X Tahun Y Bulan Z Hari" string suppressing zero units; calculate 60th birthday date and a derived pension fund date using DATEDIF with Y/M/D/YM/MD modes, IF, TEXT, DATE |
| SBEM013 | Kiriman Se-Indonesia | Nationwide shipping admin — round shipment weight to expedition units (min 1 kg), calculate delivery duration in days and remaining minutes across WIB/WITA/WIT time zones, extract payment method from resi code, and compute shipping fees and promos from a dynamic table using HLOOKUP/XLOOKUP, ROUND, CEILING, time zone offsets |
| SBEM014 | Admin Tiket Bioskop LXIX | Cinema ticket system — parse ticket codes (studio, platform, seat number, seat type, quantity in Roman numerals) to fill studio name, film duration, seat category, seat number and aisle, price by showtime, ticket count, promo percentage, total payment, and sales channel using MID, LEFT, RIGHT, VLOOKUP, Roman numeral conversion |
| SBEM015 | IF AND OR NOT | Logical functions challenge — complete 7 conditional columns (grade remarks, extra assignment, pass/fail, distinction, remedial, attendance rating, scholarship eligibility) using exactly the allotted function budget: 7× IF, 5× AND, 1× OR, 1× NOT; starred questions require AND or OR or the answer is voided |

## Skills Covered

| Category | Functions |
|---|---|
| Arithmetic | `+ - * / ^`, operator precedence, percentage |
| Aggregate | `SUM`, `AVERAGE`, `MAX`, `MIN`, `COUNT`, `COUNTA`, `PRODUCT` |
| Conditional Aggregate | `SUMIF`, `SUMIFS`, `COUNTIF`, `COUNTIFS`, `AVERAGEIF`, `AVERAGEIFS`, `SUMPRODUCT` |
| Logical | `IF`, nested `IF`, `AND`, `OR`, `NOT`, multi-condition logic |
| Lookup | `VLOOKUP`, `HLOOKUP`, `INDEX`/`MATCH`, `XLOOKUP` |
| Text | `LEFT`, `MID`, `RIGHT`, `LEN`, `TRIM`, `UPPER`, `LOWER`, `PROPER`, `EXACT`, `&`, `TEXT`, `FIND`, `SEARCH`, `ISNUMBER`, `IFERROR` |
| Date | `DATE`, `DATEDIF`, `EDATE`, `WEEKDAY`, `CHOOSE`, date arithmetic, time zone conversion |
| Math | `INT`, `MOD`, `ROUND`, `CEILING` |
| Special | Roman numeral decoding, time rounding, cross-zone duration |

## Repository Structure

```
excel-practice/
├── README.md
├── Easy
│  └── SBEE001 – SBEE012
├── Medium
│  └── SBEM001
│  └── SBEM002
│  └── SBEM003
│  └── SBEM004
│  └── SBEM005
│  └── SBEM006
│  └── SBEM007
│  └── SBEM008
│  └── SBEM009
│  └── SBEM010
│  └── SBEM011
│  └── SBEM012
│  └── SBEM013
│  └── SBEM014
│  └── SBEM015
├── Hard
├── Extreme
└── Championship
```

Each file contains the original question sheet, an automated answer-checking sheet, and my completed solutions. Opening any file and navigating to the XL-Test sheet will show which answers are marked correct.

## Source

All exercises are from [BelajarExcel.id — XL-Test](https://belajarexcel.id/xl-test/), a platform providing structured Excel practice with automated answer validation.
