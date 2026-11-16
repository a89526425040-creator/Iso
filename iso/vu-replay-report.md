# PS2 RX7 VIF1/VU1 replay

- Vehicle resource: CARS\RX7\GEOMETRY.BIN
- Candidate DVP programs at VU address 0: 2
- Supporting DVP programs preloaded: [{'program_id': '903966091', 'vu_start': 2048, 'bytes': 12288}, {'program_id': '903972827', 'vu_start': 14336, 'bytes': 1632}]
- Geometry VIF streams: 3
- Replay attempts: 6
- VU memory/register dumps and GIF packet captures are kept as a workflow artifact, not committed.

## Program 463841659 / stream 0

- VU code bytes / pairs: 16 / 2
- E-bit instructions / XGKICK instructions: 0 / 0
- Return code: 0
- GIF bytes / path-1 quadwords: 0 / 0
- GIF tags / EOP packets: 0 / 0
- GIF parse errors: 0
- VU dumps: []


```text
ps2kit: VIF1: a filled vector takes data (0)
ps2kit: VIF1: word 3951B717 at stream offset 36A0 is not a code; before it (STCYCL 0000):
  0: 4A000100, 2048 bytes of data
  804: 4A000200, 2048 bytes of data
  1008: 4A000300, 2048 bytes of data
  180C: 4A000400, 2048 bytes of data
  2010: 4A000500, 2048 bytes of data
  2814: 4A000600, 2048 bytes of data
  3018: 4ACC0700, 1632 bytes of data
  367C: 4A020000, 16 bytes of data
  3690: 6E018000, 0 bytes of data
  3694: 0007020B, 0 bytes of data
  3698: 6C01C001, 0 bytes of data
  369C: 00006000, 0 bytes of data
  the 13392 bytes waiting are dropped

```

```text
Input VIF bytes: 27376
Captured GIF bytes: 0
VIF1 status:  NOP 2 MPG 8 UNPACK V4-32 1 UNPACK V4-8 1; bytes: UNPACK 0 MPG 13936 DIRECT 0; misaligned 4, TTE 0, lost its place 1

```

## Program 463841659 / stream 1

- VU code bytes / pairs: 16 / 2
- E-bit instructions / XGKICK instructions: 0 / 0
- Return code: 0
- GIF bytes / path-1 quadwords: 0 / 0
- GIF tags / EOP packets: 0 / 0
- GIF parse errors: 0
- VU dumps: []


```text
ps2kit: VIF1: a filled vector takes data (0)
ps2kit: VIF1: word 3951B717 at stream offset 36A0 is not a code; before it (STCYCL 0000):
  0: 4A000100, 2048 bytes of data
  804: 4A000200, 2048 bytes of data
  1008: 4A000300, 2048 bytes of data
  180C: 4A000400, 2048 bytes of data
  2010: 4A000500, 2048 bytes of data
  2814: 4A000600, 2048 bytes of data
  3018: 4ACC0700, 1632 bytes of data
  367C: 4A020000, 16 bytes of data
  3690: 6E018000, 0 bytes of data
  3694: 00070209, 0 bytes of data
  3698: 6C01C001, 0 bytes of data
  369C: 00006000, 0 bytes of data
  the 7552 bytes waiting are dropped

```

```text
Input VIF bytes: 21536
Captured GIF bytes: 0
VIF1 status:  NOP 2 MPG 8 UNPACK V4-32 1 UNPACK V4-8 1; bytes: UNPACK 0 MPG 13936 DIRECT 0; misaligned 4, TTE 0, lost its place 1

```

## Program 463841659 / stream 2

- VU code bytes / pairs: 16 / 2
- E-bit instructions / XGKICK instructions: 0 / 0
- Return code: 0
- GIF bytes / path-1 quadwords: 0 / 0
- GIF tags / EOP packets: 0 / 0
- GIF parse errors: 0
- VU dumps: []


```text
ps2kit: VIF1: a filled vector takes data (0)
ps2kit: VIF1: word 3951B717 at stream offset 36A0 is not a code; before it (STCYCL 0000):
  0: 4A000100, 2048 bytes of data
  804: 4A000200, 2048 bytes of data
  1008: 4A000300, 2048 bytes of data
  180C: 4A000400, 2048 bytes of data
  2010: 4A000500, 2048 bytes of data
  2814: 4A000600, 2048 bytes of data
  3018: 4ACC0700, 1632 bytes of data
  367C: 4A020000, 16 bytes of data
  3690: 6E018000, 0 bytes of data
  3694: 00070209, 0 bytes of data
  3698: 6C01C001, 0 bytes of data
  369C: 00006000, 0 bytes of data
  the 4432 bytes waiting are dropped

```

