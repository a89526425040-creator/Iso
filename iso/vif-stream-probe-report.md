# PS2 VIF stream probe

- Vehicle resources: 3
- VIF leaf streams parsed: 9
- VIF command lengths and UNPACK payload sizes are bounds-checked; no raw payload bytes are committed.

## CARS\RX7\GEOMETRY.BIN

- VIF leaf count in complete resource: 634

### Stream 0 at 0x5AD0

- Chunk payload bytes: 13416
- Leading 0x11 padding bytes: 8
- Parsed commands: 449
- Command counts: {'MSCAL': 37, 'NOP': 56, 'UNPACK_1x16': 10, 'UNPACK_2x16': 11, 'UNPACK_3x16': 9, 'UNPACK_3x32': 37, 'UNPACK_4x16': 104, 'UNPACK_4x32': 74, 'UNPACK_4x8': 111}
- UNPACK formats: {'0x1': 10, '0x5': 11, '0x8': 37, '0x9': 9, '0xC': 74, '0xD': 104, '0xE': 111}
- UNPACK vectors: 1891
- UNPACK data bytes: 11612
- Remaining 0x11 padding bytes: 0

| Offset | Word | Command | NUM | Immediate | Payload bytes |
|---:|---:|---|---:|---:|---:|
| 0x0 | 0x6E018000 | UNPACK_4x8 | 1 | 0x8000 | 4 |
| 0x8 | 0x6C01C001 | UNPACK_4x32 | 1 | 0xC001 | 16 |
| 0x1C | 0x6802C002 | UNPACK_3x32 | 2 | 0xC002 | 24 |
| 0x38 | 0x6C01C004 | UNPACK_4x32 | 1 | 0xC004 | 16 |
| 0x4C | 0x6D068005 | UNPACK_4x16 | 6 | 0x8005 | 48 |
| 0x80 | 0x6903800B | UNPACK_3x16 | 3 | 0x800B | 20 |
| 0x98 | 0x6D04801D | UNPACK_4x16 | 4 | 0x801D | 32 |
| 0xBC | 0x6D028021 | UNPACK_4x16 | 2 | 0x8021 | 16 |
| 0xD0 | 0x6E0BC02D | UNPACK_4x8 | 11 | 0xC02D | 44 |
| 0x100 | 0x6E09804D | UNPACK_4x8 | 9 | 0x804D | 36 |
| 0x128 | 0x14000000 | MSCAL | 0 | 0x0000 | 0 |
| 0x12C | 0x00000000 | NOP | 0 | 0x0000 | 0 |
| 0x130 | 0x6E018000 | UNPACK_4x8 | 1 | 0x8000 | 4 |
| 0x138 | 0x6C01C001 | UNPACK_4x32 | 1 | 0xC001 | 16 |
| 0x14C | 0x6802C002 | UNPACK_3x32 | 2 | 0xC002 | 24 |
| 0x168 | 0x6C01C004 | UNPACK_4x32 | 1 | 0xC004 | 16 |
| 0x17C | 0x6D128005 | UNPACK_4x16 | 18 | 0x8005 | 144 |
| 0x210 | 0x65038017 | UNPACK_2x16 | 3 | 0x8017 | 12 |
| 0x220 | 0x6D0C801D | UNPACK_4x16 | 12 | 0x801D | 96 |
| 0x284 | 0x6D018029 | UNPACK_4x16 | 1 | 0x8029 | 8 |
| 0x290 | 0x6E1AC02D | UNPACK_4x8 | 26 | 0xC02D | 104 |
| 0x2FC | 0x6E15804D | UNPACK_4x8 | 21 | 0x804D | 84 |
| 0x354 | 0x14000000 | MSCAL | 0 | 0x0000 | 0 |
| 0x358 | 0x00000000 | NOP | 0 | 0x0000 | 0 |
| 0x35C | 0x00000000 | NOP | 0 | 0x0000 | 0 |
| 0x360 | 0x6E018000 | UNPACK_4x8 | 1 | 0x8000 | 4 |
| 0x368 | 0x6C01C001 | UNPACK_4x32 | 1 | 0xC001 | 16 |
| 0x37C | 0x6802C002 | UNPACK_3x32 | 2 | 0xC002 | 24 |
| 0x398 | 0x6C01C004 | UNPACK_4x32 | 1 | 0xC004 | 16 |
| 0x3AC | 0x6D068005 | UNPACK_4x16 | 6 | 0x8005 | 48 |
| 0x3E0 | 0x6503800B | UNPACK_2x16 | 3 | 0x800B | 12 |
| 0x3F0 | 0x6D04801D | UNPACK_4x16 | 4 | 0x801D | 32 |
| 0x414 | 0x6D018021 | UNPACK_4x16 | 1 | 0x8021 | 8 |
| 0x420 | 0x6E0AC02D | UNPACK_4x8 | 10 | 0xC02D | 40 |
| 0x44C | 0x6E09804D | UNPACK_4x8 | 9 | 0x804D | 36 |
| 0x474 | 0x14000000 | MSCAL | 0 | 0x0000 | 0 |
| 0x478 | 0x00000000 | NOP | 0 | 0x0000 | 0 |
| 0x47C | 0x00000000 | NOP | 0 | 0x0000 | 0 |
| 0x480 | 0x6E018000 | UNPACK_4x8 | 1 | 0x8000 | 4 |
| 0x488 | 0x6C01C001 | UNPACK_4x32 | 1 | 0xC001 | 16 |
| … | … | 409 more commands | | | |

### Stream 1 at 0x9940

