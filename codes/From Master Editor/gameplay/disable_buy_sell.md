# Disable Buy & Sell from Merchant

**الوصف:** يوقف الشراء والبيع من التاجر

**Description:** Disables buying and selling from the merchant

**ملاحظات:**
- [!] غير مختبر مع الترقيات

**Notes:**
- [!] Untested whether weapon upgrades still work

**The code:**

```
FE C9 88 4B 11 EB 34 8B D0 81 E2 00 00 00 04 33 FF 0B D7 74 07 FE C1 88 4B 11
Change To
B1 02 88 4B 11 EB 34 8B D0 81 E2 00 00 00 04 33 FF 0B D7 74 07 B1 02 88 4B 11

-

C6 46 11 01 8B C6 5E C3 CC CC CC CC CC CC CC CC
Change To
C6 46 11 02 8B C6 5E C3 CC CC CC CC CC CC CC CC
```
