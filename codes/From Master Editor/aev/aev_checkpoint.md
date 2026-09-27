# AEV Checkpoint

**الوصف:** يمديك تخلي لل AEV تشيكبونت

**Description:** Allows AEV to have checkpoints

**Necessary Codes:**

- [POINTER EDIT](../necessary/pointer_edit.md)
- [AEV-FSE](aev_fse.md)
- [AEV-ESE](aev_ese.md)
- [AEV - Auto-Door Block](aev_auto_door.md)
- [AEV-CAM](aev_cam.md)

**The code:**

```
88 50 29 0F B6 4E 6D 8B 15 3C 5F
Change To
E9 EB 0C 00 00 90 90 8B 15 3C 5F

-

Find : 002B7ED0
Paste : 88 50 29 0F B6 4E 6D 80 7E 4B C1 74 06 80 7E 4B C2 75 0A 81 88 28 50 00 00 00 00 00 80 E9 F5 F2 FF FF

-

Find : 002BE4B8
Paste : 80 78 4B C0 74 06 80 78 4B C2 75 07 60 E8 74 0A 12 00 61 C3
```