- Chunk payload bytes: 7576
- Leading 0x11 padding bytes: 8
- Parsed commands: 349
- Command counts: {'MSCAL': 28, 'NOP': 53, 'UNPACK_1x16': 6, 'UNPACK_2x16': 9, 'UNPACK_3x16': 9, 'UNPACK_3x32': 28, 'UNPACK_4x16': 76, 'UNPACK_4x32': 56, 'UNPACK_4x8': 84}
- UNPACK formats: {'0x1': 6, '0x5': 9, '0x8': 28, '0x9': 9, '0xC': 56, '0xD': 76, '0xE': 84}
- UNPACK vectors: 968
- UNPACK data bytes: 6172
- Remaining 0x11 padding bytes: 0

| Offset | Word | Command | NUM | Immediate | Payload bytes |
|---:|---:|---|---:|---:|---:|
| 0x0 | 0x6E018000 | UNPACK_4x8 | 1 | 0x8000 | 4 |
| 0x8 | 0x6C01C001 | UNPACK_4x32 | 1 | 0xC001 | 16 |
| 0x1C | 0x6802C002 | UNPACK_3x32 | 2 | 0xC002 | 24 |
| 0x38 | 0x6C01C004 | UNPACK_4x32 | 1 | 0xC004 | 16 |
| 0x4C | 0x6D068005 | UNPACK_4x16 | 6 | 0x8005 | 48 |
| 0x80 | 0x6103800B | UNPACK_1x16 | 3 | 0x800B | 8 |
| 0x8C | 0x6D04801D | UNPACK_4x16 | 4 | 0x801D | 32 |
| 0xB0 | 0x6D018021 | UNPACK_4x16 | 1 | 0x8021 | 8 |
| 0xBC | 0x6E09C02D | UNPACK_4x8 | 9 | 0xC02D | 36 |
| 0xE4 | 0x6E09804D | UNPACK_4x8 | 9 | 0x804D | 36 |
| 0x10C | 0x14000000 | MSCAL | 0 | 0x0000 | 0 |
| 0x110 | 0x6E018000 | UNPACK_4x8 | 1 | 0x8000 | 4 |
| 0x118 | 0x6C01C001 | UNPACK_4x32 | 1 | 0xC001 | 16 |
| 0x12C | 0x6802C002 | UNPACK_3x32 | 2 | 0xC002 | 24 |
| 0x148 | 0x6C01C004 | UNPACK_4x32 | 1 | 0xC004 | 16 |
| 0x15C | 0x6D098005 | UNPACK_4x16 | 9 | 0x8005 | 72 |
| 0x1A8 | 0x6503800E | UNPACK_2x16 | 3 | 0x800E | 12 |
| 0x1B8 | 0x6D06801D | UNPACK_4x16 | 6 | 0x801D | 48 |
| 0x1EC | 0x6D018023 | UNPACK_4x16 | 1 | 0x8023 | 8 |
| 0x1F8 | 0x6E0EC02D | UNPACK_4x8 | 14 | 0xC02D | 56 |
| 0x234 | 0x6E0C804D | UNPACK_4x8 | 12 | 0x804D | 48 |
| 0x268 | 0x14000000 | MSCAL | 0 | 0x0000 | 0 |
| 0x26C | 0x00000000 | NOP | 0 | 0x0000 | 0 |
| 0x270 | 0x6E018000 | UNPACK_4x8 | 1 | 0x8000 | 4 |
| 0x278 | 0x6C01C001 | UNPACK_4x32 | 1 | 0xC001 | 16 |
| 0x28C | 0x6802C002 | UNPACK_3x32 | 2 | 0xC002 | 24 |
| 0x2A8 | 0x6C01C004 | UNPACK_4x32 | 1 | 0xC004 | 16 |
| 0x2BC | 0x6D068005 | UNPACK_4x16 | 6 | 0x8005 | 48 |
| 0x2F0 | 0x6903800B | UNPACK_3x16 | 3 | 0x800B | 20 |
| 0x308 | 0x6D04801D | UNPACK_4x16 | 4 | 0x801D | 32 |
| 0x32C | 0x6D028021 | UNPACK_4x16 | 2 | 0x8021 | 16 |
| 0x340 | 0x6E0BC02D | UNPACK_4x8 | 11 | 0xC02D | 44 |
| 0x370 | 0x6E09804D | UNPACK_4x8 | 9 | 0x804D | 36 |
| 0x398 | 0x14000000 | MSCAL | 0 | 0x0000 | 0 |
| 0x39C | 0x00000000 | NOP | 0 | 0x0000 | 0 |
| 0x3A0 | 0x6E018000 | UNPACK_4x8 | 1 | 0x8000 | 4 |
| 0x3A8 | 0x6C01C001 | UNPACK_4x32 | 1 | 0xC001 | 16 |
| 0x3BC | 0x6802C002 | UNPACK_3x32 | 2 | 0xC002 | 24 |
| 0x3D8 | 0x6C01C004 | UNPACK_4x32 | 1 | 0xC004 | 16 |
| 0x3EC | 0x6D038005 | UNPACK_4x16 | 3 | 0x8005 | 24 |
| … | … | 309 more commands | | | |

### Stream 2 at 0xB960

- Chunk payload bytes: 4456
- Leading 0x11 padding bytes: 8
- Parsed commands: 204
- Command counts: {'MSCAL': 17, 'NOP': 31, 'UNPACK_1x16': 3, 'UNPACK_2x16': 4, 'UNPACK_3x16': 3, 'UNPACK_3x32': 17, 'UNPACK_4x16': 44, 'UNPACK_4x32': 34, 'UNPACK_4x8': 51}
- UNPACK formats: {'0x1': 3, '0x5': 4, '0x8': 17, '0x9': 3, '0xC': 34, '0xD': 44, '0xE': 51}
- UNPACK vectors: 562
- UNPACK data bytes: 3632
- Remaining 0x11 padding bytes: 0

