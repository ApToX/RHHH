# RHHH
Implementation of the ""Constant Time Updates in Hierarchical Heavy Hitters" paper, ACM SIGCOMM 2017

/******************************************************************************************************************************/

This is an open source implementation of the "Constant Time Updates in Hierarchical Heavy Hitters" paper,
published in ACM SIGCOMM 2017, by Ran Ben Basat, Gil Einziger, Roy Friedman, Marcelo Caggiani Luizelli, and Erez Waisbard.

Grisha Weintraub, Chen Mordekhay, and I (Amit Binenfeld) used the implementation of the algorithms by Ran Ben Basat (sran[at]cs.technion.ac.il) and the scripts for running, analyzing, and plotting the data by Tommy Fan and Austin Poore [(GitHub-Link)](https://github.com/lechengfan/RHHH). By combining both resources we tried (successfuly) to re-create figures 2-5 from the paper.


The code here contains the implementation of the researchers RHHH and 10-RHHH algorithms and Tommy Fan's and Austin Poore's implementation the parsing and ploting scripts.
For the algorithms they compared to (MST, Partial Ancestry and Full Ancestry), please refer to Thomas Steinke's implementation (http://people.seas.harvard.edu/~tsteinke/hhh/).
