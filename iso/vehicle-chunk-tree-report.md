# PS2 vehicle geometry chunk-tree validation

- Complete GEOMETRY.BIN files scanned: 8
- Scanner validates every chunk against its parent boundary and recurses only into IDs with top nibble 0x8.
- Only chunk IDs, sizes, offsets and counts are committed; no payload bytes are exported.

## CARS\RX7\GEOMETRY.BIN

- File size: 7,631,648 bytes
- Chunks: 6901 (1272 containers, 5629 leaves)
- Padding regions / bytes: 599 / 138,916
- Boundary errors: 0

| Chunk ID | Count |
|---|---:|
| 0x00039200 | 5 |
| 0x00039201 | 5 |
| 0x00039202 | 5 |
| 0x00134002 | 1 |
| 0x00134003 | 1 |
| 0x00134004 | 1 |
| 0x00134011 | 634 |
| 0x00134012 | 634 |
| 0x00134013 | 634 |
| 0x00134017 | 525 |
| 0x00134018 | 525 |
| 0x00134019 | 525 |
| 0x0013401A | 232 |
| 0x00134A00 | 634 |
| 0x00134A01 | 634 |
| 0x00134A02 | 634 |
| 0x80034020 | 1 |
| 0x80134000 | 1 |
| 0x80134001 | 1 |
| 0x80134008 | 1 |
| 0x80134010 | 634 |
| 0x80134100 | 634 |

First-level tree (first 24 nodes):

- 0x0: 0x80134000 size=7502792 (container)
-   0x10: 0x80134001 size=20464 (container)
-     0x18: 0x00134002 size=144 (leaf)
-     0xB0: 0x00134003 size=5072 (leaf)
-     0x1488: 0x00134004 size=15216 (leaf)
-     0x5000: 0x80134008 size=0 (container)
-   0x5040: 0x80134010 size=16120 (container)
-     0x5048: 0x00134011 size=192 (leaf)
-     0x5110: 0x00134012 size=32 (leaf)
-     0x5138: 0x00134013 size=40 (leaf)
-     0x5168: 0x0013401A size=1760 (leaf)
-     0x5850: 0x80134100 size=14056 (container)
-       0x5858: 0x00134A00 size=20 (leaf)
-       0x5874: 0x00134A01 size=596 (leaf)
-       0x5AD0: 0x00134A02 size=13416 (leaf)
-   0x8F40: 0x80134010 size=10136 (container)
-     0x8F48: 0x00134011 size=192 (leaf)
-     0x9010: 0x00134012 size=32 (leaf)
-     0x9038: 0x00134013 size=40 (leaf)
-     0x9068: 0x0013401A size=1760 (leaf)
-     0x9750: 0x80134100 size=8072 (container)
-       0x9758: 0x00134A00 size=20 (leaf)
-       0x9774: 0x00134A01 size=452 (leaf)
-       0x9940: 0x00134A02 size=7576 (leaf)

## CARS\CELICA\GEOMETRY.BIN

- File size: 6,671,632 bytes
- Chunks: 6641 (1222 containers, 5419 leaves)
- Padding regions / bytes: 575 / 123,736
- Boundary errors: 0

| Chunk ID | Count |
|---|---:|
| 0x00039200 | 1 |
| 0x00039201 | 1 |
| 0x00039202 | 1 |
| 0x00134002 | 1 |
| 0x00134003 | 1 |
| 0x00134004 | 1 |
| 0x00134011 | 609 |
| 0x00134012 | 609 |
| 0x00134013 | 609 |
| 0x00134017 | 509 |
| 0x00134018 | 509 |
| 0x00134019 | 509 |
| 0x0013401A | 232 |
| 0x00134A00 | 609 |
| 0x00134A01 | 609 |
| 0x00134A02 | 609 |
| 0x80034020 | 1 |
| 0x80134000 | 1 |
| 0x80134001 | 1 |
| 0x80134008 | 1 |
| 0x80134010 | 609 |
| 0x80134100 | 609 |

First-level tree (first 24 nodes):