| Offset | Word | Command | NUM | Immediate | Payload bytes |
|---:|---:|---|---:|---:|---:|
| 0x0 | 0x6E018000 | UNPACK_4x8 | 1 | 0x8000 | 4 |
| 0x8 | 0x6C01C001 | UNPACK_4x32 | 1 | 0xC001 | 16 |
| 0x1C | 0x6802C002 | UNPACK_3x32 | 2 | 0xC002 | 24 |
| 0x38 | 0x6C01C004 | UNPACK_4x32 | 1 | 0xC004 | 16 |
| 0x4C | 0x6D068005 | UNPACK_4x16 | 6 | 0x8005 | 48 |
| 0x80 | 0x6103800B | UNPACK_1x16 | 3 | 0x800B | 8 |
| 0x8C | 0x6D04801D | UNPACK_4x16 | 4 | 0x801D | 32 |
| 0xB0 | 0x6D018021 | UNPACK_4x16 | 1 | 0x8021 | 8 |
| 0xBC | 0x6E09C02D | UNPACK_4x8 | 9 | 0xC02D | 36 |
| 0xE4 | 0x6E09804D | UNPACK_4x8 | 9 | 0x804D | 36 |
| 0x10C | 0x14000000 | MSCAL | 0 | 0x0000 | 0 |
| 0x110 | 0x6E018000 | UNPACK_4x8 | 1 | 0x8000 | 4 |
| 0x118 | 0x6C01C001 | UNPACK_4x32 | 1 | 0xC001 | 16 |
| 0x12C | 0x6802C002 | UNPACK_3x32 | 2 | 0xC002 | 24 |
| 0x148 | 0x6C01C004 | UNPACK_4x32 | 1 | 0xC004 | 16 |
| 0x15C | 0x6D068005 | UNPACK_4x16 | 6 | 0x8005 | 48 |
| 0x190 | 0x6D04801D | UNPACK_4x16 | 4 | 0x801D | 32 |
| 0x1B4 | 0x6E08C02D | UNPACK_4x8 | 8 | 0xC02D | 32 |
| 0x1D8 | 0x6E06804D | UNPACK_4x8 | 6 | 0x804D | 24 |
| 0x1F4 | 0x14000000 | MSCAL | 0 | 0x0000 | 0 |
| 0x1F8 | 0x00000000 | NOP | 0 | 0x0000 | 0 |
| 0x1FC | 0x00000000 | NOP | 0 | 0x0000 | 0 |
| 0x200 | 0x6E018000 | UNPACK_4x8 | 1 | 0x8000 | 4 |
| 0x208 | 0x6C01C001 | UNPACK_4x32 | 1 | 0xC001 | 16 |
| 0x21C | 0x6802C002 | UNPACK_3x32 | 2 | 0xC002 | 24 |
| 0x238 | 0x6C01C004 | UNPACK_4x32 | 1 | 0xC004 | 16 |
| 0x24C | 0x6D068005 | UNPACK_4x16 | 6 | 0x8005 | 48 |
| 0x280 | 0x6503800B | UNPACK_2x16 | 3 | 0x800B | 12 |
| 0x290 | 0x6D04801D | UNPACK_4x16 | 4 | 0x801D | 32 |
| 0x2B4 | 0x6D018021 | UNPACK_4x16 | 1 | 0x8021 | 8 |
| 0x2C0 | 0x6E0AC02D | UNPACK_4x8 | 10 | 0xC02D | 40 |
| 0x2EC | 0x6E09804D | UNPACK_4x8 | 9 | 0x804D | 36 |
| 0x314 | 0x14000000 | MSCAL | 0 | 0x0000 | 0 |
| 0x318 | 0x00000000 | NOP | 0 | 0x0000 | 0 |
| 0x31C | 0x00000000 | NOP | 0 | 0x0000 | 0 |
| 0x320 | 0x6E018000 | UNPACK_4x8 | 1 | 0x8000 | 4 |
| 0x328 | 0x6C01C001 | UNPACK_4x32 | 1 | 0xC001 | 16 |
| 0x33C | 0x6802C002 | UNPACK_3x32 | 2 | 0xC002 | 24 |
| 0x358 | 0x6C01C004 | UNPACK_4x32 | 1 | 0xC004 | 16 |
| 0x36C | 0x6D038005 | UNPACK_4x16 | 3 | 0x8005 | 24 |
| … | … | 164 more commands | | | |

## CARS\CELICA\GEOMETRY.BIN

- VIF leaf count in complete resource: 609

### Stream 0 at 0x5A00

- Chunk payload bytes: 22824
- Leading 0x11 padding bytes: 8
- Parsed commands: 755
- Command counts: {'MSCAL': 64, 'NOP': 103, 'UNPACK_1x16': 13, 'UNPACK_2x16': 12, 'UNPACK_3x16': 13, 'UNPACK_3x32': 64, 'UNPACK_4x16': 166, 'UNPACK_4x32': 128, 'UNPACK_4x8': 192}
- UNPACK formats: {'0x1': 13, '0x5': 12, '0x8': 64, '0x9': 13, '0xC': 128, '0xD': 166, '0xE': 192}
- UNPACK vectors: 3195
- UNPACK data bytes: 19796
- Remaining 0x11 padding bytes: 0

