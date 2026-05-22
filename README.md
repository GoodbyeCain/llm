# Qwen3.6-27B Q4_K_M MTP Summary

llama.cpp draft-MTP / ngram-combo · ROCm · includes no-speculation baseline (S1)


## Key Findings
* batch 1024 & ubatch 1024 get best PP
* k4v=96 is unstable
* suggest kv4=96 n=3

# Hardware Configuration
* GPU 0	AMD Radeon RX 7900 XTX	24 GB GDDR6
* GPU 1	AMD Radeon RX 7900 XT	20 GB GDDR6
* Total VRAM	44 GB
* CPU	AMD Ryzen 7 9700X (8C/16T)
* RAM	64 GB DDR5
* Motherboard	MS-iCraft B850 AIGA
* PSU	1300W
* ROCm	7.2.2
* OS	Ubuntu 24.04.4 LTS (Linux 6.17.0-14-generic x86_64)