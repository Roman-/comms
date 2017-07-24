#In this folder, raw pure generated commutators are located
File names: a letter for element, then what algs are doing (2cycles actually means 2cycle pairs), then how many moves is part B (part A is always 1 move). Example: w5cycles4moves.txt contains wings 5cycles with 1 move part A and 4 moves part B, e.g. BUl-DBl-LBu-FRd-UFl.: [l, U' R L U].  
Cycle direction is not considered, i.e. the line  
`LU-RF-UF.: [F, L' E2 L]`  
means that the commutator for cycling LU-RF-UF has F move as its one part and L' E2 L as its another.  
Note that for edges(e3cycles3moves.txt) the cycle can be written in two different forms. Example: LU-RF-UF = UL-FR-FU. Same is true for corners: UBL-RFD-FUL = LUB-DRF-LFU = BLU-FDR-ULF.