| Offset | Word | Command | NUM | Immediate | Payload bytes |
|---:|---:|---|---:|---:|---:|
| 0x0 | 0x6E018000 | UNPACK_4x8 | 1 | 0x8000 | 4 |
| 0x8 | 0x6C01C001 | UNPACK_4x32 | 1 | 0xC001 | 16 |
| 0x1C | 0x6802C002 | UNPACK_3x32 | 2 | 0xC002 | 24 |
| 0x38 | 0x6C01C004 | UNPACK_4x32 | 1 | 0xC004 | 16 |
| 0x4C | 0x6D038005 | UNPACK_4x16 | 3 | 0x8005 | 24 |
| 0x68 | 0x6D02801D | UNPACK_4x16 | 2 | 0x801D | 16 |
| 0x7C | 0x6E04C02D | UNPACK_4x8 | 4 | 0xC02D | 16 |
| 0x90 | 0x6E03804D | UNPACK_4x8 | 3 | 0x804D | 12 |
| 0xA0 | 0x14000000 | MSCAL | 0 | 0x0000 | 0 |
| 0xA4 | 0x00000000 | NOP | 0 | 0x0000 | 0 |
| 0xA8 | 0x00000000 | NOP | 0 | 0x0000 | 0 |
| 0xAC | 0x00000000 | NOP | 0 | 0x0000 | 0 |
| 0xB0 | 0x6E018000 | UNPACK_4x8 | 1 | 0x8000 | 4 |
| 0xB8 | 0x6C01C001 | UNPACK_4x32 | 1 | 0xC001 | 16 |
| 0xCC | 0x6802C002 | UNPACK_3x32 | 2 | 0xC002 | 24 |
| 0xE8 | 0x6C01C004 | UNPACK_4x32 | 1 | 0xC004 | 16 |
| 0xFC | 0x6D038005 | UNPACK_4x16 | 3 | 0x8005 | 24 |
| 0x118 | 0x6D02801D | UNPACK_4x16 | 2 | 0x801D | 16 |
| 0x12C | 0x6E04C02D | UNPACK_4x8 | 4 | 0xC02D | 16 |
| 0x140 | 0x6E03804D | UNPACK_4x8 | 3 | 0x804D | 12 |
| 0x150 | 0x14000000 | MSCAL | 0 | 0x0000 | 0 |
| 0x154 | 0x00000000 | NOP | 0 | 0x0000 | 0 |
| 0x158 | 0x00000000 | NOP | 0 | 0x0000 | 0 |
| 0x15C | 0x00000000 | NOP | 0 | 0x0000 | 0 |
| 0x160 | 0x6E018000 | UNPACK_4x8 | 1 | 0x8000 | 4 |
| 0x168 | 0x6C01C001 | UNPACK_4x32 | 1 | 0xC001 | 16 |
| 0x17C | 0x6802C002 | UNPACK_3x32 | 2 | 0xC002 | 24 |
| 0x198 | 0x6C01C004 | UNPACK_4x32 | 1 | 0xC004 | 16 |
| 0x1AC | 0x6D038005 | UNPACK_4x16 | 3 | 0x8005 | 24 |
| 0x1C8 | 0x6D02801D | UNPACK_4x16 | 2 | 0x801D | 16 |
| 0x1DC | 0x6E04C02D | UNPACK_4x8 | 4 | 0xC02D | 16 |
| 0x1F0 | 0x6E03804D | UNPACK_4x8 | 3 | 0x804D | 12 |
| 0x200 | 0x14000000 | MSCAL | 0 | 0x0000 | 0 |
| 0x204 | 0x00000000 | NOP | 0 | 0x0000 | 0 |
| 0x208 | 0x00000000 | NOP | 0 | 0x0000 | 0 |
| 0x20C | 0x00000000 | NOP | 0 | 0x0000 | 0 |
| 0x210 | 0x6E018000 | UNPACK_4x8 | 1 | 0x8000 | 4 |
| 0x218 | 0x6C01C001 | UNPACK_4x32 | 1 | 0xC001 | 16 |
| 0x22C | 0x6802C002 | UNPACK_3x32 | 2 | 0xC002 | 24 |
| 0x248 | 0x6C01C004 | UNPACK_4x32 | 1 | 0xC004 | 16 |
| … | … | 715 more commands | | | |

### Stream 1 at 0xBDB0

- Chunk payload bytes: 6360
- Leading 0x11 padding bytes: 8
- Parsed commands: 289
- Command counts: {'MSCAL': 24, 'NOP': 47, 'UNPACK_1x16': 4, 'UNPACK_2x16': 5, 'UNPACK_3x16': 5, 'UNPACK_3x32': 24, 'UNPACK_4x16': 60, 'UNPACK_4x32': 48, 'UNPACK_4x8': 72}
- UNPACK formats: {'0x1': 4, '0x5': 5, '0x8': 24, '0x9': 5, '0xC': 48, '0xD': 60, '0xE': 72}
- UNPACK vectors: 804
- UNPACK data bytes: 5196
- Remaining 0x11 padding bytes: 0

