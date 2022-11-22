#KEY GENERATION AT PHYSICAL LAYER

This is a group Project done to test the generation of Symmetric keys at physical layer. We used RSSI values to calculate disturbances during a data transmission in presence of attacker. The files attaker , Alice ,Bob uploaded in the repository were which were used for comparison and key generation and comparison for intrusion detection. 

We first find the hamming code for each RSSI with respect to attacker and the find out the entropy.
If entropy is near to 0.5 it is very less likely that there is an intrusion. But if value goes on increasing or decreasing from 0.5 there is high possibility of intrusion.

Once we get the hamming distance we use key generation techniques using cascade and checking down the integrity of files after using cascade and generating a key and comparing the entropy and again.

The resulting keys and cascading methods will show how the keys work against attacker preventing it from gaining access to the files.