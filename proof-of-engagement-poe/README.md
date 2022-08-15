# Proof of Engagement {PoE}

Since PoE is not just one algorithm from game theory, but a solution space achieved by combining different models into a solution that best fits the current state of the chain, there is a need for both flexibility and evolution in the implementation. Given this, we propose to construct PoE via multiple Smart contracts, with clearly defined interfaces and a clean composition model. This will allow us to adjust individual contracts, swap out implementations, and even rewire the composition model as we explore the PoE solution space.

We propose to get to a working foundational PoE implementation with the following roadmap, where each stage builds on the last:

{% code overflow="wrap" lineNumbers="true" %}
```
// Controlling validator set with a privileged contract
// Implement PoE via modified multisig contracts
// Bootstrapping
// Implement PoS via token-locking contract
// Distribute rewards to validators (Rewards per block)
// Manage Slashing feedback when evidence is submitted, slashing done in contract
// PoE as mixer implementations
// Governance control and voting power
```
{% endcode %}

![](<../.gitbook/assets/POE Implementation.png>)