- 0x0: 0x80134000 size=6565784 (container)
-   0x10: 0x80134001 size=19664 (container)
-     0x18: 0x00134002 size=144 (leaf)
-     0xB0: 0x00134003 size=4872 (leaf)
-     0x13C0: 0x00134004 size=14616 (leaf)
-     0x4CE0: 0x80134008 size=0 (container)
-   0x4D00: 0x80134010 size=26152 (container)
-     0x4D08: 0x00134011 size=192 (leaf)
-     0x4DD0: 0x00134012 size=48 (leaf)
-     0x4E08: 0x00134013 size=48 (leaf)
-     0x4E40: 0x0013401A size=1928 (leaf)
-     0x55D0: 0x80134100 size=23896 (container)
-       0x55D8: 0x00134A00 size=20 (leaf)
-       0x55F4: 0x00134A01 size=1028 (leaf)
-       0x5A00: 0x00134A02 size=22824 (leaf)
-   0xB340: 0x80134010 size=9032 (container)
-     0xB348: 0x00134011 size=192 (leaf)
-     0xB410: 0x00134012 size=48 (leaf)
-     0xB448: 0x00134013 size=40 (leaf)
-     0xB478: 0x0013401A size=1920 (leaf)
-     0xBC00: 0x80134100 size=6792 (container)
-       0xBC08: 0x00134A00 size=20 (leaf)
-       0xBC24: 0x00134A01 size=388 (leaf)
-       0xBDB0: 0x00134A02 size=6360 (leaf)

## CARS\IS300\GEOMETRY.BIN

- File size: 6,216,448 bytes
- Chunks: 6198 (1140 containers, 5058 leaves)
- Padding regions / bytes: 524 / 115,064
- Boundary errors: 0

| Chunk ID | Count |
|---|---:|
| 0x00039200 | 5 |
| 0x00039201 | 5 |
| 0x00039202 | 5 |
| 0x00134002 | 1 |
| 0x00134003 | 1 |
| 0x00134004 | 1 |
| 0x00134011 | 568 |
| 0x00134012 | 568 |
| 0x00134013 | 568 |
| 0x00134017 | 472 |
| 0x00134018 | 472 |
| 0x00134019 | 472 |
| 0x0013401A | 216 |
| 0x00134A00 | 568 |
| 0x00134A01 | 568 |
| 0x00134A02 | 568 |
| 0x80034020 | 1 |
| 0x80134000 | 1 |
| 0x80134001 | 1 |
| 0x80134008 | 1 |
| 0x80134010 | 568 |
| 0x80134100 | 568 |

First-level tree (first 24 nodes):

- 0x0: 0x80134000 size=6107192 (container)
-   0x10: 0x80134001 size=18352 (container)
-     0x18: 0x00134002 size=144 (leaf)
-     0xB0: 0x00134003 size=4544 (leaf)
-     0x1278: 0x00134004 size=13632 (leaf)
-     0x47C0: 0x80134008 size=0 (container)
-   0x4800: 0x80134010 size=21224 (container)
-     0x4808: 0x00134011 size=192 (leaf)
-     0x48D0: 0x00134012 size=56 (leaf)
-     0x4910: 0x00134013 size=40 (leaf)
-     0x4940: 0x0013401A size=1928 (leaf)
-     0x50D0: 0x80134100 size=18968 (container)
-       0x50D8: 0x00134A00 size=20 (leaf)
-       0x50F4: 0x00134A01 size=868 (leaf)
-       0x5460: 0x00134A02 size=18056 (leaf)
-   0x9B00: 0x80134010 size=15416 (container)
-     0x9B08: 0x00134011 size=192 (leaf)
-     0x9BD0: 0x00134012 size=56 (leaf)
-     0x9C10: 0x00134013 size=40 (leaf)
-     0x9C40: 0x0013401A size=1928 (leaf)
-     0xA3D0: 0x80134100 size=13160 (container)
-       0xA3D8: 0x00134A00 size=20 (leaf)
-       0xA3F4: 0x00134A01 size=660 (leaf)
-       0xA690: 0x00134A02 size=12456 (leaf)

## CARS\PEUGOT\GEOMETRY.BIN

- File size: 7,047,936 bytes
- Chunks: 6609 (1214 containers, 5395 leaves)
- Padding regions / bytes: 572 / 129,556
- Boundary errors: 0

