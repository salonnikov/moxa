# moxa
Driver for moxa C168H/PCI 


I just modified several source files from original driver MOXA C168H/PCI 
This driver can be used at fedora 24 (maybe 25&26 too)



mxser.c
comment from 156 to 162.
add line 163 (define IRQ_T(info) IRQF_SHARED)

mxpcie.h
comment line 83
add line 84 (#define IRQ_T(info) IRQF_SHARED)
