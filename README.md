FastGeneralizedSuffixArrays
============
Version 0.1
[markmaz.com](http://wwww.markmaz.com)


A generalized Karkkainen-Sanders implementation in Python for building suffix arrays and trees for many strings in O(n)


Roadmap
-------
(Further scaling exploration (perhaps introduction of Maniscalco and Puglisi, cython porting, distributed implementation, etc) to be attempted in 1.x)

* <b>0.5</b> Optimizations of existing code based on profiling results
 
* <b>0.4</b> Library consolidation/cleanup for importability. Profiling at memory/swapping levels. 

* <b>0.3</b> Building suffix trees from suffix arrays - O(n) naturally

* <b>0.2</b> Adding LCP/log(n) suffix lookups and generalization code (currently to be done by concatenating strings together, separated by monotonically increasing negative numbers)

* <b>0.1</b> Initial Release: Rough and rapid protoyping of algorithm guts to spit out a suffix array for an ASCII/maybe UTF-8 string. Silly long variable names provide a quick mapping to [the algorithm description](http://www.cs.helsinki.fi/juha.karkkainen/publications/jacm05-revised.pdf)

Contact me for any suggestions/additions/corrections/requests: mark at markmaz.com

