# PNG example

Invoke this in the main folder:

```sh-session
[user@host livedecode]$ livedecode example/png.spec example/example.png
'header'
          magic_8bit = 137
               magic = 'PNG\x0D\x0A'
            magic_1a = 26
            magic_0a = 10
'chunk' 'IHDR'
        chunk_length = 13
                type = 1229472850
            type_str = 'IHDR'
               width = 45
              height = 24
               depth = 8
          color_type = 2
         compression = 0
              filter = 0
           interlace = 0
                 crc = 3788497875
'chunk' 'gAMA'
        chunk_length = 4
                type = 1732332865
            type_str = 'gAMA'
0x00000029: 00 00 B1 8F __ __ __ __  __ __ __ __ __ __ __ __ |....            |
                 crc = 201089285
'chunk' 'cHRM'
        chunk_length = 32
                type = 1665684045
            type_str = 'cHRM'
0x00000039: 00 00 7A 26 00 00 80 84  00 00 FA 00 00 00 80 E8 |..z&............|
0x00000049: 00 00 75 30 00 00 EA 60  00 00 3A 98 00 00 17 70 |..u0...`..:....p|
                 crc = 2629456188
'chunk' 'bKGD'
        chunk_length = 6
                type = 1649100612
            type_str = 'bKGD'
0x00000065: 00 FF 00 FF 00 FF __ __  __ __ __ __ __ __ __ __ |......          |
                 crc = 2696783763
'chunk' 'tIME'
        chunk_length = 7
                type = 1950960965
            type_str = 'tIME'
                year = 2021
               month = 9
                 day = 14
                hour = 15
              minute = 5
              second = 55
                 crc = 2835620772
'chunk' 'IDAT'
        chunk_length = 399
                type = 1229209940
            type_str = 'IDAT'
0x0000008A: 48 C7 ED 94 CD 8A 54 31  10 46 4F 25 55 91 E9 5E |H.....T1.FO%U..^|
0x0000009A: 08 03 BE FF 13 3A 28 F4  BD AD 55 49 CA 45 FF 5E |.....:(...UI.E.^|
0x000000AA: 71 5C 08 82 C2 2D 0E E1  F0 A5 16 DF 26 91 5E 33 |q\...-......&.^3|
0x000000BA: 0C 6F 57 EE FE 1B F9 1B  6B 85 7F 63 F6 1E 7B 8F |.oW.....k..c..{.|
0x000000CA: BD C7 FF D7 43 53 32 85  0B 6C 85 77 44 D8 88 DC |....CS2..l.wD...|
0x000000DA: 85 8D 48 BE 23 B9 95 44  12 D5 2E 09 53 AE 54 A1 |..H.#..D....S.T.|
0x000000EA: 0A 43 28 82 14 4A B9 CA  05 3A 14 B2 90 83 1C CC |.C(..J...:......|
0x000000FA: C2 1C 8C C1 A8 8C C9 C8  2B 1D 3A 0C A1 5F 28 0F |........+.:.._(.|
0x0000010A: A2 10 95 5E 89 4A 28 A1  84 31 2A FA F6 FA 35 1A |...^.J(..1*...5.|
0x0000011A: DD 08 93 BB F4 46 3C 49  37 99 8D 34 30 29 8D 6A |.....F<I7..40).j|
0x0000012A: A8 09 0D 31 A9 86 36 54  31 CB 30 4C 69 35 A3 E0 |...1..6T1.0Li5..|
0x0000013A: 10 99 31 F0 4E 48 46 E2  93 18 19 1D 0F C2 33 14 |..1.NHF.......3.|
0x0000014A: 37 C2 AE 22 9F BE BC 1E  68 07 EC 28 F6 9E 1C C4 |7.."....h..(....|
0x0000015A: 8E 37 39 D0 8E 9B A4 BD  CC 2A E7 9E 8B B3 04 67 |.79......*.....g|
0x0000016A: CF 35 58 82 C5 73 0D D6  27 59 6F 57 AB E7 F2 73 |.5X..s..'YoW...s|
0x0000017A: A2 9F 3F BE 7D 43 9D D6  69 9D 36 69 60 D0 0A AD |..?.}C..i.6i`...|
0x0000018A: D2 94 D6 B0 41 9B B4 A4  09 56 68 4A 33 5A 23 3E |....A....VhJ3Z#>|
0x0000019A: 60 2F C4 4B 2A 19 74 27  82 70 AA 53 1C 71 32 98 |`/.K*.t'.p.S.q2.|
0x000001AA: CE 70 C2 F1 E0 BB 73 76  56 E7 E4 2C C1 C9 59 9C |.p....svV..,..Y.|
0x000001BA: 93 73 72 D6 A1 96 6A 98  DE A8 68 C5 2A 56 D0 0B |.sr...j...h.*V..|
0x000001CA: 82 0A 0A 2A 54 50 D0 A4  CE 3B 52 E7 AC 65 CE CC |...*TP...;R..e..|
0x000001DA: 4A 4E B2 92 97 B5 89 4C  50 64 52 26 92 94 49 99 |JN.....LPdR&..I.|
0x000001EA: D4 44 93 9A 57 D1 C4 12  BD BC 17 1E F0 24 3C C9 |.D..W........$<.|
0x000001FA: 16 E4 26 80 48 42 0A F0  08 B7 FB B9 3D F3 17 C9 |..&.HB......=...|
0x0000020A: FE 8F ED 3D F6 1E 7B 8F  3F 9D 1F 89 E8 5F 16 __ |...=..{.?...._. |
                 crc = 2758011464
'chunk' 'tEXt'
        chunk_length = 37
                type = 1950701684
            type_str = 'tEXt'
                text = 'date:create\x002021-09-14T15:05:55+00:00'
                 crc = 3937509577
'chunk' 'tEXt'
        chunk_length = 37
                type = 1950701684
            type_str = 'tEXt'
                text = 'date:modify\x002021-09-14T15:05:55+00:00'
                 crc = 2615941237
'chunk' 'IEND'
        chunk_length = 0
                type = 1229278788
            type_str = 'IEND'
                 crc = 2923585666
[user@host livedecode]$
```
