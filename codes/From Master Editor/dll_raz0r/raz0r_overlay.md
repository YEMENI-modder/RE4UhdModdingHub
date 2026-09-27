# Raz0r DLL Overlay Removal

**الوصف:** ازاله الصوره الذي تظهر اول ما تدخل اللعبه

**Description:** Removes the overlay shown at game start

**Necessary Codes:**

- [APPLY DLL RAZ0R](apply_dll_raz0r.md)

**The code:**

```
00 00 30 00 5E C3 CC CC CC CC CC CC CC CC CC CC CC CC CC CC CC CC CC CC CC CC CC CC CC CC 55 8B EC
Change To
00 00 30 00 5E C3 8B EC C7 05 E9 88 24 10 90 90 90 90 C7 05 ED 88 24 10 90 8B C8 83 EB 03 55 EB E5
```
