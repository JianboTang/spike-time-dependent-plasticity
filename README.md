Spike time dependent plasticity
-----------

The program strengthens the relevant synaptic weight when a presynaptic spike precedes postsynaptic firing, and weakens the relevant synaptic weight when a presynaptic spike follows postsynaptic firing. The amount of synaptic weight modification is greatest if the magnitude of the difference between the timing of the pre and postsynaptic spike is small, and decreases exponentially as this difference gets larger. No modification happens if the difference between spike timings of two connected neurons is larger than 20 ms. 
This mechanism is based on the following idea. It is unlikely that a presynaptic action potential which followed postsynaptic firing has affected the postsynaptic firing at all (especially if immediately after), while it is logical that a presynaptic action potential preceding postsynaptic firing has played a significant role in causing the postsynaptic spike (especially immediately earlier). The program does not create or eliminate synaptic connections, it simply modifies existing synaptic weights.
