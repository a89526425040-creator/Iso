# ZDIR / ZZDATA validation report

- Index size: 33,408 bytes
- Record size: 24 bytes
- Records: 1,392
- Offset unit: 2,048-byte sectors
- Archive boundary validation: performed against all four extracted archives
- Validation problems: 0

## Archive distribution

| Archive | Actual size (bytes) | Entries | Declared payload bytes | Highest referenced end offset |
|---|---:|---:|---:|---:|
| ZZDATA0.BIN | 600,330,240 | 7 | 600,318,136 | 600,328,448 |
| ZZDATA1.BIN | 723,537,920 | 197 | 679,051,792 | 723,536,644 |
| ZZDATA2.BIN | 632,561,664 | 1,169 | 631,464,801 | 632,560,632 |
| ZZDATA3.BIN | 691,773,440 | 19 | 691,759,930 | 691,771,522 |

All index entries fit within their referenced archive files.

Only index metadata was committed. The ISO, ZDIR binary, and ZZDATA payloads were temporary runner files.
