---
layout: none
key: page-home
---

## Overview

&ensp;&ensp;Sigma@SDU is a research group centered around primitives and protocols of public key cryptography, led by Prof. Zengpeng Li and Prof. Mei Wang at the School of Cyber Science and Technology, Shandong University, and is part of the MoE Key Laboratory of Cryptologic Technology and Information Security.

&ensp;&ensp;Research projects at Sigma@SDU focus on real-world problems about security and privacy, including secure multiparty computation, identification and authentication, verifiable computation, and blockchain technology. Our research has been supported by various competitive grants from the National Natural Science Foundation of China, National Key Research and Development Program of the Ministry of Science and Technology, etc.

&ensp;&ensp;Sigma@SDU works with industry partners, including Huawei’s Shield Lab and BitMain’s Antalpha Lab, to secure our network, assets, and infrastructure. Our arsenal comprises state-of-the-art techniques of fields including fully homomorphic encryption, zero-knowledge proofs, authenticated key exchange, and lattice-based cryptography.

<br>

## Secure MPC at Sigma@SDU

<div class="dahezi_img_left"><img src="./images/lwe.png"/> </div>
<div class="dahezi_txt_right">
<p class="row-1">
&ensp;&ensp;Secure Multi-Party Computation (MPC) can be categorized into two tracks, i.e., garbled-circuit-based MPC and homomorphic-encryption-based MPC, the former of which being generally lightweight in terms of computation but incurring high communication cost, and the latter being the opposite. Although network overhead is more of a concern in most real-world scenarios, homomorphic-encryption-based MPC is still rarely used in practice due to computational bottlenecks present in most Fully Homomorphic Encryption (FHE) schemes which render it inefficient.
</p>
<p class="row-1">                  
&ensp;&ensp;To deal with this limitation, Sigma@SDU has been working on lattice-based FHE schemes and efficient FHE-based MPC protocols since 2012. Specifically, we have conducted research on threshold and multi-key FHE schemes, and MPC protocols with verifiability and fairness properties. In addition, we have built practical Private Information Retrieval (PIR) solutions based on FHE and Function Secret Sharing (FSS) schemes, which enable database lookups with queries hidden from the server and can also be applied to Anonymous Message Delivery and Oblivious Message Retrieval services when composed with authentication techniques; these services facilitate applications such as online advertisements, search engines, bulletin boards, and OSINT platforms with better user privacy than existing solutions.
</p>
</div>

<br>

## Identification and Authentication at Sigma@SDU

<div class="dahezi_img_left"><img src="./images/AKE1.png"/> </div>
<div class="dahezi_txt_right">	
<p class="row-1">   
&ensp;&ensp;Proper identification and authentication of the user acts as the first line of defense in securing computer systems. Multiple factors should be considered in authenticating user identities, including passwords, physical keys, and fingerprints, which represent what the user knows, what the user has, and who the user is, respectively.
 </p>  
<p class="row-1">   
&ensp;&ensp;Since 2016, Sigma@SDU has been doing research on Password-Authenticated Key Exchange (PAKE) protocols, designed for embedded devices such as Internet of Things appliances and mobile phones. Our PAKE scheme unifies identification and session key agreement, and utilizes passwords or biometrics for symmetric key establishment without the need for a Public Key Infrastructure (PKI). Besides that, we have worked on a lightweight group authentication scheme, which uses only lightweight hashing and encryption primitives, enables end-to-end secure messaging among resource-constrained group members, and can be applied to the secure communication of Unmanned Aerial Vehicles (UAVs), On-Board Units (OBUs), etc. situated in ad hoc networks.
 </p>
</div>

<br>

## Blockchains at Sigma@SDU

<div class="dahezi_img_left"><img src="./images/block.png"/> </div>
<div class="dahezi_txt_right">		
  <p class="row-1">   
&ensp;&ensp;In recent years, blockchains have been a trending topic both for the general public and cryptography researchers. Sigma@SDU keeps track of big events in the cryptocurrency world and has been working towards improved privacy and trustworthiness in that community. In more detail, we have worked on projects regarding zero-knowledge proofs in lattice-based, multiple-prover, and designated-verifier settings, and efficient threshold ECDSA/Schnorr signing protocols that enable secure, distributed wallet custody. Also, we have built Distributed Randomness Beacon (DRB) schemes that generate unbiased, unpredictable, cryptographically-secure random numbers suitable for multi-party protocols and smart contracts.
 </p>
</div>


<style>
  .dahezhi{
    width: 100%; 		/* 定义一个大盒子  宽度100% */
  }
  .dahezi_img_left{		/* 第二个盒子, */
    width: 50%;
    float: left; 		/* 要左浮动 */
    margin-right: 40px; /* 为了让图片和文字不贴着,右外边距定义40px */
    }
  .dahezi_txt_right{		/* 定义第三盒子 */
    font-size: 15px;  	/* 设置字体大小 */
    line-height: 1.6;	/* 设置行距 */
  }
  img{
    width: 100%;		标签样式 让图片宽度500px,
    height: auto;		/* 高度自动 随它去吧 */
    }
</style>
