# إصلاح كراش AEV عند كثرة الأعداء
*Fix AEV Crash with Too Many Enemies*

**الوصف:** يصلح مشكلة كراش AEV اذا الأعداء كثيرين جداً

**Description:** Fixes a crash that occurs in AEV when there are too many enemies in the scene

**The code:**

```
F6 06 02 74 09 50 E8 AD 06 D6 FF 83 C4 04 8B 4E
Change To
EB 67 90 74 09 50 E8 AD 06 D6 FF 83 C4 04 8B 4E

-

Find : 002AD010
Paste : 50 A1 00 0E 2E 10 05 5A CA 00 00 39 C6 75 03 C6 06 08 58 F6 06 02 EB 82
```
