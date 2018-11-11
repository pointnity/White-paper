Pointnity Network <br/>
=   

highcompatibleSex,canshared,Interactive collaboration of distributed systems<br>
Draftv1.0

A simple introduction The concept of blockchain<br/>
-    
  Blockchain development process<br/>
    The value of the blockchain<br/>
      Blockchain challenges<br/>
>1. Distributed consensus<br/>
>>2.performance<br/>
>>>3. scalability<br/>
>>>>4.system security<br/>
>>>>>5.data and storage<br/>
              
Pointnity Network Interpretation<br/>
-    
* HUB distributed information processing system<br>
>1.HUB design goals and effects<br>
>>2. Customized blockchain organization<br>
* Multi-chain interaction, controllable business information and ecological cooperation display<br>
>1. The essence of blockchain cross-chain<br>
>>2. Blockchain cross-chain architecture model<br>
>>>3.generate and package cross-chain transactions<br>
>>>>4. Providing sub-chains with cross-chain transactions to prove the launch of main-chain cross-chain services<br>
>>>>>5.the implementation of the main chain cross-chain transaction code<br>
>>>>>>6.Initiating Outer Chain Contract Service Call<br>
>>>>>>>7.the implementation of the external contract code<br>
>>>>>>>>8.generate a transaction log, update the status of the account<br>

* Supports extended aptamer chain internal channel cross-chain<br>
* Third.the consensus mechanism and system module<br>
* Improved Byzantine Consensus Algorithm Usage and Research<br>
>1. POINTNITY's Byzantine consensus algorithm design meets the validity attribute<br>
>>2. Basic Byzantine calculation model and reliable broadcast<br>
>>2.1 Base calculation model<br>
>>2.2 Reliable Broadcast<br>
>>>3. Blockchain Byzantine Consensus<br>
>>>3.1 Multivalued Byzantine Consensus<br>
>>>3.2 Binary Byzantine Consensus<br>
>>>>4. From multivalued to binary consensus Byzantine system<br>
>>>>4.1 The reduction<br>
>>>>4.2 Correctness certification<br>
>>>>>5.Binary consensus on the final synchronous Byzantine system<br>
>>>>>5.1 The BV Broadcast to All Communication Abstractions<br>
>>>>>5.2 Secure Binary Byzantine Consistency Algorithm BAMPn<br>
>>>>>5.3 Safety certification<br>
>>>>>5.4 Eventual synchronization hypothesis<br>
>>>>>5.5 Binary Byzantine Consensus Algorithm BAMPn<br>
* Piontnity token function<br>
* Naming system<br>
* System security<br>

