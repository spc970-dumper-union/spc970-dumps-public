## Mecha-LIBeration exploit dumps

### CXP101064 Series (v1.xx Firmware) — MD 1.36

| mecha | Revision | JP / DTL (`6xx`) | Chassis / Remarks |
| :--- | :---: | :---: | :--- |
| `1.02_0` |  | ❌ 605R | A-chassis SCPH-10000 (Japan) |
| `1.03_0` |  | ❌ 602R | A-chassis DTL-T10000, DTL-H10000 |

### CXP102064 Series (v1.xx Firmware) — MD 1.36/MD 1.38

| mecha | Revision | JP / DTL (`0xx`) | DTL (`75x`) | Chassis / Remarks |
| :--- | :---: | :---: | :---: | :--- |
| `1.06_0` |  | ❌ 001R | — | A-chassis SCPH-10000 with blacklisted DVD-Player 1.00 (GH-001, Japan) |
| `1.07_0` |  | ❌ 003R | — | A-chassis DTL-T10000, DTL-H10000 (GH-001) |
| `1.08_0` |  | ❌ 002R | — | A-chassis SCPH-15000 (GH-003 with Sony RF-amp) |
| `1.09_0` |  | — | ❌ 751R | A-chassis DTL-T10000H, DTL-T15000 |

### CXP102064 Series (v2.xx Firmware) — MD 1.39

| mecha | Revision | JP (`0xx`) | US (`1xx`) | EU (`2xx`) | AU (`3xx`) | Arcade (`6xx`) | DTL-H3000x (`70x`) | DTL-Hx010x (`75x`) | Chassis / Remarks |
| :--- | :---: | :---: |:----------:| :---: | :---: | :---: | :---: | :---: | :--- |
| `2.00 ?` |  | ❌ 004R? |     —      | — | — | — | — | — | early SCPH-15000/18000 (GH-003 Board)??? |
| `2.02_0` | `1.19` | ✅ **005R** |     —      | — | — | — | — | — | A/A+ chassis SCPH-15000/18000, AB-chassis SCPH-18000 |
| `2.04_10` | `1.2` | — |     —      | — | — | ✅ **651R** | — | — | Namco System 246 / 256 |
| `2.04/05` | `1.27` | — | ✅ **101R** | ✅ **201R** | ❌ 301R | — | ❌ 752R | ❌ 702R | B and C chassis |
| `2.06/07` | `1.30` | ❌ 006R?| ✅ **102R** | ✅ **202R** | ❌ 302R | — | — | ❌ 703R | C and D chassis |
| `2.12/13` | `1.36` | ✅ **007R** | ✅ **103R** | ✅ **203R** | ❌ 303R | — | — | ✅ **705R** | D-chassis |
| `2.14` | `1.45` | ✅ **008R** | ✅ **104R** | ❌ 204R | ❌ 304R | — | — | — | D-chassis |

### CXP103049 Series (v3.xx Firmware) — MD 1.39 

| mecha | Revision | JP (`0xx`) | US (`1xx`)  | EU (`2xx`) | AU (`3xx`) | Asia (`4xx`) | Russia (`5xx`) | Chassis / Remarks                                                                                                                                                                          |
| :--- | :---: | :---: |:-----------:| :---: | :---: | :---: |:--------------:| :--- |
| `3.00` | `3.12` | — | ✅ **101GG** | ✅ **201GG** | ❌ 301GG | — |       —        | F-chassis; SCPH-30001/2/3/4 R; separate EEPROM + RTC |
| `3.02` | `3.13` | ✅ **001GG** | ✅ **102GG** | ✅ **202GG** | ❌ 302GG | — |       —        | F-chassis; SCPH-30000 (Japan), SCPH-30001/2/3/4 R; combined EEPROM + RTC |
| `3.04_4` | `3.14` | — |      —      | — | — | ✅ **401GG** |       —        | F-chassis SCPH-30005/6/7 R (Asia), combined EEPROM+RTC |
| `3.06` | `3.24` | ✅ **002GG** | ✅ **103GG** | ✅ **203GG** | ❌ 303GG | ❌ 402GG |  ✅ **501GG**   | G-chassis; SCPH-37000 (Japan, earlier units), SCPH-39000/1/2/3/4/5/6/7/8/10 |
| `3.08` | — | ❌ 003GG |      —      | — | — | ❌ 403GG |       —        | G-chassis; SCPH-39000 (Japan) and SCPH-39005/6/7 (Asia), later units |

