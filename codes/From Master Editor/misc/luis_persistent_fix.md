# Luis Never Responds to Persistent Attacks Outside r11c

**الوصف:** يمنع لويس من التوقف عن الاستجابة خارج الكبينة

**Description:** Prevents Luis from becoming unresponsive after 5 hits outside the cabin

**Necessary Codes:**

- [APPLY DLL RAZ0R](../dll_raz0r/apply_dll_raz0r.md)

**The code:**

```
FE 8E 7A 09 00 00 8A 86 7A 09 00 00 75 09 80 8E
Change To
E9 F3 00 00 00 90 8A 86 7A 09 00 00 75 09 80 8E

-

Find : 004E6030
Paste : 80 BE 7A 09 00 00 01 74 08 FF 8E 7A 09 00 00 EB 21 50 A1 00 0E 2E 10 66 8B 80 AC 4F 00 00 66 3D 1C 01 74 07 C6 86 7A 09 00 00 05 FF 8E 7A 09 00 00 58 E9 D7 FE FF FF
```
