# Always XL Attache Case

**الوصف:** الحقيبة تكون XL دايماً حتى لو غيرتها

**Description:** Forces the attache case to always be XL size

**The code:**

```
0F BE 8F AA 02 00 00 51 8B CB 89 9F AC 02 00 00
Change To
B9 03 00 00 00 90 90 51 8B CB 89 9F AC 02 00 00

-

0F BE 86 AA 02 00 00 83 F8 03 77 50 FF 24 85 BC
Change To
B8 03 00 00 00 90 90 83 F8 03 77 50 FF 24 85 BC

-

0F BE 96 AA 02 00 00 52 89 8E AC 02 00 00 E8 B9
Change To
BA 03 00 00 00 90 90 52 89 8E AC 02 00 00 E8 B9
```
