---
layout: default
---

<div style="
  background-color: #FFD54F;
  font-size: 1.1em;
  color: #333;
  padding: 1em;
  margin-bottom: 1em;
  text-align: center;
  border: 2px solid #FFCA28;
  border-radius: 10px;
">
  <b>Update:</b> I’m looking for post-PhD opportunities!
  If you need an engineer skilled in OS internals, compiler instrumentation, hardware/software interplay, and advanced systems security, please <a href="mailto:bjohannesmeyer@gmail.com">get in touch</a>!
</div>

## Experience

I’m a PhD candidate with the [VUSec](https://vusec.net/) group at [VU Amsterdam](https://vu.nl/en), where I devise techniques to track data and uncover vulnerabilities.

Previously, I did my MS at [UC San Diego](https://ucsd.edu/), where I hacked on avionics equipment and compiler internals with the [security group](https://cryptosec.ucsd.edu/).
Before that, I did my BS at the [University of Arizona](https://www.arizona.edu/), where I poked around with code deobfuscation and anti-analysis tricks with the [Lynx Project](https://www2.cs.arizona.edu/projects/lynx-project/index.html).

---

## Open-Source Contributions

Some of my research has resulted in open-source contributions. Here are some highlights:

* _(In progress)_ --- **Linux kernel, LLVM project**: KernelDataFlowSanitizer (KDFSAN), a generalized dynamic data flow analysis for the kernel \
&emsp;&ensp;[[Linux port](https://github.com/vusec/kdfsan-linux) | [LLVM port](https://github.com/vusec/kdfsan-llvm-project) | contact me for an up-to-date version]

* _(Submitted)_ --- **Linux kernel**: Mitigate a memory corruption vulnerability in the DMA pool allocator [[series](https://lore.kernel.org/lkml/20241122211144.4186080-4-bjohannesmeyer@gmail.com/)] \
&emsp;&ensp;*📣 "Very cool finding, this is nice work!" --Greg KH [[quote](https://lore.kernel.org/linux-mm/2024111914-overuse-cider-7734@gregkh/)]\
&emsp;&ensp;&emsp;&ensp;(High praise in the kernel world.)*

* _(Submitted)_ --- **Linux kernel**: Fix hundreds of inconsistent DMA accesses in VMware’s VMXNET3 driver [[series](https://lore.kernel.org/lkml/20241119221353.3912257-1-bjohannesmeyer@gmail.com/)]

* _May 2024_ --- **Linux kernel**: Add a fix for unaligned I/O accesses and a regression test to KernelMemorySanitizer (KMSAN) [[patch1](https://git.kernel.org/pub/scm/linux/kernel/git/torvalds/linux.git/commit/?id=bf6ab33d8487f5e2a0998ce75286eae65bb0a6d6) \| [patch2](https://git.kernel.org/pub/scm/linux/kernel/git/torvalds/linux.git/commit/?id=7005e7ec28855f3aa8355c39a7786d859ec92888)]

* _Apr. 2024_ --- **Linux kernel**: Improve the address‑to‑line script perf. by 15x [[series](https://lore.kernel.org/lkml/20240415145538.1938745-3-bjohannesmeyer@gmail.com/T/)]

* _Feb. 2022_ --- **Linux kernel**: Mitigate list iterator's speculative type confusion bugs \
&emsp;&ensp;[[92 patches](https://git.kernel.org/pub/scm/linux/kernel/git/torvalds/linux.git/log/?qt=author&q=%5C%28jakobkoschel%40gmail.com%5C%29%5C%7C%5C%28jkl820.git%40gmail.com%5C%29) | co-work with [Jakob Koschel](https://jakob-koschel.github.io/)] \
&emsp;&ensp;*📝 LWN coverage: [02/2022](https://lwn.net/Articles/885941/), [03/2022](https://lwn.net/Articles/887097/)*

* _Oct. 2016_ --- **OpenVPN, Kerberos, others**: Mitigate cases of the compiler optimizing out sensitive memory clear operations

---

## Publications

* **Dynamic Detection of Vulnerable DMA Race Conditions** \
B. Johannesmeyer, R. Isemann, C. Giuffrida, H. Bos\
*Under review*

* **Information Flow‑Based Vulnerability Modeling** \
B. Johannesmeyer\
*PhD Thesis, Vrije Universiteit Amsterdam, 2025*

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
