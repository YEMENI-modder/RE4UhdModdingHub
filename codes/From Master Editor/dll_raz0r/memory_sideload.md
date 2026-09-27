# Double File Load Fix

**الوصف:** يصلح مشكلة تحميل ملفات الـ DLL مرتين

**Description:** Fixes Companion DLL double file loading issue

**Necessary Codes:**

- [APPLY DLL RAZ0R](apply_dll_raz0r.md)

**The code:**

```
55 8B EC 83 EC 44 6A 29 68 FF 00 00 00
Change To
55 8B EC 83 EC 44 6A 29 E9 8B 09 00 00

-

Find : 002D8A18
Paste : C7 05 EF C8 26 10 E9 F7 01 00 C7 05 F3 C8 26 10 00 90 83 7E C7 05 61 B5 26 10 E9 C5 18 00 C7 05 65 B5 26 10 00 90 90 75 C7 05 EE 17 27 10 E9 7D 0A 08 C7 05 F2 17 27 10 00 83 BE 28 C7 05 70 22 2F 10 E8 0B 92 F7 C7 05 74 22 2F 10 FF 6A 00 6A C7 05 78 22 2F 10 00 6A 01 8B C7 05 7C 22 2F 10 CE E8 FE 91 C7 05 80 22 2F 10 F7 FF E9 6C C7 05 84 22 2F 10 F5 F7 FF 90 68 FF 00 00 00 E9 F3 F5 FF FF
```