| Chunk ID | Count |
|---|---:|
| 0x00039200 | 5 |
| 0x00039201 | 5 |
| 0x00039202 | 5 |
| 0x00134002 | 1 |
| 0x00134003 | 1 |
| 0x00134004 | 1 |
| 0x00134011 | 605 |
| 0x00134012 | 605 |
| 0x00134013 | 605 |
| 0x00134017 | 505 |
| 0x00134018 | 505 |
| 0x00134019 | 505 |
| 0x0013401A | 232 |
| 0x00134A00 | 605 |
| 0x00134A01 | 605 |
| 0x00134A02 | 605 |
| 0x80034020 | 1 |
| 0x80134000 | 1 |
| 0x80134001 | 1 |
| 0x80134008 | 1 |
| 0x80134010 | 605 |
| 0x80134100 | 605 |

First-level tree (first 24 nodes):

- 0x0: 0x80134000 size=6925240 (container)
-   0x10: 0x80134001 size=19536 (container)
-     0x18: 0x00134002 size=144 (leaf)
-     0xB0: 0x00134003 size=4840 (leaf)
-     0x13A0: 0x00134004 size=14520 (leaf)
-     0x4C60: 0x80134008 size=0 (container)
-   0x4C80: 0x80134010 size=22656 (container)
-     0x4C88: 0x00134011 size=192 (leaf)
-     0x4D50: 0x00134012 size=40 (leaf)
-     0x4D80: 0x00134013 size=32 (leaf)
-     0x4DA8: 0x0013401A size=1920 (leaf)
-     0x5530: 0x80134100 size=19992 (container)
-       0x5538: 0x00134A00 size=20 (leaf)
-       0x5554: 0x00134A01 size=964 (leaf)
-       0x5920: 0x00134A02 size=18984 (leaf)
-     0xA350: 0x00134017 size=12 (leaf)
-     0xA364: 0x00134018 size=104 (leaf)
-     0xA3D4: 0x00134019 size=300 (leaf)
-   0xA540: 0x80134010 size=11092 (container)
-     0xA548: 0x00134011 size=192 (leaf)
-     0xA610: 0x00134012 size=40 (leaf)
-     0xA640: 0x00134013 size=32 (leaf)
-     0xA668: 0x0013401A size=1920 (leaf)
-     0xADF0: 0x80134100 size=8696 (container)

## CARS\3000GT\GEOMETRY.BIN

- File size: 6,689,440 bytes
- Chunks: 6303 (1162 containers, 5141 leaves)
- Padding regions / bytes: 539 / 122,000
- Boundary errors: 0

| Chunk ID | Count |
|---|---:|
| 0x00039200 | 5 |
| 0x00039201 | 5 |
| 0x00039202 | 5 |
| 0x00134002 | 1 |
| 0x00134003 | 1 |
| 0x00134004 | 1 |
| 0x00134011 | 579 |
| 0x00134012 | 579 |
| 0x00134013 | 578 |
| 0x00134017 | 478 |
| 0x00134018 | 478 |
| 0x00134019 | 478 |
| 0x0013401A | 216 |
| 0x00134A00 | 579 |
| 0x00134A01 | 579 |
| 0x00134A02 | 579 |
| 0x80034020 | 1 |
| 0x80134000 | 1 |
| 0x80134001 | 1 |
| 0x80134008 | 1 |
| 0x80134010 | 579 |
| 0x80134100 | 579 |

First-level tree (first 24 nodes):

