# comms
This project contains all possible center-safe commutator algorithms for 5x5 cube in form of [A, B] where A is 1 move long and B is up to 5 moves long. Commutators that don't lead to any interesting cube state are eliminated.

By "interesting" I mean the following: 3cycles, 2-2-swaps, 5cycles, corner twists, edge flips.

More info: https://www.speedsolving.com/forum/threads/commutator-generation-5cycles-and-more.65489/

## Contents
In the oneMovePartA_raw directory, raw pure generated commutators are located. Each .txt file contains algs for a specific case.

Files naming: a letter for element, then what algs are doing, then how many moves is part B (part A is always 1 move). Example: w5cycles4moves.txt contains wings 5cycles with 1 move part A and 4 moves part B, e.g. BUl-DBl-LBu-FRd-UFl.: [l, U' R L U].

Asterics sign at the end of cycle means the alg is not center-safe, but it's "solved-centers-safe", meaning it will swap some centers on the same side, which wouldn't be possible to notice if they were solved.

Note that for edges (e.g. e3cycles3moves.txt) the cycle can be written in two different forms. Example: LU-RF-UF = UL-FR-FU. Same is true for corners: UBL-RFD-FUL = LUB-DRF-LFU = BLU-FDR-ULF. This means **if you're looking for all pure corner comms that contains e.g. UFR, you should consider all comms from these tables in all 3 forms of writing**.

