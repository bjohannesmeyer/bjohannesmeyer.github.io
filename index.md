---
layout: default
---

<img class="profile-picture" src="assets/headshot.jpg">

Hi, I'm Brian! I’m a PhD student at [VU Amsterdam](https://vu.nl/en), fascinated by all things systems security and kernel hacking. I enjoy discovering and mitigating software weaknesses before attackers can exploit them.

---

## About Me

### Contact

* Email: [bjohannesmeyer@gmail.com](mailto:bjohannesmeyer@gmail.com)
* Social: [GitHub](https://github.com/bjohannesmeyer/), [Google Scholar](https://scholar.google.com/citations?user=hveLyDgAAAAJ), [LinkedIn](https://www.linkedin.com/in/bjohannesmeyer), [Twitter](https://twitter.com/bjohannesmeyer)

### Research Interests

I build tools that automatically identify vulnerabilities and generate exploits.
I’m especially into systems security, operating systems, and program analysis—basically, finding ways to break (and then fix) software in creative ways.

### Experience

I’m a PhD student with the [VUSec](https://vusec.net/) group at [VU Amsterdam](https://vu.nl/en), where I devise techniques to track data and uncover vulnerabilities.

Previously, I did my MS at [UC San Diego](https://ucsd.edu/), where I hacked on avionics equipment and compiler internals with the [security group](https://cryptosec.ucsd.edu/).
Before that, I did my BS at the [University of Arizona](https://www.arizona.edu/), where I poked around with code deobfuscation and anti-analysis tricks with the [Lynx Project](https://www2.cs.arizona.edu/projects/lynx-project/index.html).

---

## Linux Kernel Contributions

### Merged

Some of my research has resulted in [contributions to the Linux kernel](https://git.kernel.org/pub/scm/linux/kernel/git/torvalds/linux.git/log/?qt=author&q=bjohannesmeyer%40gmail.com). Here are some highlights:

* **Mitigate speculative type confusion bugs in the list implementation** \
[[92 patches](https://git.kernel.org/pub/scm/linux/kernel/git/torvalds/linux.git/log/?qt=author&q=%5C%28jakobkoschel%40gmail.com%5C%29%5C%7C%5C%28jkl820.git%40gmail.com%5C%29) | co-work with [Jakob Koschel](https://jakob-koschel.github.io/)] \
*📝 LWN coverage: [02/2022](https://lwn.net/Articles/885941/), [03/2022](https://lwn.net/Articles/887097/)*

* **Improve the performance of the address-to-line script by 15x** [[series](https://lore.kernel.org/lkml/20240415145538.1938745-3-bjohannesmeyer@gmail.com/T/)]

### Ongoing

I also have work that is either currently submitted or in-progress:

* *Submitted*: **Mitigate memory corruption vuln. in the DMA pool allocator** [[series](https://lore.kernel.org/lkml/20241122211144.4186080-4-bjohannesmeyer@gmail.com/)] \
*📣 "Very cool finding, this is nice work!" --Greg KH [[quote](https://lore.kernel.org/linux-mm/2024111914-overuse-cider-7734@gregkh/)]\
&emsp;&ensp;(High praise in the kernel world.)*

* *Submitted*: **Mitigate inconsistent DMA accesses in VMware's VMXNET3 driver** [[series](https://lore.kernel.org/lkml/20241119221353.3912257-1-bjohannesmeyer@gmail.com/)]

* *Work-in-progress*: **KernelDataFlowSanitizer (KDFSAN), \
a generalized dynamic data flow analysis for the kernel** \
[[Linux port](https://github.com/vusec/kdfsan-linux) | [LLVM port](https://github.com/vusec/kdfsan-llvm-project) | please contact me for a more up-to-date version]

---

## Publications

* **Dynamic Detection of Vulnerable DMA Race Conditions** \
B. Johannesmeyer, R. Isemann, C. Giuffrida, H. Bos\
*Under review*

* **Practical Data-Only Attack Generation** [[paper](assets/einstein_sec24.pdf) \| [slides](assets/einstein_sec24_slides.pdf) \| [poster](assets/einstein_sec24_poster.pdf) \| [code](https://github.com/vusec/einstein) \| [video](https://www.youtube.com/watch?v=i8Qja60N268)]\
B. Johannesmeyer, A. Slowinska, H. Bos, C. Giuffrida\
*USENIX Security 2024*\
***🏆 CSAW Best Paper Award Runner-up***{: style="color: #0FAF0F; opacity: 0.80;" }

* **Data-Only Attacks Are Easier than You Think** [[web](https://www.usenix.org/publications/loginonline/data-only-attacks-are-easier-you-think)]\
B. Johannesmeyer, H. Bos, C. Giuffrida, A. Slowinska\
*USENIX ;login: 2024*

* **Kasper: Scanning for Generalized Transient Execution Gadgets in the Linux Kernel** [[paper](assets/kasper_ndss22.pdf) \| [slides](assets/kasper_ndss22_slides.pdf) \| [poster](assets/kasper_ndss22_poster.pdf) \| [web](https://www.vusec.net/projects/kasper/) \| [code](https://github.com/vusec/kasper) \| [video](https://www.youtube.com/watch?v=v89Zt3vxrww)]\
B. Johannesmeyer, J. Koschel, K. Razavi, H. Bos, C. Giuffrida\
*NDSS 2022*\
***🏆 DCSR Paper Award Runner-up***{: style="color: #0FAF0F; opacity: 0.80;" }\
***🏆 Qualcomm Innovation Fellowship Runner-Up***{: style="color: #0FAF0F; opacity: 0.80;" } for follow-up proposal

* **On the Effectiveness of Same-Domain Memory Deduplication** \
[[paper](assets/dedup_eurosec22.pdf) \| [slides](assets/dedup_eurosec22_slides.pdf) \| [web](https://www.vusec.net/projects/dedup-est-machina-returns) \| [code](https://github.com/vusec/dedup-est-returns)]\
A. Costi, B. Johannesmeyer, E. Bosman, C. Giuffrida, H. Bos\
*ACM EuroSec 2022*

* **Triton: A Software-Reconfigurable Federated Avionics Testbed** [[paper](assets/triton_cset19.pdf)]\
S. Crow, B. Farinholt, B. Johannesmeyer, K. Koscher, S. Checkoway, S. Savage, A. Schulman, A.C. Snoeren, K. Levchenko\
*USENIX CSET 2019*

* **FaCT: A DSL for Timing-Sensitive Computation** [[paper](assets/fact_pldi19.pdf) \| [slides](assets/fact_pldi19_slides.pdf) \| [code](https://github.com/PLSysSec/FaCT) \| [video](https://www.youtube.com/watch?v=DRPdQk_Uqeo)]\
S. Cauligi, G. Soeller, B. Johannesmeyer, F. Brown, R.S. Wahby, J. Renner, B. Grégoire, G. Barthe, R. Jhala, D. Stefan\
*ACM PLDI 2019*

* **FaCT: A Flexible Constant-Time Programming Language** [[paper](assets/fact_secdev17.pdf) \| [slides](assets/fact_sl18_slides.pdf) \| [code](https://github.com/PLSysSec/FaCT)]\
S. Cauligi, G. Soeller, F. Brown, B. Johannesmeyer, Y. Huang, R. Jhala, D. Stefan\
*IEEE SecDev 2017*

* **Dead Store Elimination (Still) Considered Harmful** [[paper](assets/sec17.pdf) \| [video](https://www.youtube.com/watch?v=litxEtE1cj8)]\
Z. Yang, B. Johannesmeyer, A.T. Olesen, S. Lerner, K. Levchenko\
*USENIX Security 2017*

* **A Generic Approach to Automatic Deobfuscation of Executable Code** \
[[paper](assets/sp15.pdf) \| [web](https://www2.cs.arizona.edu/projects/lynx-project/) \| [code](https://www2.cs.arizona.edu/projects/lynx-project/Source/Deobfuscator.tar.gz) \| [video](https://www.youtube.com/watch?v=VWL8-2G89_c)]\
B. Yadegari, B. Johannesmeyer, B. Whitely, S. Debray\
*IEEE S&P 2015*\
***🏆 CSAW Best Paper Award Runner-up***{: style="color: #0FAF0F; opacity: 0.80;" }

* **Identifying Understanding Self-Checksumming Defenses in Software** [[paper](assets/codaspy15.pdf) \| [web](https://www2.cs.arizona.edu/projects/lynx-project/)]\
J. Qiu, B. Yadegari, B. Johannesmeyer, S. Debray, X. Su\
*ACM CODASPY 2015*

* **A Framework for Understanding Dynamic Anti-Analysis Defenses** [[paper](assets/pprew14.pdf) \| [web](https://www2.cs.arizona.edu/projects/lynx-project/)]\
J. Qiu, B. Yadegari, B. Johannesmeyer, S. Debray, X. Su\
*ACM PPREW 2014*

---

## Teaching

* [Network Security](https://web.archive.org/web/20231205215139/https://studiegids.vu.nl/EN/courses/2021-2022/XM_0100#/) (VU Amsterdam) TA: P2 2021, P2 2022.
* [Computer and Network Security](https://web.archive.org/web/20231205215155/https://studiegids.vu.nl/en/Master/2019-2020/parallel-and-distributed-computer-systems/X_400127#/) (VU Amsterdam) TA: P1 2019, P1 2020.
* [Introduction to Computer Security](https://web.archive.org/web/20210303185213/https://catalog.ucsd.edu/courses/CSE.html) (UC San Diego, CSE 127) TA: [Fall 2017](https://cseweb.ucsd.edu/classes/fa17/cse127-b/), [Spring 2018](https://cseweb.ucsd.edu/classes/sp18/cse127-b/).
* [Introduction to Communications](https://web.archive.org/web/20250104181816/https://ece.engineering.arizona.edu/undergrad-programs/courses/ECE340A) (University of Arizona, ECE 340A) TA: Fall 2014, Spring 2015.

---
