I-cache
=======

Instruction cache design in Verilog. I-cache is made up of tristate registers and a behavioral decoder. 
The instruction cache has a small 4 index victim cache. The I-cache itself is Direct-mapped. So it has simple eviction.
The victim cache however is fully-associative. So, I used Pseudo LRU as it's eviction policy

Detailed report in Report.pdf
