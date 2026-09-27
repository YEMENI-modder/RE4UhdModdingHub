# Automatic Key Unlock

**الوصف:** ينفتح الباب بالمفتاح بدون ما تدخل الشنطه

**Description:** Door opens with key without entering inventory

**Necessary Codes:**

- [APPLY DLL RAZ0R](apply_dll_raz0r.md)

**The code:**

```
66 8B C7 5F 5E 5B 8B E5 5D C2 04
Change To
E9 A7 FA FF FF 5B 8B E5 5D C2 04

-

Find : 003046A0
Paste : 66 89 F8 66 85 C0 74 18 81 7D 04 12 A5 27 10 75 0F 66 81 7D 0A FF FF 75 07 66 31 C0 66 89 59 08 5F 5E E9 32 05 00 00
```
