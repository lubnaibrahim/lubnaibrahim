Using Runtime Reconfiguration to Accelerate   
             Short Read Alignment







Student Name: Lubna Ibrahim Hamed Ibrahim Habeb.

Doctor Name: Sara Metwally.

Faculty Name: Computers and Information sciences.

University Name: Mansoura University.



Abstract : 
Recent advances in the throughput of next-generation sequencing machines have created a 
significant computational challenge in analysing vast amounts of sequenced data. 

Introduction :
NGS machines are capable of generating millions or even billions of short DNA fragments. The improvement of NGS technology has been exceeding Moore's Law for a decade. Short read-alignment is needed to bridge the gap between alignment research research and practice. NGS machines can sequence millions of DNA fragments in hours.
FPGA has shown to be a promising candidate to accelerate short read mapping because of its highly-parallel bit-wised bit-architecture. Different algorithms, for example, the FM-indexed algorithms, have been implemented and accelerated on FPGA.Most accelerators have failed to utilize the complete in-formation available in NGS data. Many FPGA researchers select and accelerate alignment algorithms that are in favor of hardware.
 As a result, the alignment implementations can be inconsistent with state-of-the-art software. This can result in incorrect alignment and generate incorrect alignment.
A two-stage alignment alignment archi-tecture that is similar to the seed-and-extend model adopted by Bowtie2. We decouple the seeding and extension stage into two separate FPGA configurations to achieve a balanced, fully optimized alignment pipeline ,The main contributions of this work are as follows:
pipeline for stage configuration alignment It takes advantage of the FPGA's reconfigurability to achieve highly efficient implementation and completely configured alignment for each configuration.

the pipeline
 A hardware implementation of the reconfigurable architectural framework
ture that focuses on a single FPGA. Seeding is the first stage of the process.on the implementation of the FM-index and the extension stage I'm basing this on a Smith-Waterman.
An evaluation of the best hardware architecture focused on the Xilinx VU9P target platform, as well as comparisons to the state-of-the-art tech Bowtie2 on multi-core platforms.
