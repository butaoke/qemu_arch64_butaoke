# Armv8-A AArch64 System Register List
> We need to focus on the following registers.

## ARM DDI 0487F.b(ID040120)
```
/* ARM DDI 0487F.b(ID040120) */

D13.2.36	ESR_EL1/2/3		(Exception Syndrome)
D13.2.39	FAR_EL1/2/3		(Fault Address)
D13.2.47	HCR_EL2			(Hypervisor Configuration)

D13.2.92	MAIR_EL1/2/3	(Memory Attribute Indirection)
D13.2.95	MIDR_EL1		(Main ID)

D13.2.96	MPIDR_EL1		(Multiprocessor Affinity)

D13.2.100	PAR_EL1			(Physical Address)

D13.2.112	SCR_EL3			(Secure Configuration)
D13.2.113	SCTLR_EL1		(System Control)
D13.2.113 	SCTLR_EL2		(System Control)
D13.2.113	SCTLR_EL3		(System Control)

D13.2.120	TCR_EL1/2/3		(Translation Control)

D13.2.132	TTBR0_EL1/2/3	(Translation Table Base)
D13.2.135	TTBR1_EL1/2		(Translation Table Base)
D13.2.137	VBAR_EL1/2/3	(Vector Base Address)
```

