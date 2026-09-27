# Treasure Box Sound Fix

**الوصف:** يصلح مشكله صوت الفلوس لما تاخذها

**Description:** Fixes sound when collecting money

**The code:**

```
8B 76 14 C1 E6 04 03 F2 8B 10 89 70 10 8B 52 14 8B 49 3C 03 CA 89 48 14 0F B7 56 0C 6B D2 2E 03 D1 5F 89 50 14 5E C3 CC CC CC CC CC CC CC CC CC CC CC CC CC CC CC CC CC CC CC CC CC
Change To
EB 25 90 C1 E6 04 03 F2 8B 10 89 70 10 8B 52 14 8B 49 3C 03 CA 89 48 14 0F B7 56 0C 6B D2 2E 03 D1 5F 89 50 14 5E C3 8B 76 14 52 8B 10 03 52 14 8B 52 FC 39 D6 5A 7C CB 31 F6 EB C7
```