* POINTNITY NETWORK was founded in November 2017 is a focus on eco-compatible, interactive collaboration, solving technical silos of block chain technology research and development team organization.<br>
POINTNITY NETWORK think to the center of the block chain, occult, can not be changed and other characteristics brought about by technological innovation will allow more individuals, groups, organizations, understanding, contact centers use to block chain and related technologies products.<br>
Because in the development of technology, information technology will inevitably become part of the islands of information, valuable concepts are not a powerful implement POINTNITY NETWORK is committed to building a high-compliant distributed interactive system. Provide distributed storage block chain information display service, rescue island information, so that information can have a strong conceptual resource assistance, and lowering the barriers to technology development team of more startups, as well as providing one-stop solution best supporting stack.<br>
BackboneThe improved PBFT consensus algorithm provides an external system interaction across chain collaboration. Low friction transactions are secured channel within the system,To provide effective protection for the good ecological development, in order to overcome many of the existingBlock chain technologyBottlenecks, speed up the block chain has spread to the quality of individual scenes pointnity committed to creating a highly flexible and compatible, collaboration, data storage and more authorityShowDistributed ecosystem decentralized to go.<br>
pointnity network<br>
In the future, a similar block chain will be the center of the internet and spoke model to integrate data and value. The future direction of the main block chain used will be achieved through the development of joint block chain to integrate these individual spoke. This integrated block chain network, will make any public or private organization to:<br>
　　　　　　　• Integration: send data and values ​​between any compatible with pointnity the block chain. <br>
　　　　　　　• Expansion: provides fast transaction processing capabilities and increased data capacity for all pointnity block chain.
　　　　　　　• Spoke: allows you to create a customized public or private block chain to keep up with the other block chain interoperability, while allowing publishers to select governance, consensus mechanism, release, and participation.<br>
Pointnity core network is a unique design, open, third-generation block chain. Designed for connecting other block chains and manage their own program chain bulk, pointnity also provides economic incentive system interoperability. pointnity token as a fuel of the entire network can be used to create a new block chain security, monetization across the chain bridge and protect the entire network.<br>
A first block chain to achieve network connection. It is designed to be a fair, distributed, open the block chain framework to meet the requirements of a multi-layer network architecture block chain. As an open chain block users will be able to deploy their own participation in the network, and communicate via a reliable infrastructure with other networks. Whether a large enterprise hosted private network, or community-based public network, you can connect to pointnity future, decentralized application can handle and integrate data from multiple block chain networks.<br>
HUB distributed information processing, storage system<br>
HUB distributed information storage processing system has the following design goals:<br>
Named dispersed and found: the end user should be able to (a) the registration and use of human-readable name and (b) find that mapped to human-readable name of network resources, without trusting any remote party.<br>
Dispersed storage: end-users should be able to use distributed storage system, where they can store their data and disclose it to any remote party.<br>
Comparable performance: the new architecture (including name / resource discovery, storage, access, etc.) end-to-end performance should focus on the traditional Internet services.<br>
* pointnity provides a very inclusive eco-system architecture, in which we can adjust themselves according to the conditions we need to develop a chimera, for the system to our needs. Now, we can replicate what we want, or need pointnity and run with the help of pointnity, avoiding strong ecosystem initially difficult ecological construction. There are challenges and sources of difficulty, which makes the environment easier to build consensus easier to reach an agreement between development.<br>
* POINTNITY team believes that cross-link technology may serve as a transition technology medium term, the future will be diversified collaboration platform is crucial, we POINTNITY team committed to creating a collaboration inside and outside the interconnection of an external multi-channel internal cross chain collaboration platform.<br>
　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　＃＃＃¹-2 / ¹-² / 2 / ¹-²-³ / 2<br>                              
Cross-channel mode with chains inside, is offchain, our POINTNITY supports dual use functionality as intermediaries relay contracts and bottom strand as the underlying operating system, our internal channel cross-link technology can be turned on chain and the results of executing the external passage interoperate across the chain.<br>
Consensus layer<br>
inPOINTNITYByzantine consensus algorithm proposed design meets the definition of consensus validity extended attributes. Structurally, it is composed of two parts.<br>
The first component is a multivalued binary ConsensusThe time to achieve consistencyReduced.itIs fully synchronized, neither randomization(E.g., Casper then bet)Nor is the ultimateCenter ofleaderMust cutThere is no signature. This reduction is always determined first asynchronous non-predetermined value O (1) consensus sequence of binary. The earliest examples of reducing wait before terminating only reliable broadcast concurrent instances of spawning binary consensus. Because it is assumed that t <N / 3, where n is the number of processes and t is the number of errors during the upper bound, this reduction is best toughness.<br>
The second component is a binary Byzantine consensus (BBC) algorithm, neither randomized nor the last leader, there is no signature. It is broadcast on the appropriate binary value (BV-broadcast) abstraction, for introducing randomization consensus. Calculated from a point of view, the BBC algorithm requires t <after N / 3 (as previous reduction), and additional synchronization hypothesis, i.e., there is a time, which is transmitting a message transmitted by the non-defective by the process delay constants the upper bound (this happens, but neither the time, nor is it a constant process known. in practice, this means that the BBC algorithm always terminate unless the transmission delay is always increased (in this case, different synchronization Suppose as described may be used).<br>
 we think that this is a process which is involved in PI Release BIN_CONS [K] by calling BIN_CONS [K] .bin_propose (V), wherein, v∈ {0,1}. Then, it executes a particular thread, and finally returns the value corresponding to the code determined by BIN_CONS [K].lowing local variables; ⊥ default values ​​can be represented by one (failure or no failure) processes proposed.<br>
Array proposalsi [1..N] is initialized to [⊥, ..., ⊥]. proposalsi [J] of the object contains a value PJ recommendations.<br>
bin_decisionsi initialized to [1..N] [⊥, ..., ⊥] array. bin_decisionsi [k] of the object contains a value (0 or 1) is determined by the binary objects consensus BIN_CONS [k] is.<br>
Operation mv_propose (VI) is (01) RB_broadcast VAL (ⅵ);<br>
If repeated ∃K: (proposalsi [k] of 6 = ⊥) ∧ (BIN_CONS [K] .bin_propose () does not call)<br>
Then call BIN_CONS [K] .bin_propose (1) END IF;<br>
Until (∃`: bin_decisionsi [ `] = 1) terminal repeat sequence;<br>
For each k that BIN_CONS [K] .bin_propose () call Not<br>
It does not call for BIN_CONS [K] .bin_propose (0) end;<br>
Until (V1≤x≤n box _decisionsi [X] 6 = ⊥);<br>
Ĵ ← min {x satisfies bin_decisionsi [X] = 1}; (09) wait_until	(Proposalsi [j] of 6 = ⊥);<br>
Return (proposalsi [J]).<br>
When VAL (v) is delivered from PJ RB- do, if valid (V) and then proposalsi [j] if the ← V cutoff.<br>
When BIN_CONS [K] .bin_propose () Returns a value b do bin_decisionsi [K] ← Bay<br>
Pointnity Token<br>
-  

