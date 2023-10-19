# Assignment-4-Template
nitialization of VMA_ITERATOR:
Used the mm_struct to initialize the VMA_ITERATOR for iterating through the VMAs.

Iteration through VMAs:
Replaced the while loop with the for_each_vma macro to iterate through each VMA.

Memory Statistics Computation:
For each VMA, we iterated through its pages.
Updated the memory statistics (RSS, SWAP, and WSS) based on the pte_present and pte_young flags of each page.
