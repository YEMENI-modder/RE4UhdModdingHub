# Transparency Pick Up Item Fix

**الوصف:** يصلح مشكلة الشفافية عند التقاط الأشياء

**Description:** Fixes transparency overlay bug when picking up items

**ملاحظات:**
- [!] التويكس يصلح هذه المشكلة تلقائياً

**Notes:**
- [!] RE4 Tweaks DLL already fixes this automatically

**The code:**

```
8B 50 58 8B 7D D0 C7 40 58 FF FF FF FF A1 3C 5F
Change To
8B 50 58 8B 7D D0 90 90 90 90 90 90 90 A1 3C 5F
```
