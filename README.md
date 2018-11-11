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
Byzantine consensus based on a predicate validity 3.1Multivalued<br>	 
In this paper, we consider a generalization of the classic Byzantine consistency, the introduction informally. Because of its effectiveness requirements excited by blockchain, it depends on effective application of specific predicate to indicate whether the value is valid, we call this predicate validity of the Byzantine consensus problem-based (expressed VPBC) and define it as follows. Assume that each process is not flawed, it proposed an effective value, each of them has in such a way, also has a satisfactory value determines the following properties.[]<br>
VPBC termination. The value of a final decision on each non-faulty process.<br>
VPBC- agreement. Two non-fault decision process is not different values.<br>
VPBC- effectiveness. Value determination is effective, it is effective to meet the predefined represented as predicates ().<br>
The classic definition of this definition Byzantine general consensus, does not include a valid predicate (). As an example, in a collision fault model, any proposed value is valid. In the Byzantine basic consensus, any suggestions values are valid unless all non Troubleshooting made the same value v, in this case, only the v is valid. This predicate into account the introduction of the consortium blockchains, as well as other possible specific distinctive features Byzantine consensus problem. In the context of the consortium blockchains, proposal is not valid, the hash value is added to the appropriate Blockchain last block if it does not contain.
3.2Binary Byzantine consensus	<br>
Multi-valued VPBC implementation relies on a potential binary Byzantine consensus (expressed as BBC). It's a free leader, as well as free signature free randomization implementation described in Section <br>
This duality Byzantine consensus validity attributes are as follows: If all non Troubleshooting made the same value, no other values can be determined. To prevent confusion, the nature of the validity of the termination agreement and the BBC is denoted BBC- effectiveness, and BBC- BBC- agreement termination.<br>
4From multi-value to binary consensus Byzantine system	<br>
This section describes the consensus of the former Byzantine binary, reducing the value of multi-Byzantine consensus. We reduced guarantee an end after two binary sequence consensus instance. This is, to our knowledge, the first reduction in the non-predetermined value of O (1) Examples of the consensus sequence of binary decisions. Other reducing or returns a predefined value if the consensus ⊥ suspension, or intolerance Byzantine fault and perform binary consensus sequence of claim dlogne instance. Our reduction is based on the abstract RB- broadcast communications, and examples of the underlying binary Byzantine consensus. Let BBC said that to solve the computing power required for two yuan Byzantine consensus. Thus, "multi-value to binary" reduced working model BAMPn, T [t <N / 3, BBC]<br>
4.1The reduction	<br>
Binary consensus object as mentioned earlier, in addition to broadcasting RB- abstract, the method can mark BIN_CONS [1..N] two yuan Byzantine array of cooperation consensus object. Examples BIN_CONS [k] allows the process to find the value of non-fault by PK proposed agreement. This object is achieved by binary Byzantine consensus algorithm presented in Section 5.<br>
To simplify the description, we think that this is a process which is involved in PI Release BIN_CONS [K] by calling BIN_CONS [K] .bin_propose (V), wherein, v∈ {0,1}. Then, it executes a particular thread, and finally returns the value corresponding to the code determined by BIN_CONS [K].lowing local variables; ⊥ default values ​​can be represented by one (failure or no failure) processes proposed.<br>
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
Figure 1: from the multi-value to binary Byzantine consensus BAMPn, T [t <N / 3, BBC]<br>
The algorithm of the reduced multivalued binary Byzantine Byzantine consensus consensus is described in this algorithm, a procedure call operation mv_propose (V), wherein, v is its value pseudomultichannel consensus value 1 in FIG. A process pi behavior can be broken down into four stages.<br>
Stage 1: PI propagation value (lines 01 and 11). A method by calling the first PI RB- broadcast operation (wire 01) which processes the transmission of all values. When a transfer process by RB-RB-broadcast technology PJ value v, which is stored in proposalsi [j] is valid if v (line 11).<br>
Stage 2: PI has been involved a first set of binary consensus instances (lines 02-04) is.<br>
Then, the PI enters a loop where it began to participate binary consensus Examples BIN_CONS [K], it is proposed 1, PK RB- from each process having an associated delivery recommended values ​​(lines 02-03). Examples of common pi binary found BIN_CONS , wherein 1 is determined (line 04) to stop the cycle. (Binary consensus of our proposed after allowing only O (1) message arrived after a delay stage (2) of the ends.)<br>
Stage 3: PI began to participate in all other binary consensus instances (lines 05-06).<br>
It knows a binary instance of consensus decision after 1, PI call in all instances it has not been involved in binary consensus BIN_CONS [K] bin_propose (0). We note that this is possible, some examples BIN_CONS [k], there is no process has provided a value from the associated process PK RB-. The purpose of these common shares is to ensure that all binary consensus, the final termination.<br>
Phase 4: the value of pi is determined (lines 07-10 and 12).<br>
Finally PI consensus that successful binary objects, i.e., the first (according to the process sequence index), i.e., those that returns 1 (line 08) is.[]Let BIN_CONS [J] is such a consensus binary objects. Since the decision value of 1 is associated, at least one non-fault proposed procedure shown in FIG. 1, which means that the PJ value from the process (lines 02-03) RBdelivered of. We observed that, due to the termination of -2 RB- property, the value of each process is final RB- delivered without defects. Thus, PI decided that (lines 09-10).<br>
 Correctness prove	<br>
