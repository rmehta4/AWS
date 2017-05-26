# EC2 Notes
 
## General
1. EC2 - Elastic Compute Cloud
2. Run Systems
   1. RunInstances API : Indicate number of instances [_Default max limit : 20_]
   2. DescribeInstances API : Check Status of your instance
   3. TerminateInstances API : Progrmatically terminates the instance
3. Local Instance V/S Elastic Block storage
   - EBS : Data on the root device will persist independently from the lifetime of the instance.
   - Local Instance : Only persists during life of the instance.
4. EC2 uses ECC memory.
5. Instance Types :
   1. General purpose
   2. Compute Optimized
   3. Memory Optimized
   4. GPU and Storage Optimized
   5. Acronym [ D R M C G I F T P X (thanks , acloudguru!!)
6. M3 >> M1
7. Instances :
     - On Demand
     - Spot
     - Dedicated
     - Reserved