* Cross-chain as a reward for the verifier<br>
*The data is stored in HUB can get as a reward token pont work.<br>
Name<br>
The traditional use of the Internet Domain Name System (DNS) maps humanreadable names to IP addresses (which gives the location of the nodes and content). When Internet users type in their browser, DNS server returns a human-readable names to IP addresses in cnn.com. ICANN, a non-profit organization, management and DNS root servers. The server is the central point of trust and failure; they can be taken offline by DDoS attacks and change the DNS server domain mapping through coercion, deception or change from their responses.<br>
In pointnity, we need to replace the dispersion DNS i.e., binds human-readable name to discover data, but without any central point of failure or control system. There is thought that human-readable name is not important, long passwords and ID search engines combine to provide an alternative DNS school. Our view is that human-readable names is to provide a good user experience, and essential in practice, it would be hard to convince Internet users to change their habits, and stop using the online human-readable name.<br>
No basic computer science challenges and build a naming system. There are three attributes, we may need to have a name: The name is<br>
The only (meaning that the absence of two independent people can create and use unique names like cnn.com)<br>
Human-readable (a name that looks like Paul should not 1A1zP1eP5QGefi2DMPTfTL5SLmv7DivfNa)<br>
Dispersion (name should be selected by the user in the center at the edge of the network by the central authorities, rather than on behalf of the user). Computer science challenge is before blockchains, naming system only allows three characteristics , any two of the three never at the same time. This limit is called the triangle Zooko. For example, the public key is unique, decentralized because users can generate their own computers without any central service, but not human readable. Twitter handle is human readable, unique, rather than scattered (Twitter, the company controls namespace). A nickname is human readable and dispersed (the user can select anyone nickname), but not the only. Blockchains party Zooko triangle, and for the first time there may be no use of a unique human-readable name of any centralized services.<br>
Namecoin is the first system to use blockchain establish decentralized naming system. Our experience running Namecoin production network on the show, highlighting the maximum mostsecure blockchain network requires a certain degree of security and reliability issues terms of reference are as follows: a space corresponding to the key organization and can not exceed a franchise<br>

