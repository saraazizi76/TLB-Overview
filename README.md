# TLB-Overview
This repository presents a simplified architectural overview of a TLB design. It does not contain the full production RTL.
## Project Overview
## Key Features
The parameters setting is based on Intel Pentium Pro Core.  
    `DATA_WIDTH              : INTEGER := 32;  `    
    `ADR_WIDTH               : INTEGER := 20;  `  
    `INDEX_WIDTH             : INTEGER := 6; `   
    `SET_COUNTS              : INTEGER := 64; -- 2 ** INDEX_WIDTH --> #ENTRIES = #SETS = #ROWS   `  
    `TAG_WIDTH               : INTEGER := 14; -- ADR_WIDTH - INDEX_WIDTH  `  
    `WAY_COUNTS              : INTEGER := 4 -- 4-WAY SET ASSOCIATIVE`    
## Architectural View

## Simulation Results


## Implementation Results
