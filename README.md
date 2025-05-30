Download link : https://programming.engineering/product/cs240-assignment-solution/

CS240 Assignment Solution
At the top of this page is the URL to the assignment guidelines for CS240, it can also be found from the course webpage from the Assignments tab. Please answer the following questions about the assignment guidelines:

    If an assignment question asks you to design an algorithm, what are the three other things you must do in addition to describing/writing the pseudocode for the algorithm?

        describe the main idea first in words

        justify correctness

        analyze the algorithm

    For programming questions, what programming language do you have to use? To what system should you upload your code?

Programming questions must be done in C++, Marmoset is where the code should be submitted.

    Mathematics

In CS 240, you will be using many mathematical concepts. It is important to be able to

typeset mathematics in your assignments. This will include sums, fractions, subscripts &

superscripts, etc.

Example:

Proof: Let n ≥ 1, by definition of summation we know that

n

i = 1 + 2 + … + n − 1 + n

i=1

From the set 1, 2, …, n − 2, n − 1 we will create pairs (k, n − k), where k is some positive integer. Therefore we can rewrite our summation as:

n

i = (1 + n − 1) + (2 + n − 2) + … + n

i=1

There is a total of n−21 pairs, each of which add up to n. Thus our summation becomes:

n i = n −2 1(n) + n

i=1

n i = n +2 1(n)

i=1

Proving the identity as required.

    Trees

CS 240 introduces many tree data structures. Here is a BST on six letters of the alphabet. Insert the first three letters of your first name into the tree (if your first name is shorter than three letters, simply insert all the letters), starting with the first letter of your name. If you are inserting duplicate letters:

    Find the largest index of the letter you are inserting.

    Insert your letter, with an index one larger than the index you found.

    When comparing to an equal value, break the tie according to the index.

For example, if you were to insert an ‘M’ into the tree below, it would be entered as M1 and it would become the left child of T0. Only show the resulting tree.

        		

        M0
        	
        	

        I0
        		

        T0

        C0
        	

        I1
        	

        R0
        	

        W0

        B0
        		

        O0
        	

Hint: For nodes with only one child, you should use “child[missing]” for the non-existent child to keep the binary search tree looking appropriately.

    Plots

CS 240 also deals with many graphs and plots. Plot the following points below, the first one has already been done for you. Only show the resulting plot. Points: (2,7), (7,1), (4,5), (1,3), (3,2), (6,6), (0,9), (9,8), (8,0), (5,4)

9

(0, 9)

(9, 8)

(2, 7)

(6, 6)

(4, 5)

(5, 4)

(1, 3)

(3, 2)

(7, 1)

(8, 0)

    				
    				
    				

For this question, include an image of the animal you added to the table in Q5 along with a caption (see example below).

Figure 1: Funny Dog.

Hint: (figure is a floating environment that gets put where it nicely fits the page layout. The optional argument says which positions are acceptable for the float: top/bottom of a page, here, and on a separate page of floats.)

5
