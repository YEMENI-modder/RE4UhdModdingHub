# ESEs Paused Instead of Removed on Companion DLL Movie

**الوصف:** يوقف ESE بدال ما يحذفه خلال الكاتسين

**Description:** ESEs are paused instead of removed during Companion DLL movies

**Necessary Codes:**

- [APPLY DLL RAZ0R](apply_dll_raz0r.md)
- [POINTER EDIT](../necessary/pointer_edit.md)

**The code:**

```
E8 6B E5 D3 FF 5F 5B B0 01 5E 5D C2 08 00 E8 A5
Change To
EB 1B 90 90 90 5F 5B B0 01 5E 5D C2 08 00 E8 A5

-

Find : 002CD3E8
Paste : E8 4E E5 D3 FF 81 7D 04 00 00 00 10 7C DA 50 53 51 31 C9 A1 00 0E 2E 10 8B 80 84 48 5E 00 0F B6 58 06 8D 40 10 39 D9 74 19 F6 00 01 74 0E 66 81 78 1E FF FF 75 06 66 C7 40 1E 01 00 41 8D 40 2C EB E3 59 5B 58 EB A1
```
