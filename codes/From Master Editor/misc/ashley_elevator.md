# Ashley Visible on Elevator (r225, r21d)

**الوصف:** أشلي تظهر معاك في المصعد في r225 و r21d

**Description:** Ashley is drawn alongside Leon when riding the elevator in r225 and r21d

**Necessary Codes:**

- [POINTER EDIT](../necessary/pointer_edit.md)

**The code:**

```
E8 CC 54 B7 FF 8B 0E 83 C4 0C 8D 91 94 00 00 00
Change To
E9 C3 01 00 00 8B 0E 83 C4 0C 8D 91 94 00 00 00

-

B9 FF FC 00 00 66 21 8E CE 02 00 00 81 4E 04 00
Change To
B9 01 16 00 00 66 89 8E CE 02 00 00 81 4E 04 00

-

Find : 00492078
Paste : E8 04 53 B7 FF 50 53 A1 00 0E 2E 10 66 8B 98 AC 4F 00 00 66 81 FB 25 02 74 0E 66 81 FB 1D 02 74 07 5B 58 E9 15 FE FF FF 8B 80 00 C9 FF FF 83 F8 00 74 EE 89 90 98 00 00 00 66 F7 80 CE 02 00 00 00 01 74 09 66 C7 80 CE 02 00 00 01 16 F7 40 04 00 08 00 00 75 CB 81 48 04 00 08 00 00 EB C2
```
