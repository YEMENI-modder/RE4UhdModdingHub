# Companion DLL No 2x Allocation

**الوصف:** إصلاح مشكلة التخصيص المزدوج في DLL

**Description:** Fixes double allocation issue in Companion DLL

**Necessary Codes:**

- [APPLY DLL RAZ0R](apply_dll_raz0r.md)
- [POINTER EDIT](../necessary/pointer_edit.md)

**The code:**

```
BF 10 00 00 00 8B 45 08 8D B4 38 07 01 00 00 68
Change To
BF 10 00 00 00 8B 45 08 EB B8 90 90 90 90 90 68

-

Find : 002AA220
Paste : 8D B4 38 07 01 00 00 50 A1 00 0E 2E 10 85 C0 75 03 58 EB 39 8D 80 10 C7 00 00 89 04 24 83 E6 80 EB 33
```
