# Viktor_S_O:fv_yik_vcl_xfv_x_zvdsea_tf
## user
```
DELETED
```
## notes

No notes found

## files
- keep_going.txt
- you_can_do_it.txt


### keep_going.txt
```
DNA: JVQ  dEN  3JN  QzQ  YX2S
DNA: TSj WW4  C1D  VPU  2UC1 
SIGNED: CNDFDWC1TMks1VUtUN0Q0L
```

> Using pattern of DNA --> `JVQ WW4 3JN VPU YX2S`
> Base32 --> Maksim_L_R

> Using pattern of DNA `TSj dEN C1D QzQ 2UC1`
> Base64 with padding of 3x`A` --> `?J7D4-CC46P-`
> Assuming this is part of a game code, following the format of other found keys, `UJ7D4-CC46P-`

### you_can_do_it.txt
```
10 00000 0110 1001 0 10000 1 1101 111 0010 1 110 10000 00111 1 011 10 00000 00011 011 101 1100 1010 11000 10 1000 00001 011 11 1100 00111 11000 11 1100 0001 1001 110 1001 00011 100 11 0111 00111 1001 11 00111 00011 000 0100 00000 00000 0010 10000 00001 100 0110 111 01 1101 1010 01 00 1000 01     001 10 100 11 11111 1011 1100 0100 1 1100 1001 11 1100 11 00111 0100 0001 0100 001 0001 100 0001 0001 0001 0001 1011 00011 010 100 1101 1 1101 11111 
YzL, MzM, VlU, QtQ
```
> First 'binary' portion should actually be interpreted as morse code.
> From there you get `N5PXE6TQOFTG62TWN53WKZC7NB4WMZ27MZVXGX3DMJ2XM23SL55F64DPOAQCAIBAUNDM0YZLTZXMZM2LVLUVDVVVVY3RDQTQ0`
> which translates to `o_rzpqfojvowed_hyfg_fks_cbuvkr_z_pop    £FÌesÍÙiu]*:ÖµÆâ8N`
>
> The second chunk of the morse code decodes to base32 `UNDM0YZLTZXMZM2LVLUVDVVVVY3RDQTQ0` <br>
> The letters `YzL, MzM, VlU, QtQ` appear in this base32 string <br>
> matching the lowercase letters into the string <br>
> Adding it to signed and padding it as shown: `AAA CNDFDWC1TMks1VUtUN0Q0L UNDM0YzLTZXMzM2LVlUVDVVVVY3RDQtQ0` <br>
> contains a gamecode `KT7D4-CC3F3-6W336-YTT5U` <br>
>
> Alternatively when adding all the lines from keep_going.txt to the second morse code section <br>
> Adding some padding as shown: `AAA JVQ dEN 3JN QzQ YX2S TSj WW4 C1D VPU 2UC1 CNDFDWC1TMks1VUtUN0Q0L UNDM0YzLTZXMzM2LVlUVDVVVVY3RDQtQ0` <br>
> decoding with base64 --> `à-CTõ6P-B41CX-S2K5UKT7D4-CC3F3-6W336-YTT5UUV7D4-C` <br>
> split into chunks and assuming utf-8--> A-CTO6P-B41CX-S2K5U-<b>KT7D4-CC3F3-6W336-YTT5U</b>-UV7D4-C
>
> Using the striped Base64 alongside the SIGNED and remaining base64 provided us with the final EoD game key that has been claimed:
> `AAATSj  dEN  C1D  QzQ  2UC1 CNDFDWC1TMks1VUtUN0Q0L UNDM0YzLTZXMzM2LVlUVDVVVVY3RDQtQ0` --> `?J7D4-CC46P-B41CX-S2K5UKT7D4-CC3F3-6W336-YTT5UUV7D4-C`
> UJ7D4-CC46P-B41CX-S2K5U -> EoD EU game code, already activated by the time of documenting.
