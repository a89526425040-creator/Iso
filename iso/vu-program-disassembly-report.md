# PS2 VU microprogram disassembly

- Executable section virtual address: 0x4555C0
- .vutext bytes: 20,624
- VU microprogram blocks: 1
- Disassembly is derived from MPG uploads found in the executable's .vutext VIF stream.

## Program 1

- VIF source offset: 0x1858
- VU destination address: 0x800
- Code bytes / instruction pairs: 13,920 / 1,740
- E-bit instructions: 1
- XGKICK instructions: 25
- Reserved/unknown decoded instructions: 0

```asm
0800  NOP                                      | SQ.xyzw vf02.xyzw, 842(vi00)                 
0808  NOP                                      | SQ.xyzw vf03.xyzw, 843(vi00)                 
0810  NOP                                      | SQ.xyzw vf04.xyzw, 844(vi00)                 
0818  NOP                                      | SQ.xyzw vf05.xyzw, 845(vi00)                 
0820  NOP                                      | SQ.xyzw vf06.xyzw, 846(vi00)                 
0828  NOP                                      | SQ.xyzw vf24.xyzw, 903(vi00)                 
0830  NOP                                      | BAL vi15, 0x14a0                             
0838  NOP                                      | IADDIU vi05, vi00, 709                       
0840  NOP                                      | LQ.xyzw vf24.xyzw, 903(vi00)                 
0848  NOP                                      | IADDIU vi01, vi00, 32                        
0850  NOP                                      | IAND vi01, vi07, vi01                        
0858  NOP                                      | NOP                                          
0860  NOP                                      | IBEQ vi01, vi00, 0x0880                      
0868  NOP                                      | NOP                                          
0870  NOP                                      | BAL vi15, 0x1c50                             
0878  NOP                                      | NOP                                          
0880  NOP                                      | IADDIU vi01, vi00, 128                       
0888  NOP                                      | IAND vi01, vi07, vi01                        
0890  NOP                                      | NOP                                          
0898  NOP                                      | IBEQ vi01, vi00, 0x08b8                      
08a0  NOP                                      | NOP                                          
08a8  NOP                                      | BAL vi15, 0x1d08                             
08b0  NOP                                      | NOP                                          
08b8  NOP                                      | IADDIU vi01, vi00, 512                       
08c0  NOP                                      | IAND vi01, vi07, vi01                        
08c8  NOP                                      | NOP                                          
08d0  NOP                                      | IBEQ vi01, vi00, 0x08f8                      
08d8  NOP                                      | NOP                                          
08e0  NOP                                      | IADDIU vi01, vi00, 1356                      
08e8  NOP                                      | JALR vi15, vi01                              
08f0  NOP                                      | NOP                                          
08f8  NOP                                      | LQ.y vf01.y, 1(vi12)                         
0900  NOP                                      | SQ.y vf01.y, 737(vi00)                       
0908  NOP                                      | IADDIU vi02, vi00, 735                       
0910  NOP                                      | XGKICK vi02                                  
0918  NOP                                      | XGKICK vi13                                  
0920  NOP                                      | IADDIU vi01, vi00, 1436                      
0928  NOP                                      | JALR vi15, vi01                              
0930  NOP                                      | NOP                                          
0938  NOP                                      | IADDIU vi01, vi00, 64                        
0940  NOP                                      | IAND vi01, vi07, vi01                        
0948  NOP                                      | NOP                                          
0950  NOP                                      | IBEQ vi01, vi00, 0x09c0                      
0958  NOP                                      | NOP                                          
0960  NOP                                      | IADDIU vi01, vi07, 8                         
0968  NOP                                      | IOR vi07, vi00, vi01                         
0970  NOP                                      | IADDIU vi01, vi00, 763                       
0978  NOP                                      | XGKICK vi01                                  
0980  NOP                                      | BAL vi15, 0x0cc0                             
0988  NOP                                      | NOP                                          
0990  NOP                                      | XGKICK vi13                                  
0998  NOP                                      | IADDIU vi01, vi00, 1436                      
09a0  NOP                                      | JALR vi15, vi01                              
09a8  NOP                                      | NOP                                          
09b0  NOP                                      | IADDIU vi03, vi00, 638                       
09b8  NOP                                      | XGKICK vi03                                  
09c0  NOP                                      | IADDIU vi01, vi00, 16                        
09c8  NOP                                      | IAND vi01, vi07, vi01                        
09d0  NOP                                      | NOP                                          
09d8  NOP                                      | IBEQ vi01, vi00, 0x0bd0                      
09e0  NOP                                      | NOP                                          
09e8  NOP                                      | IADDIU vi03, vi00, 638                       
09f0  NOP                                      | XGKICK vi03                                  
09f8  NOP                                      | ILW.x vi01, 744(vi00)                        
0a00  NOP                                      | IADDI vi01, vi01, -1                         
0a08  NOP                                      | NOP                                          
0a10  NOP                                      | IBNE vi01, vi00, 0x0ac0                      
0a18  NOP                                      | NOP                                          
0a20  NOP                                      | LQ.xyzw vf01.xyzw, 736(vi00)                 
0a28  NOP                                      | SQ.xyzw vf01.xyzw, 902(vi00)                 
0a30  NOP                                      | ILW.y vi02, 736(vi00)                        
0a38  NOP                                      | IADDIU vi01, vi00, 24                        
0a40  NOP                                      | IOR vi02, vi02, vi01                         
0a48  NOP                                      | ISW.y vi02, 736(vi00)                        
0a50  NOP                                      | IADDIU vi02, vi00, 735                       
0a58  NOP                                      | XGKICK vi02                                  
0a60  NOP                                      | IADDIU vi02, vi00, 638                       
0a68  NOP                                      | XGKICK vi02                                  
0a70  NOP                                      | IADDIU vi01, vi00, 887                       
0a78  NOP                                      | XGKICK vi01                                  
0a80  NOP                                      | XGKICK vi13                                  
0a88  NOP                                      | IADDIU vi01, vi00, 1436                      
0a90  NOP                                      | JALR vi15, vi01                              
0a98  NOP                                      | NOP                                          
0aa0  NOP                                      | IADDIU vi02, vi00, 638                       
0aa8  NOP                                      | XGKICK vi02                                  
0ab0  NOP                                      | IADDIU vi01, vi00, 897                       
0ab8  NOP                                      | XGKICK vi01                                  
0ac0  NOP                                      | IADDIU vi01, vi00, 64                        
0ac8  NOP                                      | IAND vi01, vi07, vi01                        
0ad0  NOP                                      | NOP                                          
0ad8  NOP                                      | IBEQ vi01, vi00, 0x0b08                      
0ae0  NOP                                      | NOP                                          
0ae8  NOP                                      | IADDIU vi01, vi00, 727                       
0af0  NOP                                      | XGKICK vi01                                  
0af8  NOP                                      | B 0x0b28                                     
0b00  NOP                                      | NOP                                          
0b08  NOP                                      | IADDIU vi01, vi00, 771                       
0b10  NOP                                      | XGKICK vi01                                  
0b18  NOP                                      | IADDIU vi02, vi00, 638                       
0b20  NOP                                      | XGKICK vi02                                  
0b28  NOP                                      | IADDIU vi01, vi00, 951                       
0b30  NOP                                      | IAND vi07, vi07, vi01                        
0b38  NOP                                      | IADDIU vi01, vi00, 16                        
0b40  NOP                                      | ISW.z vi01, 599(vi00)                        
0b48  NOP                                      | BAL vi15, 0x0f20                             
0b50  NOP                                      | NOP                                          
0b58  NOP                                      | XGKICK vi13                                  
0b60  NOP                                      | IADDIU vi01, vi00, 1436                      
0b68  NOP                                      | JALR vi15, vi01                              
0b70  NOP                                      | NOP                                          
0b78  NOP                                      | ILW.x vi01, 744(vi00)                        
0b80  NOP                                      | IADDI vi01, vi01, -1                         
0b88  NOP                                      | NOP                                          
0b90  NOP                                      | IBNE vi01, vi00, 0x0bd0                      
0b98  NOP                                      | NOP                                          
0ba0  NOP                                      | LQ.xyzw vf01.xyzw, 902(vi00)                 
0ba8  NOP                                      | SQ.xyzw vf01.xyzw, 736(vi00)                 
0bb0  NOP                                      | IADDIU vi02, vi00, 638                       
0bb8  NOP                                      | XGKICK vi02                                  
0bc0  NOP                                      | IADDIU vi01, vi00, 892                       
0bc8  NOP                                      | XGKICK vi01                                  
0bd0  NOP                                      | IADDIU vi01, vi00, 128                       
0bd8  NOP                                      | IAND vi01, vi01, vi07                        
0be0  NOP                                      | NOP                                          
0be8  NOP                                      | IBEQ vi01, vi00, 0x0c40                      
0bf0  NOP                                      | NOP                                          
0bf8  NOP                                      | IADDIU vi01, vi00, 1049                      
0c00  NOP                                      | JALR vi15, vi01                              
0c08  NOP                                      | NOP                                          
0c10  NOP                                      | IADDIU vi01, vi00, 755                       
0c18  NOP                                      | XGKICK vi01                                  
0c20  NOP                                      | XGKICK vi13                                  
0c28  NOP                                      | IADDIU vi01, vi00, 1436                      
0c30  NOP                                      | JALR vi15, vi01                              
0c38  NOP                                      | NOP                                          
0c40  NOP                                      | IADDIU vi01, vi00, 256                       
0c48  NOP                                      | IAND vi01, vi01, vi07                        
0c50  NOP                                      | NOP                                          
0c58  NOP                                      | IBEQ vi01, vi00, 0x0cb0                      
0c60  NOP                                      | NOP                                          
0c68  NOP                                      | IADDIU vi01, vi00, 1211                      
0c70  NOP                                      | JALR vi15, vi01                              
0c78  NOP                                      | NOP                                          
0c80  NOP                                      | IADDIU vi01, vi00, 755                       
0c88  NOP                                      | XGKICK vi01                                  
0c90  NOP                                      | XGKICK vi13                                  
0c98  NOP                                      | IADDIU vi01, vi00, 1436                      
0ca0  NOP                                      | JALR vi15, vi01                              
0ca8  NOP                                      | NOP                                          
0cb0  NOP                                      | NOP                                          E
0cb8  NOP                                      | NOP                                          
0cc0  NOP                                      | LQ.xyw vf04.xyw, 689(vi00)                   
0cc8  ADDw.xyz vf18.xyz, vf00.xyz, vf04.w      | NOP                                          
0cd0  FTOI0.xyzw vf18.xyzw, vf18.xyzw          | NOP                                          
0cd8  NOP                                      | loi 0x3b000000 (0.00195312)                  I
0ce0  ADDi.x vf05.x, vf00.x, I                 | loi 0x3b000000 (0.00195312)                  I
0ce8  ADDi.y vf05.y, vf00.y, I                 | NOP                                          
0cf0  NOP                                      | ILW.x vi01, 0(vi12)                          
0cf8  NOP                                      | IADD vi03, vi00, vi13                        
0d00  NOP                                      | IADDI vi03, vi03, 1                          
0d08  NOP                                      | loi 0xc9000000 (-524288)                     I
0d10  NOP                                      | LQ.xy vf01.xy, 2(vi03)                       
0d18  NOP                                      | MR32.z vf02.z, vf00.z                        
0d20  MULA.xy ACC, vf01.xy, vf05.xy            | NOP                                          
0d28  MADDAi.xy ACC, vf05.xy, I                | LQ.xy vf01.xy, 5(vi03)                       
0d30  MSUB.xy vf02.xy, vf05.xy, vf04.xy        | IADDI vi03, vi03, 3                          
0d38  NOP                                      | IADDI vi01, vi01, -1                         
0d40  NOP                                      | SQ.xyz vf18.xyz, -2(vi03)                    
0d48  NOP                                      | IBGEZ vi01, 0x0d28                           
0d50  MULA.xy ACC, vf01.xy, vf05.xy            | SQ.xyz vf02.xyz, -3(vi03)                    
0d58  NOP                                      | JR vi15                                      
0d60  NOP                                      | NOP                                          
0d68  NOP                                      | LQ.xyzw vf08.xyzw, 2(vi12)                   
0d70  NOP                                      | NOP                                          
0d78  NOP                                      | ILW.x vi01, 0(vi12)                          
0d80  NOP                                      | IADDIU vi09, vi12, 29                        
0d88  NOP                                      | IADDIU vi10, vi12, 29                        
0d90  NOP                                      | IADDIU vi02, vi12, 5                         
0d98  NOP                                      | IADDIU vi03, vi12, 5                         
0da0  FTOI0.xyzw vf08.xyzw, vf08.xyzw          | NOP                                          
0da8  ITOF0.xyzw vf08.xyzw, vf08.xyzw          | NOP                                          
0db0  SUBw.xyz vf08.xyz, vf08.xyz, vf00.w      | NOP                                          
0db8  NOP                                      | LQI.xyzw vf01.xyzw, (vi09++)                 
0dc0  NOP                                      | LQI.xyzw vf02.xyzw, (vi09++)                 
0dc8  NOP                                      | LQI.xyzw vf05.xyzw, (vi02++)                 
0dd0  NOP                                      | LQI.xyzw vf06.xyzw, (vi02++)                 
0dd8  NOP                                      | LQI.xyzw vf07.xyzw, (vi02++)                 
0de0  NOP                                      | NOP                                          
0de8  ITOF12.xyzw vf03.xyzw, vf01.xyzw         | NOP                                          
0df0  ITOF12.xyzw vf04.xyzw, vf02.xyzw         | NOP                                          
0df8  ITOF0.xyzw vf05.xyzw, vf05.xyzw          | NOP                                          
0e00  ITOF0.xyzw vf06.xyzw, vf06.xyzw          | NOP                                          
0e08  ITOF0.xyzw vf07.xyzw, vf07.xyzw          | SQI.xyzw vf03.xyzw, (vi10++)                 
0e10  NOP                                      | SQI.xyzw vf04.xyzw, (vi10++)                 
0e18  MULi.xyzw vf11.xyzw, vf05.xyzw, I        | IADDI vi01, vi01, -4                         
0e20  MULi.xyzw vf12.xyzw, vf06.xyzw, I        | NOP                                          
0e28  MULi.xyzw vf13.xyzw, vf07.xyzw, I        | LQI.xyzw vf01.xyzw, (vi09++)                 
0e30  NOP                                      | LQI.xyzw vf02.xyzw, (vi09++)                 
0e38  ADDx.xyzw vf11.xyzw, vf11.xyzw, vf08.x   | LQI.xyzw vf05.xyzw, (vi02++)                 
0e40  ADDy.xyzw vf12.xyzw, vf12.xyzw, vf08.y   | LQI.xyzw vf06.xyzw, (vi02++)                 
0e48  ADDz.xyzw vf13.xyzw, vf13.xyzw, vf08.z   | LQI.xyzw vf07.xyzw, (vi02++)                 
0e50  ITOF12.xyzw vf03.xyzw, vf01.xyzw         | NOP                                          
0e58  ITOF12.xyzw vf04.xyzw, vf02.xyzw         | SQI.xyzw vf11.xyzw, (vi03++)                 
0e60  ITOF0.xyzw vf05.xyzw, vf05.xyzw          | SQI.xyzw vf12.xyzw, (vi03++)                 
0e68  NOP                                      | IBGEZ vi01, 0x0e08                           
0e70  ITOF0.xyzw vf06.xyzw, vf06.xyzw          | SQI.xyzw vf13.xyzw, (vi03++)                 
0e78  NOP                                      | JR vi15                                      
0e80  NOP                                      | NOP                                          
0e88  NOP                                      | ILW.x vi01, 0(vi12)                          
0e90  NOP                                      | IADDIU vi09, vi12, 29                        
0e98  NOP                                      | IADDIU vi10, vi12, 29                        
0ea0  NOP                                      | LQI.xyzw vf01.xyzw, (vi09++)                 
0ea8  NOP                                      | LQI.xyzw vf02.xyzw, (vi09++)                 
0eb0  ITOF0.xyzw vf03.xyzw, vf01.xyzw          | loi 0x3980000d (0.000244141)                 I
0eb8  ITOF0.xyzw vf04.xyzw, vf02.xyzw          | NOP                                          
0ec0  NOP                                      | NOP                                          
0ec8  NOP                                      | NOP                                          
0ed0  MULi.xyzw vf05.xyzw, vf03.xyzw, I        | LQI.xyzw vf01.xyzw, (vi09++)                 
0ed8  MULi.xyzw vf06.xyzw, vf04.xyzw, I        | LQI.xyzw vf02.xyzw, (vi09++)                 
0ee0  NOP                                      | NOP                                          
0ee8  NOP                                      | IADDI vi01, vi01, -4                         
0ef0  ITOF0.xyzw vf03.xyzw, vf01.xyzw          | SQI.xyzw vf05.xyzw, (vi10++)                 
0ef8  ITOF0.xyzw vf04.xyzw, vf02.xyzw          | SQI.xyzw vf06.xyzw, (vi10++)                 
0f00  NOP                                      | IBGEZ vi01, 0x0ed0                           
0f08  NOP                                      | NOP                                          
0f10  NOP                                      | JR vi15                                      
0f18  NOP                                      | NOP                                          
0f20  NOP                                      | FCSET vi01, 0x000000                         
0f28  NOP                                      | LQ.xyzw vf01.xyzw, 608(vi00)                 
0f30  NOP                                      | loi 0x3f800000 (1)                           I
0f38  ADDi.w vf21.w, vf00.w, I                 | loi 0x3f800000 (1)                           I
0f40  ADDi.x vf21.x, vf00.x, I                 | loi 0x3f800000 (1)                           I
0f48  ADDi.y vf21.y, vf00.y, I                 | loi 0x3f800000 (1)                           I
0f50  ADDi.z vf21.z, vf00.z, I                 | NOP                                          
0f58  NOP                                      | LQ.xyz vf21.xyz, 690(vi00)                   
0f60  NOP                                      | LQ.xyzw vf05.xyzw, 604(vi00)                 
0f68  NOP                                      | LQ.xyzw vf06.xyzw, 605(vi00)                 
0f70  NOP                                      | LQ.xyzw vf07.xyzw, 606(vi00)                 
0f78  NOP                                      | LQ.xyzw vf08.xyzw, 607(vi00)                 
0f80  MULAx.xyzw ACC, vf05.xyzw, vf01.x        | LQ.xyzw vf02.xyzw, 609(vi00)                 
0f88  MADDAy.xyzw ACC, vf06.xyzw, vf01.y       | NOP                                          
0f90  MADDAz.xyzw ACC, vf07.xyzw, vf01.z       | NOP                                          
0f98  MADDw.xyzw vf12.xyzw, vf08.xyzw, vf01.w  | NOP                                          
0fa0  MULAx.xyzw ACC, vf05.xyzw, vf02.x        | LQ.xyzw vf03.xyzw, 610(vi00)                 
0fa8  MADDAy.xyzw ACC, vf06.xyzw, vf02.y       | NOP                                          
0fb0  MADDAz.xyzw ACC, vf07.xyzw, vf02.z       | NOP                                          
0fb8  MADDw.xyzw vf13.xyzw, vf08.xyzw, vf02.w  | NOP                                          
0fc0  MULAx.xyzw ACC, vf05.xyzw, vf03.x        | LQ.xyzw vf04.xyzw, 611(vi00)                 
0fc8  MADDAy.xyzw ACC, vf06.xyzw, vf03.y       | NOP                                          
0fd0  MADDAz.xyzw ACC, vf07.xyzw, vf03.z       | NOP                                          
0fd8  MADDw.xyzw vf14.xyzw, vf08.xyzw, vf03.w  | NOP                                          
0fe0  MULAx.xyzw ACC, vf05.xyzw, vf04.x        | NOP                                          
0fe8  MADDAy.xyzw ACC, vf06.xyzw, vf04.y       | NOP                                          
0ff0  MADDAz.xyzw ACC, vf07.xyzw, vf04.z       | NOP                                          
0ff8  MADDw.xyzw vf15.xyzw, vf08.xyzw, vf04.w  | NOP                                          
1000  NOP                                      | LQ.xyzw vf05.xyzw, 600(vi00)                 
1008  NOP                                      | LQ.xyzw vf06.xyzw, 601(vi00)                 
1010  NOP                                      | LQ.xyzw vf07.xyzw, 602(vi00)                 
1018  NOP                                      | LQ.xyzw vf08.xyzw, 603(vi00)                 
1020  MULAx.xyzw ACC, vf05.xyzw, vf01.x        | NOP                                          
1028  MADDAy.xyzw ACC, vf06.xyzw, vf01.y       | NOP                                          
1030  MADDAz.xyzw ACC, vf07.xyzw, vf01.z       | NOP                                          
1038  MADDw.xyzw vf01.xyzw, vf08.xyzw, vf01.w  | NOP                                          
1040  MULAx.xyzw ACC, vf05.xyzw, vf02.x        | NOP                                          
1048  MADDAy.xyzw ACC, vf06.xyzw, vf02.y       | NOP                                          
1050  MADDAz.xyzw ACC, vf07.xyzw, vf02.z       | NOP                                          
1058  MADDw.xyzw vf02.xyzw, vf08.xyzw, vf02.w  | NOP                                          
1060  MULAx.xyzw ACC, vf05.xyzw, vf03.x        | NOP                                          
1068  MADDAy.xyzw ACC, vf06.xyzw, vf03.y       | NOP                                          
1070  MADDAz.xyzw ACC, vf07.xyzw, vf03.z       | NOP                                          
1078  MADDw.xyzw vf03.xyzw, vf08.xyzw, vf03.w  | NOP                                          
1080  MULAx.xyzw ACC, vf05.xyzw, vf04.x        | NOP                                          
1088  MADDAy.xyzw ACC, vf06.xyzw, vf04.y       | NOP                                          
1090  MADDAz.xyzw ACC, vf07.xyzw, vf04.z       | NOP                                          
1098  MADDw.xyzw vf04.xyzw, vf08.xyzw, vf04.w  | NOP                                          
10a0  NOP                                      | MOVE.xyzw vf05.xyzw, vf01.xyzw               
10a8  NOP                                      | MOVE.xyzw vf06.xyzw, vf02.xyzw               
10b0  NOP                                      | MOVE.xyzw vf07.xyzw, vf03.xyzw               
10b8  NOP                                      | MOVE.xyzw vf08.xyzw, vf04.xyzw               
10c0  NOP                                      | IADDIU vi09, vi12, 5                         
10c8  NOP                                      | ILW.x vi02, 0(vi12)                          
10d0  NOP                                      | IADD vi03, vi00, vi13                        
10d8  NOP                                      | IADDI vi03, vi03, 1                          
10e0  NOP                                      | LQ.z vf20.z, 689(vi00)                       
10e8  SUB.xyzw vf19.xyzw, vf19.xyzw, vf19.xyzw | NOP                                          
10f0  NOP                                      | loi 0x40a00000 (5)                           I
10f8  NOP                                      | LQI.xyzw vf01.xyzw, (vi09++)                 
1100  NOP                                      | LQI.xyzw vf02.xyzw, (vi09++)                 
1108  NOP                                      | LQI.xyzw vf03.xyzw, (vi09++)                 
1110  MULAw.xyzw ACC, vf31.xyzw, vf00.w        | NOP                                          
1118  MADDAx.xyzw ACC, vf28.xyzw, vf01.x       | NOP                                          
1120  MADDAx.xyzw ACC, vf29.xyzw, vf02.x       | NOP                                          
1128  MADDx.xyzw vf18.xyzw, vf30.xyzw, vf03.x  | NOP                                          
1130  MULAx.xyzw ACC, vf05.xyzw, vf01.x        | NOP                                          
1138  MADDAx.xyzw ACC, vf06.xyzw, vf02.x       | NOP                                          
1140  MADDAx.xyzw ACC, vf07.xyzw, vf03.x       | NOP                                          
1148  MADDw.xyzw vf16.xyzw, vf08.xyzw, vf00.w  | DIV Q, vf00.w, vf18.w                        
1150  MULAx.xyzw ACC, vf12.xyzw, vf01.x        | NOP                                          
1158  MADDAx.xyzw ACC, vf13.xyzw, vf02.x       | NOP                                          
1160  MADDAx.xyzw ACC, vf14.xyzw, vf03.x       | NOP                                          
1168  MADDw.xyzw vf09.xyzw, vf15.xyzw, vf00.w  | NOP                                          
1170  CLIPw.xyz vf16.xyz, vf16.w               | NOP                                          
1178  NOP                                      | NOP                                          
1180  NOP                                      | NOP                                          
1188  SUB.z vf17.z, vf20.z, vf09.z             | NOP                                          
1190  MULq.xyz vf09.xyz, vf09.xyz, Q           | FCAND vi01, 0x000030                         
1198  NOP                                      | IBNE vi01, vi00, 0x1218                      
11a0  NOP                                      | SQ.xyzw vf19.xyzw, 1(vi03)                   
11a8  ADDz.y vf17.y, vf19.y, vf17.z            | NOP                                          
11b0  ADDz.x vf17.x, vf19.x, vf17.z            | NOP                                          
11b8  NOP                                      | NOP                                          
11c0  NOP                                      | NOP                                          
11c8  NOP                                      | NOP                                          
11d0  MUL.xyz vf17.xyz, vf17.xyz, vf21.xyz     | NOP                                          
11d8  NOP                                      | NOP                                          
11e0  NOP                                      | NOP                                          
11e8  NOP                                      | NOP                                          
11f0  FTOI0.xyzw vf17.xyzw, vf17.xyzw          | NOP                                          
11f8  NOP                                      | NOP                                          
1200  NOP                                      | NOP                                          
1208  NOP                                      | NOP                                          
1210  NOP                                      | SQ.xyz vf17.xyz, 1(vi03)                     
1218  MULAw.xyzw ACC, vf31.xyzw, vf00.w        | SQ.xyz vf09.xyz, 0(vi03)                     
1220  MADDAy.xyzw ACC, vf28.xyzw, vf01.y       | IADDI vi03, vi03, 3                          
1228  MADDAy.xyzw ACC, vf29.xyzw, vf02.y       | NOP                                          
1230  MADDy.xyzw vf18.xyzw, vf30.xyzw, vf03.y  | NOP                                          
1238  MULAy.xyzw ACC, vf05.xyzw, vf01.y        | NOP                                          
1240  MADDAy.xyzw ACC, vf06.xyzw, vf02.y       | NOP                                          
1248  MADDAy.xyzw ACC, vf07.xyzw, vf03.y       | NOP                                          
1250  MADDw.xyzw vf16.xyzw, vf08.xyzw, vf00.w  | DIV Q, vf00.w, vf18.w                        
1258  MULAy.xyzw ACC, vf12.xyzw, vf01.y        | NOP                                          
1260  MADDAy.xyzw ACC, vf13.xyzw, vf02.y       | NOP                                          
1268  MADDAy.xyzw ACC, vf14.xyzw, vf03.y       | NOP                                          
1270  MADDw.xyzw vf09.xyzw, vf15.xyzw, vf00.w  | NOP                                          
1278  CLIPw.xyz vf16.xyz, vf16.w               | NOP                                          
1280  NOP                                      | NOP                                          
1288  NOP                                      | NOP                                          
1290  SUB.z vf17.z, vf20.z, vf09.z             | NOP                                          
1298  MULq.xyz vf09.xyz, vf09.xyz, Q           | FCAND vi01, 0x000030                         
12a0  NOP                                      | IBNE vi01, vi00, 0x12d8                      
12a8  NOP                                      | SQ.xyzw vf19.xyzw, 1(vi03)                   
12b0  ADDz.y vf17.y, vf19.y, vf17.z            | NOP                                          
12b8  ADDz.x vf17.x, vf19.x, vf17.z            | NOP                                          
12c0  MUL.xyz vf17.xyz, vf17.xyz, vf21.xyz     | NOP                                          
12c8  FTOI0.xyzw vf17.xyzw, vf17.xyzw          | NOP                                          
12d0  NOP                                      | SQ.xyz vf17.xyz, 1(vi03)                     
12d8  MULAw.xyzw ACC, vf31.xyzw, vf00.w        | SQ.xyz vf09.xyz, 0(vi03)                     
12e0  MADDAz.xyzw ACC, vf28.xyzw, vf01.z       | IADDI vi03, vi03, 3                          
12e8  MADDAz.xyzw ACC, vf29.xyzw, vf02.z       | NOP                                          
12f0  MADDz.xyzw vf18.xyzw, vf30.xyzw, vf03.z  | NOP                                          
12f8  MULAz.xyzw ACC, vf05.xyzw, vf01.z        | NOP                                          
1300  MADDAz.xyzw ACC, vf06.xyzw, vf02.z       | NOP                                          
1308  MADDAz.xyzw ACC, vf07.xyzw, vf03.z       | NOP                                          
1310  MADDw.xyzw vf16.xyzw, vf08.xyzw, vf00.w  | DIV Q, vf00.w, vf18.w                        
1318  MULAz.xyzw ACC, vf12.xyzw, vf01.z        | NOP                                          
1320  MADDAz.xyzw ACC, vf13.xyzw, vf02.z       | NOP                                          
1328  MADDAz.xyzw ACC, vf14.xyzw, vf03.z       | NOP                                          
1330  MADDw.xyzw vf09.xyzw, vf15.xyzw, vf00.w  | NOP                                          
1338  CLIPw.xyz vf16.xyz, vf16.w               | NOP                                          
1340  NOP                                      | NOP                                          
1348  NOP                                      | NOP                                          
1350  SUB.z vf17.z, vf20.z, vf09.z             | NOP                                          
1358  MULq.xyz vf09.xyz, vf09.xyz, Q           | FCAND vi01, 0x000030                         
1360  NOP                                      | IBNE vi01, vi00, 0x1398                      
1368  NOP                                      | SQ.xyzw vf19.xyzw, 1(vi03)                   
1370  ADDz.y vf17.y, vf19.y, vf17.z            | NOP                                          
1378  ADDz.x vf17.x, vf19.x, vf17.z            | NOP                                          
1380  MUL.xyz vf17.xyz, vf17.xyz, vf21.xyz     | NOP                                          
1388  FTOI0.xyzw vf17.xyzw, vf17.xyzw          | NOP                                          
1390  NOP                                      | SQ.xyz vf17.xyz, 1(vi03)                     
1398  MULAw.xyzw ACC, vf31.xyzw, vf00.w        | SQ.xyz vf09.xyz, 0(vi03)                     
13a0  MADDAw.xyzw ACC, vf28.xyzw, vf01.w       | IADDI vi03, vi03, 3                          
13a8  MADDAw.xyzw ACC, vf29.xyzw, vf02.w       | NOP                                          
13b0  MADDw.xyzw vf18.xyzw, vf30.xyzw, vf03.w  | NOP                                          
13b8  MULAw.xyzw ACC, vf05.xyzw, vf01.w        | NOP                                          
13c0  MADDAw.xyzw ACC, vf06.xyzw, vf02.w       | NOP                                          
13c8  MADDAw.xyzw ACC, vf07.xyzw, vf03.w       | NOP                                          
13d0  MADDw.xyzw vf16.xyzw, vf08.xyzw, vf00.w  | DIV Q, vf00.w, vf18.w                        
13d8  MULAw.xyzw ACC, vf12.xyzw, vf01.w        | NOP                                          
13e0  MADDAw.xyzw ACC, vf13.xyzw, vf02.w       | NOP                                          
13e8  MADDAw.xyzw ACC, vf14.xyzw, vf03.w       | NOP                                          
13f0  MADDw.xyzw vf09.xyzw, vf15.xyzw, vf00.w  | NOP                                          
13f8  CLIPw.xyz vf16.xyz, vf16.w               | NOP                                          
1400  NOP                                      | NOP                                          
1408  NOP                                      | NOP                                          
1410  SUB.z vf17.z, vf20.z, vf09.z             | NOP                                          
1418  MULq.xyz vf09.xyz, vf09.xyz, Q           | FCAND vi01, 0x000030                         
1420  NOP                                      | IBNE vi01, vi00, 0x1458                      
1428  NOP                                      | SQ.xyzw vf19.xyzw, 1(vi03)                   
1430  ADDz.y vf17.y, vf19.y, vf17.z            | NOP                                          
1438  ADDz.x vf17.x, vf19.x, vf17.z            | NOP                                          
1440  MUL.xyz vf17.xyz, vf17.xyz, vf21.xyz     | NOP                                          
1448  FTOI0.xyzw vf17.xyzw, vf17.xyzw          | NOP                                          
1450  NOP                                      | SQ.xyz vf17.xyz, 1(vi03)                     
1458  NOP                                      | SQ.xyz vf09.xyz, 0(vi03)                     
1460  NOP                                      | IADDI vi03, vi03, 3                          
1468  NOP                                      | IADDI vi02, vi02, -4                         
1470  NOP                                      | NOP                                          
1478  NOP                                      | IBGEZ vi02, 0x10f8                           
1480  NOP                                      | NOP                                          
1488  NOP                                      | JR vi15                                      
1490  NOP                                      | NOP                                          
1498  NOP                                      | XTOP vi12                                    
14a0  NOP                                      | LQ.xyzw vf24.xyzw, 743(vi00)                 
14a8  NOP                                      | LQ.yzw vf01.yzw, 615(vi00)                   
14b0  NOP                                      | ILW.x vi01, 0(vi12)                          
14b8  NOP                                      | ILW.y vi02, 0(vi12)                          
14c0  NOP                                      | LQ.xyzw vf23.xyzw, 1(vi12)                   
14c8  NOP                                      | IADDIU vi04, vi00, 16384                     
14d0  NOP                                      | IADD vi04, vi04, vi04                        
14d8  NOP                                      | IOR vi04, vi04, vi01                         
14e0  NOP                                      | ISUB vi13, vi14, vi13                        
14e8  NOP                                      | IADDI vi10, vi13, 1                          
14f0  NOP                                      | ISW.x vi04, -1(vi10)                         
14f8  NOP                                      | SQ.yzw vf01.yzw, -1(vi10)                    
1500  NOP                                      | IADDIU vi06, vi12, 29                        
1508  NOP                                      | IADDIU vi09, vi12, 5                         
1510  NOP                                      | IADDIU vi08, vi12, 45                        
1518  NOP                                      | IADDIU vi03, vi00, 691                       
1520  NOP                                      | IADD vi02, vi02, vi02                        
1528  ADD.z vf15.z, vf00.z, vf00.z             | loi 0x49000000 (524288)                      I
1530  ADDi.xy vf15.xy, vf00.xy, I              | RINIT R, vf00.w                              
1538  NOP                                      | LQ.xyzw vf20.xyzw, 742(vi00)                 
1540  NOP                                      | RGET.xyzw vf22.xyzw, R                       
1548  NOP                                      | IADDIU vi01, vi00, 707                       
1550  NOP                                      | ISUB vi02, vi01, vi02                        
1558  NOP                                      | JR vi02                                      
1560  NOP                                      | RINIT R, vf23.x                              
1568  NOP                                      | JALR vi04, vi05                              
1570  NOP                                      | RINIT R, vf23.x                              
1578  NOP                                      | JALR vi04, vi05                              
1580  NOP                                      | NOP                                          
1588  NOP                                      | JALR vi04, vi05                              
1590  NOP                                      | NOP                                          
1598  NOP                                      | JALR vi04, vi05                              
15a0  NOP                                      | NOP                                          
15a8  NOP                                      | JALR vi04, vi05                              
15b0  NOP                                      | RINIT R, vf23.z                              
15b8  NOP                                      | JALR vi04, vi05                              
15c0  NOP                                      | NOP                                          
15c8  NOP                                      | JALR vi04, vi05                              
15d0  NOP                                      | NOP                                          
15d8  NOP                                      | JALR vi04, vi05                              
15e0  NOP                                      | NOP                                          
15e8  NOP                                      | JALR vi04, vi05                              
15f0  NOP                                      | RINIT R, vf23.w                              
15f8  NOP                                      | JALR vi04, vi05                              
1600  NOP                                      | NOP                                          
1608  NOP                                      | JALR vi04, vi05                              
1610  NOP                                      | NOP                                          
1618  NOP                                      | JR vi05                                      
1620  NOP                                      | IADD vi04, vi00, vi15                        
1628  NOP                                      | LQI.xyzw vf01.xyzw, (vi09++)                 
1630  NOP                                      | LQI.xyzw vf02.xyzw, (vi09++)                 
1638  NOP                                      | LQI.xyzw vf03.xyzw, (vi09++)                 
1640  MULAw.xyzw ACC, vf31.xyzw, vf00.w        | LQI.xyzw vf04.xyzw, (vi06++)                 
1648  MADDAx.xyzw ACC, vf28.xyzw, vf01.x       | LQI.xyzw vf06.xyzw, (vi06++)                 
1650  MADDAx.xyzw ACC, vf29.xyzw, vf02.x       | NOP                                          
1658  MADDx.xyzw vf16.xyzw, vf30.xyzw, vf03.x  | NOP                                          
1660  MULA.xyzw ACC, vf24.xyzw, vf20.xyzw      | NOP                                          
1668  MADD.xyzw vf04.xyzw, vf04.xyzw, vf24.xyzw | NOP                                          
1670  MADD.xyzw vf06.xyzw, vf06.xyzw, vf24.xyzw | NOP                                          
1678  NOP                                      | SQI.xyzw vf16.xyzw, (vi03++)                 
1680  MULAw.xyzw ACC, vf31.xyzw, vf00.w        | DIV Q, vf00.w, vf16.w                        
1688  MADDAy.xyzw ACC, vf28.xyzw, vf01.y       | RNEXT.w vf16.w, R                            
1690  MADDAy.xyzw ACC, vf29.xyzw, vf02.y       | LQI.xyzw vf08.xyzw, (vi09++)                 
1698  MADDy.xyzw vf17.xyzw, vf30.xyzw, vf03.y  | LQI.xyzw vf09.xyzw, (vi09++)                 
16a0  MULw.x vf05.x, vf22.x, vf04.w            | MR32.y vf07.y, vf06.y                        
16a8  MULw.x vf07.x, vf22.x, vf06.w            | MR32.y vf05.y, vf04.y                        
16b0  MULAw.xyzw ACC, vf31.xyzw, vf00.w        | MR32.zw vf04.zw, vf00.zw                     
16b8  MADDAz.xyzw ACC, vf28.xyzw, vf01.z       | NOP                                          
16c0  MADDAz.xyzw ACC, vf29.xyzw, vf02.z       | LQI.xyzw vf11.xyzw, (vi06++)                 
16c8  MADDz.xyzw vf18.xyzw, vf30.xyzw, vf03.z  | LQI.xyzw vf13.xyzw, (vi06++)                 
16d0  NOP                                      | SQI.xyzw vf17.xyzw, (vi03++)                 
16d8  ADDA.xyz ACC, vf00.xyz, vf15.xyz         | DIV Q, vf00.w, vf17.w                        
16e0  MADDq.xyz vf16.xyz, vf16.xyz, Q          | RNEXT.w vf17.w, R                            
16e8  MULq.xyz vf04.xyz, vf04.xyz, Q           | NOP                                          
16f0  MULAw.xyzw ACC, vf31.xyzw, vf00.w        | MR32.zw vf05.zw, vf00.zw                     
16f8  MADDAw.xyzw ACC, vf28.xyzw, vf01.w       | LQI.xyzw vf21.xyzw, (vi08++)                 
1700  MADDAw.xyzw ACC, vf29.xyzw, vf02.w       | LQI.xyzw vf10.xyzw, (vi09++)                 
1708  MADDw.xyzw vf19.xyzw, vf30.xyzw, vf03.w  | NOP                                          
1710  NOP                                      | SQI.xyzw vf18.xyzw, (vi03++)                 
1718  ADDA.xyz ACC, vf00.xyz, vf15.xyz         | DIV Q, vf00.w, vf18.w                        
1720  MADDq.xyz vf17.xyz, vf17.xyz, Q          | RNEXT.w vf18.w, R                            
1728  MULq.xyz vf05.xyz, vf05.xyz, Q           | SQI.xyzw vf04.xyzw, (vi10++)                 
1730  NOP                                      | SQI.xyzw vf21.xyzw, (vi10++)                 
1738  NOP                                      | SQI.xyzw vf16.xyzw, (vi10++)                 
1740  MULAw.xyzw ACC, vf31.xyzw, vf00.w        | MR32.zw vf06.zw, vf00.zw                     
1748  MADDAx.xyzw ACC, vf28.xyzw, vf08.x       | LQI.xyzw vf21.xyzw, (vi08++)                 
1750  MADDAx.xyzw ACC, vf29.xyzw, vf09.x       | LQI.xyzw vf01.xyzw, (vi09++)                 
1758  MADDx.xyzw vf16.xyzw, vf30.xyzw, vf10.x  | LQI.xyzw vf02.xyzw, (vi09++)                 
1760  NOP                                      | SQI.xyzw vf19.xyzw, (vi03++)                 
1768  ADDA.xyz ACC, vf00.xyz, vf15.xyz         | DIV Q, vf00.w, vf19.w                        
1770  MADDq.xyz vf18.xyz, vf18.xyz, Q          | RNEXT.w vf19.w, R                            
1778  MULq.xyz vf06.xyz, vf06.xyz, Q           | SQI.xyz vf05.xyz, (vi10++)                   
1780  MULA.xyzw ACC, vf24.xyzw, vf20.xyzw      | SQI.xyzw vf21.xyzw, (vi10++)                 
1788  MADD.xyzw vf11.xyzw, vf11.xyzw, vf24.xyzw | SQI.xyzw vf17.xyzw, (vi10++)                 
1790  MADD.xyzw vf13.xyzw, vf13.xyzw, vf24.xyzw | NOP                                          
1798  MULAw.xyzw ACC, vf31.xyzw, vf00.w        | MR32.zw vf07.zw, vf00.zw                     
17a0  MADDAy.xyzw ACC, vf28.xyzw, vf08.y       | LQI.xyzw vf21.xyzw, (vi08++)                 
17a8  MADDAy.xyzw ACC, vf29.xyzw, vf09.y       | MR32.y vf12.y, vf11.y                        
17b0  MADDy.xyzw vf17.xyzw, vf30.xyzw, vf10.y  | MR32.y vf14.y, vf13.y                        
17b8  NOP                                      | SQI.xyzw vf16.xyzw, (vi03++)                 
17c0  ADDA.xyz ACC, vf00.xyz, vf15.xyz         | DIV Q, vf00.w, vf16.w                        
17c8  MADDq.xyz vf19.xyz, vf19.xyz, Q          | RNEXT.w vf16.w, R                            
17d0  MULq.xyz vf07.xyz, vf07.xyz, Q           | SQI.xyzw vf06.xyzw, (vi10++)                 
17d8  MULw.x vf12.x, vf22.x, vf11.w            | SQI.xyzw vf21.xyzw, (vi10++)                 
17e0  MULw.x vf14.x, vf22.x, vf13.w            | SQI.xyzw vf18.xyzw, (vi10++)                 
17e8  MULAw.xyzw ACC, vf31.xyzw, vf00.w        | MR32.zw vf11.zw, vf00.zw                     
17f0  MADDAz.xyzw ACC, vf28.xyzw, vf08.z       | LQI.xyzw vf21.xyzw, (vi08++)                 
17f8  MADDAz.xyzw ACC, vf29.xyzw, vf09.z       | LQI.xyzw vf04.xyzw, (vi06++)                 
1800  MADDz.xyzw vf18.xyzw, vf30.xyzw, vf10.z  | LQI.xyzw vf06.xyzw, (vi06++)                 
1808  NOP                                      | SQI.xyzw vf17.xyzw, (vi03++)                 
1810  ADDA.xyz ACC, vf00.xyz, vf15.xyz         | DIV Q, vf00.w, vf17.w                        
1818  MADDq.xyz vf16.xyz, vf16.xyz, Q          | RNEXT.w vf17.w, R                            
1820  MULq.xyz vf11.xyz, vf11.xyz, Q           | SQI.xyzw vf07.xyzw, (vi10++)                 
1828  NOP                                      | SQI.xyzw vf21.xyzw, (vi10++)                 
1830  NOP                                      | SQI.xyzw vf19.xyzw, (vi10++)                 
1838  MULAw.xyzw ACC, vf31.xyzw, vf00.w        | MR32.zw vf12.zw, vf00.zw                     
1840  MADDAw.xyzw ACC, vf28.xyzw, vf08.w       | LQI.xyzw vf21.xyzw, (vi08++)                 
1848  MADDAw.xyzw ACC, vf29.xyzw, vf09.w       | LQI.xyzw vf03.xyzw, (vi09++)                 
1850  MADDw.xyzw vf19.xyzw, vf30.xyzw, vf10.w  | IADDIU vi05, vi00, 787                       
1858  NOP                                      | SQI.xyzw vf18.xyzw, (vi03++)                 
1860  ADDA.xyz ACC, vf00.xyz, vf15.xyz         | DIV Q, vf00.w, vf18.w                        
1868  MADDq.xyz vf17.xyz, vf17.xyz, Q          | RNEXT.w vf18.w, R                            
1870  MULq.xyz vf12.xyz, vf12.xyz, Q           | SQI.xyzw vf11.xyzw, (vi10++)                 
1878  NOP                                      | SQI.xyzw vf21.xyzw, (vi10++)                 
1880  NOP                                      | SQI.xyzw vf16.xyzw, (vi10++)                 
1888  NOP                                      | JR vi04                                      
1890  NOP                                      | NOP                                          
1898  MULAw.xyzw ACC, vf31.xyzw, vf00.w        | MR32.zw vf13.zw, vf00.zw                     
18a0  MADDAx.xyzw ACC, vf28.xyzw, vf01.x       | LQI.xyzw vf21.xyzw, (vi08++)                 
18a8  MADDAx.xyzw ACC, vf29.xyzw, vf02.x       | LQI.xyzw vf08.xyzw, (vi09++)                 
18b0  MADDx.xyzw vf16.xyzw, vf30.xyzw, vf03.x  | LQI.xyzw vf09.xyzw, (vi09++)                 
18b8  NOP                                      | SQI.xyzw vf19.xyzw, (vi03++)                 
18c0  ADDA.xyz ACC, vf00.xyz, vf15.xyz         | DIV Q, vf00.w, vf19.w                        
18c8  MADDq.xyz vf18.xyz, vf18.xyz, Q          | RNEXT.w vf19.w, R                            
18d0  MULq.xyz vf13.xyz, vf13.xyz, Q           | SQI.xyzw vf12.xyzw, (vi10++)                 
18d8  MULA.xyzw ACC, vf24.xyzw, vf20.xyzw      | SQI.xyzw vf21.xyzw, (vi10++)                 
18e0  MADD.xyzw vf04.xyzw, vf04.xyzw, vf24.xyzw | SQI.xyzw vf17.xyzw, (vi10++)                 
18e8  MADD.xyzw vf06.xyzw, vf06.xyzw, vf24.xyzw | NOP                                          
18f0  MULAw.xyzw ACC, vf31.xyzw, vf00.w        | MR32.zw vf14.zw, vf00.zw                     
18f8  MADDAy.xyzw ACC, vf28.xyzw, vf01.y       | LQI.xyzw vf21.xyzw, (vi08++)                 
1900  MADDAy.xyzw ACC, vf29.xyzw, vf02.y       | MR32.y vf05.y, vf04.y                        
1908  MADDy.xyzw vf17.xyzw, vf30.xyzw, vf03.y  | MR32.y vf07.y, vf06.y                        
1910  NOP                                      | SQI.xyzw vf16.xyzw, (vi03++)                 
1918  ADDA.xyz ACC, vf00.xyz, vf15.xyz         | DIV Q, vf00.w, vf16.w                        
1920  MADDq.xyz vf19.xyz, vf19.xyz, Q          | RNEXT.w vf16.w, R                            
1928  MULq.xyz vf14.xyz, vf14.xyz, Q           | SQI.xyzw vf13.xyzw, (vi10++)                 
1930  MULw.x vf05.x, vf22.x, vf04.w            | SQI.xyzw vf21.xyzw, (vi10++)                 
1938  MULw.x vf07.x, vf22.x, vf06.w            | SQI.xyzw vf18.xyzw, (vi10++)                 
1940  MULAw.xyzw ACC, vf31.xyzw, vf00.w        | MR32.zw vf04.zw, vf00.zw                     
1948  MADDAz.xyzw ACC, vf28.xyzw, vf01.z       | LQI.xyzw vf21.xyzw, (vi08++)                 
1950  MADDAz.xyzw ACC, vf29.xyzw, vf02.z       | LQI.xyzw vf11.xyzw, (vi06++)                 
1958  MADDz.xyzw vf18.xyzw, vf30.xyzw, vf03.z  | LQI.xyzw vf13.xyzw, (vi06++)                 
1960  NOP                                      | SQI.xyzw vf17.xyzw, (vi03++)                 
1968  ADDA.xyz ACC, vf00.xyz, vf15.xyz         | DIV Q, vf00.w, vf17.w                        
1970  MADDq.xyz vf16.xyz, vf16.xyz, Q          | RNEXT.w vf17.w, R                            
1978  MULq.xyz vf04.xyz, vf04.xyz, Q           | SQI.xyzw vf14.xyzw, (vi10++)                 
1980  NOP                                      | SQI.xyzw vf21.xyzw, (vi10++)                 
1988  NOP                                      | SQI.xyzw vf19.xyzw, (vi10++)                 
1990  MULAw.xyzw ACC, vf31.xyzw, vf00.w        | MR32.zw vf05.zw, vf00.zw                     
1998  MADDAw.xyzw ACC, vf28.xyzw, vf01.w       | LQI.xyzw vf21.xyzw, (vi08++)                 
19a0  MADDAw.xyzw ACC, vf29.xyzw, vf02.w       | LQI.xyzw vf10.xyzw, (vi09++)                 
19a8  MADDw.xyzw vf19.xyzw, vf30.xyzw, vf03.w  | IADDIU vi05, vi00, 744                       
19b0  NOP                                      | SQI.xyzw vf18.xyzw, (vi03++)                 
19b8  ADDA.xyz ACC, vf00.xyz, vf15.xyz         | DIV Q, vf00.w, vf18.w                        
19c0  MADDq.xyz vf17.xyz, vf17.xyz, Q          | RNEXT.w vf18.w, R                            
19c8  MULq.xyz vf05.xyz, vf05.xyz, Q           | SQI.xyzw vf04.xyzw, (vi10++)                 
19d0  NOP                                      | SQI.xyzw vf21.xyzw, (vi10++)                 
19d8  NOP                                      | SQI.xyzw vf16.xyzw, (vi10++)                 
19e0  NOP                                      | JR vi04                                      
19e8  NOP                                      | NOP                                          
19f0  NOP                                      | ILW.x vi11, 0(vi12)                          
19f8  NOP                                      | IADDIU vi09, vi12, 5                         
1a00  NOP                                      | IADDIU vi08, vi12, 77                        
1a08  NOP                                      | IADDIU vi10, vi00, 640                       
1a10  NOP                                      | IADDIU vi06, vi00, 672                       
1a18  ADDw.xyz vf15.xyz, vf00.xyz, vf00.w      | LQ.xyzw vf16.xyzw, 625(vi00)                 
1a20  SUB.xyzw vf14.xyzw, vf14.xyzw, vf14.xyzw | MOVE.w vf15.w, vf00.w                        
1a28  NOP                                      | LQ.xyzw vf23.xyzw, 871(vi00)                 
1a30  NOP                                      | LQI.xyzw vf01.xyzw, (vi09++)                 
1a38  NOP                                      | LQI.xyzw vf02.xyzw, (vi09++)                 
1a40  NOP                                      | LQI.xyzw vf03.xyzw, (vi09++)                 
1a48  NOP                                      | LQI.xyzw vf04.xyzw, (vi08++)                 
1a50  NOP                                      | LQI.xyzw vf05.xyzw, (vi08++)                 
1a58  NOP                                      | LQI.xyzw vf06.xyzw, (vi08++)                 
1a60  ITOF0.xyzw vf04.xyzw, vf04.xyzw          | NOP                                          
1a68  ITOF0.xyzw vf05.xyzw, vf05.xyzw          | NOP                                          
1a70  ITOF0.xyzw vf06.xyzw, vf06.xyzw          | NOP                                          
1a78  NOP                                      | loi 0x3c010204 (0.00787402)                  I
1a80  MULi.xyzw vf04.xyzw, vf04.xyzw, I        | NOP                                          
1a88  MULi.xyzw vf05.xyzw, vf05.xyzw, I        | NOP                                          
1a90  MULi.xyzw vf06.xyzw, vf06.xyzw, I        | NOP                                          
1a98  NOP                                      | NOP                                          
1aa0  SUBx.xyzw vf01.xyzw, vf01.xyzw, vf23.x   | SQ.xyzw vf04.xyzw, -3(vi08)                  
1aa8  SUBy.xyzw vf02.xyzw, vf02.xyzw, vf23.y   | SQ.xyzw vf05.xyzw, -2(vi08)                  
1ab0  SUBz.xyzw vf03.xyzw, vf03.xyzw, vf23.z   | SQ.xyzw vf06.xyzw, -1(vi08)                  
1ab8  NOP                                      | NOP                                          
1ac0  MULA.xyzw ACC, vf01.xyzw, vf04.xyzw      | MOVE.xyzw vf20.xyzw, vf04.xyzw               
1ac8  MADDA.xyzw ACC, vf01.xyzw, vf04.xyzw     | MOVE.xyzw vf21.xyzw, vf05.xyzw               
1ad0  MADDA.xyzw ACC, vf02.xyzw, vf05.xyzw     | MOVE.xyzw vf22.xyzw, vf06.xyzw               
1ad8  MADDA.xyzw ACC, vf02.xyzw, vf05.xyzw     | NOP                                          
1ae0  MADDA.xyzw ACC, vf03.xyzw, vf06.xyzw     | NOP                                          
1ae8  MADD.xyzw vf09.xyzw, vf03.xyzw, vf06.xyzw | NOP                                          
1af0  NOP                                      | NOP                                          
1af8  NOP                                      | NOP                                          
1b00  MULAw.xyzw ACC, vf01.xyzw, vf00.w        | NOP                                          
1b08  MSUB.xyzw vf10.xyzw, vf04.xyzw, vf09.xyzw | NOP                                          
1b10  MULAw.xyzw ACC, vf02.xyzw, vf00.w        | NOP                                          
1b18  MSUB.xyzw vf11.xyzw, vf05.xyzw, vf09.xyzw | NOP                                          
1b20  MULAw.xyzw ACC, vf03.xyzw, vf00.w        | NOP                                          
1b28  MSUB.xyzw vf12.xyzw, vf06.xyzw, vf09.xyzw | NOP                                          
1b30  MULA.xyzw ACC, vf10.xyzw, vf10.xyzw      | NOP                                          
1b38  MADDA.xyzw ACC, vf11.xyzw, vf11.xyzw     | NOP                                          
1b40  NOP                                      | NOP                                          
1b48  MADD.xyzw vf13.xyzw, vf12.xyzw, vf12.xyzw | NOP                                          
1b50  NOP                                      | NOP                                          
1b58  NOP                                      | NOP                                          
1b60  NOP                                      | NOP                                          
1b68  ITOF0.xyzw vf13.xyzw, vf13.xyzw          | NOP                                          
1b70  NOP                                      | NOP                                          
1b78  NOP                                      | NOP                                          
1b80  MULAy.xyzw ACC, vf15.xyzw, vf16.y        | NOP                                          
1b88  MADDx.xyzw vf13.xyzw, vf13.xyzw, vf16.x  | NOP                                          
1b90  NOP                                      | NOP                                          
1b98  NOP                                      | NOP                                          
1ba0  NOP                                      | IADDI vi11, vi11, -4                         
1ba8  FTOI0.xyzw vf13.xyzw, vf13.xyzw          | LQI.xyzw vf01.xyzw, (vi09++)                 
1bb0  NOP                                      | LQI.xyzw vf02.xyzw, (vi09++)                 
1bb8  NOP                                      | LQI.xyzw vf03.xyzw, (vi09++)                 
1bc0  NOP                                      | NOP                                          
1bc8  MUL.xyzw vf10.xyzw, vf10.xyzw, vf13.xyzw | NOP                                          
1bd0  MUL.xyzw vf11.xyzw, vf11.xyzw, vf13.xyzw | LQI.xyzw vf04.xyzw, (vi08++)                 
1bd8  MUL.xyzw vf12.xyzw, vf12.xyzw, vf13.xyzw | LQI.xyzw vf05.xyzw, (vi08++)                 
1be0  NOP                                      | LQI.xyzw vf06.xyzw, (vi08++)                 
1be8  MULA.xyzw ACC, vf10.xyzw, vf20.xyzw      | SQI.xyzw vf10.xyzw, (vi10++)                 
1bf0  MADDA.xyzw ACC, vf11.xyzw, vf21.xyzw     | SQI.xyzw vf11.xyzw, (vi10++)                 
1bf8  MADD.xyzw vf20.xyzw, vf12.xyzw, vf22.xyzw | SQI.xyzw vf12.xyzw, (vi10++)                 
1c00  ITOF0.xyzw vf04.xyzw, vf04.xyzw          | NOP                                          
1c08  ITOF0.xyzw vf05.xyzw, vf05.xyzw          | NOP                                          
1c10  ITOF0.xyzw vf06.xyzw, vf06.xyzw          | loi 0x3c23d70a (0.01)                        I
1c18  MAXi.xyzw vf20.xyzw, vf20.xyzw, I        | loi 0x3c010204 (0.00787402)                  I
1c20  MULi.xyzw vf04.xyzw, vf04.xyzw, I        | NOP                                          
1c28  MULi.xyzw vf05.xyzw, vf05.xyzw, I        | NOP                                          
1c30  MULi.xyzw vf06.xyzw, vf06.xyzw, I        | IBGTZ vi11, 0x1a98                           
1c38  NOP                                      | SQI.xyzw vf20.xyzw, (vi06++)                 
1c40  NOP                                      | JR vi15                                      
1c48  NOP                                      | NOP                                          
1c50  NOP                                      | ILW.x vi02, 0(vi12)                          
1c58  NOP                                      | IADDIU vi08, vi12, 77                        
1c60  NOP                                      | IADDIU vi10, vi13, 1                         
1c68  NOP                                      | IADDI vi11, vi02, -4                         
1c70  NOP                                      | LQ.xyz vf01.xyz, 862(vi00)                   
1c78  NOP                                      | loi 0x43000000 (128)                         I
1c80  MULi.w vf01.w, vf00.w, I                 | NOP                                          
1c88  NOP                                      | NOP                                          
1c90  NOP                                      | NOP                                          
1c98  NOP                                      | NOP                                          
1ca0  FTOI0.xyzw vf01.xyzw, vf01.xyzw          | NOP                                          
1ca8  NOP                                      | NOP                                          
1cb0  NOP                                      | NOP                                          
1cb8  NOP                                      | NOP                                          
1cc0  NOP                                      | SQ.xyzw vf01.xyzw, 1(vi10)                   
1cc8  NOP                                      | SQ.xyzw vf01.xyzw, 4(vi10)                   
1cd0  NOP                                      | SQ.xyzw vf01.xyzw, 7(vi10)                   
1cd8  NOP                                      | SQ.xyzw vf01.xyzw, 10(vi10)                  
1ce0  NOP                                      | IADDIU vi10, vi10, 12                        
1ce8  NOP                                      | IBGTZ vi11, 0x1cc0                           
1cf0  NOP                                      | IADDI vi11, vi11, -4                         
1cf8  NOP                                      | JR vi15                                      
1d00  NOP                                      | NOP                                          
1d08  NOP                                      | ILW.x vi02, 0(vi12)                          
1d10  NOP                                      | IADDIU vi08, vi12, 77                        
1d18  NOP                                      | IADDIU vi10, vi13, 1                         
1d20  NOP                                      | IADDIU vi06, vi00, 640                       
1d28  NOP                                      | IADDIU vi09, vi00, 672                       
1d30  NOP                                      | IADDI vi11, vi02, -4                         
1d38  NOP                                      | SQ.xyzw vf24.xyzw, 903(vi00)                 
1d40  NOP                                      | SQ.xyzw vf25.xyzw, 904(vi00)                 
1d48  NOP                                      | SQ.xyzw vf26.xyzw, 905(vi00)                 
1d50  NOP                                      | SQ.xyzw vf27.xyzw, 906(vi00)                 
1d58  NOP                                      | SQ.xyzw vf28.xyzw, 907(vi00)                 
1d60  NOP                                      | SQ.xyzw vf29.xyzw, 908(vi00)                 
1d68  NOP                                      | SQ.xyzw vf30.xyzw, 909(vi00)                 
1d70  NOP                                      | SQ.xyzw vf31.xyzw, 910(vi00)                 
1d78  NOP                                      | LQ.xyzw vf10.xyzw, 877(vi00)                 
1d80  NOP                                      | LQ.xyzw vf11.xyzw, 878(vi00)                 
1d88  NOP                                      | LQ.xyzw vf12.xyzw, 879(vi00)                 
1d90  NOP                                      | LQ.xyzw vf13.xyzw, 880(vi00)                 
1d98  NOP                                      | LQ.xyzw vf14.xyzw, 881(vi00)                 
1da0  NOP                                      | LQ.xyzw vf15.xyzw, 882(vi00)                 
1da8  NOP                                      | LQ.xyzw vf16.xyzw, 883(vi00)                 
1db0  NOP                                      | LQ.xyzw vf17.xyzw, 884(vi00)                 
1db8  NOP                                      | LQ.xyzw vf18.xyzw, 885(vi00)                 
1dc0  NOP                                      | LQ.xyzw vf19.xyzw, 886(vi00)                 
1dc8  NOP                                      | LQ.xyzw vf25.xyzw, 841(vi00)                 
1dd0  NOP                                      | LQ.xyzw vf26.xyzw, 842(vi00)                 
1dd8  ADDw.xyz vf24.xyz, vf00.xyz, vf00.w      | NOP                                          
1de0  NOP                                      | MOVE.w vf24.w, vf00.w                        
1de8  NOP                                      | LQI.xyzw vf01.xyzw, (vi08++)                 
1df0  NOP                                      | LQI.xyzw vf02.xyzw, (vi08++)                 
1df8  NOP                                      | LQI.xyzw vf03.xyzw, (vi08++)                 
1e00  NOP                                      | LQI.xyzw vf28.xyzw, (vi09++)                 
1e08  MUL.xyzw vf04.xyzw, vf01.xyzw, vf01.xyzw | NOP                                          
1e10  MUL.xyzw vf05.xyzw, vf02.xyzw, vf02.xyzw | NOP                                          
1e18  MUL.xyzw vf06.xyzw, vf03.xyzw, vf03.xyzw | NOP                                          
1e20  MUL.xyzw vf07.xyzw, vf01.xyzw, vf02.xyzw | NOP                                          
1e28  MUL.xyzw vf08.xyzw, vf03.xyzw, vf01.xyzw | NOP                                          
1e30  MUL.xyzw vf09.xyzw, vf02.xyzw, vf03.xyzw | NOP                                          
1e38  MULAw.xyzw ACC, vf10.xyzw, vf00.w        | NOP                                          
1e40  MADDAx.xyzw ACC, vf11.xyzw, vf04.x       | NOP                                          
1e48  MADDAx.xyzw ACC, vf12.xyzw, vf05.x       | NOP                                          
1e50  MADDAx.xyzw ACC, vf13.xyzw, vf06.x       | NOP                                          
1e58  MADDAx.xyzw ACC, vf14.xyzw, vf07.x       | NOP                                          
1e60  MADDAx.xyzw ACC, vf15.xyzw, vf08.x       | NOP                                          
1e68  MADDAx.xyzw ACC, vf16.xyzw, vf09.x       | NOP                                          
1e70  MADDAx.xyzw ACC, vf17.xyzw, vf01.x       | NOP                                          
1e78  MADDAx.xyzw ACC, vf18.xyzw, vf02.x       | NOP                                          
1e80  MADDx.xyzw vf20.xyzw, vf19.xyzw, vf03.x  | NOP                                          
1e88  MULAw.xyzw ACC, vf10.xyzw, vf00.w        | NOP                                          
1e90  MADDAy.xyzw ACC, vf11.xyzw, vf04.y       | NOP                                          
1e98  MADDAy.xyzw ACC, vf12.xyzw, vf05.y       | NOP                                          
1ea0  MADDAy.xyzw ACC, vf13.xyzw, vf06.y       | NOP                                          
1ea8  MADDAy.xyzw ACC, vf14.xyzw, vf07.y       | NOP                                          
1eb0  MADDAy.xyzw ACC, vf15.xyzw, vf08.y       | NOP                                          
1eb8  MADDAy.xyzw ACC, vf16.xyzw, vf09.y       | NOP                                          
1ec0  MADDAy.xyzw ACC, vf17.xyzw, vf01.y       | NOP                                          
1ec8  MADDAy.xyzw ACC, vf18.xyzw, vf02.y       | NOP                                          
1ed0  MADDy.xyzw vf21.xyzw, vf19.xyzw, vf03.y  | NOP                                          
1ed8  MULAw.xyzw ACC, vf10.xyzw, vf00.w        | NOP                                          
1ee0  MADDAz.xyzw ACC, vf11.xyzw, vf04.z       | NOP                                          
1ee8  MADDAz.xyzw ACC, vf12.xyzw, vf05.z       | NOP                                          
1ef0  MADDAz.xyzw ACC, vf13.xyzw, vf06.z       | NOP                                          
1ef8  MADDAz.xyzw ACC, vf14.xyzw, vf07.z       | NOP                                          
1f00  MADDAz.xyzw ACC, vf15.xyzw, vf08.z       | NOP                                          
1f08  MADDAz.xyzw ACC, vf16.xyzw, vf09.z       | NOP                                          
1f10  MADDAz.xyzw ACC, vf17.xyzw, vf01.z       | NOP                                          
1f18  MADDAz.xyzw ACC, vf18.xyzw, vf02.z       | NOP                                          
1f20  MADDz.xyzw vf22.xyzw, vf19.xyzw, vf03.z  | NOP                                          
1f28  MULAw.xyzw ACC, vf10.xyzw, vf00.w        | NOP                                          
1f30  MADDAw.xyzw ACC, vf11.xyzw, vf04.w       | NOP                                          
1f38  MADDAw.xyzw ACC, vf12.xyzw, vf05.w       | NOP                                          
1f40  MADDAw.xyzw ACC, vf13.xyzw, vf06.w       | NOP                                          
1f48  MADDAw.xyzw ACC, vf14.xyzw, vf07.w       | NOP                                          
1f50  MADDAw.xyzw ACC, vf15.xyzw, vf08.w       | NOP                                          
1f58  MADDAw.xyzw ACC, vf16.xyzw, vf09.w       | NOP                                          
1f60  MADDAw.xyzw ACC, vf17.xyzw, vf01.w       | NOP                                          
1f68  MADDAw.xyzw ACC, vf18.xyzw, vf02.w       | NOP                                          
1f70  MADDw.xyzw vf23.xyzw, vf19.xyzw, vf03.w  | NOP                                          
1f78  MULAw.xyzw ACC, vf25.xyzw, vf00.w        | NOP                                          
1f80  MADDx.xyzw vf01.xyzw, vf26.xyzw, vf28.x  | NOP                                          
1f88  MADDy.xyzw vf02.xyzw, vf26.xyzw, vf28.y  | NOP                                          
1f90  MADDz.xyzw vf03.xyzw, vf26.xyzw, vf28.z  | NOP                                          
1f98  MADDw.xyzw vf04.xyzw, vf26.xyzw, vf28.w  | NOP                                          
1fa0  MUL.xyz vf01.xyz, vf01.xyz, vf20.xyz     | NOP                                          
1fa8  MUL.xyz vf02.xyz, vf02.xyz, vf21.xyz     | NOP                                          
1fb0  MUL.xyz vf03.xyz, vf03.xyz, vf22.xyz     | NOP                                          
1fb8  MUL.xyz vf04.xyz, vf04.xyz, vf23.xyz     | NOP                                          
1fc0  MAXx.xyzw vf01.xyzw, vf01.xyzw, vf00.x   | NOP                                          
1fc8  MAXx.xyzw vf02.xyzw, vf02.xyzw, vf00.x   | NOP                                          
1fd0  MAXx.xyzw vf03.xyzw, vf03.xyzw, vf00.x   | NOP                                          
1fd8  MAXx.xyzw vf04.xyzw, vf04.xyzw, vf00.x   | loi 0x3ffeb852 (1.99)                        I
1fe0  MINIi.xyzw vf01.xyzw, vf01.xyzw, I       | NOP                                          
1fe8  MINIi.xyzw vf02.xyzw, vf02.xyzw, I       | NOP                                          
1ff0  MINIi.xyzw vf03.xyzw, vf03.xyzw, I       | NOP                                          
1ff8  MINIi.xyzw vf04.xyzw, vf04.xyzw, I       | loi 0x43000000 (128)                         I
2000  MULi.xyzw vf05.xyzw, vf01.xyzw, I        | NOP                                          
2008  MULi.xyzw vf06.xyzw, vf02.xyzw, I        | NOP                                          
2010  MULi.xyzw vf07.xyzw, vf03.xyzw, I        | NOP                                          
2018  MULi.xyzw vf08.xyzw, vf04.xyzw, I        | NOP                                          
2020  FTOI0.xyzw vf05.xyzw, vf05.xyzw          | LQI.xyzw vf01.xyzw, (vi08++)                 
2028  FTOI0.xyzw vf06.xyzw, vf06.xyzw          | LQI.xyzw vf02.xyzw, (vi08++)                 
2030  FTOI0.xyzw vf07.xyzw, vf07.xyzw          | LQI.xyzw vf03.xyzw, (vi08++)                 
2038  FTOI0.xyzw vf08.xyzw, vf08.xyzw          | LQI.xyzw vf28.xyzw, (vi09++)                 
2040  MUL.xyzw vf04.xyzw, vf01.xyzw, vf01.xyzw | SQ.xyzw vf05.xyzw, 1(vi10)                   
2048  MUL.xyzw vf05.xyzw, vf02.xyzw, vf02.xyzw | SQ.xyzw vf06.xyzw, 4(vi10)                   
2050  MUL.xyzw vf06.xyzw, vf03.xyzw, vf03.xyzw | SQ.xyzw vf07.xyzw, 7(vi10)                   
2058  MUL.xyzw vf07.xyzw, vf01.xyzw, vf02.xyzw | SQ.xyzw vf08.xyzw, 10(vi10)                  
2060  MUL.xyzw vf08.xyzw, vf03.xyzw, vf01.xyzw | IADDIU vi10, vi10, 12                        
2068  MUL.xyzw vf09.xyzw, vf02.xyzw, vf03.xyzw | IBGTZ vi11, 0x1e40                           
2070  MULAw.xyzw ACC, vf10.xyzw, vf00.w        | IADDI vi11, vi11, -4                         
2078  NOP                                      | LQ.xyzw vf24.xyzw, 903(vi00)                 
2080  NOP                                      | LQ.xyzw vf25.xyzw, 904(vi00)                 
2088  NOP                                      | LQ.xyzw vf26.xyzw, 905(vi00)                 
2090  NOP                                      | LQ.xyzw vf27.xyzw, 906(vi00)                 
2098  NOP                                      | LQ.xyzw vf28.xyzw, 907(vi00)                 
20a0  NOP                                      | LQ.xyzw vf29.xyzw, 908(vi00)                 
20a8  NOP                                      | LQ.xyzw vf30.xyzw, 909(vi00)                 
20b0  NOP                                      | LQ.xyzw vf31.xyzw, 910(vi00)                 
20b8  NOP                                      | JR vi15                                      
20c0  NOP                                      | NOP                                          
20c8  NOP                                      | ILW.x vi11, 0(vi12)                          
20d0  NOP                                      | LQ.yzw vf01.yzw, 619(vi00)                   
20d8  NOP                                      | LQ.yzw vf02.yzw, 620(vi00)                   
20e0  NOP                                      | IADDIU vi01, vi00, 16384                     
20e8  NOP                                      | IADD vi01, vi01, vi01                        
20f0  NOP                                      | IOR vi01, vi01, vi11                         
20f8  NOP                                      | MFIR.x vf01.x, vi01                          
2100  NOP                                      | MFIR.x vf02.x, vi01                          
2108  NOP                                      | IADDI vi09, vi13, 1                          
2110  NOP                                      | ISUB vi13, vi14, vi13                        
2118  NOP                                      | IADDI vi10, vi13, 1                          
2120  NOP                                      | SQ.xyzw vf01.xyzw, -1(vi10)                  
2128  NOP                                      | SQ.xyzw vf02.xyzw, 626(vi00)                 
2130  NOP                                      | IADDIU vi06, vi00, 640                       
2138  NOP                                      | IADDIU vi08, vi00, 672                       
2140  NOP                                      | IADDIU vi04, vi00, 913                       
2148  NOP                                      | IADDIU vi05, vi00, 945                       
2150  NOP                                      | IADDI vi11, vi11, -4                         
2158  NOP                                      | SQ.xyzw vf24.xyzw, 903(vi00)                 
2160  NOP                                      | SQ.xyzw vf25.xyzw, 904(vi00)                 
2168  NOP                                      | SQ.xyzw vf26.xyzw, 905(vi00)                 
2170  NOP                                      | SQ.xyzw vf27.xyzw, 906(vi00)                 
2178  NOP                                      | SQ.xyzw vf28.xyzw, 907(vi00)                 
2180  NOP                                      | SQ.xyzw vf29.xyzw, 908(vi00)                 
2188  NOP                                      | SQ.xyzw vf30.xyzw, 909(vi00)                 
2190  NOP                                      | SQ.xyzw vf31.xyzw, 910(vi00)                 
2198  NOP                                      | LQ.xyzw vf10.xyzw, 877(vi00)                 
21a0  NOP                                      | LQ.xyzw vf11.xyzw, 878(vi00)                 
21a8  NOP                                      | LQ.xyzw vf12.xyzw, 879(vi00)                 
21b0  NOP                                      | LQ.xyzw vf13.xyzw, 880(vi00)                 
21b8  NOP                                      | LQ.xyzw vf14.xyzw, 881(vi00)                 
21c0  NOP                                      | LQ.xyzw vf15.xyzw, 882(vi00)                 
21c8  NOP                                      | LQ.xyzw vf16.xyzw, 883(vi00)                 
21d0  NOP                                      | LQ.xyzw vf17.xyzw, 884(vi00)                 
21d8  NOP                                      | LQ.xyzw vf18.xyzw, 885(vi00)                 
21e0  NOP                                      | LQ.xyzw vf19.xyzw, 886(vi00)                 
21e8  NOP                                      | LQ.xyzw vf25.xyzw, 843(vi00)                 
21f0  NOP                                      | LQ.xyzw vf26.xyzw, 844(vi00)                 
21f8  ADDw.xyz vf24.xyz, vf00.xyz, vf00.w      | NOP                                          
2200  NOP                                      | MOVE.w vf24.w, vf00.w                        
2208  NOP                                      | LQI.xyzw vf01.xyzw, (vi06++)                 
2210  NOP                                      | LQI.xyzw vf02.xyzw, (vi06++)                 
2218  NOP                                      | LQI.xyzw vf03.xyzw, (vi06++)                 
2220  NOP                                      | LQI.xyzw vf28.xyzw, (vi08++)                 
2228  MUL.xyzw vf04.xyzw, vf01.xyzw, vf01.xyzw | NOP                                          
2230  MUL.xyzw vf05.xyzw, vf02.xyzw, vf02.xyzw | NOP                                          
2238  MUL.xyzw vf06.xyzw, vf03.xyzw, vf03.xyzw | NOP                                          
2240  MUL.xyzw vf07.xyzw, vf01.xyzw, vf02.xyzw | NOP                                          
2248  MUL.xyzw vf08.xyzw, vf03.xyzw, vf01.xyzw | NOP                                          
2250  MUL.xyzw vf09.xyzw, vf02.xyzw, vf03.xyzw | NOP                                          
2258  MULAw.xyzw ACC, vf24.xyzw, vf10.w        | NOP                                          
2260  MADDAw.xyzw ACC, vf01.xyzw, vf17.w       | NOP                                          
2268  MADDAw.xyzw ACC, vf02.xyzw, vf18.w       | NOP                                          
2270  MADDAw.xyzw ACC, vf03.xyzw, vf19.w       | NOP                                          
2278  MADDAw.xyzw ACC, vf07.xyzw, vf14.w       | NOP                                          
2280  MADDAw.xyzw ACC, vf08.xyzw, vf15.w       | NOP                                          
2288  MADDAw.xyzw ACC, vf09.xyzw, vf16.w       | NOP                                          
2290  MADDAw.xyzw ACC, vf04.xyzw, vf11.w       | NOP                                          
2298  MADDAw.xyzw ACC, vf05.xyzw, vf12.w       | NOP                                          
22a0  MADDw.xyzw vf29.xyzw, vf06.xyzw, vf13.w  | NOP                                          
22a8  MULAw.xyzw ACC, vf10.xyzw, vf00.w        | NOP                                          
22b0  MADDAx.xyzw ACC, vf11.xyzw, vf04.x       | NOP                                          
22b8  MADDAx.xyzw ACC, vf12.xyzw, vf05.x       | NOP                                          
22c0  MAXx.xyzw vf29.xyzw, vf29.xyzw, vf00.x   | NOP                                          
22c8  MADDAx.xyzw ACC, vf13.xyzw, vf06.x       | NOP                                          
22d0  MADDAx.xyzw ACC, vf14.xyzw, vf07.x       | NOP                                          
22d8  MADDAx.xyzw ACC, vf15.xyzw, vf08.x       | NOP                                          
22e0  MINIw.xyzw vf29.xyzw, vf29.xyzw, vf00.w  | NOP                                          
22e8  MADDAx.xyzw ACC, vf16.xyzw, vf09.x       | NOP                                          
22f0  MADDAx.xyzw ACC, vf17.xyzw, vf01.x       | NOP                                          
22f8  MADDAx.xyzw ACC, vf18.xyzw, vf02.x       | NOP                                          
2300  MADDx.xyzw vf20.xyzw, vf19.xyzw, vf03.x  | SQI.xyzw vf29.xyzw, (vi04++)                 
2308  MULAw.xyzw ACC, vf10.xyzw, vf00.w        | NOP                                          
2310  MADDAy.xyzw ACC, vf11.xyzw, vf04.y       | NOP                                          
2318  MADDAy.xyzw ACC, vf12.xyzw, vf05.y       | NOP                                          
2320  MADDAy.xyzw ACC, vf13.xyzw, vf06.y       | SQI.xyzw vf20.xyzw, (vi05++)                 
2328  MADDAy.xyzw ACC, vf14.xyzw, vf07.y       | NOP                                          
2330  MADDAy.xyzw ACC, vf15.xyzw, vf08.y       | NOP                                          
2338  MADDAy.xyzw ACC, vf16.xyzw, vf09.y       | NOP                                          
2340  MADDAy.xyzw ACC, vf17.xyzw, vf01.y       | NOP                                          
2348  MADDAy.xyzw ACC, vf18.xyzw, vf02.y       | NOP                                          
2350  MADDy.xyzw vf21.xyzw, vf19.xyzw, vf03.y  | NOP                                          
2358  MULAw.xyzw ACC, vf10.xyzw, vf00.w        | NOP                                          
2360  MADDAz.xyzw ACC, vf11.xyzw, vf04.z       | NOP                                          
2368  MADDAz.xyzw ACC, vf12.xyzw, vf05.z       | NOP                                          
2370  MADDAz.xyzw ACC, vf13.xyzw, vf06.z       | SQI.xyzw vf21.xyzw, (vi05++)                 
2378  MADDAz.xyzw ACC, vf14.xyzw, vf07.z       | NOP                                          
2380  MADDAz.xyzw ACC, vf15.xyzw, vf08.z       | NOP                                          
2388  MADDAz.xyzw ACC, vf16.xyzw, vf09.z       | NOP                                          
2390  MADDAz.xyzw ACC, vf17.xyzw, vf01.z       | NOP                                          
2398  MADDAz.xyzw ACC, vf18.xyzw, vf02.z       | NOP                                          
23a0  MADDz.xyzw vf22.xyzw, vf19.xyzw, vf03.z  | NOP                                          
23a8  MULAw.xyzw ACC, vf10.xyzw, vf00.w        | NOP                                          
23b0  MADDAw.xyzw ACC, vf11.xyzw, vf04.w       | NOP                                          
23b8  MADDAw.xyzw ACC, vf12.xyzw, vf05.w       | NOP                                          
23c0  MADDAw.xyzw ACC, vf13.xyzw, vf06.w       | SQI.xyzw vf22.xyzw, (vi05++)                 
23c8  MADDAw.xyzw ACC, vf14.xyzw, vf07.w       | NOP                                          
23d0  MADDAw.xyzw ACC, vf15.xyzw, vf08.w       | NOP                                          
23d8  MADDAw.xyzw ACC, vf16.xyzw, vf09.w       | NOP                                          
23e0  ITOF0.xyzw vf29.xyzw, vf29.xyzw          | NOP                                          
23e8  ITOF0.xyzw vf28.xyzw, vf28.xyzw          | NOP                                          
23f0  MADDAw.xyzw ACC, vf17.xyzw, vf01.w       | NOP                                          
23f8  MADDAw.xyzw ACC, vf18.xyzw, vf02.w       | NOP                                          
2400  MADDw.xyzw vf23.xyzw, vf19.xyzw, vf03.w  | NOP                                          
2408  MULAw.xyzw ACC, vf24.xyzw, vf26.w        | NOP                                          
2410  MADDw.xyzw vf29.xyzw, vf29.xyzw, vf25.w  | NOP                                          
2418  MULAw.xyzw ACC, vf24.xyzw, vf26.w        | NOP                                          
2420  MADDw.xyzw vf28.xyzw, vf28.xyzw, vf25.w  | NOP                                          
2428  NOP                                      | NOP                                          
2430  FTOI0.xyzw vf29.xyzw, vf29.xyzw          | SQI.xyzw vf23.xyzw, (vi05++)                 
2438  FTOI0.xyzw vf28.xyzw, vf28.xyzw          | NOP                                          
2440  NOP                                      | NOP                                          
2448  NOP                                      | NOP                                          
2450  MAXx.xyzw vf29.xyzw, vf29.xyzw, vf00.x   | NOP                                          
2458  MAXx.xyzw vf28.xyzw, vf28.xyzw, vf00.x   | NOP                                          
2460  MULAw.xyzw ACC, vf25.xyzw, vf00.w        | LQ.xyzw vf01.xyzw, 0(vi09)                   
2468  MADDx.xyzw vf05.xyzw, vf26.xyzw, vf28.x  | LQ.xyzw vf02.xyzw, 2(vi09)                   
2470  MADDy.xyzw vf06.xyzw, vf26.xyzw, vf28.y  | LQ.xyzw vf03.xyzw, 3(vi09)                   
2478  MADDz.xyzw vf07.xyzw, vf26.xyzw, vf28.z  | LQ.xyzw vf04.xyzw, 5(vi09)                   
2480  MADDw.xyzw vf08.xyzw, vf26.xyzw, vf28.w  | loi 0x3ffeb852 (1.99)                        I
2488  MULx.xyzw vf05.xyzw, vf05.xyzw, vf29.x   | SQ.xyzw vf01.xyzw, 0(vi10)                   
2490  MULy.xyzw vf06.xyzw, vf06.xyzw, vf29.y   | SQ.xyzw vf02.xyzw, 2(vi10)                   
2498  MULz.xyzw vf07.xyzw, vf07.xyzw, vf29.z   | SQ.xyzw vf03.xyzw, 3(vi10)                   
24a0  MULw.xyzw vf08.xyzw, vf08.xyzw, vf29.w   | SQ.xyzw vf04.xyzw, 5(vi10)                   
24a8  MUL.xyzw vf20.xyzw, vf20.xyzw, vf05.xyzw | LQ.xyzw vf05.xyzw, 6(vi09)                   
24b0  MUL.xyzw vf21.xyzw, vf21.xyzw, vf06.xyzw | LQ.xyzw vf06.xyzw, 8(vi09)                   
24b8  MUL.xyzw vf22.xyzw, vf22.xyzw, vf07.xyzw | LQ.xyzw vf07.xyzw, 9(vi09)                   
24c0  MUL.xyzw vf23.xyzw, vf23.xyzw, vf08.xyzw | LQ.xyzw vf08.xyzw, 11(vi09)                  
24c8  MAXx.xyzw vf20.xyzw, vf20.xyzw, vf00.x   | SQ.xyzw vf05.xyzw, 6(vi10)                   
24d0  MAXx.xyzw vf21.xyzw, vf21.xyzw, vf00.x   | SQ.xyzw vf06.xyzw, 8(vi10)                   
24d8  MAXx.xyzw vf22.xyzw, vf22.xyzw, vf00.x   | SQ.xyzw vf07.xyzw, 9(vi10)                   
24e0  MAXx.xyzw vf23.xyzw, vf23.xyzw, vf00.x   | SQ.xyzw vf08.xyzw, 11(vi10)                  
24e8  MINIi.xyzw vf20.xyzw, vf20.xyzw, I       | LQI.xyzw vf01.xyzw, (vi06++)                 
24f0  MINIi.xyzw vf21.xyzw, vf21.xyzw, I       | LQI.xyzw vf02.xyzw, (vi06++)                 
24f8  MINIi.xyzw vf22.xyzw, vf22.xyzw, I       | LQI.xyzw vf03.xyzw, (vi06++)                 
2500  MINIi.xyzw vf23.xyzw, vf23.xyzw, I       | loi 0x43000000 (128)                         I
2508  MULi.xyzw vf20.xyzw, vf20.xyzw, I        | LQI.xyzw vf28.xyzw, (vi08++)                 
2510  MULi.xyzw vf21.xyzw, vf21.xyzw, I        | NOP                                          
2518  MULi.xyzw vf22.xyzw, vf22.xyzw, I        | NOP                                          
2520  MULi.xyzw vf23.xyzw, vf23.xyzw, I        | NOP                                          
2528  FTOI0.xyzw vf20.xyzw, vf20.xyzw          | NOP                                          
2530  FTOI0.xyzw vf21.xyzw, vf21.xyzw          | NOP                                          
2538  FTOI0.xyzw vf22.xyzw, vf22.xyzw          | NOP                                          
2540  FTOI0.xyzw vf23.xyzw, vf23.xyzw          | NOP                                          
2548  MUL.xyzw vf04.xyzw, vf01.xyzw, vf01.xyzw | SQ.xyzw vf20.xyzw, 1(vi10)                   
2550  MUL.xyzw vf05.xyzw, vf02.xyzw, vf02.xyzw | SQ.xyzw vf21.xyzw, 4(vi10)                   
2558  MUL.xyzw vf06.xyzw, vf03.xyzw, vf03.xyzw | SQ.xyzw vf22.xyzw, 7(vi10)                   
2560  MUL.xyzw vf07.xyzw, vf01.xyzw, vf02.xyzw | SQ.xyzw vf23.xyzw, 10(vi10)                  
2568  MUL.xyzw vf08.xyzw, vf03.xyzw, vf01.xyzw | IADDIU vi09, vi09, 12                        
2570  MUL.xyzw vf09.xyzw, vf02.xyzw, vf03.xyzw | IADDIU vi10, vi10, 12                        
2578  MULAw.xyzw ACC, vf24.xyzw, vf10.w        | IBGTZ vi11, 0x2268                           
2580  MADDAw.xyzw ACC, vf01.xyzw, vf17.w       | IADDI vi11, vi11, -4                         
2588  NOP                                      | LQ.xyzw vf24.xyzw, 903(vi00)                 
2590  NOP                                      | LQ.xyzw vf25.xyzw, 904(vi00)                 
2598  NOP                                      | LQ.xyzw vf26.xyzw, 905(vi00)                 
25a0  NOP                                      | LQ.xyzw vf27.xyzw, 906(vi00)                 
25a8  NOP                                      | LQ.xyzw vf28.xyzw, 907(vi00)                 
25b0  NOP                                      | LQ.xyzw vf29.xyzw, 908(vi00)                 
25b8  NOP                                      | LQ.xyzw vf30.xyzw, 909(vi00)                 
25c0  NOP                                      | LQ.xyzw vf31.xyzw, 910(vi00)                 
25c8  NOP                                      | JR vi15                                      
25d0  NOP                                      | NOP                                          
25d8  NOP                                      | ILW.x vi11, 0(vi12)                          
25e0  NOP                                      | LQ.yzw vf01.yzw, 617(vi00)                   
25e8  NOP                                      | LQ.yzw vf02.yzw, 618(vi00)                   
25f0  NOP                                      | IADDIU vi01, vi00, 16384                     
25f8  NOP                                      | IADD vi01, vi01, vi01                        
2600  NOP                                      | IOR vi01, vi01, vi11                         
2608  NOP                                      | MFIR.x vf01.x, vi01                          
2610  NOP                                      | MFIR.x vf02.x, vi01                          
2618  NOP                                      | IADDI vi09, vi13, 1                          
2620  NOP                                      | ISUB vi13, vi14, vi13                        
2628  NOP                                      | IADDI vi10, vi13, 1                          
2630  NOP                                      | SQ.xyzw vf01.xyzw, -1(vi10)                  
2638  NOP                                      | SQ.xyzw vf02.xyzw, 626(vi00)                 
2640  NOP                                      | IADDIU vi06, vi00, 640                       
2648  NOP                                      | IADDIU vi08, vi00, 672                       
2650  NOP                                      | IADDIU vi04, vi00, 913                       
2658  NOP                                      | IADDIU vi05, vi00, 945                       
2660  NOP                                      | IADDI vi11, vi11, -4                         
2668  NOP                                      | LQ.xyzw vf15.xyzw, 625(vi00)                 
2670  NOP                                      | LQ.xyzw vf16.xyzw, 845(vi00)                 
2678  NOP                                      | LQ.xyzw vf17.xyzw, 846(vi00)                 
2680  NOP                                      | LQ.xyzw vf20.xyzw, 873(vi00)                 
2688  NOP                                      | LQ.xyzw vf21.xyzw, 874(vi00)                 
2690  NOP                                      | LQ.xyzw vf22.xyzw, 875(vi00)                 
2698  NOP                                      | LQ.xyzw vf23.xyzw, 871(vi00)                 
26a0  SUB.xyzw vf19.xyzw, vf00.xyzw, vf00.xyzw | MOVE.w vf13.w, vf00.w                        
26a8  SUB.xyw vf18.xyw, vf18.xyw, vf18.xyw     | loi 0x3f800000 (1)                           I
26b0  ADDi.z vf18.z, vf00.z, I                 | NOP                                          
26b8  ADDi.xyz vf13.xyz, vf00.xyz, I           | NOP                                          
26c0  SUB.xzw vf20.xzw, vf19.xzw, vf20.xzw     | NOP                                          
26c8  SUB.xzw vf21.xzw, vf19.xzw, vf21.xzw     | NOP                                          
26d0  SUB.xzw vf22.xzw, vf19.xzw, vf22.xzw     | NOP                                          
26d8  NOP                                      | LQI.xyzw vf05.xyzw, (vi06++)                 
26e0  NOP                                      | LQI.xyzw vf06.xyzw, (vi06++)                 
26e8  NOP                                      | LQI.xyzw vf07.xyzw, (vi06++)                 
26f0  NOP                                      | loi 0x3f000000 (0.5)                         I
26f8  MULAx.xyzw ACC, vf20.xyzw, vf05.x        | NOP                                          
2700  MADDAx.xyzw ACC, vf21.xyzw, vf06.x       | NOP                                          
2708  MADDx.xyzw vf01.xyzw, vf22.xyzw, vf07.x  | NOP                                          
2710  MULAy.xyzw ACC, vf20.xyzw, vf05.y        | NOP                                          
2718  MADDAy.xyzw ACC, vf21.xyzw, vf06.y       | NOP                                          
2720  MADDy.xyzw vf02.xyzw, vf22.xyzw, vf07.y  | NOP                                          
2728  MULAz.xyzw ACC, vf20.xyzw, vf05.z        | NOP                                          
2730  MADDAz.xyzw ACC, vf21.xyzw, vf06.z       | NOP                                          
2738  MADDz.xyzw vf03.xyzw, vf22.xyzw, vf07.z  | NOP                                          
2740  MULAw.xyzw ACC, vf20.xyzw, vf05.w        | NOP                                          
2748  MADDAw.xyzw ACC, vf21.xyzw, vf06.w       | NOP                                          
2750  MADDw.xyzw vf04.xyzw, vf22.xyzw, vf07.w  | NOP                                          
2758  ADD.xyzw vf05.xyzw, vf01.xyzw, vf18.xyzw | NOP                                          
2760  ADD.xyzw vf06.xyzw, vf02.xyzw, vf18.xyzw | NOP                                          
2768  ADD.xyzw vf07.xyzw, vf03.xyzw, vf18.xyzw | NOP                                          
2770  ADD.xyzw vf08.xyzw, vf04.xyzw, vf18.xyzw | NOP                                          
2778  MUL.xyzw vf05.xyzw, vf05.xyzw, vf05.xyzw | NOP                                          
2780  MUL.xyzw vf06.xyzw, vf06.xyzw, vf06.xyzw | NOP                                          
2788  MUL.xyzw vf07.xyzw, vf07.xyzw, vf07.xyzw | NOP                                          
2790  MUL.xyzw vf08.xyzw, vf08.xyzw, vf08.xyzw | NOP                                          
2798  ADDAy.x ACC, vf05.x, vf05.y              | NOP                                          
27a0  MADDz.x vf09.x, vf13.x, vf05.z           | NOP                                          
27a8  ADDAx.y ACC, vf06.y, vf06.x              | NOP                                          
27b0  MADDz.y vf09.y, vf13.y, vf06.z           | NOP                                          
27b8  ADDAx.z ACC, vf07.z, vf07.x              | NOP                                          
27c0  MADDy.z vf09.z, vf13.z, vf07.y           | NOP                                          
27c8  MULAz.w ACC, vf13.w, vf08.z              | NOP                                          
27d0  MADDAy.w ACC, vf13.w, vf08.y             | NOP                                          
27d8  MADDx.w vf09.w, vf13.w, vf08.x           | NOP                                          
27e0  NOP                                      | NOP                                          
27e8  NOP                                      | NOP                                          
27f0  NOP                                      | NOP                                          
27f8  ITOF0.xyzw vf09.xyzw, vf09.xyzw          | NOP                                          
2800  NOP                                      | NOP                                          
2808  NOP                                      | NOP                                          
2810  MULAy.xyzw ACC, vf13.xyzw, vf15.y        | NOP                                          
2818  MADDx.xyzw vf09.xyzw, vf09.xyzw, vf15.x  | NOP                                          
2820  NOP                                      | NOP                                          
2828  NOP                                      | NOP                                          
2830  NOP                                      | NOP                                          
2838  FTOI0.xyzw vf09.xyzw, vf09.xyzw          | NOP                                          
2840  NOP                                      | NOP                                          
2848  NOP                                      | NOP                                          
2850  NOP                                      | NOP                                          
2858  MULx.xyz vf05.xyz, vf01.xyz, vf09.x      | NOP                                          
2860  MULy.xyz vf06.xyz, vf02.xyz, vf09.y      | NOP                                          
2868  MULz.xyz vf07.xyz, vf03.xyz, vf09.z      | NOP                                          
2870  MULw.xyz vf08.xyz, vf04.xyz, vf09.w      | NOP                                          
2878  ADDAi.xy ACC, vf00.xy, I                 | NOP                                          
2880  MADDi.xy vf05.xy, vf05.xy, I             | NOP                                          
2888  MADDi.xy vf06.xy, vf06.xy, I             | NOP                                          
2890  MADDi.xy vf07.xy, vf07.xy, I             | NOP                                          
2898  MADDi.xy vf08.xy, vf08.xy, I             | LQI.xyzw vf10.xyzw, (vi08++)                 
28a0  NOP                                      | LQ.zw vf05.zw, 0(vi09)                       
28a8  NOP                                      | LQ.zw vf06.zw, 3(vi09)                       
28b0  NOP                                      | LQ.zw vf07.zw, 6(vi09)                       
28b8  NOP                                      | LQ.zw vf08.zw, 9(vi09)                       
28c0  MULz.xy vf05.xy, vf05.xy, vf05.z         | NOP                                          
28c8  ITOF0.xyzw vf10.xyzw, vf10.xyzw          | NOP                                          
28d0  MULAw.xyzw ACC, vf13.xyzw, vf17.w        | NOP                                          
28d8  NOP                                      | NOP                                          
28e0  NOP                                      | NOP                                          
28e8  MULz.xy vf06.xy, vf06.xy, vf06.z         | NOP                                          
28f0  MADDw.xyzw vf10.xyzw, vf10.xyzw, vf16.w  | SQ.xyzw vf05.xyzw, 0(vi10)                   
28f8  NOP                                      | NOP                                          
2900  NOP                                      | NOP                                          
2908  MULz.xy vf07.xy, vf07.xy, vf07.z         | NOP                                          
2910  FTOI0.xyzw vf10.xyzw, vf10.xyzw          | SQ.xyzw vf06.xyzw, 3(vi10)                   
2918  NOP                                      | NOP                                          
2920  NOP                                      | NOP                                          
2928  MULz.xy vf08.xy, vf08.xy, vf08.z         | NOP                                          
2930  MAXx.xyzw vf10.xyzw, vf10.xyzw, vf00.x   | SQ.xyzw vf07.xyzw, 6(vi10)                   
2938  NOP                                      | NOP                                          
2940  NOP                                      | NOP                                          
2948  NOP                                      | NOP                                          
2950  MINIw.xyzw vf10.xyzw, vf10.xyzw, vf00.w  | SQ.xyzw vf08.xyzw, 9(vi10)                   
2958  MULAw.xyzw ACC, vf16.xyzw, vf00.w        | NOP                                          
2960  MADDx.xyzw vf01.xyzw, vf17.xyzw, vf10.x  | NOP                                          
2968  MADDy.xyzw vf02.xyzw, vf17.xyzw, vf10.y  | NOP                                          
2970  MADDz.xyzw vf03.xyzw, vf17.xyzw, vf10.z  | NOP                                          
2978  MADDw.xyzw vf04.xyzw, vf17.xyzw, vf10.w  | NOP                                          
2980  MAXx.xyzw vf01.xyzw, vf01.xyzw, vf00.x   | LQ.xyzw vf05.xyzw, 2(vi09)                   
2988  MAXx.xyzw vf02.xyzw, vf02.xyzw, vf00.x   | LQ.xyzw vf06.xyzw, 5(vi09)                   
2990  MAXx.xyzw vf03.xyzw, vf03.xyzw, vf00.x   | LQ.xyzw vf07.xyzw, 8(vi09)                   
2998  MAXx.xyzw vf04.xyzw, vf04.xyzw, vf00.x   | LQ.xyzw vf08.xyzw, 11(vi09)                  
29a0  NOP                                      | loi 0x3ffeb852 (1.99)                        I
29a8  MINIi.xyzw vf01.xyzw, vf01.xyzw, I       | SQ.xyzw vf05.xyzw, 2(vi10)                   
29b0  MINIi.xyzw vf02.xyzw, vf02.xyzw, I       | SQ.xyzw vf06.xyzw, 5(vi10)                   
29b8  MINIi.xyzw vf03.xyzw, vf03.xyzw, I       | SQ.xyzw vf07.xyzw, 8(vi10)                   
29c0  MINIi.xyzw vf04.xyzw, vf04.xyzw, I       | SQ.xyzw vf08.xyzw, 11(vi10)                  
29c8  NOP                                      | loi 0x43000000 (128)                         I
29d0  MULi.xyzw vf01.xyzw, vf01.xyzw, I        | NOP                                          
29d8  MULi.xyzw vf02.xyzw, vf02.xyzw, I        | NOP                                          
29e0  MULi.xyzw vf03.xyzw, vf03.xyzw, I        | NOP                                          
29e8  MULi.xyzw vf04.xyzw, vf04.xyzw, I        | NOP                                          
29f0  FTOI0.xyzw vf01.xyzw, vf01.xyzw          | LQI.xyzw vf05.xyzw, (vi06++)                 
29f8  FTOI0.xyzw vf02.xyzw, vf02.xyzw          | LQI.xyzw vf06.xyzw, (vi06++)                 
2a00  FTOI0.xyzw vf03.xyzw, vf03.xyzw          | LQI.xyzw vf07.xyzw, (vi06++)                 
2a08  FTOI0.xyzw vf04.xyzw, vf04.xyzw          | loi 0x3f000000 (0.5)                         I
2a10  NOP                                      | SQ.xyzw vf01.xyzw, 1(vi10)                   
2a18  NOP                                      | SQ.xyzw vf02.xyzw, 4(vi10)                   
2a20  NOP                                      | SQ.xyzw vf03.xyzw, 7(vi10)                   
2a28  NOP                                      | SQ.xyzw vf04.xyzw, 10(vi10)                  
2a30  NOP                                      | IADDI vi09, vi09, 12                         
2a38  NOP                                      | IADDI vi10, vi10, 12                         
2a40  NOP                                      | IBGTZ vi11, 0x26f8                           
2a48  NOP                                      | IADDI vi11, vi11, -4                         
2a50  NOP                                      | JR vi15                                      
2a58  NOP                                      | NOP                                          
2a60  NOP                                      | LQ.yzw vf01.yzw, 616(vi00)                   
2a68  NOP                                      | ILW.x vi11, 0(vi12)                          
2a70  NOP                                      | IADDIU vi01, vi00, 16384                     
2a78  NOP                                      | IADD vi01, vi01, vi01                        
2a80  NOP                                      | IOR vi01, vi01, vi11                         
2a88  NOP                                      | MFIR.x vf01.x, vi01                          
2a90  NOP                                      | IADDIU vi09, vi00, 691                       
2a98  NOP                                      | IADDIU vi10, vi13, 1                         
2aa0  NOP                                      | IADDI vi04, vi00, -1                         
2aa8  NOP                                      | SQ.xyzw vf01.xyzw, 626(vi00)                 
2ab0  NOP                                      | IADDIU vi06, vi13, 1                         
2ab8  NOP                                      | FCSET vi01, 0x000000                         
2ac0  NOP                                      | LQI.xyzw vf01.xyzw, (vi09++)                 
2ac8  NOP                                      | IADDI vi11, vi11, -2                         
2ad0  NOP                                      | IADDI vi11, vi11, -4                         
2ad8  NOP                                      | NOP                                          
2ae0  MULA.xyzw ACC, vf26.xyzw, vf01.xyzw      | LQI.xyzw vf02.xyzw, (vi09++)                 
2ae8  MADDw.xyzw vf01.xyzw, vf27.xyzw, vf01.w  | NOP                                          
2af0  NOP                                      | NOP                                          
2af8  NOP                                      | NOP                                          
2b00  NOP                                      | NOP                                          
2b08  CLIPw.xyz vf01.xyz, vf01.w               | NOP                                          
2b10  MULA.xyzw ACC, vf26.xyzw, vf02.xyzw      | LQI.xyzw vf03.xyzw, (vi09++)                 
2b18  MADDw.xyzw vf02.xyzw, vf27.xyzw, vf02.w  | ILW.w vi02, 2(vi10)                          
2b20  NOP                                      | NOP                                          
2b28  NOP                                      | NOP                                          
2b30  NOP                                      | NOP                                          
2b38  CLIPw.xyz vf02.xyz, vf02.w               | NOP                                          
2b40  MULA.xyzw ACC, vf26.xyzw, vf03.xyzw      | LQI.xyzw vf04.xyzw, (vi09++)                 
2b48  MADDw.xyzw vf03.xyzw, vf27.xyzw, vf03.w  | ILW.w vi03, 5(vi10)                          
2b50  NOP                                      | NOP                                          
2b58  NOP                                      | NOP                                          
2b60  NOP                                      | NOP                                          
2b68  CLIPw.xyz vf03.xyz, vf03.w               | NOP                                          
2b70  MULA.xyzw ACC, vf26.xyzw, vf04.xyzw      | LQI.xyzw vf01.xyzw, (vi09++)                 
2b78  MADDw.xyzw vf04.xyzw, vf27.xyzw, vf04.w  | ILW.w vi02, 8(vi10)                          
2b80  NOP                                      | NOP                                          
2b88  NOP                                      | FCAND vi01, 0x03ffff                         
2b90  NOP                                      | IADDI vi01, vi01, -1                         
2b98  CLIPw.xyz vf04.xyz, vf04.w               | IOR vi01, vi01, vi02                         
2ba0  MULA.xyzw ACC, vf26.xyzw, vf01.xyzw      | ILW.w vi03, 11(vi10)                         
2ba8  MADDw.xyzw vf01.xyzw, vf27.xyzw, vf01.w  | IBLTZ vi01, 0x2bd0                           
2bb0  NOP                                      | LQI.xyzw vf02.xyzw, (vi09++)                 
2bb8  NOP                                      | ISW.w vi04, 8(vi10)                          
2bc0  NOP                                      | ISW.w vi09, 0(vi06)                          
2bc8  NOP                                      | IADDI vi06, vi06, 3                          
2bd0  NOP                                      | FCAND vi01, 0x03ffff                         
2bd8  NOP                                      | IADDI vi01, vi01, -1                         
2be0  CLIPw.xyz vf01.xyz, vf01.w               | IOR vi01, vi01, vi03                         
2be8  MULA.xyzw ACC, vf26.xyzw, vf02.xyzw      | ILW.w vi02, 14(vi10)                         
2bf0  MADDw.xyzw vf02.xyzw, vf27.xyzw, vf02.w  | IBLTZ vi01, 0x2c18                           
2bf8  NOP                                      | LQI.xyzw vf03.xyzw, (vi09++)                 
2c00  NOP                                      | ISW.w vi04, 11(vi10)                         
2c08  NOP                                      | ISW.w vi09, 0(vi06)                          
2c10  NOP                                      | IADDI vi06, vi06, 3                          
2c18  NOP                                      | FCAND vi01, 0x03ffff                         
2c20  NOP                                      | IADDI vi01, vi01, -1                         
2c28  CLIPw.xyz vf02.xyz, vf02.w               | IOR vi01, vi01, vi02                         
2c30  MULA.xyzw ACC, vf26.xyzw, vf03.xyzw      | ILW.w vi03, 17(vi10)                         
2c38  MADDw.xyzw vf03.xyzw, vf27.xyzw, vf03.w  | IBLTZ vi01, 0x2c60                           
2c40  NOP                                      | LQI.xyzw vf04.xyzw, (vi09++)                 
2c48  NOP                                      | ISW.w vi04, 14(vi10)                         
2c50  NOP                                      | ISW.w vi09, 0(vi06)                          
2c58  NOP                                      | IADDI vi06, vi06, 3                          
2c60  NOP                                      | FCAND vi01, 0x03ffff                         
2c68  NOP                                      | IADDI vi01, vi01, -1                         
2c70  CLIPw.xyz vf03.xyz, vf03.w               | IOR vi01, vi01, vi03                         
2c78  MULA.xyzw ACC, vf26.xyzw, vf04.xyzw      | ILW.w vi02, 20(vi10)                         
2c80  MADDw.xyzw vf04.xyzw, vf27.xyzw, vf04.w  | IBLTZ vi01, 0x2ca8                           
2c88  NOP                                      | LQI.xyzw vf01.xyzw, (vi09++)                 
2c90  NOP                                      | ISW.w vi04, 17(vi10)                         
2c98  NOP                                      | ISW.w vi09, 0(vi06)                          
2ca0  NOP                                      | IADDI vi06, vi06, 3                          
2ca8  NOP                                      | IADDIU vi10, vi10, 12                        
2cb0  NOP                                      | IBGTZ vi11, 0x2b88                           
2cb8  NOP                                      | IADDI vi11, vi11, -4                         
2cc0  NOP                                      | IADDIU vi01, vi00, 8191                      
2cc8  NOP                                      | ISW.w vi01, 0(vi06)                          
2cd0  NOP                                      | JR vi15                                      
2cd8  NOP                                      | NOP                                          
2ce0  NOP                                      | IADDIU vi01, vi00, 512                       
2ce8  NOP                                      | IAND vi01, vi07, vi01                        
2cf0  NOP                                      | NOP                                          
2cf8  NOP                                      | IBNE vi01, vi00, 0x2d18                      
2d00  NOP                                      | NOP                                          
2d08  NOP                                      | JR vi15                                      
2d10  NOP                                      | NOP                                          
2d18  NOP                                      | ILW.x vi11, 0(vi12)                          
2d20  NOP                                      | IADDIU vi06, vi13, 1                         
2d28  NOP                                      | IADDIU vi01, vi00, 691                       
2d30  NOP                                      | IADDI vi01, vi01, 3                          
2d38  NOP                                      | IADD vi11, vi01, vi11                        
2d40  NOP                                      | ILW.w vi08, 0(vi06)                          
2d48  NOP                                      | NOP                                          
2d50  NOP                                      | NOP                                          
2d58  NOP                                      | NOP                                          
2d60  NOP                                      | ISUB vi01, vi11, vi08                        
2d68  NOP                                      | NOP                                          
2d70  NOP                                      | IBLTZ vi01, 0x2e60                           
2d78  NOP                                      | NOP                                          
2d80  NOP                                      | LQ.xyzw vf01.xyzw, -6(vi08)                  
2d88  NOP                                      | LQ.xyzw vf02.xyzw, -5(vi08)                  
2d90  NOP                                      | LQ.xyzw vf03.xyzw, -4(vi08)                  
2d98  NOP                                      | ISUBIU vi08, vi08, 694                       
2da0  MULA.xyzw ACC, vf26.xyzw, vf01.xyzw      | IADD vi01, vi08, vi08                        
2da8  MADDw.xyzw vf16.xyzw, vf27.xyzw, vf01.w  | IADD vi08, vi08, vi01                        
2db0  MULA.xyzw ACC, vf26.xyzw, vf02.xyzw      | IADD vi08, vi08, vi13                        
2db8  MADDw.xyzw vf17.xyzw, vf27.xyzw, vf02.w  | IADDI vi08, vi08, 1                          
2dc0  MULA.xyzw ACC, vf26.xyzw, vf03.xyzw      | NOP                                          
2dc8  MADDw.xyzw vf18.xyzw, vf27.xyzw, vf03.w  | NOP                                          
2dd0  NOP                                      | NOP                                          
2dd8  CLIPw.xyz vf16.xyz, vf16.w               | NOP                                          
2de0  CLIPw.xyz vf17.xyz, vf17.w               | NOP                                          
2de8  CLIPw.xyz vf18.xyz, vf18.w               | NOP                                          
2df0  NOP                                      | IADDIU vi04, vi00, 63                        
2df8  NOP                                      | FCGET vi01                                   
2e00  NOP                                      | FCGET vi02                                   
2e08  NOP                                      | FCGET vi03                                   
2e10  NOP                                      | IAND vi01, vi01, vi04                        
2e18  NOP                                      | IAND vi02, vi02, vi04                        
2e20  NOP                                      | IAND vi03, vi03, vi04                        
2e28  NOP                                      | IAND vi04, vi01, vi02                        
2e30  NOP                                      | IAND vi04, vi04, vi03                        
2e38  NOP                                      | IOR vi09, vi01, vi02                         
2e40  NOP                                      | IBEQ vi04, vi00, 0x2e80                      
2e48  NOP                                      | IOR vi09, vi09, vi03                         
2e50  NOP                                      | B 0x2d40                                     
2e58  NOP                                      | IADDI vi06, vi06, 3                          
2e60  NOP                                      | IADDIU vi01, vi00, 623                       
2e68  NOP                                      | XGKICK vi01                                  
2e70  NOP                                      | JR vi15                                      
2e78  NOP                                      | NOP                                          
2e80  NOP                                      | ISW.x vi06, 627(vi00)                        
2e88  NOP                                      | ISW.y vi11, 627(vi00)                        
2e90  NOP                                      | ISW.z vi00, 627(vi00)                        
2e98  NOP                                      | ISW.w vi00, 627(vi00)                        
2ea0  NOP                                      | ISW.x vi13, 628(vi00)                        
2ea8  NOP                                      | ISW.y vi14, 628(vi00)                        
2eb0  NOP                                      | ISW.z vi07, 628(vi00)                        
2eb8  NOP                                      | ISW.w vi15, 628(vi00)                        
2ec0  NOP                                      | ISW.w vi08, 629(vi00)                        
2ec8  SUB.xyzw vf01.xyzw, vf01.xyzw, vf01.xyzw | IADDIU vi13, vi00, 913                       
2ed0  SUB.xyzw vf02.xyzw, vf02.xyzw, vf02.xyzw | IADDIU vi14, vi13, 945                       
2ed8  SUB.xyzw vf03.xyzw, vf03.xyzw, vf03.xyzw | IADDIU vi11, vi00, 3                         
2ee0  NOP                                      | IADD vi07, vi00, vi09                        
2ee8  SUB.xyzw vf14.xyzw, vf00.xyzw, vf00.xyzw | loi 0x3f800000 (1)                           I
2ef0  ADDi.x vf01.x, vf01.x, I                 | NOP                                          
2ef8  ADDi.y vf02.y, vf02.y, I                 | NOP                                          
2f00  ADDi.z vf03.z, vf03.z, I                 | NOP                                          
2f08  NOP                                      | SQ.xyzw vf16.xyzw, 0(vi13)                   
2f10  NOP                                      | SQ.xyzw vf17.xyzw, 1(vi13)                   
2f18  NOP                                      | SQ.xyzw vf18.xyzw, 2(vi13)                   
2f20  NOP                                      | ISW.w vi01, 10(vi13)                         
2f28  NOP                                      | ISW.w vi02, 11(vi13)                         
2f30  NOP                                      | ISW.w vi03, 12(vi13)                         
2f38  NOP                                      | SQ.xyz vf01.xyz, 10(vi13)                    
2f40  NOP                                      | SQ.xyz vf02.xyz, 11(vi13)                    
2f48  NOP                                      | SQ.xyz vf03.xyz, 12(vi13)                    
2f50  NOP                                      | IADDIU vi08, vi00, 32                        
2f58  NOP                                      | BAL vi15, 0x3438                             
2f60  NOP                                      | IADDIU vi05, vi00, 1667                      
2f68  NOP                                      | IADDIU vi08, vi00, 16                        
2f70  NOP                                      | BAL vi15, 0x3438                             
2f78  NOP                                      | IADDIU vi05, vi00, 1669                      
2f80  NOP                                      | IADDIU vi08, vi00, 2                         
2f88  NOP                                      | BAL vi15, 0x3438                             
2f90  NOP                                      | IADDIU vi05, vi00, 1659                      
2f98  NOP                                      | IADDIU vi08, vi00, 1                         
2fa0  NOP                                      | BAL vi15, 0x3438                             
2fa8  NOP                                      | IADDIU vi05, vi00, 1661                      
2fb0  NOP                                      | IADDIU vi08, vi00, 8                         
2fb8  NOP                                      | BAL vi15, 0x3438                             
2fc0  NOP                                      | IADDIU vi05, vi00, 1663                      
2fc8  NOP                                      | IADDIU vi08, vi00, 4                         
2fd0  NOP                                      | BAL vi15, 0x3438                             
2fd8  NOP                                      | IADDIU vi05, vi00, 1665                      
2fe0  NOP                                      | IBEQ vi11, vi00, 0x3388                      
2fe8  NOP                                      | IADD vi02, vi00, vi11                        
2ff0  NOP                                      | NOP                                          
2ff8  NOP                                      | IADDIU vi01, vi00, 623                       
3000  NOP                                      | XGKICK vi01                                  
3008  NOP                                      | LQ.yzw vf01.yzw, 626(vi00)                   
3010  NOP                                      | IADD vi09, vi00, vi13                        
3018  NOP                                      | IADDIU vi10, vi00, 977                       
3020  NOP                                      | IADDIU vi01, vi00, 16384                     
3028  NOP                                      | IADD vi01, vi01, vi01                        
3030  NOP                                      | IOR vi01, vi01, vi11                         
3038  NOP                                      | MFIR.x vf01.x, vi01                          
3040  NOP                                      | IADDIU vi09, vi09, 10                        
3048  NOP                                      | IADDI vi11, vi11, -1                         
3050  NOP                                      | IADDI vi10, vi10, 1                          
3058  NOP                                      | SQ.xyzw vf01.xyzw, -1(vi10)                  
3060  NOP                                      | ILW.w vi08, 629(vi00)                        
3068  ADD.z vf15.z, vf00.z, vf00.z             | loi 0x49000000 (524288)                      I
3070  ADDi.xy vf15.xy, vf00.xy, I              | LQ.xyzw vf11.xyzw, -9(vi08)                  
3078  SUB.xyzw vf04.xyzw, vf04.xyzw, vf04.xyzw | LQ.xyzw vf08.xyzw, -8(vi08)                  
3080  NOP                                      | LQ.xyzw vf09.xyzw, -5(vi08)                  
3088  NOP                                      | LQ.xyzw vf10.xyzw, -2(vi08)                  
3090  NOP                                      | LQ.xyzw vf12.xyzw, -6(vi08)                  
3098  NOP                                      | LQ.xyzw vf13.xyzw, -3(vi08)                  
30a0  ITOF0.xyzw vf08.xyzw, vf08.xyzw          | DIV Q, vf00.w, vf11.z                        
30a8  ITOF0.xyzw vf09.xyzw, vf09.xyzw          | NOP                                          
30b0  ITOF0.xyzw vf10.xyzw, vf10.xyzw          | NOP                                          
30b8  NOP                                      | loi 0x3f000000 (0.5)                         I
30c0  ADDi.xyzw vf08.xyzw, vf08.xyzw, I        | NOP                                          
30c8  ADDi.xyzw vf09.xyzw, vf09.xyzw, I        | NOP                                          
30d0  ADDi.xyzw vf10.xyzw, vf10.xyzw, I        | NOP                                          
30d8  MULq.xy vf11.xy, vf11.xy, Q              | WAITQ                                        
30e0  NOP                                      | DIV Q, vf00.w, vf12.z                        
30e8  MULq.xy vf12.xy, vf12.xy, Q              | WAITQ                                        
30f0  NOP                                      | DIV Q, vf00.w, vf13.z                        
30f8  MULq.xy vf13.xy, vf13.xy, Q              | WAITQ                                        
3100  NOP                                      | IADDIU vi08, vi00, 580                       
3108  NOP                                      | LQ.xyzw vf03.xyzw, -10(vi09)                 
3110  NOP                                      | LQI.xyzw vf05.xyzw, (vi09++)                 
3118  NOP                                      | MR32.xyzw vf01.xyzw, vf00.xyzw               
3120  NOP                                      | NOP                                          
3128  NOP                                      | SQI.xyzw vf03.xyzw, (vi08++)                 
3130  MULA.xyzw ACC, vf24.xyzw, vf03.xyzw      | NOP                                          
3138  MADDw.xyzw vf03.xyzw, vf25.xyzw, vf03.w  | NOP                                          
3140  MULAx.xyzw ACC, vf08.xyzw, vf05.x        | NOP                                          
3148  MADDAy.xyzw ACC, vf09.xyzw, vf05.y       | NOP                                          
3150  MADDz.xyzw vf02.xyzw, vf10.xyzw, vf05.z  | NOP                                          
3158  MULAx.xyzw ACC, vf11.xyzw, vf05.x        | DIV Q, vf00.w, vf03.w                        
3160  MADDAy.xyzw ACC, vf12.xyzw, vf05.y       | NOP                                          
3168  MADDz.xy vf01.xy, vf13.xy, vf05.z        | NOP                                          
3170  FTOI0.xyzw vf02.xyzw, vf02.xyzw          | NOP                                          
3178  NOP                                      | NOP                                          
3180  NOP                                      | NOP                                          
3188  ADDA.xyz ACC, vf00.xyz, vf15.xyz         | NOP                                          
3190  MULq.xyz vf01.xyz, vf01.xyz, Q           | NOP                                          
3198  MADDq.xyz vf04.xyz, vf03.xyz, Q          | NOP                                          
31a0  NOP                                      | NOP                                          
31a8  NOP                                      | SQI.xyzw vf01.xyzw, (vi10++)                 
31b0  NOP                                      | SQI.xyzw vf02.xyzw, (vi10++)                 
31b8  NOP                                      | SQI.xyzw vf04.xyzw, (vi10++)                 
31c0  NOP                                      | IBGTZ vi11, 0x3108                           
31c8  NOP                                      | IADDI vi11, vi11, -1                         
31d0  NOP                                      | IADDIU vi01, vi00, 977                       
31d8  NOP                                      | IADDIU vi03, vi00, 8                         
31e0  NOP                                      | ILW.z vi07, 628(vi00)                        
31e8  NOP                                      | IAND vi03, vi07, vi03                        
31f0  NOP                                      | NOP                                          
31f8  NOP                                      | IBEQ vi03, vi00, 0x3290                      
3200  NOP                                      | NOP                                          
3208  NOP                                      | LQ.xy vf04.xy, 689(vi00)                     
3210  NOP                                      | loi 0x3b000000 (0.00195312)                  I
3218  ADDi.x vf05.x, vf00.x, I                 | ISUB vi10, vi10, vi02                        
3220  ADDi.y vf05.y, vf00.y, I                 | ISUB vi10, vi10, vi02                        
3228  NOP                                      | ISUB vi10, vi10, vi02                        
3230  NOP                                      | LQ.xy vf01.xy, 2(vi10)                       
3238  NOP                                      | loi 0xc9000000 (-524288)                     I
3240  NOP                                      | MR32.z vf02.z, vf00.z                        
3248  MULA.xy ACC, vf01.xy, vf05.xy            | NOP                                          
3250  MADDAi.xy ACC, vf05.xy, I                | LQ.xy vf01.xy, 5(vi10)                       
3258  MSUB.xy vf02.xy, vf05.xy, vf04.xy        | IADDI vi10, vi10, 3                          
3260  NOP                                      | IADDI vi02, vi02, -1                         
3268  NOP                                      | NOP                                          
3270  NOP                                      | IBGEZ vi02, 0x3248                           
3278  NOP                                      | SQ.xyz vf02.xyz, -3(vi10)                    
3280  NOP                                      | B 0x3380                                     
3288  NOP                                      | NOP                                          
3290  NOP                                      | IADDIU vi08, vi00, 580                       
3298  NOP                                      | IADDIU vi03, vi00, 16                        
32a0  NOP                                      | ILW.z vi07, 599(vi00)                        
32a8  NOP                                      | IAND vi03, vi07, vi03                        
32b0  NOP                                      | NOP                                          
32b8  NOP                                      | IBEQ vi03, vi00, 0x3380                      
32c0  NOP                                      | NOP                                          
32c8  NOP                                      | ISUB vi10, vi10, vi02                        
32d0  NOP                                      | ISUB vi10, vi10, vi02                        
32d8  NOP                                      | ISUB vi10, vi10, vi02                        
32e0  NOP                                      | LQ.xyzw vf01.xyzw, 595(vi00)                 
32e8  NOP                                      | LQ.xyzw vf02.xyzw, 596(vi00)                 
32f0  NOP                                      | LQ.xyzw vf03.xyzw, 597(vi00)                 
32f8  NOP                                      | LQ.xyzw vf04.xyzw, 598(vi00)                 
3300  NOP                                      | LQI.xyzw vf09.xyzw, (vi08++)                 
3308  MULAw.xyzw ACC, vf04.xyzw, vf09.w        | LQ.z vf10.z, 0(vi10)                         
3310  MADDAx.xyzw ACC, vf01.xyzw, vf09.x       | NOP                                          
3318  MADDAy.xyzw ACC, vf02.xyzw, vf09.y       | NOP                                          
3320  MADDz.xyzw vf09.xyzw, vf03.xyzw, vf09.z  | NOP                                          
3328  MULz.xyz vf09.xyz, vf09.xyz, vf10.z      | NOP                                          
3330  NOP                                      | NOP                                          
3338  NOP                                      | NOP                                          
3340  NOP                                      | NOP                                          
3348  NOP                                      | SQ.xyz vf09.xyz, 0(vi10)                     
3350  NOP                                      | loi 0x43000000 (128)                         I
3358  NOP                                      | IADDI vi10, vi10, 3                          
3360  NOP                                      | IADDI vi02, vi02, -1                         
3368  NOP                                      | NOP                                          
3370  NOP                                      | IBGEZ vi02, 0x3300                           
3378  NOP                                      | NOP                                          
3380  NOP                                      | XGKICK vi01                                  
3388  NOP                                      | ILW.x vi13, 628(vi00)                        
3390  NOP                                      | ILW.y vi14, 628(vi00)                        
3398  NOP                                      | ILW.z vi07, 628(vi00)                        
33a0  NOP                                      | ILW.w vi15, 628(vi00)                        
33a8  NOP                                      | ILW.x vi06, 627(vi00)                        
33b0  NOP                                      | ILW.y vi11, 627(vi00)                        
33b8  NOP                                      | ILW.z vi00, 627(vi00)                        
33c0  NOP                                      | ILW.w vi00, 627(vi00)                        
33c8  NOP                                      | B 0x2e50                                     
33d0  NOP                                      | NOP                                          
33d8  ADDx.w vf05.w, vf01.w, vf01.x            | JR vi15                                      
33e0  ADDx.w vf06.w, vf02.w, vf02.x            | NOP                                          
33e8  SUBx.w vf05.w, vf01.w, vf01.x            | JR vi15                                      
33f0  SUBx.w vf06.w, vf02.w, vf02.x            | NOP                                          
33f8  ADDy.w vf05.w, vf01.w, vf01.y            | JR vi15                                      
3400  ADDy.w vf06.w, vf02.w, vf02.y            | NOP                                          
3408  SUBy.w vf05.w, vf01.w, vf01.y            | JR vi15                                      
3410  SUBy.w vf06.w, vf02.w, vf02.y            | NOP                                          
3418  ADDz.w vf05.w, vf01.w, vf01.z            | JR vi15                                      
3420  ADDz.w vf06.w, vf02.w, vf02.z            | NOP                                          
3428  SUBz.w vf05.w, vf01.w, vf01.z            | JR vi15                                      
3430  SUBz.w vf06.w, vf02.w, vf02.z            | NOP                                          
3438  NOP                                      | IAND vi01, vi07, vi08                        
3440  NOP                                      | ISW.x vi15, 629(vi00)                        
3448  NOP                                      | IBEQ vi01, vi00, 0x3588                      
3450  NOP                                      | NOP                                          
3458  NOP                                      | LQ.xyzw vf01.xyzw, 0(vi13)                   
3460  NOP                                      | LQ.xyzw vf02.xyzw, 10(vi13)                  
3468  NOP                                      | IADD vi01, vi13, vi11                        
3470  NOP                                      | SQ.xyzw vf01.xyzw, 0(vi01)                   
3478  NOP                                      | SQ.xyzw vf02.xyzw, 10(vi01)                  
3480  NOP                                      | IADD vi09, vi00, vi13                        
3488  NOP                                      | ISUB vi13, vi14, vi13                        
3490  NOP                                      | IADD vi10, vi00, vi13                        
3498  NOP                                      | IADDI vi06, vi11, -1                         
34a0  NOP                                      | IADDIU vi11, vi00, 0                         
34a8  NOP                                      | LQ.xyzw vf01.xyzw, 0(vi09)                   
34b0  NOP                                      | LQ.xyzw vf02.xyzw, 1(vi09)                   
34b8  NOP                                      | ILW.w vi01, 10(vi09)                         
34c0  NOP                                      | ILW.w vi02, 11(vi09)                         
34c8  NOP                                      | LQ.xyz vf03.xyz, 10(vi09)                    
34d0  NOP                                      | LQ.xyz vf04.xyz, 11(vi09)                    
34d8  NOP                                      | JALR vi15, vi05                              
34e0  NOP                                      | NOP                                          
34e8  NOP                                      | IAND vi03, vi01, vi08                        
34f0  NOP                                      | IAND vi04, vi02, vi08                        
34f8  NOP                                      | IBEQ vi03, vi00, 0x3528                      
3500  NOP                                      | NOP                                          
3508  NOP                                      | IBEQ vi04, vi00, 0x35d8                      
3510  NOP                                      | NOP                                          
3518  NOP                                      | B 0x3598                                     
3520  NOP                                      | NOP                                          
3528  NOP                                      | IBEQ vi04, vi00, 0x35a8                      
3530  NOP                                      | NOP                                          
3538  NOP                                      | B 0x36a8                                     
3540  NOP                                      | NOP                                          
3548  NOP                                      | IBNE vi06, vi00, 0x34a8                      
3550  NOP                                      | IADDI vi06, vi06, -1                         
3558  NOP                                      | IBEQ vi11, vi00, 0x3388                      
3560  NOP                                      | NOP                                          
3568  NOP                                      | ILW.x vi15, 629(vi00)                        
3570  NOP                                      | NOP                                          
3578  NOP                                      | NOP                                          
3580  NOP                                      | NOP                                          
3588  NOP                                      | JR vi15                                      
3590  NOP                                      | NOP                                          
3598  NOP                                      | B 0x3548                                     
35a0  NOP                                      | IADDI vi09, vi09, 1                          
35a8  NOP                                      | ISW.w vi02, 10(vi10)                         
35b0  NOP                                      | SQ.xyz vf04.xyz, 10(vi10)                    
35b8  NOP                                      | SQI.xyzw vf02.xyzw, (vi10++)                 
35c0  NOP                                      | IADDI vi09, vi09, 1                          
35c8  NOP                                      | B 0x3548                                     
35d0  NOP                                      | IADDI vi11, vi11, 1                          
35d8  SUB.w vf08.w, vf06.w, vf05.w             | FCSET vi01, 0x000000                         
35e0  SUB.xyzw vf09.xyzw, vf01.xyzw, vf02.xyzw | IADDI vi09, vi09, 1                          
35e8  SUB.xyzw vf10.xyzw, vf03.xyzw, vf04.xyzw | IADDI vi11, vi11, 2                          
35f0  NOP                                      | NOP                                          
35f8  NOP                                      | DIV Q, vf06.w, vf08.w                        
3600  NOP                                      | NOP                                          
3608  NOP                                      | NOP                                          
3610  NOP                                      | NOP                                          
3618  NOP                                      | NOP                                          
3620  NOP                                      | NOP                                          
3628  ADDA.xyzw ACC, vf14.xyzw, vf02.xyzw      | NOP                                          
3630  MADDq.xyzw vf11.xyzw, vf09.xyzw, Q       | NOP                                          
3638  ADDA.xyzw ACC, vf14.xyzw, vf04.xyzw      | NOP                                          
3640  MADDq.xyzw vf12.xyzw, vf10.xyzw, Q       | NOP                                          
3648  NOP                                      | NOP                                          
3650  CLIPw.xyz vf11.xyz, vf11.w               | NOP                                          
3658  NOP                                      | NOP                                          
3660  NOP                                      | SQ.xyz vf12.xyz, 10(vi10)                    
3668  NOP                                      | SQ.xyz vf04.xyz, 11(vi10)                    
3670  NOP                                      | FCGET vi03                                   
3678  NOP                                      | ISW.w vi03, 10(vi10)                         
3680  NOP                                      | ISW.w vi02, 11(vi10)                         
3688  NOP                                      | SQI.xyzw vf11.xyzw, (vi10++)                 
3690  NOP                                      | SQI.xyzw vf02.xyzw, (vi10++)                 
3698  NOP                                      | B 0x3548                                     
36a0  NOP                                      | IOR vi07, vi07, vi03                         
36a8  SUB.w vf08.w, vf05.w, vf06.w             | FCSET vi01, 0x000000                         
36b0  SUB.xyzw vf09.xyzw, vf02.xyzw, vf01.xyzw | IADDI vi09, vi09, 1                          
36b8  SUB.xyzw vf10.xyzw, vf04.xyzw, vf03.xyzw | IADDI vi11, vi11, 1                          
36c0  NOP                                      | NOP                                          
36c8  NOP                                      | DIV Q, vf05.w, vf08.w                        
36d0  NOP                                      | NOP                                          
36d8  NOP                                      | NOP                                          
36e0  NOP                                      | NOP                                          
36e8  NOP                                      | NOP                                          
36f0  NOP                                      | NOP                                          
36f8  ADDA.xyzw ACC, vf14.xyzw, vf01.xyzw      | NOP                                          
3700  MADDq.xyzw vf11.xyzw, vf09.xyzw, Q       | NOP                                          
3708  ADDA.xyzw ACC, vf14.xyzw, vf03.xyzw      | NOP                                          
3710  MADDq.xyzw vf12.xyzw, vf10.xyzw, Q       | NOP                                          
3718  NOP                                      | NOP                                          
3720  CLIPw.xyz vf11.xyz, vf11.w               | NOP                                          
3728  NOP                                      | NOP                                          
3730  NOP                                      | NOP                                          
3738  NOP                                      | SQ.xyz vf12.xyz, 10(vi10)                    
3740  NOP                                      | FCGET vi03                                   
3748  NOP                                      | ISW.w vi03, 10(vi10)                         
3750  NOP                                      | SQI.xyzw vf11.xyzw, (vi10++)                 
3758  NOP                                      | B 0x3548                                     
3760  NOP                                      | IOR vi07, vi07, vi03                         
3768  NOP                                      | B 0x3768                                     
3770  NOP                                      | NOP                                          
3778  NOP                                      | IADDIU vi05, vi00, 255                       
3780  NOP                                      | ILW.x vi01, 0(vi12)                          
3788  NOP                                      | IADDIU vi09, vi12, 5                         
3790  NOP                                      | IADDIU vi06, vi12, 29                        
3798  NOP                                      | IADDIU vi08, vi12, 77                        
37a0  NOP                                      | SQ.xyzw vf24.xyzw, 903(vi00)                 
37a8  NOP                                      | SQ.xyzw vf25.xyzw, 904(vi00)                 
37b0  NOP                                      | SQ.xyzw vf26.xyzw, 905(vi00)                 
37b8  NOP                                      | SQ.xyzw vf28.xyzw, 907(vi00)                 
37c0  NOP                                      | SQ.xyzw vf29.xyzw, 908(vi00)                 
37c8  NOP                                      | SQ.xyzw vf30.xyzw, 909(vi00)                 
37d0  NOP                                      | SQ.xyzw vf31.xyzw, 910(vi00)                 
37d8  SUB.xyzw vf25.xyzw, vf25.xyzw, vf25.xyzw | NOP                                          
37e0  SUB.xyzw vf26.xyzw, vf26.xyzw, vf26.xyzw | loi 0x7f7fffff (3.40282e+38)                 I
37e8  ADDi.xyzw vf25.xyzw, vf25.xyzw, I        | loi 0xff7fffff (-3.40282e+38)                I
37f0  ADDi.xyzw vf26.xyzw, vf26.xyzw, I        | loi 0x3b80807f (0.00392157)                  I
37f8  NOP                                      | LQI.xyzw vf01.xyzw, (vi09++)                 
3800  NOP                                      | LQI.xyzw vf02.xyzw, (vi09++)                 
3808  NOP                                      | LQI.xyzw vf03.xyzw, (vi09++)                 
3810  NOP                                      | ILWR.x vi10, (vi06)                          
3818  NOP                                      | ILWR.y vi11, (vi06)                          
3820  NOP                                      | ILW.x vi04, -1(vi09)                         
3828  NOP                                      | ILW.x vi03, -2(vi09)                         
3830  NOP                                      | ILW.x vi02, -3(vi09)                         
3838  NOP                                      | IAND vi10, vi10, vi05                        
3840  NOP                                      | IAND vi11, vi11, vi05                        
3848  NOP                                      | LQI.xyzw vf28.xyzw, (vi08++)                 
3850  NOP                                      | LQI.xyzw vf29.xyzw, (vi08++)                 
3858  NOP                                      | LQI.xyzw vf30.xyzw, (vi08++)                 
3860  NOP                                      | MFIR.x vf24.x, vi10                          
3868  NOP                                      | MFIR.y vf24.y, vi11                          
3870  ITOF0.xyzw vf28.xyzw, vf28.xyzw          | ISUB vi10, vi00, vi10                        
3878  ITOF0.xyzw vf29.xyzw, vf29.xyzw          | ISUB vi10, vi10, vi11                        
3880  ITOF0.xyzw vf30.xyzw, vf30.xyzw          | IADDIU vi10, vi10, 255                       
3888  NOP                                      | MFIR.z vf24.z, vi10                          
3890  NOP                                      | IAND vi03, vi03, vi05                        
3898  NOP                                      | IAND vi02, vi02, vi05                        
38a0  NOP                                      | IAND vi04, vi04, vi05                        
38a8  NOP                                      | loi 0x3b80807f (0.00392157)                  I
38b0  NOP                                      | IADDIU vi02, vi02, 440                       
38b8  NOP                                      | IADDIU vi03, vi03, 440                       
38c0  ITOF0.xyz vf24.xyz, vf24.xyz             | IADDIU vi04, vi04, 440                       
38c8  NOP                                      | LQ.xyzw vf04.xyzw, 0(vi02)                   
38d0  NOP                                      | LQ.xyzw vf05.xyzw, 1(vi02)                   
38d8  NOP                                      | LQ.xyzw vf06.xyzw, 2(vi02)                   
38e0  MULi.xyz vf24.xyz, vf24.xyz, I           | LQ.xyzw vf07.xyzw, 3(vi02)                   
38e8  MULAx.xyzw ACC, vf04.xyzw, vf01.x        | LQ.xyzw vf08.xyzw, 0(vi03)                   
38f0  MADDAx.xyzw ACC, vf05.xyzw, vf02.x       | LQ.xyzw vf09.xyzw, 1(vi03)                   
38f8  MADDAx.xyzw ACC, vf06.xyzw, vf03.x       | LQ.xyzw vf10.xyzw, 2(vi03)                   
3900  MADDw.xyzw vf16.xyzw, vf07.xyzw, vf00.w  | LQ.xyzw vf11.xyzw, 3(vi03)                   
3908  MULAx.xyzw ACC, vf08.xyzw, vf01.x        | LQ.xyzw vf12.xyzw, 0(vi04)                   
3910  MADDAx.xyzw ACC, vf09.xyzw, vf02.x       | LQ.xyzw vf13.xyzw, 1(vi04)                   
3918  MADDAx.xyzw ACC, vf10.xyzw, vf03.x       | LQ.xyzw vf14.xyzw, 2(vi04)                   
3920  MADDw.xyzw vf17.xyzw, vf11.xyzw, vf00.w  | LQ.xyzw vf15.xyzw, 3(vi04)                   
3928  MULAx.xyzw ACC, vf12.xyzw, vf01.x        | ILWR.w vi10, (vi06)                          
3930  MADDAx.xyzw ACC, vf13.xyzw, vf02.x       | ILWR.z vi11, (vi06)                          
3938  MADDAx.xyzw ACC, vf14.xyzw, vf03.x       | IADDI vi06, vi06, 1                          
3940  MADDw.xyzw vf18.xyzw, vf15.xyzw, vf00.w  | ILW.y vi04, -1(vi09)                         
3948  MULAx.xyzw ACC, vf04.xyzw, vf28.x        | IADDI vi01, vi01, -1                         
3950  MADDAx.xyzw ACC, vf05.xyzw, vf29.x       | NOP                                          
3958  MADDx.xyzw vf31.xyzw, vf06.xyzw, vf30.x  | NOP                                          
3960  FTOI0.xyzw vf31.xyzw, vf31.xyzw          | NOP                                          
3968  NOP                                      | SQ.x vf31.x, -3(vi08)                        
3970  NOP                                      | MR32.xyz vf31.xyz, vf31.xyz                  
3978  NOP                                      | SQ.x vf31.x, -2(vi08)                        
3980  NOP                                      | MR32.xyz vf31.xyz, vf31.xyz                  
3988  NOP                                      | SQ.x vf31.x, -1(vi08)                        
3990  MULAx.xyz ACC, vf16.xyz, vf24.x          | ILW.y vi03, -2(vi09)                         
3998  MADDAy.xyz ACC, vf17.xyz, vf24.y         | ILW.y vi02, -3(vi09)                         
39a0  MADDz.xyz vf18.xyz, vf18.xyz, vf24.z     | IAND vi10, vi10, vi05                        
39a8  NOP                                      | IAND vi11, vi11, vi05                        
39b0  MINI.xyzw vf25.xyzw, vf25.xyzw, vf18.xyzw | MFIR.x vf24.x, vi10                          
39b8  MAX.xyzw vf26.xyzw, vf26.xyzw, vf18.xyzw | MFIR.y vf24.y, vi11                          
39c0  NOP                                      | IBLEZ vi01, 0x3da0                           
39c8  NOP                                      | ISUB vi10, vi00, vi10                        
39d0  NOP                                      | ISUB vi10, vi10, vi11                        
39d8  NOP                                      | IADDIU vi10, vi10, 255                       
39e0  NOP                                      | MFIR.z vf24.z, vi10                          
39e8  NOP                                      | IAND vi03, vi03, vi05                        
39f0  NOP                                      | IAND vi02, vi02, vi05                        
39f8  NOP                                      | IAND vi04, vi04, vi05                        
3a00  ITOF0.xyz vf24.xyz, vf24.xyz             | NOP                                          
3a08  NOP                                      | LQ.xyzw vf04.xyzw, 440(vi02)                 
3a10  NOP                                      | LQ.xyzw vf05.xyzw, 441(vi02)                 
3a18  NOP                                      | LQ.xyzw vf06.xyzw, 442(vi02)                 
3a20  MULi.xyz vf24.xyz, vf24.xyz, I           | LQ.xyzw vf07.xyzw, 443(vi02)                 
3a28  MULAy.xyzw ACC, vf04.xyzw, vf01.y        | LQ.xyzw vf08.xyzw, 440(vi03)                 
3a30  MADDAy.xyzw ACC, vf05.xyzw, vf02.y       | LQ.xyzw vf09.xyzw, 441(vi03)                 
3a38  MADDAy.xyzw ACC, vf06.xyzw, vf03.y       | LQ.xyzw vf10.xyzw, 442(vi03)                 
3a40  MADDw.xyzw vf16.xyzw, vf07.xyzw, vf00.w  | LQ.xyzw vf11.xyzw, 443(vi03)                 
3a48  MULAy.xyzw ACC, vf08.xyzw, vf01.y        | LQ.xyzw vf12.xyzw, 440(vi04)                 
3a50  MADDAy.xyzw ACC, vf09.xyzw, vf02.y       | LQ.xyzw vf13.xyzw, 441(vi04)                 
3a58  MADDAy.xyzw ACC, vf10.xyzw, vf03.y       | LQ.xyzw vf14.xyzw, 442(vi04)                 
3a60  MADDw.xyzw vf17.xyzw, vf11.xyzw, vf00.w  | LQ.xyzw vf15.xyzw, 443(vi04)                 
3a68  MULAy.xyzw ACC, vf12.xyzw, vf01.y        | ILWR.x vi10, (vi06)                          
3a70  MADDAy.xyzw ACC, vf13.xyzw, vf02.y       | ILWR.y vi11, (vi06)                          
3a78  MADDAy.xyzw ACC, vf14.xyzw, vf03.y       | ILW.z vi04, -1(vi09)                         
3a80  MADDw.xyzw vf22.xyzw, vf15.xyzw, vf00.w  | ILW.z vi03, -2(vi09)                         
3a88  MULAy.xyzw ACC, vf04.xyzw, vf28.y        | IADDI vi01, vi01, -1                         
3a90  MADDAy.xyzw ACC, vf05.xyzw, vf29.y       | NOP                                          
3a98  MADDy.xyzw vf31.xyzw, vf06.xyzw, vf30.y  | NOP                                          
3aa0  FTOI0.xyzw vf31.xyzw, vf31.xyzw          | NOP                                          
3aa8  NOP                                      | MR32.xyzw vf31.xyzw, vf31.xyzw               
3ab0  NOP                                      | MR32.xyzw vf31.xyzw, vf31.xyzw               
3ab8  NOP                                      | MR32.xyzw vf31.xyzw, vf31.xyzw               
3ac0  NOP                                      | SQ.y vf31.y, -3(vi08)                        
3ac8  NOP                                      | MR32.xyzw vf31.xyzw, vf31.xyzw               
3ad0  NOP                                      | SQ.y vf31.y, -2(vi08)                        
3ad8  NOP                                      | MR32.xyzw vf31.xyzw, vf31.xyzw               
3ae0  NOP                                      | SQ.y vf31.y, -1(vi08)                        
3ae8  MULAx.xyz ACC, vf16.xyz, vf24.x          | ILW.z vi02, -3(vi09)                         
3af0  MADDAy.xyz ACC, vf17.xyz, vf24.y         | IAND vi10, vi10, vi05                        
3af8  MADDz.xyz vf19.xyz, vf22.xyz, vf24.z     | IAND vi11, vi11, vi05                        
3b00  MINI.xyzw vf25.xyzw, vf25.xyzw, vf19.xyzw | MFIR.x vf24.x, vi10                          
3b08  MAX.xyzw vf26.xyzw, vf26.xyzw, vf19.xyzw | MFIR.y vf24.y, vi11                          
3b10  NOP                                      | IBLEZ vi01, 0x3da0                           
3b18  NOP                                      | ISUB vi10, vi00, vi10                        
3b20  NOP                                      | ISUB vi10, vi10, vi11                        
3b28  NOP                                      | IADDIU vi10, vi10, 255                       
3b30  NOP                                      | MFIR.z vf24.z, vi10                          
3b38  NOP                                      | IAND vi03, vi03, vi05                        
3b40  NOP                                      | IAND vi02, vi02, vi05                        
3b48  NOP                                      | IAND vi04, vi04, vi05                        
3b50  ITOF0.xyz vf24.xyz, vf24.xyz             | NOP                                          
3b58  NOP                                      | LQ.xyzw vf04.xyzw, 440(vi02)                 
3b60  NOP                                      | LQ.xyzw vf05.xyzw, 441(vi02)                 
3b68  NOP                                      | LQ.xyzw vf06.xyzw, 442(vi02)                 
3b70  MULi.xyz vf24.xyz, vf24.xyz, I           | LQ.xyzw vf07.xyzw, 443(vi02)                 
3b78  MULAz.xyzw ACC, vf04.xyzw, vf01.z        | LQ.xyzw vf08.xyzw, 440(vi03)                 
3b80  MADDAz.xyzw ACC, vf05.xyzw, vf02.z       | LQ.xyzw vf09.xyzw, 441(vi03)                 
3b88  MADDAz.xyzw ACC, vf06.xyzw, vf03.z       | LQ.xyzw vf10.xyzw, 442(vi03)                 
3b90  MADDw.xyzw vf16.xyzw, vf07.xyzw, vf00.w  | LQ.xyzw vf11.xyzw, 443(vi03)                 
3b98  MULAz.xyzw ACC, vf08.xyzw, vf01.z        | LQ.xyzw vf12.xyzw, 440(vi04)                 
3ba0  MADDAz.xyzw ACC, vf09.xyzw, vf02.z       | LQ.xyzw vf13.xyzw, 441(vi04)                 
3ba8  MADDAz.xyzw ACC, vf10.xyzw, vf03.z       | LQ.xyzw vf14.xyzw, 442(vi04)                 
3bb0  MADDw.xyzw vf17.xyzw, vf11.xyzw, vf00.w  | LQ.xyzw vf15.xyzw, 443(vi04)                 
3bb8  MULAz.xyzw ACC, vf12.xyzw, vf01.z        | ILWR.w vi10, (vi06)                          
3bc0  MADDAz.xyzw ACC, vf13.xyzw, vf02.z       | ILWR.z vi11, (vi06)                          
3bc8  MADDAz.xyzw ACC, vf14.xyzw, vf03.z       | IADDI vi06, vi06, 1                          
3bd0  MADDw.xyzw vf22.xyzw, vf15.xyzw, vf00.w  | ILW.w vi04, -1(vi09)                         
3bd8  MULAz.xyzw ACC, vf04.xyzw, vf28.z        | IADDI vi01, vi01, -1                         
3be0  MADDAz.xyzw ACC, vf05.xyzw, vf29.z       | NOP                                          
3be8  MADDz.xyzw vf31.xyzw, vf06.xyzw, vf30.z  | NOP                                          
3bf0  FTOI0.xyzw vf31.xyzw, vf31.xyzw          | NOP                                          
3bf8  NOP                                      | MR32.xyzw vf31.xyzw, vf31.xyzw               
3c00  NOP                                      | MR32.xyzw vf31.xyzw, vf31.xyzw               
3c08  NOP                                      | SQ.z vf31.z, -3(vi08)                        
3c10  NOP                                      | MR32.xyzw vf31.xyzw, vf31.xyzw               
3c18  NOP                                      | SQ.z vf31.z, -2(vi08)                        
3c20  NOP                                      | MR32.xyzw vf31.xyzw, vf31.xyzw               
3c28  NOP                                      | SQ.z vf31.z, -1(vi08)                        
3c30  MULAx.xyz ACC, vf16.xyz, vf24.x          | ILW.w vi03, -2(vi09)                         
3c38  MADDAy.xyz ACC, vf17.xyz, vf24.y         | ILW.w vi02, -3(vi09)                         
3c40  MADDz.xyz vf20.xyz, vf22.xyz, vf24.z     | IAND vi10, vi10, vi05                        
3c48  NOP                                      | IAND vi11, vi11, vi05                        
3c50  MINI.xyzw vf25.xyzw, vf25.xyzw, vf20.xyzw | MFIR.x vf24.x, vi10                          
3c58  MAX.xyzw vf26.xyzw, vf26.xyzw, vf20.xyzw | MFIR.y vf24.y, vi11                          
3c60  NOP                                      | IBLEZ vi01, 0x3da0                           
3c68  NOP                                      | ISUB vi10, vi00, vi10                        
3c70  NOP                                      | ISUB vi10, vi10, vi11                        
3c78  NOP                                      | IADDIU vi10, vi10, 255                       
3c80  NOP                                      | MFIR.z vf24.z, vi10                          
3c88  NOP                                      | IAND vi03, vi03, vi05                        
3c90  NOP                                      | IAND vi02, vi02, vi05                        
3c98  NOP                                      | IAND vi04, vi04, vi05                        
3ca0  ITOF0.xyz vf24.xyz, vf24.xyz             | NOP                                          
3ca8  NOP                                      | LQ.xyzw vf04.xyzw, 440(vi02)                 
3cb0  NOP                                      | LQ.xyzw vf05.xyzw, 441(vi02)                 
3cb8  NOP                                      | LQ.xyzw vf06.xyzw, 442(vi02)                 
3cc0  MULi.xyz vf24.xyz, vf24.xyz, I           | LQ.xyzw vf07.xyzw, 443(vi02)                 
3cc8  MULAw.xyzw ACC, vf04.xyzw, vf01.w        | LQ.xyzw vf08.xyzw, 440(vi03)                 
3cd0  MADDAw.xyzw ACC, vf05.xyzw, vf02.w       | LQ.xyzw vf09.xyzw, 441(vi03)                 
3cd8  MADDAw.xyzw ACC, vf06.xyzw, vf03.w       | LQ.xyzw vf10.xyzw, 442(vi03)                 
3ce0  MADDw.xyzw vf16.xyzw, vf07.xyzw, vf00.w  | LQ.xyzw vf11.xyzw, 443(vi03)                 
3ce8  MULAw.xyzw ACC, vf08.xyzw, vf01.w        | LQ.xyzw vf12.xyzw, 440(vi04)                 
3cf0  MADDAw.xyzw ACC, vf09.xyzw, vf02.w       | LQ.xyzw vf13.xyzw, 441(vi04)                 
3cf8  MADDAw.xyzw ACC, vf10.xyzw, vf03.w       | LQ.xyzw vf14.xyzw, 442(vi04)                 
3d00  MADDw.xyzw vf17.xyzw, vf11.xyzw, vf00.w  | LQ.xyzw vf15.xyzw, 443(vi04)                 
3d08  MULAw.xyzw ACC, vf12.xyzw, vf01.w        | MR32.w vf24.w, vf00.w                        
3d10  MADDAw.xyzw ACC, vf13.xyzw, vf02.w       | LQ.xyzw vf01.xyzw, 0(vi09)                   
3d18  MADDAw.xyzw ACC, vf14.xyzw, vf03.w       | LQ.xyzw vf02.xyzw, 1(vi09)                   
3d20  MADDw.xyzw vf22.xyzw, vf15.xyzw, vf00.w  | LQ.xyzw vf03.xyzw, 2(vi09)                   
3d28  MULAw.xyzw ACC, vf04.xyzw, vf28.w        | IADDI vi01, vi01, -1                         
3d30  MADDAw.xyzw ACC, vf05.xyzw, vf29.w       | NOP                                          
3d38  MADDw.xyzw vf31.xyzw, vf06.xyzw, vf30.w  | NOP                                          
3d40  FTOI0.xyzw vf31.xyzw, vf31.xyzw          | NOP                                          
3d48  NOP                                      | MR32.xyzw vf31.xyzw, vf31.xyzw               
3d50  NOP                                      | SQ.w vf31.w, -3(vi08)                        
3d58  NOP                                      | MR32.xyzw vf31.xyzw, vf31.xyzw               
3d60  NOP                                      | SQ.w vf31.w, -2(vi08)                        
3d68  NOP                                      | MR32.xyzw vf31.xyzw, vf31.xyzw               
3d70  NOP                                      | SQ.w vf31.w, -1(vi08)                        
3d78  MULAx.xyz ACC, vf16.xyz, vf24.x          | ILWR.x vi10, (vi06)                          
3d80  MADDAy.xyz ACC, vf17.xyz, vf24.y         | ILWR.y vi11, (vi06)                          
3d88  MADDz.xyz vf21.xyz, vf22.xyz, vf24.z     | ILW.x vi04, 2(vi09)                          
3d90  MINI.xyzw vf25.xyzw, vf25.xyzw, vf21.xyzw | NOP                                          
3d98  MAX.xyzw vf26.xyzw, vf26.xyzw, vf21.xyzw | NOP                                          
3da0  NOP                                      | IADDI vi09, vi09, 3                          
3da8  ADDx.y vf22.y, vf00.y, vf19.x            | SQ.x vf18.x, -6(vi09)                        
3db0  ADDx.z vf22.z, vf00.z, vf20.x            | SQ.y vf19.y, -5(vi09)                        
3db8  ADDx.w vf22.w, vf24.w, vf21.x            | SQ.z vf20.z, -4(vi09)                        
3dc0  ADDy.x vf23.x, vf00.x, vf18.y            | ILW.x vi03, -2(vi09)                         
3dc8  ADDy.z vf23.z, vf00.z, vf20.y            | ILW.x vi02, -3(vi09)                         
3dd0  ADDy.w vf23.w, vf24.w, vf21.y            | IAND vi10, vi10, vi05                        
3dd8  ADDz.x vf24.x, vf00.x, vf18.z            | IAND vi11, vi11, vi05                        
3de0  ADDz.y vf24.y, vf00.y, vf19.z            | NOP                                          
3de8  ADDz.w vf24.w, vf24.w, vf21.z            | NOP                                          
3df0  NOP                                      | SQ.yzw vf22.yzw, -6(vi09)                    
3df8  NOP                                      | SQ.xzw vf23.xzw, -5(vi09)                    
3e00  NOP                                      | IBGTZ vi01, 0x3848                           
3e08  NOP                                      | SQ.xyw vf24.xyw, -4(vi09)                    
3e10  NOP                                      | LQ.xyzw vf28.xyzw, 907(vi00)                 
3e18  NOP                                      | LQ.xyzw vf29.xyzw, 908(vi00)                 
3e20  NOP                                      | LQ.xyzw vf30.xyzw, 909(vi00)                 
3e28  NOP                                      | LQ.xyzw vf31.xyzw, 910(vi00)                 
3e30  NOP                                      | SQ.xyz vf25.xyz, 2(vi12)                     
3e38  NOP                                      | SQ.xyz vf26.xyz, 3(vi12)                     
3e40  NOP                                      | LQ.xyzw vf24.xyzw, 903(vi00)                 
3e48  NOP                                      | LQ.xyzw vf25.xyzw, 904(vi00)                 
3e50  NOP                                      | JR vi15                                      
3e58  NOP                                      | LQ.xyzw vf26.xyzw, 905(vi00)                 
```