```text
Input VIF bytes: 18416
Captured GIF bytes: 0
VIF1 status:  NOP 2 MPG 8 UNPACK V4-32 1 UNPACK V4-8 1; bytes: UNPACK 0 MPG 13936 DIRECT 0; misaligned 4, TTE 0, lost its place 1

```

## Program 463841787 / stream 0

- VU code bytes / pairs: 2048 / 256
- E-bit instructions / XGKICK instructions: 0 / 0
- Return code: 0
- GIF bytes / path-1 quadwords: 0 / 0
- GIF tags / EOP packets: 0 / 0
- GIF parse errors: 0
- VU dumps: []


```text
ps2kit: VIF1: a filled vector takes data (0)
ps2kit: VIF1: word 3951B717 at stream offset 3E90 is not a code; before it (STCYCL 0000):
  0: 4A000100, 2048 bytes of data
  804: 4A000200, 2048 bytes of data
  1008: 4A000300, 2048 bytes of data
  180C: 4A000400, 2048 bytes of data
  2010: 4A000500, 2048 bytes of data
  2814: 4A000600, 2048 bytes of data
  3018: 4ACC0700, 1632 bytes of data
  367C: 4A000000, 2048 bytes of data
  3E80: 6E018000, 0 bytes of data
  3E84: 0007020B, 0 bytes of data
  3E88: 6C01C001, 0 bytes of data
  3E8C: 00006000, 0 bytes of data
  the 13392 bytes waiting are dropped

```

```text
Input VIF bytes: 29408
Captured GIF bytes: 0
VIF1 status:  NOP 2 MPG 8 UNPACK V4-32 1 UNPACK V4-8 1; bytes: UNPACK 0 MPG 15968 DIRECT 0; misaligned 4, TTE 0, lost its place 1

```

## Program 463841787 / stream 1

- VU code bytes / pairs: 2048 / 256
- E-bit instructions / XGKICK instructions: 0 / 0
- Return code: 0
- GIF bytes / path-1 quadwords: 0 / 0
- GIF tags / EOP packets: 0 / 0
- GIF parse errors: 0
- VU dumps: []


```text
ps2kit: VIF1: a filled vector takes data (0)
ps2kit: VIF1: word 3951B717 at stream offset 3E90 is not a code; before it (STCYCL 0000):
  0: 4A000100, 2048 bytes of data
  804: 4A000200, 2048 bytes of data
  1008: 4A000300, 2048 bytes of data
  180C: 4A000400, 2048 bytes of data
  2010: 4A000500, 2048 bytes of data
  2814: 4A000600, 2048 bytes of data
  3018: 4ACC0700, 1632 bytes of data
  367C: 4A000000, 2048 bytes of data
  3E80: 6E018000, 0 bytes of data
  3E84: 00070209, 0 bytes of data
  3E88: 6C01C001, 0 bytes of data
  3E8C: 00006000, 0 bytes of data
  the 7552 bytes waiting are dropped

```

```text
Input VIF bytes: 23568
Captured GIF bytes: 0
VIF1 status:  NOP 2 MPG 8 UNPACK V4-32 1 UNPACK V4-8 1; bytes: UNPACK 0 MPG 15968 DIRECT 0; misaligned 4, TTE 0, lost its place 1

```

## Program 463841787 / stream 2

- VU code bytes / pairs: 2048 / 256
- E-bit instructions / XGKICK instructions: 0 / 0
- Return code: 0
- GIF bytes / path-1 quadwords: 0 / 0
- GIF tags / EOP packets: 0 / 0
- GIF parse errors: 0
- VU dumps: []


```text
ps2kit: VIF1: a filled vector takes data (0)
ps2kit: VIF1: word 3951B717 at stream offset 3E90 is not a code; before it (STCYCL 0000):
  0: 4A000100, 2048 bytes of data
  804: 4A000200, 2048 bytes of data
  1008: 4A000300, 2048 bytes of data
  180C: 4A000400, 2048 bytes of data
  2010: 4A000500, 2048 bytes of data
  2814: 4A000600, 2048 bytes of data
  3018: 4ACC0700, 1632 bytes of data
  367C: 4A000000, 2048 bytes of data
  3E80: 6E018000, 0 bytes of data
  3E84: 00070209, 0 bytes of data
  3E88: 6C01C001, 0 bytes of data
  3E8C: 00006000, 0 bytes of data
  the 4432 bytes waiting are dropped

```

```text
Input VIF bytes: 20448
Captured GIF bytes: 0
VIF1 status:  NOP 2 MPG 8 UNPACK V4-32 1 UNPACK V4-8 1; bytes: UNPACK 0 MPG 15968 DIRECT 0; misaligned 4, TTE 0, lost its place 1

```

