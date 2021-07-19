# Cache Simulator

**Note**: the memory address are read from a separate text file, make sure the file is in the same directory and give the name of file as input in the command line when prompted.

This cache simulator can simulate the following replacement policies:

- Random Replacement policy
- LRU Replacement policy
- Tree base pseudo LRU replacement policy

The following cache mappings are supported:

- direct-mapped
- fully-associative
- set-associative 

### **C****ommand line input f****ormat:**

&lt;Cache Size&gt;

&lt;Block Size&gt;

&lt;Associativity&gt;

&lt;Replacement Policy&gt;

&lt;file name containing memory traces&gt;

### **Output format: (STDOUT)**

&lt;cache Size&gt; #Cache size

&lt;block Size&gt; #Cache line size

&lt;Associativity&gt;

&lt;Replacement Policy&gt;

&lt;Cache accesses&gt; #Cache accesses

&lt;Read accesses&gt; #Read accesses

&lt;Write accesses&gt; #Write accesses

&lt;Cache misses&gt; #Cache misses

&lt;Compulsory misses&gt; #Compulsory misses

&lt;Capacity misses&gt; #Capacity misses

&lt;Conflict misses&gt; #Conflict misses

&lt;Read misses&gt; #Read misses

&lt;Write misses&gt; #Write misses

&lt;Dirty blocks evicted&gt; #Dirty blocks evicted

## Team Members:

Mandala Tejesh - CS19B062

Madhav Mittal - CS19B029

Kshitij Raj - CS19B061
