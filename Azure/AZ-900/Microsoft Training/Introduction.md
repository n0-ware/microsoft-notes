# What is the Cloud

- Matrix spoon reference
	- "There is no cloud"
	- Is just someone elses computer
	- I.e., Economy at scale
- What makes it special
	- Rent computing on demand
- 1000 different azure services

# Quick Tour

## Creating Resources 
### Compute
#az/compute/vm

- VM Creation similar to AWS. Region, family, VM Size (t2.nano but B4ms, etc.), IOPS
	- Some "Premium disk" option
- Charged by minute
- All VM's require username or password on Windows
- Assign an network/subnet and port(s)
- Everything is so very similar to AWS

#### Hybrid Licensing

#az/compute/vm/licensing 

- May be able to assign licenses from existing packages to new VMs