- 0x0: 0x80134000 size=6572968 (container)
-   0x10: 0x80134001 size=18704 (container)
-     0x18: 0x00134002 size=144 (leaf)
-     0xB0: 0x00134003 size=4632 (leaf)
-     0x12D0: 0x00134004 size=13896 (leaf)
-     0x4920: 0x80134008 size=0 (container)
-   0x4940: 0x80134010 size=22456 (container)
-     0x4948: 0x00134011 size=192 (leaf)
-     0x4A10: 0x00134012 size=40 (leaf)
-     0x4A40: 0x00134013 size=32 (leaf)
-     0x4A68: 0x0013401A size=1920 (leaf)
-     0x51F0: 0x80134100 size=20232 (container)
-       0x51F8: 0x00134A00 size=20 (leaf)
-       0x5214: 0x00134A01 size=884 (leaf)
-       0x5590: 0x00134A02 size=19304 (leaf)
-   0xA100: 0x80134010 size=10184 (container)
-     0xA108: 0x00134011 size=192 (leaf)
-     0xA1D0: 0x00134012 size=32 (leaf)
-     0xA1F8: 0x00134013 size=32 (leaf)
-     0xA220: 0x0013401A size=1928 (leaf)
-     0xA9B0: 0x80134100 size=7960 (container)
-       0xA9B8: 0x00134A00 size=20 (leaf)
-       0xA9D4: 0x00134A01 size=388 (leaf)
-       0xAB60: 0x00134A02 size=7528 (leaf)

## CARS\ESCALADE\GEOMETRY.BIN

- File size: 3,131,408 bytes
- Chunks: 3715 (708 containers, 3007 leaves)
- Padding regions / bytes: 327 / 59,700
- Boundary errors: 0

| Chunk ID | Count |
|---|---:|
| 0x00039200 | 1 |
| 0x00039201 | 1 |
| 0x00039202 | 1 |
| 0x00134002 | 1 |
| 0x00134003 | 1 |
| 0x00134004 | 1 |
| 0x00134011 | 352 |
| 0x00134012 | 352 |
| 0x00134013 | 352 |
| 0x00134017 | 265 |
| 0x00134018 | 265 |
| 0x00134019 | 265 |
| 0x0013401A | 94 |
| 0x00134A00 | 352 |
| 0x00134A01 | 352 |
| 0x00134A02 | 352 |
| 0x80034020 | 1 |
| 0x80134000 | 1 |
| 0x80134001 | 1 |
| 0x80134008 | 1 |
| 0x80134010 | 352 |
| 0x80134100 | 352 |

First-level tree (first 24 nodes):

- 0x0: 0x80134000 size=3080188 (container)
-   0x10: 0x80134001 size=11440 (container)
-     0x18: 0x00134002 size=144 (leaf)
-     0xB0: 0x00134003 size=2816 (leaf)
-     0xBB8: 0x00134004 size=8448 (leaf)
-     0x2CC0: 0x80134008 size=0 (container)
-   0x2D00: 0x80134010 size=21896 (container)
-     0x2D08: 0x00134011 size=192 (leaf)
-     0x2DD0: 0x00134012 size=40 (leaf)
-     0x2E00: 0x00134013 size=32 (leaf)
-     0x2E28: 0x0013401A size=1920 (leaf)
-     0x35B0: 0x80134100 size=19672 (container)
-       0x35B8: 0x00134A00 size=20 (leaf)
-       0x35D4: 0x00134A01 size=900 (leaf)
-       0x3960: 0x00134A02 size=18728 (leaf)
-   0x82C0: 0x80134010 size=11528 (container)
-     0x82C8: 0x00134011 size=192 (leaf)
-     0x8390: 0x00134012 size=40 (leaf)
-     0x83C0: 0x00134013 size=32 (leaf)
-     0x83E8: 0x0013401A size=1920 (leaf)
-     0x8B70: 0x80134100 size=9304 (container)
-       0x8B78: 0x00134A00 size=20 (leaf)
-       0x8B94: 0x00134A01 size=436 (leaf)
-       0x8D50: 0x00134A02 size=8824 (leaf)

## CARS\MIRRORS_BODY\GEOMETRY.BIN

- File size: 1,115,712 bytes
- Chunks: 2646 (483 containers, 2163 leaves)
- Padding regions / bytes: 238 / 26,240
- Boundary errors: 0

| Chunk ID | Count |
|---|---:|
| 0x00134002 | 1 |
| 0x00134003 | 1 |
| 0x00134004 | 1 |
| 0x00134011 | 240 |
| 0x00134012 | 240 |
| 0x00134013 | 240 |
| 0x00134017 | 240 |
| 0x00134018 | 240 |
| 0x00134019 | 240 |
| 0x00134A00 | 240 |
| 0x00134A01 | 240 |
| 0x00134A02 | 240 |
| 0x80134000 | 1 |
| 0x80134001 | 1 |
| 0x80134008 | 1 |
| 0x80134010 | 240 |
| 0x80134100 | 240 |

