# epimoric

I name this repository 'epimoric', which is synonymous with 'super-particular'.  It signifies proportions or ratios or fractions composed of positive integers where  (x+1) : x  OR  (x+1) / x .  Examples are 2:1, 3:2, 4/3, 5/4, etc.  I feel Claudius Ptolemy correctly surmised this wisdom: that all of harmony and the very foundation of consonance are rooted in epimoric proportions...


This repository collects and releases to the public my own software and any supplementary, educational materials.  The software allows one to compose microtonal scales from pitch intervals which are epimoric proportions or derived therefrom.  It also allows one to directly compose scales with the same ratios.  Both means produce a Scala tuning file (.scl) with which I produce in modern, digital audio workstations music NOT tuned to the conventional standard of equal temperament.  Microtonality is possible in Bitwig Studio, Ableton Live and possibly other digital audio workstations with the use of a Scala tuning file in addition to defining the root ( i.e. 'tonic' ) key of the composition.


Why did I code this in the Wolfram Language?  Because when I do, I do well.  A programming language that discretely converts my positive-integer ratios to floating point numbers and then does floating point arithmetic on them and then discretely converts them back to seeming positive-integer ratios is like SLAPPING ME IN THE FACE WHILE CALLING ME STUPID.  The nature of these calculations necessitate a programming language with native, RATIONAL VARIABLE TYPES IN ADDITION TO PURE, RATIONAL ARITHMETIC AND IN COMPLETE ABSENCE OF ANY FLOATING-POINT ARITHMETIC.  I had therefore only two choices: Julia or Wolfram Language.  I chose Wolfram for the maturity and robustness of functionality, despite its not being an open-source option.  It is a damned fine tool, and the best one for the job.  Again, when I do, I do well.


All of this is released to you, and to anyone, under a 'free NOT fee', open source license of my own creation which legally stipulates that any and all are free to consume, modify, copy, distribute, download, and enjoy so long as: 


          1. I am accredited with the sole authorship and ownership of the versions of this code which I release in this repository.  My email address ( 
             xorxecor@gmail.com ) and name must be included in a legal notice of ownership / authorship. 
          
          2. No money is exchanged in connection to this software.  One may not commercialize this code, sell it, profit financially by it or from it.     
             Financial loss caused by the use, distribution, etc. of this software is, however, not only acceptable, but perhaps even desirable and 
             honorable...   ;-)
             
             
Enjoy!


Frank O'Neill
