---
tags:
  - tech
  - comp_sci
---
The ENIAC was developed by Eckert and Mauchley as a electronic calculator for repetitive solutions of complex maths problems in the US Army. This was done through punched cards which were placed into the system to give it instructions. The UNIVAC, developed by the same duo brought a paradigm shift to the architecture of computing and von Neumann's work on this new form of computing architecture lead to the creation of the 'von Neumann Architecture of Computing' which is arguably the only constant in the half century of computing history.[[@ceruzzi2003history]]

The UNIVAC worked on the *stored-program principle*, the idea being that "operating instructions and function tables would be stored exactly in the same sort of memory device as that was used for numbers."[@Johnson1970] This system lead to the advent of 'programming' as the instructions had to given separately forming a different layer of the computing stack apart from the data that was to be processed.  

The von Neumann architecture takes this  concept further. 
- In his model, the units that process information are *separate* from the ones that *store* it.
- Though in the storage model, like the UNIVAC the data to be processed and the processing instructions are stored on the same memory device. This was done for two reasons: 
	- Firstly to ensure that the computer is not remaining idle for any span of time waiting for the instruction. It travels with the data
	- Secondly because the ratio of instructions to data is not constant, it made no sense to dedicate a separate expensive memory unit to it.
- There is a basic cycle that involves 
	- Transferring instructions (from the store to the processor) --> Decoding Instructions --> Executing it (using the data and the processing instruction) --> Transfer (from the very next position in memory)

![[Pasted image 20250620070513.png|center]]

This is at the foundation of computing as we know it. 