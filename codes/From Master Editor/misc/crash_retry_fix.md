# Crash on Retry Fix

**الوصف:** إصلاح كراش عند الريتراي

**Description:** Fixes crash when retrying

**ملاحظات:**
- [!] نصيحة: لا تحطه إلا إذا واجهت المشكلة

**Notes:**
- [!] Only use if you experience this crash

**The code:**

```
68 98 00 00 00 50 E8 7A E9 D5 FF 81 C6 98 00 00 00
Change To
68 18 00 00 00 50 E8 7A E9 D5 FF 81 C6 18 00 00 00
```
