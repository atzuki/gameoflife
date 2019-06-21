# gameoflife

   Welcome to an educational project to provide adaptations of the aritifical intelligence algorithm, Game of Life (or simply Life), orignially developed by John Horton Conway. Newcomers have a chance to learn about the principles of Life and aritificial intelligence (AI) by executing or modifying the code. This document is structured as follows:

I. Getting Started

II. Introduction to the Principles of Life

III. Suggested Applications

============I. Getting Started============

Visual Basic for Applications (VBA)
   a. Create a new workbook and select an empty worksheet. The Life algorithm will display output in the cells of the worksheet.
   
   b. Go to the Developer tab and open the VBE (Visual Basic Editor).
   
   c. Create a new module, then copy and paste the code in the Main file into the module. 
   
   d. Execute the code by pressing the Play button in the VBE.
   
   e. View the pattern output of the algorithm expressed as a 20X20 array of cells containing 1s and/or 0s in the selected worksheet.
   
C++

Comming soon...

============II. Introduction to the Principles of Life============

Life simulates cellular behavior observed in nature by automating the production of cellular patterns according to three principles: 

1) If a cell is in state 1 at time t and has exactly two (no more, n less) of its neighbors also in state 1 at time t, then at time t+1 it will remain in state 1.

2) Whatever the state of a cell at time t, if exactly three (no more, no less) of its eight neighbors are in state 1 at time t, then at time t+1 it will be in state 1.

3) For any other situation at time t, then at time t+1 the cell will be in state 0.
   
   (Source: Artificial Intelligence: The Basics, Kevin Warwick, 2012)
   
============III. Suggested Applications============

Since Excel has been installed on many computers, the VBA version of life is a convenient method for running various cellular pattern simulations. Parameters such as the the intial values in the cells, the size of the cell array and the number of iterations can be altered to change the pattern output. Through successive simulations, users can try to optimize the persistence or complexity of patterns or simply enjoy the experience. Other principles for cellular automation can be tested by modifying the code. There are mulitple possibilities for users to explore!
