# AEV Type A Damage Type changes from 0A to 08 upon reaching 1 health
*AEV Type A - Damage Type 0A to 08 at 1 HP*

**الوصف:** TYPE A يمديه يخلي هيلك 1

**Description:** Type A can set player HP to 1

**The code:**

```
82 A3 00 00 00 D9 45 18 53 8A 5D 08 D9 C0 DD 05
Change To
82 A3 00 00 00 D9 45 18 53 E9 FA 11 00 00 DD 05

-

Find : 0027F090
Paste : 8A 5D 08 D9 C0 66 3D 00 00 75 07 80 FB 0A 75 02 B3 08 E9 EF ED FF FF
```
