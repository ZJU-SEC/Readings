# Readings


### Kernel analysis

* 2020-CCS: [Exaggerated Error Handling Hurts! An In-Depth Study and Context-Aware Detection](https://www-users.cs.umn.edu/~kjlu/papers/eecatch.pdf)
* 2020-TOCS：[Effective Detection of Sleep-in-atomic-context Bugs in the Linux Kernel](https://dl.acm.org/doi/pdf/10.1145/3381990)
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
* 2013-WCRE: [Who Allocated My Memory? Detecting Custom Memory Allocators in C Binaries](https://www.cs.vu.nl/~herbertb/papers/membrush_wcre13.pdf)
* 2012-OSDI：[Improving integer security for systems with KINT](https://www.usenix.org/conference/osdi12/technical-sessions/presentation/wang)
