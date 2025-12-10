All characters are a representation using ascii
| Value | Token         | Char         | Notes             |
| ----- | ------------- | ------------ | ----------------- |
| 00    |               |              |                   |
| 01    | Mp            | start        |                   |
| 02    | Mn            | start+1      |                   |
| 03    | Me            | start+2      |                   |
| 04    | Mm            | start+3      |                   |
| 05    | ao            | start+4      |                   |
| 06    | h             | start+5      |                   |
| 07    | mN            | start+6      |                   |
| 08    | mB            | start+7      |                   |
| 09    | ħ             | start+8      |                   |
| 0A    | α             | start+9      |                   |
| 0B    | re            | start+10     |                   |
| 0C    | λc            | start+11     |                   |
| 0D    | rp            | start+12     |                   |
| 0E    | rcp           | start+13     |                   |
| 0F    | λcn           | start+14     |                   |
| 10    | Ex^2          | start+15     |                   |
| 11    | Ex            | start+16     |                   |
| 12    | n             | start+17     |                   |
| 13    | Ey^2          | start+18     |                   |
| 14    | Ey            | start+19     |                   |
| 15    | Exy           | start+20     |                   |
| 16    | Ex^3          | start+21     |                   |
| 17    | Ex^2y         | start+22     |                   |
| 18    | Ex^4          | start+23     |                   |
| 19    | minX          | start+24     |                   |
| 1A    | maxX          | start+25     |                   |
| 1B    | minY          | start+26     |                   |
| 1C    | maxY          | start+27     |                   |
| 1D    | R∞            | start+28     | inf is infinite   |
| 1E    | u             | start+29     |                   |
| 1F    | mp            | start+30     |                   |
| 20    | AtWt          | start+31     | space at end      |
| 21    |              | start+32     | rectangle (space) |
| 22    | me            | start+33     |                   |
| 23    | mn            | start+34     |                   |
| 24    | mm            | start+35     |                   |
| 25    | %             | %            |                   |
| 26    | F             | % +1         |                   |
| 27    | e             | % +2         |                   |
| 28    | (             | (            |                   |
| 29    | )             | )            |                   |
| 2A    | NA            | ) + 1        |                   |
| 2B    | +             | +            |                   |
| 2C    | ,             | \+ +1        |                   |
| 2D    | \-            | \-           |                   |
| 2E    | .             | .            |                   |
| 2F    | @             | . +1         |                   |
| 30    | 0             | 0            |                   |
| 31    | 1             | 1            |                   |
| 32    | 2             | 2            |                   |
| 33    | 3             | 3            |                   |
| 34    | 4             | 4            |                   |
| 35    | 5             | 5            |                   |
| 36    | 6             | 6            |                   |
| 37    | 7             | 7            |                   |
| 38    | 8             | 8            |                   |
| 39    | 9             | 9            |                   |
| 3A    | :             | 9 +1         |                   |
| 3B    | k             | 9 +2         |                   |
| 3C    | <             | 9 +3         |                   |
| 3D    | \=            | 9 +4         |                   |
| 3E    | \>            | 9 +5         |                   |
| 3F    | RndFix(       | 9 +6         |                   |
| 40    | Vm            | 9 +7         |                   |
| 41    | A             | A            |                   |
| 42    | B             | B            |                   |
| 43    | C             | C            |                   |
| 44    | D             | D            |                   |
| 45    | E             | E            |                   |
| 46    | F             | F            |                   |
| 47    | \->A          | F +1         |                   |
| 48    | \->B          | F +2         |                   |
| 49    | \->C          | F +3         |                   |
| 4A    | \->D          | F +4         |                   |
| 4B    | \->M          | F +5         |                   |
| 4C    | \->X          | F +6         |                   |
| 4D    | \->Y          | F +7         |                   |
| 4E    | ×             | ×            |                   |
| 4F    | ÷             | ÷            |                   |
| 50    | h             | ÷ +1         |                   |
| 51    | d             | ÷ +2         |                   |
| 52    | o             | ÷ +3         |                   |
| 53    | b             | ÷ +4         |                   |
| 54    | M             | M            |                   |
| 55    | \>a+bi        | M +1         |                   |
| 56    | \>r/_0        | M +2         |                   |
| 57    | !             | !            |                   |
| 58    | X             | X            |                   |
| 59    | Y             | Y            |                   |
| 5A    | Ref(          | Y +1         |                   |
| 5B    | Rref(         | Y +2         |                   |
| 5C    | ▫             | ▫            |                   |
| 5D    | Π(            | Π(           |                   |
| 5E    | ^(            | ^(           |                   |
| 5F    | ÷R            | ^( +1        |                   |
| 60    | (-)           | (-)          |                   |
| 61    | Not(          | (-) +1       |                   |
| 62    | Neg(          | (-) +2       |                   |
| 63    | Abs(          | Abs(         |                   |
| 64    | x̂1           | Abs( +1      |                   |
| 65    | x̂            | Abs( +2      |                   |
| 66    | ŷ             | Abs( +3      |                   |
| 67    | x̂2           | Abs( +4      |                   |
| 68    | log(          | log(         |                   |
| 69    | Σ(            | log( +1      |                   |
| 6A    | ∫(            | log( +2      |                   |
| 6B    | d/dx(         | log( +3      |                   |
| 6C    | Pol(          | Pol(         |                   |
| 6D    | Rec(          | Rec(         |                   |
| 6E    | and           | Rec( +1      |                   |
| 6F    | or            | Rec( +2      |                   |
| 70    | sinh(         | sinh(        |                   |
| 71    | cosh(         | cosh(        |                   |
| 72    | tanh(         | tanh(        |                   |
| 73    | e^(           | e^(          |                   |
| 74    | x10           | x10          |                   |
| 75    | ^2            | ^2           |                   |
| 76    | ^3            | ^2 +1        |                   |
| 77    | ^-1           | ^-1          |                   |
| 78    | R             | ^-1 +1       |                   |
| 79    | C0            | ^-1 +2       |                   |
| 7A    | C1            | ^-1 +3       |                   |
| 7B    | Int(          | ^-1 +4       |                   |
| 7C    | @             | ^-1 +5       |                   |
| 7D    | Intg(         | ^-1 +6       |                   |
| 7E    | xor           | ^-1 +7       |                   |
| 7F    | xnor          | ^-1 +8       |                   |
| 80    | i             | ^-1 +9       |                   |
| 81    | e             | e            |                   |
| 82    | π             | π            |                   |
| 83    | \->E          | π+1          |                   |
| 84    | \->F          | π+2          |                   |
| 85    | deg           | deg          |                   |
| 86    | rad           | rad          |                   |
| 87    | grad          | grad         |                   |
| 88    | Conjg(        | grad +1      |                   |
| 89    | x--(tophat)   | grad +2      |                   |
| 8A    | y-- (tophat)  | grad +3      |                   |
| 8B    | Ans           | Ans          |                   |
| 8C    | Ran#          | Ran#         |                   |
| 8D    | Q1            | Ran# +1      |                   |
| 8E    | Q3            | Ran# +2      |                   |
| 8F    | med           | Ran# +3      | (wide char)       |
| 90    | sinh^-1(      | sinh^-1(     |                   |
| 91    | cosh^-1(      | cosh^-1(     |                   |
| 92    | tanh^-1(      | tanh^-1(     |                   |
| 93    | 10^(          | 10^(         |                   |
| 94    | <             | 10^( +1      |                   |
| 95    | ≠             | 10^( +2      |                   |
| 96    | \>            | 10^( +3      |                   |
| 97    | Simp          | 10^( +4      |                   |
| 98    | √(            | √(           |                   |
| 99    | M+            | √(+1         |                   |
| 9A    | A             | √(+2         |                   |
| 9B    | B             | √(+3         |                   |
| 9C    | C             | √(+4         |                   |
| 9D    | r             | √(+5         |                   |
| 9E    | \-            | √(+6         | (single dot)      |
| 9F    | ^x√(          | ^x√(         |                   |
| A0    | sin(          | sin(         |                   |
| A1    | cos(          | cos(         |                   |
| A2    | tan(          | tan(         |                   |
| A3    | ln(           | ln(          |                   |
| A4    | @             | ln( +1       |                   |
| A5    | Conv          | ln( +2       |                   |
| A6    | GCD(          | ln( +3       |                   |
| A7    | LCM(          | ln( +4       |                   |
| A8    | ^3√(          | ^3√(         |                   |
| A9    | M-            | ^3√( +1      |                   |
| AA    | σx            | ^3√( +2      |                   |
| AB    | sx            | ^3√( +3      |                   |
| AC    | σy            | ^3√( +4      |                   |
| AD    | sy            | ^3√( +5      |                   |
| AE    | ■/□           | ■/□          | (frac)            |
| AF    | /_            | ■/□ +1       |                   |
| B0    | sin^-1(       | sin^-1(      |                   |
| B1    | cos^-1(       | cos^-1(      |                   |
| B2    | tan^-1(       | tan^-1(      |                   |
| B3    | Rnd(          | Rnd(         |                   |
| B4    | c2            | Rnd +1       |                   |
| B5    | σ             | Rnd +2       |                   |
| B6    | εo            | Rnd +3       |                   |
| B7    | mo            | Rnd +4       |                   |
| B8    | A             | Rnd +5       |                   |
| B9    | B             | Rnd +6       |                   |
| BA    | C             | Rnd +7       |                   |
| BB    | D             | Rnd +8       |                   |
| BC    | E             | Rnd +9       |                   |
| BD    | F             | Rnd +10      |                   |
| BE    | P             | Rnd +11      |                   |
| BF    | C             | Rnd +12      |                   |
| C0    | det(          | Rnd +13      |                   |
| C1    | Trn(          | Rnd +14      |                   |
| C2    | RanInt#(      | RanInt#(     |                   |
| C3    | arg(          | RanInt#( +1  |                   |
| C4    | øo            | RanInt#( +2  |                   |
| C5    | g             | RanInt#( +3  |                   |
| C6    | Go            | RanInt#( +4  |                   |
| C7    | Zo            | RanInt#( +5  |                   |
| C8    | MatA          | RanInt#( +6  |                   |
| C9    | MatB          | RanInt#( +7  |                   |
| CA    | MatC          | RanInt#( +8  |                   |
| CB    | MatAns        | RanInt#( +9  |                   |
| CC    | VctA          | RanInt#( +10 |                   |
| CD    | VctB          | RanInt#( +11 |                   |
| CE    | VctC          | RanInt#( +12 |                   |
| CF    | VctAns        | RanInt#( +13 |                   |
| D0    | P(            | RanInt#( +14 |                   |
| D1    | Q(            | RanInt#( +15 |                   |
| D2    | R(            | RanInt#( +16 |                   |
| D3    | \>t           | RanInt#( +17 |                   |
| D4    | t             | RanInt#( +18 |                   |
| D5    | G             | RanInt#( +19 |                   |
| D6    | atm           | RanInt#( +20 |                   |
| D7    | in>cm         | RanInt#( +21 |                   |
| D8    | cm>in         | RanInt#( +22 |                   |
| D9    | ft>m          | RanInt#( +23 |                   |
| DA    | m>ft          | RanInt#( +24 |                   |
| DB    | yd>m          | RanInt#( +25 |                   |
| DC    | m>yd          | RanInt#( +26 |                   |
| DD    | mile>km       | RanInt#( +27 |                   |
| DE    | km>mile       | RanInt#( +28 |                   |
| DF    | n mile>m      | RanInt#( +29 |                   |
| E0    | m>n mile      | RanInt#( +30 |                   |
| E1    | acre>m^2      | RanInt#( +31 |                   |
| E2    | m^2>acre      | RanInt#( +32 |                   |
| E3    | gal(US)>Q     | RanInt#( +33 |                   |
| E4    | Q>gal(US)     | RanInt#( +34 |                   |
| E5    | gal(UK)>Q     | RanInt#( +35 |                   |
| E6    | Q>gal(UK)     | RanInt#( +36 |                   |
| E7    | pc>km         | RanInt#( +37 |                   |
| E8    | km>pc         | RanInt#( +38 |                   |
| E9    | km/h>m/s      | RanInt#( +39 |                   |
| EA    | m/s>km/h      | RanInt#( +40 |                   |
| EB    | oz>g          | RanInt#( +41 |                   |
| EC    | g>oz          | RanInt#( +42 |                   |
| ED    | lb>kg         | RanInt#( +43 |                   |
| EE    | kg>lb         | RanInt#( +44 |                   |
| EF    | atm>Pa        | RanInt#( +45 |                   |
| F0    | Pa>atm        | RanInt#( +46 |                   |
| F1    | mmHg>Pa       | RanInt#( +47 |                   |
| F2    | Pa>mmHg       | RanInt#( +48 |                   |
| F3    | hp>kW         | RanInt#( +49 |                   |
| F4    | kW>hp         | RanInt#( +50 |                   |
| F5    | kgf/cm^2>Pa   | RanInt#( +51 |                   |
| F6    | Pa>kgf/cm^2   | RanInt#( +52 |                   |
| F7    | kgf·m>J       | RanInt#( +53 |                   |
| F8    | J>Kgf·m       | RanInt#( +54 |                   |
| F9    | lbf/in^2>kPa  | RanInt#( +55 |                   |
| FA    | kPa>lbf/in^2  | RanInt#( +56 |                   |
| FB    | (deg)F>(deg)C | RanInt#( +57 |                   |
| FC    | (deg)C>(deg)F | RanInt#( +58 |                   |
| FD    | J>cal         | RanInt#( +59 |                   |
| FE    | cal>J         | RanInt#( +60 |                   |
| FF    | @             | RanInt#( +61 |                   |
