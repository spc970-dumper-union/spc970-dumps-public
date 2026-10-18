## Mecha-LIBeration exploit dumps

Full SHA-256 hashes and verification details are available in [checksums.md](checksums.md).

### MechaCon v1.xx Series (MD 1.36 / MD 1.38) — 256 KiB ROM (CXP101064 / CXP102064)

| Mecha | Rev | Timestamp | Retail (JP) | DTL (Dev) | Chassis / Remarks |
| :--- | :---: | :---: | :---: | :---: | :--- |
| `1.02_0` | `1.193` | `2000-01-10 01:54:21+09` | ✅ **605R** / **001R** | — | A-chassis SCPH-10000 (Japan launch); **identical firmware** on CXP101064-605R and CXP102064-001R |
| `1.03_0` | `1.194` | `2000-01-13 14:17:00+09` | — | ✅ **602R** | A-chassis DTL-T10000, DTL-H10000 (v1, v3) |
| `1.07/08` | `1.6` | `2000-04-06 12:45:46+09` | ✅ **002R** (`1.08_0`) | ✅ **003R** (`1.07_0`) | A-chassis: 002R = SCPH-10K/15K GH-003 with RF-amp (blacklisted DVD-Player 1.00); 003R = DTL-H10000 v2 |
| `1.09_0` | `1.6` | `2000-10-13 21:22:24+09` | — | ✅ **751R** | A-chassis DTL-T10000H, DTL-T15000 |

### MechaCon v2.xx Series (MD 1.39) — 256 KiB ROM (CXP102064)

| Mecha | Rev | Timestamp | JP (`0xx`) | US (`1xx`) | EU (`2xx`) | AU (`3xx`) | Arcade (`6xx`) | DTL-H3000x | DTL-Hx010x | Chassis / Remarks |
| :--- | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :--- |
| `2.00_0` | `1.19` | `2000-06-22 16:11:26+09` | ✅ **004R** | — | — | — | — | — | — | early SCPH-15000/18000 (GH-003 Board) |
| `2.02_0` | `1.19` | `2000-07-04 21:12:51+09` | ✅ **005R** | — | — | — | — | — | ❌ 009R | A/A+ chassis SCPH-15000/18000 (radial auto-tilt motor), maybe DTL-H10100 |
| `2.04/05` | `1.27` | `2000-07-13 01:20:06+09` | — | ✅ **101R** | ✅ **201R** | ✅ **301R** | — | ❌ 702R | — | B and C chassis (SCPH-30001, SCPH-30002); 702R (v2.05_1, US region) used in DTL-H30001 and DTL-H30002 |
| `2.04_10` | `1.2` | `2000/08/04 07:00:31` | — | — | — | — | ✅ **651R** | — | — | Namco System 246 / 256, Konami Python 1 |
| `2.06/07` | `1.30` | `2000-09-20 21:31:39+09` | ❌ 006R? | ✅ **102R** | ✅ **202R** | ❌ 302R | — | ❌ 703R | — | C and D chassis (SCPH-30001, SCPH-30004); 703R (v2.07_1, US region) used in DTL-H30001 and DTL-H30002 |
| `2.12/13` | `1.36` | `2001-02-21 23:58:37+09` | ✅ **007R** | ✅ **103R** | ✅ **203R** | ❌ 303R | — | ✅ **752R** | — | D-chassis (SCPH-30000/1/4) & DTL-H30000 |
| `2.14` | `1.45` | `2001-04-18 22:16:12+09` | ✅ **008R** | ✅ **104R** | ❌ 204R | ❌ 304R | — | — | — | D-chassis (SCPH-30000, SCPH-30001) |
| `2.13` | `1.36` | `2003-06-16 18:26:05+09` | — | — | — | — | — | — | ✅ **705R** | All DTL-H3010x models (DEX Multi-region) |

### MechaCon v3.xx Series (MD 1.39) — 192 KiB Native ROM (CXP103049)

| Mecha | Rev | Timestamp | JP (`0xx`) | US (`1xx`) | EU (`2xx`) | AU (`3xx`) | Asia (`4xx`) | Russia (`5xx`) | Chassis / Remarks |
| :--- | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :--- |
| `3.00` | `3.12` | `2001-06-15 17:12:13+09` | — | ✅ **101GG** | — | — | — | — | F-chassis; SCPH-30001 R; separate EEPROM + RTC |
| `3.00` | `3.12` | `2001-07-23 20:24:31+09` | — | — | ✅ **201GG** | ✅ **301GG** | — | — | F-chassis; SCPH-30004 R, SCPH-30002 R |
| `3.02` | `3.13` | `2001-09-13 23:20:39+09` | ✅ **001GG** | ✅ **102GG** | ✅ **202GG** | ❌ 302GG | — | — | F-chassis; SCPH-30000, SCPH-30001/4 R; combined EEPROM + RTC |
| `3.04` | `3.14` | `2001-09-21 16:00:35+09` | — | — | — | — | ✅ **401GG** | — | F-chassis SCPH-30005/6/7 R (Asia), combined EEPROM + RTC |
| `3.06` | `3.24` | `2002-02-01 21:43:17+09` | ✅ **002GG** | ✅ **103GG** | ✅ **203GG** | ✅ **303GG** | ❌ 402GG | ✅ **501GG** | G-chassis; SCPH-37000 (early), SCPH-39000/1/2/3/4/5/6/7/8/10 |
| `3.08` | `3.30` | `2002-08-27 15:42:48+09` | ✅ **003GG** | — | — | — | ✅ **403GG** | — | G-chassis; SCPH-39000 (Japan) and SCPH-39005/6/7 (Asia), later units |