| Offset | Word | Command | NUM | Immediate | Payload bytes |
|---:|---:|---|---:|---:|---:|
| 0x0 | 0x6E018000 | UNPACK_4x8 | 1 | 0x8000 | 4 |
| 0x8 | 0x6C01C001 | UNPACK_4x32 | 1 | 0xC001 | 16 |
| 0x1C | 0x6802C002 | UNPACK_3x32 | 2 | 0xC002 | 24 |
| 0x38 | 0x6C01C004 | UNPACK_4x32 | 1 | 0xC004 | 16 |
| 0x4C | 0x6D038005 | UNPACK_4x16 | 3 | 0x8005 | 24 |
| 0x68 | 0x6D02801D | UNPACK_4x16 | 2 | 0x801D | 16 |
| 0x7C | 0x6E04C02D | UNPACK_4x8 | 4 | 0xC02D | 16 |
| 0x90 | 0x6E03804D | UNPACK_4x8 | 3 | 0x804D | 12 |
| 0xA0 | 0x14000000 | MSCAL | 0 | 0x0000 | 0 |
| 0xA4 | 0x00000000 | NOP | 0 | 0x0000 | 0 |
| 0xA8 | 0x00000000 | NOP | 0 | 0x0000 | 0 |
| 0xAC | 0x00000000 | NOP | 0 | 0x0000 | 0 |
| 0xB0 | 0x6E018000 | UNPACK_4x8 | 1 | 0x8000 | 4 |
| 0xB8 | 0x6C01C001 | UNPACK_4x32 | 1 | 0xC001 | 16 |
| 0xCC | 0x6802C002 | UNPACK_3x32 | 2 | 0xC002 | 24 |
| 0xE8 | 0x6C01C004 | UNPACK_4x32 | 1 | 0xC004 | 16 |
| 0xFC | 0x6D038005 | UNPACK_4x16 | 3 | 0x8005 | 24 |
| 0x118 | 0x6D02801D | UNPACK_4x16 | 2 | 0x801D | 16 |
| 0x12C | 0x6E04C02D | UNPACK_4x8 | 4 | 0xC02D | 16 |
| 0x140 | 0x6E03804D | UNPACK_4x8 | 3 | 0x804D | 12 |
| 0x150 | 0x14000000 | MSCAL | 0 | 0x0000 | 0 |
| 0x154 | 0x00000000 | NOP | 0 | 0x0000 | 0 |
| 0x158 | 0x00000000 | NOP | 0 | 0x0000 | 0 |
| 0x15C | 0x00000000 | NOP | 0 | 0x0000 | 0 |
| 0x160 | 0x6E018000 | UNPACK_4x8 | 1 | 0x8000 | 4 |
| 0x168 | 0x6C01C001 | UNPACK_4x32 | 1 | 0xC001 | 16 |
| 0x17C | 0x6802C002 | UNPACK_3x32 | 2 | 0xC002 | 24 |
| 0x198 | 0x6C01C004 | UNPACK_4x32 | 1 | 0xC004 | 16 |
| 0x1AC | 0x6D038005 | UNPACK_4x16 | 3 | 0x8005 | 24 |
| 0x1C8 | 0x6D02801D | UNPACK_4x16 | 2 | 0x801D | 16 |
| 0x1DC | 0x6E04C02D | UNPACK_4x8 | 4 | 0xC02D | 16 |
| 0x1F0 | 0x6E03804D | UNPACK_4x8 | 3 | 0x804D | 12 |
| 0x200 | 0x14000000 | MSCAL | 0 | 0x0000 | 0 |
| 0x204 | 0x00000000 | NOP | 0 | 0x0000 | 0 |
| 0x208 | 0x00000000 | NOP | 0 | 0x0000 | 0 |
| 0x20C | 0x00000000 | NOP | 0 | 0x0000 | 0 |
| 0x210 | 0x6E018000 | UNPACK_4x8 | 1 | 0x8000 | 4 |
| 0x218 | 0x6C01C001 | UNPACK_4x32 | 1 | 0xC001 | 16 |
| 0x22C | 0x6802C002 | UNPACK_3x32 | 2 | 0xC002 | 24 |
| 0x248 | 0x6C01C004 | UNPACK_4x32 | 1 | 0xC004 | 16 |
| … | … | 249 more commands | | | |

### Stream 2 at 0xD840

- Chunk payload bytes: 952
- Leading 0x11 padding bytes: 8
- Parsed commands: 49
- Command counts: {'MSCAL': 4, 'NOP': 9, 'UNPACK_2x16': 1, 'UNPACK_3x16': 1, 'UNPACK_3x32': 4, 'UNPACK_4x16': 10, 'UNPACK_4x32': 8, 'UNPACK_4x8': 12}
- UNPACK formats: {'0x5': 1, '0x8': 4, '0x9': 1, '0xC': 8, '0xD': 10, '0xE': 12}
- UNPACK vectors: 112
- UNPACK data bytes: 748
- Remaining 0x11 padding bytes: 0

