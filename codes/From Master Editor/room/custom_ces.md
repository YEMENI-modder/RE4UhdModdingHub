# Allow Custom Chapter Ending Screens

**الوصف:** تحدد غرف مخصصة لشاشات نهاية الفصل

**Description:** Set custom room pairs to trigger Chapter Ending Screens

**Necessary Codes:**

- [POINTER EDIT](../necessary/pointer_edit.md)

**Find:** 00702578 *(important — New CodeCave address, Updated 12-29-2023)*

في هذا القسم من الـ paste، تدخل رقم الغرفة على شكل أزواج: Last Entered ---> Destination.
الـ CES يصير مرة وحدة بس في غرفة الـ Destination ثم ما يتكرر.

**ملاحظة:** عشان يشتغل صح، أول مرة تدخل غرفة الـ Destination لازم تكون فعلاً أول مرة تدخلها. تقدر تعيد استخدام غرف Last Entered لكن مو غرف Destination.
الزوج الأول يستخدم أول CES، الزوج الثاني يستخدم ثاني CES، وهكذا.

Example Paste (كود REmix):
```
20 02 0A 02 FF FF FF FF FF FF FF FF 0C 01 13 02 FF FF FF FF FF FF FF FF 07 02 07 01 FF FF FF FF FF FF FF FF FF FF FF FF 25 02 1D 02 FF FF FF FF FF FF FF FF 21 02 10 02
```

استخدم `FF FF FF FF` عشان تتخطى subchapter.

- r220 ---> r20a
- r10c ---> r213
- r207 ---> r107
- r225 ---> r21d
- r221 ---> r210

نفس منطق ترميز أرقام الغرف من AEV-CAM ينطبق هنا.

**The code:**

```
E8 9E 3B D4 FF 68 00 00 00 80 53 6A 0A 8B C3 50
Change To
E9 45 01 00 00 68 00 00 00 80 53 6A 0A 8B C3 50

-

88 81 9A 4F 00 00 A1 3C 5F
Change To
E9 03 08 00 00 90 A1 3C 5F

-

F6 C4 41 75 33 53 68 00 00 00 20 E8 28 C4 D4 FF
Change To
E9 03 05 00 00 53 68 00 00 00 20 E8 28 C4 D4 FF

-

E8 BC 86 D4 FF F6 05 38 40
Change To
E9 B2 04 00 00 F6 05 38 40

-

E8 2B 0B D4 FF A0 21 41
Change To
E9 D9 02 00 00 A0 21 41

-

E8 E4 03 D4 FF A0 21 41
Change To
E9 81 02 00 00 A0 21 41

-

E8 CA 15 D4 FF 6A 28 E8 B7 67 D4 FF 83 C4 20 8B
Change To
E9 2E 02 00 00 6A 28 E8 B7 67 D4 FF 83 C4 20 8B

-

0F BE 45 FF 48 5E 75 12 6A 0A 53 E8 2A FC D3 FF
Change To
E9 21 02 00 00 5E 75 12 6A 0A 53 E8 2A FC D3 FF

-

E9 8E 00 00 00 6A 05 53 E8 32 83 D4 FF 83 C4 18
Change To
E9 1D 03 00 00 6A 05 53 E8 32 83 D4 FF 83 C4 18

-

Find : 002C20F8
Paste : 50 A1 00 0E 2E 10 80 B8 A1 D4 00 00 FF 58 0F 85 1C FB FF FF F6 C4 41 0F 85 13 FB FF FF E9 DB FA FF FF E8 05 82 D4 FF 50 A1 00 0E 2E 10 80 B8 A1 D4 00 00 FF 58 0F 85 51 FB FF FF E9 30 FB FF FF E8 4D 08 D4 FF 50 A1 00 0E 2E 10 80 B8 A1 D4 00 00 FF 58 0F 85 2A FD FF FF E9 09 FD FF FF E8 5E 01 D4 FF 50 A1 00 0E 2E 10 80 B8 A1 D4 00 00 FF 58 0F 85 85 FD FF FF E9 61 FD FF FF 50 A1 00 0E 2E 10 80 B8 A1 D4 00 00 FF 58 75 05 E8 87 13 D4 FF E9 B8 FD FF FF 50 A1 00 0E 2E 10 80 B8 A1 D4 00 00 FF 58 5E 75 0A 0F BE 45 FF 48 E9 C5 FD FF FF 0F BE 45 FF 48 E9 CF FD FF FF 50 A1 00 0E 2E 10 80 B8 A1 D4 00 00 FF 58 0F 85 DA FC FF FF E9 58 FD FF FF 50 A1 00 0E 2E 10 81 B0 1C 50 00 00 00 00 00 10 58 E8 43 3A D4 FF E9 A0 FE FF FF 88 81 9A 4F 00 00 81 89 1C 50 00 00 00 00 00 10 E9 E9 F7 FF FF

-

0F 8C A8 00 00 00 A1 D4 37
Change To
E9 A9 00 00 00 90 A1 D4 37

-

E8 18 A6 D4 FF A1 3C 5F
Change To
E9 7C ED FF FF A1 3C 5F

-

Find : 002C2CC8
Paste : 60 A1 00 0E 2E 10 8D 98 98 C2 EA FF 8B 88 AC 4F 00 00 66 8B 90 B0 4F 00 00 31 F6 66 81 7C 33 02 CC CC 74 3D 66 3B 4C B3 02 75 31 66 3B 14 B3 75 2B 50 51 8D 88 F4 CD 00 00 E8 B1 74 D4 FF F7 00 00 00 80 00 75 26 58 90 6A FF 56 C6 80 A1 D4 00 00 FF E8 85 00 D4 FF 83 C4 08 EB 05 46 90 90 EB BA 61 E8 35 B8 D4 FF E9 18 12 00 00 66 81 38 25 03 75 11 F7 00 00 00 00 10 75 09 81 08 00 00 00 10 58 EB C4 58 EB DA
```