System Security
--

Security pointnity defensive programming language derived from the design of the AVM and strict restrictions on the time, space and resource use. In addition, the security focus will also be provided by scripting language authoring tool. For example, the logical correctness pointnity chain code may, model checking verification and analysis tools provided by conventional bytecode.<br>
pointnity is an open, integrated block chain network and the initial network construction. It provides information on a homemade organization or enterprise developers the basic architecture of the complex technology, greatly reducing development time and cost value, so pointnity is a developer-friendly gathering place.<br>

Block Chain Development
--

The rapid development of the Internet in recent years, coupled with the strength and depth feedback physical world, has radically altered the production, living and management decision-making model of modern society, the formation of the real physical world - tight coupling virtual network space, interaction and actual situation parallel co-evolution of social space, gave birth to the "Internet +" and 4.0 and a series of national industrial strategy for the future development trend of social network certainly from CPS + actual physical world (Cyber-physical systems, CPS) to spiritual artificial world, forming a physical network + + artificial man - machine - ternary composition integration coupling system, information systems called social physical (Cyber-physical-social systems, CPSS) present, based on parallel societies have gradually taken shape CPSS its core is the actual situation and the essential characteristics of the interaction with the parallel evolution<br>
CPSS block chain is parallel to achieve one of the infrastructure of society, its main contribution is to provide a data structure of a well-established center to a distributed social systems and distributed artificial intelligence research, interaction mechanics and computing models, to achieve parallel and lay a solid social foundation and credit data on the basis of the data base, the management Edward Deming once said: in addition to God, everyone must speak to the data center of the social system, however, the data usually controlled by the government and large enterprises and other "minority" in the hands, a few people "speak", its impartiality, the authority may even security can not be guaranteed. block chain data through highly redundant distributed storage nodes, held by "everyone" in the hands, can do real "data democracy." on the basis of credit terms, its highly centralized system of social engineering complexity and social complexity inevitably there will be "Merton system" characteristics, namely uncertainty, diversity and complexity of social systems in the central institutions and rule-makers may arise due to acts of dishonesty individual interests; the block chain technology Contribute to social systems software-defined, the basic idea is to reject centralized institution, to the unpredictable behavior of the program code in the form of a smart contract early deployment and curing block chain data, and afterwards can not be forged and tampered with automation execution, which to some extent can the "Merton" social systems into a comprehensive observation can be actively controlled, can accurately predict the "Newton" social system .<br>
ACP (artificial social Artificial societies, computational experiments Computational experiments and parallel execution Parallel execution) method is so far the only parallel system into the field of social management, integrated research framework, is a logical extension of the lower complexity of science in parallel with the new era of social environment and innovation. ACP method can naturally be combined with the block chain technology, block chain-driven parallel social management. first, P2P networking block chain, distributed collaboration and consensus based on the contribution of economic incentives and other mechanisms themselves distributed modeling natural social system in which each node in a distributed system as an autonomous agent and self-government (Agent). with the improvement of the ecological system of the block chain, chain blocks each node and the growing consensus complex and intelligent autonomous contract through participation in various forms Dapp, form a particular form of organization and the DAO DAC, ultimately the DAS, i.e. ACP artificial society. Secondly, the programmable characteristics of contracts intelligent block chain such that each may be species "WHAT-IF" type of virtual experimental design and evaluation of results deduced scenario, this calculation experimented Obtain and automatically or semi-automatically execute optimal decision. Finally, the block chain with a combination of things such as intelligence assets, which makes China Unicom real physical world and the virtual network space as possible, and through real and actual situation interaction and artificial social systems parallel tuned achieve synergies and optimize social management decision-making is not hard to foresee the future of the real physical world of physical assets are registered as chain intelligence assets when the time is approaching block chain-driven parallel society.ACP (artificial social Artificial societies, computational experiments Computational experiments and parallel execution Parallel execution) method is so far the only parallel system into the field of social management, integrated research framework, is a logical extension of the lower complexity of science in parallel with the new era of social environment and innovation. ACP method can naturally be combined with the block chain technology, block chain-driven parallel social management. first, P2P networking block chain, distributed collaboration and consensus based on the contribution of economic incentives and other mechanisms themselves distributed modeling natural social system in which each node in a distributed system as an autonomous agent and self-government (Agent). with the improvement of the ecological system of the block chain, chain blocks each node and the growing consensus complex and intelligent autonomous contract through participation in various forms Dapp, form a particular form of organization and the DAO DAC, ultimately the DAS, i.e. ACP artificial society. Secondly, the programmable characteristics of contracts intelligent block chain such that each may be species "WHAT-IF" type of virtual experimental design and evaluation of results deduced scenario, this calculation experimented Obtain and automatically or semi-automatically execute optimal decision. Finally, the block chain with a combination of things such as intelligence assets, which makes China Unicom real physical world and the virtual network space as possible, and through real and actual situation interaction and artificial social systems parallel tuned achieve synergies and optimize social management decision-making is not hard to foresee the future of the real physical world of physical assets are registered as chain intelligence assets when the time is approaching block chain-driven parallel society.<br>

