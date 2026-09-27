# Verdugo No Teleport (raz0r version)

**الوصف:** فيردوقو ما يختفي - نسخة raz0r

**Description:** Verdugo does not teleport (raz0r version)

**Necessary Codes:**

- [APPLY DLL RAZ0R](apply_dll_raz0r.md)
- [POINTER EDIT](../necessary/pointer_edit.md)

**The code:**

```
D8 9F 78 03 00 00 DF E0 F6 C4 41 75 10 33 C0 8B
Change To
EB A8 90 90 90 90 DF E0 F6 C4 41 75 10 33 C0 8B

-

Find : 000C2440
Paste : 50 A1 00 0E 2E 10 66 81 B8 AC 4F 00 00 21 02 75 09 D8 9F 78 03 00 00 58 EB 42 58 EB 46
```