Lemma 1. The decision is worth at least a binary consensus, all non-fault process exit repeat the cycle.
From the operational point of view, this lemma can be restated as follows: At least one `∈ [1..N] so that each non-faulty process P1, we end up with bin_decisionsi [`] = 1.<br>Evidence is contradictory. Let us assume that, in any non-fault process P1, no bin_decisionsi [ `], 1≤`≤N, is constantly set to 1. Thus, there is no non-fault process exit "repeat" loop (line 0204). Valid values as non-defective RB-PJ broadcast process, it follows from the RB-terminated -1 characteristic, each non-fault proposed to provide an effective process PI RB- PJ, so we end up with proposalsi [j] of 6 = ⊥ PI processing in each non-defective.<br>
It follows the first sub-predicate from line 02 of all non-fault handling Pi call bin_propose (1). In the object BIN_CONS BBC [J]. Thus, the BBC termination, BBC- protocol, BBC- effectiveness and tolerance of intrusion, which returns all instances BBC process to a value of the non-defective, wherein the outlet<br>
"Repeat" cycle.	2Lemma 1<br>
Lemma 2 determination value is a valid value (i.e., it is effective to satisfy the predicate ()).We first prove that observed for a value proposalsi [J] is determined by the circumference of a process, we need bin_decisionsi [J] = 1 (lines 08-10).If the value is 1 when BIN_CONS [j], bin_decisionsi [j] = 1 is a processing decision PI (line 12) in each non-fault final true. If only one example proposed a BBC, and (ii) BIN_CONS in line 03 from (i) the value [J] intrusion resistance, i.e. at least one non-fault PI procedure call BIN_CONS following facts [j] of .bin_propose (1). Because the predicate line 02, when this process is the non-faulty pI of such proposalsi [j] of 6 = ⊥ it calls BIN_CONS [j] of .bin_propose (1). Since the line 11, it follows proposalsi [j] contains a valid value.	2Lemma 2Lemma 3 is not a non-fault handling two different values determined.Let us consider two prove any non troubleshooting Pi and PJ, PI so decided proposalsi [K] and PJ decided proposalsj [K2]. It follows from line 08 is K1 = min {x satisfies bin_decisionsi [X] = 1} and k2 = MIN {x satisfies bin_decisionsj [X] = 1}.Ontheonehand, itfollowsfromline07that(V1≤x≤nbin_decisionsi [X] 6 =⊥)with(V1≤x≤nbin_decisionsj [X] 6 = ⊥), from which we conclude that both pi and PJ known examples (line 12) is determined by the binary value of each binary consensus. Due to the properties of each binary consensus agreement BBC- instance, we have ∀x: bin_decisionsi [X] = bin_decisionsj [X]. Let decanoate [X] = bin_decisionsi [X] = bin_decisionsj [X]. From line 08 it is K1 = K2 = min {x dec satisfy [X] = 1} = K then follows. Thus, decyl [K] = 1.On the other hand, it is derived from BIN_CONS [k] is a non-invasive properties of fault tolerant process p` call BIN_CONS [K] .bin_propose (1). In line 03 may be issued as the call only, we conclude (verb from line 02), the proposals` [K] = V 6 = ⊥. P` as fault-free, and it follows from the RB-RB-terminated -2 ​​unity for all non-fault handling characteristics supplied from PK RB- v. Thus, we end up with proposalsi [K] = proposalsj [K], wherein draw conclusions prove the lemma. 2Lemma 3Lemma 4. The value of each non-fault handling decision.It follows from the proof of Lemma 1, there are some PJ allows us to finally have bin_decisionsi [J] = 1 in the process of all non-fault and non-fault does not always online processing block 04. Therefore, all non-fault process calls each binary consensus instance ( line 03 or line 06). Further, due to their characteristics BBC- termination, each of n binary consensus non-return results in each example of troubleshooting. Thus, in the always-on 07. Finally, no trouble-free process PI block, as seen in the proof of Lemma 3, line 09 predicate is free from defects in every process, summed up the proof of the lemma, ultimate satisfaction . 2Lemma 4Byzantine Consensus Model (VPBC) of a multi-value system algorithm in the tool of FIG. 1 described theorem BAMPn, T [t <N / 3, BBC].Evidenced by Lemma 2 (VPBC- potency), Lemma 3 (VPBC- protocol), and Lemma 4 (VPBC termination) as follows.<br>
2Theorem 1<br>
In the final synchronization Byzantine system 5Binary consensus<br>	
This section describes the underlying binary consistency Byzantine algorithm BBC, which provides a process operation bin_propose (). The advantage of this algorithm is that it is guaranteed to terminate, if all non-faulty process made the same value, if not synchronized and always in a constant number of message delays. The algorithm may terminate within a fixed time, this is the case, e.g., if all non-fault handling proposed by the same value. The algorithm relies on all communication to all binary abstract (BVbroadcast) and final synchronization hypothesis, which is described in the following section. The algorithm gradually established. We first present a simple algorithm, only to meet consensus safety performance (BBC- effectiveness and BBC- protocol). The algorithm is then synchronized with the final extension to meet the consensus assumptions active property (BBC- termination). The purpose of this gradual approach is for ease of understanding and proof.<br>
5.1The BV broadcast to all communication to abstract all	<br>
Broadcast binary value (BV-broadcast) communication abstraction has been introduced (which is implemented in the Appendix A review) in .<br>
Broadcast to all is defined BV- abstract all communications, it provides a method BV_broadcast represented by a single operation (). When a process calls BV_broadcast TAG (m), we say that it "BVbroadcasts message TAG (meters)." Content of the message m is 0 or 1 (hence the "binary value" word Communications Abstract names herein).<br>
In a broadcast BV- e.g., each binary value of the non-faulty process PI BV- broadcast, and obtains a set of binary values, local variables are stored in read-only setting is represented as bin_valuesi. This set, initialized to ∅, adding new value is received. BV- broadcast defined by the following four properties.<br>
BV- obligations. If at least (T + 1) during non-fault BV- same broadcast value v, v is added to the final set of non-defective bin_valuesi each process pi.<br>
BV- reasons. If no fault is pi and v∈bin_valuesi, V has a non-fault process BV- broadcast.<br>
BV- uniform. If the value of v is added to the fault set bin_valuesi no process P1, the final v∈bin_valuesj no defect each process PJ.<br>
BV- terminated. Finally, each non-fault process pi bin_valuesi collection is not empty.<br>
Play a BV- Properties The following properties are a direct consequence of the previous character. Finally, the non-faulty process Pi (i) become non-empty set bin_valuesi, (ii) becomes equal, (iii) contains the values ​​of all the non-faulty processing broadcast, and (iv) does not contain a value only by the broadcast Byzantine type of process. However, (ii) and (iii) does not occur when the process known non-defective.<br>
Byzantine consensus algorithm in binary security 5.2A 	BAMPn, T [T <N / 3]2 depicts a simple binary consistency Byzantine algorithm, satisfy the model system BBC- BAMPn effectiveness and properties BBCAgreement, T [T <N / 3]. The algorithm, which is based on a circle, depending on previous broadcast BV- abstract, have the same structure, the introduction of random consensus algorithm.<br>
Local variables Local variables for each of the following management process PI.<br>
ESTI: Current estimates place the value of the decision. It is initialized value of PI raised.<br>
RI: Local round number, initialized to zero.<br>
Box _valuesi [1 ..]: an array of binary values; bin_valuesi [R] (initialized ∅) storing a set of stainless steel by a monovalent BV- broadcast associated filling local output. (This can be a single infinite array of local variables bin_valuesi replacement, re-start of each round ∅. Here, we consider one array to simplify the presentation.)<br>
Double: auxiliary binary value.<br>
valuesi: an auxiliary set of values.<br>
Message Type The algorithm uses two types of messages, indicated as EST and AUX. Both use in each round, a round number so they always appear.<br>
EST [R] () in a stainless steel by the PI value to estimate BV- broadcast its current decision ESTI be used.<br>
AUX [R] () for propagating its current bin_valuesi [R] is a value obtained by PI (broadcast under the macro (help) operation).<br>
Let us consider the algorithm of FIG. 2 after it has been deposited proposal The ESTI binary (line 01), each non-fault sequence into the asynchronous process PI wheel. Each round r, using a broadcast BV- instance, its local variables associated with the process pi is bin_valuesi [R].<br>
Operation bin_propose (VI) is<br>
ESTI ← six; RI ← 0;<br>
While (true) do<br>
RI ← RI + 1;<br>
BV_broadcast EDT [RI] (ESTI);<br>
wait_until bin_ value	;<br>
Broadcast AUX [RI] (bin_valuesi [RI]);<br>
wait_until message AUX [RI] (b_valp (1)), ..., different AUX process P (X), 1≤X≤N - [RI] (b_valp (N- t)) has the (TN) - receiving tons, and their content is such, that ∃ a non-empty valuesi (ⅰ) valuesi⊆bin_valuesi [RI] and (ii) the value of	;<br>
2 ← RI double mold;<br>
If (valuesi = {V}) // valuesi is a single, whose elements v<br>
Then ESTI ← V; if (V = BI) before deciding (V), if not ended, if;<br>
Otherwise ESTI ← double<br>
just in case;<br>
The end of a period of time.<br>
Figure 2: a binary security algorithm for Byzantine agreement BAMPn, T [t <N / 3] conduct during the non-faulty process oxygen circular pi can be broken down in three stages.<br>
Stage 1: The current estimate (lines 03-05) coordinated the exchange.<br>
PI process first proceeds to the next round, and BV- broadcast its current estimate (line 04). After, PI wait until it sets bin_valuesi [R] is not empty (let us recall that when bin_valuesi [R] is not empty, it is not necessarily its final value).<br>
Phase 2: The second estimate of exchange in favor of convergence (lines 06-07).<br>
In this second stage, the PI broadcast (Thus, this is neither a nor RB- BV- broadcast broadcast) message<br>
AUX [R] (the content of which is bin_valuesi [R] (line 06)). Then, the PI waits until it receives a set of values that satisfy the following two properties valuesi.<br>
valuesi ⊆bin_valuesi [R]. Thanks BV- reason attributes, which ensures (even Byzantine AUX false message transmission process [R & lt] () contains only the values proposed by the Byzantine process) valuesi comprising a non-fault handling only by the broadcast values.<br>
Valuesi from at least the value of the message AUX [R] () - different processes (N t) is.<br>
Thus, in any round R, line 07, valuesi⊆ {0,1} and broadcast only the value of a non-fault comprises BV- process line 04.<br>
Stage 3: Try to decide (lines 08-12).<br>
This stage is a purely local computing stage, during which (if not yet complete) trying to determine the PI value b = R 2 mode (line 08 and 10), which depends on the content of valuesi.<br>
If valuesi contains a single element v (line 09), then v becomes the new estimate of the PI. In addition, v is a candidate decision. In order to ensure BBC- agreement, V can be determined only if V = B. This decision is determined by the statement implemented (V) (line 10).<br>
If valuesi = {0,1}, and PI can not be determined. Since this value has been proposed by two non-fault process, cause such convergence protocol, selecting one of them the PI (b, i.e., all non-faulty at the same process) as a new estimated value (line 11).<br>
Let us observe the decision (five) PI does not terminate the call to participate in the algorithm of pi, namely PI continue the endless cycle continues. The algorithm can be used [49] given by randomization techniques terminated. Instead, we keep it simple and to postpone this algorithm in Section 5.5 of uncertainty terminal solutions.<br>
5.3Safety prove	<br>
PI process is a non-fault process, so valuesri predicate satisfied by line 07. In addition, the set of values ​​valuesi, let us recall that in a given operation, C represents a non-fault handling in this run.<br>
Lemma 5 provided T <N / 3. If at the beginning of a round r, all non-fault process has the same estimate V, after which they never change their valuation.<br>
We assume that all non-faulty proof treatment (which at least N - T> T + 1) have the same when they begin estimating v Accordingly a river, they broadcast the same message BV- EST [R] (v) in a line 04 it is the duty BV- BV- reasons and properties, each non-faulty process pi is derived bin_valuesi [R] = {V} in line 05, it is possible to broadcast only the AUX [R] 06. consider any non-fault line processing PI ({v}), then it follows from line 07 predicate (valuesi containing only V), predicate line 09 (valuesi a single), and the dispensing line 10, i.e., the value held ESTI v. 2Lemma 5Lemma 3 Let T <N / 3. (PI, PJ∈C) ∧ (valuesri = {V}) ∧ (value.Proof: PI is provided a process trouble such valuesri = {V}. It follows the same PI message received AUX [R] ({V}) from the line 07-- different processes (N t), i.e., from at least (N - 2T) different non-fault handling. The n - 2 t in ≥t + 1, which means that the PI message received AUX [R] ({V}) from at least (T + 1) of different non-homogeneous set of process failure.<br>
PJ is so fault-free process, such valuesrj = {w}. (- TN) different treatment. Thus, PJ received at least one group from QJ AUX [R] ({W}). Is (n - T) + (T + 1)> N, it follows that Qi ∩QJ = 6∅. Let PK∈ Qi ∩QJ. As PK∈ Qi, this is not a defect of the process. Thus, in line 06, PK send the same message AUX [R] ({}) to pi and PJ, so we have V = Watts.	2Lemma 6Lemma 7. disposed T <N / 3. Value processed by the non-fault decision, made by the process of the non-defective.<br>
Let us prove considering the round R = 1, due to the characteristics of the reasons BV- BV- broadcast line 04, it follows that the set bin_valuesi [1] contains only non Troubleshooting recommended value. Thus, non-fault line 06 during the broadcast message AUX containing the values set by the proposed process only the non-faulty. Then, the predicate it from line 07 (i) as follows (values1i⊆bin_valuesi ), and abstract BVJustification BV- broadcast attributes, such that each set of non-defective values1i process contains only non-defective by the recommendation process values. Thus, ESTI distribution (either in line 10 or 11) provided by the value presented by the non-faulty process. The same principle applies to two R = 2, R = 3, etc., these results prove the lemma.	2Lemma 7
Lemma 8. provided T <N / 3. Two non-fault decision process is not different values.<br>
Let R be a first round proved, during which no fault decision process, so that PI is a trouble-free process, (line 10) determined in a circle R, and v is a value to make its decision. Thus, we have valuesri = {V} where, v = (R modulo 2).<br>
If another non-fault decision process during oxygen PJ wheel, we have valuesrj = {W}, and since Lemma 6, we have W = v. Thus, all non-fault decision process in a stainless steel monovalent, and in the decision v each non-fault decision process has been previously distributed v = (R modulo 2) to its local estimation in a stainless steel monovalent ESTI.<br>
Let PJ is not a flaw, it is not decided in a stainless steel prices. As valuesri = {V}, and PJ is not a value determined stainless steel, it is not always the next Lemma 6 there valuesrj = {1 - V}, so valuesrj = {0,1}. Thus, the circular R, PJ execution pipeline 11, where it is assigned a value (R mode 2) = v to its local estimation ESTJ.<br>
Thus, all non-faulty estimation process begins with the same local v wheel (R + 1) = R MOD 2. Since Lemma 5, they will always maintain this estimate. Accordingly, no process of a different value by the non-defective, the circular R, wherein the proof that the lemma is not yet determined in the determined future rounds. 2Lemma 8<br>
Lemma 9. Let the system model is BAMPn, T [T <N / 3]. No trouble-free process remains blocked in a circle forever.<br>
We have proof by contradiction assume a first round, some non-fault process PI remain forever blocked. Since all non-fault termination process circle (R - 1), they have begun a comprehensive r instance stainless steel price and all calls BV broadcast. Since BV- termination characteristic line 05 wait_until () statement terminates at each process the non-defective. Then, if all non-faulty processing a broadcast message AUX [R] () (line 06), it follows line 07 wait_until () statement terminates at each process the non-defective. Thus, there will always be blocked in the first round during which the non-fault process is still round oxygen. 2Lemma 9<br>
Lemma the system 10. The model is BAMPn, T [T <N / 3]. If all non-faulty process Pi terminate valuesri circle R = {V}, which are determined by the wheel (R + 1).<br>
If all non-faulty demonstrate this process, valuesri = {V}, and r is the circle such that V = (R 2 mode), it follows that (if not already done so) from lines 08-10, one each non-fault handling decide when stainless steel prices.<br>
If r is such that, V 6 = (R modulo 2), which each non-fault current estimation process V (line 10). As the next round, we have: V = ((R + 1) mod 2), and valuesri + 1 = bin_valuesi [R + 1] = {V} in each non-fault process P1, each wheel during non-fault during the decision (R + 1). 2Lemma 10<br>
Lemma 1. Let the system model is BAMPn, T [T <N / 3]. If each non-fault process PI terminates with a circular R valuesri = {0,1}, and it is determined by their circle (R + 2).<br>
If each non-fault proof procedure is such that pi valuesri = {0,1}, line 11 during its execution oxygen circle, we have ESTI = (R-mode 2) = V start wheel (R + 1). Due to Lemma 5, it is always to maintain this estimate. Since all non-faulty procedures to perform round (R + 1) and (R + 2) (Lemma 9) and v = ((R + 2) mod 2), we have the value ofIn each non-fault process P1. Thus, each non-fault line 10 in the decision process.<br>
Theorem 2 satisfy the safety performance of the consensus algorithm described in Figure 2.<br>
Evidenced by Lemma 7 (BBC- potency) and Lemma 8 (BBC- Protocol) is proven as follows.	<br>
It described the decision does not guarantee the decision-making algorithm in Figure 2. While some non-fault process which can occur, for example made 0, other trouble-free process proposed 1, and Byzantine double play during the game, each proposal to 0 or 1 for each process trouble-free, so it will never happen, in a circle all non-faulty process ends either valuesi = {0,1}, or they all have valuesi = {v}, where v is 0 or 1. In other words, if not all of the non-faulty process made the same initial value, the process may be made after the Byzantine round, circular, having a non-fault process valuesi = {0,1}, rather than the rest of the process has a fault valuesi = {v }, where v 6 = (R-mode 2), is determined to prevent them.[]<br>
5.4Eventual synchronization hypothesis	<br>
Consensus impossibilityIt it is known, there is no consensus algorithm to ensure the safety and fully asynchronous messaging system activity, which, even in a single process may crash [24]. Since the collapse of the fault model is less serious than the Byzantine model fails, the process can not reach a consensus, if possible, make Byzantine fault is still the case.	<br>
In order to avoid such a possibility, and to ensure consistent termination properties, the model must be rich with additional computing power. Examples of such power may be set in the input vectors , randomized, or the synchronization is assumed that the fault detector is provided with a , the constraint (see for further development). As the announcement date, we here consider the method of synchronization based on additional assumptions.<br>
Additional synchronization is assumed in the following, it is assumed after a certain limited time [tau], the packet transmission delay upper limit δ. This assumption is a 3Synch (eventual synchrony hypothesis). To take advantage of it by using a timer, we also assume that the process can be accurately measured intervals, although they do not need to have synchronized clocks.<br>
Symbolic model BAMPn, T [T <N / 3] and is represented 3Synch enriched BAMPn, T [t <N / 3,3Synch].<br>
5.5A binary Byzantine consensus algorithm 	BAMPn, T [T <N / 3,3Synch]<br>
In this section, we describe this is to ensure that our binary O to terminate the Byzantine consensus algorithm (t) of the wheel, which is known to be the best . The algorithm described in FIG. 3 in FIG. 2 is extended security algorithms The goal is to add the consensus termination property. The same line with the same number of two algorithms. FIG 3 is a new line number "at the end next", where x is an integer, and the modified line by the "M-'prefix. In addition to using local timer based on the wheel, and ultimately benefit from 3Synch assumptions, which extends round the concept of coordination algorithms used: plays a special role in each round scheduled process of coordinating efforts to impose the value of the other wheel of the decision process . For this purpose, the circular sequentially plays the role of the coordinator in each process . More precisely, the process is set to P1, ..., the PN, the circle r PI coordinator process is such that i = ((R - 1) MOD N) + 1.[]Additional local variables and message types in addition to ESTI, RI, bin_valuesi [R], and valuesi, each process manages the following local variable PI.<br>
timeri a local timer and a timeout value timeouti, both to use assumptions 3Synch.<br>
coordi round is coordinated indicators.<br>
AUXI is a secondary set of values for stored value (if any) is currently coordinating efforts to exert their judgment value.<br>
Circle R coordinator, using message type COORD_VALUE [R] () to attempt to facilitate broadcast its value is a value determined.<br>
Operation bin_propose (VI) is<br>
ESTI ← six; RI ← 0; timeouti ← 0;<br>
While (true) do<br>
RI ← RI + 1;<br>
(NEW1) coordi ← ((RI - 1) MOD N) + 1; timeouti ← timeouti + 1; timeri provided to timeouti;<br>
BV_broadcast EDT [RI] (ESTI);<br>
(NEW2) If (I = coordi) and wait_until (bin_valuesi [RI] = {w}); // w is a value of the first entering bin_valuesi of [the RI] RADIO COORD_ value [RI] (w) of<br>
just in case;<br>
wait_until (bin_valuesi [RI] 6 = ∅) ∧ (timeri expired);<br>
(NEW3) arranged to timeri timeouti;<br>
(NEW4) if (COORD_ value [RI] (W) received from pcoord I) ∧ - (Watts ∈bin_values ​​then AUXI ← {w}<br>
Otherwise AUXI ← bin_valuesi [RI]<br>
just in case;<br>
Broadcast AUX [RI] (AUXI);<br>
wait_until (message AUX [RI] (b_valp (1)), ..., AUX [RI] (b_valp (N- t)) has been received<br>
From the (N - t) different process P (X), 1≤X≤N - t and their content is such that, ∃ valuesi such that a non-empty (i) valuesi⊆bin_valuesi [RI] and (ii) valuesi = ∪1≤x≤n-tb_valx) ∧ (timeri expired);<br>
(New5) if (when considering the entire message of the set of AUX [RI] () received, sets values1i, values2i, ... satisfy the previously waiting predicate) ∧ - (AUXI which is one) then valuesi ← AUXI END IF;<br>
2 ← RI double mold;<br>
If (valuesi = {V}) // valuesi is a single, whose elements v<br>
Then ESTI ← V; if (V = BI) before deciding (V), if not ended, if;<br>
Otherwise ESTI ← double<br>
just in case;<br>
The end of a period of time.<br>
Figure 3: a safe and BAMPn binary Byzantine algorithm consensus site, T [t <N / 3,3Synch]<br>
Description Extended algorithm describes the following items appear in Figure 3 of the new and revised statements.<br>
In line NEW1, PI calculating the current wheel coordinator, and set its local timer, which is used in the predicate of the expiration line M-05. The timeout value is initialized before entering the loop, then rose in every round.<br>
NEW3 line is a timer, whose expiration for a simple reset to the modified line M-07 predicate.<br>
Line NEW2, NEW4, M-06, and New5 implement a mechanism that allows the current round of coordination, trying to impose its bin_values ｓet to enter a judgment of the value of[]. The fact that, after the presence of a time, by a non-fault message exchange process is timely, it will have to ensure that the wheel during this period, the non-faulty process will have a single value in their valuesi sleeve (which binds - 10 required by the lemma their decision).<br>
Modified lines of M-05 and M-07: In addition to the predicate corresponding line considered in timer expires.<br>
As just seen, the idea to start the operation of these new or revised statement is: caused such a decision from the overall coordination of the interests of a defect-free, by requiring the process, so that all non-fault process uses it to play a recommended value. to this end:<br>
Circular coordinate PK broadcast message COORD_VALUE [RI] (W), wherein w is set into its bin_values (line NEW2) the first value. If PK is no fault, the fault-free process timeout value is large enough, and the message transmission delay binding, all non-faulty process will receive the line M-06 before the timer expires.<br>
Then, assuming that the previous item, the set {w} AUXI (line NEW4) all non-fault handling, and broadcasts it (line M-06). W predicate ∈bin_valuesi [RI] for preventing Byzantine coordinator sends the non-faulty process false foil.<br>
Finally, all non-faulty process will receive the message AUX [RI] ({W}) from a - different processes (N t), and set by line New5 valuesi = {w}. This will round (R 1) or (R + 2) means that during their decision.<br>
From asynchronous to synchronous decision-making in order to ensure the final synchronization hypothesis, and after each trouble-free processing time-out value is large enough (that is, than the upper bound messaging big delay), we need to eventually perform all non-synchronized troubleshooting Round . It observed that, since the initial asynchronous, non-fault on the consensus algorithm can process at different times. In addition, due to the potential participants Byzantine process, a number of non-faulty process can be ahead of two, without decisions, and other trouble-free process is still executing the previous rounds. By using a long process times out all round, and ultimately achieve synchronous behavior from their circle.<br>
Lemma 12. We consider the algorithm of Figure 3 will ultimately no faults in the process of synchronization round from their behavior.
3Synch final proofing has an unknown message transmission delay constraint δ. As noted in Section 2, assuming local processing time is equal to zero. (Or, in Appendix B and C do not depend on this assumption is provided with two additional evidence). Hereinafter, description will be given in time units of integers. Subscripts (e.g. tfirst0) will be used to represent the sign of t is elapsed since the beginning of the algorithm have been, observed as measured by the amount of time given the full knowledge of the global viewer G.ģ measurement time unit the same time at least the rate of non-fault processes and events can occur at integer time unit.<br>
We will use the following definitions:<br>
tfirstr as measured by a G in the first time of non-failure process pfirst arrival circle R (tfirst0 time, when the first non-consensus start troubleshooting).<br>
tlastr is the last non-faulty process PLAST arrival circle R (tlast0 is the time when the last non-consensus start troubleshooting) as the time measured by the G.<br>
For a circle is synchronous, all non-fault process must have enough time to get all the news that a timeout before any due process trouble-free broadcast of trouble-free process that round. In this case, the last non-fault is processed in turn reaches the coordinator, which may take up to COORD_VALUE [R] 3 prior to the delay message () message received by all non-fault handling (message comprises up to 2 delayed until a value into its bin_values [r] and the further delayed broadcast message COORD_VALUE [R]. Therefore, we must have a round in which r<br>
tlastr + δ≤tfirstr + timeoutr. (1)<br>
It should be noted that taking into account the time-out from 0 0 round, each by one round of growth, we can replace any one of R timeoutr River<br>
Consider first round timeoutr0≥δ wherein R0 satisfied. R00 R00 wherein for any circle ≥R0 maximum amount of time to complete plastr00 wheel will be 2 × timeoutr00. This is due to the fact, finally trouble-free process in an information circular arrival will not have to wait more than δ longer to accept, to meet on-line M-05 and M-07 to the required conditions, in order to take time to perform the wheel will no more than two timeout length polymorphism. All other non-faulty process requires 2 × timeoutr00 R00 least complete circle.
From a certain round in which R00 process last no defect in time can be written as:<br>
When the first time the process reaches a circle without defects R00 is:<br>
1 block to the results of this inequality points<br>
Remove the equal components, we have:<br>
tlastr0 + 3 × δ≤ tons first [R0 + R00.]<br>
Therefore, through a circular R00 = tlastr0 + 3 × δ - tfirstr0 synchronization is guaranteed.<br>
Now we will show that once inequality (1) satisfies an R00 (which timeoutr00≥δ), it will remain satisfactory in all of the following rounds. Consider wheel R00 + 1, in view of inequality (1) Established in round R00, we have:<br>
tlastr00 + 3 × δ≤tfirstr00 + timeoutr00. (2)<br>
And it needs to prove the following inequality is true:<br>
tlastr00 + 1 + 3 × δ≤ tons first [R00 + 1 + Timeout [R00 + 1 (3)<br>
Using the same parameters as the above process of the first and last times wherein R00 + 1 reaches the wheel has: tlastr00 + 1 = tlastr00 + 2 × timeoutr00 and tfirstr00 + 1≥tfirstr00 + 2 × timeoutr00. This clogging of the inequality (3) results in:<br>
tlastr00 + 2 × timeoutr00 + 3 × δ≤tfirstr00 + 2 × timeoutr00 + timeoutr00 + 1.<br>
Aliquots result in:<br>
tlastr00 + 3 × δ≤tfirstr00 + timeoutr00 + 1.<br>
This inequality, which is equivalent to Inequality (3) having the same components, the inequality (2), except that instead of having timeoutr00 + 1 timeoutr00. Thus, Inequality (3) must be satisfied, because the inequality (2) is satisfied. This is summed up by any one of R00 after real. 2Lemma 12<br>
The 5.6Proof 	3Synch based algorithm<br>
The certificate consists of two parts :( a) show, add statements consistent security proof idle time algorithm in FIG. 2, and (ii) show that all non-faulty final decision process.<br>
Lemma 13. Validity and satisfaction algorithm BBC- BBC- protocol properties as described in FIG.<br>
Proof to prove the lemma proof comprising 5,6, 7 and 8, maintain the correct, these proofs 3 substantially remains the algorithm takes into account FIG correct because, as the new and modified assignment statement does not set bin_valuesi [R] in the non-fault handling, and with a characteristic not bin_valuesi timing hypothesis, non-faulty process can not contain only by the PI process Byzantine recommended value setting bin_valuesi [R]. It follows from this local variables and ESTI observed, any non-fault handling (line M-07, New5,10 or 11 defined or updated) from valuesi may contain only during non-fault value. More specifically, we have the following.<br>
Lemma 5. Let R be considered circular, and v is no fault current estimate of the process. Then, we have bin_valuesi [R] = {V} M-05 line of each non-fault process pi.<br>
If a fault-free round coordination PK, we each non-fault occurred AUXI = bin_valuesi [R] = {V}. It follows then valuesri = {V} and lemma since the line 09 and 10 hold true.<br>
If PK is Byzantine and coordinate round transmittable different values in a non-fault occurred, let us consider the received message COORD_VALUE [R] non-fault handling ({1 - V}). The (1 - v) of ∈ / bin_valuesi [R], online NEW4, PI performed "else" portion, where it is provided to AUXI {V} (unique value of [R] in bin_valuesi), and the following lemma.<br>
Lemma 6, since it does not rely on a timer, and relates only to the fact that valuesri each group and the two non-fault process valuesrj single, still prove effective.<br>
Lemma 7. The following facts prove collection bin_valuesi any non-fault process of troubleshooting can only contain non-recommended value.<br>
Lemma 8. Since it depends only on sets valuesri trouble-free processes, this proof is still correct.<br>
Lemma 14. The algorithm described in Figure 3 ensures that each non-fault decision process.<br>
Prove that we first observed, due to the expiration of the timer always, "wait" statements (revised line M-05 and M07) always terminates, so Lemma 9 is still correct. Readers can also check the proof of Lemma 10 is still valid.<br>
It still indicates that there has rounded R at the final end, which all non-fault handling Pi w have the same value in their set of variables (valuesri = {W}) (from which decides Since Lemma 10) demonstrated shown that, due to the assumed final synchronization (a) in, (b) the wheel coordination mechanism, and (c) the message transmitted by the wheel COORD_VALUE Coordinator , there is a circle R, as valuesri = {w} in each process the non-defective.<br>
Let us consider a time τ from (due to the lemma 12) system behavior synchronous (time-out value of all non-fault process, so that all information provided by non-faulty process of exchange of timely arrival). Let r PK is coordinated by the failure of the process is not after τ minimum number of turns. The circular R, PK broadcast COORD_VALUE [R] line NEW2 (W), a first value is set into its watt bin_valuesk [R] is. Message COORD_VALUE [R] (w) is received by all non-faulty process in a timely manner, to the set {w} AUXI line NEW4. Thus, all non-fault handling broadcast AUX in the M-06 line of [R] ({W}) and the line receiving M-07 in the (N - t) of the AUX [R] ({W}) from a different process message, the line is set to {w} New5 valuesi. By Lemma 10, all non-fault decision process for a W R + 1, wherein the proof of Lemma conclusions drawn. 2Lemma 14<br>
Theorem 3 Algorithm described in FIG. 3 solves the binary system model BAMPn Byzantine agreement, T [t <N / 3,3Synch].<br>
Demonstrate proof directly from Lemma 13 (BBC- validity and BBC- Protocol) and lemma 14 (BBC- followstermination).	<br>
Pointnity Token<br>
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
<br>
System Security<br>
Security pointnity defensive programming language derived from the design of the AVM and strict restrictions on the time, space and resource use. In addition, the security focus will also be provided by scripting language authoring tool. For example, the logical correctness pointnity chain code may, model checking verification and analysis tools provided by conventional bytecode.<br>
pointnity is an open, integrated block chain network and the initial network construction. It provides information on a homemade organization or enterprise developers the basic architecture of the complex technology, greatly reducing development time and cost value, so pointnity is a developer-friendly gathering place.<br>
Block Chain Development<br>
The rapid development of the Internet in recent years, coupled with the strength and depth feedback physical world, has radically altered the production, living and management decision-making model of modern society, the formation of the real physical world - tight coupling virtual network space, interaction and actual situation parallel co-evolution of social space, gave birth to the "Internet +" and 4.0 and a series of national industrial strategy for the future development trend of social network certainly from CPS + actual physical world (Cyber-physical systems, CPS) to spiritual artificial world, forming a physical network + + artificial man - machine - ternary composition integration coupling system, information systems called social physical (Cyber-physical-social systems, CPSS) present, based on parallel societies have gradually taken shape CPSS its core is the actual situation and the essential characteristics of the interaction with the parallel evolution<br>
CPSS block chain is parallel to achieve one of the infrastructure of society, its main contribution is to provide a data structure of a well-established center to a distributed social systems and distributed artificial intelligence research, interaction mechanics and computing models, to achieve parallel and lay a solid social foundation and credit data on the basis of the data base, the management Edward Deming once said: in addition to God, everyone must speak to the data center of the social system, however, the data usually controlled by the government and large enterprises and other "minority" in the hands, a few people "speak", its impartiality, the authority may even security can not be guaranteed. block chain data through highly redundant distributed storage nodes, held by "everyone" in the hands, can do real "data democracy." on the basis of credit terms, its highly centralized system of social engineering complexity and social complexity inevitably there will be "Merton system" characteristics, namely uncertainty, diversity and complexity of social systems in the central institutions and rule-makers may arise due to acts of dishonesty individual interests; the block chain technology Contribute to social systems software-defined, the basic idea is to reject centralized institution, to the unpredictable behavior of the program code in the form of a smart contract early deployment and curing block chain data, and afterwards can not be forged and tampered with automation execution, which to some extent can the "Merton" social systems into a comprehensive observation can be actively controlled, can accurately predict the "Newton" social system .<br>
ACP (artificial social Artificial societies, computational experiments Computational experiments and parallel execution Parallel execution) method is so far the only parallel system into the field of social management, integrated research framework, is a logical extension of the lower complexity of science in parallel with the new era of social environment and innovation. ACP method can naturally be combined with the block chain technology, block chain-driven parallel social management. first, P2P networking block chain, distributed collaboration and consensus based on the contribution of economic incentives and other mechanisms themselves distributed modeling natural social system in which each node in a distributed system as an autonomous agent and self-government (Agent). with the improvement of the ecological system of the block chain, chain blocks each node and the growing consensus complex and intelligent autonomous contract through participation in various forms Dapp, form a particular form of organization and the DAO DAC, ultimately the DAS, i.e. ACP artificial society. Secondly, the programmable characteristics of contracts intelligent block chain such that each may be species "WHAT-IF" type of virtual experimental design and evaluation of results deduced scenario, this calculation experimented Obtain and automatically or semi-automatically execute optimal decision. Finally, the block chain with a combination of things such as intelligence assets, which makes China Unicom real physical world and the virtual network space as possible, and through real and actual situation interaction and artificial social systems parallel tuned achieve synergies and optimize social management decision-making is not hard to foresee the future of the real physical world of physical assets are registered as chain intelligence assets when the time is approaching block chain-driven parallel society.ACP (artificial social Artificial societies, computational experiments Computational experiments and parallel execution Parallel execution) method is so far the only parallel system into the field of social management, integrated research framework, is a logical extension of the lower complexity of science in parallel with the new era of social environment and innovation. ACP method can naturally be combined with the block chain technology, block chain-driven parallel social management. first, P2P networking block chain, distributed collaboration and consensus based on the contribution of economic incentives and other mechanisms themselves distributed modeling natural social system in which each node in a distributed system as an autonomous agent and self-government (Agent). with the improvement of the ecological system of the block chain, chain blocks each node and the growing consensus complex and intelligent autonomous contract through participation in various forms Dapp, form a particular form of organization and the DAO DAC, ultimately the DAS, i.e. ACP artificial society. Secondly, the programmable characteristics of contracts intelligent block chain such that each may be species "WHAT-IF" type of virtual experimental design and evaluation of results deduced scenario, this calculation experimented Obtain and automatically or semi-automatically execute optimal decision. Finally, the block chain with a combination of things such as intelligence assets, which makes China Unicom real physical world and the virtual network space as possible, and through real and actual situation interaction and artificial social systems parallel tuned achieve synergies and optimize social management decision-making is not hard to foresee the future of the real physical world of physical assets are registered as chain intelligence assets when the time is approaching block chain-driven parallel society.<br>
PONT token rules and Legal Notices<br>
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
Name:<br>
Sex:<br>
Nationality (does not support the United States, Australia area、china):<br>
date of birth:<br>
ID card / passport / driver's license:<br>
ID Photo:<br>
Proof of bank card statement, utility bill payment, property receipts identity information:<br>
Number of intended contributions(ETH):<br>
Risk Warning: Potential contributors should independently evaluate their preferences for these risks, and decided to consult with their advisor before making any contribution to the POI tokens.<br>
Token Rule:<br>
A total of 5 billion tokens<br>
  pre-sale: 5%<br>
Official ratio: 1: 35000(note: Pre-sale contributors lock-in rules, 50 immediately after the exchange is available, and the remaining 50% is released for 6 months on the online exchange.)<br>
Sale: 15%<br>
Official ratio: 1: 23000(note: the sales contributor releases 50% of PONTs immediately after the exchange, and the remainder is released after 3 months of trading.)<br>
 Team 35: technical development and operation awards for team members(note: team lock-in is released in linear equilibrium within 24 months after 12 months on the exchange, once every two months, for a total of 12 releases.)<br>
Cooperation Organization 25: use it for ecological incubation, expand the radiation scope of the project, and establish beneficial and good cooperation(note: depending on the circumstances, the minimum time limit for the release and locking of the cooperative organization's tokens is 6 months.)<br>
Community 20: to provide advice on community operations, maintain and build a good community environment, you can receive token awards.(note: community escrow release and lock-in, depending on the circumstances, lower limit of unlocked time)<br>
This token is a ERC-20 token and will be replaced by 1:1 tokens on the main network<br>
In conclusion<br>
With the strong rise of digital encryption to Bitcoin currency as the representative of an emerging block chain technology has become the hot research topic in academia and industry. Credit to the center of the block chain technology can not be tampered with and programmable features so that it has a wide range of applications in digital encryption monetary, financial and social systems. However, compared with the block chain booming business applications, theory and technology research foundation block chain is still in its infancy, and many more the essential, vital to the development of the industry chain block scientific issues that must be follow-up study. This paper systematically reviews the basic principles of the block chain technology, techniques, methods and applications in order to provide useful inspiration and reference for future research .<br>
PointnityIs a compatible open network, ITheyI believe that his appearance will truly enhance the further development of blockchain world. Here, we sincerely hope that more people will participate in the construction blockchain world has made blockchain contribute to the construction of the world.<br>
PONT token rules and Legal Notices<br>
Please note that this is not any type of investment Description<br>
This document does not constitute any form of prospectus; it is not a solicitation to invest, not in any way involve the provision of securities in Canada or the United States, and Canada and the United StatesAs well as China'sResidents are expressly excluded any PONT exchange token donation in public products.<br>
DISCLAIMER:<br>
This site is for reference only. POINITY and all related companies and affiliates do not guarantee the accuracy of the conclusions reached by this site "as is" without any express or implied representations and warranties, including, but not limited to:<br>
Warranties of merchantability, for a particular purpose, or non-infringement of ownership;<br>
Contents of this website without any errors or for any purpose;<br>
Such Content will not infringe rights of third parties. All ensure clear sound. POINITY and its subsidiaries expressly disclaims any form of liability and damages resulting from the use, reference or reliance on information contained on this website caused, which we are not responsible.<br>
Recipients specific notice as follows:<br>
• does not provide any securities: PONT token (such as the POINITY white paper) is not intended to constitute securities in any jurisdiction. This site does not constitute a prospectus, nor does it provide any form of document, nor does it constitute an offer or solicitation of securities or any other investment product or any other jurisdiction.<br>
• No suggestion: POINITY this website does not constitute a recommendation to any PONT exchange token, should not rely on any contract or contribution decision.<br>
• No, said: Recipient or its advisers did not cause on this website, or contain information, statements, opinions or issues derived (expressed or implied) or the accuracy or completeness of any omission in this document or to make representations or warranties now or any other future available to any written or oral information or advice about the party or its advisers. For any plan or predict the future prospects of achievement or reasonableness makes no representations or warranties Nothing in this document should not be considered for future commitments or statements. To the maximum extent.<br>
• Donation: We only accept certified by KYC DonateDETAILED format by KYC<br>
Name:<br>
Sex:<br>
Nationality (does not support the United States, Australia area、china):<br><br>
date of birth:<br>
ID card / passport / driver's license:<br>
ID Photo:<br>
Proof of bank card statement, utility bill payment, property receipts identity information:<br>
Number of intended contributions(ETH):<br>
Risk Warning: Potential contributors should independently evaluate their preferences for these risks, and decided to consult with their advisor before making any contribution to the POI tokens.<br>
Token Rule:<br>
A total of 5 billion tokens<br>
  pre-sale: 5%<br>
Official ratio: 1: 35000(note: Pre-sale contributors lock-in rules, 50 immediately after the exchange is available, and the remaining 50% is released for 6 months on the online exchange.)<br>
Sale: 15%<br>
Official ratio: 1: 23000(note: the sales contributor releases 50% of PONTs immediately after the exchange, and the remainder is released after 3 months of trading.)<br>
 Team 35: technical development and operation awards for team members(note: team lock-in is released in linear equilibrium within 24 months after 12 months on the exchange, once every two months, for a total of 12 releases.)<br>
Cooperation Organization 25: use it for ecological incubation, expand the radiation scope of the project, and establish beneficial and good cooperation(note: depending on the circumstances, the minimum time limit for the release and locking of the cooperative organization's tokens is 6 months.)<br>
Community 20: to provide advice on community operations, maintain and build a good community environment, you can receive token awards.(note: community escrow release and lock-in, depending on the circumstances, lower limit of unlocked time)<br>
This token is a ERC-20 token and will be replaced by 1:1 tokens on the main network<br>
In conclusion<br>
With the strong rise of digital encryption to Bitcoin currency as the representative of an emerging block chain technology has become the hot research topic in academia and industry. Credit to the center of the block chain technology can not be tampered with and programmable features so that it has a wide range of applications in digital encryption monetary, financial and social systems. However, compared with the block chain booming business applications, theory and technology research foundation block chain is still in its infancy, and many more the essential, vital to the development of the industry chain block scientific issues that must be follow-up study. This paper systematically reviews the basic principles of the block chain technology, techniques, methods and applications in order to provide useful inspiration and reference for future research .<br>
PointnityIs a compatible open network, ITheyI believe that his appearance will truly enhance the further development of blockchain world. Here, we sincerely hope that more people will participate in the construction blockchain world has made blockchain contribute to the construction of the world.<br>