PONT token rules and Legal Notices
---

Please note that this is not any type of investment Description<br>
This document does not constitute any form of prospectus; it is not a solicitation to invest, not in any way involve the provision of securities in Canada or the United States, and Canada and the United StatesAs well as China'sResidents are expressly excluded any PONT exchange token donation in public products.<br>
DISCLAIMER:<br>
This site is for reference only. POINITY and all related companies and affiliates do not guarantee the accuracy of the conclusions reached by this site "as is" without any express or implied representations and warranties, including, but not limited to:<br>
Warranties of merchantability, for a particular purpose, or non-infringement of ownership;<br>
Contents of this website without any errors or for any purpose;<br>
Such Content will not infringe rights of third parties. All ensure clear sound. POINITY and its subsidiaries expressly disclaims any form of liability and damages resulting from the use, reference or reliance on information contained on this website caused, which we are not responsible.<br><br>
Recipients specific notice as follows:<br>
• does not provide any securities: PONT token (such as the POINITY white paper) is not intended to constitute securities in any jurisdiction. This site does not constitute a prospectus, nor does it provide any form of document, nor does it constitute an offer or solicitation of securities or any other investment product or any other jurisdiction.<br>
• No suggestion: POINITY this website does not constitute a recommendation to any PONT exchange token, should not rely on any contract or contribution decision.<br>
• No, said: Recipient or its advisers did not cause on this website, or contain information, statements, opinions or issues derived (expressed or implied) or the accuracy or completeness of any omission in this document or to make representations or warranties now or any other future available to any written or oral information or advice about the party or its advisers. For any plan or predict the future prospects of achievement or reasonableness makes no representations or warranties Nothing in this document should not be considered for future commitments or statements. To the maximum extent.<br><br>
• Donation: We only accept certified by KYC DonateDETAILED format by KYC<br>
In conclusion<br>
With the strong rise of digital encryption to Bitcoin currency as the representative of an emerging block chain technology has become the hot research topic in academia and industry. Credit to the center of the block chain technology can not be tampered with and programmable features so that it has a wide range of applications in digital encryption monetary, financial and social systems. However, compared with the block chain booming business applications, theory and technology research foundation block chain is still in its infancy, and many more the essential, vital to the development of the industry chain block scientific issues that must be follow-up study. This paper systematically reviews the basic principles of the block chain technology, techniques, methods and applications in order to provide useful inspiration and reference for future research .<br>
PointnityIs a compatible open network, ITheyI believe that his appearance will truly enhance the further development of blockchain world. Here, we sincerely hope that more people will participate in the construction blockchain world has made blockchain contribute to the construction of the world.<br>
