---
layout: page
title: About
---

# What HPC is

The HPC facility is a 7332 core/1PB 'Condo Cluster' available to all researchers at UCI (no School or Dept affiliation required). 'Condo' means that most of the compute nodes are individually owned by contributing Schools, Depts, or individual PIs, and are available to them preferentially, but when not so used, are available to the rest of campus users, using the [Free Queue](http://hpc.oit.uci.edu/free-queue) system. This allows all users to effectively get more computational power than they paid for, since usage among owners is quite spiky and the 'Free Queue' allows us to harvest otherwise unused cycles.

While the HPC facility is not [HIPAA-compliant](http://goo.gl/Qqcez), we have been told that appropriately anonymized human data are being reduced and analyzed through various pipelines on HPC.

In summary, HPC offers very large computing resources to all UCI researchers to allow them to store and analyze data of a size that would not otherwise be possible locally, and personal assistance in resolving specific computational problems. Should UCI researchers require even larger compute power, Harry Mangalam is an [XSEDE Campus Champion](https://www.xsede.org/campus-champions), who can help to move your problems to the larger XSEDE resources.

## Hardware

The HPC cluster is now the largest on campus with about 7330 64bit CPU cores, \~43TB aggregate RAM, 10 [Nvidia Tesla GPUs](http://www.nvidia.com/object/tesla-servers.html), with Quad Data Rate (40Gbs) Infiniband interconnects. There is \~1PB of storage with 650TB in 2 [BeeGFS (aka Fraunhofer)](http://www.beegfs.com/cms/) distributed filesystems, and the rest available from \~34 public and private NFS automounts. We have \~1600 users, of whom ~100 are logged in at any one time on 2 login nodes and over 250 use the cluster in an average month. The cluster generally has 65%-90% usage with several thousand jobs running and queued at any one time (>6000 as I write this; 20,000 is not unusual).

## Software

The HPC staff can usually add requested Open Source Software within a day; our 'module' system has >1000 external applications (various versions), libraries, and compilers/interpreters. These include image processing (freesurfer/fsl), statistics (R, SAS, STATA) numerical processing (MATLAB, Mathematica, Pylab/Numpy/SciPy, Scilab, GSL, Boost, etc), molecular dynamics (Gromacs, NAMD, AMBER, VMD), as well as a number of Engineering applications (OpenSees, Openfoam).

However, since our largest user group is biologists, we have an exceptionally large group of bioinformatics tools including the bam/sam/bedtools, tophat, bowtie, bwa, wgs, trimmomatic, repeatmasker, fastx toolkit, emboss, tacg, Bioconductor, BLAST, Trinity, GATK, Annovar, velvet, vcftools, cufflinks, smrtanalysis, the SOAP tools, picard, the Bio (Perl; Python; Java) toolkits, etc.

Our compilers support parallel approaches including OpenMP, OpenMPI, Gnu Parallel, R's SNOW, and CUDA. We support debugging and profiling with TotalView, PerfSuite, HPCToolkit, Oprofile, and PAPI. We also support a local installation of Galaxy, integrated into our GridEngine scheduler.
Our module library currently (Feb 25, 2016) consists of [this list](http://hpc.oit.uci.edu/all.modules).

---

# Classes

We run classes and tutorials in using Linux and the HPC cluster as well as Bioinformatics (in conjunction with the [Genomic High Throughput Facility](http://ghtf.biochem.uci.edu/)) and also offer classes in 'BigData' processing (with Padraic Smith of Information & Computer Sciences).

---

# Staff

HPC is supported by 2.5 FTEs, including 1.5 PhDs (in Molecular Biology & Bioinformatics and in Signal Processing), as well as 1 student assistant and these support staff regularly assist with debugging workflows and performance problems in all domains (~700 domain-specific emails per month). We very much welcome new computational and research challenges and our interaction with scientists. Please feel free to mail all of us at [hpc-support@uci.edu](mailto:hpc-support@uci.edu).

- **Joseph Farran**, HPC LEAD, HPC Architect Senior SysAdmin, 30+ years IT experience
- **Harry Mangalam**, PhD, HPC Data Storage Expert & Sys Admin, for the Research Computing Support Staff
- **Garr Updegraff**, PhD, DB Expert & Part-time Sys Admin
- **Edward Xia**, Part-time student SysAdmin