| Offset | Word | Command | NUM | Immediate | Payload bytes |
|---:|---:|---|---:|---:|---:|
| 0x0 | 0x6E018000 | UNPACK_4x8 | 1 | 0x8000 | 4 |
| 0x8 | 0x6C01C001 | UNPACK_4x32 | 1 | 0xC001 | 16 |
| 0x1C | 0x6802C002 | UNPACK_3x32 | 2 | 0xC002 | 24 |
| 0x38 | 0x6C01C004 | UNPACK_4x32 | 1 | 0xC004 | 16 |
| 0x4C | 0x6D068005 | UNPACK_4x16 | 6 | 0x8005 | 48 |
| 0x80 | 0x6903800B | UNPACK_3x16 | 3 | 0x800B | 20 |
| 0x98 | 0x6D04801D | UNPACK_4x16 | 4 | 0x801D | 32 |
| 0xBC | 0x6D028021 | UNPACK_4x16 | 2 | 0x8021 | 16 |
| 0xD0 | 0x6E0BC02D | UNPACK_4x8 | 11 | 0xC02D | 44 |
| 0x100 | 0x6E09804D | UNPACK_4x8 | 9 | 0x804D | 36 |
| 0x128 | 0x14000000 | MSCAL | 0 | 0x0000 | 0 |
| 0x12C | 0x00000000 | NOP | 0 | 0x0000 | 0 |
| 0x130 | 0x6E018000 | UNPACK_4x8 | 1 | 0x8000 | 4 |
| 0x138 | 0x6C01C001 | UNPACK_4x32 | 1 | 0xC001 | 16 |
| 0x14C | 0x6802C002 | UNPACK_3x32 | 2 | 0xC002 | 24 |
| 0x168 | 0x6C01C004 | UNPACK_4x32 | 1 | 0xC004 | 16 |
| 0x17C | 0x6D038005 | UNPACK_4x16 | 3 | 0x8005 | 24 |
| 0x198 | 0x6D02801D | UNPACK_4x16 | 2 | 0x801D | 16 |
| 0x1AC | 0x6E04C02D | UNPACK_4x8 | 4 | 0xC02D | 16 |
| 0x1C0 | 0x6E03804D | UNPACK_4x8 | 3 | 0x804D | 12 |
| 0x1D0 | 0x14000000 | MSCAL | 0 | 0x0000 | 0 |
| 0x1D4 | 0x00000000 | NOP | 0 | 0x0000 | 0 |
| 0x1D8 | 0x00000000 | NOP | 0 | 0x0000 | 0 |
| 0x1DC | 0x00000000 | NOP | 0 | 0x0000 | 0 |
| 0x1E0 | 0x6E018000 | UNPACK_4x8 | 1 | 0x8000 | 4 |
| 0x1E8 | 0x6C01C001 | UNPACK_4x32 | 1 | 0xC001 | 16 |
| 0x1FC | 0x6802C002 | UNPACK_3x32 | 2 | 0xC002 | 24 |
| 0x218 | 0x6C01C004 | UNPACK_4x32 | 1 | 0xC004 | 16 |
| 0x22C | 0x6D038005 | UNPACK_4x16 | 3 | 0x8005 | 24 |
| 0x248 | 0x6D02801D | UNPACK_4x16 | 2 | 0x801D | 16 |
| 0x25C | 0x6E04C02D | UNPACK_4x8 | 4 | 0xC02D | 16 |
| 0x270 | 0x6E03804D | UNPACK_4x8 | 3 | 0x804D | 12 |
| 0x280 | 0x14000000 | MSCAL | 0 | 0x0000 | 0 |
| 0x284 | 0x00000000 | NOP | 0 | 0x0000 | 0 |
| 0x288 | 0x00000000 | NOP | 0 | 0x0000 | 0 |
| 0x28C | 0x00000000 | NOP | 0 | 0x0000 | 0 |
| 0x290 | 0x6E018000 | UNPACK_4x8 | 1 | 0x8000 | 4 |
| 0x298 | 0x6C01C001 | UNPACK_4x32 | 1 | 0xC001 | 16 |
| 0x2AC | 0x6802C002 | UNPACK_3x32 | 2 | 0xC002 | 24 |
| 0x2C8 | 0x6C01C004 | UNPACK_4x32 | 1 | 0xC004 | 16 |
| … | … | 9 more commands | | | |

## CARS\IS300\GEOMETRY.BIN

- VIF leaf count in complete resource: 568

### Stream 0 at 0x5460

- Chunk payload bytes: 18056
- Leading 0x11 padding bytes: 8
- Parsed commands: 665
- Command counts: {'MSCAL': 54, 'NOP': 105, 'UNPACK_1x16': 14, 'UNPACK_2x16': 11, 'UNPACK_3x16': 12, 'UNPACK_3x32': 54, 'UNPACK_4x16': 145, 'UNPACK_4x32': 108, 'UNPACK_4x8': 162}
- UNPACK formats: {'0x1': 14, '0x5': 11, '0x8': 54, '0x9': 12, '0xC': 108, '0xD': 145, '0xE': 162}
- UNPACK vectors: 2473
- UNPACK data bytes: 15388
- Remaining 0x11 padding bytes: 0

| Offset | Word | Command | NUM | Immediate | Payload bytes |
|---:|---:|---|---:|---:|---:|
| 0x0 | 0x6E018000 | UNPACK_4x8 | 1 | 0x8000 | 4 |
| 0x8 | 0x6C01C001 | UNPACK_4x32 | 1 | 0xC001 | 16 |
| 0x1C | 0x6802C002 | UNPACK_3x32 | 2 | 0xC002 | 24 |
| 0x38 | 0x6C01C004 | UNPACK_4x32 | 1 | 0xC004 | 16 |
| 0x4C | 0x6D038005 | UNPACK_4x16 | 3 | 0x8005 | 24 |
| 0x68 | 0x6D02801D | UNPACK_4x16 | 2 | 0x801D | 16 |
| 0x7C | 0x6E04C02D | UNPACK_4x8 | 4 | 0xC02D | 16 |
| 0x90 | 0x6E03804D | UNPACK_4x8 | 3 | 0x804D | 12 |
| 0xA0 | 0x14000000 | MSCAL | 0 | 0x0000 | 0 |
| 0xA4 | 0x00000000 | NOP | 0 | 0x0000 | 0 |
| 0xA8 | 0x00000000 | NOP | 0 | 0x0000 | 0 |
| 0xAC | 0x00000000 | NOP | 0 | 0x0000 | 0 |
| 0xB0 | 0x6E018000 | UNPACK_4x8 | 1 | 0x8000 | 4 |
| 0xB8 | 0x6C01C001 | UNPACK_4x32 | 1 | 0xC001 | 16 |
| 0xCC | 0x6802C002 | UNPACK_3x32 | 2 | 0xC002 | 24 |
| 0xE8 | 0x6C01C004 | UNPACK_4x32 | 1 | 0xC004 | 16 |
| 0xFC | 0x6D038005 | UNPACK_4x16 | 3 | 0x8005 | 24 |
| 0x118 | 0x6D02801D | UNPACK_4x16 | 2 | 0x801D | 16 |
| 0x12C | 0x6E04C02D | UNPACK_4x8 | 4 | 0xC02D | 16 |
| 0x140 | 0x6E03804D | UNPACK_4x8 | 3 | 0x804D | 12 |
| 0x150 | 0x14000000 | MSCAL | 0 | 0x0000 | 0 |
| 0x154 | 0x00000000 | NOP | 0 | 0x0000 | 0 |
| 0x158 | 0x00000000 | NOP | 0 | 0x0000 | 0 |
| 0x15C | 0x00000000 | NOP | 0 | 0x0000 | 0 |
| 0x160 | 0x6E018000 | UNPACK_4x8 | 1 | 0x8000 | 4 |
| 0x168 | 0x6C01C001 | UNPACK_4x32 | 1 | 0xC001 | 16 |
| 0x17C | 0x6802C002 | UNPACK_3x32 | 2 | 0xC002 | 24 |
| 0x198 | 0x6C01C004 | UNPACK_4x32 | 1 | 0xC004 | 16 |
| 0x1AC | 0x6D038005 | UNPACK_4x16 | 3 | 0x8005 | 24 |
| 0x1C8 | 0x6D02801D | UNPACK_4x16 | 2 | 0x801D | 16 |
| 0x1DC | 0x6E04C02D | UNPACK_4x8 | 4 | 0xC02D | 16 |
| 0x1F0 | 0x6E03804D | UNPACK_4x8 | 3 | 0x804D | 12 |
| 0x200 | 0x14000000 | MSCAL | 0 | 0x0000 | 0 |
| 0x204 | 0x00000000 | NOP | 0 | 0x0000 | 0 |
| 0x208 | 0x00000000 | NOP | 0 | 0x0000 | 0 |
| 0x20C | 0x00000000 | NOP | 0 | 0x0000 | 0 |
| 0x210 | 0x6E018000 | UNPACK_4x8 | 1 | 0x8000 | 4 |
| 0x218 | 0x6C01C001 | UNPACK_4x32 | 1 | 0xC001 | 16 |
| 0x22C | 0x6802C002 | UNPACK_3x32 | 2 | 0xC002 | 24 |
| 0x248 | 0x6C01C004 | UNPACK_4x32 | 1 | 0xC004 | 16 |
| … | … | 625 more commands | | | |

