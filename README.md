# Readings


### Static Analysis for Bug Finding
* 2021-USENIX: [Understanding and Detecting Disordered Error Handling with Precise Function Pairing](https://www-users.cs.umn.edu/~kjlu/papers/hero.pdf)
* 2021-NDSS: [KUBO: Precise and Scalable Detection of User-triggerable Undefined Behavior Bugs in OS Kernel](https://www.ndss-symposium.org/wp-content/uploads/ndss2021_1B-5_24461_paper.pdf)
* 2020-CCS: [Exaggerated Error Handling Hurts! An In-Depth Study and Context-Aware Detection](https://www-users.cs.umn.edu/~kjlu/papers/eecatch.pdf)
* 2020-TOCS：[Effective Detection of Sleep-in-atomic-context Bugs in the Linux Kernel](https://dl.acm.org/doi/pdf/10.1145/3381990)
* 2019-ASPLOS: [DCNS: Automated Detection Of Conservative Non-Sleep Defects in the Linux Kernel](https://hal.inria.fr/hal-02389543/document)
* 2019-FSE：[Detecting Concurrency Memory Corruption Vulnerabilities](https://dl.acm.org/doi/10.1145/3338906.3338927) — 【[tool-CONVUL](https://github.com/mryancai/ConVul)】
* 2019-USENIX：[Detecting Missing-Check Bugs via Semantic- and Context-Aware Criticalness and Constraints Inferences](https://www.usenix.org/conference/usenixsecurity19/presentation/lu) — 【[tool-CRIX](https://github.com/umnsec/crix)】
* 2019-USENIX：[PeX: A Permission Check Analysis Framework for Linux Kernel](https://www.usenix.org/conference/usenixsecurity19/presentation/zhang-tong)
* 2019-USENIX-ATC：[Effective Static Analysis of Concurrency Use-After-Free Bugs in Linux Device Drivers](https://www.usenix.org/conference/atc19/presentation/bai) — 【[note](https://securitygossip.com/blog/2019/11/22/effective-static-analysis-of-concurrency-use-after-free-bugs-in-linux-device-drivers/)】
* 2018-USENIX-ATC：[DSAC: Effective Static Analysis of Sleep-in-Atomic-Context Bugs in Kernel Modules](https://www.usenix.org/system/files/conference/atc18/atc18-bai.pdf)
* 2018-NDSS：[K-Miner: Uncovering Memory Corruption in Linux](http://wp.internetsociety.org/ndss/wp-content/uploads/sites/25/2018/02/ndss2018_05A-1_Gens_paper.pdf) — 【[note](https://mp.weixin.qq.com/s/3N3rmAyZEbZpiBvxnjWVvA)】【[note2](https://blog.csdn.net/u012332816/article/details/79795643)】【[tool-K-Miner](https://github.com/ssl-tud/k-miner)】
* 2018-S&P：[DEADLINE-Precise and Scalable Detection of Double-Fetch Bugs in OS Kernels](http://www-users.cs.umn.edu/~kjlu/papers/deadline.pdf) — 【[note](https://www.jianshu.com/p/e4084b2c7c16)】【[note2](https://www.jianshu.com/p/7e2f15547f1e)】【[note3](https://www.inforsec.org/wp/?p=2550)】【[tool-DEADLINE](https://github.com/sslab-gatech/deadline)】
* 2018-CCS：[Check It Again- Detecting Lacking-Recheck Bugs in OS Kernels ](https://www-users.cs.umn.edu/~kjlu/papers/lrsan.pdf)— 【[note](https://www.jianshu.com/p/2f8df6082b1d)】【[note2](https://securitygossip.com/blog/2018/11/27/check-it-again-detecting-lacking-recheck-bugs-in-os-kernels/)】【[tool-LRSan](https://github.com/kengiter/lrsan)】
* 2017-USENIX：[How Double-Fetch Situations turn into DoubleFetch](https://www.usenix.org/system/files/conference/usenixsecurity17/sec17-wang.pdf) — 【[note](http://www.inforsec.org/wp/?p=2049)】【[tool](https://github.com/wpengfei/double_fetch_cocci)】
* 2017-USENIX：[DR. CHECKER- A Soundy Analysis for Linux Kernel Drivers](https://www.usenix.org/system/files/conference/usenixsecurity17/sec17-machiry.pdf) — 【[tool-dr_checker](https://github.com/ucsb-seclab/dr_checker)】
* 2017-USENIX：[Digtool- A Virtualization-Based Framework for Detecting Kernel Vulnerabilities-usenix](https://www.usenix.org/system/files/conference/usenixsecurity17/sec17-pan.pdf) — 【[note](https://www.jianshu.com/p/3cc85231657d)】【[note2](https://mp.weixin.qq.com/s/RFWqx0LXWuHcJNbb8lrjFA)】【[note3](http://yama0xff.com/2019/02/15/Digtool-A-Virtualization-Based-Framework-for-Detecting-Kernel-Vulnerabilities/)】【[note4](https://securitygossip.com/blog/2018/10/09/digtool-a-virtualization-based-framework-for-detecting-kernel-vulnerabilities/)】
* 2017-EUROSYS：[DangSan - Scalable Use-after-free Detection](https://doi.org/10.1145/3064176.3064211) — 【[tool-dangsan](https://github.com/vusec/dangsan)】
* 2016-USENIX：[APISan: Sanitizing API Usages through Semantic Cross-Checking](https://pdfs.semanticscholar.org/29c2/42b2b73c376a61344877d5488f33e066ecc8.pdf?_ga=2.254762891.2010008061.1593351615-150437918.1586869794) — 【[tool-apisan](https://github.com/sslab-gatech/apisan)】
* 2016-USENIX：[UniSan-Proactive Kernel Memory Initialization to Eliminate Data Leakages](https://dl.acm.org/doi/pdf/10.1145/2976749.2978366) — 【[note](http://www.inforsec.org/wp/?p=1416)】【[tool-unisan](https://github.com/sslab-gatech/unisan)】
* 2015-SOSP：[Cross-checking semantic correctness: The case of finding file system bugs](https://lifeasageek.github.io/papers/min-juxta.pdf) — 【[tool-JUXTA](https://github.com/sslab-gatech/juxta)】
* 2014-USENIX：[Static Analysis of Variability in System Software - The 90, 000 #ifdefs Issue](https://www.usenix.org/conference/atc14/technical-sessions/presentation/tartler)
* 2013-DSN: [Hector: Detecting resource-release omission faults in error-handling code for systems software](https://hal.inria.fr/hal-00918079/document)
* 2013-WCRE: [Who Allocated My Memory? Detecting Custom Memory Allocators in C Binaries](https://www.cs.vu.nl/~herbertb/papers/membrush_wcre13.pdf)
* 2012-OSDI：[Improving integer security for systems with KINT](https://www.usenix.org/conference/osdi12/technical-sessions/presentation/wang)
* 2008-EUROSYS: [Documenting and automating collateral evolutions in linux device drivers](https://www.researchgate.net/profile/Yoann_Padioleau/publication/221351679_Towards_Documenting_and_Automating_Collateral_Evolutions_in_Linux_Device_Drivers/links/00b7d5255a2ef57876000000/Towards-Documenting-and-Automating-Collateral-Evolutions-in-Linux-Device-Drivers.pdf)
* 2007-ICSE: [Pathsensitive inference of function precedence protocols](https://docs.lib.purdue.edu/cgi/viewcontent.cgi?article=2660&context=cstech)
* 2005-ESEC/FSE: [Context- and Path-sensitive Memory Leak Detection](http://groups.csail.mit.edu/pag/OLD/parg/xie05leak.pdf)
* 2001-OSR: [Bugs as Deviant Behavior: A General Approach to Inferring Errors in Systems Code](https://apps.dtic.mil/sti/pdfs/ADA419584.pdf)

### Kernel Code and Page Table Protection

#### x86
* 2020-SP: [xMP: Selective Memory Protection for Kernel and User Space](https://www3.cs.stonybrook.edu/~mikepo/papers/xmp.sp20.pdf)
* 2017-EUROSP: [On the Effectiveness of Virtualization Based Memory Isolation on Multicore Platforms](https://ink.library.smu.edu.sg/cgi/viewcontent.cgi?article=4701&context=sis_research)
* 2017-NDSS: [PT-Rand: Practical Mitigation of Data-only Attacks against Page Tables](https://pdfs.semanticscholar.org/97c7/8ac6c015b5ed11eb825adc02fbb2a55913ae.pdf)
* 2016-CCS: [Prefetch Side-Channel Attacks: Bypassing SMAP and Kernel ASLR](https://dl.acm.org/doi/pdf/10.1145/2976749.2978356)
* 2015-ASPLOS: [Nested Kernel: An Operating System Architecture for Intra-Kernel Privilege Separation](https://nathandautenhahn.com/downloads/publications/asplos200-dautenhahn.pdf)
* 2015-ATC: [SecPod: A Framework for Virtualization-based Security Systems](https://www.usenix.org/system/files/conference/atc15/atc15-paper-wang-xiaoguang.pdf)
* 2011-ASPLOS: [Ensuring Operating System Kernel Integrity with OSck](https://dl.acm.org/doi/pdf/10.1145/1961295.1950398)
* 2011-NDSS: [Practical Protection of Kernel Integrity for Commodity OS from Untrusted Extensions](https://www.ndss-symposium.org/wp-content/uploads/2017/09/xipdf.pdf)
* 2010-CCS: [Hypersentry: enabling stealthy in-context measurement of hypervisor integrity](http://www.cse.psu.edu/~trj1/cse597-s11/docs/hypersentry_ccs10.pdf)
* 2010-SP: [Hypersafe: A lightweight approach to provide lifetime hypervisor control-flow integrity](http://www.cs.fsu.edu/~zwang/files/oakland10.pdf)
* 2009-USENIX: [Return-Oriented Rootkits: Bypassing Kernel Code Integrity Protection Mechanisms](https://www.usenix.org/legacy/events/sec09/tech/full_papers/hund.pdf)
* 2007-SOSP: [SecVisor : A Tiny Hypervisor to Provide Lifetime Kernel Code Integrity for Commodity OSes](http://www.cs.cmu.edu/~arvinds/pubs/secvisor.pdf)

#### ARM
* 2017-NDSS：Dynamic Virtual Address Range Adjustment for Intra-Level Privilege Separation on ARM
* 2016-NDSS: SKEE: A lightweight Secure Kernel-level Execution Environment for ARM
* 2014-MST: SPROBES: Enforcing Kernel Code Integrity on the TrustZone Architecture
* 2014-CCS: Hypervision Across Worlds: Real-time Kernel Protection from the ARM TrustZone Secure World

#### RISCV


#### MISC
* 2018-DAC: Hypernel: a hardware-assisted framework for kernel protection without nested paging
* 2016-HASP：Architectural supports to protect OS kernels from code-injection attacks
