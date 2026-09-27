# Parasite Plaga ITA Respawn Fix

**الوصف:** إصلاح مشكلة البلاغا ما تظهر في العدو

**Description:** Fixes parasite plaga not appearing on enemies

**The code:**

```
66 89 86 24 03 00 00 6A 00 56 E8 30 84 F6
Change To
EB 3E 90 90 90 90 90 6A 00 56 E8 30 84 F6

-

Find : 0009DC18
Paste : 66 89 86 24 03 00 00 50 8A 86 A0 03 00 00 3C FF 58 74 07 56 E8 AF D8 F6 FF 5E EB AB
```
