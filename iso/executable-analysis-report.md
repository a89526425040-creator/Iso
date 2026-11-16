# PS2 executable inspection

- File: SLUS_210.65
- Size: 4697728 bytes
- SHA-256: a666f3e8869e63ad2f5eff90fc30c4953fcce41166ff006aaf1ed327d180d8ff

## File identification
\`\`\`text
/home/runner/work/_temp/executable/SLUS_210.65: ELF 32-bit LSB executable, MIPS, MIPS-III version 1 (SYSV), statically linked, stripped
\`\`\`

## ELF header and program segments
\`\`\`text
ELF Header:
  Magic:   7f 45 4c 46 01 01 01 00 00 00 00 00 00 00 00 00 
  Class:                             ELF32
  Data:                              2's complement, little endian
  Version:                           1 (current)
  OS/ABI:                            UNIX - System V
  ABI Version:                       0
  Type:                              EXEC (Executable file)
  Machine:                           MIPS R3000
  Version:                           0x1
  Entry point address:               0x100008
  Start of program headers:          52 (bytes into file)
  Start of section headers:          4695048 (bytes into file)
  Flags:                             0x20924001, noreorder, 5900, eabi64, mips3
  Size of this header:               52 (bytes)
  Size of program headers:           32 (bytes)
  Number of program headers:         1
  Size of section headers:           40 (bytes)
  Number of section headers:         67
  Section header string table index: 66

Program Headers:
  Type           Offset   VirtAddr   PhysAddr   FileSiz MemSiz  Flg Align
  LOAD           0x001000 0x00100000 0x00100000 0x474985 0x4a410c RWE 0x1000

 Section to Segment mapping:
  Segment Sections...
   00     .text .vutext .rodata .gcc_except_table .data .gnu.linkonce.d._vt$Q28EAGLAnim10FnPoseAnim .gnu.linkonce.d._vt$Q28EAGLAnim13FnStatelessF3 .gnu.linkonce.d._vt$Q28EAGLAnim12FnStatelessQ .gnu.linkonce.d._vt$Q28EAGLAnim13FnTurnBlender .gnu.linkonce.d._vt$Q28EAGLAnim12FnRunBlender .gnu.linkonce.d._vt$Q28EAGLAnim11FnPhaseChan .gnu.linkonce.d._vt$Q28EAGLAnim13FnPoseBlender .gnu.linkonce.d._vt$Q28EAGLAnim16FnRawPoseChannel .gnu.linkonce.d._vt$Q28EAGLAnim14FnEventBlender .gnu.linkonce.d._vt$Q28EAGLAnim11FnDeltaChan .gnu.linkonce.d._vt$Q28EAGLAnim15FnDeltaLerpChan .gnu.linkonce.d._vt$Q28EAGLAnim15FnDeltaQuatChan .gnu.linkonce.d._vt$Q28EAGLAnim14FnKeyDeltaChan .gnu.linkonce.d._vt$Q28EAGLAnim13FnKeyLerpChan .gnu.linkonce.d._vt$Q28EAGLAnim13FnKeyQuatChan .gnu.linkonce.d._vt$Q28EAGLAnim14FnDeltaSingleQ .gnu.linkonce.d._vt$Q28EAGLAnim9FnDeltaF1 .gnu.linkonce.d._vt$Q28EAGLAnim8FnDeltaQ .gnu.linkonce.d._vt$Q28EAGLAnim9FnDeltaF3 .gnu.linkonce.d._vt$Q28EAGLAnim12FnDeltaQFast .gnu.linkonce.d._vt$Q28EAGLAnim17FnCompoundChannel .gnu.linkonce.d._vt$Q28EAGLAnim15FnAnimMemoryMap .gnu.linkonce.d._vt$Q28EAGLAnim6FnAnim .gnu.linkonce.d._vt$Q28EAGLAnim14FnRawStateChan .gnu.linkonce.d._vt$Q28EAGLAnim11FnAnimSuper .gnu.linkonce.d._vt$Q28EAGLAnim17MemoryPoolManager .gnu.linkonce.d._vt$Q28EAGLAnim17FnRawEventChannel .gnu.linkonce.d._vt$Q28EAGLAnim18FnCsisEventChannel .gnu.linkonce.d._vt$Q28EAGLAnim18FnRawLinearChannel .gnu.linkonce.d._vt$Q28EAGLAnim7FnGraft .gnu.linkonce.d._vt$Q28EAGLAnim12FnPoseMirror .gnu.linkonce.d._vt$Q28EAGLAnim7FnCycle .gnu.linkonce.d._vt$Q24EAGL29TextureRenderContextExtension .gnu.linkonce.d._vt$Q212EAGLInternal27TextureRenderContextPrivate .gnu.linkonce.d._vt$Q24EAGL20TextureRenderContext .gnu.linkonce.d._vt$Q24EAGL26RenderContextExtensionBase .gnu.linkonce.d._vt$Q212EAGLInternal24RenderContextPrivateBase .gnu.linkonce.d._vt$Q24EAGL22RenderContextExtension .gnu.linkonce.d._vt$Q212EAGLInternal20RenderContextPrivate .gnu.linkonce.d._vt$Q24EAGL17RenderContextBase .gnu.linkonce.d._vt$Q24EAGL13RenderContext .vudata .lit4 .sdata .sbss .bss 
\`\`\`

## ELF sections
\`\`\`text
There are 67 section headers, starting at offset 0x47a408:

Section Headers:
  [Nr] Name              Type            Addr     Off    Size   ES Flg Lk Inf Al
  [ 0]                   NULL            00000000 000000 000000 00      0   0  0
  [ 1] .text             PROGBITS        00100000 001000 3555b8 00  AX  0   0 256
  [ 2] .vutext           PROGBITS        004555c0 3565c0 005090 00  AX  0   0 16
  [ 3] .reginfo          MIPS_REGINFO    00000000 475a08 000018 01      0   0  4
  [ 4] .rodata           PROGBITS        0045b000 35c000 046f3e 00   A  0   0 16
  [ 5] .gcc_except_table PROGBITS        004a1f80 3a2f80 00005c 00  WA  0   0  4
  [ 6] .DVP.ovlytab      LOPROC+0xffff420 00000000 475a20 00006c 0c   W  7   0  4
  [ 7] .DVP.ovlystrtab   STRTAB          00000000 475a8c 000154 00      0   0  1
  [ 8] .DVP.overlay..0x0.463841659.44.0 LOPROC+0xffff421 00000000 475be0 000010 00  WX  0   0  1
  [ 9] .DVP.overlay..0x0.463841787.201.0 LOPROC+0xffff421 00000000 475bf0 000800 00  WX  0   0  1
  [10] .DVP.overlay..unknvma.903966091.507.1 LOPROC+0xffff421 00000000 4763f0 000800 00  WX  0   0  1
  [11] .DVP.overlay..unknvma.903966091.1005.2 LOPROC+0xffff421 00000000 476bf0 000800 00  WX  0   0  1
  [12] .DVP.overlay..unknvma.903966091.1889.3 LOPROC+0xffff421 00000000 4773f0 000800 00  WX  0   0  1
  [13] .DVP.overlay..unknvma.903966091.2507.4 LOPROC+0xffff421 00000000 477bf0 000800 00  WX  0   0  1
  [14] .DVP.overlay..unknvma.903966091.2863.5 LOPROC+0xffff421 00000000 4783f0 000800 00  WX  0   0  1
  [15] .DVP.overlay..unknvma.903966091.3261.6 LOPROC+0xffff421 00000000 478bf0 000800 00  WX  0   0  1
  [16] .DVP.overlay..unknvma.903972827.435.7 LOPROC+0xffff421 00000000 4793f0 000660 00  WX  0   0  1
  [17] .mdebug.eabi64    PROGBITS        004a1fdc 479a50 000000 00      0   0  1
  [18] .data             PROGBITS        004a2000 3a3000 0c810c 00  WA  0   0 64
  [19] .gnu.linkonce.d._vt$Q28EAGLAnim10FnPoseAnim PROGBITS        0056a110 46b110 0000b8 00  WA  0   0  8
  [20] .gnu.linkonce.d._vt$Q28EAGLAnim13FnStatelessF3 PROGBITS        0056a1c8 46b1c8 0000b8 00  WA  0   0  8
  [21] .gnu.linkonce.d._vt$Q28EAGLAnim12FnStatelessQ PROGBITS        0056a280 46b280 0000b8 00  WA  0   0  8
  [22] .gnu.linkonce.d._vt$Q28EAGLAnim13FnTurnBlender PROGBITS        0056a338 46b338 0000a0 00  WA  0   0  8
  [23] .gnu.linkonce.d._vt$Q28EAGLAnim12FnRunBlender PROGBITS        0056a3d8 46b3d8 0000a0 00  WA  0   0  8
  [24] .gnu.linkonce.d._vt$Q28EAGLAnim11FnPhaseChan PROGBITS        0056a478 46b478 0000b8 00  WA  0   0  8
  [25] .gnu.linkonce.d._vt$Q28EAGLAnim13FnPoseBlender PROGBITS        0056a530 46b530 0000a0 00  WA  0   0  8
  [26] .gnu.linkonce.d._vt$Q28EAGLAnim16FnRawPoseChannel PROGBITS        0056a5d0 46b5d0 0000b8 00  WA  0   0  8
  [27] .gnu.linkonce.d._vt$Q28EAGLAnim14FnEventBlender PROGBITS        0056a688 46b688 0000a0 00  WA  0   0  8
  [28] .gnu.linkonce.d._vt$Q28EAGLAnim11FnDeltaChan PROGBITS        0056a728 46b728 0000b8 00  WA  0   0  8
  [29] .gnu.linkonce.d._vt$Q28EAGLAnim15FnDeltaLerpChan PROGBITS        0056a7e0 46b7e0 0000b8 00  WA  0   0  8
  [30] .gnu.linkonce.d._vt$Q28EAGLAnim15FnDeltaQuatChan PROGBITS        0056a898 46b898 0000b8 00  WA  0   0  8
  [31] .gnu.linkonce.d._vt$Q28EAGLAnim14FnKeyDeltaChan PROGBITS        0056a950 46b950 0000b8 00  WA  0   0  8
  [32] .gnu.linkonce.d._vt$Q28EAGLAnim13FnKeyLerpChan PROGBITS        0056aa08 46ba08 0000b8 00  WA  0   0  8
  [33] .gnu.linkonce.d._vt$Q28EAGLAnim13FnKeyQuatChan PROGBITS        0056aac0 46bac0 0000b8 00  WA  0   0  8
  [34] .gnu.linkonce.d._vt$Q28EAGLAnim14FnDeltaSingleQ PROGBITS        0056ab78 46bb78 0000c0 00  WA  0   0  8
  [35] .gnu.linkonce.d._vt$Q28EAGLAnim9FnDeltaF1 PROGBITS        0056ac38 46bc38 0000b8 00  WA  0   0  8
  [36] .gnu.linkonce.d._vt$Q28EAGLAnim8FnDeltaQ PROGBITS        0056acf0 46bcf0 0000c0 00  WA  0   0  8
  [37] .gnu.linkonce.d._vt$Q28EAGLAnim9FnDeltaF3 PROGBITS        0056adb0 46bdb0 0000b8 00  WA  0   0  8
  [38] .gnu.linkonce.d._vt$Q28EAGLAnim12FnDeltaQFast PROGBITS        0056ae68 46be68 0000b8 00  WA  0   0  8
  [39] .gnu.linkonce.d._vt$Q28EAGLAnim17FnCompoundChannel PROGBITS        0056af20 46bf20 0000b8 00  WA  0   0  8
  [40] .gnu.linkonce.d._vt$Q28EAGLAnim15FnAnimMemoryMap PROGBITS        0056afd8 46bfd8 0000b8 00  WA  0   0  8
  [41] .gnu.linkonce.d._vt$Q28EAGLAnim6FnAnim PROGBITS        0056b090 46c090 0000a0 00  WA  0   0  8
  [42] .gnu.linkonce.d._vt$Q28EAGLAnim14FnRawStateChan PROGBITS        0056b130 46c130 0000b8 00  WA  0   0  8
  [43] .gnu.linkonce.d._vt$Q28EAGLAnim11FnAnimSuper PROGBITS        0056b1e8 46c1e8 000018 00  WA  0   0  8
  [44] .gnu.linkonce.d._vt$Q28EAGLAnim17MemoryPoolManager PROGBITS        0056b200 46c200 000080 00  WA  0   0  8
  [45] .gnu.linkonce.d._vt$Q28EAGLAnim17FnRawEventChannel PROGBITS        0056b280 46c280 0000b8 00  WA  0   0  8
  [46] .gnu.linkonce.d._vt$Q28EAGLAnim18FnCsisEventChannel PROGBITS        0056b338 46c338 0000b8 00  WA  0   0  8
  [47] .gnu.linkonce.d._vt$Q28EAGLAnim18FnRawLinearChannel PROGBITS        0056b3f0 46c3f0 0000b8 00  WA  0   0  8
  [48] .gnu.linkonce.d._vt$Q28EAGLAnim7FnGraft PROGBITS        0056b4a8 46c4a8 0000a0 00  WA  0   0  8
  [49] .gnu.linkonce.d._vt$Q28EAGLAnim12FnPoseMirror PROGBITS        0056b548 46c548 0000a0 00  WA  0   0  8
  [50] .gnu.linkonce.d._vt$Q28EAGLAnim7FnCycle PROGBITS        0056b5e8 46c5e8 0000a0 00  WA  0   0  8
  [51] .gnu.linkonce.d._vt$Q24EAGL29TextureRenderContextExtension PROGBITS        0056b688 46c688 000018 00  WA  0   0  8
  [52] .gnu.linkonce.d._vt$Q212EAGLInternal27TextureRenderContextPrivate PROGBITS        0056b6a0 46c6a0 000018 00  WA  0   0  8
  [53] .gnu.linkonce.d._vt$Q24EAGL20TextureRenderContext PROGBITS        0056b6b8 46c6b8 000030 00  WA  0   0  8
  [54] .gnu.linkonce.d._vt$Q24EAGL26RenderContextExtensionBase PROGBITS        0056b6e8 46c6e8 000018 00  WA  0   0  8
  [55] .gnu.linkonce.d._vt$Q212EAGLInternal24RenderContextPrivateBase PROGBITS        0056b700 46c700 000018 00  WA  0   0  8
  [56] .gnu.linkonce.d._vt$Q24EAGL22RenderContextExtension PROGBITS        0056b718 46c718 000018 00  WA  0   0  8
  [57] .gnu.linkonce.d._vt$Q212EAGLInternal20RenderContextPrivate PROGBITS        0056b730 46c730 000018 00  WA  0   0  8
  [58] .gnu.linkonce.d._vt$Q24EAGL17RenderContextBase PROGBITS        0056b748 46c748 000030 00  WA  0   0  8
  [59] .gnu.linkonce.d._vt$Q24EAGL13RenderContext PROGBITS        0056b778 46c778 000030 00  WA  0   0  8
  [60] .vudata           PROGBITS        0056b7a8 46c7a8 000000 00  WA  0   0  1
  [61] .lit4             PROGBITS        0056b800 46c800 002b98 00 WAp  0   0  4
  [62] .sdata            PROGBITS        0056e400 46f400 006585 00 WAp  0   0  8
  [63] .sbss             NOBITS          00574a00 475a00 0001f8 00 WAp  0   0 64
  [64] .bss              NOBITS          00574c00 475a08 02f50c 00  WA  0   0 128
  [65] .vubss            NOBITS          005a410c 475a08 000000 00  WA  0   0  1
  [66] .shstrtab         STRTAB          00000000 479a50 0009b6 00      0   0  1
Key to Flags:
  W (write), A (alloc), X (execute), M (merge), S (strings), I (info),
  L (link order), O (extra OS processing required), G (group), T (TLS),
  C (compressed), x (unknown), o (OS specific), E (exclude),
  D (mbind), p (processor specific)
\`\`\`

## VU / VIF / geometry-related strings
\`\`\`text
>AcidEffectSystem::RenderEffects
smooth_vertex_index_table
eRenderLightFlarePool()
eRenderWorldLightFlares()
Sky Rendering
Render Cars
Render AcidFX
eBuildFogMesh()
OFFSET (Invalid on Vif0)
BASE (Invalid on Vif0)
MSKPATH3 (Invalid on Vif0)
FLUSH (Invalid on Vif0)
FLUSHA (Invalid on Vif0)
MSCALF (Invalid on Vif0)
DIRECT (Invalid on Vif0)
DIRECTHL (Invalid on Vif0)
FrontendRenderingCar
RenderMinimap()
FERenderObjectSlotPool
FERenderEPolySlotPool
FERenderEPolySlotPoolOverflow
FEngine::Render()
RenderObjectList()
cFEngRender::RenderImage()
cFEngRender::RenderString()
cFEngRender::RenderObject()
cFEngRender::PrepForPackage()
cFEngRender::PackageFinished()
FEngRenderer
CARS\AUDIO\GEOMETRY.bin
CARS\MIRRORS_POST\GEOMETRY.BIN
CARS\MIRRORS_BODY\GEOMETRY.BIN
CARS\MIRRORS_SUV\GEOMETRY.BIN
CARS\MIRRORS_HUMMER\GEOMETRY.BIN
CARS\SPOILER\GEOMETRY.BIN
CARS\SPOILER_HATCH\GEOMETRY.BIN
CARS\SPOILER_SUV\GEOMETRY.BIN
CARS\ROOF\GEOMETRY.BIN
CARS\EXHAUST\GEOMETRY.BIN
CARS\BRAKES\GEOMETRY.BIN
CARS\PLATES\GEOMETRY.BIN
CARS\WHEELS\GEOMETRY_%s.BIN
TrackPolygonCollisionBodySlotPool
TrackPolygonCollisionBodies
DynamicCollisionBody::CreateTrackPolygonCollisionBodies()
TrackPolygonCollisionBody::TrackPolygonCollisionBody()
TrackPolygon%d %s
TrackPolygonCollisionBody
AllTrackPolygonCollisionBodies
GJKVertex
RenderSkids()
NumPolygons
TrackPolygonTable
ALLOCATING_GEOMETRY_SECTIONS
LOADING_GEOMETRY_SECTIONS
DrawAScenery()
CarRenderInfo
../indep/src/World/CarRender.cpp
RenderTextureHeadlights()
RenderFlare()
CarRenderInfo::Render()
CarRenderInfo::RenderFast()
RenderFEFlares()
RenderFlares()
RenderCars()
RenderDashboards()
Rain::Render()
?Rain::UpdateAndRender()
DeviceExtension::NewTextureRenderContext
Device::NewTextureRenderContext
DeviceExtension::DeleteTextureRenderContext
Device::DeleteTextureRenderContext
VifListAccumulator::VifListAccumulator
rendercontext.cpp
DrawArray: User Var: %s is not aligned to %d-byte boundary!
EAGL::SingleDraw Coord Buf
EAGL::SingleDraw Colour Buf
EAGL::SingleDraw Coord  Buf
EAGL::SingleDraw STQ    Buf
VifListAccumulator::VifListAccumulator
VifListAccumulator::VifListAccumulator
VifListAccumulator::VifListAccumulator
PS2EXTOBJ_SetRenderMask
VifListAccumulator::VifListAccumulator
Dynamic Model DrawArray list
Dynamic Model Draw Array list
Dynamic Model Draw
VifListAccumulator::VifListAccumulator
Desnchronized interrupts at end of draw: cg = %d, cv = %d
Frame draw stalled, restarting graphics engine.
The drawing has stalled a total of %d times.
EAGL::VerifyChecksums - VifList Checksum failed on marker '%s'
VifListAccumulator::VifListAccumulator
VifListAccumulator::VifListAccumulator
VifListAccumulator::VifListAccumulator
DMA CHAIN: First Bad VIFCODE found in data that was REF Tagged.
DMA CHAIN: First Bad VIFCODE found in on the DMA accumulator.
DMA CHAIN: First Bad VIFCODE found in a CALL block.
           If this object has drawn successfully before, it is a memory stomp.
VIF1_R0    = 0x%08x
VIF1_R1    = 0x%08x
VIF1_R2    = 0x%08x
VIF1_R3    = 0x%08x
VIF1_C0    = 0x%08x
VIF1_C1    = 0x%08x
VIF1_C2    = 0x%08x
VIF1_C3    = 0x%08x
VIF1_CYCLE = 0x%08x
VIF1_MASK  = 0x%08x
VIF1_MODE  = 0x%08x
VIF1_ITOP  = 0x%08x
VIF1_ITOPS = 0x%08x
VIF1_BASE  = 0x%08x
VIF1_OFST  = 0x%08x
VIF1_TOP   = 0x%08x
VIF1_TOPS  = 0x%08x
VIF1_MARK  = 0x%08x
VIF1_NUM   = 0x%08x
VIF1_CODE  = 0x%08x
VIF1_STAT  = 0x%08x
VIF1_ERR   = 0x%08x
countInterVIF = %d, countInterGIF = %d
VIF UPLOADS: DMA CHANNEL 1 STATE:
waiting for drawing to complete.
waiting for Draw that is already finished.
VIF1: crashed on undefined VIF code
VIF1: crashed on DMA tag detected in VIF stream
VIF1: interrupted
VIF1: interrupt stall in effect
VIF1: force break stall in effect
VIF1: stop stall in effect
VIF1: waiting for end of GIF transfer
VIF1: waiting for end of VU code
VIF1: IDLE
VIF1: waiting for data from DMA engine
VIF1: decoding VIF data
VIF1: decompressing/transferring data.
VIF1: LAST VIF code was %x
GIF: VIF path 3 masked
Drawing DMA chain did not terminate.
VifListAccumulator::VifListAccumulator
EAGL::PT_POLYGON
VifListAccumulator::VifListAccumulator
Will not release an uncompiled render method!
Will not compile a compiled render method!
EAGL::RenderMethod
SingleDrawClipGouraud
SingleDrawClipTexture
SingleDrawGouraud
SingleDrawTexture
VIF0
VIF1
DRAWN
.gnu.linkonce.d._vt$Q24EAGL29TextureRenderContextExtension
.gnu.linkonce.d._vt$Q212EAGLInternal27TextureRenderContextPrivate
.gnu.linkonce.d._vt$Q24EAGL20TextureRenderContext
.gnu.linkonce.d._vt$Q24EAGL26RenderContextExtensionBase
.gnu.linkonce.d._vt$Q212EAGLInternal24RenderContextPrivateBase
.gnu.linkonce.d._vt$Q24EAGL22RenderContextExtension
.gnu.linkonce.d._vt$Q212EAGLInternal20RenderContextPrivate
.gnu.linkonce.d._vt$Q24EAGL17RenderContextBase
.gnu.linkonce.d._vt$Q24EAGL13RenderContext
\`\`\`
