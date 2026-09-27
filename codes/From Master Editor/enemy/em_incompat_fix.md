# EM Incompatibility Issue Fix

**الوصف:** يحل مشاكل توافق الاعداء

**Description:** Fixes enemy compatibility issues

**The code:**

```
74 13 81 C1 98 00 00 00 40 81 F9 60 02 00 00 72 E8 33 C0 5D C3 69 C0 98 00 00 00 05 20 38 C6 00 5D C3 CC CC CC CC CC CC CC CC CC CC CC CC CC CC CC CC CC CC CC CC CC
Change To
74 13 81 C1 98 00 00 00 40 81 F9 60 02 00 00 72 E8 33 C0 5D C3 69 C0 98 00 00 00 05 20 38 C6 00 60 8B 80 88 00 00 00 85 C0 74 09 8B 48 34 85 C9 74 02 FF D1 61 5D C3
```
