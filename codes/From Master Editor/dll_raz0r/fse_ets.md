# FSE-ETS

**الوصف:** تربط FSE ب ETS - Offset[128..131] use ETS id HERE

**Description:** Links FSE with ETS - Offset[128..131] use ETS id

**Necessary Codes:**

- [APPLY DLL RAZ0R](apply_dll_raz0r.md)

**The code:**

```
66 89 86 24 03 00 00 81 A6 6C 06 00 00 FF FF FF
Change To
EB 6F 90 90 90 90 90 81 A6 6C 06 00 00 FF FF FF

-

0F B6 4A 01 33 C0 49 74 17 49 74 05 49 74 00 5D
Change To
EB B0 90 90 33 C0 49 74 17 49 74 05 49 74 00 5D

-

Find : 0018A718
Paste : 0F B6 4A 01 80 7A 6F 00 74 48 50 8A 42 6F 38 05 00 0F 2E 10 74 03 58 EB 39 C6 42 31 00 C6 05 00 0F 2E 10 00 EB F0

-

Find : 001E3708
Paste : 66 89 86 24 03 00 00 80 BE 65 06 00 00 00 75 02 EB 84 50 8A 86 65 06 00 00 A2 00 0F 2E 10 58 EB EF
```
