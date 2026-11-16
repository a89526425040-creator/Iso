# C++ / Python PS2 chunk reader cross-check

- Complete PS2 vehicle resources were parsed independently by both readers.
- The comparison requires exact agreement on chunk, container, leaf, and padding counts.
- Extracted files exist only in the temporary workflow runner.

## CARS\RX7\GEOMETRY.BIN

- File bytes: 7,631,648
- Matching counts (chunks / containers / leaves / padding regions / padding bytes): (6901, 1272, 5629, 599, 138916)

Chunk ID counts from the C++ reader:

- 0x39200: 5
- 0x39201: 5
- 0x39202: 5
- 0x134002: 1
- 0x134003: 1
- 0x134004: 1
- 0x134011: 634
- 0x134012: 634
- 0x134013: 634
- 0x134017: 525
- 0x134018: 525
- 0x134019: 525
- 0x13401a: 232
- 0x134a00: 634
- 0x134a01: 634
- 0x134a02: 634
- 0x80034020: 1
- 0x80134000: 1
- 0x80134001: 1
- 0x80134008: 1
- 0x80134010: 634
- 0x80134100: 634

## CARS\CELICA\GEOMETRY.BIN

- File bytes: 6,671,632
- Matching counts (chunks / containers / leaves / padding regions / padding bytes): (6641, 1222, 5419, 575, 123736)

Chunk ID counts from the C++ reader:

- 0x39200: 1
- 0x39201: 1
- 0x39202: 1
- 0x134002: 1
- 0x134003: 1
- 0x134004: 1
- 0x134011: 609
- 0x134012: 609
- 0x134013: 609
- 0x134017: 509
- 0x134018: 509
- 0x134019: 509
- 0x13401a: 232
- 0x134a00: 609
- 0x134a01: 609
- 0x134a02: 609
- 0x80034020: 1
- 0x80134000: 1
- 0x80134001: 1
- 0x80134008: 1
- 0x80134010: 609
- 0x80134100: 609

## CARS\IS300\GEOMETRY.BIN

- File bytes: 6,216,448
- Matching counts (chunks / containers / leaves / padding regions / padding bytes): (6198, 1140, 5058, 524, 115064)

Chunk ID counts from the C++ reader:

- 0x39200: 5
- 0x39201: 5
- 0x39202: 5
- 0x134002: 1
- 0x134003: 1
- 0x134004: 1
- 0x134011: 568
- 0x134012: 568
- 0x134013: 568
- 0x134017: 472
- 0x134018: 472
- 0x134019: 472
- 0x13401a: 216
- 0x134a00: 568
- 0x134a01: 568
- 0x134a02: 568
- 0x80034020: 1
- 0x80134000: 1
- 0x80134001: 1
- 0x80134008: 1
- 0x80134010: 568
- 0x80134100: 568

## CARS\PEUGOT\GEOMETRY.BIN

- File bytes: 7,047,936
- Matching counts (chunks / containers / leaves / padding regions / padding bytes): (6609, 1214, 5395, 572, 129556)

Chunk ID counts from the C++ reader:

- 0x39200: 5
- 0x39201: 5
- 0x39202: 5
- 0x134002: 1
- 0x134003: 1
- 0x134004: 1
- 0x134011: 605
- 0x134012: 605
- 0x134013: 605
- 0x134017: 505
- 0x134018: 505
- 0x134019: 505
- 0x13401a: 232
- 0x134a00: 605
- 0x134a01: 605
- 0x134a02: 605
- 0x80034020: 1
- 0x80134000: 1
- 0x80134001: 1
- 0x80134008: 1
- 0x80134010: 605
- 0x80134100: 605

## CARS\3000GT\GEOMETRY.BIN

- File bytes: 6,689,440
- Matching counts (chunks / containers / leaves / padding regions / padding bytes): (6303, 1162, 5141, 539, 122000)

Chunk ID counts from the C++ reader:

- 0x39200: 5
- 0x39201: 5
- 0x39202: 5
- 0x134002: 1
- 0x134003: 1
- 0x134004: 1
- 0x134011: 579
- 0x134012: 579
- 0x134013: 578
- 0x134017: 478
- 0x134018: 478
- 0x134019: 478
- 0x13401a: 216
- 0x134a00: 579
- 0x134a01: 579
- 0x134a02: 579
- 0x80034020: 1
- 0x80134000: 1
- 0x80134001: 1
- 0x80134008: 1
- 0x80134010: 579
- 0x80134100: 579

## CARS\ESCALADE\GEOMETRY.BIN

- File bytes: 3,131,408
- Matching counts (chunks / containers / leaves / padding regions / padding bytes): (3715, 708, 3007, 327, 59700)

Chunk ID counts from the C++ reader:

- 0x39200: 1
- 0x39201: 1
- 0x39202: 1
- 0x134002: 1
- 0x134003: 1
- 0x134004: 1
- 0x134011: 352
- 0x134012: 352
- 0x134013: 352
- 0x134017: 265
- 0x134018: 265
- 0x134019: 265
- 0x13401a: 94
- 0x134a00: 352
- 0x134a01: 352
- 0x134a02: 352
- 0x80034020: 1
- 0x80134000: 1
- 0x80134001: 1
- 0x80134008: 1
- 0x80134010: 352
- 0x80134100: 352

## CARS\MIRRORS_BODY\GEOMETRY.BIN

- File bytes: 1,115,712
- Matching counts (chunks / containers / leaves / padding regions / padding bytes): (2646, 483, 2163, 238, 26240)

Chunk ID counts from the C++ reader:

- 0x134002: 1
- 0x134003: 1
- 0x134004: 1
- 0x134011: 240
- 0x134012: 240
- 0x134013: 240
- 0x134017: 240
- 0x134018: 240
- 0x134019: 240
- 0x134a00: 240
- 0x134a01: 240
- 0x134a02: 240
- 0x80134000: 1
- 0x80134001: 1
- 0x80134008: 1
- 0x80134010: 240
- 0x80134100: 240

## CARS\LANCEREVO8\GEOMETRY.BIN

- File bytes: 6,523,056
- Matching counts (chunks / containers / leaves / padding regions / padding bytes): (6263, 1148, 5115, 539, 119832)

Chunk ID counts from the C++ reader:

- 0x39200: 5
- 0x39201: 5
- 0x39202: 5
- 0x134002: 1
- 0x134003: 1
- 0x134004: 1
- 0x134011: 572
- 0x134012: 572
- 0x134013: 572
- 0x134017: 483
- 0x134018: 483
- 0x134019: 483
- 0x13401a: 216
- 0x134a00: 572
- 0x134a01: 572
- 0x134a02: 572
- 0x80034020: 1
- 0x80134000: 1
- 0x80134001: 1
- 0x80134008: 1
- 0x80134010: 572
- 0x80134100: 572

