# Drawn Enemies During Camera Events

**الوصف:** تخلي الأعداء يظهرون خلال الكميرا في 4 غرف تختارها

**Description:** Makes enemies visible during camera events in up to 4 rooms of your choice

**Find:** 002BDBE8
**Paste:**
```
53 8B 98 AC 4F 00 00 66 81 FB 25 03 74 1F 66 81 FB 1C 03 74 18 66 81 FB 1A 02 74 11 66 81 FB 0B 03 74 0A 81 88 20 50 00 00 00 00 00 10 5B E9 F9 FE FF FF
```

البايتات `25 03` و `1C 03` و `1A 02` و `0B 03` هي أرقام الغرف (r325, r31c, r21a, r30b) — استبدلها بالغرفة الي تبيها. مثلاً لو تبي R113 اكتب `01 13`.

**The code:**

```
81 88 20 50 00 00 00 00 00 10 8B 15 3C 5F
Change To
E9 D9 00 00 00 90 90 90 90 90 8B 15 3C 5F

-

Find : 002BDBE8
Paste : 53 8B 98 AC 4F 00 00 66 81 FB 25 03 74 1F 66 81 FB 1C 03 74 18 66 81 FB 1A 02 74 11 66 81 FB 0B 03 74 0A 81 88 20 50 00 00 00 00 00 10 5B E9 F9 FE FF FF
```