## Dump checksums

| Dump | SHA-256 | Build date | Author |
| :--- | :--- | :---: | :---: |
| `2.02_0.BIN` | `24f35a30c06e249ce92f32700e37a00b554c9220b9a96634dfb4574ce48f0589` | `2000-07-04` | `dai` |
| `2.02_2.BIN` | `a83862547484eaafe91f0396596a1cd1f5c7b8f364d9566001a10a0d0b580f5a` | `2000-07-13` | `dai` |
| `2.04_1.BIN` | `fde32c17c6f5ec611814b9a71606709be09b56da7a1ad9ef2d12b87c8846346d` | `2000-07-13` | `dai` |
| `2.04_10.BIN` | `75f58e288215141187de8591b466e9aa273bdb53e049d2606bd137957daf21d2` | `2000-08-04` | `inui` |
| `2.06_1.BIN` | `089ad12b0b44881af1b0649914925da2a9c46f79adacc5b7f6e2dcf84af03d10` | `2000-09-20` | `dai` |
| `2.06_2.BIN` | `620b61188e7d1e551c861c8b6f945010286968bd65a49d1da69bc7322590091f` | `2000-09-20` | `dai` |
| `2.12_0.BIN` | `5aedb863116a8708bf9ad7222c8410170a2508024b07de85051d158a61bf276f` | `2001-02-21` | `dai` |
| `2.12_1.BIN` | `c44ecac0335f006930c535bb568f0fc8477bd1167bbb0534d553dd9f61b40482` | `2001-02-21` | `dai` |
| `2.12_2.BIN` | `f505a5525347acf3adb86661dcccc6deedbe167bc762442eb04688b00da4d57d` | `2001-02-21` | `dai` |
| `2.13_0.BIN` | `ca497983a4b74331825589ccbf4e345e3f374b806f5bd98b45bfb4a17f746b5d` | `2003-06-16` | `dai` |
| `2.14_0.BIN` | `8a9ecb6f4d03be40e8e1b90ed4144bb2a53bf79c3f0f81b32936290a8828a306` | `2001-04-18` | `dai` |
| `2.14_1.BIN` | `d6340c57b9b0ce32192454a09321ecba072d898c8b17e88152a7cb61e2b9b1e1` | `2001-04-18` | `dai` |
| `3.00_1.BIN` | `cfeb9f4d7dc96ed8e5bfcf751e9d4c40614cbefa6918a7a210ed220cf7f064df` | `2001-06-15` | `dai` |
| `3.00_2.BIN` | `0138ad7b825239a09e61bb7ad200a48eff7744e62ebe6147539c13db168fb6d5` | `2001-07-23` | `dai` |
| `3.02_0.BIN` | `3cb542343534f94af72f63831f6a61e894e6d107128b448ca7bed4e2ae447094` | `2001-09-13` | `dai` |
| `3.02_1.BIN` | `45b2bdb3b44c623c05076113932a280e62e5f91703e44047227d963678bb273d` | `2001-09-13` | `dai` |
| `3.02_2.BIN` | `84b7f045f74344074fab53780fd71c0c32ac103d6103685b095f790676fa09d0` | `2001-09-13` | `dai` |
| `3.04_4.BIN` | `02cb3d13423409706aa57d34dac404f331d1f869acdef75afbcc2610c95f93b4` | `2001-09-21` | `dai` |
| `3.06_0.BIN` | `6481048108f8de9085406a75c8b3f8ae2e0e237bcd76a7ae35f7f0c2bd8d515c` | `2002-02-01` | `dai` |
| `3.06_1.BIN` | `d4662c30d99c98b72d3d5b77986ca74e9d36df2dbb4eaad5f63b787722ef7a2b` | `2002-02-01` | `dai` |
| `3.06_2.BIN` | `15b4dd3997c06bc229e98b2c0028d1be8e6651a924780ee201c84612d95d4cf2` | `2002-02-01` | `dai` |
| `3.06_5.BIN` | `6230a06a608ab450e37a1cecf796c54e89508e274c91fa8a3c0acd5386a007e4` | `2002-02-01` | `dai` |