### Stream 1 at 0xA690

- Chunk payload bytes: 12456
- Leading 0x11 padding bytes: 8
- Parsed commands: 492
- Command counts: {'MSCAL': 41, 'NOP': 69, 'UNPACK_1x16': 14, 'UNPACK_2x16': 6, 'UNPACK_3x16': 10, 'UNPACK_3x32': 41, 'UNPACK_4x16': 106, 'UNPACK_4x32': 82, 'UNPACK_4x8': 123}
- UNPACK formats: {'0x1': 14, '0x5': 6, '0x8': 41, '0x9': 10, '0xC': 82, '0xD': 106, '0xE': 123}
- UNPACK vectors: 1669
- UNPACK data bytes: 10480
- Remaining 0x11 padding bytes: 0

| Offset | Word | Command | NUM | Immediate | Payload bytes |
|---:|---:|---|---:|---:|---:|
| 0x0 | 0x6E018000 | UNPACK_4x8 | 1 | 0x8000 | 4 |
| 0x8 | 0x6C01C001 | UNPACK_4x32 | 1 | 0xC001 | 16 |
| 0x1C | 0x6802C002 | UNPACK_3x32 | 2 | 0xC002 | 24 |
| 0x38 | 0x6C01C004 | UNPACK_4x32 | 1 | 0xC004 | 16 |
| 0x4C | 0x6D038005 | UNPACK_4x16 | 3 | 0x8005 | 24 |
| 0x68 | 0x6D02801D | UNPACK_4x16 | 2 | 0x801D | 16 |
| 0x7C | 0x6E04C02D | UNPACK_4x8 | 4 | 0xC02D | 16 |
| 0x90 | 0x6E03804D | UNPACK_4x8 | 3 | 0x804D | 12 |
| 0xA0 | 0x14000000 | MSCAL | 0 | 0x0000 | 0 |
| 0xA4 | 0x00000000 | NOP | 0 | 0x0000 | 0 |
| 0xA8 | 0x00000000 | NOP | 0 | 0x0000 | 0 |
| 0xAC | 0x00000000 | NOP | 0 | 0x0000 | 0 |
| 0xB0 | 0x6E018000 | UNPACK_4x8 | 1 | 0x8000 | 4 |
| 0xB8 | 0x6C01C001 | UNPACK_4x32 | 1 | 0xC001 | 16 |
| 0xCC | 0x6802C002 | UNPACK_3x32 | 2 | 0xC002 | 24 |
| 0xE8 | 0x6C01C004 | UNPACK_4x32 | 1 | 0xC004 | 16 |
| 0xFC | 0x6D038005 | UNPACK_4x16 | 3 | 0x8005 | 24 |
| 0x118 | 0x6D02801D | UNPACK_4x16 | 2 | 0x801D | 16 |
| 0x12C | 0x6E04C02D | UNPACK_4x8 | 4 | 0xC02D | 16 |
| 0x140 | 0x6E03804D | UNPACK_4x8 | 3 | 0x804D | 12 |
| 0x150 | 0x14000000 | MSCAL | 0 | 0x0000 | 0 |
| 0x154 | 0x00000000 | NOP | 0 | 0x0000 | 0 |
| 0x158 | 0x00000000 | NOP | 0 | 0x0000 | 0 |
| 0x15C | 0x00000000 | NOP | 0 | 0x0000 | 0 |
| 0x160 | 0x6E018000 | UNPACK_4x8 | 1 | 0x8000 | 4 |
| 0x168 | 0x6C01C001 | UNPACK_4x32 | 1 | 0xC001 | 16 |
| 0x17C | 0x6802C002 | UNPACK_3x32 | 2 | 0xC002 | 24 |
| 0x198 | 0x6C01C004 | UNPACK_4x32 | 1 | 0xC004 | 16 |
| 0x1AC | 0x6D038005 | UNPACK_4x16 | 3 | 0x8005 | 24 |
| 0x1C8 | 0x6D02801D | UNPACK_4x16 | 2 | 0x801D | 16 |
| 0x1DC | 0x6E04C02D | UNPACK_4x8 | 4 | 0xC02D | 16 |
| 0x1F0 | 0x6E03804D | UNPACK_4x8 | 3 | 0x804D | 12 |
| 0x200 | 0x14000000 | MSCAL | 0 | 0x0000 | 0 |
| 0x204 | 0x00000000 | NOP | 0 | 0x0000 | 0 |
| 0x208 | 0x00000000 | NOP | 0 | 0x0000 | 0 |
| 0x20C | 0x00000000 | NOP | 0 | 0x0000 | 0 |
| 0x210 | 0x6E018000 | UNPACK_4x8 | 1 | 0x8000 | 4 |
| 0x218 | 0x6C01C001 | UNPACK_4x32 | 1 | 0xC001 | 16 |
| 0x22C | 0x6802C002 | UNPACK_3x32 | 2 | 0xC002 | 24 |
| 0x248 | 0x6C01C004 | UNPACK_4x32 | 1 | 0xC004 | 16 |
| … | … | 452 more commands | | | |