First-level tree (first 24 nodes):

- 0x0: 0x80134000 size=1098220 (container)
-   0x10: 0x80134001 size=7856 (container)
-     0x18: 0x00134002 size=144 (leaf)
-     0xB0: 0x00134003 size=1920 (leaf)
-     0x838: 0x00134004 size=5760 (leaf)
-     0x1EC0: 0x80134008 size=0 (container)
-   0x1F00: 0x80134010 size=4276 (container)
-     0x1F08: 0x00134011 size=192 (leaf)
-     0x1FD0: 0x00134012 size=16 (leaf)
-     0x1FE8: 0x00134013 size=16 (leaf)
-     0x2000: 0x80134100 size=3800 (container)
-       0x2008: 0x00134A00 size=20 (leaf)
-       0x2024: 0x00134A01 size=196 (leaf)
-       0x20F0: 0x00134A02 size=3560 (leaf)
-     0x2EE0: 0x00134017 size=12 (leaf)
-     0x2EF4: 0x00134018 size=64 (leaf)
-     0x2F3C: 0x00134019 size=120 (leaf)
-   0x3000: 0x80134010 size=2924 (container)
-     0x3008: 0x00134011 size=192 (leaf)
-     0x30D0: 0x00134012 size=16 (leaf)
-     0x30E8: 0x00134013 size=16 (leaf)
-     0x3100: 0x80134100 size=2552 (container)
-       0x3108: 0x00134A00 size=20 (leaf)
-       0x3124: 0x00134A01 size=164 (leaf)

## CARS\LANCEREVO8\GEOMETRY.BIN

- File size: 6,523,056 bytes
- Chunks: 6263 (1148 containers, 5115 leaves)
- Padding regions / bytes: 539 / 119,832
- Boundary errors: 0

| Chunk ID | Count |
|---|---:|
| 0x00039200 | 5 |
| 0x00039201 | 5 |
| 0x00039202 | 5 |
| 0x00134002 | 1 |
| 0x00134003 | 1 |
| 0x00134004 | 1 |
| 0x00134011 | 572 |
| 0x00134012 | 572 |
| 0x00134013 | 572 |
| 0x00134017 | 483 |
| 0x00134018 | 483 |
| 0x00134019 | 483 |
| 0x0013401A | 216 |
| 0x00134A00 | 572 |
| 0x00134A01 | 572 |
| 0x00134A02 | 572 |
| 0x80034020 | 1 |
| 0x80134000 | 1 |
| 0x80134001 | 1 |
| 0x80134008 | 1 |
| 0x80134010 | 572 |
| 0x80134100 | 572 |

First-level tree (first 24 nodes):

- 0x0: 0x80134000 size=6408808 (container)
-   0x10: 0x80134001 size=18480 (container)
-     0x18: 0x00134002 size=144 (leaf)
-     0xB0: 0x00134003 size=4576 (leaf)
-     0x1298: 0x00134004 size=13728 (leaf)
-     0x4840: 0x80134008 size=0 (container)
-   0x4880: 0x80134010 size=23324 (container)
-     0x4888: 0x00134011 size=192 (leaf)
-     0x4950: 0x00134012 size=64 (leaf)
-     0x4998: 0x00134013 size=56 (leaf)
-     0x49D8: 0x0013401A size=1920 (leaf)
-     0x5160: 0x80134100 size=20744 (container)
-       0x5168: 0x00134A00 size=20 (leaf)
-       0x5184: 0x00134A01 size=948 (leaf)
-       0x5540: 0x00134A02 size=19752 (leaf)
-     0xA270: 0x00134017 size=12 (leaf)
-     0xA284: 0x00134018 size=80 (leaf)
-     0xA2DC: 0x00134019 size=192 (leaf)
-   0xA3C0: 0x80134010 size=16484 (container)
-     0xA3C8: 0x00134011 size=192 (leaf)
-     0xA490: 0x00134012 size=64 (leaf)
-     0xA4D8: 0x00134013 size=48 (leaf)
-     0xA510: 0x0013401A size=1928 (leaf)
-     0xACA0: 0x80134100 size=13992 (container)

