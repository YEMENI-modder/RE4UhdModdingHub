# Changing the Parameters of some AEV Type A events
*AEV Type A Parameter Changes*

**الوصف:** يغير بارامترات بعض ايفنتات Type A

**Description:** Changes parameters for some Type A events

**Necessary Codes:**

- [POINTER EDIT](../necessary/pointer_edit.md)

**The code:**

```
8B 45 0C 6A 01 6A 00 50 56 E8 25 69 CA FF D9 45
Change To
E9 7F FE FF FF 6A 00 50 56 E8 25 69 CA FF D9 45

-

74 06 8A 4E 5C 88 4D BC 51 0F B6 4E 60 F6 C2 02 8B
Change To
74 06 8A 4E 5C 88 4D BC E9 0D 01 00 00 F6 C2 02 8B

-

Find : 0035FB30
Paste : 8B 45 0C 8B 0C 24 83 F9 00 74 09 80 B9 98 00 00 00 FE 74 07 6A 01 E9 66 01 00 00 53 8B 1D 00 0E 2E 10 66 83 BB B8 4F 00 00 01 5B 7F E7 6A 00 EB E5

-

Find : 002B2DF0
Paste : 51 80 BE 98 00 00 00 FE 74 09 0F B6 4E 60 E9 E0 FE FF FF 50 A1 00 0E 2E 10 66 83 B8 B8 4F 00 00 01 58 75 E6 B1 09 EB E6
```
