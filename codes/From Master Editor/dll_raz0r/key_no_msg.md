# Key Unlock No Message No Cam
*Key Unlock - No Message No Cam*

**الوصف:** تقفيل أبواب بدون لا رساله ولا كميرا

**Description:** Lock doors without message or camera

**Necessary Codes:**

- [APPLY DLL RAZ0R](apply_dll_raz0r.md)

**The code:**

```
B8 01 00 00 00 F6 C3 01 75 05 B8 02 00
Change To
EB 96 90 90 90 F6 C3 01 75 05 B8 02 00

-

8B 90 28 4F 00 00 8B 41 2C 89 51
Change To
8B 90 28 4F 00 00 EB 2B 90 89 51

-

Find : 002F58D8
Paste : 8B 41 2C 81 3C 24 1F A5 27 10 75 CA 81 7D F4 FF FF FF FF 75 C1 C2 04 00

-

Find : 002C14F0
Paste : 81 7D 08 FF FF FF FF 74 07 B8 01 00 00 00 EB 5D 5E 5B 5D C3
```
