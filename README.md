# Memory_Simulator

Though this is a personal project, welcome anyone who are interested to join and commit.

The goal of this project is to build a memory simulator. There are serval functions need to support:

1. mimic the memory operations from logic level. But the logic level should down to each memory cell. Decoder should also be imitated.
2. Try to support SRAM, ROM, CAM, DRAM, Cache, DDRAM
3. Three inputs: 
	First of all, config and genrate memory cell, and memory controller(mux,decoder). That means, need to define a config file that can describe all the required feature of a memory. 
	Second, algorithms used to test the memory.
	Third, injected faults 
4. two outputs(one mandatory one optional):
	Mandatory: Coverage of the algorithm
	Optional: fault cells

		
			
