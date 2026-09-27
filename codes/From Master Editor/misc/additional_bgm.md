# Adding Additional BGM files
*Adding Additional BGM Files*

**الوصف:** يضيف ملف XSB و XWB جديده

**Description:** Adds new XSB and XWB files

**Necessary Codes:**

- [POINTER EDIT](../necessary/pointer_edit.md)

**Find:** 0078C200
Start Entering String Directories at this address

For Example:
```
BIO4\snd\1234567.xwb
BIO4\snd\1234567.xsb
```

If we are to use more than one extra BGM file they will need to be separated by 20 bytes (hex) to separate each new set of XWB and XSB. The order MUST be xwb and xsb respectively. The maximum string length of each entry is 32(DEC) or 20(HEX) bytes long.

Example Paste:
```
42 49 4F 34 5C 73 6E 64 5C 31 32 33 34 35 36 37 2E 78 77 62 00 00 00 00 00 00 00 00 00 00 00 00 42 49 4F 34 5C 73 6E 64 5C 31 32 33 34 35 36 37 2E 78 73 62 00 00 00 00 00 00 00 00 00 00 00 00
```

**The code:**

```
7C BC 5F 5E 8B E5 5D C3
Change To
7C BC E9 EA FA FF FF C3

-

83 C4 10 89 45 F8 33 C9 33 F6 B8 44 7E
Change To
83 C4 10 E9 D8 01 00 00 90 90 B8 44 7E

-

57 F6 C1 01 0F 84 09 01 00 00 8B 04 9D 00 02
Change To
57 F6 C1 01 E9 A4 01 00 00 90 8B 04 9D 00 02

-

3C FF 0F 84 EC 00 00 00 0F BE F8 8B 04 9D 00 02
Change To
3C FF E9 6B 01 00 00 90 0F BE F8 8B 04 9D 00 02

-

Find : 0056DDB0
Paste : 0F 84 60 FF FF FF 83 FB 02 0F 8C 4E FE FF FF A1 00 0E 2E 10 8B 80 20 93 5C 00 E9 45 FE FF FF 74 80 83 FB 02 0F 8C 8B FE FF FF 0F BE F8 A1 00 0E 2E 10 8B 80 20 93 5C 00 E9 82 FE FF FF

-

Find : 005771A0
Paste : 89 45 F8 31 F6 8B 0D 00 0E 2E 10 8D 89 20 69 F3 FF 80 39 00 74 06 46 8D 49 40 EB F5 31 C9 A1 00 0E 2E 10 8D 80 64 0F 62 00 56 6B F6 5C 8D 04 30 5E E9 FA FD FF FF

-

Find : 00577168
Paste : 3B B6 3F E0 D4 FF 75 1C 50 53 8D 5E FC 8D 86 CC 35 F6 FF 80 38 00 74 0A 89 03 8D 40 20 8D 5B 04 EB F1 5B 58 83 3E 00 0F 85 A0 04 00 00 5F 5E 8B E5 5D C3
```
