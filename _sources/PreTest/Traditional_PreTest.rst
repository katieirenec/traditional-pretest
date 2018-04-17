=========================
Multiple Choice Pre-Test
=========================

.. Here is were you specify the content and order of your new book.

.. Each section heading (e.g. "SECTION 1: A Random Section") will be
   a heading in the table of contents. Source files that should be
   generated and included in that section should be placed on individual
   lines, with one line separating the first source filename and the
   :maxdepth: line.

.. Sources can also be included from subfolders of this directory.
   (e.g. "DataStructures/queues.rst").

Introduction
:::::::::::::::::::::::
//insert introduction text blurb here//



Multiple Choice
---------------

.. timed:: pretest-mc_timed
    :timelimit: 30
    :nofeedback:

    .. mchoice:: pre5
        :correct: b
	:answer_a: 3
	:answer_b: 4
	:answer_c: 7
	:answer_d: 0
	:answer_e: Nothing is printed.

	Consider the following code:
	
	    .. code-block:: python
	    
	    	x = 3
	        y = 4
	        x = y
	        y = 7
	        print(x)

	What will be printed?


    .. mchoice:: pre1
        :correct: c
        :answer_a: A
        :answer_b: B
        :answer_c: C
        :answer_d: D
        :answer_e: Nothing is printed.

        Consider the following code:

	    .. code-block:: python

	        if a > 0 and b > 0:
	            if a > b:
		        print("A")
   	            else:
		        print("B")
	        elif b < 0 or a < 0:
   		        print("C")
	        else:
    		        print("D")

        What is printed when **a is 3**, and **b is -2**?

    .. mchoice:: pre2
	:correct: d
	:answer_a: [12, 9, 8, 4, 3, 6, 11, 1, 7]
	:answer_b: [12, 9, 7, 8, 4, 6, 11, 1, 3]
	:answer_c: [12, 9, 7, 4, 3, 6, 11, 1, 8]
	:answer_d: [8, 4, 3, 6, 11, 1, 12, 9, 7]
	:answer_e: [1, 11, 6, 12, 9, 7, 8, 4, 3]

	Consider the following code:

	    .. code-block:: python

		list = getInputList()
		n = getNValue()

		for k in range(0, n):
			item = list[0]
			del list[0]
			list.append[item]

		print(list)

	Assume that the input collected by **getInputList()** is [12, 9, 7, 8, 4, 3, 6, 11, 1]. What is printed if the value of n is 3?


    .. mchoice:: pre3
        :correct: a
	:answer_a: I
	:answer_b: II
	:answer_c: III
	:answer_d: IV
	:answer_e: V

	Consider the following segments of code.

	**I**
	    .. code-block:: python 

		arr = getInputList()
		isEven = false
		for x in arr:
		    if x % 2 == 0:
		        isEven = true
		print(isEven)

	**II** 
	    .. code-block:: python

	        arr = getInputList()
	        isEven = false
		for x in arr:
		    if x % 2 != 0
		        isEven = false
		    else:
		        isEven = true
	        print(isEven)

	**III**
	    .. code-block:: python 

		arr = getInputList()
		isEven = false
		for x in arr:
		    if x % 2!= 0:
		        isEven = false
		    print(isEven)

	**IV**
	    .. code-block:: python

		arr = getInputList()
		isEven = true;
		if x % 2 != 0:
		    isEven = false
		else:
		    isEven = true
		print(isEven)

	**V**
	    .. code-block:: python

		arr = getInputList()
		isEven = true
		for x in arr:
		    if x % 2 == 0:
		        isEven = false
		    else:
			isEven = true
		print(isEven)

	Which piece of code prints **true** if all items in the list are even numbers?

    .. mchoice:: pre4
        :correct: a
	:answer_a: I only
	:answer_b: II only
	:answer_c: III only
	:answer_d: I and III
	:answer_e: II and III

	Consider the following code:
	    .. code-block:: python

		if value < 0 or value > 100:
		    print("Not in range")
		else:
		    print("In range")

	Which of the following code segments will have the same behavior as the original code version above?

	**I.**	
		.. code-block:: python 

			if value < 0:
			    if value > 100:
				print("Not in range")
			    else:
				print("In range")
			else:
			    print("In range")

	**II.**	
		.. code-block:: python

			if value < 0:
			    print("Not in range")
			elif value > 100:
			    print("Not in range")
			else:
			    print("In range")

	**III.**
		.. code-block:: python

			if value >= 0:
			    print("In range")
			elif value <= 100:
			    print("in range")
			else:
			    print("Not in range")




When you are finished answering all of the questions, click the **Finish Exam** button.