### Stream 2 at 0xD920

- Chunk payload bytes: 2216
- Leading 0x11 padding bytes: 8
- Parsed commands: 99
- Command counts: {'MSCAL': 8, 'NOP': 17, 'UNPACK_1x16': 3, 'UNPACK_2x16': 2, 'UNPACK_3x32': 8, 'UNPACK_4x16': 21, 'UNPACK_4x32': 16, 'UNPACK_4x8': 24}
- UNPACK formats: {'0x1': 3, '0x5': 2, '0x8': 8, '0xC': 16, '0xD': 21, '0xE': 24}
- UNPACK vectors: 286
- UNPACK data bytes: 1812
- Remaining 0x11 padding bytes: 0

| Offset | Word | Command | NUM | Immediate | Payload bytes |
|---:|---:|---|---:|---:|---:|
| 0x0 | 0x6E018000 | UNPACK_4x8 | 1 | 0x8000 | 4 |
| 0x8 | 0x6C01C001 | UNPACK_4x32 | 1 | 0xC001 | 16 |
| 0x1C | 0x6802C002 | UNPACK_3x32 | 2 | 0xC002 | 24 |
| 0x38 | 0x6C01C004 | UNPACK_4x32 | 1 | 0xC004 | 16 |
| 0x4C | 0x6D038005 | UNPACK_4x16 | 3 | 0x8005 | 24 |
| 0x68 | 0x6D02801D | UNPACK_4x16 | 2 | 0x801D | 16 |
| 0x7C | 0x6E04C02D | UNPACK_4x8 | 4 | 0xC02D | 16 |
| 0x90 | 0x6E03804D | UNPACK_4x8 | 3 | 0x804D | 12 |
| 0xA0 | 0x14000000 | MSCAL | 0 | 0x0000 | 0 |
| 0xA4 | 0x00000000 | NOP | 0 | 0x0000 | 0 |
| 0xA8 | 0x00000000 | NOP | 0 | 0x0000 | 0 |
| 0xAC | 0x00000000 | NOP | 0 | 0x0000 | 0 |
| 0xB0 | 0x6E018000 | UNPACK_4x8 | 1 | 0x8000 | 4 |
| 0xB8 | 0x6C01C001 | UNPACK_4x32 | 1 | 0xC001 | 16 |
| 0xCC | 0x6802C002 | UNPACK_3x32 | 2 | 0xC002 | 24 |
| 0xE8 | 0x6C01C004 | UNPACK_4x32 | 1 | 0xC004 | 16 |
| 0xFC | 0x6D038005 | UNPACK_4x16 | 3 | 0x8005 | 24 |
| 0x118 | 0x6D02801D | UNPACK_4x16 | 2 | 0x801D | 16 |
| 0x12C | 0x6E04C02D | UNPACK_4x8 | 4 | 0xC02D | 16 |
| 0x140 | 0x6E03804D | UNPACK_4x8 | 3 | 0x804D | 12 |
| 0x150 | 0x14000000 | MSCAL | 0 | 0x0000 | 0 |
| 0x154 | 0x00000000 | NOP | 0 | 0x0000 | 0 |
| 0x158 | 0x00000000 | NOP | 0 | 0x0000 | 0 |
| 0x15C | 0x00000000 | NOP | 0 | 0x0000 | 0 |
| 0x160 | 0x6E018000 | UNPACK_4x8 | 1 | 0x8000 | 4 |
| 0x168 | 0x6C01C001 | UNPACK_4x32 | 1 | 0xC001 | 16 |
| 0x17C | 0x6802C002 | UNPACK_3x32 | 2 | 0xC002 | 24 |
| 0x198 | 0x6C01C004 | UNPACK_4x32 | 1 | 0xC004 | 16 |
| 0x1AC | 0x6D038005 | UNPACK_4x16 | 3 | 0x8005 | 24 |
| 0x1C8 | 0x6D02801D | UNPACK_4x16 | 2 | 0x801D | 16 |
| 0x1DC | 0x6E04C02D | UNPACK_4x8 | 4 | 0xC02D | 16 |
| 0x1F0 | 0x6E03804D | UNPACK_4x8 | 3 | 0x804D | 12 |
| 0x200 | 0x14000000 | MSCAL | 0 | 0x0000 | 0 |
| 0x204 | 0x00000000 | NOP | 0 | 0x0000 | 0 |
| 0x208 | 0x00000000 | NOP | 0 | 0x0000 | 0 |
| 0x20C | 0x00000000 | NOP | 0 | 0x0000 | 0 |
| 0x210 | 0x6E018000 | UNPACK_4x8 | 1 | 0x8000 | 4 |
| 0x218 | 0x6C01C001 | UNPACK_4x32 | 1 | 0xC001 | 16 |
| 0x22C | 0x6802C002 | UNPACK_3x32 | 2 | 0xC002 | 24 |
| 0x248 | 0x6C01C004 | UNPACK_4x32 | 1 | 0xC004 | 16 |
| … | … | 59 more commands | | | |

