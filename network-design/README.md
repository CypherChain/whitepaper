# Network Design

Consensus mechanisms like PoW and PoS are usually classified as the “proof-class” mechanisms, in which once the calculated value is within the target range, a new block is produced. PoE is also a kind of proof-class mechanism. To model PoE, we first present the abstract definition of a consensus mechanism for the blockchain. The proof-class consensus mechanisms, as shown in Figure 1. In Figure 1, the consensus mechanism extracts the key attributes from the existing blocks as the basis for the computation, and when the computation results in a certain target solution, a new block is produced.

![](<../.gitbook/assets/network design.png>)

Under a proof-class consensus mechanism, a new block is produced if and only if it follows the inequality:

$$
Calculation ( ) < Target X Attribute ( )
$$

Calculation ( ) represents the calculation for a solution, target represents the solution target, and Attribute ( ) represents the key attributes of network nodes for the “proof,” such as computing power in PoW and coinage in PoS; note that some of the attributes are recorded in the blockchain ledger.

