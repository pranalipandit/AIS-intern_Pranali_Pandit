Task_1
 1. Numbers in Python
    - (Integer, Folat, Complex) Perform basic arithmetic operations like addition, subtraction, multiplication, and division.
 2. Operators in Python
    - (Discuss arithmetic, comparison, logical, and assignment operators and Perform operations )
 3. Lists in Python
    - (Perform i.Accessing elements: Use indexing and slicing   ii.Modifying elements: Change the value of an element by index.  iii.Adding elements: Use append(), insert().   iv.Removing elements: Use remove(), pop(), or clear().
       v.Other methods: Use sort(), reverse(), extend(), count(), index(), and copy())
 4. Tuples in Python
    - (Perform  i.Accessing elements: Use indexing and slicing.   ii.Slicing: Extract a portion of the tuple.    iii.Concatenation: Combine two tuples using +.  iv.Repetition: Repeat a tuple using *.                                     
       v.Count: Count occurrences of an element with count().       vi.Index: Find the index of an element using index())

 5. Sets in Python
    - (Discuss set operations (e.g., adding elements, removing elements, union, intersection, difference).Perform methods like add(), remove(), union(), intersection(), difference())

 6. Dictionaries in Python
    - (Discuss dictionary operations (e.g., accessing key-value pairs, adding, and removing items). Perform methods like get(), keys(), values(), items(), pop(), update())

 7. Common Python Errors
    - (i.IndentationError: Explain the cause and show how to fix it.    ii.NameError: Discuss the cause and provide a fix.    iii.ValueError: Explain what causes this error and how to avoid it.
      iv.TypeError: Describe the reason for this error and how to handle it.    v.IndexError: Discuss the cause of accessing out-of-range indexes.
       vi.KeyError: Explain how accessing non-existent keys causes this error and ways to handle it.


Task_2
 1. If-else
- (i).grade code
p=50
O: p>75
A : 60 < p>75
B: 50<p<60
C: 35<p<50
fail:p<35

 - ii)n divisible by 2 or 3
n=7
2 divisble, 3 not
divisible by 2,and 3
divisible by 3, not 2
not divisible by 2, and 3

- (iii) Any other 5 Example each…. 
If 
If else
If elife else

2. For loop
   (i.print odd value between 20 and 80, without using if. Using for loop only.   ii.creat a list of 1 to 20 number using for loop [1,2,3..20]
   iii.create a  list of 20 to 1 value using  for loop (dont Use Reverse) 20,19,18,...3,2,1]     iv.take Cube of odd values between 20 to 40
   v.take 5 freinds name in list name=[a,b,c,d,e]
take corresponding ages in second list age = [20,21,23,25,24]
expected ans:
    my name is a , my age is 20
    my name is b, my age is 21
  

3. Solve Using if and for loop  and data types methods ; 
  (i.Given a list, write a Python code  to swap first and last element of the list.     ii.write code count lenght of string
   iii.Write a Python program to get the sum of a only non-negative integer. ex, [1,4,-5,-20,10] ans is 15             iv.write code of factorial , ex.ans 6 (3*2*1)

4. While Loop
  (i.odd-even using while loop                                                 ii. using while cteate loop
    iii. creat list 1-20 numbers list using while loop=> [1,2,3... 20]            iv.  creat list 20-1 (revers order) using while loop=> [20,19...1]             v. try with one any eg. break, contnue , pass control statement


Task_3
   User define function 
   - (1)Write a Python function to find the maximum of from given        2)Write a Python function to sum all the numbers in a list.  Sample List : [8, 2, 3, 0, 7] Expected Output : 20
    
     3)Write a Python function that takes a list and returns a new list with distinct elements from the first list.  Sample List : [1,2,3,3,3,3,4,5] Unique List : [1, 2, 3, 4, 5]
    
     4)Write a Python function total number of  Combinations. Ex. a,b,c  Ans: 4 : ab,ac,bc,ac
    
     5)Write a Python function total number of  permutation Ex. a,b,c Ans: 6 : ab,ac,ba,bc,ca,cb
    
     6)Exercise 5: Define a function which counts vowels and consonant in a word.   input :  statistics 
        Expected output : Count of vowel is = 3 Count of consonant is = 7
    
     7)Define a function that accepts lowercase words and returns uppercase words.      Input:= statistics 
         Expected output  Result is = STATISTICS
    
     8)count lower case and upper case  letter.   Ex : STatiStiCS
          Ans: upper case :5            Lower case: 5


Task_4 
   Machine learning 
 1. Introduction to NumPy
What NumPy is and why it’s important for numerical computations in Python.
Installation of NumPy (pip install numpy).
Understanding its role in data science, machine learning, and scientific computing.

 2. Arrays in NumPy
Understanding the concept of ndarray (N-dimensional array).
Creating arrays using np.array(), np.zeros(), np.ones(), np.arange(), and np.linspace().
Array indexing and slicing.

 3. Array Operations
Arithmetic operations on NumPy arrays (addition, subtraction, multiplication, division).
Broadcasting (performing operations on arrays of different shapes).
Element-wise operations and functions (e.g., np.sqrt(), np.sin(), np.exp()).

 4. Array Shapes and Reshaping
Checking array dimensions with .shape and .ndim.
Changing array shape with .reshape(), .flatten(), .transpose().
Concatenating and splitting arrays using np.concatenate(), np.vstack(), np.hstack(), np.split().

 5. Array Manipulation
Indexing and slicing: understanding multi-dimensional arrays.
Masking (logical indexing based on conditions).
Fancy indexing (using arrays of indices to select elements).

 6. Mathematical Functions
Universal functions (ufuncs) like np.add(), np.subtract(), np.multiply().
Statistical functions: np.mean(), np.median(), np.std(), np.var(), np.min(), np.max().
Linear algebra functions: np.dot(), np.matmul(), np.linalg.inv(), np.linalg.eig().

 7. Random Number Generation
Generating random numbers using np.random (e.g., np.random.rand(), np.random.randint()).
Seeding random number generation (np.random.seed()).
Random sampling, shuffling, and permutations.

 8. Broadcasting
Understanding how NumPy handles operations between arrays of different shapes.
Rules of broadcasting (e.g., matching dimensions, aligning axes).

Task_5
 1. Introduction to Pandas
 2. Key Data Structures:
 3. Series: 1D labeled array
 4. DataFrame: 2D labeled table.
 5. Creating Data Structures:
    pd.Series()
    pd.DataFrame()
 6. Data Operations:
 7. Indexing & Slicing: df['col'], df.iloc[], df.loc[]
 8. Data Cleaning: .isnull(), .dropna(), .fillna()
 9. Renaming: df.rename()
 10. Filtering: df[df['col'] > value]
 11. Aggregation and Grouping:
     GroupBy: df.groupby('col')
     Aggregation: .sum(), .mean(), .count()

 12. Merging and Joining:
      pd.merge(), df.conacat()
 13. File I/O:
     pd.read_csv(), df.to_csv(), pd.read_excel(), df.to_excel()
 14. Time Series:
     Datetime: pd.to_datetime(), .resample()
 15. visualization:
     df.plot() for basic plotting.
 16. Condition Selection:
     And ,or

Task_6
 1. Work on matplotlib and seanorn
 2. Plot various plot with interpretations.


