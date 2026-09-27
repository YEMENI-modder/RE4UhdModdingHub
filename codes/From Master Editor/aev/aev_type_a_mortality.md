# Adding player mortality to AEV Type A events
*Player Mortality for AEV Type A*

**الوصف:** TYPE A يمديه يقتلك

**Description:** Type A AEV can kill the player

**The code:**

```
8B 45 0C 6A 01 6A 00 50 56 E8 72 87 D8 FF 0F B6
Change To
E9 9C 01 00 00 6A 00 50 56 E8 72 87 D8 FF 0F B6

-

Find : 0027E000
Paste : 8B 45 0C 8B 0C 24 83 F9 00 74 09 80 B9 98 00 00 00 FE 74 07 6A 01 E9 49 FE FF FF 6A 00 EB F7
```
