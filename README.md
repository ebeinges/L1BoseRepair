This is a quick journal of the steps I am going through to try and fix the L1 BOSE system I use.

This is all based on the pages at https://lensprojects.com/2016/08/25/bose-l1-repair/

I documented the disassembly with these diagrams:
![Showing main right side connections](/images/BoseL1-disassemblyA.JPG)
![Showing main right side connections](/images/BoseL1-disassemblyB.JPG)
![Showing main right side connections](/images/BoseL1-disassemblyC.JPG)
![Showing main right side connections](/images/BoseL1-disassemblyE.JPG)
![Showing main right side connections](/images/BoseL1-disassemblyD.JPG)

These are the photos for pulling out the Aux Power board:
![Pulling the Aux Power board](/images/BoseL1-pulling-aux-board1.jpg)
![Pulling the Aux Power board](/images/BoseL1-pulling-aux-board2.jpg)
![Pulling the Aux Power board](/images/BoseL1-pulling-aux-board3.jpg)
![Pulling the Aux Power board](/images/BoseL1-pulling-aux-board4.jpg)


With the AUX power board pulled, I started checking the diodes.

Found that D606 measured as an open circuit.

Also found that measuring accross the +15V power pins measured open.

Think we found the culprit.

Ordered Digikey part # 497-3216-1-ND from https://www.digikey.ca/ to have a replacement handy.

![Measuring the AUX board](/images/BoseL1-measureAuxBoard.jpg)

Next step is to remove the bad Diode.


